<b>NOTE:</b>

I'M NOT THE OWNER OF THIS PROJECT AND ALL THE WORK BEHIND THIS ROM IS THANKS TO THE SWITCHROOT ORGANIZATION.

THESE BUILDS ARE PUBLISHED WITHOUT ANY GUARANTEE OR SUPPORT, ARE JUST PERSONAL BUILDS COMPILED BY ME THANKS TO THE SOURCE CODE AVAILABLE AT <b><a href="https://gitlab.com/switchroot/android/android_device_nvidia_t210-common/-/tree/lineage-17.1">SWITCHROOT GITLAB REPOSITORY</b></a>
<br/>
<br/>


# LineageOS-Switch
<img src="https://github.com/daviiid99/Lineageos-17.1-T210-Switch-/blob/main/qbuilds.png">
Android 8.x, 9.x and 10.x builds for Nintendo Switch based on the open-source project LineageOS
<br/>

All the builds in this repository were compiled using the official <a href="https://github.com/LineageOS/android">LineageOS</a> and <a href="https://gitlab.com/switchroot/android">Switchroot</a> sources

## Versiones soportadas

| LineageOS           | Releases                                   |  
| ------------------- | -------------------------------------------
| LineageOS 15.1      |  Download/Descargar|
| LineageOS 16.0      |  Download/Descargar
| LineageOS 17.1      |  <a href="https://github.com/daviiid99/LineageOS-Switch-T210/releases/tag/20201226">Download/Descargar</a>



# How to flash this ROM (English Instructions)

1.- Grab the latest update from <a href="https://github.com/daviiid99/Lineageos-17.1-T210-Switch/releases">Releases</a>
  (Download both files, the <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> and the <b>Hekate SD.zip</b>)
  
2.- Extract the <b>Hekate SD.zip</b> contents into your SD Card root and copy the <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> file in the root as well.
  
3.- Launch Hekate on your non-mariko Switch and go to <b>Tools> Arch bit • RCM • Touch • Partitions> Partition SD Card</b>

4.- Use the slider to give <b>Android</b> some space, then select <b>Next Step</b> to start the repartition process.
  
5.- Select the <b>Flash Android</b> option, when finished presh <b>Continue</b>
  
6.- When prompted to boot into TWRP, select <b>Continue</b>
  
7.- In TWRP, select the <b> Flash </b> option , then <b>Select Storage</b> and choose the <b>Micro SD card</b> option and select the <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> file from root directory
  
8.- Wait for the flash process to end, then return and select <b>Reboot> System</b>
 
9.- Your Switch will boot into LineageOS 17.x system
 
NOTE¹: Optionally you can flash Magisk and GApps packages from TWRP, <b><a href="https://opengapps.org/">OpenGApps</a>/<a href="https://sourceforge.net/projects/nikgapps/files/Releases/NikGapps-Q/">NikGApps</a> </b> and <b><a href="https://github.com/topjohnwu/Magisk/releases">Magisk Stable release</a></b> are the recommended options.

NOTE²: Switch AArch is ARM64-v8a, choose ARM64 GApps package

# Cómo instalar esta ROM (Spanish Instructions)

1.- Descarga la última actualización de <a href="https://github.com/daviiid99/Lineageos-17.1-T210-Switch/releases">Releases</a>
  (Descarga ambos archivos, el <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> y el <b>Hekate SD.zip</b>)
  
2.- Extrae el archivo <b>Hekate SD.zip</b> en la raíz de tu SD y copia el archivo <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> también en la raíz.
  
3.- Ejecuta Hekate en tu Switch(no Mariko) y selecciona las opciones siguientes <b>Tools> Arch bit • RCM • Touch • Partitions> Partition SD Card</b>

4.- Use el slider para dar a <b>Android</b> espacio en su partición, y selecciona <b>Next Step</b> para reparticionar la SD.
  
5.- Selecciona la opción <b>Flash Android</b>, cuando finalize pulsa <b>Continue</b>
  
6.- Cuando te pregunte sobre iniciar TWRP, selecciona <b>Continue</b>
  
7.- En TWRP, selecciona la opción <b> Flash </b>, después <b>Select Storage</b> y elige <b>Micro SD card</b> y selecciona el archivo de la rom, el <b>lineage-17.1-[date]-icosa-daviiid99.zip</b> de la raíz.
  
8.- Espera a que termine de instalarse la ROM, cuando finalice retrocede al menú principal y selecciona <b>Reboot> System</b>
 
8.- Tu Nintendo Switch iniciará LineageOS sin problemas.
 
NOTA¹: Opcionalmente puedes instalar Magisk y un paquete de GApps desde TWRP, <b><a href="https://opengapps.org/">OpenGApps</a>/<a href="https://sourceforge.net/projects/nikgapps/files/Releases/NikGapps-Q/">NikGApps</a> </b> y <b><a href="https://github.com/topjohnwu/Magisk/releases">Magisk Estable</a></b> son las opciones recomendadas.

NOTA²: La arquitectura de Switch es ARM64-v8a, selecciona ARM64 al descargar un paquete de GApps.
