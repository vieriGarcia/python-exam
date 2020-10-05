**Prueba de ingreso OpenLab - Grupo de Freelancers y asesorías - Django**

Estimados postulantes, el siguiente examen tiene como objetivo medir sus siguientes capacidades respecto a los requerimientos del grupo de Freelancers y asesorías de OpenLab.

Se evaluará: detalle de respuestas, capacidad, rol que desempeñan (hay espacio por cada rol), manejo de funciones, framework que usen. Deberán crear un FORK de este repositorio y resolver en el readme.me las preguntas así como linkear las resoluciones a los problemas de programación por este medio

1. **Responda las siguientes preguntas sobre las siguientes tecnologías: Docker, git, postman.**

- ¿Sabes que es?
   -> Git: Es un software gestionador de versiones que tiene por finalidad tener un control respecto a distintos cambios que se hagan sobre el código fuente de determinado proyecto de software y coordinar el trabajo del equipo de desarrollo sobre este, facilitando la colaboració de este modo.
   -> Docker: Es una tecnología que tiene por finalidad crear contenedores que faciliten el despliegue de aplicaciones de software haciendo transparente la capa de bajo nivel de los computadores en que se desplieguen.
   -> Postman: Es un software que se utiliza para poder hacer pruebas a distintos servicios de tipo API rest, de modo que se puede crear peticiones al servidor.
- ¿Sabes para qué sirve?
  -> Como mencione, Git se utiliza para mantener un control de versiones del código fuente de proyectos de software colaborativo, Postman para ejecutar pruebas sobre los servicios API rest de alguna aplicación y poder documentar información de dichos servicios, Docker se utiliza para crear contenedores de aplicaciones web y facilitar el despliegue de las mismas.

- ¿Sabes cómo se usa?
  -> Se como usar Git y Postman; sin embargo, respecto a Docker solo tengo nociones teóricas que deseo poner en práctica de la mano de ustedes.

1. **Responda las siguientes preguntas**

- ¿Tienes experiencia en hackatones, concursos, freelancer, laboral?
  -> No tengo ninguna experiencia en hackatones ni concursos; sin embargo, tengo
     cierta experiencia en el campo, en primera instancia estuve trabajando en el
     desarrollo de una aplicación web denominada SISCAE para la biblioteca de la FISI, 
     adicionalmente, posterior a ello estuve trabajando 10 meses en una empresa llamada Odybank bajo modalidad freelance.
     adquirí
- ¿Cuéntanos sobre tu experiencia?
  -> En la experiencia ocurrida en la universidad desempeñé principalmente el rol de 
     analista funcional; sin embargo, tambien desempeñé funciones de desarrollador
     backend y gestor de base de datos. Dicha experiencia me permitió aprender a 
     desarrollar bajo el framework Spring y usando GitLab, además de pulir mis habilidades blandas sobretodo de liderazgo, comunicación y gestión del cambio. Respecto a la experiencia en Odybank, inicialmente desempeñé el rol de desarrollador full stack, tiempo después estuve a cargo de un proyecto para desarrollar un servicio encargado de generar reportes y estadísticas  que pueda reutilizarse en los diversos sistemas de la organización. En esta experiencia reforcé más mi conocimiento de Spring y Spring Boot, uso de herramientas como Postman, SonarQube, desarrollo fronted de igual manera con habilidades blandas como liderazgo, trabajo en equipo, comunicación, entre otros.
- ¿Qué rubro del desarrollar software te gustaría desempeñar?
  - QA
  - Desarrollo
  - Product Owner
  -> De las 3 opciones dadas, tengo mayor preferencia por desempeñar el rol de Product Owner
     ya que si bien me siento capacitado por igual para desempeñar dicho rol como el de desarrollador, el primero se ajusta más a mi proyecto profesional, además que considero tener la empatía que se necesita tener con el cliente como para poder comprenderlo, identificar sus necesidades y ser un digno representate del mismo. Con respecto al rol de QA, si bien tengo ciertas nociones de su función y conozco algunas herramientas que suelen utilizar como SonarQube o Testlink, siento que debo adquirir mayor experiencia aún.
  - ¿Tienes ideas de apps o algo propio que quieras desarrollar? (ya sea como startup o libre para la comunidad)
  -> Efectivamente, tengo planes futuros de llevar a cabo una startup con algunos compañeros
     de la universidad para ofrecer soluciones tecnológicas que puedan ser de utilidad para el sector retail.

**Resuelva las siguientes preguntas en un repositorio aparte y linkealas en tu readme.md**
## Problema 1 - Python: Para los siguientes arreglos

Solución= https://github.com/vieriGarcia/Pregunta-01.git
1. [1,1,1,0,2,1,0,0,2,0,1,0]
2. [1,1,1,0,2,1,0,0,2,0,0,0,1]
3. [0,2,2,2,0,0,0,1,2,1,1,0,0,0]
4. [3,3,3,3,3,3,3,1,0,0,0,1]

Cada arreglo representa una parcela, que tiene en cada posición una regadera. Dicha regadera tiene un valor que representa su alcance, por ejemplo en la parcela: [0,0,0,1] la regadera de la posición &quot;4&quot; puede regar 1 espacio más aparte de su misma ubicación ![](https://res.cloudinary.com/openlab-pe/image/upload/v1601789562/temporal/2.png) .

Nota:

- Cada valor &quot;X&quot; indica que una regadera puede regar una distancia &quot;X&quot; hacia ambas direcciones (Derecha e izquierda) como indica la figura.
- El cero indica que solo se riega así misma.

![](https://res.cloudinary.com/openlab-pe/image/upload/v1601789532/temporal/1.png)

El objetivo de este problema es crear un algoritmo que me indique por cada arreglo presentado, la cantidad mínima de regaderas que se necesita prender para regar toda la parcela.

Si tienen una duda sobre este problema, pueden comunicarse con Edwin Deza al 987645213 y él resolverá sus dudas.

## Problema 2 - Django:

Solución = https://github.com/vieriGarcia/Pregunta-02.git
Hacer un proyecto Django con las siguientes características

- Ruteo:
  - /
    - Debe tener un texto que de la hora del sistema en el siguiente formato: DD-MM-AA - Hora - Segundos
  - /Nosotros
    - lorem ipsum
  - /Servicios
    - 4 Servicios renderizados de manera dinámica
      - Servicio:
        - Nombre
        - Descripción
        - Imagen.
- Ruteo API:
  - /usuarios - GET
    - Listado de 5 usuarios
      - Usuario:
        - Nombres
        - Apellido paterno
        - Apellido materno
        - Edad
  - /usuarios/${id} - GET
  - /crear-usuarios - POST
  - /editar-usuarios/${id} - PUT
  - /borrar-usuarios/${id} - DELETE
- Debe tener un menú con las 4 opciones de las rutas
- Se debe usar una BD SQLite