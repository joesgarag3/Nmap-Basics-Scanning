# Nmap-Basics-Scanning
Basic commands for a successful Nmap network scanning

## Español : 
Este proyecto demuestra los principios para un escaneo de red exitoso utilizando **Nmap** dentro de un ambiente controlado en un entorno virtual. En el se ejecutara diferentes comandos los cuales demuestran habilidades necesarias para escaneo de host, descubrir estado de puertos, determinar servicios y identificar sistemas operativos.

**Resultados de aprendizaje :**
 * Configuración de laboratirio : Configuración de red virtual aislada en Kali Linux y Windows10 dentro de VirtualBox.
 * Descubrimiento de Hosts : Identificación de hosts en una red mediante escaneos ping.
 * Escaneo de puertos : Ejecución de sondeos TCP SYN enviando paquetes sigilosos para descubrir puertos abiertos.
 * Detección de servicios y versiones : Identificación de aplicaciones y sus versiones que son ejecutadas en puertos abiertos.
 * Detección de sistema operativo : Determinación del SO usado.
 * Escaneo puertos principales : Escaneo de puertos más usados.
 * Documentacion : Explicaciónes claras, ejemplos de comandos, respuestas y evidencia basada en capturas de pantalla.

**Herramientas usadas**
 * Nmap : Herramienta de escaneo y seguridad.
 * Kali Linux : Atacante dentro de un entorno virtual controlado.
 * Windows 10 : Objetivo dentro de un entorno virtual controlado.
 * VirtualBox : Software de virtualización.

**Comandos Nmap :**

  [ nmap -sS <HOST> -oN SYN_scan.txt ]

 *txt* = 
 *screenshot* = 

**-sS :** realiza un escaneo de puertos bajo el protocolo TCP, envía paquetes SYN y es considerado rápido y discreto ya que no completa la conexion TCP. Los resultados de puertos a esperar son:
  * SYN-ACK (abierto)
  * RST (cerrado)
  * No responce / ICMP error (filtrado)
**-oN :** guarda la salida del escaneo en un archivo *.txt*

## English: 
This project demonstrates the principles of successful network scanning using Nmap within a controlled, virtual environment. It will execute various commands that demonstrate the skills necessary for host scanning, discover port status, determine service, and identify operating system.

**Learning Outcomes:**
* Lab Setup: Isolated virtual network configuration on Kali Linux and Windows 10 within VirtualBox.
* Host Discovery: Hosts scanning on a network using ping scans.
* Port Scanning: Running TCP SYN probes by sending stealth packets to discover open ports.
* Service and Version Detection: Identifying applications and their versions running on open ports.
* OS Detection: Determining the operating system used.
* Main ports scan: Scanning of the most used ports.
* Documentation: Clear explanations, command examples, responses, and screenshot-based evidence.

**Tools Used**
* Nmap: Scanning and security tool.
* Kali Linux: Attacker within a controlled virtual environment.
* Windows 10: Target within a controlled virtual environment.
* VirtualBox: Virtualization software.
  
