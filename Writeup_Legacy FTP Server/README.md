## Laboratorio Legacy FTP Server

Este laboratorio simula un servidor de hosting (SecureServers Inc) que expone un sitio web corporativo y un servicio FTP heredado (ProFTPD 1.3.5a). 
Las credenciales del FTP quedan filtradas en comentarios HTML del propio sitio web, y una vez dentro del FTP, el directorio raíz no está correctamente enjaulado (chroot), lo que permite escapar del directorio /svr/ftp hacia el sistema de archivos real y llegar hasta /root, donde se encuentra la flag.

## Detalle

- **Máquina**: Legacy FTP Server
- **Plataforma**: Whoami-Labs.com
- **IP Objetivo**: 172.17.0.2
- **Sistema Operativo**: Kali Linux
- **Dificultad**: Fácil
- **Fecha**: 20/10/2026

## Herramientas utilizadas

- **Nmap**: descubrimientos de puertos y servicios 
- **Feroxbuster**: fuzzing de directorios y archivos web
- **Navegador web (view-source)**: revisión de código fuente HTML
- **Cliente FTP (línea de comandos)**: conexión, enumeración y axfiltración de archivos

## DISCLAIMER

Este laboratorio esta realizado con fines educativos


## Autora
**Ruth Pérez**
