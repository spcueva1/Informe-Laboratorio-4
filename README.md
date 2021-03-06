# INFORME-DE-LABORATIRIO-4

# 1) OBJETIVOS

 Objetivo general:

Comprobar experimentalmente el Teorema de Superposición, mediante calculos escritos y utilizando simuladores.

Objetivos especificos:

-Identificar el elemento a cambiar del circuito, para realizar el análisis correcto del Teorema de Superposición.

-Diseñar en algún simulador facilitado por el docente el esquema propuesto y tomar los valores de tensión o intensidad respectivamente.

-Realizar la comparación de datos de forma indirecta y directa de los valores calculados y realizados en el simulador.


# 2) Marco teorico

Teorema de Superposición.

Un circuito lineal que contenga dos o más fuentes independientes puede analizarse obteniendo las tensiones y corrientes en las ramas debida a cada una de las fuentes por separado y luego superponiendo los resultados. Un circuito lineal que contenga dos o más fuentes independientes puede analizarse obteniendo las tensiones y corrientes en las ramas debida a cada una de las fuentes por separado y luego superponiendo los resultados.

En cualquier rama dada de un circuito con múltiples fuentes, la corriente puede calcularse al determinar en esa rama particular las corrientes producidas por cada fuente que
actúa sola, con todas las demás fuentes reemplazadas por sus resistencias internas. La corriente total en la rama es la suma algebraica de las corrientes individuales presentes
en dicha rama. 

Las fuentes de tensión se suprimen sustituyéndolas por un cortocircuito; las fuentes de intensidad se suprimen por un circuito abierto. La superposición no puede aplicarse directamente para el cálculo de la potencia, ya que la potencia de un elemento es proporcional al cuadrado de la corriente o al cuadrado de la tensión, por lo que no es lineal.

Los pasos para aplicar el método de superposición:

Paso 1. Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

Paso 2. Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito.

Paso 3. Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

Paso 4. Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/06f686ae463d21a4ba6b2a7a2bc710f66daaa8bf/Info%204/Imagen1.44.jpg)


# 3) Explicacion de procedimiento

Primero plasmamos en el simulador el ejercicio propueto en la guia. De esta maner analizamos lo pedido y comenzamos a resolver.

Para las fuetes de voltaje hacemos un circuto cerrado es decir eliminamos esa fuente.

Para esto debemos remplazar primero la de 20 vol y despues remplazamos la segunda fuente de 12 vol y asi al final de los resultados realizamos una suma algebraica para obtener la intensidad que sircula por esa parte del circuito.

Para calcular las resistencias equivalentes dependiendo el caso utilizamos ley de ohm, circuitos serie paralelo y mas.

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/6272e6211d4eee6435ceedde3cd225115f612a47/Info%204/Imagen2.44.png)


 Cálculos:
 
Usando la fuente de 20v, es decir remplazando por un circuito cerrado a mi funete de voltaje de 12v.

Req1=1/(1/0,82+1/2,2)=0,597kΩ

RT=Req2=1+0,597=1,597Ω

It=20/1,597=12,523mA

Divisor de corriente.

Ix=(2,2/(2,2+0,82))*12,523= 9,12mA

VA=9,122*0,82=7,48 V

Usando la fuente de 12v, es decir remplazando por un circuito cerrado a mi funete de voltaje de 20v.

Req1=1/(1/1k+1/2,2k)=687,5Ω

Req2=820+687,5=1507,5Ω

Ieq2=12/1507,5=7,960*10^(-3) A

VA=820*7,96*10^(-3)=6,5272 V

Req3=1/(1/1507,5+1/470)=358,29Ω

It=12/358,29=0,03349A

Divisor de corriente.

Ix=(47/(1507,5+47))*0,03349= 7,96mA




![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/475898bd59676e59ec1f1bd9aa3a773a2fe28b23/info%204.1/inf%204%20calculo.png)


Simulacion en Tinkercard:

Imagen 1 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%201.jpg)

Imagen 2 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%202.jpg)

Imagen 3 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%203.jpg)


# 4) Respuesta a interrogantes y cálculo de error.

Resultados:

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/9c9ec0d6893ae6cfca7a6437609089c43786a97b/respuesta%20inf%204%20(2).png)


Se logro comprabar que los resutlados del  simulado es igual a los valores que encontramos dentro de el analisis por superposición, los cuales fueron evaluados por los conocimientos adquiridos, y por lo tanto obtuvimos lo propuesto en el ejercicio.

El calculo de error, si se lo evalua, este tendra un resultado de +-0,025% de error ya que corresponde a los valores exactos, tanto medidos, simulados y calculados.

# 5) Video

https://youtu.be/FNPo62Q5EE4


# 6) Conclusiones.

-Se comprobó el teorema de Superposición, haciendo la comprobación mediante los cálculos y el simulador, con lo que se establece que el teorema funciona con cualquier método que se use.

-Se analizaron los circuitos en serie, con uso de las leyes de Ohm y Kirchhoff, así se lograron resolver los problemas en circuitos eléctricos aplicando el teorema de superposición.

-El teorema de la superposición establece que varias fuentes de un circuito es igual a la suma de los circuitos simplificados usando solo una de las fuentes, este teorema no es exclusiva para los circuitos lineales.


# 7) Bibliografia

- M. (2021b, abril 2). Teorema de superposición. MiElectrónicaFácil.com. Recuperado 27 de diciembre de 2021, de https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-superposición/#pasos-del-teorema-de-superposición.

- Salazar, A. (2012). 3. Análisis de superposición 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_superposición.pdf



