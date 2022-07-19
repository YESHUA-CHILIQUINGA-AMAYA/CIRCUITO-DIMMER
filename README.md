# CIRCUITO-DIMMER

# UNIVERDIAD DE LAS FUERZAS ARMADAS “ESPE”

## NOMBRE: YESHUA AMADOR CHILIQUINGA AMAYA

## NRC: 7909-202250

# INFORME DEL CIRCUITO DIMMER

## OBJETIVOS:

### Objetivo principal:

Construir un circuito Dimmer con la finalidad de entender su funcionamiento.
### Objetivos específicos:
* Explicar el funcionamiento del circuito.
* Mostrar que el circuito realizado por el estudiante funcione a la perfección.
* Explicar sus componentes y para poder entender a detalle su funcionamiento.

## Introducción:

El Dimmer electrónico es un regulador atenuador o dimmer, sirve para regular la energía en uno o varios focos con el fin de variar la intensidad de la luz que emiten, cuando las propiedades de la lámpara lo hacen posible, en sí, el dimmer tiene muchas aplicaciones, podemos regular la velocidad de giro de un motor eléctrico, también podemos conectar un cautín para regular su temperatura, en si lo que hace el dimmer es variar el voltaje AC (corriente alterna) en una des sus salidas del dimmer, al final del blog veremos cómo regular la velocidad e un ventilador.

## Marco teórico:

### Diagrama:  

