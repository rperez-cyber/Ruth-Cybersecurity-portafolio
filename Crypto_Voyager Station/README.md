## Writeup del laboratorio **Crypto Voyager Station**

Este laboratorio esta centrado en Enumeración de Servicios, Acceso Inicial por SSH y Escalada de Privilegios mediante un binario SUID.

## Información 

- **Máquina**: Crypto Voyager Station
- **Plataforma**: Whoami-Labs.com
- **IP Objetivo**: 172.17.0.2
- **Sistema Operativo**: Linux
- **Dificultad**: Media
- **Fecha**: 06/10/2026

  ## Herramientas utilizadas
  
- Nmap: escaneo de puertos y servicios.
- Navegador web: inspección de la aplicación y su código fuente.
- Base64: decodificación de la contraseña y lectura de la flag.
- SSH/OpenSSH: acceso remoto a la máquina.
- ssh-keygen: eliminación de la clave antigua del host.
- find: búsqueda de binarios con permisos SUID.

## Explicación de parámetros

-p- :            **Escaneo de los 65535 puertos TCP**
-sV :            **Deteción de versiones**.
-sC :            **Scripts básicos NSE**
-sS :            **SYN Scan**.
-Pn :            **Omitir el descubrimiento inicial del host**.
--min-rate=5000: **Aumenta la velocidad del escaneo**.
-oN regla.txt :  **Guarda la salida**. 

## Writeup
 La explicación detallada del proceso se encuentran en el PDF incluido en este .

## Diclaimer 
Laboratorio educativo. Realiza pruebas únicamente en sistemas propios o con autorización.

## Autora 
**Ruth Pérez**
