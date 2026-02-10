# **Actualizar a Windows 11**
![w](https://github.com/user-attachments/assets/a5a8231f-1d0a-49b9-ba4c-8a0d5e124bea) 

## Ejecución de MediaCreationTool
  Accedemos a la [herramienta](https://github.com/AveYo/MediaCreationTool.bat) facilitada que va a permitir la actualización:
  
  Descargamos el archivo:
  
  Clic en Code -> Download ZIP

  ![1](https://github.com/user-attachments/assets/467eeb74-7f04-4ef5-981d-2ea5dcd06efd)
  
  Una vez descargado, vamos a la carpeta descargas y lo extraemos: 
  
  Clic derecho en Extraer todo... -> Extraer

![](https://github.com/user-attachments/assets/7220c955-c379-4e9b-9587-e724d09a9a56)
  
  Entramos a la carpeta extraída y ejecutamos como administrador:
  
  Clic derecho en MediaCreationTool -> Ejecutar como administrador

  ![](https://github.com/user-attachments/assets/987e7aee-1819-4880-8bb7-85d79271ad06)
  
  Buscamos la versión que queremos instalar y clic en Auto Upgrade.

  ![](https://github.com/user-attachments/assets/01cd8c18-9136-418d-8646-5acdf2768eb8)

## Instalación inicial

Una vez finalizada la instalación, entramos con el usuario admin-mtda y restauramos el 
equipo:

Inicio -> Configuración -> Sistema -> Recuperación -> Restablecer el equipo

![](https://github.com/user-attachments/assets/3717d18a-ac54-4708-a514-04f73b8554a8)

- Una vez restaurado e iniciado, creamos el usuario local “admin-mtda” con contraseña M*tda-78+17

- Elegimos el Navegador predeterminado que tendrá el usuario, preferiblemente Edge

- Agregamos la impresora llamada Ricoh e instalamos los drivers que le correspondan:

Inicio -> Configuración -> Bluetooth y dispositivos -> Impresoras y escáneres -> Agregar dispositivo -> RICOH MP 5055

- Agregamos el antivirus Bitdefender (lo encontramos en la carpeta de red compartida)

Win+R y ejecutamos “\\192.168.0.5\mtda\Tecnologia\Software\Bitdefender\W10”

- Le cambiamos el nombre al dispositivo y le ponemos el que le va a identificar respecto a los otros equipos.

![](https://github.com/user-attachments/assets/3bd11193-3862-44ce-b2cb-3ae35a81da0a)

- Meterlo en el dominio de la empresa:

Configuración -> Grupo de trabajo -> Cambiar -> MTDA.local

- Instalamos las siguientes herramientas:

[7zip](https://7-zip.org/download.html)

[Supremo](https://www.supremocontrol.com/es/descarga-supremo/windows/)

Herramientas -> Opciones

![](https://github.com/user-attachments/assets/a2624d8d-033f-41b8-b306-94cc4bfcd368)

Herramientas -> Seguridad -> Contraseña secundaria

![](https://github.com/user-attachments/assets/d0e6a75c-a663-42c3-aaa1-2c910710f01e)

[OpenOffice](https://www.openoffice.org/es/descargar/)

[Foxit](https://www.foxit.com/es/pdf-reader/)

[SonicWall NetxTender](https://www.sonicwall.com/products/remote-access/vpn-clients)

Server 80.59.97.245:4433

Dominio MTDA

Teams (Microsoft Store)

SGA

Win+R y ejecutamos “\\192.168.0.5\mtda\Varios\SGA_MTDA”

Instalamos el certificado

![](https://github.com/user-attachments/assets/e19200aa-5e7a-44d7-bab7-2366a12f9432)

Seguidamente entramos al link de Versión nueva SGA e instalamos

![](https://github.com/user-attachments/assets/e3572001-dcbe-42fc-9294-3da2f54dd37a)

