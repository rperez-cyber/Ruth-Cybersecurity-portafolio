
## Nombre del laboratorio
## Brew Portal

## Información 

- **Plataforma:** Whoami-labs.com
- **Laboratorio:** Brew Portal
- **Dificultad:** Fácil
- **Sistema Operativo** Linux
- **Fecha** 16/09/2026
- **Autora** Ruth Pérez

## Herramientas utilizadas
- Nmap
- Feroxbuster
- Navegador web (barra de direcciones y view-source:)
- Curl + base64 (para decodificar el código fuente extraído)

  ## Metodología
  
  - Reconocimiento de puertos
  - enumeración de contenido web
  - exploración manual de la navegación
  - confirmación de LFI vía /etc/passwd
  - extracción del código fuente con php://filter
  - Análisis de la lógica vulnerable
  - enumeración de rutas del sistema hastas localizar la flag.

  ## Resultado
  Se identificó y explotó una vulnerabilidad de Local File Inclusion sin sanitización de rutas en el parámetro page, lo que permitió leer archivos arbitrarios
  del sistema, extraer el código fuente de la aplicación  y finalmente obtener la flag.

  ## **Laboratorio realizado con fines educativos y de práctica en ciberseguridad**
