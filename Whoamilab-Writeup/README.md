## Whoamilab - FTP/SSH Brute Force & Privilege Escalation

## Writeup de un laboratorio de pentesting desplegado en [whoami-labs.com], que simula un entorno corporativo vulnerable con servicios FTP y SSH mal configurado, resultando en una escalada de privilegios completa hasta "root".

## Introcucción 
Este laboratorio consiste en una máquina vulnerable accesible desde kali linux en red interna.El objetivo es realizar un pentest completo siguiendo la metodología estándar.
**Reconocimiento - Enumeración - Explotación - Escalada de privilegios - Captura de flag** 

## Información 

- **Máquina**: whoamilab
- **Plataforma**: Whoami-Labs.com
- **IP Objetivo**: 172.17.0.2
- **Sistema Operativo**: Kali Linux
- **Dificultad**: Media
- **Servicio expuestos**: FTP (21). SSH (22)
- **Fecha**: 06/09/2026

  ## Herramientas utilizadas
  - Nmap : Escaneo de puertos y servicios
  - ftp (cliente): Enumeración y descarga de archivos vía FTP
  - Hydra : Ataque de fuerza bruta
  - Rockyou.txt : Diccionario de contraseñas
  - ssh/su/sudo : Acceso remoto y escalada de privilegios
 
    ## Writeup
    El análisis completo de este laboratorio se encuentra en el PDF anexado a este README.
 
  - ## Disclaimer
  - Este writeup documenta la resolucón de un laboratorio controlado de la plataforma WHOAMI-LABS.COM, diseñado especificamente con fines educativos. Las técnicas aquí descritas no deben aplicarse
  - contra sistemas sin autorización explícita.
 
  - ## Autora
  - **Ruth Pérez**
 
    
