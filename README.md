<p align="center" id="caratula">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC"><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>SI729 Aplicaciones Open Source | SECCIÓN SW51</strong><br>
    <strong>Profesor: Mori Paiva, Hugo Allan</strong><br>
    <br>INFORME DE TRABAJO FINAL
</p>
<p align="center">
    <strong>Startup: LearnE</strong><br>
    <strong>Producto: LearnE</strong>
</p>

<div>
    <h3 align="center">Integrantes:</h3>
</div>

<div align="center">
     <table>
        <tr>
            <th style="text-align:center;">Integrante</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Orrego Noriega, Jorge David</td>
            <td>u201921734</td>
        </tr>
        <tr>
            <td>Huanaco Huayta, Elizabeth Lucero </td>
            <td>u20211g522</td>
        </tr>
        <tr>
            <td>Guía Carrasco, Pedro Andre </td>
            <td></td>
        </tr>
        <tr>
            <td>nombre</td>
            <td>codigo</td>
        </tr>
        <tr>
            <td>nombre</td>
            <td>codigo</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Setiembre 2024</strong>
</p>



# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 17/08/2024 | Grupo LearnE | Se crea el documento y plantilla de trabajo |


# Project Report Collaboration Insights

**Commits del Informe TB1:**


# Student Outcome

**ABET – EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Elizabeth Huanaco: <br> TB1: <br>La elaboración de User Personas, User Task Matrix y User Journey Mapping ha facilitado una comprensión más profunda de las necesidades de los usuarios a través de una previa coordinación con el equipo y entrevistas. Los Web Applications Wireframes y Wireflow Diagrams han sido clave para presentar la funcionalidad de las aplicaciones, coordinadas con el equipo, de manera clara. En resumen, el proceso de coordinación, las reuniones realizadas y las entrevistas a los usuarios han sido fundamentales para alinear nuestros esfuerzos y asegurar que todas estas actividades se integren eficazmente. <br><br> Jorge Orrego: <br> TB1: <br>  <br><br> Pedro Guia: <br> TB1: <br> La descripción de la Startup nos dejo en claro al momento de identificar la misión y vision que nos proponemos a cumplir durante el proyecto. Las reuniones realizadas fueron parte de este logro.|  TB1: <br><br> | 
| Comunica por escrito con efectividad a diferentes rangos de audiencia.| Elizabeth Huanaco: <br> TB1: <br>La elaboración de User Personas, User Task Matrix y User Journey Mapping ha permitido documentar de manera detallada las necesidades y experiencias de los usuarios, lo que se refleja este informe. Asimismo, la preparación de Class Diagrams y Class Dictionary ha permitido que los detalles del sistema sean presentados de manera comprensible y accesible en este informe escrito. <br><br> Jorge Orrego: <br> TB1: <br>  <br><br> Pedro Guia: <br> TB1: <br> La elaboración del Domain-Driven Software Architecture simplifico los detalles del proyecto, gracias al contexto, contenedor y componente que desarrollaremos. No obstante, al realizar el DDS tenemos la base de datos entidad-relación que permite los detalles del sistema sean entendibles.| TB1: <br><br>  |

# Contenido

