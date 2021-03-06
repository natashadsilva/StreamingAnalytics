---

copyright:
  years: 2015, 2017
lastupdated: "2017-04-13"

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

#Uso de las aplicaciones de inicio de {{site.data.keyword.streaminganalyticsshort}}
{: #starterapps}

Despliegue y modifique las aplicaciones de inicio y aprenda rápidamente a utilizar el servicio de {{site.data.keyword.streaminganalyticsshort}}:
{:shortdesc}

<table summary="En la primera fila de esta tabla se describe la aplicación de inicio Stock Trades. En la segunda fila, la tabla incluye:
1. En la primera columna, un enlace a un vídeo sobre cómo desplegar la aplicación de inicio Stock Trades. 2. En la segunda columna, un enlace a la descarga directa de la aplicación de inicio Stock Trades.
 ">
  <tr>
    <th colspan="3">App de ejemplo Stock Trades<br></th>
  </tr>
  <tr>
    <td colspan="3">Esta aplicación analiza una secuencia de cotizaciones bursátiles y genera una media móvil de los precios utilizando el operador <a href="https://www.ibm.com/support/knowledgecenter/SSCRJU_4.2.0/com.ibm.streams.toolkits.doc/spldoc/dita/tk$spl/op$spl.relational$Aggregate.html">Aggregate</a>.
Puede ejecutar la aplicación de inicio sin ninguna modificación. Si desea experimentar más con el servicio, también puede modificar el código y devolver los cambios al entorno de {{site.data.keyword.Bluemix_short}}. El código fuente completo de la aplicación de inicio <a href="https://github.com/IBMStreams/samples/tree/master/QuickStart/TradesApp">está disponible en GitHub</a>.</p>
</td>
  </tr>
  <tr>
    <td><a href="https://developer.ibm.com/streamsdev/videos/getting-started-streaming-analytics-service-using-trades-starter-application/" target="_blank">DESPLEGAR LA APP</a><br></td>
    <td><a href="https://github.com/IBMStreams/samples/raw/master/QuickStart/TradesApp/starterApp/StockTradesStarterApp.sab" target="_blank">DESCARGAR</a></td>
  </tr>
</table>

*Tabla 1. App de ejemplo Stock Trades*


<table summary="En la primera fila de esta tabla se describe la aplicación de ejemplo Event Detection. En la segunda fila, la tabla incluye:
1. En la primera columna, un enlace a las instrucciones sobre cómo desplegar la aplicación de inicio Event Detection. 2. En la segunda columna, un enlace a guías de aprendizaje sobre cómo utilizar la aplicación de inicio Event Detection. 3. En la tercera columna, un enlace a la descarga directa de la aplicación de inicio Event Detection.
 ">
  <tr>
    <th colspan="3">App de ejemplo Event Detection<br></th>
  </tr>
  <tr>
    <td colspan="3">La app Event Detection se implementa a través del tiempo de ejecución <a href="https://console.ng.bluemix.net/catalog/starters/sdk-for-nodejs/?cm_mmc=dw-_-bluemix-_-ba-bluemix-detect-complex-events-from-data-stream-trs-_-article">{{site.data.keyword.sdk4node}}</a>.
La app proporciona una sencilla IU web para mostrar el estado y los resultados del análisis.
La app Node.js está enlazada con una instancia del servicio de {{site.data.keyword.streaminganalyticsshort}}. La app controla el servicio mediante la API REST de {{site.data.keyword.streaminganalyticsshort}}.
<p>Puede ejecutar la aplicación de inicio sin ninguna modificación.
Si desea experimentar más con el servicio, también puede modificar el código y devolver los cambios al entorno de {{site.data.keyword.Bluemix_short}}.</p>
</td>
  </tr>
  <tr>
    <td><a href="/docs/services/StreamingAnalytics/t_starter_app_deploy.html" target="_blank">DESPLEGAR LA APP</a><br></td>
    <td><a href="http://www.ibm.com/developerworks/library/ba-bluemix-detect-complex-events-from-data-stream-trs/index.html" target="_blank">GUÍA DE APRENDIZAJE</a></td>
    <td><a href="https://hub.jazz.net/git/streamscloud/EventDetection/" target="_blank">DESCARGAR</a></td>
  </tr>
</table>

*Tabla 2. App de ejemplo Event Detection*

<table summary="En la primera fila de esta tabla se describe la aplicación de ejemplo Tráfico en Nueva York. En la segunda fila, la tabla incluye:
1. En la primera columna, un enlace a las instrucciones sobre cómo desplegar la aplicación de ejemplo Tráfico en Nueva York. 2. En la segunda columna, un enlace a guías de aprendizaje sobre cómo utilizar la aplicación de ejemplo Tráfico en Nueva York. 3. En la tercera columna, un enlace a la descarga directa de la aplicación de ejemplo Tráfico en Nueva York.">
  <tr>
    <th colspan="3">App de ejemplo NYC Traffic<br></th>
  </tr>
  <tr>
    <td colspan="3">La app de inicio NYC Traffic es una aplicación de {{site.data.keyword.Bluemix_short}} que está escrita en Liberty for Java. Contiene una aplicación de {{site.data.keyword.streamsshort}} que recupera datos públicos de los sensores de tráfico de la ciudad de Nueva York, calcula estadísticas globales y devuelve los resultados a la aplicación Liberty.
<p>Puede ejecutar la aplicación de inicio sin ninguna modificación. Si desea experimentar más con el servicio, también puede modificar el código y devolver los cambios al entorno de {{site.data.keyword.Bluemix_short}}.</p>
</td>
  </tr>
  <tr>
    <td><a href="/docs/services/StreamingAnalytics/t_starter_app_deploy.html" target="_blank">DESPLEGAR LA APP</a><br></td>
    <td><a href="https://developer.ibm.com/streamsdev/docs/bluemix-streaming-analytics-starter-application/" target="_blank">GUÍA DE APRENDIZAJE</a></td>
    <td><a href="https://hub.jazz.net/git/streamscloud/NYCTraffic/" target="_blank">DESCARGAR</a></td>
  </tr>
</table>

*Tabla 3. App de ejemplo NYC Traffic*
