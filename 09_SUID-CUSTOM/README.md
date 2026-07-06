# Laboratorio SUID-CUSTOM - PrivilegeEscalation vía PATH Hijacking
Este repositorio contiene el writeup del laboratorio **SUID-CUSTO** de WHOAMI-Labs, donde se explota un binario con el bit **SUID** configurado de dforma insegura.
La vulnerabilidad permite realizar un **PATH Hijacking** para obtener una shell con privilegios de **root**.

---

## Objetivo del laboratorio 
Escalar privilegios explotando el binario SUID ´/usr/local/bin/backup´, el cual ejecuta comandos sin utilizar rutas absolutas, permitiendo manipular la variable ´PATH´

---

## Reconocimeinto inicial 
Conexión al laboratorio

´´´bash
ssh hacker@172.17.0.2
´´´

## Encotramos un programa especial (SUID)
## Analizamos qué hacía 
## Vimos su vulnerabilidad (PATH HIJACKING)
## Creamos un programa falso para explotarla
## Obtuvimos acceso root y encontramos la flag 
