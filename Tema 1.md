# Ciclo de vida de un Sofware

1. Define "Ciclo de vida del software".

   Es la disciplina y metodología establecida del desarrollo del sofware, hoy en día se considera más apropiado esta terminología que ingeneria de sofware.

   ------

2. Nombra las fases principales del desarrollo de software y explica brevemente que se hace en cada una de ellas.

   ##### Fases del desarrollo del Sofware;

   - Análisis: 

     Se acuerdan las necesidades del cliente sobre el producto y se delimitan los requisitos que se tienen que desarrolla.

     

   - Diseño:

     Divide el producto en diversas partes para que se puedan manejar por separado y puedan diseñarse de manera más rápida y eficiente. También se decide la relación entre los componentes del producto

   - Codificación:

     Se escribe el código fuente del producto y se decide en que lenguaje se va a codificar el producto. Será el más apropiado para ese producto, tanto si es Java, C-Sharp o JavaScript.

   - Prueba:

     El objetivo real es que el código no funcione bien para así subsanar los posibles errores del codigo y hacer una entrega sin bug al cliente.

   - Mantenimiento:

     En momentos puntuales hay que rehacer el desarrollo ya hecho para realizar cambios debido a la explotación del sofware
     
     

   ------

3. Explica brevemente en qué consiste el modelo en cascada cuando hablamos de desarrollo de software.

   ###### Tipo de modelo en cascada

   Es el modelo de mayor antigüedad que se usa en el entorno laboral, es lineas y ordena las fases de desarrollo de la manera que hemos denominado más arriba. Único sentido  del desarrollo, no admite cambios por parte del cliente. Hay modelos con mayor o menor cantidad de actividad.

   ------

4. Ventajas e inconvenientes del modelo en cascada.

   *No encuentro ninguna ventaja a un modelo desfasado, que no permite cambios y de jerarquía vertical, a parte no hay equipos multidisciplinarios trabajando, sino que cada departamento trabaja el desarrollo por su cuenta y cuando acaban si hay problemas la cosa es de otro.* 

   ------

5. ¿Qué se entiende por verificación? ¿Y por validación?

   * La validación es cuando el cliente da su visto bueno al desarrollo que se ha hecho y tiene que **pagar** el producto ya finalizado.

   * La validación es cuando el cliente da su **consentimiento** para seguir a delante con el desarrollo del producto, hasta su fiscalización.

     

   ------

6. Explica como funciona el modelo de desarrollo mediante creación de prototipos.

   * Se enseña un primer diseño al cliente para que de su opinión y vea en que estamos trabajando, de este modo hay un feedback y puede a 	ver cambio en los requisitos. Esto se repita tantas veces como sea necesario hasta que el prototipo este a la venta.
   * hay dos tipos de *prototipos*:
   * El prototipo rápido que se puede desatollar el mismo lenguaje o herramienta y finalmente se desecha para acabar vendiendo el proyecto 	en si basado en ese prototipo. (se lanza al mercado lo antes posible para ocupar ese hueco que el proyecto quiere ocupar).
   * El evolutivo, se comporta muy similar que el rápido solo que no busca yenar el hueco de mercado lo antes posible, ya que se crea un        prototipo en el mismo lenguaje o herramienta que el proyecto para después basarse en el y crear el proyecto en esa base.

		 

## Metodologías Ágiles

 **1** KANBAN. Haz un resumen de la metodología Kanban e indica sus diferencias frente a SCRUM. 

* Kambas es una metodología desarrollada por *Toyota* para el control del desatollo de sus productos, se utilizaban post-it para crear se control, pasando por diversos estados, por hacer, elección, en desarrollo, test y por fin hecho ( entregable.) Así siempre se entrega valor al cliente de manera constante.
* SCRUM es una metodologia agil, que utiliza cambas, para que el equipo **auto-gestionable** pueda saber las taras por hacer, las que se estan haciendo y las que estan hechas, se determina un tiempo ideal para casa tarea, y el propietario de esa tarea estima ese tiempo para un tiempo real no mayor de 8h. Sino dividirá esa tare en dos. 

 **2** SCRUM. Explica como funciona Scrum. 

​	*Lo explico en la pregunta anterior 

 **3** SCRUM. Define los siguientes términos:

- Product backlog: *Es un Sprint guía que divide en semanas todos los requerimientos de usuarios, para tener un control de la evolución del proyecto. 
- Sprint backlog  *Son los objetivos prioritarios del sprint*

 **4** SCRUM. En la terminología Scrum qué terminos se utilizan como sinónimo de:

- Jefe de proyecto: *Scrum master*
- Cliente: Scrum: *Product Owne*
- Equipo de desarrollo. *Scrum team*

 **5** SCRUM. Haz un resumen de los requisitos para poder utilizar Scrum. 

	* Método incremental de su desarrollo.
	* División del desarrollo o requerimiento del cliente en Sprint (Valor) que se entrega casa 2/4 semanas. 
	  Estas divisiones no pueden superar las 8h realaes, sino se tienen que dividir.
	* Al principio de cada Sprint se tienen que decir que requisitos son prioritarios para entregar al cliente
	* Cada entrega de valor se hace con una reunion y demostración funcional del valor al cliente que durara unas 4/6 hs
	* En esta metodologia hay una reunion diaria de unos 10 min para ver como va el sprint y que problemas se ha encontrado el equipo. 

 **6** XP. Explica los 5 valores de la Programación Extrema.

