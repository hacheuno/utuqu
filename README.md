UTUQU
-----
Utuqu es una librería para desarrollo frontend, gratuita y libre bajo licencia LGNU/GPL3. El objetivo es una base sólida que permita empezar un proyecto web con lo mínimo imprecindible. Además Utuqu incluye módulos opcionales que ofrecen patrones comunes para el desarrollo rápido de aplicaciones y prototipos.

El objetivo es crear una caja de herramienta versatil para uso personal, aunque estás invitado a usarla y colaborar con tus propias aportaciones.

Esta librería parte de algunas ideas preconcebidas de como debe ser una biblitoteca para el desarrollo de frontal de aplicaciones:

  * Solo usamos clases, para reducir la aparición de problemas de especificidad. ID = poblemas.
  * Clases documentadas en la hoja de estilos, para que el código se explique a sí mismo.
  * Los enlaces los subrallamos para que parezcan enlaces
  * Los ni los componentes ni los elementos tienen color, unícamente aquellos que lo necesiten por su idiosincrasia (ej. botones...)

### Características
Utuqu es una librería creada priorizando el desarrollo partiendo de la vista para pantallas estrechas y tiene como principal característica el uso de propiedades personalizadas que, aunque carece de soporte en el 100% de navegadores, brinda la posibilidad de configurar los ajustes globales en un solo sitio, algo común en algunos preprocesadores.

Otra de sus características es que tanto la documentación como las clases que lo componen están escritas en castellano, la segunda lengua más hablada del mundo. Esto facilita el trabajo y el aprendizaje a aquellas personas hispano-parlantes que prefieren usar su lengua materna.

Utuqu está escrita adaptando filosofias como BEM, ACSS u OOCSS para generar un entorno de trabajo flexible y modular, que permita escojer para cada proyecto solo los componentes o características necesarios, sin sobrecargarlo de código sin uso.

Para reducir al mínimo el uso las dependencias, Utuqu está construido sin preprocesadores, herramientas de linea de comandos ni otras tencnologias aparte de CSS y HTML.

Para facilitar el uso modular de los componentes y características de Utuqu, se ha dividido en varias partes:

 * __Base:__ contiene las características básicas; ajustes globales, cuadrícula, estilos básicos de texto, formularios y una biblioteca de utilidades.

 * __Componentes:__ aquí se encuentran componentes con funcionalidades completas, como los menús, la barra superior o el carrusel en CSS puro. Estós componentes están pensados para que podamos crear nuestros propios módulos.

 * __Módulos:__ está carpeta está vacia por defecto, y tiene como objetivo servir de biblioteca personal de aquellos módulos que generemos a partir de los componentes antes mencionados.

 * __Extensiones:__ contiene extras provenientes de otras librerías de código abierto; una biblioteca de filtros CSS para imágenes o Animate CSS entre otras.

 ## Por hacer
 Cosas se quieren añadir a la bliblioteca:
 - Pestañas-acordeon como las de Foundation 6.3, en CSS puro
 - Imagen de cabecera en pantalla completa
