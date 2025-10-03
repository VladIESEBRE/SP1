---
layout: default
title: "Sprint 1: Instal·lació i Configuració Inicial"
---
<details>
  <summary>Virtualització i instal·lació del S.O Ubuntu</summary>

 ## **"Virtualització i instal·lació del S.O Ubuntu"**

### **Instalación y particionamiento Ubuntu**

 # Paso 1
 &nbsp;&nbsp;- En esta foto podemos elegir la memoria RAM y el número de cpus que se van a utilizar en la instalación de Ubuntu en una máquina virtual.
  
 <img width="859" height="478" alt="Captura de pantalla de 2025-09-26 12-45-05" src="https://github.com/user-attachments/assets/9a6edb8b-b134-415e-bc94-46d7e0bde50c" />

  # Paso 2
&nbsp;&nbsp;- Aquí podemos elegir la capacidad total que tendrá el disco duro.
 
 <img width="859" height="478" alt="Captura de pantalla de 2025-09-26 12-45-47" src="https://github.com/user-attachments/assets/87922ad6-541d-413c-b3b0-57d8050a26ea" />
 
  # Paso 3
&nbsp;&nbsp;- Aquí podemos ver la pagina inicial de particiones.Con el espacio total indicado por "dev/sda". Podemos empezar la partición manual haciendo click en el botón "Nueva tabla de particiones".

 
<img width="830" height="624" alt="Captura de pantalla de 2025-09-26 12-56-35" src="https://github.com/user-attachments/assets/b4832ebe-b028-4432-a813-170f35c93eec" />

  # Paso 4
&nbsp;&nbsp;- Seleccionamos cuanto espacio queremos utilizar para la partición.

<img width="830" height="624" alt="Captura de pantalla de 2025-09-26 12-57-03" src="https://github.com/user-attachments/assets/d7e58052-dad4-4dbd-862c-2444124aee33" />

  # Paso 5
&nbsp;&nbsp; -Elegimos el punto de montaje ,sda1(/)(es el espeacio reservado para el S.O).Reservamos 20GB en este caso.

<img width="906" height="718" alt="Captura de pantalla de 2025-09-26 12-59-07" src="https://github.com/user-attachments/assets/84732e9b-9593-4b10-b9f1-a03fea89453f" />

  # Paso 6
&nbsp;&nbsp;- Seleccionamos cuanto espacio queremos utilizar para la partición.

<img width="830" height="624" alt="Captura de pantalla de 2025-09-26 12-57-03" src="https://github.com/user-attachments/assets/d7e58052-dad4-4dbd-862c-2444124aee33" />

  # Paso 7
&nbsp;&nbsp; -Damos click a "Utilizar como: Sistema de ficheros ext4 transaccional ,ya que ext4 es el estándar para Linux


<img width="906" height="718" alt="Captura de pantalla de 2025-09-26 12-58-24" src="https://github.com/user-attachments/assets/cbd3f8d0-9d5e-44ce-b982-7573a160a590" />

  # Paso 8
 &nbsp;&nbsp; -Después, seleccionamos "espacio libre" y damos click al botón "+" para crear nuevas particiones: sda2 (/home) (el espacio reservado para los documentos de usuario, 10GB en este caso) 

<img width="906" height="718" alt="Captura de pantalla de 2025-09-26 13-01-56" src="https://github.com/user-attachments/assets/3a31622e-08a1-4f7d-a093-4979d3c713bd" />

  # Paso 9
 
 &nbsp;&nbsp; -Seguimos con el mismo proceso de antes para crear: 
 - sda3(/boot) (Archivos de arranque (kernel)(Facilita acualizaciónes y multi-boot) *5GB*
 - sda4(swap) (Memoria virtual; útil si la RAM es limitada(elegimos "Área de intercambio",en la opción "Utilizar como") *4GB*
 - sda5(efi) (contiene los archivos de arranque necesarios para que el sistema operativo se inicie en un sistema con UEFI(elegimos "FAT32",en la opción "Utilizar como".)) *1GB* 
 - sda6(biosgrub)(área reservada para BIOS(elegimos "Área reservada de la BIOS de arranque" en la opción "Utilizar como")) *98MB*

<img width="906" height="718" alt="Captura de pantalla de 2025-09-26 13-07-54" src="https://github.com/user-attachments/assets/b62dbb33-45c5-4ef9-8386-bfe512526977" />

 </details>

 <details>
  <summary>Llicenciament</summary>

   ## Llicenciament

#### **Licencia de Ubuntu**
&nbsp;&nbsp;Ubuntu, no utiliza una sola licencia, sino que es un sistema operativo compuesto por miles de paquetes de software, cada uno con su propia licencia de código abierto. Sin embargo, la licencia predominante es la GNU General Public License (GPL), específicamente versiones como GPL-2.0 y GPL-3.0, junto con la GNU Lesser General Public License (LGPL) para bibliotecas. Esto permite que los usuarios modifiquen y redistribuyan el software libremente.

#### **Por qué hay tantas licencias diferentes en Ubuntu?**
&nbsp;&nbsp;Hay tantas licencias diferentes porque el mundo del software libre y de código abierto ha evolucionado durante décadas con necesidades variadas según los creadores y proyectos. Ubuntu, al basarse en Debian y en el ecosistema Linux, incorpora software de múltiples fuentes, lo que genera esta diversidad.

<img width="266" height="59" alt="Captura de pantalla de 2025-09-26 11-59-32" src="https://github.com/user-attachments/assets/5c421019-47b9-472a-a5c6-d3e65fbb23c0" />

&nbsp;&nbsp;En este proyecto utilizo la licencia Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) de Creativer Commons.
 
 - La © indica que la obra está protegida por derechos de autor.
 - Attribution (BY),simbolizado por el icono de la persona ,requiere que se dé crédito al autor original.
 - NoDerivatives (ND),sibolizado por "=", prohíbe modificar o crear obras derivadas de la original.
 - 4.0 International quiere decir que es la versión más reciente de esta licencia, aplicable globalmente con términos estandarizados.
    </details>
 
 <details>
  <summary>Instal·lacións duals i Gestors d'arrancada</summary>

## Instal·lacións duals i Gestors d'arrancada
</details>
 
 <details>
  <summary>Particions i punts de restauració</summary>

## Particions i punts de restauració
</details>
 <details>
  <summary>Configuració basica de la xarxa</summary>
      

## Configuració basica de la xarxa
</details>
 <details>
  <summary>Comandes generals i instal·lació d'aplicacions</summary>
     

## Comandes generals i instal·lació d'aplicacions
</details>


