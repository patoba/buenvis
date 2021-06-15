# Impacto del COVID-19 en la economía mexicana

- Barrero Olguín Adolfo Patricio
- Barriga Rosales Alan
- Martínez Ostoa Néstor Iván
- Ramírez Bondi Jorge Alejandro

## Introducción

Enfrentados al dilema en el que suavizar la curva epidemiológica implica agravar la recesión económica y alargarla, los gobiernos se han visto obligados a implementar medidas económicas contracíclicas para aminorar los efectos de las cuarentenas y el distanciamiento social. Debido al grado de globalización que se ha visto desde principios del siglo XXI, los efectos de las medidas de salud para combatir la pandemia del SARS-COV2 seguramente serán a largo plazo y se acentuarán si no se responde con las medidas adecuadas.

Las administraciones de EE.UU. y países europeos, han demostrado que están dispuestas a ir más allá de las respuestas tradicionales a crisis económicas. Si bien es cierto que dichas medidas —enfocadas en apoyar directamente a las familias para estimular el ingreso y evitar la bancarrota de las empresas— sean probablemente la manera más efectiva de romper los efectos del confinamiento y detención de las cadenas de suministro, puede que la respuesta que puedan dar los países en desarrollo sea muy diferente que la de aquellos desarrollados.

En el caso de México, ¿qué se puede esperar de la caída en ingresos de las familias mexicanas? ¿Los más vulnerables lograrán escapar las condiciones de pobreza en las que se encuentran? ¿La pandemia es el único causante de los efectos económicos que ya se empiezan a vislumbrar? ¿Qué se puede esperar de una recuperación desigual, en su mayoría provocada por la recuperación económica en EE.UU., entre los sectores económicos?

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~nestorivanmo/1.embed" height="525" width="100%"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~nestorivanmo/3.embed" height="525" width="100%"></iframe>

Incluso antes de que comenzara el confinamiento en México, los efectos de la pandemia a nivel global, golpearon nuestra economía. Partiendo de un precio por dólar de $19.64 en febrero de 2020, el 23 de marzo se alcanzó un máximo histórico de $25.68 pesos. Es decir, un aumento de más del 30%. A pesar de que el precio ya se haya estabilizado nuevamente, este evento es una alerta más de que la composición de las actividades económicas en México son sumamente sensibles a golpes externos.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/5.embed" height="525" width="100%"></iframe>

<p style="text-align:center;">Figura 2 — fuente: <a href="banxico.org.mx">Banco de México</a></p>

La economía mexicana depende en gran medida de sectores que estuvieron sumamente afectados por la pandemia. Desde el inicio del confinamiento en países europeos y asiáticos, se puede identificar una primera etapa, sobre todo para los estados que dependen del turismo y tienen una gran presencia manufacturera, debido a que desde enero de 2020, se interrumpieron las cadenas de suministro globales y los vuelos hacia nuestro país o cualquier otro destino turístico. También, se observó una caída desenfrenada en los precios de materias primas, principalmente la del petróleo. Por lo que, llevó a que el mercado redujera la producción.

A raiz de las medidas impuestas durante la *Jornada Nacional de Sana Distancia* —la cual implicaba limitar la realización de ciertas actividades y reducir el contacto físico entre personas e incluso el cierre de centros de trabajo— llevó a que los negocios considerados como no esenciales sufrieran reveses, probablemente nunca antes vistos, en sus ingresos. En consecuencia, millones de personas perdieron su empleo y miles de negocios cerraron permanentemente. Más adelante, se incluye una gráfica con la caída del número de personas con alguna actividad económica.

Posteriormente, se observó una ligera baja en el número de contagios y un aumento en la capacidad hospitalaria. Por lo que, el gobierno mexicano optó por relajar las medidas de sanidad, llevando el color del Semáforo Epidemiológico (así se conoce a la serie de indicadores que muestran las restricciones producto de la pandemia) a fases que permitían mayor actividad. Esto, junto con el hecho de que los países asiáticos comenzaban a retomar las actividades industriales, pudo significar un aliciente para que aumentara la actividad económica del sector manufacturero y de servicios. También, es importante recalcar que el precio de las mercancías aumentó.

La relajación de las medidas, junto con un aparente empuje del gobierno para que la economía repuntara, llevó a que durante los meses de diciembre de 2020 y enero de 2021 —también coincidente con las fiestas de fin de año— se viviera un elevado número de contagios y muertes consecuencia de la enfermedad. Esto llevó a que los sectores minoristas y de servicios no tuvieran actividad durante meses importantes de venta.