![image](https://user-images.githubusercontent.com/104863870/179682601-6c6089d4-22a4-4c9f-9268-f95f5cb70dc6.png)

### Materiales:

* 1 TRIAC el BT136.
* 1 DIAC, con el código DB3, o también pueden utilizar otro DIAC.
* 1 Condensador cerámico 104/630v, pueden utilizar de 250v, 400v.
* 1 Potenciómetro de 500kΩ.
* 1 Resistencia de 10kΩ.
* 1 Resistencia de 100Ω.
* 1 Lámpara de 220v o 110v AC.

### El TRIAC:

Un TRIAC o Triodo para Corriente Alterna es un dispositivo semiconductor, de la familia de los tiristores. La Diferencia con un tiristor convencional es que es unidireccional y el TRIAC es bidireccional. De forma coloquial podría decirse que el TRIAC es un interruptor capaz de conmutar la corriente alterna (permite modificar el camino que deben seguir los electrones).

El TRIAC es un dispositivo semiconductor de tres terminales (T1, T2 y G), que se usa para controlar el flujo de corriente promedio a una carga, con la particularidad de que conduce en ambos sentidos y puede ser bloqueado por inversión de la tensión o al disminuir la corriente por debajo del valor de mantenimiento. El TRIAC puede ser disparado independientemente de la polarización de puerta, es decir, mediante una corriente de puerta positiva o negativa.

#### Características generales del TRIAC.

•	La corriente puede pasar en ambas direcciones.
•	Adecuados para convertidores de conmutación forzada en aplicaciones de potencia intermedia y alta.
•	Control del encendido por corriente de puerta (pulso). No es posible apagarlo desde la puerta.
•	Pueden apagarse con un pulso de señal negativo.

![image](https://user-images.githubusercontent.com/104863870/179682715-7ab648df-7bf1-486f-9f10-5526559d86d0.png)

### EL DIAC:

Es un componente que está preparado para conducir en los dos sentidos de sus terminales, por ello se le denomina bidireccional, siempre que se llegue a su tensión de cebado o de disparo (30v aproximadamente, dependiendo del modelo.)
Los encapsulados de estos dispositivos suelen ser iguales a los de los diodos de unión o de Zener, es un diodo bidireccional disparable que conduce la corriente solo tras haberse superado su tensión de disparo, y mientras la corriente circulante no sea inferior al valor característico para ese dispositivo.
El comportamiento es fundamentalmente el mismo para ambas direcciones de la corriente. La mayoría de los DIAC tienen una tensión de disparo de alrededor de 30v. En este sentido, su comportamiento es similar a un neón. Los DIAC son una clase de tiristor, y que se usan normalmente para disparar los TRIAC, otra clase de tiristor. Es un dispositivo semiconductor de dos terminales, llamados ánodo y cátodo. Actúa como un interruptor bidireccional el cual activa cuando el voltaje entre sus terminales alcanza el voltaje de ruptura, dicho voltaje puede estar entre 20 y 36 volt según la referencia.
Cuando la tensión de disparo se alcanza, la tensión en el DIAC se reduce y entra en conducción dejando pasar la corriente necesaria para el disparo de SCR o TRIAC. Se utiliza principalmente en aplicaciones de control de potencia mediante control de fase.
Un diac es un elemento semiconductor utilizado normalmente en el control de potencia, lo que significa que servirá para controlar electrónicamente el paso de corriente eléctrica.

#### Características generales y aplicaciones

Se emplea normalmente en circuitos que realizan un control de fase de la corriente del TRIAC, de forma que solo se aplica tensión a la carga durante una fracción de ciclo de la alterna. Estos sistemas se utilizan para el control de iluminación con intensidad variable, calefacción eléctrica con regulación de temperatura y algunos controles de velocidad de motores.

#### Otras aplicaciones del DIAC:

* Controles de relevador.
* Circuitos de retardo de tiempo.
* Fuentes de alimentación regulada.
* Interruptores estáticos.
* Controles de motores.
* Recortadores.
* Inversores.
* Ciclo-conversores.
* Cargadores de baterías.
* Circuitos de protección.
* Controles de calefacción.
* Controles de fase.
 
![image](https://user-images.githubusercontent.com/104863870/179683047-8414604b-ae84-4090-9cb7-86ca5d54fde2.png)

### CONDENSADOR CERÁMICO:

Es un componente electrónico pasivo que es capaz de almacenar una carga eléctrica, se comporta como un filtro que bloquea la corriente directa y permite que la corriente alterna fluya sin ningún problema.

Este tipo de condensador está compuesto de dos superficies conductoras llamadas electrodos, separadas por un aislante el cual es llamado “dieléctrico”.
El condensador de cerámica no está polarizado, lo cual significa que los dos electrodos no están cargados activa y negativamente; y utiliza capas de metal y cerámica como dieléctricos.
 
![image](https://user-images.githubusercontent.com/104863870/179683107-98ea51dc-e90a-445e-b307-e5b00de07f81.png)

### Potenciómetro
El potenciómetro es un instrumento utilizado generalmente en un ámbito técnico con el fin de determinar la diferencia de potencial eléctrico entre dos terminales eléctricas. La diferencia de potencial es lo que comúnmente se conoce como voltaje.

#### ¿Cómo funcional?

Un potenciómetro tiene un funcionamiento sencillo, tiene una resistencia variable en cada extremo y una tercera conexión hacia un control deslizante, el cual nos permitirá aumentar o disminuir la resistencia propiamente. El propósito de esto es conseguir un valor variable entre las conexiones, el cual podremos controlar nosotros mismos.
 
![image](https://user-images.githubusercontent.com/104863870/179683264-c966472a-0cfc-4435-a926-5b51a089d727.png)

### Circuito Armado:
  
![image](https://user-images.githubusercontent.com/104863870/179683182-ace6931c-b824-404a-8e27-638ede2626c1.png)

![image](https://user-images.githubusercontent.com/104863870/179683202-9d6615c5-8f02-4322-be03-72076db42d82.png)

![image](https://user-images.githubusercontent.com/104863870/179683211-c26a443b-2fc8-4d3f-a493-a24649ee4b9b.png)

### CONCLUSIÓN:

Como pudimos observar su funcionamiento del circuito DIMMER nos ayuda a regular el nivel de energía que recibe el foco para poder manejar la intensidad de luz que nos proporciona. Aprendimos cada funcionamiento  de los elementos fundamentales y también un ejemplo de como está construido y como funciona.

### BIBLIOGRAFÍA:

https://como-funciona.co/un-potenciometro/

https://www.onubaelectronica.es/condensador-ceramico/

http://www.electronicaivanespinoza.com/2018/12/como-hacer-un-dimmer-electronico-con.html

