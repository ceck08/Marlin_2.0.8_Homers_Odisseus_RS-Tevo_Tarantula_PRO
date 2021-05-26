# Marlin_2.0.8_Homers_Odyssues_RS/Tevo_Tarantula_PRO
Aggiornamento Firmware Marlin Per Tevo Tarantula PRO/Homers Odyssues RS

Non trovavo nulla in rete per aggiornare questa stampante allora mi sono rimboccato le maniche e ho costruito questo firmware per aiutare chi come me ha questo modello di stampante.

#Info Stampante 3D

Scheda Madre : MKS SGen L v1.0
Microcontrollore : LPC1768

#Opzioni Firmware

Aggiunto menu per cambio filamento,
Menu in Italiano,
BLTouch disabilitato (io non ho il sensore ma si puo abilitare nel file configuration.h).

Questi sono i file da sostituire nella cartella dove si trova il file Marlin.ino

--------------------------------------------------------------------------------------------------------------------------------

# Firmware Completo Gia Compilato

Aggiungo il link del firmware gia compilato per fare piu veloce https://bit.ly/3bUI0Tw.

Per effettuare il flash del firmware, prendere il file situato in ".pio/build/LPC1768/firmware.bin" e metterlo in una scheda micro SD.
Dopodiche inserire la micro SD nella stampante e riavviare.
