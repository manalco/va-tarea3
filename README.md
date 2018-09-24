# Índice de Calidad del Aire (ICA) de Santiago de Cali 2010 a 2018
La presente visualización es una actividad para la clase de [Visual Analytics - Uniandes 2018-2](http://johnguerra.co/classes/visual_analytics_fall_2018/). Los datos originales fueron recolectados por el [Departamento Administrativo de Gestión de Medio Ambiente](http://www.cali.gov.co/dagma) de la Alcaldía Municipal de Santiago de Cali y publicados en la página de [Datos Abiertos del Gobierno de Colombia](https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/Indice-de-calidad-del-aire-ICA-de-Santiago-de-Cali/fci7-y95i).

Esta visualización presenta el Índice de Calidad del Aire (ICA) tomado en nueve diferentes estaciones de medición en la ciudad de Santiago de Cali desde enero 2010 hasta agosto 2018. Usando steamgraph, inicialmente se presenta el ICA por cada una de las estaciones de medición através del tiempo y por medio de una interacción con un select se muestra el ICA por "color" en cada estación de medición y a nivel general.

Los colores del ICA están establecidos en la [Resolución 2254 de 2017](http://www.minambiente.gov.co/images/normativa/app/resoluciones/96-res%202254%20de%202017.pdf) (página 8) del Ministerio de Ambiente y Desarrollo Sostenible. Más información en la visualización https://cubosensei.github.io/va-tarea3.


## Objetivo
Generar una visualización interactiva para presentar el Índice de Calidad del Aire (ICA) en las diferentes estaciones de medición de la ciudad de Santiago de Cali desde enero de 2010 hasta agosto de 2018. La información presentada debe permitir comprender de forma básica el ICA y sus códigos de color así como la tendencia de dicho índice através del tiempo en las diferentes estaciones de medición y a nivel general de la ciudad y de ser necesario establecer si son necesarias acciones de control sobre la calidad del aire en Santiago de Cali.


## Tecnologías Usadas
* [D3](https://d3js.org/)
* [Vega-Lite](https://vega.github.io/vega-lite/)
* [SASS](https://sass-lang.com/)


## Ejecución Local
Para la ejecución local basta con usar un servidor web como Apache y dirigir un dominio localmente hacia el directorio que contenga los archivos fuente. Se recomienda XAMPP y el tutorial de [1&1](https://www.1and1.com/digitalguide/server/tools/xampp-tutorial-create-your-own-local-test-server/) para la configuración de Windows, [Gestiona tu Web](https://www.gestionatuweb.net/instalar-un-servidor-web-en-linux-para-pruebas-y-aprendizaje-con-xampp/) para Linux y [MAMP](https://documentation.mamp.info/en/MAMP-Mac/First-Steps/) para MacOs.


## Screenshot
![preview](/ScreenShot.png)


## Créditos
* Este contenido es publicado bajo la licencia MIT. Realizado por [Manuel Alvarado](http://www.manalco.co).
* Datos por [Departamento Administrativo de Gestión de Medio Ambiente](http://www.cali.gov.co/dagma) de la Alcaldía Municipal de Santiago de Cali publicados en https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/Indice-de-calidad-del-aire-ICA-de-Santiago-de-Cali/fci7-y95i

---

Visualización disponible en https://cubosensei.github.io/va-tarea3
