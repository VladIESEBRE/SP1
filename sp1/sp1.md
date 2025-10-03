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
 # Paso 1
 &nbsp;&nbsp;
<img width="874" height="578" alt="Captura de pantalla de 2025-10-03 11-56-28" src="https://github.com/user-attachments/assets/f02d0b70-215d-4a02-9ea0-ae9ed4d58d7d" />


<img width="874" height="578" alt="Captura de pantalla de 2025-10-03 11-59-31" src="https://github.com/user-attachments/assets/1424ef9b-ad47-49f1-b8d1-c4058580b0d0" />

<img width="1186" height="886" alt="Captura de pantalla de 2025-10-03 12-03-46" src="https://github.com/user-attachments/assets/c395f3ea-d0e8-4482-85e4-1e6d462ba0a5" />

<img width="1186" height="886" alt="Captura de pantalla de 2025-10-03 12-04-48" src="https://github.com/user-attachments/assets/458fa1b7-bd1f-4392-aa49-ee3a513beed4" />

<img width="1186" height="886" alt="Captura de pantalla de 2025-10-03 12-28-39" src="https://github.com/user-attachments/assets/cb21aaeb-7d50-412d-8355-5e2f7d9df452" />

<img width="880" height="542" alt="Captura de pantalla de 2025-10-03 12-29-26" src="https://github.com/user-attachments/assets/e5fb4ee1-8454-4233-af71-7c4f60686900" />

<img width="880" height="542" alt="Captura de pantalla de 2025-10-03 12-29-47" src="https://github.com/user-attachments/assets/608725a0-8125-432c-98bb-c046210dfa49" />

<img width="1104" height="639" alt="Captura de pantalla de 2025-10-03 12-39-50" src="https://github.com/user-attachments/assets/48f1c293-ddf0-4a88-b35f-f4cade900f8c" />

<img width="651" height="483" alt="Captura de pantalla de 2025-10-03 12-40-43" src="https://github.com/user-attachments/assets/4e2693ce-580f-45f4-b63c-88cca4dfddb6" />

<img width="641" height="489" alt="Captura de pantalla de 2025-10-03 12-41-20" src="https://github.com/user-attachments/assets/79a04a1b-58e9-43d3-a7a1-3628b83625f0" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-46-42" src="https://github.com/user-attachments/assets/3a4a50aa-82a1-4eeb-b4a1-3caed095bef8" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-49-01" src="https://github.com/user-attachments/assets/05c42854-8a97-49cf-bda1-572091513149" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-51-43" src="https://github.com/user-attachments/assets/10c47847-be52-46cf-ad35-390b4871f561" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-53-05" src="https://github.com/user-attachments/assets/a82c9858-418f-446a-a3b2-9e306f3f8cb8" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-53-49" src="https://github.com/user-attachments/assets/a463d045-65a2-4598-a807-3a4dab15ab2b" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-54-49" src="https://github.com/user-attachments/assets/01cd6b90-38ba-4e02-8b48-5237f51e4cf7" />

<img width="746" height="486" alt="Captura de pantalla de 2025-10-03 12-57-50" src="https://github.com/user-attachments/assets/847b8947-4da3-4331-8cc8-e3113ff74bf5" />

<img width="1037" height="821" alt="Captura de pantalla de 2025-10-03 13-01-18" src="https://github.com/user-attachments/assets/31c34a3b-7463-4640-b561-b7d93b2069cc" />


 
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


