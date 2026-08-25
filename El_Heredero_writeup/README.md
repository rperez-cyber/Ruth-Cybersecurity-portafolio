# El Heredero - Whoami-Labs

 
## Herramientas

- Nmap
- Curl
- Feroxbuster
- SSH
- getcap

- ## Resumen de la cadena de ataque
- 
- Enumeración de puertos, SSH y servidor HTTP expuestos.
- Enumeración web listado de archivos internos accesible sin autenticación.
- Archivo de histórico de bash filtrado revala ruta de una clave SSH privada olvidada.
- Descarga de la clave privada, acceso SSH como usuario student.
- Enumeración de privilegios, binario con capability cap_chown mal configurada.
- Abuso de cap_chown, apropiación directa del archivo de la flag de **root**, sin necesidad de shell de root.

## Writeup

El análisis completo del laboratorio se encuentra en **Writeup-Transferencia.pdf**.

## Disclaimer

Este laboratorio fue realizado exclusivamente con fines educativos en la plataforma  **Whoami-Labs**.

## Realizado **Ruth Pérez**

---
**Autora:** Ruth Pérez
