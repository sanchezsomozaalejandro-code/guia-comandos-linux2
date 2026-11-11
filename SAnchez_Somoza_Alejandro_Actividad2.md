# INDICE
1. [Introducción](#1Introducción)
2. [Requisitos previos](#2Requisitos-previos)
3. [Procedimientos de uso de comandos](#3Procedimiento-de-uso-de-comandos)
4. [Resolución de problemas](#4Resolución-de-problemas)
5. [Comprobación](#5Comprobación)
6. [Referencias](#6Referencias)

------------
## 1. Introducción
El uso de la **linea de comandos en Linux** es fundamental para una administración eficiente del sistema operativo.
La terminal permite ejecutar acciones complejas con gran facilidad
## 2. Requisitos previos
Antes de empezar a usar los comandos asegúrate de cumplir los siguientes requisitos
* Equipo con distribución **Linux** instalada
* Tener acceso a una terminal de comandos activa
* Conocer los conceptos básicos de rutas absolutas y relativas.
## 3. Procedimiento de uso de comandos
A continuación se detallan los pasos y sintaxis para las operaciones más habituales en la terminal
### Navegación por el sistema de archivos
Para moverte entre directorios y ver qué archivos contienen, utiliza las siguientes instrucciones en bloque de código:

```Bash
pwd
ls -l
cd /etc
```
### Gestión de archivos y directorios
Para crear carpetas, copiar archivos o eliminarlos
```Bash
mkdir
cp
rm
```
## 4. Resolución de problemas
Si encuentras dificultades al ejecutar comandos en la terminal, consulta la siguiente tabla de diagnóstico rápido:
|Error|Causa probable|Solución|
|------|------|-------|
|Permission denied|Falta de privilegios de usuario|Anteponer sudo al comando para ejecutarlo como administrador|
|Command not found|El paquete no está instalado|Verificar la ortografía o instalar la herramienta requerida|

## 5. Comprobación
Para verificar el estado de los archivos creados o el espacio en disco disponible,puedes ejecutar comandos de validación rápida 

```Bash
ls -la
df -h
```
## 6. Referencias
*Para profundizar en el uso avanzado de la terminal y consultar manuales detallados de comandos*

--------
[Saber más sobre Linux](https://laptopwithlinux.com/linux-laptops/?msclkid=1c33680a9923102db7ba02f8bec90959)
![Simbolo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS_wY3hirmbTlhHpLzFzwQBdMTPoCTK34GgbjUYQd18Jwk3hwT09WncWFU&s=10)
> Linux ofrece total libertad y control sobre el sistema, pero requiere una gestión rigurosa de permisos y copias de seguridad para garantizar su seguridad.
## Información del proyecto
Esta documentación se ha elaborado utilizando Markdown.
El control de versiones se realiza mediante Git
y el repositorio remoto se encuentra alojado en GitHub.
## Próximas mejoras
# 1. Comandos de **recirecciones y tuberiaas** para encadenar comandos
```Bash
|
>
```
# 2. Comandos de **gestión de permisos y usuarios**
```Bash
chmod
chown
```
# 3. Comandos de **monitorización de procesos y red** (ps, top, ss, ip a).
```Bash
ps
top
ss
```
