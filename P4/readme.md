# DIU - Practica 4, entregables

## 1. Introducción

El objetivo de esta práctica  es evaluar nuestro prototipo con usuarios reales aplicando técnicas que nos permitan indagar sobre la experiencia en base al producto diseñado y sobre posibles mejoras.

Para ello, usaremos diversas técnicas como la técnica A/B testing para medir dos prototipos para un producto muy similar y otras técnicas como cuestionario SUS (System Usability Scale) o Eye Tracking.

Para comenzar vamos a partir de dos diseños de web (nuestra propuesta  A y otra práctica de otro compañero de clase asignada al azar denominada B). Vamos a seleccionar un conjunto de usuarios que actuarán como usuarios de estas dos prácticas (A y B), y a continuación, éstos deberán rellenar un cuestionario de usabilidad (encuesta SUS). Por último, se hará una valoración de cuál es la mejor opción a partir de los datos recogidos.

## 2. Caso B asignado
El caso B que se nos ha asignado es el del grupo **DIU2.Padulink**. 

Link del GitHub: https://github.com/VeraJose05/UX_CaseStudy

## 3. Usuarios

Los usuarios reales que se han elegido para participar en este estudio y a los que se les realizarán pruebas futuras son:

| Usuarios    | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| Javier          | H / 51   |  Director    | Media       | Persistente | Windows      | A 
| Cristina         | M / 19   | Estudiante    | Alta        | Extrovertida | Móvil    | A 
| Samuel         | H / 31   | Bombero    | Media/Alta        | Social | Linux    | A 
| Jose Diego          | H / 28   | Trabajador  | Alta        | Introvertido       |Windows       | B 
| Agustín         | H / 64   | Médico     | Baja       | Racional     |Móvil       | B 
| Paula         | M / 35   | Ama de casa     | Media       | Extrovertida     |Móvil       | B 

## 4. Pruebas diseñadas (Basadas en A/B testing)

### 4.1 Eye Tracking

Este estudio de eye tracking se llevó a cabo para analizar el comportamiento de los usuarios mientras realizan una tarea especifica dentro del caso B. Los usuarios escogidos para las pruebas son Agustín y Jose Diego.

La tarea a realizar es la siguiente:
* Acceder a los tallerres disponibles, escoger uno y  finalmente reservarlo.

Los objetivos de este estudio son:

* Identificar áreas de interés (AOI) en las interfaces de usuario.
* Analizar patrones de fijación y movimientos oculares.
* Evaluar la usabilidad de las plataformas en función del comportamiento visual de los usuarios.

Los participantes han realizado este test de unos 20 segundos aproximadamente mediante el uso de la herramienta Gaze Recorder.

#### Resultados del Eye Tracking del caso B:

![EyeTracking](EyeTracking/EyeTracking.png)
![EyeTrackingAreas](EyeTrackingAreas.png)
Somos conscientes de la baja calidad de resolución de la segunda imagen, sin embargo, nos pedía hacernos una cuenta de pago para poder exportar las imágenes con calidad.

#### Conclusiones del test

Con este test hemos comprobado que lo primero en lo que se fijan las personas al entrar al sitio web es el banner para explorar talleres lo cual es algo positivo ya que está es la principal funcionalidad que nos ofrece este sitio.

Más adelante comprobamos que una vez seleccionada la opción de explorar talleres, lo siguiente que nos aparece por pantalla son los talleres recientemente añadidos y los talleres más populares, recibiendo estos últimos la principal atención del usuario.

Una vez seleccionado un taller, nos encontramos con toda la información del taller y las opciones de reserva y descraga en pdf de este. Aqui nos hemos dado cuenta como los usuarios se fijan por igual en toda la descripción del taller. Sin embargo, los botones de reservar y descargar el PDF no reciben mucha atención del usuario hasta que no se tiene la intención de reservarlo, por lo que se concluye que no llaman mucho la atención.