Finalmente, pasamos a la última fase de la pandemia —la misma en la que actualmente nos encontramos—. El entorno actual se encuentra determinado por un perseverante temor de que la COVID-19 sigue siendo un riesgo latente para todas las personas, a pesar de los programas de vacunación. Las escuelas comienzan a tener clases presenciales, sin que los alumnos ni gran mayoría de los padres de familia tengan su esquema de vacunación completo. Peor aún, no se sabe con mayor detalle cuál es panorama del estado de vacunación de los diferentes sectores de la población debido a que no existen datos abiertos y transparentes disponibles.

Aún así, las actividades comienzan a regresar a la actividad y, por ello, será fundamental entender las afectaciones que las restricciones a la movilidad y medidas de distanciamiento social han traído a la economía. Solo así, será posible diseñar políticas e implementar mecanismos que ayuden a revertir el impacto. Conocer los efectos de más de un año de confinamiento y las marcas sobre los sectores poblacionales y regiones del país permitirá focalizar la respuesta para recuperar el crecimiento y desarrollo de México.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/1.embed" height="525" width="100%"></iframe>

## Metodología

### Preprocesamiento de datos

Dado que los datos se obtuvieron de fuentes que presentan un buen manejo de datos, no fue necesario verificar ni eliminar duplicados.

#### COVID-19

- Obtención de datos de la página de la Secretaría de Salud
- Verificación y de-duplicación de registros
- Agrupamiento por fechas de registro del paciente
  - Obtención de suma del total de pacientes registrados como enfermos de la COVID-19
- Eliminación de campos no utilizados durante el análisis
- Normalización de fechas de registro para empatar dicho campo con las fechas de los demás datos

#### Indicador Global de la Actividad Económica

- Obtención de base de datos de la página del Banco de México
- Agrupamiento por fechas
- Segmentación por actividades relevantes
- Eliminación de campos no utilizados durante el análisis
- Normalización de registros y emparejamiento con fechas de registro de pacientes de COVID-19

#### Producto Interno Bruto

- Obtención de base de datos de la página del Banco de México
- Segmentación de base de datos
  - Base a precios corrientes
  - Base a precios constantes
- Agrupamiento por fechas
- Eliminación de estimadores y campos no utilizados durante el análisis
- Eliminación de campos vacíos o no disponibles. Perteneciente a periodos donde no se contaba con este registro o índice
- Normalización de flujos a periodos trimestrales

#### Tipo de cambio USD-MXN

- Descarga de datos de la página del Banco de México
- Sustitución de campos vacíos mediante promedio de los datos existentes.
  - Generalmente se utilizó el campo “para solventar obligaciones”
  - Para los campos correspondientes a días no laborables se utilizó el valor de “para solventar obligaciones”.
- Normalización de fechas a formato de base de datos COVID-19

#### Venta de autos

- Descarga de datos de la página del INEGI
- Eliminación de datos no relevantes
- Fechas anteriores al enfoque del análisis
- Eliminación de campos: cobertura, marca, modelo, producto estadístico y área geográfica de referencia.
- Agrupamiento por tipo de vehículo y segmento.
- Suma de unidades vendidas.
- Carga al repositorio y programa. 

### Creacion de graficos

#### Frameworks usados

Para visualizar los datos usamos la biblioteca de Python llamada Plotly. Plotly además de ser una biblioteca de programación ofrece más servicios a programadores. Como un servicio llamado Dash que permite construir aplicaciones web analiticas.

Para crear una gráfica en plotly se puede usar plotly express que permite crear gráficos de forma sencilla, rápida pero con desventaja de ser simples. Usando Figure es posible crear gráficos con más propiedades aunque sea un poco más lento su creación. Plotly también permite crear subplots de forma similar a como matplotlib lo hace.

#### Proceso de creacion de graficos

El proceso para realización de gráficas (una vez obtenido de los datos junto con su preprocesamiento) es determinar el tipo de gráfico que vamos a realizar (serie de tiempo, gráfico de barras, mapa) y la cantidad de gráficos que queremos en una misma figura. A partir de ello buscamos la forma de crear dicho gráfico en la documentación de plotly, añadimos las anotaciones correspondientes de los gráficos, y al final subimos la figura creada a chart-studio de plotly lo que nos permite generar un iframe que posteriormente será insertado en la página web. El iframe es un gráfico interactivo que permite que cualquiera pueda visualizar los datos y el usuario tenga interacción con el mismo.

#### Creación del sitio web

El sitio web fue creado con la herramienta de github llamada github pages, la cual permite crear una página web únicamente con markdown. Markdown al estar basado en html, es posible insertar el código de un iframe y funciona a la perfeccion.


