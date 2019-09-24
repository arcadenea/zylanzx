# zylanzx
Zylan Z7/Z9 card phones (mt6261ma chipset)


Zylan Z7 - Zylan Z9
===================
El chipset del télefono es un mt6261ma (Mediatek). Conectandose por el puerto COM da el siguiente ID (at+cgmr): p399_bw_zylan_f15_lcd1306_v1.0.1 -ver sección comandos AT-


Información del teléfono
========================
ver imei: *#06#


Configuración vía puerto COM
============================
Para configurar el teléfono, conectarlo mediante cable USB y seleccionar la opción de modem COM. Utilizar algún programa de comunicaciones como Minicom 


Comandos AT válidos (incompleto):
=================================
at
ata
atd
ate
ath
at+casp - reproducir sonido
at+cgmm - muestra información del fabricante (devuelve MTK2)
at+cgmr - ver identificación del firmware (devuelve p399_bw_zylan_f15_lcd1306_v1.0.1)
at+egmr=0,7 - leer imei
AT+EGMR=1,7,"123456789123456"
