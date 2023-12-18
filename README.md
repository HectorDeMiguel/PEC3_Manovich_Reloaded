


#PEC3_Manovich_Reloaded

CASOS DE HIBRIDACIÓN

  

Fecha: 18/12/2023

Autor: Héctor de Miguel

  

## Planteamiento

Después de haber indagado en la evolución de los medios y como el metamedio ordenador ha cambiado la forma en la que nos relacionamos con la creación y difusión de contenido de todo tipo gracias a aquello que Lev Manovich describe como la remediación, veremos como el metamedio ordenador, más allá de ser un contenedor de medios, se trata de un gran conjunto de pequeños componentes que se unen para crear híbridos. Este concepto de hibridación según L. Manoveich, *"es la consecuencia de la digitalización de medios preexistentes mediante software (finales de los 1970)"* y que dieron paso a nuevas técnicas informáticas para la generación y edición de “nuevos” medios. Para esclarecer estos conceptos lo resumiré en dos ejemplos concretos como Autotune respecto al “audio processing” y Mocha como pretexto del video tracking.


## Autotune, Vocaloid y la producción musical.

Autotune nació a manos de Andy Hildebrand, geofisico dedicado al desarrollo de algoritmos para la interpretación de ondas sísmicas, mientras trabajaba en la empresa petrolifera Exxon. Es decir, la finalidad principal de su desarrollo de código estaba enfocado en la detección de yacimientos petroliferos. Hildebrand observó que dichos algoritmos le permitían analizar detectar y modificar el tono de archivos de audio. No fué hasta el momento en el que le presentó su trabajo a un amigo, donde se bromeó sobre cómo ese software podría hacer cantar bien a una de sus parejas.

En el medio digital la hibridación toma total sentido cuando una herramienta o entorno se toma como base para otra actividad para la que no había estado ideada en un principio. Y en ese sentido autotune nace de la propia hibridación. Pero este concepto va más allá de un aspecto meramente técnico, la utilización de estos nuevos medios nos ha de traer una nueva forma de hacer las cosas, una creatividad que emana de la propia hibridación.

En un principio, Auto-Tune estaba ideado para corregir discretamente leves fallos de afinación en la voz humana, para ayudar en la grabación de voces en producciones musicales, ya que la afinación es un tema crucial en el aspecto artístico y emocional del medio musical. La vuelta de tuerca vino en su implementación a nivel comercial, donde la artista y cantante Cher, utilizó este plug-in de forma exagerada sobre su voz, ya que a nivel tonal no necesitaba corrección, en el tema “Belive”. El empleo bajo parametros exagerados causando un efecto de sonido nunca antes escuchado causó un gran revuelo, y a partir de entonces este recurso estilístico se llamó popularmente el “efecto Cher”.

