# Wireshark Filters

Filtros utilizados en laboratorios de analisis 
de trafico de red.

## Filtros por protocolo

### DHCP
dhcp

### DNS
dns

### TCP
tcp

## Filtros especificos utilizados en labs

### Filtrar DNS que contenga un dominio
dns contains "shodan"

### Filtrar TCP por direccion IP
tcp && ip.addr == 104.18.12.238

## Protocolos analizados

| Protocolo | Descripcion |
|-----------|-------------|
| DHCP | Asignacion dinamica de IPs |
| DNS | Resolucion de nombres de dominio |
| TCP | Control de transmision - Handshake |
| TLSv1.3 | Trafico cifrado HTTPS |

## Archivos pcap utilizados

| Archivo | Contenido |
|---------|-----------|
| DHCPEx.pcapng | Trafico DHCP - Discover, Offer, Request, ACK |
| Traffic_Sample.pcapng | Trafico DNS, TCP y TLS hacia shodan.io |

## Origen
Bootcamp SOC Analyst - ComunidadDOJO
