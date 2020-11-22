# Manual de Comandos
### Datos 
- Grupo 31

### Comandos de EtherSwitch
<strong>conf t:</strong> nos permite acceder a las configuraciones de algun terminal<br>
<strong>vlan #:</strong> nos permite crear una vlan indicandole el número de esta<br>
<strong>name *NOMBRE*:</strong> nos permite crear un nombre para nuestra VLAN <br>
<strong>int f#/#:</strong> nos permite ingresar a alguna de nuestras interfaces donde los # indicaran a que interface nosotros deseamos acceder<br>
<strong>switchport mode trunk:</strong> convierte un puerto de nuestro etherswitch en modo trunk que este nos permite tener limitadas las vlans que nosotros vamos a emplear<br>
<strong>no shu:</strong> Este es el comando que habilita una interfaz.<br>

### Comandos de router

<strong>int range f#/# - #:</strong> Permite entrar a un rango para la configuracion de las interfaces donde # es el número de 
<strong>no shu:</strong> Este es el comando que habilita una interfaz.<br>
<strong>exit</strong> Este sirve para salir de la configuracion actual.<br>

<strong>int f#/#.#:</strong> sirve para configurar una sub interfaz.
<strong>encapsulation dot1Q #:</strong> Sirve para encapsular una vlan a la subinterfaz
<strong>ip address IP MASK:</strong> Sirve para agregar una ip y una mascara.
