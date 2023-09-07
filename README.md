# bloqueos
Herramientas para ejercer restricciones sobre usuarios


# README - Instalación y Configuración

Este repositorio contiene archivos y configuraciones necesarios para facilitar la instalación y configuración de bloqueos de parnerts. Siga los siguientes pasos para una instalación exitosa:

## Paso 1: Habilitar Editor de directivas de grupo (gpedit) en Windows 11 Home

Para habilitar el Editor de directivas de grupo (gpedit) en Windows 11 Home, ejecute el archivo `desblock_gpedit.bat` que se encuentra en la siguiente ruta del repositorio:


## Paso 2: Copiar archivos ADMX

Copie todos los archivos ADMX requeridos o deseados desde la carpeta `/Configuration/admx` de este repositorio a la siguiente ubicación en su sistema:

C:\windows\policydefinitions


## Paso 3: Copiar archivos ADML

Copie todos los archivos ADML desde la carpeta `/Configuration/admx/<idioma>` de este repositorio a la carpeta correspondiente en su sistema:

C:\windows\policydefinitions<idioma>


## Paso 4: Ejecutar "blockpass.reg"

En la raíz de este repositorio, encontrará un archivo llamado `blockpass.reg`. Para configurar adecuadamente su sistema, ejecute este archivo en modo administrador. Esto asegurará que el resgistro realice el bloque de almacenamiento de contraseñas de manera automatica.

## Paso 5: Instalar Google Enterprise

Los archivos de instalación para Google Enterprise se encuentran en la carpeta `GoogleChromeEnterpriseBundle64\Installers` de este repositorio. Siga el procedimiento estándar de instalación para Google Enterprise utilizando los archivos proporcionados.

**¡Listo!** Ahora tienes el bloqueo de los parnerts instalado y configurado correctamente en su sistema. Asegúrese de seguir todas las instrucciones detenidamente para garantizar un proceso sin problemas.

## Versiones

### Versión [1.0.0]

- versión funcionando validada con windows 11 utilizando regedit



## Contribuir

Si desea contribuir a este proyecto, siéntase libre de abrir un problema o enviar una solicitud de extracción. Agradecemos sus contribuciones y su ayuda para mejorar.

## Problemas y Soporte

Si encuentra problemas o tiene preguntas relacionadas con la instalación y configuración de bloqueo parnerts, por favor abra un problema en este repositorio. Haremos nuestro mejor esfuerzo para ayudarlo.

## Licencia

Este proyecto está licenciado bajo empredemos MIT. Consulte el archivo [LICENSE.md] para obtener más detalles.