* Simplicidad en el código y en la manera de trabajar.	

* comunicación constante entre el equipo y el cliente

	* Reto-alimentación: Se aprende de cada feedback que se optiene del cliente o del usuario
	* Valentía a la hora de promover un código eficiente.
	* Humildad para saber que el código siempre es mejorable y que lo mas corto no siempre lo mejor

 **7** XP. ¿Cuáles son las características distintivas de XP frente a otras metodologías ágiles? Explícalas.

	* Un diseño sencillo del producto, para que pueda ser escalable y versatil
	* Siempre se puede mejorar alguna característica de nuestro producto.
	* Tenemos que hacer test siempre aunque sea unitario para poder saber que todo funciona bien y sino refactorizare
	* Integrar cada pequeña pieza en un proyecto mayor hasta llegar el producto final
	* Siempre se programa en dos en dos uno dice y opina como se hace el código y el otro mira si es posible y se puede mejorar. Los roles se van cambiando.
	* El equipo de trabajo es multidisciplinar e incluso el propio cliente esta integrado en el atravess de las entregas periodicas y escuchando su feedback.
	* El código fuente no es propiedad de un solo individuo, sino de todo el equipo.
	* el equipo tiene que usar siempre los mismos estadares topodos para así hacer una integracion facil.
	* Y los proyectos divididos no superan las cuarenta horas semanalas o las ocho diarias.



# Lenguaje de programación

1. ¿Qué diferencia existe entre los lenguajes declarativos y los imperativos?. Nombra al menos 2 de cada tipo.

   1. decimos el resulresultado que queremos obterner sin indicar los pasos a seguir, sintexis breve y abstracta. (SQL, Prolog )
   2. Decimos de manera mas conciso los pasos a seguir para obtener el resultado, sin ser tan abtracto ni breve(JavaScript, Java)

   ------

2. ¿Explica qué es compilar? ¿Explica qué es interpretar?

   1. Copilar es obtener un paquete con el código verboso que nosotros hemos usado y lo pasa a binario para que la maquina lo interprete,
   2. Interpretar es coger el código que hemos creado que no son mas que ordenes y el interprete, va leyendo de una en una las líneas de ese código ,

   ------

3. Ventajas de los lenguajes compilados.

   1. Los lenguajes copilados, son lenguajes de tipado fuerte algo más seguros que los lenguajes de tipado débil pero no son para nada dinámicos, algunos son poco amables con los que empiezan a programar. Se usan más para la creación de app de escritorio o usa de videojuegos.

   ------

4. Ventajas de los lenguajes interpretados.

   1. Los lenguajes interpretados suelen ser más dinámicos y más débiles de tiempado, buscando un dinamismo y facilidad al programador, se usan normalmente en la creación de app web o web en general. Si es cierto que son menos seguro

   ------

5. Nombra 2 lenguajes compilados y otros 2 interpretados.

   1. c y c++ 
   2. JavaScrip y Php

   ------

6. ¿Puede considerarse código objeto el **bytecode** generado en Java tras la compilación? Explica la respuesta.

   ------

7. Pon un ejemplo de lenguaje de los siguientes tipos:

   - Bajo nivel. Lenguaje Copilador

   - Nivel medio. El lenguaje C

   - Alto nivel. Paython

     ------

8. ¿Qué paradigma de programación siguen los siguientes lenguajes?

   - C *Estructurado*
   - C++ *Multiparadigma*
   - SQL *Algebraico*
   - Java *Multiparadigma*
   - Javascript *Multiparadigma*
   - Lisp *Funcionales*
   - Prolog *Logico*

   Puedes consultar el siguiente enlace:

   - https://es.wikipedia.org/wiki/Paradigma_de_programaci%C3%B3n

     ------

9. Explica qué criterios pueden seguirse a la hora de elegir un lenguade de programación para el desarrollo software.

   1. **Campos de Aplicación**: Debemos tener en cuenta que lenguaje se usa o es más conveniente para el proyecto que vamos a realizar.
   2.  **Experiencia Previa**:  Utilizaremos un lenguaje que ya conozcamos o tengamos facilidad para ello si es posible, dentro de ese campo de aplicación.
   3. **Herramientas de desarrollo:** Considerando el lenguaje final que vamos a usar deberemos tener enceuenta que herramienta es la mas beneficiosa para este proyecto y que IDE'S son los más efectivos
   4. **Documentación Disponible:** Miraremos la documentación que hay de esta herramienta y cuanta comunidad lo utiliza, así será más fácil encontrar documentación veraz y solucionar lo antes posible problemas inesperados con las herramientas elegidas.
   5. **Base de Usuarios:** La comunidad que utiliza este lenguaje y si la documentación esta actualizada a la realidad de hoy en día.
   6. **Reusabilidad:** Siempre tener cuenta la reusabilidad del lenguaje para otros proyectos o para el mismo, sea capaz sobre todo de crear componentes que puedan volver a utilizarse de nuevo.
   7. **Transportabilidad:** Si el lenguaje es capaz de migrar a otro más conveniente o más novedoso que aporte mejoras.
   8. **Imposición del cliente:** Siempre tener en cuenta si el cliente quiere que trabajemos en un lenguaje determinado, si es así intentar mediar y si no se puede aprenderlo lo antes posible con la documentación y la comunidad que exista.
