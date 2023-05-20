# Pruebas con generación de datos Grupo 17

Este repositorio fue creado como parte de la entrega correspondiente a la semana 7 de la asignatura de Pruebas Automatizadas de Software.

## Integrantes del grupo
- Santiago Alvarez Soto
- Camilo Ramírez Restrepo
- Laura Daniela Molina
- Wilmar Julian Puentes

## Escenarios de prueba
Hemos elaborado una hoja de cálculo en la que detallamos de manera precisa cada escenario de prueba, junto con la funcionalidad a la que se encuentra vinculada, las pre-condiciones necesarias, el resultado esperado una vez concluida la prueba, la estrategia de generación de datos utilizada y demás información de utilidad.

Durante la ejecución de las pruebas, algunas fallaron como consecuencia de errores propios de Ghost. Estas pruebas se resaltaron en color rojo y se les asignó una incidencia correspondiente, como se muestra en la imagen:
![image](https://github.com/CamiloRamirezR/Pruebas_Generacion_Datos_Grupo_17/assets/17149432/6457f195-1e1e-48a4-92d8-e26c256c0fc6)

Por otro lado, aunque algunas pruebas no presentaron fallas, durante su ejecución identificamos errores adicionales, como por ejemplo áreas de mejora o posibles problemas en la interfaz o el comportamiento del sistema, que también se reportaron como incidencias. Estas pruebas se resaltaron en color amarillo, tal como se muestra en la imagen:
![image](https://github.com/CamiloRamirezR/Pruebas_Generacion_Datos_Grupo_17/assets/17149432/de765dfd-1c2d-4241-bea6-859b5a7fafba)

Por lo cuál al correr los 120 escenarios, no todos van a pasar y estos son los que hemos marcado en rojo.

[Link escenarios de prueba](https://uniandes-my.sharepoint.com/:x:/g/personal/ld_molina11_uniandes_edu_co/EQLNOAClGmZPqHEsnikAkTwBQ5vvZPJeeqVltoQnUci4pw?e=LltiaR)

## Escenarios probados con Cypress
Para mantener en un solo lugar los scripts en Cypress creamos un repositorio independiente. El README del repositorio explica cómo se pueden ejecutar los scripts correspondientes. De 120 escenarios, 107 se crearon en esta herramienta. [Link repositorio](https://github.com/CamiloRamirezR/Prueba_Generacion_Datos_Cypress)

## Escenarios probados con Kraken
Para mantener en un solo lugar los scripts en Kraken, creamos un repositorio independiente. El README del repositorio explica cómo se pueden ejecutar los scripts correspondientes. De 120 escenarios, 13 se crearon en esta herramienta. [Link repositorio](https://github.com/CamiloRamirezR/Pruebas_Generacion_Datos_Kraken)

## Resumen actividades

**1. Código de los escenarios de prueba que usan las tres estrategias de generación de datos y permiten generar 120 escenarios diferentes. Los escenarios son funcionales y en el readme del repo se detallan las instrucciones para ejecutarlos. Estas instrucciones deben llevar a la ejecución de los escenarios**

Se decidió reutilizar 26 escenarios de los 40 escenarios creados anteriormente para la entrega de la semana 5, 13 en  Kraken y 13 Cypress, en los cuáles ya estabamos utilizando la estrategia de generación de datos aleatoria. 

En cuanto a los 94 escenarios restantes, se optó por desarrollarlos exclusivamente en Cypress debido a nuestra familiaridad con esta herramienta. Dentro del repositorio de Cypress, se pueden encontrar tres carpetas: "a_priori", "dinámico" y "aleatorio". En cada una de estas carpetas se encuentran los escenarios correspondientes que fueron diseñados siguiendo la estrategia a priori, dinámica y aleatoria, respectivamente.

<hr/>

**2. Descripción de las estrategias usadas y cómo se integran estas estrategias en los escenarios de pruebas. Se debe evidenciar en la descripción que se usan las tres estrategias solicitadas: pool de datos a-priori, pool de datos (pseudo) aleatorio dinámico y escenario aleatorio.**

En el [siguiente link](https://github.com/CamiloRamirezR/Prueba_Generacion_Datos_Cypress/wiki/Descripci%C3%B3n-estrategias) se puede observar la descripción de las estrategias de utilizamos y como las implementamos. 

**_Nota_**: Para saber que estrategia se utilizo especificamente en cada escenario, puede revisar la [hoja de cálculo](https://uniandes-my.sharepoint.com/:x:/g/personal/ld_molina11_uniandes_edu_co/EQLNOAClGmZPqHEsnikAkTwBQ5vvZPJeeqVltoQnUci4pw?e=LltiaR) que hicimos con la descripción cada escenario.

<hr/>

**3. Se reportan, en el sistema de registro de incidencias, por lo menos 10 defectos por manejo de datos inválidos.**

La incidencias observadas se reportaron en el [sistema de registro de incidencias](https://github.com/santi8194/ghost-grupo-17/issues).