## Resultados y discusión

Como lo mencionamos en la introducción, el eje de enfoque de nuestro proyecto será el analizar el impacto del COVID-19 en dos índices macroeconómicos:
1. Crecimiento económico medido a través del PIB
2. Desempleo medido a través de tasas de actividad, informalidad laboral y desempleo

### Impacto del COVID-19 en el crecimiento económico

#### Contexto en torno a la economía previo a la pandemia

Para poder entender a fondo el impacto de la pandemia en la economía mexicana, en particular si realizamos un análisis desde la perspectiva macroeconómica, es fundamental tener presente el contexto bajo el que se ha enfrentado la crisis sanitaria. La magnitud de las afectaciones están directamente relacionadas con el punto de partida y el 2019, no ha sido un año del todo alentador.

Durante 2019, el PIB de México decreció un 0.1%. A pesar de la promesa del gobierno federal de mantener el llamado superávit primario, la realidad es que el costo de la deuda interna y externa aumenta conforme se contrae la economía mexicana. Con ello, México se encuentra en circunstancias muy distintas respecto a la crisis global más reciente, la Crisis Financiera del 2008. A pesar del poco margen de maniobra con el que se cuenta, es posible minimizar el impacto del fenómeno global en la economía local.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/10.embed" height="525" width="100%"></iframe>

<p style="text-align:center;">Figura 3 — fuente: <a href="banxico.org.mx">Banco de México</a></p>

En la Figura 3, se puede observar que la economía mexicana ya tenía un bajo dinamismo desde principios del año 2018. Precisamente, no hubo crecimiento en dicho par de años, e incluso, se observan trimestre de caídas en el indicador de la actividad económica. Esto es muestra clara de la compleja situación fiscal en la que se encontraba México, mucho antes de siquiera tener que enfrentar los procesos de confinamiento, bajos niveles de producción o consumo y escasez de materias primas.

Con ello, se explica la baja demanda de consumo y escasez de bienes de producción que las empresas en México y el mundo están enfrentando. Las economías más influyentes del planeta han enfatizado en la importancia de dotar a las empresas con garantías para asegurar la supervivencia de las empresas, para mantener equilibrados los niveles de empleo y contar con las herramientas para un crecimiento económico en cuanto disminuyan las medidas sanitarias y distanciamiento social.

En consecuencia, el Banco de México redujo la tasa de interés objetivo en reiteradas ocasiones para buscar impulsar el consumo y aumentar el capital circulante. Sin embargo, especialistas coinciden en que dichas medidas de política monetaria no serán suficientes, dado que el problema de la pandemia se deriva de la economía real. Además, reducir la tasa implica que México sea menos atractivo frente a otras economías y llevaría a una fuga de capitales, aumentando el precio del dólar, en consecuencia, y reduciendo el poder de compra de los mexicanos.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Fecha</th>
    <th class="tg-0lax">Tasa objetivo</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">01/01/2020</td>
    <td class="tg-0lax">7.2500</td>
  </tr>
  <tr>
    <td class="tg-0lax">13/02/2020</td>
    <td class="tg-0lax">7.0000</td>
  </tr>
  <tr>
    <td class="tg-0lax">20/03/2020</td>
    <td class="tg-0lax">6.5000</td>
  </tr>
  <tr>
    <td class="tg-0lax">21/04/2020</td>
    <td class="tg-0lax">6.0000</td>
  </tr>
  <tr>
    <td class="tg-0lax">14/05/2020</td>
    <td class="tg-0lax">5.5000</td>
  </tr>
  <tr>
    <td class="tg-0lax">25/06/2020</td>
    <td class="tg-0lax">5.0000</td>
  </tr>
  <tr>
    <td class="tg-0lax">14/08/2020</td>
    <td class="tg-0lax">4.5000</td>
  </tr>
  <tr>
    <td class="tg-0lax">25/09/2020</td>
    <td class="tg-0lax">4.2500</td>
  </tr>
  <tr>
    <td class="tg-0lax">12/02/2021</td>
    <td class="tg-0lax">4.0000</td>
  </tr>
</tbody>
</table>

#### IGAE

Adicionalmente, si uno analiza el comportamiento de los diversos sectores componentes de la economía, es posible observar que la posible recuperación y disminución de la actividad se ha conformado de manera desigual. También, se debe considerar la naturaleza altamente informal de la economía mexicana, especialmente en el sector terciario. En consecuencia, más del 50% de los mexicanos no han podido ni podrán realizar trabajo desde casa, debido a que esto llevaría a que dejaran de percibir ingresos.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/12.embed" height="525" width="100%"></iframe>

