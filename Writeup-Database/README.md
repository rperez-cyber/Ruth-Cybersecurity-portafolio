## Database -whoami-labs
Laboratorio de la plataforma **whoami-labs.com** centrado en una aplicación WordPress mal configurada. El objetivo era identificar servicios expuestos, abusar de configuraciones
débiles y escalar privilegios para capturar la flag.

## objetivo
IP interna del laboratorio: ´172.17.0.2´
Servicios expuestos: FTP (21), SSH (22), HTTP (8080)

## Indice de laboratorio

- **Máquina**: Database
- **Plataforma**: Whoami-Labs.com
- **IP Objetivo**: 172.17.0.2
- **Sistema Operativo**: Kali Linux
- **Dificultad**: Media
- **Fecha**: 18/10/2026
- **Técnicas**: WordPress RCE, SUID abuse

## Técnicas utilizada
- Reconocimiento con Nmap
- Fuga de información en código fuente HTML
- Enumeración de directorios con Feroxbuster
- Explotación del instalador de WordPress expuesto (´install.php´)
- RCE vía editor de temas/plugins de WordPress
- Reverse shell con Netcat
- Escalación de privilegios por abuso de binarios SUID (´date -f´)

    ## Herramientas 
  
- Nmap: escaneo de puertos y servicios.
- Feroxbuster: Fuzzing de directorios.
- Netcat: Listener para reverse shell.
- Navegar / viem-source, Enumeración manual.


## Diclaimer

Laboratorio realizado en entorno autorizado y controlado de whoami-labs con fines educativos.

## Writeup

La explicación detallada del proceso se encuentran en el PDF incluido en este.

## Autora

**Ruth Pérez**