Por último, accedemos a la pantalla para reservar el taller donde se selecciona la fecha y se confirma la compra. Etse apartado está bien diseñado ya que se puede ver como el usuario ha distinguido bien los distintos apartados además de haber identificado claramente el botón de pago.

Finalizamos comentando que ambos usuarios han tardado una media de unos 20 segundos en llegar a la pantalla final por lo que se entiende que es bastante eficiente el sitio en cuanto a navegación y busqueda además de que están bien distribuidos la mayoría de los elementos.


### 4.2 Cuestionario SUS (System Usability Scale Test)

Esta herramienta nos ayudará a medir la usabilidad de los dos casos A y B. Para ello, se presentará a los usuarios un cuestionario de unas 10 preguntas simples. Este cuestionario tiene como opciones de respuesta un valor entre 1 - 5 , que van desde "Completamente en desacuerdo" hasta "Completamente de acuerdo". Las preguntas que aparecen tiene como objetivo estudiar el nivel general de usabilidad del sistema.

Los resultados obtenidos junto a la valoración final son los siguientes:

![Cuestionario SUS](Cuestionario_SUS.png)

#### Conclusiones

* El caso A (el nuestro) ha obtenido una puntuación media de 78/100, lo que deja un SUS Score de "Good" según la escala adjetiva. La valoración final deja un nivel de usabilidad aceptable.
* El caso B (el de otros compañeros de clase) ha obtenido una puntuación media de 67/100, lo que deja un SUS Score de "OK" según la escala adjetiva. La valoración final deja un grado de usabilidad medianamente aceptable.

### 4.3 Checklist de usabilidad

[Completar]

## 5. Usability Report del Caso B

El informe de usabilidad del caso B "Granada Cooking" nos permite ver tanto sus puntos positivos como sus negativos los cuales nos dan la posibilidad de conocer que puntos deben ser mejorados. Dicha aplicación, orientada a personas interesadas en perfeccionar sus habilidades culinarias mediante formación en línea, nos presenta una interfaz clara y sencilla con buenos niveles de contraste, lo cual favorece a la lectura y la navegación. Sin embargo, hemos podido comprobar como algunos botones para realizar determinadas acciones no tienen una buena posición dentro de la página, lo cual puede hacer un poco más complicada la navegación de los usuarios afectando directamente a su satisfacción/experiencia.

Los resultados de los tests de usabilidad, que involucraron a usuarios de diferentes perfiles, revelaron la necesidad de mejorar el diseño y accesibilidad de la plataforma teniendo en mente a aquellos con menos experiencia con las tecnologías. Las técnicas utilizadas, como los estudios de eyetracking , los cuestionarios SUS y los checklist de usabilidad, fueron útiles para descubrir estos puntos e identificar posibles soluciones , como ajustar las posiciónes de algunos botones y mejorar el diseño, lo cual afectará positivamente a la experiencia del usuario.

Para más información ->  [Usability Report](Usability-Report.md)

## 6. Conclusiones

En esta práctica hemos llevado a cabo el estudio de la usabilidad tanto de nuestra aplicación como de la del grupo DIU2.Padulink con su proyecto "Granada Cooking". Para ello hemo usado el método A/B testing junto con la realización de varios test ( eye tracking, cuestionario SUS, checklist de usabilidad) para los que se han reunido a una serie de participantes los cuales son usuarios a los que se les han realizado los diferentes test.

Estos test realizados a los usuarios nos han revelado tantos puntos buenos como partes ha mejores de ambos proyectos. Esto nos ha ayuddo a la hora de planificar futuros cambios con la idea de mejorar la satisfacción y las experiencias de los usuarios.

En cuanto a la distribución del trabajo, nos lo hemos repartido todo de manera equitativa además de que hemos trabajo muy bien sin tener ningun tipo de problema. Apoyandonos entre nosotros cuando teniamos algún tipo de duda o algo no nos quedaba claro.

En definitiva, esta práctica nos ha servido para tener ua idea más precisa y clara sobre el nivel de usabilidad de nuestro proyectos y tener en mente futuros cambios que se puedan llegar a implementar.