![Interface de Auto-Tune]([https://images.app.goo.gl/rpx7wDCWxYGPQYrWA](https://everythingrecording.com/wp-content/uploads/2015/02/66_1_AT8_Auto.png))

Su uso se popularizó a finales de la década del 2000 donde el artista de hip-hop T-Pain hizo un uso generalizado en sus creaciones de esta herramienta. Tal era su vinculación al uso de Auto-Tune que tenía una app para iPhone (otro caso de hibridación) llamada “I am T-Pain” para simular su voz. Por otro lado, Tom Yorke, cantante de Radiohead, utilizo dicho software para otorgar musicalidad a un archivo donde simplemente se estaba recitando un texto. Autotune, como programa, busca de forma indiscriminada la musicalidad de aquello que se le introduce.

Estos son algunos ejemplos de cómo estos medios híbridos pueden llegar a influirnos en en la forma en la que nos relacionamos y entendemos los medios y crear nuevos escenarios no solo tecnológicos sinó conceptuales y artísticos.

Como dice Lev Manovich en su libro El software toma el mando:

>Un híbrido puede definir nuevas técnicas de navegación e interacción que funcionan con formatos de medios no modificados. Por otro lado, un híbrido puede definir nuevos formatos de medios, pero utilizar técnicas de interacción/interfaz ya existentes. Un híbrido también puede combinar ambas estrategias, es decir, definir nuevas interfaces/herramientas y nuevos formatos de medios al mismo tiempo.”

Suscribiendo esta afirmación, Autotune pasa a otro nivel cuando se incluye en otros enntornos y se combina con otras herramientas y funcionalidades como pasa con Vocaloid. Este es un software desarrollado por Yamaha a partir de los estudios de Kenmochi Hideki en la unidad de Music Technology de la universidad Pompeu Fabra de Barcelona. Este software lanzado en 2004 permite sintetizar voces a partir de librerías de audio permitiendo crear canciones simplemente introduciendoel texto de la letra y la melodía que se le ha de aplicar. Gracias a diversos efectos se puede añadir vibrato, cambio de dinámica o cambio de tono (auto-tune).

Su forma de operar se basa en la introducción de la melodía mediante la interface de rollo de piano, una suerte “partitura” de piano de varias octavas. Una vez creada la melodia se introduce la letra de forma textual y el motor de síntesis selecciona las muestras adecuadas de la librería y las incorpora al editor. Es decir, se combinan elementos reconocibles para el usuario junto a diferentes herramientas digitales y se acaba generando un nuevo entorno de trabajo que abre un abanico de posibilidades creativas totalmente nuevo.


## Mocha y After effects y los sistemas de trackeo visual

El *trackeo* de movimiento es la técnica mediante la cual se registra  el movimiento de un sujeto o una escena para la posterior integración de contenido visual adherido a ese .

Hay dos tipos de tecnologías por las cuales se puede conseguir esto, cada una de ellas con sus particularidades en el proceso de posproducción audiovisual. Los dos procesos son los siguientes:

  

-   Kernel-based tracking. Que se basa en la localización de un punto en concreto en la escena, mediante una área que define la muestra y otra que define la superficie de rastreo.
    
-   Contour tracking: Se basa en el seguimiento de superficies mediante areas de rastreo de un fotograma al siguiente.

After effects incorpora su propio motor de trackeo basado en Kernel, el cual nos permite no solo traquear un punto en la composición permitiéndonos incorporar elementos gráfios que siguen a un objeto en la escena, sinó que nos permite trackear hasta 3 puntuntos diferentes para poder modificar diversas propiedades (posición, escala y rotación) de esos gráficos que queremos incorporar a la escena, y simular así mayor integración con los posibles movimientos de cámara o del objeto de la escena.

Desde hace años After effects incorpora una segunda herramienta de trackeo mediante kernel, para detectar el punto de vista de la cámara y poder así incorporar elementos en una escena donde la cámara esta en movimiento.

Por otro lado, Mocha (que se incluye como plug-in en After Effects) es un software que se basa en el Contour tracking o trakeo de superficies. Su finalidad pueda parecer la misma, sus aplicaciones pueden diferir, ya que no solo nos sirve para identificar una superficie y aplicar una gráfica a esta, tambien es útil para detectar contornos y rastrear su movimiento a lo largo de la sucesión de fotogramas,  permitiendo así generar animaciones rotoscópicas digitalmente.

El software de trackeo, ya sea basado en kernel o contourn, son una herramienta muy poderosa en si misma, pero cobran su total significado en combinación o reconfiguración con otros medios u otras funcionalidades propias del medio. El trackeo es una recolección de datos a partir de imagenes en movimiento. Lo que hacemos con estos datos con el resto de herramientas que tengamos disponibles es en esencia, hibridación.
 
>La nueva *especie de medios* (...) representa el encuentro de diversas técnicas que anteriormente pertenecian a medios distintos.


Estas técnicas de software que en un principio se utilizaban con una finalidad concreta como es la producción audiovisual, han servido de base para el desarollo de nuevas aplicaciones como es el reconocimiento facial, situar objetos en un entorno de realidad aumentada, o hacer un “face swap” en un autorretrato para redes sociales.

  
  

## Conclusiones

La hibridación es por tanto la propia evolución del entorno digital. Es la combinación del desarrollo digital en pro de la creatividad tanto artística como tecnológica. Aplicar los nuevos conocimientos sobre conceptos que pueden ser tanto pretéritos como disruptivos.

Y esto lo vemos claramente en los dos ejemplos anteriormente mencionados y como han servido y continuan sirviendo como base de nuevos entornos creativos digitales. Gracias al tracking y la modulación de voz, más los nuevos motores de inteligencia artificial, estan surgiendo nuevas tendencias tecnológicas como es el caso del deepfake. Softwares que crean material audiovisual que simula la realidad a partir de imágenes y sonidos que nosotros proporcionamos.

![Video sobre como funciona los softwares de deep fake](https://images.app.goo.gl/TtGUkzPaqNb6Qhc19)https://youtu.be/AmUC4m6w1wo?feature=shared

La falsificación profunda busca la verosimilitud por encima de todo y mientras que esto puede suponer un gran problema ético y moral sobre su uso fraudulento difundiendo información falsa, suplantación de identidad, también es una herramienta que  mediante la cual surgen nuevas posibilidades creativas y de hacer negocio. Por ejemplo, servicios de atención al cliente mejorados, el mecenazgo de modelos virtuales, como es el caso de Aitana Lopez o grupos de música totalmente virtuales como Hatsune Miku o Kizuna AI.

![Concierto de artista virtual Hatsune Miku](https://www.youtube.com/watch?v=jhl5afLEKdo)
  
  
  

### Referencias y Bibliografía

  

* Manovich, Lev. (2013). **El Software toma el mando**. Barcelona: Editorial UOC.

Referencias web
* <https://en.wikipedia.org/wiki/Video_tracking>
* <https://en.wikipedia.org/wiki/Auto-Tune>
* <https://borisfx.com/products/mocha-pro/?product=mocha-pro&host=standalone-plug-ins&purchase-options=new-permanent-license>
* <https://es.wikipedia.org/wiki/Vocaloid>