Según podemos observar en la gráfica anterior, el impacto puede haber sido mayor gracias a que la economía se encontraba en un periodo de estancamiento y mayor fragilidad. Parte, atribuido a las malas decisiones de la administración saliente y la actual. En particular, destaca la cancelación del aeropuerto internacional de la Ciudad de México —una obra que llevaba más de una tercera parte de avance y se encontraba completamente fondeada—.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/14.embed" height="525" width="100%"></iframe>

#### Producto Interno Bruto

Igual que el Indicador Global de la Actividad Económica, el Producto Interno Bruto (PIB) muestran comportamientos similares. Aunado al contexto de fragilidad y bajo dinamismo previo al evento provocado por el virus SARS-COV-2, se observa una caída muy pronunciada, incluso antes del inicio del confinamiento. Cabe destacar, que los [indicadores de movilidad][apple mobility] arrojan una disminución de la actividad de tránsito antes del confinamiento oficial. La población se resguardó sabiendo que existía el riesgo de contraer la enfermedad, a pesar de que las autoridades no habían hecho la declaratoria formal de la emergencia sanitaria.

[apple mobility]: https://covid19.apple.com/mobility

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/16.embed" height="525" width="100%"></iframe>

A continuación, se observa que la “recuperación” ha sido desigual. El sector terciario sigue muy por debajo de los niveles pre-pandemia, gracias a la poca confianza y posibilidades de salir a consumir.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/18.embed" height="525" width="100%"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/20.embed" height="525" width="100%"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~bondi/22.embed" height="525" width="100%"></iframe>

### Impacto del COVID-19 en el empleo mexicano

Como lo mencionamos en la introducción, el eje de enfoque de nuestro proyecto será el analizar el impacto del COVID-19 en dos índices macroeconómicos:

1. Crecimiento económico medido a través del PIB


3. Desempleo medido a través de tasas de actividad, informalidad laboral y desempleo

Uno de los pilares fundamentales de cualquier economía mundial es el empleo de sus ciudadanos. En la sección anterior analizamos lo que fue el impacto del COVID-19 en el crecimiento económico y vimos que uno de los resultados que no deberían sorprender es que la Ciudad de México concentra la mayor cantidad del PIB mexicano. Bueno, ahora entraremos a analizar los resultados encontrados en el empleo mexicano, medidos con base en la Encuesta Nacional de Ocupación y Empleo del INEGI. Los datos que recabamos abarcan desde el 2005, sin embargo, presentamos resultados únicamente de años posteriores al 2008 pues las tasas de actividad económica, desempleo e informalidad no tuvieron cambios drásticos entre 2005 y 2008. 

Una de las primeras gráficas que nos van a dar un panorama del impacto del COVID-19 en la economía mexicana en el empleo es la que se muestra a continuación: 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~nestorivanmo/30.embed" height="525" width="100%"></iframe>

En esta gráfica se muestran las tres principales tasas que miden el empleo:

1. Tasa de actividad económica: mide el porcentaje de población ocupada con respecto a la población económicamente activa mayor a 15 años
2. Tasa de informalidad: mide el porcentaje de la población ocupada y económicamente activa que tienen como fuente principal de ingreso algo relacionado con un negocio informal
3. Tasa de desempleo: mide la cantidad de personas no ocupadas dentro del total de población económicamente activa mayor a 15 años

El resultado principal de este análisis tiene como conclusión que tanto la tasa de actividad económica como de informalidad se vieron afectadas de la siguiente manera:

- Tasa de actividad económica pasó del  59%  en marzo del 2020 a un  47%  en abril del 2020. Este periodo de tiempo coincide con la etap de la primer ola de COVID-19
- Por otro lado, la tasa de informalidad pasó del  55 %  al  47%  de marzo a abril del 2020

Esta disminución tan rotunda en estas dos tasas nos indican que el COVID-19 afectó de manera considerable el empleo en México. Observar que la tasa de actividad económica haya disminuido 10 puntos porcentuales nos habla que aproximadamente 4,300,000  personas dejaron de producir ingresos. 

Por otro lado, la tasa de desempleo, incrmentó del 2.93% en marzo del 2020 a 4.7%  en abril del mismo año. En números concretos, en marzo del 2020 existían 1,686,000 personas sin trabajo, para abril del 2020, esta cifra se incrementó a 2,123,000. Este resultado es dramático porque gran parte de los mexicanos trabajan en empleos que se vieron fuertemente afectados por la pandemia, como lo son micronegocios que se vieron obligados a cerrar. 

