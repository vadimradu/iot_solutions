
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
  *  * Preferabile un singur strat
  * Respectarea conexiunilor pentru header

  Nu prezinta interes partile de GPIO/PWM/I2C/DBG/LCD ...
  Trebuie doar conectat modulul SIM900A la un conector de SIM (preferabil microSIM)
  Trebuie conectate firele pentru comunicatii seriale (RXD, TXD) la un header

###BOM  
  [1]: http://simcomm2m.com/En/module/detail.aspx?id=71
