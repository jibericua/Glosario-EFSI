# EFSI 2
## Clasroom 5to a:
jncwcwo
## Clasroom 5to b:
gvqmat4

___
# TP1

(Template)

 ## Consigna:
 * El trabajo es por grupos de proyecto
 * Tienen que trabajar todos utilizando la metodologia del workflow de github
 * Organizar que parte del glosario/tabla hace cada uno por medio de la seccion de Issues
 * Cada alumno:
    * trabaja en su propia Branch
    * tiene que resolver por lo menos 1 issue del profesor
    * tiene que efectuar un pull request y resolver conflictos


# Tabla "Guia" =\> "Cheat-Sheet":

<table class="tg">
<thead>
  <tr>
    <th class="tg-9wq8" colspan="6">MODELO DE CAPAS (Layers)</th>
    <th class="tg-9wq8" rowspan="2">Protocolos de red </th>
    <th class="tg-9wq8" rowspan="2">Dispositivo de conexion de red</th>
  </tr>
  <tr>
    <th class="tg-9wq8">"Tipos" de Capas</th>
    <th class="tg-9wq8" colspan="2"> MODELO OSI</th>
    <th class="tg-9wq8" colspan="2">MODELO TCP/IP </th>
    <th class="tg-9wq8">Unidad de datos de protocolo (PDU)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas del anfitrion/host "Software"</td>
    <td class="tg-9wq8">7</td>
    <td class="tg-9wq8">Aplication</td>
    <td class="tg-9wq8" rowspan="3">4</td>
    <td class="tg-9wq8" rowspan="3">Process</td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="3"></td>
    <td class="tg-9wq8" rowspan="4"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">6</td>
    <td class="tg-9wq8">Presentation</td>
  </tr>
  <tr>
    <td class="tg-9wq8">5</td>
    <td class="tg-9wq8">Session</td>
  </tr>
  <tr>
    <td class="tg-9wq8">4</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Transport</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="4">Capas de red  "Firmware" "Hardware"</td>
    <td class="tg-9wq8">3</td>
    <td class="tg-9wq8">Network</td>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Network / Internet</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">2</td>
    <td class="tg-9wq8">Data link</td>
    <td class="tg-9wq8" rowspan="3">1</td>
    <td class="tg-9wq8" rowspan="3">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">1</td>
    <td class="tg-9wq8">Physical</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
  <tr>
    <td class="tg-9wq8">0*</td>
    <td class="tg-9wq8">Media</td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
    <td class="tg-9wq8"></td>
  </tr>
</tbody>
</table>

*La capa de Medio (Media) no forma parte oficial del Modelo OSI, pero esquematicamente la estudiamos ahi

# Glosario

## Contenido del Glosario :
* Definicion y/o explicacion
* En que capa TCP/IP \<=\> OSI trabajan
* ### Elementos de una red
#### y en que capa de los modelos TCP/IP \<=\> OSI trabajan ==>> se completa en la tabla
  *  Router
  *  Switch
   *  Switch Capa 2 (modelo osi)
   *  Switch Capa 3
  *  Hub
  *  Server
  *  Host
  *  Firewall
  *  IP phone
  *  Wireless Access-point
  *  Wireless Router
  *  Wan
  *  Lan
  *  Media (Medio de Transporte)
* ### Protocolos
  *  DNS
  *  FTP
  *  SSH
  *  SMTP
  *  POP
  *  SNMP
  *  DHCP
  *  HTTP/S
  *  TCP / UDP
  *  IPv4
  *  IPv6
  *  ARP
  *  MAC
  *  IEEE 802.11 (WIFI)
  *  Fibra OPTICA

* ###   Unidad de Datos de protocolo (PDU)(Encapsulamiento)
  * Datos
  * Segmento
  * Paquete
  * Trama
  * Bits
  * Señal (dbm)

* ###   Medios
  * #### Conectores
    * (con foto) Conector RJ45 Hembra (Jack RJ45)
    * (con foto) Conector RJ45 Macho (ficha RJ45)
    * (con foto) Norma T568A y T568B (ficha RJ45 y JackRJ45)
    * Cable Cruzado vs Cable Derecho
  * #### CABLE UTP (CAT5 CAT5e y CAT6)
    * Colores de los pares del cable UTP
    * Diferencias Constructivas
    * Velocidades Maximas
    * Distancias Maximas
  * #### IEEE 802.3 (ETHERNET)
    * 10BASE-T (802.3i)
        1. cantidad de pares en uso
        2. Velocidad Maxima
        3. Tipo de cable
    * 100BASE-TX (802.3u)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * 1000BASE-T (802.3ab)
     1. cantidad de pares en uso
     2. Velocidad Maxima
     3. Tipo de cable
    * Full Duplex (802.3x)
    * Auto-negociación
      * velocidad
      * Full Duplex vs Half Duplex\
    * POE (802.3af)