1. [Capítulo I: Introducción](#cap1)<br>
   1.1. [Startup Profile](#1.1.)<br>
      1.1.1. [Descripción del startup](#1.1.1.)<br>
      1.1.2. [Perfiles de los integrantes del equipo](#1.1.2.)<br>
   1.2. [Solution Profile](#1.2.)<br>
      1.2.1. [Antecedentes y Problemática](#1.2.1.)<br>
      1.2.2. [Lean UX Process](#1.2.2.)<br>
        1.2.2.1. [Lean UX Problem Statements](#1.2.2.1.)<br>
        1.2.2.2. [Lean UX Assumptions](#1.2.2.2.)<br>
        1.2.2.3. [Lean UX Hypothesis Statements](#1.2.2.3.)<br>
        1.2.2.4. [Lean UX Canvas](#1.2.2.4.)<br>
   1.3. [Segmentos objetivo](#1.3.)<br>
2. [Capítulo II: Requirements Elicitation & Analysis](#cap2)<br>
   2.1. [Competidores](#2.1.)<br>
      2.1.1. [Análisis competitivo](#2.1.1.)<br>
      2.1.2. [Estrategias y tácticas frente a competidores](#2.1.2.)<br>
   2.2. [Entrevistas](#2.2.)<br>
      2.2.1. [Diseño de entrevistas](#2.2.1.)<br>
      2.2.2. [Registro de entrevistas](#2.2.2.)<br>
      2.2.3. [Análisis de entrevistas](#2.2.3.)<br>
   2.3. [Needfinding](#2.3.)<br>
      2.3.1. [User Personas](#2.3.1.)<br>
      2.3.2. [User Task Matrix](#2.3.2.)<br>
      2.3.3. [User Journey Mapping](#2.3.3.)<br>
      2.3.4. [Empathy Mapping](#2.3.4.)<br>
      2.3.5. [As-is Scenario Mapping](#2.3.5.)<br>
   2.4. [Ubiquitous Language](#2.4.) <br>
3. [Capítulo III: Requirements Specification](#cap3)<br>
   3.1. [To-Be Scenario Mapping](#3.1.)<br>
   3.2. [User Stories](#3.2.)<br>
   3.3. [Impact Mapping](#3.3.)<br>
   3.4. [Product Backlog](#3.4.)<br>
4. [Capítulo IV: Product Design](#cap4)<br>
   4.1. [Style Guidelines](#4.1.)<br>
      4.1.1. [General Style Guidelines](#4.1.1.)<br>
      4.1.2. [Web Style Guidelines](#4.1.2.)<br>
   4.2. [Information Architecture](#4.2.)<br>
      4.2.1. [Organization Systems](#4.2.1.)<br>
      4.2.2. [Labeling Systems](#4.2.2.)<br>
      4.2.3. [SEO Tags and Meta Tags](#4.2.3.)<br>
      4.2.4. [Searching Systems](#4.2.4.)<br>
      4.2.5. [Navigation Systems](#4.2.5.)<br>
   4.3. [Landing Page UI Design](#4.3.)<br>
      4.3.1. [Landing Page Wireframe](#4.3.1.)<br>
      4.3.2. [Landing Page Mock-up](#4.3.2.)<br>
   4.4. [Web Applications UX/UI Design](#4.4.)<br>
      4.4.1. [Web Applications Wireframes](#4.4.1.)<br>
      4.4.2. [Web Applications Wireflow Diagrams](#4.4.2.)<br>
      4.4.3. [Web Applications Mock-ups](#4.4.3.)<br>
      4.4.4. [Web Applications User Flow Diagrams](#4.4.4.)<br>
   4.5. [Web Applications Prototyping](#4.5.)<br>
   4.6. [Domain-Driven Software Architecture](#4.6.)<br>
      4.6.1. [Software Architecture Context Diagram](#4.6.1.)<br>
      4.6.2. [Software Architecture Container Diagrams](#4.6.2.)<br>
      4.6.3. [Software Architecture Components Diagrams](#4.6.3.)<br>
   4.7. [Software Object-Oriented Design](#4.7.)<br>
      4.7.1. [Class Diagrams](#4.7.1.)<br>
      4.7.2. [Class Dictionary](#4.7.2.)<br>
   4.8. [Database Design](#4.8.)<br>
      4.8.1. [Database Diagram](#4.8.1.)<br>
5. [Capítulo V: Product Implementation, Validation & Deployment](#cap5)<br>
   5.1. [Software Configuration Management](#5.1.)<br>
      5.1.1. [Software Development Environment Configuration](#5.1.1.)<br>
      5.1.2. [Source Code Management](#5.1.2.)<br>
      5.1.3. [Source Code Style Guide & Conventions](#5.1.3.)<br>
      5.1.4. [Software Deployment Configuration](#5.1.4.)<br>
   5.2. [Landing Page, Services & Applications Implementation](#5.2.)<br>
      5.2.1. [Sprint 1](#5.2.1.)<br>
         5.2.1.1. [Sprint Planning 1](#5.2.1.1.)<br>
         5.2.1.2. [Sprint Backlog 1](#5.2.1.2.)<br>
         5.2.1.3. [Development Evidence for Sprint Review](#5.2.1.3.)<br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#5.2.1.4.)<br>
         5.2.1.5. [Execution Evidence for Sprint Review](#5.2.1.5.)<br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review.](#5.2.1.6.)<br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review.](#5.2.1.7.)<br>
         5.2.1.8. [Team Collaboration Insights during Sprint.](#5.2.1.8.)<br>
6. [Conclusiones](#conclusiones)<br>
7. [Bibliografía](#bibliografía)<br>
8. [Anexos](#anexos) <br>

   
# Capítulo I: Introducción <a name ="cap1">

## 1.1. Startup Profile <a name ="1.1.">

### 1.1.1. Descripción de la Startup <a name ="1.1.1.">
Cuenta con la capacidad de enseñar las materias académicas de forma lúdica, autodidacta y divertida, haciendo uso de herramientas gráficas con el fin de fomentar la creatividad e ingenio de los clientes para comprender el uso de las materias de aprendizaje a futuro académico o laboral. 

Entre las materias principales se encuentra el uso de las matemáticas, estadística, física, biología, lenguaje, entre otros. Así mismo, el usuario podrá visualizar el temario de los cursos que guste llevar. Además, se incorporarán exámenes semanales para tener en cuenta el rendimiento del usuario en el curso.

Será una aplicación con dos planes de suscripción, el primero es de ámbito freemium, esto quiere decir que solo contará con las funciones básicas y podrá llevar un límite de materias. No obstante, habrá un plan mensual que permitirá al usuario tener gran cantidad de herramientas y cursos asignados.


#### 1.1.2. Perfiles de integrantes del equipo <a name ="1.1.2.">

<table align="center" border="1" width="70%" style="text-align:center; border-collapse: collapse;">
  <!-- Huanaco Huayta, Elizabeth Lucero -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="" alt="" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
         Elizabeth Lucero Huanaco Huayta
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
         Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Colocar descripción
    </td>
  </tr>
  <!-- Pedro Andre Guía Carrasco -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="" alt="" style="margin-bottom: 5px;" width="200"/>
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
         Pedro Andre Guía Carrasco
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Colocar descripción
    </td>
  </tr>
  <!--  -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="" alt="" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
         Colocar nombre
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Colocar descripción
  </tr>
  <!-- Pedro Guia -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/perfil.png" alt="perfilPG" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Pedro Andre Guia Carrasco
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Estudio en la Universidad Peruana de Ciencias Aplicadas la carrera de Ingenieria de Software, voy por mi 6° ciclo academico y la razón por la que escogi esta carrera es por el futuro innovador que brindara a la sociedad.
    </td>
  </tr>
  <!-- Jorge David Orrego Noriega -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/JorgeOrrego.png" alt="Jorge David Orrego Noriega" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Jorge David Orrego Noriega
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Estudio actualmente la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas y la razón por la cual me encuentro estudiando esta carrera es porque siempre he tenido un interés particular por la tecnología, con un mayor énfasis en el software.
    </td>
  </tr>
</table>



## 1.2. Solution Profile <a name ="1.2.">

### 1.2.1 Antecedentes y problemática <a name ="1.2.1.">

**Antecedentes:** 

A medida que pasa el tiempo, las maneras en las cuales se está educando a cualquier tipo de estudiante han ido cambiando y, a su vez, adaptándose a las nuevas necesidades de nuestra actual era digital. Es así como las computadoras o equipos similares pasaron de ser parte de ciertas clases en la malla curricular a ser indispensables para poder desarrollarse plenamente en el ámbito académico. Este cambio de paradigma en la educación moderna se vio acelerado por la pandemia del COVID-19 a inicios del 2020, en donde se puso en evidencia la importancia por parte de cualquier institución educativa superior de poseer la infraestructura necesaria para seguir brindando clases.  


Esta tendencia desembocó en el aumento de alumnos matriculados tanto en cursos masivos abiertos en línea (o mejor conocidos como massive open online courses en inglés) de 300,000 a 220 millones desde 2011 hasta 2019 como en modalidades de aprendizaje a distancia en universidades tradicionales en un 92% en el 2020 (Diaz-Infante et al., 2022). Además, se vieron a gran escala los beneficios de las tecnologías de aprendizaje virtual que van desde la mejora de la interacción de los alumnos con las clases hasta la mejora de acceso a nuevas herramientas de aprendizaje para personas que no tienen los recursos para pagar una educación formal tradicional (Haleem et al., 2022).


**Problemática:**

* ¿Qué?: El problema radica en la necesidad de herramientas alternativas para el aprendizaje autónomo que, además de contar con recursos educativos de calidad, también brinde la oportunidad de interactuar y de aprender con tutores a su disposición. 
* ¿Quién?: Los principales afectados son personas que no tienen recursos necesarios para aprender por medios de educación superior (universidades o institutos) junto a los mismos estudiantes de dichas instituciones que requieran de conocimiento extra para desempeñarse mejor en sus estudios. 
* ¿Por qué?: La principal causa de esta problemática es la falta de herramientas virtuales que puedan brindarle al alumno tanto herramientas y material de calidad como el acompañamiento especializado de un tutor durante su periodo de aprendizaje. Esto puede impedir el desarrollo tanto profesional como laboral de varias personas que no tienen un acceso ideal a recursos educativos. 
* ¿Dónde?: Es un desafío que se presenta a un nivel global, más aún cuando se trata de comunidades o regiones con recursos limitados o con acceso restringido a educación de alta calidad. 
* ¿Cuándo?: Este problema se puede dar a lo largo de la vida de un estudiante, ya que siempre va a necesitar expandir y actualizar sus conocimientos. 
* ¿Cómo?: Esta situación es consecuencia tanto de un modelo educativo que no se ha adaptado para el uso eficiente de nuevas tecnologías, como de la falta de promoción de nuevas herramientas virtuales que puedan ayudar con la distribución de la educación a más personas. 
* ¿Cuánto?: A varias empresas de diferentes rubros les está costando encontrar personal calificado para sus puestos de trabajo, lo cual podría resultar en la disminución de la productividad y hasta pérdidas económicas (Diaz-Infante et al., 2022). 


### 1.2.2 Lean UX Process. <a name ="1.2.2.">
#### 1.2.2.1. Lean UX Problem Statements. <a name ="1.2.2.1.">
Hemos podido observar que existe gente con el deseo de seguir aprendiendo tanto en lo académico como en lo laboral. Sin embargo, muchos se enfrentan a la falta de una metodología de enseñanza adecuada o eficaz que facilite la comprensión profunda de las materias. Los métodos tradicionales de enseñanza a menudo no se adaptan a las necesidades individuales de los estudiantes, lo que resulta en frustración, pérdida de interés y una comprensión superficial de los temas. Además, la falta de acceso a recursos de aprendizaje personalizados limita el crecimiento personal y profesional, afectando negativamente las oportunidades en el mercado laboral.
Como consecuencia, no podrían comprender temas posteriores porque no tuvieron bases sólidas de aprendizaje en aquellos cursos académicos. Frente a esta problemática, planteamos la siguiente pregunta:
¿Cómo podríamos promover el aprendizaje de aquellos cursos académicos en las personas autodidactas y didácticas?

#### 1.2.2.2. Lean UX Assumptions. <a name ="1.2.2.2.">

| Business Assumptions | User Assumptions |
| --------------------|-------------------|
| Creemos que nuestros usuarios tienen la necesidad de aprender nuevos temas académicos de una forma más interactiva y autodidacta. | Los usuarios de este producto son personas que ya hayan acabado sus estudios secundarios y deseen aprender más acerca de un tema en específico de una manera interactiva y personalizada. |
| Este problema se puede solucionar por medio de métodos de aprendizaje que tengan en cuenta las necesidades y limitaciones de los alumnos. | Nuestro producto podría encajar como un complemento para el aprendizaje diario de nuestros usuarios, dependiendo de su organización de su estudio académico. |
| Los usuarios serán personas que ya hayan terminado sus estudios secundarios y que deseen aprender más acerca de un tema de manera interactiva y personalizada.| Este producto podrá resolver la falta de conocimiento de nuestros usuarios de cualquier tema que les sea relevante ya sea en su vida profesional o académica. |
| La propuesta de valor #1 de nuestra plataforma que nuestros clientes quieren aprovechar es la oportunidad de poder manejar su ritmo y avance de aprendizaje.| El producto se podrá utilizar en cualquier horario que el usuario crea conveniente, a excepción de las tutorías. Se podrá acceder a la plataforma desde cualquier computadora que cuente con un navegador web.|
| Dado que la plataforma cuenta con planes freemium y premium, el usuario podrá optar por obtener más beneficios si es que se suscribe al plan premium como la habilitación de cursos con un nivel de profundidad más avanzado, tutorías personalizadas, etc.| La características más importantes de nuestra plataforma es que pueda ser accedida por cualquier usuario a cualquier hora del día, el poseer un catálogo amplio de cursos de distintos temas y el contar con tutores que puedan complementar el aprendizaje de nuestros usuarios.|
| Se buscará conseguir la mayoría de nuestros usuarios por medio de márketing digital, además de promocionar nuestros servicios en círculos universitarios o redes sociales.
| Nuestro producto se tiene que dar a conocer como un complemento al aprendizaje de nuestros usuarios y se debería comportar de tal manera que ayude en el entendimiento de nuevos conocimientos.|
| Se conseguirán ingresos a través de las suscripciones premium. | |
| Nuestros competidores principales serán Khan Academy, Platzi y Udemy.| |
| Los venceremos brindándoles a nuestros usuarios tutorías en vivo con un tutor especializado en tema como complemento a los cursos ofrecidos en la plataforma. | |
| El mayor riesgo del producto es la disponibilidad de tutores para la cantidad de usuarios que puedan haber.  | |
| Se solucionará esto con una convocatoria masiva de tutores por medio de redes sociales.| |
|Un supuesto que en caso se pruebe que sea falso pueda causar que el proyecto falle sería la demanda por los servicios ofrecidos en nuestra plataforma. | |

#### 1.2.2.3. Lean UX Hypothesis Statements. <a name ="1.2.2.4.">
- Creemos que al ofrecer una plataforma de aprendizaje autodidacta y lúdica con herramientas gráficas y tutorías personalizadas, mejoramos la comprensión y retención de conceptos académicos en nuestros usuarios. 
Sabremos que esta hipótesis es cierta si vemos un aumento en la tasa de finalización de cursos y un feedback positivo en la satisfacción de los usuarios respecto a la claridad y profundidad de los contenidos.

- Creemos que un modelo de suscripción freemium que ofrezca acceso limitado pero efectivo a recursos educativos incentivará a los usuarios a optar por la suscripción mensual para obtener acceso completo a las herramientas y cursos. 
Sabremos que esta hipótesis es cierta si observamos una tasa de conversión significativa de usuarios del plan freemium al plan mensual, motivados por la necesidad de más recursos para su aprendizaje.
#### 1.2.2.4. Lean UX Canvas. <a name ="1.2.2.4.">

## 1.3. Segmentos objetivo. <a name ="1.3.">
| Conceptos | Segmento Objetivo 1 | Segmento Objetivo 2|
| ---------- | ---------- | ---------- |
| Variables | Personas a partir de 10 a 25 años que estén dispuestos a mejorar su conocimiento en las materias académicas que requieren tanto en la escuela como en la universidad. | Tutores que cuentan con buen registro de enseñanza hacía jóvenes y adultos. |
| Geográfica | Perú | Perú |
| Demográfica | Entre 10 a 25 años de genero masculino o femenino. | De 30 a más con experiencia profesional de genero masculino o femenino. |
| Psicológica | Están motivados por mejorar su rendimiento académico, curiosos, con mentalidad de crecimiento, y abiertos a nuevas formas de aprendizaje. | Están preocupados por la gran responsabilidad de guiar y educar a sus alumnos, reflexionando sobre cómo mejorar su enseñanza y hacer el contenido accesible para todos. |
| Funcion de comportamientos | Actitudes: Positivos hacia el aprendizaje digital, buscan soluciones innovadoras para mejorar su comprensión en diferentes materias. Conocimientos: Familiarizados con el uso de dispositivos tecnológicos, pero pueden tener diferentes niveles de conocimientos previos en materias académicas. | Actitudes: Compromiso con el aprendizaje, demostrando paciencia, empatía, y una disposición a guiar y motivar. Conocimientos: Utiliza sus conocimientos no solo para transmitir información, sino también para diseñar experiencias de aprendizaje significativas.|
||
# Capítulo II: Requirements Elicitation & Analysis <a name ="cap2">
## 2.1. Competidores. <a name ="2.1.">
Khan Academy: 
Es una organización sin fines de lucro dedicada a proporcionar recursos educativos gratuitos en una amplia variedad de materias, como matemáticas, ciencias, economía y más. Su plataforma ofrece videos educativos, ejercicios interactivos y una interfaz fácil de usar que permite a los estudiantes aprender a su propio ritmo. El acceso es completamente gratuito, gracias al financiamiento que recibe a través de donaciones de particulares, fundaciones y empresas. Su contenido está disponible para cualquier persona con conexión a internet y está dirigido a estudiantes de todas las edades, desde nivel primario hasta universitario.

	
Platzi:
Es una plataforma de aprendizaje en línea que se enfoca en desarrollar habilidades tecnológicas, corporativas y creativas. Ofrece una amplia variedad de cursos en áreas como idiomas, programación, marketing, diseño y negocios, todos impartidos por expertos en sus respectivas industrias. Los cursos están diseñados para ser prácticos y directamente aplicables en el entorno profesional. La plataforma ofrece opciones de suscripción mensual o anual, y mantiene una comunidad activa a través de eventos, foros y otras actividades. Está dirigida a estudiantes, profesionales, emprendedores y cualquier persona interesada en aprender de manera autodidacta..
	
Udemy:	
Es una plataforma global de aprendizaje en línea que ofrece cursos en una amplia variedad de temas, que van desde tecnología y negocios hasta desarrollo personal y arte. Los cursos son creados por instructores independientes, lo que da lugar a una gran diversidad en la calidad y el enfoque de los contenidos, con una valiosa influencia de las opiniones de los estudiantes. Los cursos se pueden adquirir de forma individual, aunque también existe un modelo de suscripción pensado para empresas. Está dirigida a cualquier persona que busque adquirir conocimientos específicos o habilidades prácticas en un corto período de tiempo.



### 2.1.1. Análisis competitivo. <a name ="2.1.1.">




### 2.1.2. Estrategias y tácticas frente a competidores. <a name ="2.1.2.">



## 2.2. Entrevistas. <a name ="2.2.">
### 2.2.1. Diseño de entrevistas. <a name ="2.2.1.">


### 2.2.3. Análisis de entrevistas. <a name ="2.2.3.">

## 2.3. Needfinding. <a name ="2.3.">
### 2.3.1. User Personas. <a name ="2.3.1.">
En esta sección, se incluyen las fichas de User Personas que representan arquetipos detallados de los segmentos objetivo definidos para nuestro sitio web. Estos arquetipos se han creado a partir de un análisis de las entrevistas que hemos realizado con usuarios reales y un estudio comparativo de la competencia, con el objetivo de capturar las caracterí­sticas, necesidades, y comportamientos de nuestros usuarios.<br>

<ul>
   <li>
      <p>Profesor</p>
      <img src="assets/user-person-teacher.png" alt="Teacher's user person" title="Teacher's user person">
   </li>
   <li>
      <p>Estudiante</p>
      <img src="assets/user-person-student.png" alt="Student's user person" title="Student's user person">
   </li>
</ul>


### 2.3.2. User Task Matrix. <a name ="2.3.2.">
En esta sección, se presenta el User Task Matrix, que agrupa las principales tareas que los User Personas realizan para cumplir sus objetivos. Los segmentos considerados para este análisis son "Rafael Rojas," un estudiante autodidacta que busca complementar su formación académica con tutorí­as en lí­nea, y "Marcos Rivera," un profesor que utiliza plataformas digitales para impartir clases y gestionar sus materiales educativos. Las siguientes tareas identificadas reflejan las actividades esenciales que estos usuarios realizan independientemente de la existencia de nuestra aplicación web.
<br>

<table border="1" style="text-align: center;">  
  <tr>
    <th style="text-align: center;">Tarea/Persona</th>
    <th colspan="2" style="text-align: center;">Rafael Rojas</th>
    <th colspan="2" style="text-align: center;">Marcos Rivera</th>
  </tr>
  <tr>
    <th></th>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Buscar cursos online</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Buscar materiales online</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Agendar tutorí­as</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar en tutorí­as</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Usar plataformas en lí­nea para las tutorí­as</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Diseñar evaluaciones en línea</td>
    <td>Baja</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Resolver exámenes en lí­nea</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comunicarse con estudiantes o profesores</td>
    <td>Media</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Subir y gestionar materiales educativos a internet</td>
    <td>Media</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Buscar herramientas tecnológicas en internet para realizar tareas</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
</table>

<br>
En el análisis del User Task Matrix, se observan varias tareas clave que son importantes para cada segmento objetivo. Ambos usuarios consideran la búsqueda de materiales online como una tarea de alta frecuencia e importancia, lo que indica que acceder a recursos es esencial para ellos. Además, la participación en tutorí­as es crucial para ambos, aunque el estudiante participa con menos frecuencia en comparación con el profesor y el uso de plataformas en lí­nea para tutorí­as también es vital para ambos, aunque la frecuencia varí­a. Asimismo, la búsqueda de herramientas tecnológicas es una tarea común de alta importancia para ambos. Existen diferencias significativas en tareas especí­ficas. Por ejemplo, el profesor se involucra más en el diseño de evaluaciones en lí­nea y en la subida y gestión de materiales educativos, mientras que el estudiante le asigna menos frecuencia e importancia a estas actividades. Este análisis destaca tanto las necesidades comunes como las especí­ficas de cada usuario, lo cual es crucial para diseñar un sitio web que aborde efectivamente sus requerimientos.

### 2.3.3. User Journey Mapping. <a name ="2.3.3.">
En esta sección se presentan los User Journey Maps, que ilustran el end-to-end journey que experimentan nuestros segmentos objetivo sin la intervención de nuestra solución propuesta. En estos mapas se identifican las etapas, interacciones y puntos de contacto que atraviesan para cumplir sus objetivos educativos. Por un lado, se presenta el recorrido completo que sigue el estudiante, Rafael Rojas, al buscar un curso en una plataforma en lí­nea. Por otro lado, se detalla el recorrido del profesor, Marcos Rivera, al buscar plataformas en línea para publicar un curso y ofrecer tutorí­as.<br>

<ul>
   <li>
      <p>Profesor</p>
      <img src="assets/customer-journey-map-teacher.png" alt="Teacher's customer journey map" title="Teacher's customer journey map">
   </li>
   <li>
      <p>Estudiante</p>
      <img src="assets/customer-journey-map-student.png" alt="Student's customer journey map" title="Student's customer journey map">
   </li>
</ul>


### 2.3.4. Empathy Mapping. <a name ="2.3.4.">

### 2.3.5. As-is Scenario Mapping. <a name ="2.3.5.">




## 2.4. Ubiquitous Language. <a name ="2.4.">

1. **Cursos virtuales:** Son cursos de diferentes materias que se brindan en plataformas de aprendizaje virtual. Cuentan con material como videos, documentos de teoría y/o exámenes periódicos.  
2. **Tutores:** Son profesores que ejercen la labor de orientar al estudiante en una sesión corta y previamente agendada en un tema en específico. 
3. **Alumnos:** Son estudiantes que desean inscribirse en un curso de cualquier plataforma de aprendizaje. Para ello, tendrán que crearse una cuenta en la plataforma. 

# Capítulo III: Requirements Specification <a name ="cap3">
## 3.1. To-Be Scenario Mapping. <a name ="3.1.">




## 3.2. User Stories. <a name ="3.2.">

| Epic/User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------------|--------|-------------|--------------------------|---------------------------|
| HU01 |  Registrar nuevo usuario en la plataforma. | Como nuevo usuario quiero registrarme en la aplicación para luego hacer uso de sus servicios. | **Escenario 1:** El usuario se registra como alumno. <br> <br> Dado que soy un nuevo usuario, cuando inicio el formulario de registro, y elijo la opción de registrarme como alumno, entonces la aplicación creará una cuenta de alumno y me redirigirá a la pantalla principal para alumnos. <br> <br> **Escenario 2:** El usuario se registra como profesor. <br> <br> Dado que soy un nuevo usuario, cuando inicio el formulario de registro, y elijo la opción de registrarme como profesor, entonces la aplicación creará una cuenta de profesor y me redirigirá a la pantalla principal para profesores. |         |
| HU02 |  Buscar nuevos cursos dentro de la plataforma. | Como alumno quiero poder buscar nuevos cursos fácilmente desde la página de inicio de la aplicación para encontrar rápidamente la información que necesite. | **Escenario 1:** El usuario busca contenido por medio de una consulta de búsqueda. <br> <br> Dado que soy un alumno, y me encuentro en la página de inicio de la aplicación luego de haber iniciado sesión, cuando seleccione la barra de búsqueda, y escriba en esta lo que quiera buscar, entonces me redirigirá a una nueva página en la que se muestren los resultados de mi búsqueda. <br> <br> **Escenario 2:**  El usuario busca nuevo contenido por medio de las recomendaciones hechas por la misma aplicación <br> <br> Dado que soy un alumno, y me encuentro en la página principal, cuando me dirija a las recomendaciones personalizadas de la aplicación, entonces podré encontrar contenido que me pueda ser de interés.  |         |
| HU03 | Ver detalles de un curso | Como alumno quiero poder ver los detalles de un curso en específico para saber con más detalle su contenido y profesores que lo dicten. | **Escenario 1:** El alumno selecciona un curso para ver sus detalles. <br> <br> Dado que soy un alumno, y quiera ver los detalles de un curso en particular, cuando lo seleccione dentro de la aplicación, entonces me dará todos los detalles de este. <br> <br> **Escenario 2:** El alumno ve los detalles de los profesores que complementan el curso. <br> <br> Dado que soy un alumno, y me encuentro en la página principal, cuando me dirija a las recomendaciones personalizadas de la aplicación, entonces podré encontrar contenido que me pueda ser de interés.  |         |
| HU04 | Inscribirse en un curso. | Como alumno quiero inscribirme en un curso para poder aprender más sobre un tema en específico. | **Escenario 1:** El alumno se inscribe en un curso <br> <br> Dado que el alumno quiera registrarse en un curso luego de haber visto sus detalles, cuando el alumno seleccione la opción de inscribirse en un curso, entonces la plataforma registrará como inscrito al alumno en el curso y se podrá acceder al contenido de este. <br> <br> **Escenario 2:** El alumno cancela su inscripción en el curso <br> <br> Dado que el alumno ya se inscribió en un curso, y este desee cancelar su inscripción al mismo, cuando el alumno seleccione la opción de cancelar su inscripción al curso, entonces la aplicación removerá el curso de su lista de cursos activos.  |         |
| HU05 | Ver descripción de la plataforma en la landing page | Como visitante de la landing page quiero visualizar un breve y llamativo resumen del funcionamiento de la plataforma para así tener una mejor idea de los beneficios que me pueda brindar. | **Escenario 1:** El visitante logra conocer el propósito de la aplicación. <br> <br> Dado que el visitante se encuentra viendo el contenido de la landing page, cuando este lea la descripción de la aplicación y de los servicios que se ofrecen, entonces el visitante tendrá una idea clara de cómo la aplicación le puede beneficiar personalmente. <br> <br> **Escenario 2:** El visitante no logra conocer el propósito de la aplicación. <br> <br> Dado que el visitante se encuentra viendo el contenido de la landing page, cuando esté lea la descripción de la aplicación y de los servicios que se ofrecen, y no entienda con exactitud el propósito y los beneficios de la aplicación, entonces el visitante no se verá interesado en la aplicación.|         |

## 3.3. Impact Mapping. <a name ="3.3.">


## 3.4. Product Backlog. <a name ="3.4.">

| #Order | User Story ID | Título | Descripción | Story Points |
|--------|---------------|--------|-------------|--------------|
|        |               |        |             |              |

# Capítulo IV: Product Design <a name ="cap4">
## 4.1. Style Guidelines. <a name ="4.1.">
### 4.1.1. General Style Guidelines. <a name ="4.1.1.">

#### Color Palette

Se eligió una paleta de colores con tonalidades que van desde el púrpura hasta el rosado con el objetivo de transmitir seguridad y confianza en el usuario. Además, 

<img src="assets/ColorPalette.png" alt="Color Palette" title="Color Palette" style="width:40%;">

#### Tipografía 

La tipografía implementada será Bahnschrift dado que es claramente legible en cualquier tamaño de texto, sea un título o parte del cuerpo de un párrafo. Además, sus caracteres curvilíneos reflejan la calma y poca rigidez de nuestro producto. 

Para textos largos se hace uso de Bahnschrift light y para subtítulos Bahnschrift Condensed se consideran las demás variables de Bahnschrift. 

<img src="assets/Tipografia.png" alt="Tipografia" title="Tipografia" style="width:40%;">

#### Branding 

Nuestro logotipo fue hecho con los colores presentados en la paleta de colores, haciendo el uso de morado como el color principal. El sombrero de graduación o también conocido como un birrete expresa la realización que el alumno pueda sentir a la hora de completar satisfactoriamente un curso, además de señalar que nuestra aplicación va dirigida al rubro de aprendizaje. 

<img src="assets/Logo.jpeg" alt="Logo LearnE" title="Logo LearnE" style="width:40%;">

### 4.1.2. Web Style Guidelines. <a name ="4.1.2.">



## 4.2. Information Architecture. <a name ="4.2.">
### 4.2.1. Organization Systems. <a name ="4.2.1.">
En esta sección el equipo explica en qué grupos de información aplicará cuáles 
sistemas de organización.

1. Categorización Temática 
   - Organizar los contenidos de cada curso como matemáticas, fisica, lenguaje, programación, etc.
2. Niveles de Dificultad
   - Clasificar los contenidos en diferentes niveles de dificultad, desde principiante hasta senior.
3. Perfiles de Usuario
   - Permitir a los usuarios crear perfiles personalizados con información sobre su nivel de habilidad y preferencias de aprendizaje.
4. Seguimiento del Progreso
   - Registrar el progreso individual de los usuarios, incluyendo lecciones completadas y ejercicios resueltos.
5. Sistema de Personalización (Premium)
   - Ofrecer opciones de personalización para suscriptores, permitiéndoles adaptar la experiencia de aprendizaje a sus preferencias.
6. Logros
   - Implementar un sistema de logros para motivar a los usuarios a seguir aprendiendo y alcanzar hitos.

### 4.2.2. Labeling Systems. <a name ="4.2.2.">


### 4.2.3. SEO Tags and Meta Tags <a name ="4.2.3.">


### 4.2.4. Searching Systems. <a name ="4.2.4.">


### 4.2.5. Navigation Systems. <a name ="4.2.5.">


## 4.3. Landing Page UI Design. <a name ="4.3.">
### 4.3.1. Landing Page Wireframe. <a name ="4.3.1.">

<img src="assets/LandingPageWF1.png" alt="Landing Page WF1" title="Landing Page WF1">

<img src="assets/LandingPageWF2.png" alt="Landing Page WF2" title="Landing Page WF2">


### 4.3.2. Landing Page Mock-up. <a name ="4.3.2.">

<img src="assets/LandingPageMK1.png" alt="Landing Page MK1" title="Landing Page MK1">

<img src="assets/LandingPageMK2.png" alt="Landing Page MK2" title="Landing Page MK2">


**Enlace para ver el Figma:** https://www.figma.com/design/hnp3YEhTSCtPJYefiEQyfm/LearnE-Landing-Page?node-id=0-1&t=F1hZNoovfjKbmniN-1 

## 4.4. Web Applications UX/UI Design. <a name ="4.4.">
### 4.4.1. Web Applications Wireframes. <a name ="4.4.1.">

### 4.4.2. Web Applications Wireflow Diagrams. <a name ="4.4.2.">

### 4.4.3. Web Applications Mock-ups. <a name ="4.4.3.">


### 4.4.4. Web Applications User Flow Diagrams. <a name ="4.4.4.">


## 4.5. Web Applications Prototyping. <a name ="4.5.">

## 4.6. Domain-Driven Software Architecture. <a name ="4.6.">

### 4.6.1. Software Architecture Context Diagram. <a name ="4.6.1.">
<img src="assets/SystemContext.png" alt="Diagrama de Contexto" title="SystemContext" style="width:100%;">

### 4.6.2. Software Architecture Container Diagrams. <a name ="4.6.2.">
<img src="assets/Container.png" alt="Diagrama de Contenedores" title="Container" style="width:190%">

### 4.6.3. Software Architecture Components Diagrams. <a name ="4.6.3.">
- Log/Register
<img src="assets/Component Log_Register.png" alt="Loggin and Register" title="Component_1" style="heigth:150%">

- Library
<img src="assets/Component Library.png" alt="Library" title="Component_2" style="heigth:150%">

- Search
<img src="assets/Component Search.png" alt="Search" title="Component_3" style="heigth:150%">

- Courses
<img src="assets/Component Courses.png" alt="Courses" title="Component_4" style="heigth:150%">

- Suscription
<img src="assets/Component Suscription.png" alt="Suscription" title="Component_5" style="heigth:150%">

- Note book
<img src="assets/Component Note book.png" alt="Note book" title="Component_6" style="heigth:150%">

## 4.7. Software Object-Oriented Design. <a name ="4.7.">

### 4.7.1. Class Diagrams. <a name ="4.7.1.">


### 4.7.2. Class Dictionary. <a name ="4.7.2.">



## 4.8. Database Design. <a name ="4.8.">

### 4.8.1. Database Diagram. <a name ="4.8.1.">


# Capítulo V: Product Implementation, Validation & Deployment <a name ="cap5">

## 5.1. Software Configuration Management. <a name ="5.1.">

### 5.1.1. Software Development Environment Configuration. <a name ="5.1.1.">

### Requirements Management
   1. UXPressia: Es una herramienta de diseño utilizada principalmente para crear user personas, empathy mappings, impact maps, etc. Con esta hemos desarrollado la mayoría de gráficos vistos en los capítulos II y III. Enlace de referencia: <https://uxpressia.com/>
   2. Vertabelo: Plataforma especializada en crear diseños para bases de datos de manera colaborativa. En esta hemos creado nuestro diseño de la base de datos de LearnE. Enlace de referencia <https://vertabelo.com/>
   3. Figma: Plataforma de elaboracion de prototipos y edicion grafica, que usamos principalmente para nuestra Landing Page y Web Aplication, tanto para los Wireframes y los Mock-ups, al igual que para nuestros Wireflow Diagrams. Enlace de referencia: <https://www.figma.com/>
### Software Development
   1. JetBrains WebStorm: Entorno de desarrollo especializado al desarrollo web, usando accesos mas simples de prubas en diferentes navegadores web, como Chrome, Microsoft Edge, Safari y Mozilla Firefox. Usar este IDE nos agrega un valor para el desarrollo de nuestro proyecto dado que nos brinda la posibilidad de ejecutar nuestra aplicación web (frontend) que nos permita ver los cambios al programa en tiempo real cuando se edita el código. Enlace de referencia https://www.jetbrains.com/es-es/webstorm/
   2. IntelliJ IDEA Ultimate: Entorno de desarrollo de software especializado en el desarrollo de aplicaciones con el lenguaje de programación Java. Lo vamos a utilizar a la hora de desarrollar el backend con OpenJDK. Enlace de referencia: https://www.jetbrains.com/es-es/idea/ 
   3. HTML5: Es un lenguaje de etiquetado para paginas web, tambien conocido como HyperText Markup Language. En este caso vamos a utilizar su última versión en la creación tanto de la landing page como del frontend en complemento con otras herramientas. Enlace de referencia: https://www.w3schools.com/html/
   4. CSS: Cascading Style Sheets o CSS es lenguaje de diseño gráfico nos permite complementar a HTML5 para aplicar estilos con más precisión y control. Enlace de referencia: https://developer.mozilla.org/es/docs/Web/CSS
   5. JavaScript: Lenguaje de programacion interpretado y orientado a objetos. Se usará para elaborar la landing page. Enlace de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript
   6. TypeScript: Lenguaje de programación derivado de JavaScript, con la diferencia que este es fuertemente tipado. Enlace de referencia: https://www.typescriptlang.org/ 
   7. Java: Lenguaje de programación oriendado a objetos que utilizaremos en el desarrollo del backend 
   8. OpenJDK: Kit de desarrollo de Java de código abierto que utilizaremos en el desarrollo del backend. Enlace de referencia: https://openjdk.org/ 
   9. MySQL: Motor de base de datos que utilizaremos en el desarrollo de nuestro backend. Se eligió por ser más simple de administrar que otros motores de bases de datos. Enlace de referencia: https://www.mysql.com/ 
    
### Software Deployment
   1. GitHub Pages: Servicio de hosting para páginas web de GitHub que nos permite desplegar de una manera más sencilla, ya que solo tenemos que subir el proyecto a un repositorio sin mucha configuración por nuestra parte para que funcione. Se utilizará para desplegar la landing page. Enlace de referencia: https://pages.github.com/ 
   2. Google Firebase: Servicio de hosting de Google para páginas web que nos permiten desplegar aplicaciones web más complejas. Requiere de una configuración previa por el desarrollador en su proyecto para desplegarlo. Se utilizará para desplegar el frontend de nuestra aplicación web. Enlace de referencia: https://firebase.google.com 
   3. Microsoft Azure: Plataforma de computación en la nube que nos permite desplegar una gran variedad de aplicaciones. En este caso la utilizaremos para desplegar tanto nuestra base de datos MySQL como nuestro backend. Enlace de referencia: https://azure.microsoft.com/es-es/

### Software Documentation and Project Management
   1. Git: Software de control de versiones, pensado en ayudar a la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de una aplicación en desarrollo. Los miembros del equipo podrán acceder a ella a través de servicios como GitHub o desde sus propias computadoras. Enlace de referencia: https://git-scm.com/
   2. Github: Plataforma en la cual podemos alojar nuestros proyectos utilizando el control de versiones de Git. Esto nos facilitará la colaboracion en tiempo real y la revision de nuestros avances del proyecto por parte de cada miembro del equipo. Enlace de referencia https://github.com/
   

### 5.1.2. Source Code Management. <a name ="5.1.2.">

### 5.1.3. Source Code Style Guide & Conventions. <a name ="5.1.3.">


### 5.1.4. Software Deployment Configuration. <a name ="5.1.4.">


## 5.2. Landing Page, Services & Applications Implementation. <a name ="5.2.">

### 5.2.1. Sprint 1 <a name ="5.2.1.">

#### 5.2.1.1. Sprint Planning 1. <a name ="5.2.1.1.">

| Sprint # | Sprint 1 |
|----------|----------|
| Sprint Planning Background |
| Date |  |
| Time |  |
| Location |  |
| Prepared By |  |
| Attendees (to planning meeting) | |
| Sprint Goal & User Stories |
| Sprint 1 Goal |  |
| Sprint 1 Velociy |  |
| Sum of Story Point |  |

#### 5.2.1.2. Sprint Backlog 1. <a name ="5.2.1.2.">



| Sprint # | Sprint 1 |
|----------|----------|
| User Story | WorkItem/Task |

| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-do/In-Process/To-Review/Done) |
|----|-------|----|-------|-------------|--------------------|-------------|------------------------------------------|
| |  |  |  |  |  |  |  |



#### 5.2.1.3. Development Evidence for Sprint Review. <a name ="5.2.1.3.">

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commit on (Date) |
|------------|--------|-----------|----------------|---------------------|------------------|
|            |        |           |                |                     |                  | 

#### 5.2.1.4. Testing Suite Evidence for Sprint Review. <a name ="5.2.1.4.">

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
|            |        |           |                |                     |                  | 



#### 5.2.1.5. Execution Evidence for Sprint Review. <a name ="5.2.1.5.">



#### 5.2.1.8. Team Collaboration Insights during Sprint. <a name ="5.2.1.8.">

| Alumno | Actividad |
|--------|-----------|
| Nombre | Actividad realizada en el sprint 1 |




# Conclusiones y recomendaciones.

## Conclusiones TB1


# Bibliografía

Diaz-Infante, N., Lazar, M., Ram, S., & Ray, A. (2022, July 29). Growth in online education. Are providers ready? McKinsey & Company. https://www.mckinsey.com/industries/education/our-insights/demand-for-online-education-is-growing-are-providers-ready


Día Internacional de la Educación: solo el 30.9 % de jóvenes peruanos logró transitar a la educación superior. (2024, 24 enero). SENAJU - Secretaría Nacional de la Juventud. Recuperado 22 de agosto de 2024, de https://juventud.gob.pe/2024/01/dia-internacional-de-la-educacion-solo-el-30-9-de-jovenes-peruanos-logro-transitar-a-la-educacion-superior/ 


Haleem, A., Javaid, M., Qadri, M. A., & Suman, R. (2022). Understanding the role of digital technologies in education: A review. Sustainable Operations and Computers, 3, 275–285. https://doi.org/10.1016/J.SUSOC.2022.05.004


# Anexos

**Enlace de la landing page:**


**Video Exposición TB1:** 


**Video de las Entrevistas:**
* Link de la entrevista en Youtube: 
* Link de la entrevista en Microsoft Stream: 
