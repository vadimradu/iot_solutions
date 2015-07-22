
Modul IoT cu sim-card
-----
###Descriere
 Modulul este construit in jurul unui [integrat de la SIMCOM][1] si este realizat intr-un format modular ce permite adaugarea lui intr-un sistem mai complex.

###Referinte
In folderul docs se gasesc doua documente de interes de la SIMCOM:
* [Design Reference](/docs/AN_SIM900 Reference Design Guide_V1.02.pdf)
* [PCB design](/docs/SIM900_Two-layer PCB RF Design_Application Note_V1.02.pdf)

Pe baza acestora trebuie realizat un layout de interfatare cu un modul host

###Obiective
  * Alegerea componentelor, vezi partea cu [BOM](README.md#BOM)
  * Completarea layoutului
    * Preferabil un singur strat
    * Numar mic de componente
    * Preferabil smd 0805 ca footprint pentru discrete
  * Respectarea conexiunilor pentru header
    * Standardul pentru header este inca in lucru
  * Footprinturi pentru componentele nonstandard

###Generalitati
  Nu prezinta interes partile de GPIO/PWM/I2C/DBG/LCD ...
  Trebuie doar conectat modulul SIM900A la un conector de SIM (preferabil microSIM)
  Trebuie conectate firele pentru comunicatii seriale (RXD, TXD) la un header

###BOM  
* Modul SIM900
* 2x Led 0805
* 2x Rez 0805
* Conector SIM, doua propuneri: [miniSIM][2] sau [microSIM][3]
* de completat...

  [1]: http://simcomm2m.com/En/module/detail.aspx?id=71
  [2]: http://ro.farnell.com/molex/78727-0001/connector-sim-socket-6pos/dp/2426393
  [3]: http://ro.farnell.com/multicomp/simmp-00601b000-g/connector-mini-sim-6pin/dp/2211802