Otro aspecto fundamental que nos ayuda a entender el impacto del COVID-19 en el empleo mexicano es la cantidad de empleadores y distribución de los empleados mexicanos por número de salarios mínimos. Los resultados de este análisis se encuentran en la siguiente gráfica: 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~nestorivanmo/7.embed" height="525" width="100%"></iframe>

Lo que podemos observar es que la pandemia provocada por el COVID-19 impactó con mayor fuerza a las personas cuyos ingresos por hora equivalen hasta 5 salarios mínimos. Aquellas personas que tienen ingresos mayores a 5 salarios mínimos no vieron afectados sus ingresos radicalmente. De nuevo, esto se presenta porque aproximadamente el 55% de los mexicanos tienen un empleo informal y estos empleos son los que se vieron afectados con mayor fuerza. 

Por otro lado, en las cinco gráficas de la izquierda, mostramos la relación que tienen el número de empleadores a nivel nacional, es decir, personas que son dueños o dueñas de algún negocio (pequeño, mediano y grande), contra los salarios. Lo más contundente a mencionar es que existe una relación directa entre la cantidad de empleadores con la cantida de personas cuyo ingreso es de hasta 2 salarios mínimos. La conclusión directa es que al país le conviene incrementar el número de empleadores para generar más riqueza a nivel nacional. Nuestra estimación es que si se incrementa el número de empleadores, la tasa de informalidad podría disminuir y por ende, meno impacto en la economía de los mexicanos. 


## Conclusiones
El enfoque principal de este artículo fue analizar el impacto del COVID-19 en la economía mexicana, tomando como indicadores principales el crecimiento económico y el desempleo. Uno de los resultados que más nos sorprendió encontrar fue que la primer ola de COVID-19 tuvo un impacto más profundo en la economía a diferencia de la segunda ola de COVID-19 en México. 

Aunado a esto, creemos que nuestro entendimiento para el manejo y presentación de las series de tiempo se incrementó sustancialmente pues fuimoos capaces de presentar gráficas muy sintetizadas que combinan varias presentaciones de una serie de tiempo.

Juntando todos estos elementos y un análisis de varias bases de datos (COVID-19, crecimiento económico, ENOE, INEGI), fuimos capaces de entender con mayor detalle el impacto de la pandemia ante nuestra economía. Si bien México es un país en vías de desarrollo y un referente en latinoamerica, la pandemia tuvo un impacto muy fuerte en la vida de millones de mexicanos y mexicanas. Las gráficas presentadas en este reporte esperamos sirvan como una forma más palpable de entender lo que sucedió en 2020 y sobre todo llamar a la reflexión colectiva sobre las medidas económicas que se deben de realizar en el país para la mejora colectiva.


## Referencias

- García Huitrón, A., González Esquinca, K. D. (2020, marzo 20). Los efectos macroeconómicos del Covid-19 en México. Revista Nexos. Economía y Sociedad. https://economia.nexos.com.mx/los-efectos-macroeconomicos-del-covid-19-en-mexico/#:~:text=Efectos%20macroecon%C3%B3micos%20en%20M%C3%A9xico,en%20la%20producci%C3%B3n%20apenas%20comienza.
- Retamoza Yocupicio, Ricardo Rodolfo. (2021, abril 15). La otra cara del empleo en México: informalidad y subempleo durante el covid-19. Revista Nexos. Economía y Sociedad. https://economia.nexos.com.mx/la-otra-cara-del-empleo-en-mexico-informalidad-y-subempleo-durante-el-covid-19/
- Campos Vázquez, R., Esquivel, G. (2020, mayo 6) Niveles y patrones de consumo en la era del COVID-19. Revista Nexos. https://www.nexos.com.mx/?p=48034
- Esquivel, G. (2020, julio). Los impactos económicos de la pandemia en México. Ciudad de México; Banco de México. https://www.banxico.org.mx/publicaciones-y-prensa/articulos-y-otras-publicaciones/%7BD442A596-6F43-D1B5-6686-64A2CF2F371B%7D.pdf
- Secretaría de Salud. *"Información referente a casos COVID-19 en México"*. Consultado el 12 de junio del 2021 en: https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico
- Instituto Nacional de Estadística y Geografía. *"Encuesta Nacional de Ocupación y Empleo (ENOE), población de 15 años y más de edad"*. Consultado el 12 de junio del 2021: https://www.inegi.org.mx/programas/enoe/15ymas/
- Instituto Nacional de Estadística y Geografía. *"Banco de Información Económica (BIE)"*. Consultado el 14 junio del 2021 en: https://www.inegi.org.mx/app/indicadores/?tm=0&t=10200034#D10200034

