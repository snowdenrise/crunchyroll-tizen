# Crunchyroll for TIZEN [![PayPal donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/donate/?hosted_button_id=SLLWEKD6QD5UJ)

## Description:

**INFO: Application is incomplete, some features are missing that will be added later.**

## TODO Features:

#### Complete
- [x] Auth workflow
- [x] Home screen
- [x] Details screen
- [x] Episodes screen
- [x] Video player
- [x] Menu options screen
- [x] Search element
- [x] Auto next episode
- [x] History screen and workflow
- [x] Change audio and subtitles language inside player
- [x] Settings screen
- [x] Browse elements by categories

#### In progress
- [ ] My list screen and workflow
- [ ] WebOS compatibility

#### Pending
- [ ] Migrate to react

## Captures:
![layouts.gif](https://raw.githubusercontent.com/jhassan8/crunchyroll-tizen/master/layouts.gif)

## [Installation with Installer (Recommended)](https://github.com/jhassan8/crunchyroll-tizen/blob/master/.github/GUIDES/INSTALL.md)

## Installation with IDE

1. Install [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download)
2. In Package Manager install "Extension SDK" -> "TV extension <version>"
3. Clone repository ```git clone https://github.com/jhassan8/crunchyroll-tizen```
4. Open project ("File" -> "Open Project From File System" -> "Directory") and select project folder
5. in tv open [developer mode](https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html)
    - Open Samsung Apps
    - Press buttons 1, 2, 3, 4, 5
    - Enable developer Mode
    - Enter IP address PC with tizen studio
6. Open "Device manager" -> ("Remote Device" -> "Scan") and Select Your Device
7. Right click on the project ("Run as" -> "Tizen Web Application". (if the option does not appear, follow the next steps)
    - Right click on the project
    - Configure
    - Convert To Tizen Project
8. The app opens on the TV and will be installed.

## Installation with NPM

#### required: npm, configure device (developer mode, "on" device in "device manager")
#### veresions: online (auto-update use cdn), offline (no auto-update)

1. Set tizen var
    - Linux: ```export PATH=$PATH:<your_tizen_path>/tizen-studio/tools/ide/bin```
    - Windows: ```set PATH=%PATH%;<your_tizen_path>/tizen-studio/tools/ide/bin```
2. Install build dependencies: ```npm install```
3. In project folder run:
    - online: ```npm run start-tv-online --tv=<name_of_tv_device_manager>```
    - offline: ```npm run start-tv --tv=<name_of_tv_device_manager>```


# VERSIÓN en ESPAÑOL (Versión en español)

# Crunchyroll para TIZEN (Televisores Samsung) [![Donar a través de PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/donate/?hosted_button_id=SLLWEKD6QD5UJ)

## Descripción:

**INFO: La aplicación está incompleta, algunas funciones faltan y se agregarán más tarde.**

## Características PENDIENTES:

#### Completas
- [x] Flujo de autenticación
- [x] Pantalla de inicio
- [x] Pantalla de detalles
- [x] Pantalla de episodios
- [x] Reproductor de video
- [x] Pantalla de opciones del menú
- [x] Elemento de búsqueda
- [x] Reproducción automática del siguiente episodio
- [x] Pantalla y flujo de historial
- [x] Cambiar idioma de audio y subtítulos dentro del reproductor
- [x] Pantalla de configuración
- [x] Navegar elementos por categorías

#### En progreso
- [ ] Pantalla y flujo de "Mi lista"
- [ ] Compatibilidad con WebOS

#### Pendientes
- [ ] Migrar a react

## Capturas:
![layouts.gif](https://raw.githubusercontent.com/jhassan8/crunchyroll-tizen/master/layouts.gif)

## [Instalación con instalador (Recomendado)](https://github.com/jhassan8/crunchyroll-tizen/blob/master/.github/GUIDES/INSTALL.md)

## Instalación con IDE

1. Instalar [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download)
2. En el Administrador de Paquetes (Package Manager), instalar "Extension SDK" -> "TV Extension <versión>"
3. Clonar el repositorio ```git clone https://github.com/jhassan8/crunchyroll-tizen```
4. Abrir el proyecto ("Archivo" -> "Open Project From File System" -> "Directory") y seleccionar la carpeta del proyecto
5. En la TV, activar el [modo desarrollador](https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html)
    - Abrir Samsung Apps
    - Presionar los botones 1, 2, 3, 4, 5
    - Activar el modo desarrollador
    - -  (En caso de no funcionar, debe usar la aplicacion SmartThings para ingresar estos numeros)
    - Ingresar la dirección IP de la PC con Tizen Studio
6. Abrir "Device manager" -> ("Remote Device" -> "Scan") y seleccionar su dispositivo
7. Hacer clic derecho en el proyecto ("Run as" -> "Tizen Web Application". (si la opción no aparece, seguir los siguientes pasos)
    - Hacer clic derecho en el proyecto
    - Configurar
    - Convertir a Proyecto Tizen
8. La aplicación se abrirá en la TV y se instalará.

## Instalación con NPM

#### Requerido: npm, configurar el dispositivo (modo desarrollador, "encendido" en "gestor de dispositivos")
#### Versiones: en línea (actualización automática mediante cdn), fuera de línea (sin actualización automática)

1. Configurar la variable de entorno de Tizen
    - Linux: ```export PATH=$PATH:<tu_ruta_de_tizen>/tizen-studio/tools/ide/bin```
    - Windows: ```set PATH=%PATH%;<tu_ruta_de_tizen>/tizen-studio/tools/ide/bin```
2. Instalar las dependencias de compilación: ```npm install```
3. En la carpeta del proyecto, ejecutar:
    - En línea: ```npm run start-tv-online --tv=<nombre_del_gestor_de_dispositivos_de_tv>```
    - Fuera de línea: ```npm run start-tv --tv=<nombre_del_gestor_de_dispositivos_de_tv>```
