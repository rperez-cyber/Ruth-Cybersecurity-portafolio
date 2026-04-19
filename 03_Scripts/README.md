# Nmap Commands

Comandos utilizados en laboratorios practicos 
de reconocimiento activo.

## Escaneo basico de versiones

nmap -sV -p- --open <IP>

Ejemplo:
nmap -sV -p- --open 172.17.0.2

## Escaneo completo con scripts y sistema operativo

sudo nmap -sV -sC -O -p- --open <IP> -oN resultado.txt

Ejemplo:
sudo nmap -sV -sC -O -p- --open 172.17.0.2 -oN resultado_vuln.txt

## Parametros utilizados

| Parametro | Descripcion |
|-----------|-------------|
| -sV | Detecta versiones de servicios |
| -sC | Ejecuta scripts por defecto |
| -O | Detecta sistema operativo |
| -p- | Escanea todos los puertos |
| --open | Muestra solo puertos abiertos |
| -oN | Guarda resultado en archivo .txt |

## Laboratorios donde se aplico

- Lab Transferencia (172.17.0.3)
- Lab Password (172.17.0.2)
- Lab SUID (172.17.0.2)
- Lab Vulnerability Scanning - CVE-2007-2447

## Origen
Curso: Ethical Hacking 2026 - Edutek
Instructor: Hector Camacho
Plataforma: whoami-labs.com
