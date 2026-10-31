## Nombre del Laboratorio
**SUIDX**


## Descripción
Laboratorio de pentesting enfocado en escalada de prívilegios en Linux mediante binarios SUID mal configurados. Forma parte de la plataforma **whoami-labs**

## Objetivo
Obtener acceso root en la máquina víctima (172.17.0.2) y capturar la flag ubicada en /root/flag.txt.


## Herramientas utilizada
- nmap
- feroxbuster
- hydra
- ssh
- GTFOBins

 ## Resumen rápidos de pasos
  
- Escaneo comppleto de puertos con **nmap**.
- Enumeración de rutas web en el puerto 8080 con **feroxbuster**.
- Descubrimiento de credeciales SSH parciales en la ruta **/user/**.
- Ataque de diccionario sobre SSH CON **hydra** y **rockyou.txt**.
- Conexión SSH como usuario **hacker**.
- Enumeración de binarios SUID (find / -perm -4000 -type f).
- Explotación de **find** con SUID (técnica documentada en GTFOBins).
- Escalada a root y captura de la flag.
 
## Referecia

Ver el writeup completo con el detalle paso a paso en el PDF adjutado a este REAME

## Autora

**Ruth Pérez**
    
