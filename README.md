# Guía del Usuario de OpenGD77

## Para OpenGD77 / OpenGD77S / OpenDM1801* / OpenDM1801A* / OpenRD5R / MD-9600 (RT-90) / MD-UV380 (RT-3S) / MD-UV390 / DM-1701 / RT-84

Para obtener la información más reciente y participar en discusiones, visita el foro de desarrollo y comunidad en <https://opengd77.com>

# El firmware TAMPOCO es compatible con la nueva versión 2022 del Baofeng DM-1801 ni con el nuevo DM-1801A #

## Tabla de Contenidos

* [Introducción](#introducción)
  * [Enlaces de descarga y otros recursos](#enlaces-de-descarga-y-otros-recursos)
* [Instalación](#instalación)
* [Transferencia de datos a la radio](#transferencia-de-datos-a-la-radio)
* [Compatibilidad con codeplugs](#compatibilidad-con-codeplugs)
* [Diferencias entre las radios compatibles](#diferencias-entre-las-radios-compatibles)
* [Pantallas principales (modos VFO y Canal)](#pantallas-principales-modos-vfo-y-canal)
  * [Cambio entre modo FM y DMR](#cambio-entre-modo-fm-y-dmr)
  * [Cambio de timeslot en modo DMR](#cambio-de-timeslot-en-modo-dmr)
  * [Configuración automática de Talkgroup/PrivateCall y Timeslot en modo DMR](#configuración-automática-de-talkgroupprivatecall-y-timeslot-en-modo-dmr)
  * [Cambio de ancho de banda en modo FM](#cambio-de-ancho-de-banda-en-modo-fm)
  * [Control de potencia de transmisión](#control-de-potencia-de-transmisión)
  * [Gráfico de intensidad de señal](#gráfico-de-intensidad-de-señal)
  * [Funcionalidades específicas de la pantalla de Canal](#funcionalidades-específicas-de-la-pantalla-de-canal)
    * [Cambio de canales dentro de la zona actual](#cambio-de-canales-dentro-de-la-zona-actual)
    * [Cambio de zonas](#cambio-de-zonas)
    * [Visualización de la frecuencia del canal](#visualización-de-la-frecuencia-del-canal)
    * [Visualización de información específica de FM](#visualización-de-información-específica-de-fm)
    * [Operación inversa de repetidor](#operación-inversa-de-repetidor)
  * [Menú rápido de Canal](#menú-rápido-de-canal)
    * [Copiar un canal al VFO](#copiar-un-canal-al-vfo)
    * [Leer el VFO en el canal actual](#leer-el-vfo-en-el-canal-actual)
    * [Filtros (Canal)](#filtros-canal)
    * [Talkaround](#talkaround)
    * [Roaming](#roaming)
  * [Menú rápido de VFO](#menú-rápido-de-vfo)
    * [Selección de VFO A o B](#selección-de-vfo-a-o-b)
    * [Intercambio de frecuencias TX y RX](#intercambio-de-frecuencias-tx-y-rx)
    * [Copiar la frecuencia RX a TX](#copiar-la-frecuencia-rx-a-tx)
    * [Copiar la frecuencia TX a RX](#copiar-la-frecuencia-tx-a-rx)
    * [Filtros (VFO)](#filtros-vfo)
    * [VFO a Nuevo Canal](#vfo-a-nuevo-canal)
    * [Escaneo de tonos CTCSS o DCS en FM](#escaneo-de-tonos-ctcss-o-dcs-en-fm)
    * [Dual Watch](#dual-watch)
    * [Freq Bind](#freq-bind)
  * [Funcionalidad específica de DMR (pantallas VFO y Canal)](#funcionalidad-específica-de-dmr-pantallas-vfo-y-canal)
    * [Selección de Timeslot](#selección-de-timeslot)
    * [Visualización de ID DMR, indicativo y nombre](#visualización-de-id-dmr-indicativo-y-nombre)
    * [Visualización de alias del interlocutor](#visualización-de-alias-del-interlocutor)
    * [Selección de Talkgroup desde la lista TG](#selección-de-talkgroup-desde-la-lista-tg)
    * [Asignación de Timeslot a TalkGroup de Contacto Digital](#asignación-de-timeslot-a-talkgroup-de-contacto-digital)
    * [TalkGroup mostrado en inverso](#talkgroup-mostrado-en-inverso)
    * [Entrada manual de número de TalkGroup](#entrada-manual-de-número-de-talkgroup)
    * [Entrada de número de Llamada Privada](#entrada-de-número-de-llamada-privada)
    * [Selección de Contacto Digital](#selección-de-contacto-digital)
    * [Entrada de número de ID DMR de la estación](#entrada-de-número-de-id-dmr-de-la-estación)
* [Modo Monitor](#modo-monitor)
* [Transmisión](#transmisión)
  * [Aviso de tiempo de transmisión](#aviso-de-tiempo-de-transmisión)
  * [TOT](#tot)
* [Escaneo](#escaneo)
  * [Escaneo de canales](#escaneo-de-canales)
  * [Escaneo en VFO](#escaneo-en-vfo)

---

### Introducción

Esta guía del usuario está en constante actualización, al igual que el firmware.

El objetivo del proyecto es desarrollar un firmware completamente funcional y de código abierto que reemplace totalmente el firmware de fábrica. Este firmware está diseñado específicamente para su uso en **radioaficionados**, e incorpora funciones que no están disponibles en el firmware oficial.

