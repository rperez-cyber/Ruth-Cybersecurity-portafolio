## Laboratorio de whoami-labs.com enfocado en enumeración web y escalada de privilegios.


## Información General
- **Plataforma** : whoami-labs.com
- **Dificutad** : Fácil
- **IP** : 172.17.0.2
- **Categoría** : Enumeración web, escalada de privilegios

  ## Herramientas Utilizadas
  - Nmap
  - Navegador web (inspección de códigob fuente)
  - SSH / ssh-keygen
  - sudo -l
  - vim (GTFOBins)
 
  ## Habilidades practicadas
  - Escaneo de puertos y servicios con Nmap.
  - Análisis de código fuente HTML.
  - Identificación de credenciales expuestas.
  - Conexión y gestión de claves SSH
  - Enumeración de privilegios en Linux (SUID, sudo).
  - Escalada de privilegios mediante GTGOBins.
 
    ## Resultado
    Se obtuvo acceso inicia mediante credenciales filtradas en el código fuente y se escaló a root explotando una mala configuración de sudo sobre vim.

    ## Disclaimer
    Este laboratorio es realizados con fines educativos

    ## Writeup Completo
    Ver writeup detallado para el proceso paso a paso en el PDF, incluido en el repositorio.

    ## Autora
    **Ruth Pérez**
