<div style="text-align: center">
  <p align="center">
    <br />
    <img
      src="https://www.upc.edu.pe/static/img/logo_upc_red.png"
      width="100px"
    />
    <br />
    <strong>Universidad Peruana de Ciencias Aplicadas</strong>
    <br /><br />
    <strong>Carrera de Ingeniería de Software</strong>
    <br /><br />
    <strong>Ciclo 202610</strong>
    <br /><br />
    1ASI0572 - Desarrollo de Soluciones IOT
    <br /><br />
    <strong>NRC:</strong> 6770 <br /><br />
    <strong>Profesor:</strong> Prudencio Vidal, Javier Antonio <br /><br />
    <strong>Informe de TB1</strong>
  </p>

  <div style="width: 80%; margin: 0 auto; text-align: center">
    <p>
      <strong>Startup:</strong> LogicNodes 
      <br />
      <strong>Producto:</strong> OmniTrack
    </p>

  <div>
      <strong>Relación de integrantes</strong>
      <br /><br />
      <table style="width: 60%; margin: 0 auto;   text-align: left">
        <thead>
          <tr>
            <th>Código</th>
            <th>Nombre</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>u202216698 </td>
            <td> Rodrigo Alonso, Alcántara Cruz, </td>
          </tr>
          <tr>
            <td> u20191e562 </td>
            <td> Paulo Percy, Quincho Gamarra </td>
          </tr>
          <tr>
            <td> u202210334 </td>
            <td> Adrian Emanuel, Valerio Garcia  </td>
          </tr>
          <tr>
            <td> U202011431 </td>
            <td> Luiggi Jeremy Jouvenel, Antonio Loayza </td>
          </tr>
          <tr>
            <td> u202313397 </td>
            <td> Alejandro Daniel, Oroncoy Almeyda </td>
          </tr>
        </tbody>
      </table>
      <p style="text-align: center">
        <br />
        <strong>Abril 2026</strong>
      </p>
    </div>

  </div>
</div>

<div style="page-break-after: always;"></div>

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
|  1.0    |              |              |                    |
|  1.0.1  |              |               |                   |
|  1.0.2  |              |              |                    |
|  1.0.3    |              |              |                    |

# Project Report Collaboration Insights

En esta seccion se registra la colaboración de todo el equipo durante el desarrollo del informe del proyecto, se adjunta el enlace del repositorio 

| Repository Name | Link |
| :--- | :--- |
| **logic-nodes-report** | [https://github.com/Logic-Nodes/logic-nodes-report](https://github.com/Logic-Nodes/logic-nodes-report) |

# Contenido

_Tabla de contenidos_


- [Student Outcome]
- [Capítulo I: Introducción]
  - [1.1. Startup Profile]
    - [1.1.1. Descripción de la Startup]
    - [1.1.2. Perfiles de integrantes del equipo]
  - [1.2. Solution Profile]
    - [1.2.1. Antecedentes y problemática]
    - [1.2.2. Lean UX Process]
      - [1.2.2.1. Lean UX Problem Statements]
      - [1.2.2.2. Lean UX Assumptions]
      - [1.2.2.3. Lean UX Hypothesis Statements]
      - [1.2.2.4. Lean UX Canvas]
  - [1.3. Segmentos objetivo]
- [Capítulo II: Requirements Elicitation \& Analysis]
  - [2.1. Competidores]
    - [2.1.1. Análisis competitivo]
    - [2.1.2. Estrategias y tácticas frente a competidores]
  - [2.2. Entrevistas]
    - [2.2.1. Diseño de entrevistas]
    - [2.2.2. Registro de entrevistas]
    - [2.2.3. Análisis de entrevistas]
  - [2.3. Needfinding]
    - [2.3.1. User Personas]
    - [2.3.2. User Task Matrix]
    - [2.3.3. User Journey Mapping]
    - [2.3.4. Empathy Mapping]
  - [2.4. Big Picture EventStorming]
  - [2.5. Ubiquitous Language]
- [Capítulo III: Requirements Specification]
  - [3.1. User Stories]
  - [3.2. Impact Mapping]
  - [3.3. Product Backlog]
- [Capítulo IV: Solution Software Design]
  - [4.1. Strategic-Level Domain-Driven Design]
    - [4.1.1. Design-Level EventStorming]
      - [4.1.1.1 Candidate Context Discovery]
      - [4.1.1.2. Domain Message Flows Modeling]
      - [4.1.1.3. Bounded Context Canvases]
    - [4.1.2. Context Mapping]
    - [4.1.3. Software Architecture]
      - [4.1.3.1. Software Architecture System Landscape Diagram]
      - [4.1.3.2. Software Architecture Context Level Diagrams]
      - [4.1.3.2. Software Architecture Container Level Diagrams]
      - [4.1.3.3. Software Architecture Deployment Diagrams]
  - [4.2. Tactical-Level Domain-Driven Design]
    - [4.2.1. Bounded Context: Identity and Access Management]
      - [4.2.1.1. Domain Layer]
      - [4.2.1.2. Interface Layer]
      - [4.2.1.3. Application Layer]
      - [4.2.1.4. Infrastructure Layer]
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.1.6.2. Bounded Context Database Design Diagram]
    - [4.2.2. Bounded Context: _Subscriptions and Billing_]
      - [4.2.2.1. Domain Layer]
      - [4.2.2.2. Interface Layer]
      - [4.2.2.3. Application Layer]
      - [4.2.2.4. Infrastructure Layer]
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.2.6.2. Bounded Context Database Design Diagram]
    - [4.2.3. Bounded Context: _Alerts \& Resolution_]
      - [4.2.3.1. Domain Layer]
      - [4.2.3.2. Interface Layer]
      - [4.2.3.3. Application Layer]
      - [4.2.3.4. Infrastructure Layer]
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.3.6.2. Bounded Context Database Design Diagram]
    - [4.2.4. Bounded Context: _Real-Time Monitoring_]
      - [4.2.4.1. Domain Layer.]
      - [4.2.4.2. Interface Layer.]
      - [4.2.4.3. Application Layer.]
      - [4.2.4.4. Infrastructure Layer.]
      - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.4.6.2. Bounded Context Database Design Diagram]
    - [4.2.5. Bounded Context: _Trip management_]
      - [4.2.5.1. Domain Layer.]
      - [4.2.5.2. Interface Layer.]
      - [4.2.5.3. Application Layer.]
      - [4.2.5.4. Infrastructure Layer.]
      - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.5.6.2. Bounded Context Database Design Diagram.]
    - [4.2.6. Bounded Context: Fleet Management]
      - [4.2.6.1. Domain Layer]
      - [4.2.6.2. Interface Layer]
      - [Controllers principales (HTTP REST)]
      - [4.2.6.3. Application Layer]
      - [4.2.6.4. Infrastructure Layer]
      - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.5.6.2. Bounded Context Database Design Diagram.]
    - [4.2.7. Bounded Context: Profile and Preferences Management]
      - [4.2.7.1. Domain Layer.]
      - [4.2.7.2. Interface Layer.]
      - [4.2.7.3. Application Layer.]
      - [4.2.7.4. Infrastructure Layer.]
      - [4.2.7.5. Bounded Context Software Architecture Component Level Diagrams.]
      - [4.2.7.6. Bounded Context Software Architecture Code Level Diagrams.]
        - [4.2.7.6.1. Bounded Context Domain Layer Class Diagrams.]
        - [4.2.7.6.2. Bounded Context Database Design Diagram]
    - [4.2.8. Bounded Context: Visualization Analytics]
      - [4.2.8.1. Domain Layer]
      - [4.2.8.2. Interface Layer]
      - [4.2.8.3. Application Layer]
      - [4.2.8.4. Infrastructure Layer]
      - [4.2.8.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.8.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.8.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.8.6.2. Bounded Context Database Design Diagram]
    - [4.2.9. Bounded Context: Merchant]
      - [4.2.9.1. Domain Layer]
      - [4.2.9.2. Interface Layer]
      - [4.2.9.3. Application Layer]
      - [4.2.9.4. Infrastructure Layer]
      - [4.2.9.5. Bounded Context Software Architecture Component Level Diagrams]
      - [4.2.9.6. Bounded Context Software Architecture Code Level Diagrams]
        - [4.2.9.6.1. Bounded Context Domain Layer Class Diagrams]
        - [4.2.9.6.2. Bounded Context Database Design Diagram]

# Student Outcome

El curso cumple de manera directa el cumplimiento del Student Outcome 5 definido por ABET - EAC, asegurando que los integrantes logren alcanzar las competencias establecidas

Criterio: La capacidad de funcionar efectivamente en un
equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de
colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** Elaboró el Impact Mapping del Capítulo III para ambos segmentos objetivo (gestores de flota y clientes finales), identificando actores, impactos esperados y entregables alineados a los objetivos de negocio de OmniTrack. <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** Contribuyó a la especificación de requerimientos del proyecto colaborando en la definición del Impact Mapping, estableciendo vínculos claros entre los objetivos del negocio, los comportamientos esperados de los usuarios y las funcionalidades del sistema OmniTrack. <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

LogicNodes es una iniciativa tecnológica emergente conformada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). Nuestra organización nace con el firme propósito de transformar la gestión logística y de seguridad mediante la implementación de soluciones basadas en el Internet de las Cosas (IoT). Nos enfocamos en el desarrollo de sistemas inteligentes que permitan a las empresas optimizar sus procesos operativos, reducir riesgos y garantizar la integridad de sus activos en tiempo real.

Como equipo, LogicNodes combina el rigor técnico con una visión innovadora para enfrentar los desafíos actuales de la industria. Nuestra misión es democratizar el acceso a tecnologías de monitoreo avanzadas, ofreciendo plataformas robustas, escalables y centradas en la experiencia del usuario.

El nombre de nuestra organización es LogicNodes. Este término refleja nuestra identidad central: la convergencia entre el pensamiento lógico de la ingeniería y la arquitectura de nodos interconectados que define a los sistemas IoT.

Bajo el respaldo de LogicNodes, presentamos OmniTrack, una solución integral diseñada para revolucionar la seguridad y el seguimiento de mercancías durante su transporte y almacenamiento. OmniTrack no es solo una herramienta de rastreo, sino un ecosistema inteligente que integra sensores de vanguardia, conectividad en la nube y una interfaz de gestión intuitiva.

El producto permite monitorear variables críticas como la ubicación exacta, el estado de las cerraduras y las condiciones ambientales de la carga. Gracias a su capacidad de respuesta inmediata y análisis de datos, OmniTrack proporciona a los usuarios un control total sobre sus operaciones, mitigando pérdidas y elevando los estándares de confianza en la cadena de suministro.

### 1.1.2. Perfiles de integrantes del equipo

| Foto | Información General |
| :---: | :--- |
| <img src="img/RodrigoAlcProfile.png" width="250" alt="Foto de Perfil"> | **Nombre y Apellidos:** <br> Rodrigo Alonso Alcántara Cruz <br><br> **Código:** <br> u202216698 <br><br> **Carrera:** <br> Ingeniería de Software <br><br> **Información:** <br> Mi nombre es Rodrigo Alonso Alcantara Cruz y tengo 21 años. Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Considero que soy una persona que busca el aprendizaje continuo y siempre intento resolver los problemas de forma rapida y eficaz. Tengo conocimiento en lenguajes de programación. Por lo general siempre intento mejorar mi metodo de estudio para poder expandir mi conocimiento. |


| Foto | Información General |
| :---: | :--- |
| <img src="img/AdrianValProfile.jpg" width="250" alt="Foto de Perfil"> | **Nombre y Apellidos:** <br> Adrian Emanuel Valerio Garca <br><br> **Código:** <br> u202210334 <br><br> **Carrera:** <br> Ingeniería de Software <br><br> **Información:** <br> Mi nombre es Adrian Valerio Garcia y tengo 21 años. Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me interesa el aprendizaje continuo y suelo enfocarme en resolver problemas de manera rápida y eficiente. Disfruto los videojuegos y aprender nuevas tecnologías, además de trabajar en equipo para lograr objetivos en conjunto. Tengo conocimientos en lenguajes de programación y procuro mejorar constantemente mis métodos de estudio para ampliar mis habilidades. |

| Foto | Información General |
| :---: | :--- |
| <img src="pending..." width="250" alt="Foto de Perfil"> | **Nombre y Apellidos:** <br> [pending...] <br><br> **Código:** <br> [pending...] <br><br> **Carrera:** <br> Ingeniería de Software <br><br> **Información:** <br> [pending...] |

| Foto | Información General |
| :---: | :--- |
| <img src="pending..." width="250" alt="Foto de Perfil"> | **Nombre y Apellidos:** <br> [pending...] <br><br> **Código:** <br> [pending...] <br><br> **Carrera:** <br> Ingeniería de Software <br><br> **Información:** <br> [pending...] |


| Foto | Información General |
| :---: | :--- |
| <img src="img/AlejandroOroProfile.jpg" width="250" alt="Foto de Perfil"> | **Nombre y Apellidos:** <br> Alejandro Daniel Oroncoy Almeyda <br><br> **Código:** <br> u202313397 <br><br> **Carrera:** <br> Ingeniería de Software <br><br> **Información:** <br> Mi nombre es Alejandro Daniel Oroncoy Almeyda y soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona proactiva y orientada a la resolución de problemas, con interés en el desarrollo de software y las nuevas tecnologías. Disfruto trabajar en equipo y contribuir activamente en cada etapa de los proyectos. Cuento con conocimientos en programación y procuro mejorar continuamente mis habilidades técnicas y blandas para aportar valor a los equipos en los que participo. |

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

### What (¿Qué?)

El transporte de mercancías sensibles enfrenta un desafío permanente: lograr un seguimiento continuo y confiable de las condiciones reales del cargamento a lo largo de todo el recorrido. No se trata solo de conocer la ubicación del vehículo, sino de detectar eventos críticos como aperturas no autorizadas de puertas, impactos fuertes, vibraciones intensas, variaciones de humedad, exposición a temperaturas inadecuadas, desvíos inesperados o interrupciones en la custodia. La falta de datos objetivos y actualizados sobre estos incidentes provoca daños frecuentes en los productos, pérdidas económicas significativas, conflictos entre los participantes de la cadena logística y un incremento sostenido en los costos operativos. Actualmente, la visibilidad suele reducirse a puntos administrativos básicos (salida y llegada) o a sistemas de geolocalización independientes, dejando importantes áreas sin control respecto al estado físico de la carga y la integridad del embalaje, especialmente durante paradas prolongadas, transbordos o cambios entre operadores. Para industrias como el retail, agroexportación, farmacéutica, pesquera y bienes de consumo masivo, disponer de telemetría completa que incluya condiciones ambientales, eventos de seguridad y registros auditables se ha vuelto indispensable para minimizar mermas, agilizar resoluciones y cumplir con los compromisos de calidad exigidos por clientes y aseguradoras.

### Who (¿Quién?)

Esta situación afecta directamente a dos grupos principales:

Las empresas transportistas y operadores logísticos: Soportan el riesgo económico de perder mercancía, enfrentar reclamos constantes de sus clientes y sufrir deterioro en su imagen por entregas defectuosas.

Los clientes finales: Reciben productos deteriorados, vencidos o, en el caso de medicamentos, con su eficacia comprometida, lo que genera riesgos para la salud y genera desconfianza hacia el servicio.

### Where (¿Dónde?)

El problema se presenta en toda la cadena de suministro, desde el almacén de origen hasta el punto de entrega final. Resulta especialmente grave en rutas de larga distancia (terrestre, aérea o marítima) y en los momentos de transferencia entre vehículos o bodegas, donde el control manual es limitado y más propenso a fallos. La implementación de tecnologías avanzadas de monitoreo es una tendencia mundial que avanza con mayor rapidez en países con infraestructura logística consolidada y un fuerte auge del comercio electrónico.

### When (¿Cuándo?)

La demanda de visibilidad en tiempo real ha crecido de forma notable tras la pandemia de COVID-19, que expuso las debilidades de las cadenas de abastecimiento. El incremento en el traslado de productos médicos y la exigencia de los consumidores por entregas rápidas y transparentes han convertido esta capacidad en un requisito estándar del mercado. Hoy en día, la mayoría de los clientes esperan poder seguir el estado de sus pedidos en cualquier momento, haciendo que la trazabilidad completa deje de ser una opción y se convierta en una expectativa generalizada.

### Why (¿Por qué?)

La raíz del problema radica en la ausencia de información oportuna y precisa. Las empresas no disponen de datos clave sobre temperatura, humedad, vibración o posición geográfica en el instante en que ocurren las anomalías. Esta limitación impide reaccionar de inmediato con medidas correctivas, como ajustar el sistema de climatización, modificar la ruta o alertar al cliente. Sin esta capacidad, las incidencias solo se descubren al final del viaje, cuando el daño ya se ha producido y las pérdidas son inevitables.

### How (¿Cómo?)

En la práctica actual, el monitoreo se basa en métodos dispersos o poco eficientes. Muchas compañías todavía utilizan registradores de datos que solo se revisan al concluir el trayecto, o combinan herramientas separadas (GPS para ubicación y sensores aislados para temperatura) que no interactúan entre sí. Esta falta de integración reduce la capacidad de respuesta, aumenta la probabilidad de errores humanos y dificulta la optimización de rutas, la gestión de riesgos y la entrega de un servicio confiable y de alto nivel.

### How much (¿Cuánto?)
La ausencia de un monitoreo integral genera consecuencias en varios niveles: funcional, operativo y estratégico. Las empresas invierten tiempo y recursos adicionales en resolver incidencias que podrían haberse prevenido. Desde el punto de vista operativo, esto implica mayores primas de seguros y costos derivados del desperdicio de productos. A nivel estratégico, representa una oportunidad clara para diferenciarse en el mercado, fortalecer la lealtad de los clientes y construir una reputación sólida basada en confiabilidad y transparencia.


### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

#### Domain
El proyecto se desarrolla dentro del ámbito del transporte y la logística de carga, enfocándose particularmente en el seguimiento y control de las condiciones de productos sensibles mientras se desplazan de un lugar a otro. En este contexto, contar con datos actualizados y precisos sobre el estado de la mercancía es clave para mantener la trazabilidad, proteger la calidad de los bienes y cumplir con las regulaciones aplicables a la cadena de frío, medicamentos y artículos perecederos.

#### Customer Segments

Empresas transportistas y operadores logísticos: son los responsables de administrar las flotas y asegurar que los productos lleguen en buen estado.
Clientes corporativos y distribuidores de bienes sensibles: necesitan total transparencia, control y pruebas concretas de que el transporte se realizó bajo las condiciones adecuadas.

Ambos grupos requieren información confiable, actualizada en tiempo real y herramientas que les permitan intervenir rápidamente cuando surge algún problema.

#### Pain Points

Ausencia de información inmediata sobre temperatura, humedad, vibración y posición de la carga.
Pérdidas financieras provocadas por fallos en la cadena de frío o manipulaciones incorrectas.
Comunicación poco efectiva entre transportistas y clientes cuando ocurren inconvenientes.
Dificultad para generar registros digitales que permitan auditar las condiciones y determinar responsabilidades.
Dependencia de procesos manuales y desconectados que complican la operación diaria y retrasan las decisiones.

#### Gap

En la actualidad, muchas empresas del sector usan soluciones independientes, como localizadores GPS o sensores de temperatura aislados, que no se conectan entre sí. Esto crea una distancia importante entre los datos que se obtienen y la capacidad real de detectar y resolver problemas de forma oportuna y preventiva.

#### Vision / Strategy

Logic Nodes tiene como objetivo convertir el monitoreo tradicional de cargas en un sistema inteligente, proactivo y totalmente integrado. La estrategia se basa en crear OmniTrack, una plataforma IoT completa que utiliza sensores instalados en los vehículos para capturar información sobre las condiciones ambientales y enviarla a un centro de control que procesa, alerta y presenta los datos de manera clara y en tiempo real. Así, las empresas podrán anticiparse a los riesgos, minimizar pérdidas y generar mayor confianza en sus clientes a través de reportes automáticos y una trazabilidad transparente.

#### Initial Segment
La primera fase de implementación se centrará en empresas de transporte de productos perecederos y farmacéuticos que operan en la zona de Lima Metropolitana. Este grupo se seleccionó porque maneja cargas muy sensibles a cambios ambientales y muestra interés en modernizar sus procesos logísticos, lo que lo convierte en un entorno adecuado para probar tanto la tecnología como el modelo de negocio.


#### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions

- Creemos que en el mercado latinoamericano existe una demanda considerable por soluciones de monitoreo asequibles que midan varios parámetros al mismo tiempo (temperatura, vibración, ubicación y nivel de energía). Lo confirmaremos cuando al menos 15 entrevistas con empresas y el 30% de las respuestas en encuestas muestren interés real en evaluar o implementar la solución.

- Creemos que las empresas estarán dispuestas a pagar una cuota mensual por una herramienta que ayude a reducir pérdidas y fortalecer la confianza de sus clientes. Lo validaremos cuando consigamos al menos 5 cartas de intención que indiquen un precio mensual aceptable.

- Creemos que sensores IoT económicos pueden ofrecer la precisión necesaria para monitorear cadena de frío, vibración, ubicación y consumo de energía. Lo validaremos cuando las pruebas en campo demuestren una exactitud de ±0.5 °C en temperatura, detección confiable de vibración y precisión de GPS dentro de 10 metros en el 95% de las mediciones.

- Creemos que el modelo de pago por suscripción mensual será más atractivo que comprar una licencia de por vida para el segmento objetivo. Lo validaremos cuando al menos el 70% de las decisiones simuladas o cotizaciones prefieran la opción de suscripción.

- Creemos que ofrecer parámetros adicionales como humedad, vibración y detección de volcado aumentará el valor percibido de la solución. Lo validaremos cuando pruebas de precios comparativos muestren que los clientes están dispuestos a pagar al menos 15% más por el paquete completo.

#### Business Outcome Assumptions

- Creemos que disminuir los incidentes relacionados con la cadena de frío reducirá los costos por productos dañados. Lo validaremos cuando se registre una baja de al menos 20% en eventos críticos por mes en comparación con el período anterior.

- Creemos que la visibilidad inmediata ayudará a reducir disputas y acortar el tiempo de cobro. Lo validaremos cuando el indicador de días pendientes de cobro (DSO) baje al menos un 10% después de dos meses de uso.

- Creemos que OmniTrack acelerará el proceso de ventas en el segmento objetivo. Lo validaremos cuando la tasa de conversión de pruebas piloto a clientes de pago supere el 40% y el ciclo promedio de venta no exceda los 60 días.

- Creemos que el servicio logrará mantener a los clientes a lo largo del tiempo. Lo validaremos cuando la tasa de retención mensual sea igual o menor al 3% y el indicador de retención de ingresos netos (NRR) sea igual o superior al 100% a los seis meses.

- Creemos que la solución podrá crecer manteniendo márgenes adecuados. Lo validaremos cuando el margen bruto del servicio alcance al menos el 60% una vez que cada cliente tenga 50 dispositivos activos o más.


#### 1.2.2.3. Lean UX Hypothesis Statements

#### Hipótesis 1

Creemos que lograremos reducir las pérdidas de mercancía en un 25% y mejorar la satisfacción de los clientes en un 30% si las empresas de transporte pueden reaccionar de inmediato ante problemas como ruptura de cadena de frío, humedad fuera de rango o detección de volcado, gracias a un sistema de alertas en tiempo real. Lo confirmaremos cuando los incidentes reportados disminuyan al menos un 25% y el indicador de satisfacción (CSAT o NPS) aumente en 15 puntos o más durante las 8 semanas de prueba piloto, con al menos el 75% de opiniones positivas.

#### Hipótesis 2

Creemos que aumentaremos la eficiencia operativa en un 35% si los gerentes de operaciones pueden identificar y priorizar incidentes en pocos minutos mediante un panel sencillo que muestre el estado completo de toda la flota. Lo confirmaremos cuando el tiempo promedio de respuesta baje de más de 4 horas a menos de 25 minutos y los usuarios logren localizar un vehículo en riesgo en menos de 8 segundos en al menos el 85% de los casos durante las primeras 4 semanas.

#### Hipótesis 3

Creemos que alcanzaremos un 12% de adopción en el mercado objetivo dentro de 12 meses si las empresas pueden seleccionar fácilmente el plan que mejor se adapte a sus necesidades gracias a un modelo de suscripción flexible por niveles. Lo confirmaremos cuando tengamos al menos 120 empresas activas, una tasa de conversión de piloto a cliente de pago superior al 35% y una tasa de cancelación mensual igual o menor al 4%.

#### 1.2.2.4. Lean UX Canvas

<img src="img/LeanUXCanvas.png.png"/>

## 1.3. Segmentos objetivo

### Segmento 1: Empresas Clientes

Estas organizaciones se dedican principalmente a la logística, distribución y producción de bienes sensibles que requieren condiciones especiales durante su traslado. Su principal necesidad es contar con un control preciso y continuo sobre sus cargas para proteger la calidad de los productos, minimizar pérdidas económicas y optimizar sus procesos internos.

Buscan una solución que les permita tener una visión completa y en tiempo real de toda su operación, integrando toda la información relevante en una sola plataforma. De esta forma pueden mejorar la eficiencia operativa, cumplir más fácilmente con las regulaciones del sector y transmitir mayor confianza a sus propios clientes.
Características principales:

Rol: Gerentes de logística, jefes de operaciones, responsables de control de calidad o directores de distribución.

Ubicación: Empresas con sede en zonas de alta actividad logística y con disposición para adoptar herramientas digitales.

Sector de la industria: Alimentos perecederos, productos farmacéuticos, químicos, flores de exportación y otros bienes que exigen un manejo controlado de temperatura, humedad y condiciones ambientales.

### Segmento 2: Clientes Finales

Los clientes finales son las personas o empresas que reciben los productos transportados. Su principal preocupación es la transparencia y la seguridad del proceso de entrega. Necesitan la tranquilidad de saber que la mercancía ha sido manejada correctamente desde su origen hasta su destino final.

Valoran especialmente la posibilidad de verificar por sí mismos el estado de su pedido en cualquier momento, a través de una herramienta sencilla, clara y confiable que les brinde información actualizada sobre las condiciones de transporte.
Características principales:

Edad: Mayores de 18 años.

Ubicación: Principalmente en Lima, Perú.

Nivel Socioeconómico: Medio y medio-alto, con interés en productos de calidad y servicios transparentes.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo

<table>
  <!-- Título -->
  <tr>
    <th colspan="6" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>

  <!-- Motivación del análisis -->
  <tr>
    <td rowspan="2" colspan="1" valign="top"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5" valign="top">
      Realizar este análisis competitivo nos permite identificar las fortalezas, debilidades y estrategias de las soluciones existentes en el mercado de monitoreo IoT para carga sensible. De esta forma, podemos entender mejor las expectativas de los clientes, detectar oportunidades de diferenciación y definir con claridad la ventaja competitiva que OmniTrack debe ofrecer para destacar frente a otras alternativas, especialmente en el contexto latinoamericano donde predominan las medianas empresas de transporte.
    </td>
  </tr>
  <tr></tr>

  <!-- Cabeceras de competidores -->
  <tr>
    <td colspan="2" valign="top"></td>
    <td align="center" valign="top">
      <img src="img/product.png" width="120"/><br/>
      <b>Logic Nodes / Omnitrack</b>
    </td>
    <td align="center" valign="top">
      <img src="img/tive-logo.png" width="120"/><br/>
      <b>Tive</b>
    </td>
    <td align="center" valign="top">
      <img src="img/roambee-logo.png" width="120"/><br/>
      <b>Roambee</b>
    </td>
    <td align="center" valign="top">
      <img src="img/samsara-logo.png" width="120"/><br/>
      <b>Samsara</b>
    </td>
  </tr>

  <!-- PERFIL -->
  <tr>
    <td rowspan="2" valign="top"><b>Perfil</b></td>
    <td valign="top">Overview</td>
    <td valign="top">Plataforma IoT latinoamericana enfocada en monitoreo multi-parámetro (temperatura, humedad, vibración, GPS y detección de volcado) con alertas en tiempo real y modelo de suscripción accesible.</td>
    <td valign="top">Plataforma global de trackers en tiempo real con sensores multi-parámetro para envíos de alto valor.</td>
    <td valign="top">Plataforma de visibilidad supply chain con sensores IoT y analítica predictiva.</td>
    <td valign="top">Plataforma completa de operaciones de flota con monitoreo de temperatura y telemática vehicular.</td>
  </tr>
  <tr>
    <td valign="top">¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Propuesta accesible que asegura la conservación de productos, con Dashboards intuitivos y notificaciones.</td>
    <td valign="top">Alertas instantáneas y alta precisión en condiciones críticas (especialmente pharma y alimentos premium).</td>
    <td valign="top">Analítica predictiva avanzada y visibilidad end-to-end muy robusta.</td>
    <td valign="top">Integración total con gestión de flota (cámaras, seguridad del conductor y eficiencia operativa).</td>
  </tr>

  <!-- MARKETING -->
  <tr>
    <td rowspan="2" valign="top"><b>Perfil de Marketing</b></td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Empresas de transporte, agroexportadores medianos y fármacos.</td>
    <td valign="top">Grandes shippers de pharma, alimentos premium y carga de alto valor a nivel global.</td>
    <td valign="top">Empresas grandes de logística y supply chain con operaciones internacionales.</td>
    <td valign="top">Flotas grandes de transporte y distribución que necesitan control vehicular integral.</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Marketing digital formando alianzas con programas de suscripción y cámaras de seguridad.</td>
    <td valign="top">Marketing global B2B, casos de éxito en pharma y presencia en ferias internacionales.</td>
    <td valign="top">Marketing basado en datos y ROI, campañas de "visibilidad predictiva".</td>
    <td valign="top">Marketing amplio en transporte pesado, énfasis en seguridad y eficiencia de flota.</td>
  </tr>

  <!-- PRODUCTO -->
  <tr>
    <td rowspan="3" valign="top"><b>Perfil de Producto</b></td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Sensores IoT, aplicación web y móvil, dashboards con métricas importantes y alertas en tiempo real para mayor seguridad.</td>
    <td valign="top">Trackers reutilizables con sensores de temperatura, humedad, shock y luz + plataforma en la nube.</td>
    <td valign="top">Sensores IoT + plataforma de visibilidad con IA predictiva.</td>
    <td valign="top">Dispositivos telemáticos, sensores de temperatura, cámaras y software de gestión de flota completa.</td>
  </tr>
  <tr>
    <td valign="top">Precios y costos</td>
    <td valign="top">Suscripciones y costo bajo por equipo.</td>
    <td valign="top">Precio premium por tracker + suscripción anual.</td>
    <td valign="top">Suscripción basada en volumen de envíos.</td>
    <td valign="top">Suscripción por vehículo/flota (más costosa para operaciones pequeñas).</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución</td>
    <td valign="top">Venta directa, alianzas con cámaras de seguridad y distribuidores de logística.</td>
    <td valign="top">Web + App móvil.</td>
    <td valign="top">Plataforma web principal + integraciones móviles.</td>
    <td valign="top">Web + App móvil + integración con sistemas de flota.</td>
  </tr>

  <!-- SWOT -->
  <tr>
    <td rowspan="4" valign="top"><b>Análisis SWOT</b></td>
    <td valign="top">Fortalezas</td>
    <td valign="top">• Accesibilidad y escalabilidad<br/>• Enfoque en empresas de transporte<br/>• Software amigable</td>
    <td valign="top">• Alta precisión y reputación en pharma y alimentos premium</td>
    <td valign="top">• Analítica predictiva muy avanzada</td>
    <td valign="top">• Plataforma muy completa de flota (no solo monitoreo de carga)</td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">• Respaldo de marca frente a multinacionales<br/>• Mercado nicho especializado</td>
    <td valign="top">• Precio elevado para medianas empresas</td>
    <td valign="top">• Enfoque más corporativo y menos accesible para PYMEs</td>
    <td valign="top">• Solución más orientada a flotas grandes que a monitoreo específico de carga sensible</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">• Expansión en LATAM donde grandes competidores no tienen presencia fuerte<br/>• Crecimiento del e-commerce y transporte</td>
    <td valign="top">—</td>
    <td valign="top">—</td>
    <td valign="top">—</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">• Fácil de replicar el modelo por competidores grandes o locales</td>
    <td valign="top">—</td>
    <td valign="top">—</td>
    <td valign="top">—</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Para posicionar a OmniTrack de manera efectiva en el mercado y diferenciarse de competidores establecidos como Tive, Roambee y Samsara, Logic Nodes ha definido una serie de estrategias y tácticas claras enfocadas en las necesidades específicas del segmento de medianas empresas de transporte en Latinoamérica.

### 1. Estrategia de Diferenciación por Accesibilidad y Precio
A diferencia de Tive y Samsara, que tienen precios premium orientados principalmente a grandes corporaciones, OmniTrack adopta un modelo de suscripción mensual accesible y flexible. Esta estrategia permite que las medianas empresas de transporte puedan implementar la solución sin realizar grandes inversiones iniciales, reduciendo la barrera de entrada que presentan los competidores globales.
### 2. Estrategia de Enfoque Regional (LATAM-First)
Mientras que la mayoría de competidores tienen un enfoque global o se centran en mercados maduros de Estados Unidos y Europa, OmniTrack se desarrolla pensando en las particularidades del mercado latinoamericano (infraestructura logística variable, tamaño de flotas medianas y sensibilidad al precio). Se priorizará la localización del idioma, soporte en español y alianzas con cámaras de transporte y asociaciones logísticas locales.
### 3. Estrategia de Simplicidad y Facilidad de Uso
OmniTrack busca destacar por su interfaz intuitiva y onboarding sencillo, reduciendo la curva de aprendizaje. A diferencia de plataformas más complejas como Roambee o Samsara, el enfoque está en que gerentes y conductores puedan usar la plataforma de forma efectiva desde el primer día, sin necesidad de capacitaciones extensas.
### 4. Estrategia de Funcionalidades Específicas para Carga Sensible
Se priorizará el monitoreo multiparámetro (temperatura, humedad, vibración y detección de volcado) con alertas inteligentes y reportes automáticos de trazabilidad. Esta combinación responde directamente a los dolores más comunes de las empresas que transportan alimentos perecederos y productos farmacéuticos, ofreciendo un equilibrio entre profundidad técnica y practicidad que no siempre encuentran en soluciones más generales.
### 5. Estrategia de Alianzas y Ecosistema Local
Se buscará establecer alianzas estratégicas con distribuidores de sensores, empresas de logística y cámaras de comercio en Perú y otros países de LATAM. Esta táctica permitirá acelerar la adopción y generar confianza en el mercado local, algo que los competidores globales suelen tener más dificultad para lograr rápidamente.
### 6. Estrategia de Marketing y Posicionamiento
Se implementará un marketing digital enfocado en casos de éxito locales, demostraciones prácticas y contenido educativo sobre la importancia del monitoreo de cadena de frío. El mensaje principal será: “Monitoreo profesional accesible para empresas medianas que quieren competir con los grandes”


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

### 1. Preguntas generales

¿Cuál es tu nombre y cuál es tu cargo actual?

¿Qué edad tienes?

¿En qué sector o industria trabajas? (alimentos, farmacéutica, logística, entre otros)

### 2. Preguntas — Segmento: Empresa (Gestores de transporte)

¿Cómo controlas actualmente la temperatura de tus productos durante el transporte?

¿Qué dispositivos o sistemas utilizas para el monitoreo de la cadena de frío? ¿Por qué los elegiste?

¿Cómo organizas y registras los viajes de transporte? ¿Qué información consideras más importante registrar?

¿Qué dificultades enfrentas cuando se rompe la cadena de frío? ¿Cómo afecta esto a tus costos y tiempos de operación?

¿Cómo te das cuenta cuando ocurre un problema de temperatura? ¿Qué tan rápido puedes reaccionar ante este tipo de situaciones?

¿Qué tipo de reportes necesitas preparar para tus clientes o para las autoridades regulatorias?

¿Cuál ha sido tu experiencia al gestionar el mantenimiento y configuración de sensores o dispositivos de monitoreo? ¿Qué dificultades has encontrado?

Si pudieras diseñar la plataforma ideal para tu trabajo, ¿qué funciones serían absolutamente necesarias para ti?

¿Qué modelo de pago preferirías para este tipo de servicio? ¿Qué factores influyen en esa decisión?

### 3. Preguntas — Segmento: Clientes Finales (Consumidores finales)

¿Cómo verificas actualmente que los productos que recibes llegaron en las condiciones de temperatura adecuadas?

¿Qué nivel de confianza tienes en los reportes de temperatura que te entregan tus proveedores? ¿Qué elementos aumentarían o reducirían esa confianza?

¿Qué tipo de información te resulta más útil conocer sobre el transporte de tus productos? ¿Cómo te ayudaría esa información en tu día a día?

¿Puedes compartir alguna experiencia en la que hayas tenido que rechazar productos por problemas relacionados con la cadena de frío? ¿Cómo detectaste el problema y qué impacto tuvo?

¿Cómo prefieres recibir y consultar la información sobre tus pedidos? ¿Qué canales o métodos de comunicación te resultan más prácticos?

¿Qué tipo de notificaciones durante el transporte de tus productos serían más útiles para ti y en qué momentos te gustaría recibirlas?

¿Qué tan importante es para ti que la información técnica se presente de forma clara y fácil de entender? ¿Qué características valoras en las interfaces que utilizas?

¿Qué funcionalidades crees que aportarían mayor valor a tu proceso de recepción y validación de productos?

¿Qué beneficios esperas obtener de un sistema de monitoreo basado en IoT para tus compras de productos sensibles a la temperatura? ¿Qué preocupaciones o dudas tienes al respecto?

### 2.2.2. Registro de entrevistas

### SEGMENTO EMPRESA (GESTORES DE TRANSPORTE)

#### ENTREVISTA 1

Entrevistado: Elmer Alcántara (58 años)

Cargo: Gerente de Operaciones en empresa de transporte refrigerado.

<img src="img/elmer-entrevista.png">

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216698_upc_edu_pe/IQCab9COVFqDRZj4fEqtB9h5AfwV7nuQDBlWWBDq9TOKXSU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=sJeec7


### SEGMENTO CLIENTES FINALES

#### ENTREVISTA 1

Entrevistada: Angélica Cruz (54 años)

Cargo: Dueña y administradora de tienda minorista de productos perecederos.

<img src="img/angelica-entrevista.png">


https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216698_upc_edu_pe/IQAiZh8wMly5SbTbqBcDgSRqAQdUbRp4lYrVhYckLbH6_Q0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KXhZ7q


### 2.2.3. Análisis de entrevistas

### SEGMENTO EMPRESA (GESTORES DE TRANSPORTE)

#### ENTREVISTA 1

Entrevistado: Elmer Alcántara, 58 años, Gerente de Operaciones.

Desde la perspectiva de la gestión operativa, Elmer Alcántara describe un entorno de trabajo dominado por métodos tradicionales y fragmentados que limitan la capacidad de respuesta de la empresa. La dependencia de bitácoras físicas en papel y de la comunicación verbal con los conductores genera "puntos ciegos" durante el trayecto, lo que provoca que los problemas de temperatura suelan detectarse de forma reactiva, usualmente cuando el cliente ya está rechazando la carga. Esta falta de monitoreo integrado no solo eleva los costos operativos por el envío de unidades de emergencia, sino que también desgasta la relación con el cliente al no contar con evidencia objetiva en caso de disputas. Elmer identifica como una carga administrativa pesada la elaboración de reportes de cumplimiento, ya que consolidar datos de fuentes desintegradas es un proceso lento y tedioso. Su necesidad principal se centra en la centralización y la automatización: requiere un dashboard intuitivo que monitoree múltiples parámetros (temperatura, humedad y vibración) y que genere reportes automáticos. Finalmente, su decisión de adoptar una nueva tecnología está condicionada por la facilidad de uso ("conectar y usar") y un modelo de pago por suscripción mensual que no exija una inversión inicial elevada, facilitando así la digitalización de su equipo de trabajo.

### SEGMENTO CLIENTES FINALES

#### ENTREVISTA 1

Entrevistada: Angélica Cruz, 54 años, dueña de tienda minorista.

El análisis de la entrevista revela que Angélica Cruz enfrenta una vulnerabilidad crítica debido a la falta de herramientas objetivas para validar la calidad de sus suministros. Actualmente, su proceso de recepción depende enteramente de una inspección sensorial (vista y tacto) de los empaques, lo que resulta insuficiente para detectar rupturas sutiles en la cadena de frío que afectan la vida útil del producto. Esta carencia se traduce en una confianza "moderada" hacia sus proveedores, alimentada por la entrega de reportes que ella califica como genéricos o incompletos. Para Angélica, el impacto de una mala gestión logística no es solo operativo, sino económico, ya que ha sufrido la pérdida directa de ventas y ha encontrado serias dificultades para sustentar reclamos ante sus proveedores al no poseer pruebas verificables. Por ello, su plataforma ideal debe eliminar la incertidumbre mediante visibilidad transparente en tiempo real y alertas que le permitan anticiparse a la llegada de mercadería dañada. Valora la simplicidad extrema en la interfaz, buscando evitar procesos técnicos complejos o capacitaciones largas, y espera que el sistema IoT le brinde la seguridad necesaria para aceptar o rechazar pedidos basándose en datos reales.

## 2.3. Needfinding
### 2.3.1. User Personas

<img src="img/user-persona-1.png" alt="User Persona 1">

Jorge Ramírez es un Gerente de Operaciones experimentado de 44 años que trabaja en una empresa mediana de transporte refrigerado con sede en Lima. Con más de 12 años en el sector logístico, es responsable de gestionar una flota de 35 vehículos dedicados principalmente al traslado de alimentos perecederos y productos farmacéuticos.
Es un profesional práctico y orientado a resultados, que valora el control total de sus operaciones. Su principal preocupación es evitar cualquier tipo de pérdida económica causada por fallos en la cadena de frío. Jorge necesita herramientas simples pero potentes que le permitan monitorear toda su flota en tiempo real, recibir alertas inmediatas y tomar decisiones rápidas sin complicaciones. Aunque está abierto a la tecnología, prefiere soluciones fáciles de implementar que no requieran largas capacitaciones ni procesos complejos.


<img src="img/user-persona-2.png" alt="User Persona 1">

Ana Patricia Torres, de 39 años, es propietaria y gerente de una cadena de tiendas de productos naturales y orgánicos en Lima. Con un enfoque muy cuidadoso en la calidad, depende completamente de proveedores confiables para mantener la frescura de sus frutas, verduras, lácteos y suplementos.
Es una persona detallista y consciente de la importancia de la transparencia en toda la cadena de suministro. Ana Patricia busca tranquilidad al saber que sus productos viajan en condiciones óptimas, ya que cualquier incidente con la temperatura o el manejo de la carga afecta directamente la satisfacción de sus clientes y la rentabilidad de su negocio. Valora enormemente la posibilidad de verificar el estado de sus pedidos de forma sencilla y en tiempo real, ya que esto le permite generar mayor confianza con sus compradores finales y reducir riesgos innecesarios.


### 2.3.2. User Task Matrix

### Segmento: Empresas Clientes

| Tarea | Frecuencia | Importancia |
|-------|-----------|-------------|
| Llamar a conductores para verificar condiciones de carga manualmente | Alta | Alta |
| Revisar múltiples parámetros (temperatura, humedad, vibración) al final del viaje | Alta | Alta |
| Completar bitácoras en papel con datos de condiciones del cargamento | Alta | Media |
| Buscar información de viajes en múltiples sistemas desintegrados | Alta | Media |
| Coordinar por teléfono cuando hay incidencias en las condiciones de transporte | Media | Alta |
| Recopilar firmas y documentos físicos de entregas | Alta | Media |
| Armar reportes manuales combinando datos de diferentes fuentes | Media | Alta |
| Enviar unidades de emergencia cuando se detecta falla en el transporte | Baja | Alta |
| Atender consultas de clientes por falta de visibilidad en tiempo real | Media | Alta |
| Revisar rutas en GPS básico sin integración con sensores de carga | Alta | Media |
| Capacitar conductores en procedimientos de verificación de carga | Baja | Media |
| Verificar manualmente el funcionamiento de sistemas de conservación | Alta | Alta |
| Consolidar información de múltiples dispositivos y plataformas | Alta | Alta |


### Segmento: Clientes Finales

| Tarea | Frecuencia | Importancia |
|-------|-----------|-------------|
| Verificar productos visualmente al recibirlos | Alta | Alta |
| Inspeccionar condiciones físicas de productos sensibles | Alta | Alta |
| Llamar al proveedor para preguntar estado del envío | Media | Media |
| Examinar empaques buscando señales de deterioro o daños | Alta | Alta |
| Rechazar productos que muestran signos de mal manejo | Media | Alta |
| Solicitar reportes de trazabilidad que suelen ser genéricos o incompletos | Media | Alta |
| Esperar sin información sobre el estado real de sus pedidos | Media | Alta |
| Revisar fechas de vencimiento y condiciones de almacenamiento | Alta | Alta |
| Registrar incidencias de productos que llegan en mal estado | Baja | Alta |
| Aceptar productos sin evidencia objetiva de las condiciones de transporte | Alta | Media |
| Realizar reclamos por productos deteriorados o fuera de especificación | Baja | Alta |
| Archivar documentación física de entregas | Media | Baja |
| Validar cumplimiento de condiciones especiales sin datos verificables | Alta | Alta |


### 2.3.3. User Journey Mapping

<img src="img/journey-mapping-1.png">

Este journey representa el proceso diario de Jorge Ramírez, Gerente de Operaciones de una empresa mediana de transporte refrigerado. Muestra cómo actualmente planifica, monitorea y documenta sus viajes de carga sensible. Se evidencia una fuerte dependencia de métodos manuales y comunicación verbal, lo que genera falta de visibilidad en tiempo real, respuestas reactivas ante incidentes y dificultad para analizar patrones de riesgo. OmniTrack busca transformar este flujo en un proceso digital, proactivo y centralizado.

<img src="img/journey-mapping-2.png">

Este journey representa el proceso de Ana Patricia Torres, propietaria de una cadena de tiendas de productos naturales. Muestra cómo actualmente solicita, sigue y recibe sus pedidos de insumos sensibles. Actualmente depende de promesas verbales y verificaciones subjetivas, lo que genera incertidumbre, riesgo de recibir productos en mal estado y dificultad para reclamar. OmniTrack le permitiría tener visibilidad transparente y evidencia objetiva, aumentando su confianza en los proveedores.

### 2.3.4. Empathy Mapping

A continuación se presentan los Empathy Maps de ambos segmentos objetivo. Cada mapa resume lo que el usuario dice, piensa, hace y siente en su interacción diaria con el proceso de transporte de carga sensible.

### Empathy Map 1 - Segmento: Empresas Clientes

<img src="img/empathy-map-1.png">

### Empathy Map 2 - Segmento: Clientes Finales

<img src="img/empathy-map-2.png">

## 2.4. Big Picture EventStorming

El Big Picture Event Storming es una técnica de taller colaborativo que ayudó al equipo a entender de forma visual y conjunta el dominio completo del negocio de monitoreo de transporte de carga sensible. Esta actividad permitió mapear los procesos principales, identificar los eventos más importantes, analizar cómo interactúan los diferentes actores y sistemas, y descubrir oportunidades clave de mejora que servirán de base para el diseño de OmniTrack.

Link del Big Picture Event Storming: https://miro.com/app/board/uXjVGhhI3ec=/?share_link_id=985657624736

#### 1. Preparación del Espacio

Siguiendo el material entregado en el blackboard, el equipo comenzó la sesión organizando un tablero compartido en Miro. Se definió claramente el objetivo de la actividad: analizar todo el ciclo de vida del servicio de transporte de carga sensible, desde la solicitud inicial hasta la entrega y evaluación posterior.

#### 2. Motivación de los Participantes

Para generar mayor compromiso, se realizaron dinámicas de integración y se mostraron ejemplos prácticos de eventos de negocio, con el fin de que todos entendieran cómo esta técnica ayuda a construir una visión compartida del sistema.

#### 3. Explicación de la Agenda

Se presentó el alcance de la sesión:

Explorar la interacción entre gestores de flota, conductores, personal de muelle y clientes finales.
Identificar los eventos clave desde que se solicita un servicio hasta la entrega y cierre de la operación.
Reconocer los actores principales y los sistemas externos involucrados.

#### 4. Generación de Eventos de Dominio

Los participantes propusieron libremente todos los eventos que consideraron relevantes, anotándolos en tarjetas sin preocuparse por el orden en ese momento.

<img src="img/big-event-storm-1.png">

#### 5. Ordenamiento de Eventos de Dominio

Se organizaron los eventos siguiendo una secuencia lógica de tiempo, desde el inicio del proceso (solicitud de envío) hasta su finalización (cierre de la operación). Esta organización permitió visualizar el flujo completo y detectar posibles puntos de fricción o actividades redundantes.

<img src="img/big-event-storm-2.png">

#### 6. Incorporación de Actores y Sistemas Externos

Se identificaron los actores clave que participan en los eventos y los sistemas externos que intervienen:
Actores:

Gestor de Flota: Responsable de gestionar operaciones, rutas, costos y acuerdos de nivel de servicio (SLA).

Personal del Muelle: Encargado de la carga, descarga y verificación física de la mercancía.

Conductor: Responsable de ejecutar el viaje y responder a las alertas durante el trayecto.

Personal Logístico: Coordina el flujo de mercancías, gestiona inventario, almacenamiento y documentación.

Sistemas Externos:

Sistema de Planificación de Rutas: Encargado de calcular las rutas más eficientes considerando distancia, tiempo estimado, ventanas de entrega, capacidad del vehículo y costos.

<img src="img/big-event-storm-3.png">

#### 7. Narrativa (Storytelling)

El equipo contó la historia del proceso desde dos puntos de vista principales:

#### Desde la perspectiva del Gestor de Flota:

Recibe una solicitud, genera una cotización, acuerda un SLA y planifica la ruta. Asigna vehículo y conductor, prepara documentación y reserva espacios en muelles. Durante el viaje, depende principalmente de llamadas del conductor para conocer el estado de la carga. Si surge un problema, suele enterarse cuando ya ha ocurrido.

#### Desde la perspectiva del Cliente Final:

No recibe información actualizada del envío. Al momento de la entrega, solo puede inspeccionar visualmente la mercancía. La falta de datos objetivos hace que la verificación sea subjetiva y que cualquier reclamo sea lento y complicado.

#### 8. Narrativa Inversa (Reverse Storytelling)

Se recorrió el proceso en sentido contrario, comenzando desde el cierre de la operación (recepción de la mercancía) hasta la solicitud inicial. Esta técnica ayudó a validar que no se omitiera ningún evento importante y a confirmar que los principales problemas (falta de visibilidad en tiempo real y dependencia del papeleo) eran consistentes.

#### 9. Cierre de la Sesión

Se resumieron los aprendizajes más relevantes y las principales oportunidades de mejora:

La fuerte dependencia de comunicación manual y papeleo genera puntos ciegos importantes durante el transporte.

Es necesario contar con visibilidad en tiempo real de parámetros críticos para poder actuar de forma proactiva.

La trazabilidad actual es insuficiente, ya que la inspección visual al final del trayecto no garantiza el cumplimiento de condiciones durante todo el viaje.

Se requieren políticas claras sobre umbrales de temperatura, tiempos de respuesta y manejo de desviaciones para evitar disputas.

El cliente final tiene una experiencia limitada debido a la falta de transparencia, lo que afecta la confianza en el servicio.

La resolución de incidencias y el cumplimiento normativo se ven perjudicados por la ausencia de reportes automáticos y datos históricos confiables.

## 2.5. Ubiquitous Language

## 1. Términos del Dominio Central
 
| Término | Definición |
|---------|-----------|
| **Cadena de Frío** | Proceso logístico que mantiene los productos perecederos dentro de rangos específicos de temperatura desde el origen hasta el destino final, preservando su calidad e integridad. |
| **Envío** | Conjunto de productos o carga que se transporta desde un punto de origen hacia un destino bajo una misma guía o registro. |
| **Transportista** | Persona o empresa responsable de trasladar los productos y garantizar que se cumplan las condiciones de transporte acordadas. |
| **Plan de Ruta** | Itinerario detallado que define el recorrido, tiempos estimados, puntos de parada y condiciones necesarias para completar la entrega. |
| **Rango de Temperatura** | Intervalo de grados aceptable dentro del cual debe mantenerse el producto durante todo el transporte. |
| **Desviación de Temperatura** | Diferencia entre la temperatura real de la carga y el rango permitido, que puede comprometer la calidad del producto. |
 
---
 
## 2. Términos de Actores
 
| Término | Definición |
|---------|-----------|
| **Gestor de Flota** | Usuario responsable de configurar dispositivos, establecer parámetros de viaje, monitorear múltiples transportes y generar reportes para clientes. |
| **Conductor** | Usuario operativo que recibe alertas durante el trayecto y ejecuta acciones correctivas cuando se detectan problemas en las condiciones de la carga. |
| **Cliente Final** | Receptor de la mercancía que requiere visibilidad del estado del transporte y documentación de cumplimiento térmico para aceptar o rechazar los productos. |
 
---
 
## 3. Términos de Procesos de Negocio
 
| Término | Definición |
|---------|-----------|
| **Configuración de Viaje** | Proceso de definir parámetros específicos antes del inicio del transporte: rangos de temperatura, duración estimada, tipo de carga y responsables. |
| **Acción Correctiva** | Medidas tomadas por el conductor o el operador para resolver violaciones de temperatura, como ajustar refrigeración, cambiar ruta o notificar supervisores. |
| **Calibración de Sensores** | Proceso periódico de verificación y ajuste de los sensores para garantizar precisión en las mediciones según estándares de calidad. |
| **Cumplimiento de Cadena de Frío** | Estado que certifica que un viaje se completó dentro de todos los parámetros térmicos requeridos, cumpliendo con regulaciones y estándares de calidad. |
 
---
 
## 4. Contexto de Métricas y KPIs
 
| Término | Definición |
|---------|-----------|
| **Excursión de Temperatura** | Período durante el cual la temperatura de la carga estuvo fuera del rango permitido, medido en minutos u horas según la criticidad del producto. |
| **Tasa de Cumplimiento** | Porcentaje de viajes que se completaron sin violaciones de temperatura en un período determinado. Es uno de los KPIs principales del servicio. |
| **Tiempo de Respuesta a Alertas** | Métrica que mide el tiempo transcurrido entre la generación de una alerta y la ejecución de acciones correctivas por parte del equipo operativo. |

# Capítulo III: Requirements Specification
## 3.1. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| --------------- | ------ | ----------- | ----------------------- | ------------------------- |
| E1 | Landing Page | Página principal orientada a informar al visitante y facilitar su conversión. | Scenario: Experiencia informativa completa<br>Given un visitante ingresa por primera vez al sitio<br>When revisa el contenido de la landing<br>Then encuentra información clara de valor, funcionalidades y contacto<br>And puede identificar rápidamente cómo continuar hacia la app. | |
| E2 | Autenticación | Conjunto de funciones para registro, acceso y recuperación segura de cuentas. | Scenario: Gestión de acceso confiable<br>Given un usuario interactúa con registro o inicio de sesión<br>When envía sus credenciales al sistema<br>Then el sistema valida y responde según reglas de seguridad<br>And protege la sesión del usuario autenticado. | |
| E3 | Gestión de flota | Administración integral de vehículos y dispositivos IoT vinculados a la operación logística. | Scenario: Control operativo de activos<br>Given un administrador gestiona unidades y sensores<br>When registra, actualiza o da de baja elementos de la flota<br>Then el sistema mantiene información consistente y trazable<br>And aplica validaciones de negocio en cada operación. | |
| E4 | Planificador de viajes | Módulo para crear, actualizar y reprogramar viajes de forma controlada. | Scenario: Planificación y seguimiento de viajes<br>Given un viaje requiere programación y control de estado<br>When el administrador ejecuta acciones sobre el viaje<br>Then el sistema registra cambios con reglas válidas de transición<br>And conserva historial operativo para seguimiento. | |
| E5 | Monitoreo en tiempo real | Supervisión continua de temperatura y conectividad de dispositivos IoT. | Scenario: Vigilancia de telemetría en vivo<br>Given existen dispositivos activos transmitiendo datos<br>When el sistema recibe lecturas de operación<br>Then actualiza la información en tiempo real<br>And genera alertas ante incidentes críticos. | |
| E6 | Dashboard de viajes | Vista analítica para consultar estado, detalle y métricas históricas de viajes. | Scenario: Visualización para toma de decisiones<br>Given un usuario necesita analizar la operación<br>When accede al dashboard de viajes<br>Then obtiene listas, filtros, gráficos y detalle por viaje<br>And puede exportar evidencia cuando sea necesario. | |
| E7 | Módulo de suscripciones | Gestión de planes, pagos, renovaciones y cancelaciones del servicio. | Scenario: Administración de ciclo de suscripción<br>Given un cliente consulta o modifica su plan<br>When realiza acciones de pago, revisión o cancelación<br>Then el sistema muestra el estado actualizado de su suscripción<br>And notifica eventos relevantes como renovaciones próximas. | |
| US001 | Navegación en landing page | **Como** visitante <br>**quiero** recorrer las secciones del servicio <br>**para** informarme adecuadamente sobre la plataforma. | Scenario: Visualización de contenido principal<br>Given un visitante entra a la landing page<br>When navega por la información del servicio<br>Then el sistema muestra correctamente Inicio, Características, Planes y Contacto<br>And mantiene el contenido accesible sin errores.<br><br>Scenario: Exploración completa de la página<br>Given un visitante desea revisar todo el sitio<br>When se desplaza entre secciones de forma continua<br>Then recibe información coherente en cada bloque<br>And no encuentra secciones vacías ni inconsistentes. | E1 |
| US002 | Sección portada | **Como** visitante, <br>**quiero** identificar el mensaje principal del producto, <br>**para** comprender su propósito desde el inicio. | Scenario: Mensaje de valor visible<br>Given un visitante accede a la portada<br>When observa el encabezado principal<br>Then entiende claramente la propuesta de valor de la plataforma<br>And reconoce a qué tipo de problema responde el servicio. | E1 |
| US003 | Sección de funcionalidades | **Como** visitante, <br>**quiero** conocer las capacidades clave de la plataforma, <br>**para** saber qué solución me ofrece. | Scenario: Presentación de funcionalidades<br>Given un visitante revisa la sección funcional del sitio<br>When consulta qué hace la plataforma<br>Then el sistema muestra al menos tres funcionalidades principales<br>And cada una se describe de forma clara y comprensible. | E1 |
| US004 | Sección de beneficios | **Como** visitante, <br>**quiero** entender los beneficios del servicio, <br>**para** evaluar el valor de adoptarlo. | Scenario: Exposición de beneficios<br>Given un visitante accede a la sección de beneficios<br>When analiza el valor ofrecido<br>Then encuentra una lista clara de ventajas del producto<br>And puede diferenciar el impacto positivo para su operación. | E1 |
| US005 | Sección de testimonios | **Como** visitante, <br>**quiero** conocer experiencias de otros usuarios, <br>**para** incrementar mi confianza en la plataforma. | Scenario: Evidencia social visible<br>Given un visitante revisa la sección de testimonios<br>When busca referencias de clientes<br>Then el sistema presenta al menos dos testimonios verificables<br>And cada testimonio aporta contexto útil sobre la experiencia. | E1 |
| US006 | Sección de contáctanos | **Como** visitante, <br>**quiero** enviar consultas a la empresa, <br>**para** recibir soporte o información adicional. | Scenario: Envío válido de formulario<br>Given un visitante completa nombre, correo y mensaje válidos<br>When envía su consulta<br>Then el sistema registra correctamente la solicitud<br>And confirma al visitante que el mensaje fue recibido.<br><br>Scenario: Validación de datos incompletos<br>Given un visitante omite campos obligatorios<br>When intenta enviar el formulario<br>Then el sistema rechaza la solicitud<br>And muestra qué campos deben corregirse. | E1 |
| US007 | Call to Action a la aplicación web | **Como** visitante <br>**quiero** entrar a la aplicación web <br>**para** registrarme o iniciar sesión desde el navegador. | Scenario: Redirección correcta a la app<br>Given un visitante pulsa el botón de acceso a la app<br>When solicita iniciar uso de la plataforma web<br>Then el sistema lo dirige al flujo de autenticación<br>And habilita el acceso a funcionalidades según su cuenta. | E1 |
| US008 | Call to Action de descarga de App Móvil | **Como** visitante <br>**quiero** descargar la app móvil <br>**para** instalarla y usar el servicio desde mi dispositivo. | Scenario: Descarga según plataforma<br>Given un visitante desea instalar la app móvil<br>When selecciona la opción de descarga<br>Then el sistema ofrece enlaces correctos para iOS y Android<br>And evita redirecciones incorrectas por tipo de dispositivo. | E1 |
| US009 | Registro de usuario | **Como** usuario <br>**quiero** registrarme en la plataforma <br>**para** acceder a mi cuenta personalizada. | Scenario: Registro exitoso<br>Given un usuario no cuenta con registro previo<br>When completa y envía datos válidos<br>Then el sistema crea su cuenta satisfactoriamente<br>And habilita su acceso al servicio.<br><br>Scenario: Registro rechazado por datos inválidos<br>Given un usuario envía información incorrecta o incompleta<br>When intenta registrarse<br>Then el sistema rechaza la solicitud<br>And comunica el motivo del error. | E2 |
| US010 | Inicio de sesión | **Como** usuario <br>**quiero** iniciar sesión en la plataforma <br>**para** acceder a mis funciones y datos. | Scenario: Autenticación válida<br>Given un usuario registrado ingresa credenciales correctas<br>When confirma el inicio de sesión<br>Then el sistema autentica su identidad<br>And permite el acceso a su cuenta.<br><br>Scenario: Autenticación inválida<br>Given un usuario registrado ingresa credenciales incorrectas<br>When intenta iniciar sesión<br>Then el sistema deniega el acceso<br>And muestra un mensaje de error de autenticación. | E2 |
| US011 | Cerrar sesión | **Como** usuario autenticado <br>**quiero** cerrar sesión en la aplicación <br>**para** proteger mi cuenta en el dispositivo actual. | Scenario: Cierre de sesión exitoso<br>Given el usuario tiene una sesión activa y token vigente<br>When solicita cerrar sesión<br>Then el sistema elimina la sesión del cliente<br>And obliga a autenticarse nuevamente para acceder a recursos protegidos. | E2 |
| US012 | Recuperar contraseña | **Como** usuario <br>**quiero** restablecer mi contraseña cuando la olvido <br>**para** recuperar el acceso a mi cuenta. | Scenario: Solicitud de recuperación<br>Given un cliente no recuerda su contraseña<br>When ingresa su correo registrado en el flujo de recuperación<br>Then el sistema envía un enlace seguro de restablecimiento<br>And asocia el enlace a una vigencia temporal.<br><br>Scenario: Uso válido de enlace de restablecimiento<br>Given el cliente recibió el enlace dentro del tiempo permitido<br>When accede al enlace de recuperación<br>Then el sistema muestra el formulario para nueva contraseña<br>And valida que el enlace no haya sido usado antes.<br><br>Scenario: Enlace expirado<br>Given el cliente intenta usar un enlace fuera de vigencia<br>When envía la solicitud de cambio<br>Then el sistema rechaza la operación<br>And muestra que debe solicitar un nuevo enlace.<br><br>Scenario: Cambio de contraseña exitoso<br>Given el cliente define una contraseña válida<br>When confirma el restablecimiento<br>Then el sistema actualiza la contraseña en base de datos<br>And notifica que la operación fue completada. | E2 |
| US013 | Registro de vehículos de carga | **Como** administrador logístico, <br>**quiero** registrar vehículos en la plataforma, <br>**para** mantener actualizada la flota operativa. | Scenario: Alta válida de vehículo<br>Given el administrador dispone de marca, modelo, placa, capacidad y dimensiones<br>When registra el vehículo en el sistema<br>Then la plataforma lo incorpora a la flota activa<br>And almacena sus datos correctamente.<br><br>Scenario: Campos obligatorios incompletos<br>Given el administrador omite datos requeridos como marca, modelo o placa<br>When intenta completar el registro<br>Then el sistema rechaza la operación<br>And muestra errores de validación.<br><br>Scenario: Formato de placa inválido<br>Given el administrador ingresa una placa en formato incorrecto<br>When guarda el registro del vehículo<br>Then el sistema no acepta la operación<br>And solicita ingresar una placa válida.<br><br>Scenario: Validación de dimensiones<br>Given el administrador registra alto, ancho y largo del vehículo<br>When los valores son numéricos y positivos<br>Then el sistema acepta los datos<br>And los conserva como parte del registro técnico.<br><br>Scenario: Validación de capacidad<br>Given el administrador ingresa la capacidad de carga en kilogramos<br>When la capacidad es mayor que cero<br>Then el sistema guarda la capacidad ingresada<br>And rechaza valores nulos o negativos. | E3 |
| US014 | Actualización de datos de vehículos de carga | **Como** administrador logístico, **quiero** editar información de vehículos, **para** mantener su estado operativo actualizado. | Scenario: Actualización de datos básicos<br>Given existe un vehículo previamente registrado<br>When el administrador modifica marca, modelo o dimensiones<br>Then el sistema actualiza los datos del vehículo<br>And registra la modificación en el historial.<br><br>Scenario: Detección de placa duplicada<br>Given una placa ya está asignada a otro vehículo<br>When el administrador intenta reutilizar esa placa<br>Then el sistema rechaza la actualización<br>And notifica la duplicidad detectada.<br><br>Scenario: Protección de campos obligatorios<br>Given el administrador elimina un dato obligatorio durante la edición<br>When intenta guardar cambios<br>Then el sistema invalida la actualización<br>And mantiene la información previa sin alteraciones. | E3 |
| US015 | Eliminación de vehículos de carga | **Como** administrador logístico, **quiero** retirar vehículos de la plataforma, **para** depurar el inventario sin perder trazabilidad. | Scenario: Baja lógica de vehículo activo<br>Given un vehículo se encuentra registrado en la flota<br>When el administrador ejecuta su eliminación<br>Then el sistema lo marca como inactivo<br>And conserva historial de viajes y mantenimientos.<br><br>Scenario: Restricción por viaje en curso<br>Given el vehículo tiene un viaje activo<br>When el administrador intenta eliminarlo<br>Then el sistema bloquea la operación<br>And muestra que existen viajes pendientes asociados.<br><br>Scenario: Eliminación de vehículo sin viajes activos<br>Given el vehículo no presenta viajes en curso<br>When el administrador confirma la eliminación<br>Then el sistema actualiza su estado a eliminado<br>And deja de mostrarlo en la flota activa. | E3 |
| US016 | Registro de dispositivos IoT | **Como** Administrador Logístico <br>**quiero** registrar dispositivos IoT en la plataforma <br>**para** vincularlos a la flota y recibir telemetría. | Scenario: Registro exitoso de nuevo dispositivo<br>Given un dispositivo IoT cuenta con identificador único<br>When el administrador realiza el registro<br>Then el sistema almacena el dispositivo en base de datos<br>And lo habilita para su posterior asignación a un vehículo.<br><br>Scenario: Registro duplicado de dispositivo<br>Given el identificador del dispositivo ya existe en el sistema<br>When el administrador intenta registrarlo nuevamente<br>Then el sistema rechaza la solicitud<br>And informa que el dispositivo ya fue registrado.<br><br>Scenario: Validación de campos requeridos<br>Given faltan datos obligatorios como deviceId o tipo<br>When el administrador envía el formulario de alta<br>Then el sistema invalida el registro<br>And comunica los campos faltantes. | E3 |
| US017 | Eliminar dispositivo IoT | **Como** Administrador Logístico, <br>**quiero** eliminar un dispositivo IoT de la plataforma, <br>**para** retirarlo por falla o reemplazo. | Scenario: Baja de dispositivo inactivo<br>Given un dispositivo está registrado y sin transmisión activa<br>When el administrador lo elimina<br>Then el sistema actualiza su estado a inactivo<br>And conserva su historial de alertas y lecturas.<br><br>Scenario: Bloqueo de eliminación por actividad<br>Given un dispositivo transmite datos en tiempo real<br>When el administrador intenta eliminarlo<br>Then el sistema rechaza la operación<br>And notifica que el dispositivo continúa activo.<br><br>Scenario: Eliminación de dispositivo sin actividad reciente<br>Given un dispositivo no reporta datos desde hace más de 24 horas<br>When el administrador confirma su retiro<br>Then el sistema lo marca como eliminado<br>And deja de mostrarlo en la lista de dispositivos activos. | E3 |
| US018 | Asignar dispositivo a vehículo de carga | **Como** Administrador Logístico <br>**quiero** asignar un dispositivo IoT a un vehículo de carga <br>**para** asociar correctamente cada transmisión. | Scenario: Vinculación de dispositivo disponible<br>Given un dispositivo registrado no tiene asignación vigente<br>When el administrador selecciona un vehículo de la flota<br>Then el sistema crea la relación dispositivo-vehículo<br>And muestra las futuras lecturas bajo ese vehículo.<br><br>Scenario: Dispositivo ya asignado<br>Given un dispositivo ya se encuentra vinculado a otra unidad<br>When el administrador intenta asignarlo sin liberar la relación previa<br>Then el sistema rechaza la acción<br>And muestra que el dispositivo ya está vinculado. | E3 |
| US019 | Cambiar dispositivo de vehículo | **Como** Administrador Logístico <br>**quiero** reasignar un dispositivo IoT a otra unidad <br>**para** reutilizarlo durante rotaciones o mantenimiento. | Scenario: Reasignación exitosa entre vehículos<br>Given un dispositivo está asociado a un vehículo actual<br>When el administrador lo reasigna a otro vehículo<br>Then el sistema actualiza la relación de asignación<br>And enruta las próximas transmisiones al nuevo vehículo.<br><br>Scenario: Confirmación de inventario tras cambio<br>Given la reasignación fue completada<br>When se consulta el vehículo anterior<br>Then el dispositivo ya no aparece en su inventario<br>And solo figura en el vehículo nuevo. | E3 |
| US020 | Ver vehículos de carga | **Como** Administrador Logístico <br>**quiero** visualizar la lista de vehículos registrados <br>**para** supervisar y administrar el inventario. | Scenario: Consulta de listado de vehículos<br>Given existen vehículos en la base de datos<br>When el administrador abre la sección de vehículos<br>Then el sistema muestra placa, modelo, estado y capacidad de cada unidad<br>And permite revisar el inventario de forma rápida.<br><br>Scenario: Inventario sin registros<br>Given no hay vehículos registrados<br>When el administrador consulta la sección de vehículos<br>Then el sistema muestra un mensaje de lista vacía<br>And evita mostrar datos inconsistentes.<br><br>Scenario: Consulta de detalle por vehículo<br>Given un vehículo existe en el listado<br>When el administrador selecciona una unidad específica<br>Then el sistema muestra su ficha completa<br>And expone todos sus atributos relevantes. | E3 |
| US021 | Ver dispositivos IoT | **Como** Administrador Logístico <br>**quiero** visualizar la lista de dispositivos IoT registrados <br>**para** controlar su estado y administración. | Scenario: Consulta de lista de dispositivos<br>Given existen dispositivos registrados en el sistema<br>When el administrador accede a la sección de dispositivos<br>Then la plataforma muestra ID, tipo, estado y vehículo asignado<br>And presenta la información actualizada de cada equipo.<br><br>Scenario: Lista de dispositivos vacía<br>Given no existen dispositivos IoT cargados<br>When el administrador abre la sección de dispositivos<br>Then el sistema muestra mensaje de ausencia de registros<br>And mantiene la vista sin errores.<br><br>Scenario: Revisión de detalle de dispositivo<br>Given un dispositivo aparece en la lista<br>When el administrador lo selecciona<br>Then el sistema abre su detalle completo<br>And permite revisar su información técnica y de asignación. | E3 |
| US022 | Ver estado de dispositivo por vehículo | **Como** Administrador Logístico <br>**quiero** visualizar el estado de los dispositivos asociados a un vehículo <br>**para** monitorear su funcionamiento. | Scenario: Visualización de dispositivos conectados<br>Given un vehículo tiene dispositivos vinculados<br>When el administrador lo selecciona en el dashboard<br>Then el sistema muestra la lista con estado online/offline<br>And actualiza la condición de cada dispositivo en pantalla.<br><br>Scenario: Detección automática de desconexión<br>Given un dispositivo deja de transmitir por más de 5 minutos<br>When el sistema evalúa su última actividad<br>Then lo marca como desconectado<br>And refleja el cambio en el panel operativo.<br><br>Scenario: Recuperación de estado conectado<br>Given un dispositivo estaba marcado como desconectado<br>When vuelve a transmitir datos
Then la plataforma cambia su estado a conectado<br>And actualiza su condición en el dashboard. | E3 |
| US023 | Ver estado de dispositivo | **Como** usuario del dispositivo <br>**quiero** conocer su estado actual <br>**para** verificar rápidamente su funcionamiento. | Scenario: Dispositivo operativo<br>Given el dispositivo está encendido y reportando datos<br>When el usuario consulta su estado<br>Then el sistema indica que está activo y conectado<br>And confirma su operatividad normal.<br><br>Scenario: Dispositivo sin conectividad<br>Given el dispositivo perdió conexión de red<br>When el usuario revisa su estado
Then el sistema informa ausencia de transmisión<br>And muestra condición de desconexión.<br><br>Scenario: Batería baja detectada<br>Given el nivel de batería es menor al 20%<br>When el usuario visualiza el estado del dispositivo<br>Then el sistema genera aviso de batería baja<br>And alerta sobre posible afectación operativa.<br><br>Scenario: Dispositivo apagado
Given el dispositivo fue apagado o quedó inactivo<br>When el usuario consulta su condición<br>Then el sistema muestra estado apagado/inactivo<br>And evita reportarlo como operativo. | E3 |
| US024 | Creación de viajes | **Como** administrador logístico, <br>**quiero** crear viajes asignando vehículo y ruta, <br>**para** planificar el traslado de mercancía. | Scenario: Registro de viaje válido<br>Given existe un vehículo disponible para operación<br>When el administrador crea un viaje con origen y destino definidos<br>Then el sistema registra el viaje correctamente<br>And lo establece con estado inicial pendiente. | E4 |
| US025 | Actualización de estados de viaje | **Como** administrador logístico, <br>**quiero** actualizar el estado de un viaje, <br>**para** mantener informados a clientes y responsables. | Scenario: Cambio a estado en ruta<br>Given un viaje se encuentra en estado pendiente<br>When el administrador lo actualiza a en ruta<br>Then el sistema guarda el nuevo estado<br>And notifica a los usuarios relacionados.<br><br>Scenario: Cambio a estado finalizado<br>Given un viaje está actualmente en ruta<br>When el administrador lo marca como finalizado<br>Then el sistema cierra el viaje
And registra fecha y hora de finalización.<br><br>Scenario: Restricción de viaje cancelado<br>Given un viaje está en estado cancelado<br>When el administrador intenta cambiar su estado<br>Then el sistema rechaza la actualización<br>And muestra un mensaje de restricción. | E4 |
| US026 | Reprogramación de viajes | **Como** administrador logístico, <br>**quiero** reprogramar un viaje ya creado, <br>**para** ajustar horarios por cambios operativos. | Scenario: Reprogramación permitida
Given un viaje tiene estado pendiente
When el administrador modifica fecha y hora de inicio
Then el sistema actualiza la planificación del viaje
And guarda el cambio en el historial.<br><br>Scenario: Reprogramación no permitida
Given el viaje ya se encuentra en ruta
When el administrador intenta cambiar fecha u hora
Then el sistema rechaza la reprogramación
And comunica la restricción operativa. | E4 |
| US027 | Código de viaje para cliente | **Como** cliente final, <br>**quiero** recibir un código único de viaje, <br>**para** consultar fácilmente el estado de mi pedido. | Scenario: Generación de código al crear viaje
Given el administrador registra un nuevo viaje
When el sistema confirma su creación
Then genera un código único de seguimiento
And envía dicho código al cliente por canal disponible.<br><br>Scenario: Seguimiento con código
Given un cliente dispone de su código de viaje
When lo ingresa en la aplicación
Then el sistema muestra el estado actualizado del viaje
And permite visualizar su progreso en tiempo real. | E4 |
| US028 | Actualización de temperatura en tiempo real | **Como** empresa, <br>**quiero** recibir temperatura en tiempo real de mis dispositivos IoT, <br>**para** controlar la cadena de frío durante el viaje. | Scenario: Recepción de telemetría en vivo
Given un sensor IoT transmite lecturas de temperatura
When la plataforma recibe nuevos datos
Then actualiza la temperatura inmediatamente
And refleja la lectura en el panel sin retrasos relevantes.<br><br>Scenario: Pérdida temporal de conexión
Given un dispositivo pierde conectividad
When el sistema detecta ausencia de nuevas lecturas
Then mantiene visible la última temperatura disponible
And marca el estado de conexión del dispositivo. | E4 |
| US029 | Alertas por incumplimiento de temperatura | **Como** cliente final, <br>**quiero** recibir alertas cuando la temperatura exceda límites definidos <br>**para** tomar acciones correctivas a tiempo. | Scenario: Generación de alerta térmica
Given una lectura supera el umbral permitido
When el sistema procesa la medición
Then crea una alerta de incumplimiento
And notifica al usuario correspondiente.<br><br>Scenario: Visualización de alerta recibida
Given el usuario tiene notificaciones activas
When se emite una alerta de temperatura
Then el usuario la visualiza en el sistema o canal externo
And puede actuar de inmediato. | E5 |
| US030 | Alertas de conexión IoT | **Como** empresa, <br>**quiero** recibir alertas cuando un dispositivo deje de enviar datos <br>**para** reaccionar rápidamente ante fallas. | Scenario: Detección de desconexión
Given un dispositivo no transmite información por más de X minutos
When el sistema verifica la inactividad
Then genera una alerta de conexión
And notifica a la empresa para intervención. | E5 |
| US031 | Roles y permisos de acceso | **Como** empresa, <br>**quiero** gestionar roles y permisos de usuarios (admin, cliente, operador) <br>**para** controlar el acceso al sistema. | Scenario: Acceso con rol administrador
Given un usuario con rol administrador inicia sesión
When accede al panel de gestión
Then puede ejecutar operaciones administrativas
And dispone de permisos completos según política.<br><br>Scenario: Acceso con rol cliente
Given un usuario con rol cliente inicia sesión
When ingresa a la plataforma
Then visualiza solo información de sus viajes y suscripciones
And no accede a funciones restringidas. | E5 |
| US032 | Lista de viajes registrados | **Como** empresa, <br>**quiero** ver la lista de viajes registrados <br>**para** gestionarlos con mayor rapidez. | Scenario: Consulta de viajes en dashboard
Given un usuario autenticado accede al tablero
When solicita el listado de viajes
Then el sistema muestra todos los viajes disponibles
And presenta sus datos principales para gestión. | E6 |
| US033 | Detalle de viaje | **Como** cliente final, <br>**quiero** consultar el detalle de un viaje <br>**para** revisar ruta, estado y temperatura. | Scenario: Visualización de detalle completo
Given un viaje existe en la plataforma
When el usuario selecciona ese viaje
Then el sistema muestra toda su información asociada
And presenta ruta, estado y datos de monitoreo. | E6 |
| US034 | Gráficos de tiempo y temperatura | **Como** cliente final, <br>**quiero** ver la evolución de temperatura en gráficos <br>**para** validar cumplimiento de parámetros. | Scenario: Gráfico histórico de temperatura
Given un viaje tiene registros de temperatura
When el usuario consulta el detalle del viaje
Then el sistema muestra un gráfico de línea temporal
And permite interpretar la variación durante el recorrido. | E6 |
| US035 | Gráficos de incidencias por mes | **Como** empresa, <br>**quiero** visualizar incidencias por mes <br>**para** identificar patrones de falla. | Scenario: Análisis mensual de incidencias
Given existen eventos de incidencia en el histórico
When el usuario abre el dashboard analítico
Then el sistema presenta un gráfico mensual consolidado
And permite detectar tendencias operativas. | E6 |
| US036 | Filtrado de viajes por fecha | **Como** empresa, <br>**quiero** filtrar viajes por rango de fechas <br>**para** analizar un período específico. | Scenario: Filtro temporal aplicado
Given un usuario define una fecha de inicio y fin
When el sistema procesa el filtro solicitado
Then muestra únicamente viajes dentro del rango
And oculta registros fuera del período. | E6 |
| US037 | Descarga de reporte de viajes | **Como** cliente final, <br>**quiero** descargar un reporte PDF del viaje <br>**para** archivarlo o compartirlo. | Scenario: Exportación de reporte
Given el usuario selecciona un viaje concreto
When solicita generar el reporte
Then el sistema crea un archivo PDF con datos y gráficos
And entrega el archivo para su descarga. | E6 |
| US038 | Cancelar suscripción | **Como** cliente final, <br>**quiero** cancelar mi suscripción <br>**para** detener cobros futuros. | Scenario: Cancelación de plan activo
Given un cliente tiene una suscripción vigente
When solicita la cancelación del servicio
Then el sistema actualiza el estado a cancelado
And evita programar nuevos cobros. | E7 |
| US039 | Visualizar información de suscripción | **Como** cliente final, <br>**quiero** ver estado y vencimiento de mi suscripción <br>**para** gestionar mi continuidad en el servicio. | Scenario: Consulta de datos de suscripción
Given un cliente autenticado accede a la sección de suscripciones
When solicita ver su información
Then el sistema muestra plan, estado y fecha de expiración
And presenta la información de forma clara. | E7 |
| US040 | Historial de pagos | **Como** cliente final, <br>**quiero** consultar mi historial de pagos <br>**para** verificar mis transacciones. | Scenario: Revisión de pagos históricos
Given un cliente autenticado abre el módulo de pagos
When consulta su historial
Then el sistema lista todas las transacciones registradas
And muestra fecha y monto de cada una. | E7 |
| US041 | Notificación de renovación próxima | **Como** cliente final, <br>**quiero** recibir un aviso antes de la renovación <br>**para** decidir si continúo o cancelo. | Scenario: Aviso previo de renovación
Given una suscripción se encuentra próxima a renovarse
When se alcanza el umbral de aviso configurado (ej. 3 días antes)
Then el sistema envía una notificación preventiva al cliente
And le permite decidir acciones antes del cobro. | E7 |
| TS001 | API de autenticación | **Como** developer <br>**quiero** implementar endpoints de login, logout, refresh y validación de sesión <br>**para** asegurar el acceso de usuarios. | Scenario: Login exitoso
Given un usuario envía credenciales válidas al endpoint de login
When el backend valida usuario y contraseña
Then responde con código 200 OK
And devuelve access token y refresh token.<br><br>Scenario: Login fallido
Given un usuario envía credenciales inválidas
When el backend intenta autenticarlas
Then responde con 401 Unauthorized
And retorna mensaje de error de autenticación.<br><br>Scenario: Logout exitoso
Given un usuario tiene sesión activa con refresh token vigente
When solicita cierre de sesión
Then el backend responde con 200 OK
And deja invalidado el refresh token.<br><br>Scenario: Registro de usuario exitoso
Given un nuevo usuario envía correo, contraseña y nombre válidos
When el backend valida y almacena la información
Then responde con 201 Created
And confirma la creación del usuario.<br><br>Scenario: Registro con correo duplicado
Given el correo ya existe en la base de datos
When se intenta registrar una nueva cuenta con ese correo
Then el backend responde con 409 Conflict
And retorna mensaje de correo ya registrado.<br><br>Scenario: Refresh token válido
Given el usuario cuenta con refresh token vigente
When solicita renovación de sesión
Then el backend responde con 200 OK
And emite un nuevo par de tokens.<br><br>Scenario: Token inválido o expirado
Given un token inválido o vencido es enviado al endpoint de validación
When el backend procesa la solicitud
Then responde con 401 Unauthorized
And devuelve mensaje de token inválido o expirado. | E2 |
| TS002 | Servicio de autenticación con JWT | **Como** developer, <br>**quiero** usar JWT para autenticar solicitudes, <br>**para** proteger la comunicación cliente-servidor. | Scenario: Emisión de JWT
Given un usuario inicia sesión correctamente
When el backend completa la autenticación
Then genera un JWT con userId, rol y expiración
And devuelve el token al cliente.<br><br>Scenario: Verificación de JWT válido
Given el cliente envía un JWT válido en Authorization
When el backend valida firma y vigencia
Then acepta la solicitud
And habilita el acceso al recurso protegido.<br><br>Scenario: Verificación de JWT inválido
Given el cliente envía un token alterado o mal formado
When el backend intenta validarlo
Then rechaza la solicitud
And responde con 401 Unauthorized.<br><br>Scenario: JWT expirado
Given el cliente envía un token vencido
When el backend verifica la expiración
Then rechaza el acceso
And retorna 401 con mensaje de token expirado.<br><br>Scenario: Renovación con refresh token
Given el access token expiró y el refresh token sigue vigente
When el cliente solicita renovación
Then el backend emite un nuevo JWT de acceso
And responde con tokens actualizados. | E2 |
| TS003 | API de vehículos de carga | **Como** developer, <br>**quiero** exponer endpoints para registrar, modificar y consultar vehículos, <br>**para** administrar el inventario de flota. | Scenario: Alta exitosa de vehículo
Given un vehículo tiene placa, modelo, año y capacidad válidos
When se envía POST al endpoint de vehículos
Then el backend guarda el registro
And responde con 201 y el detalle creado.<br><br>Scenario: Registro duplicado por placa
Given la placa ya existe en el sistema
When se intenta registrar nuevamente el vehículo
Then el backend rechaza la solicitud
And responde con 409 indicando duplicidad.<br><br>Scenario: Actualización de vehículo existente
Given un vehículo está registrado en la base de datos
When se envía PUT con datos actualizados
Then el backend guarda los cambios
And responde con 200 y el detalle actualizado.<br><br>Scenario: Consulta por identificador
Given existe un vehículo con ID registrado
When se envía GET al endpoint con ese ID
Then el backend responde con 200
And retorna información completa del vehículo.<br><br>Scenario: Consulta de listado
Given existen múltiples vehículos registrados
When se envía GET al endpoint de vehículos
Then el backend responde con 200
And retorna la lista de vehículos disponibles. | E3 |
| TS004 | API de dispositivos IoT | **Como** developer <br>**quiero** exponer endpoints de dispositivos <br>**para** registrar y administrar equipos IoT en la plataforma. | Scenario: Registro exitoso de dispositivo
Given un dispositivo tiene deviceId, tipo y estado inicial válidos
When se envía POST al endpoint de dispositivos
Then el backend guarda el dispositivo
And responde con 201 y su detalle.<br><br>Scenario: Registro duplicado de dispositivo
Given el deviceId ya existe en base de datos
When se intenta registrar el mismo dispositivo
Then el backend rechaza la operación
And responde con 409 indicando duplicidad.<br><br>Scenario: Consulta por ID
Given un dispositivo está registrado
When se envía GET con su identificador
Then el backend responde con 200
And entrega la información completa del dispositivo.<br><br>Scenario: Consulta de lista de dispositivos
Given existen varios dispositivos activos o históricos
When se envía GET al endpoint general
Then el backend responde con 200
And retorna el listado completo.<br><br>Scenario: Actualización de dispositivo
Given un dispositivo existe en la base de datos
When se envía PUT con cambios de nombre, estado o vehículo asociado
Then el backend actualiza los datos
And responde con 200 y el registro actualizado.<br><br>Scenario: Baja lógica de dispositivo
Given un dispositivo no tiene transmisiones activas
When se envía DELETE al endpoint
Then el sistema cambia su estado a inactivo
And conserva el historial de transmisiones y eventos. | E3 |
| TS005 | API de viajes | **Como** developer, <br>**quiero** implementar un endpoint REST para registrar viajes, <br>**para** gestionar la operación logística en backend. | Scenario: Registro de viaje exitoso
Given el cliente envía datos válidos de vehículo, dispositivo IoT, fecha de inicio y destino
When el backend valida la solicitud
Then responde con 201 Created
And almacena el viaje correctamente.<br><br>Scenario: Registro con datos incompletos
Given faltan campos obligatorios en la solicitud
When el backend procesa el registro
Then responde con 400 Bad Request
And detalla los campos faltantes.<br><br>Scenario: Vehículo no encontrado
Given el ID de vehículo no existe en base de datos
When se intenta registrar el viaje
Then el backend responde con 404 Not Found
And devuelve mensaje de vehículo no encontrado.<br><br>Scenario: Dispositivo IoT no encontrado
Given el ID de dispositivo IoT no existe en base de datos
When se intenta registrar el viaje
Then el backend responde con 404 Not Found
And devuelve mensaje de dispositivo IoT no encontrado.<br><br>Scenario: Conflicto por solapamiento de viaje
Given el vehículo ya tiene un viaje activo
When se intenta crear otro viaje en paralelo con la misma unidad
Then el backend responde con 409 Conflict
And devuelve mensaje indicando conflicto de viaje activo. | E4 |

## 3.2. Impact Mapping

El Impact Mapping de OmniTrack permite conectar los objetivos de negocio con las funcionalidades concretas del sistema, a través de los actores clave y los comportamientos que se busca generar en cada segmento objetivo.

### Impact Map 1 — Segmento: Empresas Clientes (Gestores de Flota)

**Objetivo (Goal):** Incrementar en un 30% la tasa de cumplimiento de cadena de frío de la flota, reduciendo incidentes reactivos y reportes manuales en los primeros 6 meses de uso de OmniTrack.

| Actor | Impacto esperado en su comportamiento | Entregable que lo genera |
|-------|--------------------------------------|--------------------------|
| **Gestor de Flota** | Deja de depender de llamadas a conductores para conocer el estado de la carga | Dashboard de monitoreo en tiempo real con temperatura por vehículo (US028) |
| **Gestor de Flota** | Reacciona proactivamente ante excursiones de temperatura antes de que dañen la carga | Sistema de alertas automáticas por incumplimiento de temperatura (US029) |
| **Gestor de Flota** | Elimina la elaboración manual de reportes de cumplimiento consolidando datos de múltiples fuentes | Descarga de reporte PDF por viaje con gráficos de temperatura (US037) |
| **Gestor de Flota** | Gestiona múltiples rutas activas sin perder visibilidad de ningún vehículo | Lista de viajes con filtros y estados en tiempo real (US032, US036) |
| **Administrador Logístico** | Planifica viajes desde la plataforma en vez de hacerlo por medios externos | Módulo de creación y reprogramación de viajes (US024, US026) |
| **Administrador Logístico** | Mantiene inventario de dispositivos IoT sincronizado con la flota | Registro, asignación y estado de dispositivos IoT por vehículo (US016, US018, US022) |
| **Conductor** | Recibe instrucciones claras ante incidencias sin llamadas al centro de control | Notificaciones de alerta con indicación de acción correctiva (US029, US030) |

### Impact Map 2 — Segmento: Clientes Finales (Receptores de Carga Sensible)

**Objetivo (Goal):** Reducir en un 40% los reclamos sin sustento por productos recibidos en mal estado, dotando al cliente final de visibilidad objetiva y evidencia descargable sobre las condiciones de transporte.

| Actor | Impacto esperado en su comportamiento | Entregable que lo genera |
|-------|--------------------------------------|--------------------------|
| **Cliente Final** | Deja de basar la validación de calidad solo en inspección visual al momento de recibir | Visualización del estado del pedido en tiempo real durante el trayecto (US033) |
| **Cliente Final** | Anticipa problemas antes de la recepción en lugar de descubrirlos al abrir el embalaje | Alertas de incidencia de temperatura durante el transporte (US029) |
| **Cliente Final** | Sustenta reclamos con evidencia objetiva en lugar de depender de promesas verbales | Reporte PDF automático de cumplimiento de cadena de frío descargable (US037) |
| **Cliente Final** | Consulta el historial de condiciones de entregas anteriores para evaluar a sus proveedores | Gráficos de tiempo y temperatura por viaje accesibles desde su cuenta (US034, US035) |
| **Cliente Final** | Recibe un código de seguimiento único para monitorear su pedido de forma autónoma | Generación automática de código de viaje para el cliente (US027) |
| **Cliente Final** | Gestiona su suscripción y visualiza sus pagos sin depender de atención al cliente | Portal de suscripción y historial de pagos (US038, US039, US040) |

## 3.3. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points |
| ------- | ------------- | ------ | ----------- | ------------ |
| 1 | US028 | Monitoreo de temperatura en tiempo real | Como empresa, quiero visualizar lecturas de temperatura en tiempo real por dispositivo y por viaje, para supervisar la cadena de frío y reaccionar de inmediato ante cualquier desviación. | 8 |
| 2 | US029 | Alertas por incumplimiento de temperatura | Como cliente final, quiero recibir alertas automáticas cuando la temperatura exceda el rango permitido, para ejecutar acciones correctivas antes de afectar la mercadería. | 5 |
| 3 | US024 | Creación de viajes | Como administrador logístico, quiero crear viajes asociando vehículo, ruta y ventana horaria, para planificar operaciones de transporte con trazabilidad desde el inicio. | 5 |
| 4 | US025 | Actualización de estados de viaje | Como administrador logístico, quiero actualizar el estado operativo de cada viaje, para informar a clientes y responsables sobre el avance real de la entrega. | 5 |
| 5 | US033 | Detalle de viaje | Como cliente final, quiero consultar el detalle completo de un viaje, para validar ruta, estado, tiempos y comportamiento de temperatura. | 3 |
| 6 | US032 | Lista de viajes registrados | Como empresa, quiero revisar una lista consolidada de viajes con datos clave, para facilitar seguimiento, control y priorización operativa. | 3 |
| 7 | US026 | Reprogramación de viajes | Como administrador logístico, quiero reprogramar viajes pendientes ante contingencias, para ajustar fechas y horarios sin perder historial de cambios. | 5 |
| 8 | US027 | Código de viaje para cliente | Como cliente final, quiero recibir un código único de seguimiento, para consultar el estado del pedido de forma rápida y autónoma. | 5 |
| 9 | US036 | Filtrado de viajes por fecha | Como empresa, quiero filtrar viajes por rangos de fecha, para analizar periodos específicos y medir desempeño operativo. | 3 |
| 10 | US037 | Descarga de reporte de viajes | Como cliente final, quiero descargar un reporte PDF del viaje con indicadores y gráficos, para compartir evidencia o archivarla. | 5 |
| 11 | US034 | Gráficos de tiempo y temperatura | Como cliente final, quiero visualizar gráficos de evolución térmica durante el viaje, para comprobar cumplimiento de parámetros de conservación. | 5 |
| 12 | US035 | Gráficos de incidencias por mes | Como empresa, quiero ver incidencias mensuales en formato gráfico, para identificar tendencias y tomar decisiones de mejora continua. | 5 |
| 13 | US016 | Registro de dispositivos IoT | Como administrador logístico, quiero registrar dispositivos IoT con identificación única y metadatos técnicos, para integrarlos correctamente a la flota. | 5 |
| 14 | US018 | Asignar dispositivo a vehículo de carga | Como administrador logístico, quiero asignar cada dispositivo a un vehículo específico, para garantizar trazabilidad de origen de cada lectura. | 3 |
| 15 | US022 | Ver estado de dispositivo por vehículo | Como administrador logístico, quiero visualizar el estado de conectividad de dispositivos por unidad, para detectar desconexiones y actuar rápidamente. | 3 |
| 16 | US030 | Alertas de conexión IoT | Como empresa, quiero recibir alertas cuando un dispositivo deje de transmitir por un umbral definido, para minimizar periodos sin visibilidad. | 5 |
| 17 | US021 | Ver dispositivos IoT | Como administrador logístico, quiero consultar el inventario de dispositivos con su estado y asignación, para administrar la infraestructura IoT con control. | 3 |
| 18 | US017 | Eliminar dispositivo IoT | Como administrador logístico, quiero retirar dispositivos inactivos o defectuosos manteniendo el histórico, para depurar el inventario sin perder trazabilidad. | 3 |
| 19 | US023 | Ver estado de dispositivo | Como usuario del dispositivo, quiero conocer su estado operativo (activo, desconectado, batería baja, inactivo), para validar su funcionamiento de forma inmediata. | 3 |
| 20 | US013 | Registro de vehículos de carga | Como administrador logístico, quiero registrar vehículos con datos técnicos y capacidad, para mantener un inventario confiable de flota. | 5 |
| 21 | US014 | Actualización de datos de vehículos de carga | Como administrador logístico, quiero actualizar información de vehículos bajo validaciones, para mantener datos consistentes y vigentes. | 3 |
| 22 | US015 | Eliminación de vehículos de carga | Como administrador logístico, quiero dar de baja vehículos sin uso o fuera de servicio, para mantener un inventario limpio sin eliminar historial relevante. | 3 |
| 23 | US020 | Ver vehículos de carga | Como administrador logístico, quiero visualizar la lista de vehículos con sus atributos principales, para facilitar control, búsqueda y asignación. | 3 |
| 24 | US019 | Cambiar dispositivo de vehículo | Como administrador logístico, quiero reasignar un dispositivo entre vehículos, para soportar rotaciones por mantenimiento o contingencia operativa. | 3 |
| 25 | US031 | Roles y permisos de acceso | Como empresa, quiero administrar roles y permisos por tipo de usuario, para proteger operaciones sensibles y controlar acceso por perfil. | 8 |
| 26 | US038 | Cancelar suscripción | Como cliente final, quiero cancelar mi suscripción cuando lo requiera, para detener renovaciones automáticas y cobros futuros. | 2 |
| 27 | US039 | Visualizar información de suscripción | Como cliente final, quiero consultar plan, estado y fecha de vencimiento, para gestionar mi continuidad en el servicio de manera informada. | 2 |
| 28 | US040 | Historial de pagos | Como cliente final, quiero revisar mi historial de pagos con detalle, para validar montos, fechas y transacciones procesadas. | 3 |
| 29 | US041 | Notificación de renovación próxima | Como cliente final, quiero recibir avisos anticipados de renovación, para decidir si mantengo o cancelo mi suscripción antes del cobro. | 3 |
| 30 | US001 | Navegación en landing page | Como visitante, quiero navegar con fluidez entre secciones de la landing, para comprender rápidamente el servicio y su propuesta de valor. | 3 |
| 31 | US002 | Sección portada | Como visitante, quiero visualizar una portada clara y persuasiva, para entender de inmediato el propósito de la plataforma. | 3 |
| 32 | US003 | Sección de funcionalidades | Como visitante, quiero conocer las funcionalidades principales en una sección dedicada, para evaluar la utilidad del producto. | 3 |
| 33 | US004 | Sección de beneficios | Como visitante, quiero revisar beneficios concretos del servicio, para identificar valor diferencial frente a alternativas. | 2 |
| 34 | US005 | Sección de testimonios | Como visitante, quiero leer testimonios de clientes reales, para fortalecer mi confianza antes de registrarme. | 2 |
| 35 | US006 | Sección de contáctanos | Como visitante, quiero completar un formulario de contacto simple y validado, para solicitar información comercial o soporte inicial. | 3 |
| 36 | US007 | Call to Action a la aplicación web | Como visitante, quiero disponer de un acceso directo a la aplicación web, para registrarme o iniciar sesión en pocos pasos. | 3 |
| 37 | US008 | Call to Action de descarga de App Móvil | Como visitante, quiero acceder a botones de descarga según sistema operativo, para instalar la app móvil sin confusión. | 3 |
| 38 | US009 | Registro de usuario | Como usuario, quiero crear una cuenta con validaciones de seguridad, para acceder a funcionalidades personalizadas y proteger mis datos. | 3 |
| 39 | US010 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura y rápida, para acceder a mi cuenta y operaciones habilitadas. | 3 |
| 40 | US011 | Cerrar sesión | Como usuario autenticado, quiero cerrar sesión explícitamente, para evitar accesos no autorizados en dispositivos compartidos. | 2 |
| 41 | US012 | Recuperar contraseña | Como usuario, quiero restablecer mi contraseña mediante un flujo seguro, para recuperar acceso sin comprometer mi cuenta. | 3 |
| 42 | TS001 | API de autenticación | Como developer, quiero implementar endpoints de login, logout, refresh y validación, para soportar autenticación robusta y control de sesión. | 5 |
| 43 | TS002 | Servicio de autenticación con JWT | Como developer, quiero usar JWT para emitir y validar tokens de acceso, para proteger recursos y estandarizar seguridad entre cliente y backend. | 8 |
| 44 | TS003 | API de vehículos de carga | Como developer, quiero exponer endpoints para crear, actualizar y consultar vehículos, para soportar el módulo de gestión de flota. | 8 |
| 45 | TS004 | API de dispositivos IoT | Como developer, quiero implementar endpoints para ciclo de vida de dispositivos IoT, para registrar, consultar y mantener su estado operativo. | 8 |
| 46 | TS005 | API de viajes | Como developer, quiero implementar endpoints REST para gestión de viajes, para crear, consultar y validar reglas operativas del monitoreo logístico. | 8 |

# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. Design-Level EventStorming
#### 4.1.1.1 Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams
## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Identity and Access Management
#### 4.2.1.1. Domain Layer
#### 4.2.1.2. Interface Layer
#### 4.2.1.3. Application Layer
#### 4.2.1.4. Infrastructure Layer
#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.1.6.2. Bounded Context Database Design Diagram
### 4.2.2. Bounded Context: Subscriptions and Billing
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer
#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
#### 4.2.2.6.2. Bounded Context Database Design Diagram
### 4.2.3. Bounded Context: Alerts & Resolution
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.3.6.2. Bounded Context Database Design Diagram
### 4.2.4. Bounded Context: Real-Time Monitoring
#### 4.2.4.1. Domain Layer.
#### 4.2.4.2. Interface Layer.
#### 4.2.4.3. Application Layer.
#### 4.2.4.4. Infrastructure Layer.
#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.4.6.2. Bounded Context Database Design Diagram
### 4.2.5. Bounded Context: Trip management
#### 4.2.5.1. Domain Layer.
#### 4.2.5.2. Interface Layer.
#### 4.2.5.3. Application Layer.
#### 4.2.5.4. Infrastructure Layer.
#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.5.6.2. Bounded Context Database Design Diagram.
### 4.2.6. Bounded Context: Fleet Management
#### 4.2.6.1. Domain Layer
#### 4.2.6.2. Interface Layer
#### 4.2.6.3. Application Layer
#### 4.2.6.4. Infrastructure Layer
#### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.5.6.2. Bounded Context Database Design Diagram.
### 4.2.7. Bounded Context: Profile and Preferences Management
#### 4.2.7.1. Domain Layer.
#### 4.2.7.2. Interface Layer.
#### 4.2.7.3. Application Layer.
#### 4.2.7.4. Infrastructure Layer.
#### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.7.6.2. Bounded Context Database Design Diagram
### 4.2.8. Bounded Context: Visualization Analytics
#### 4.2.8.1. Domain Layer
#### 4.2.8.2. Interface Layer
#### 4.2.8.3. Application Layer
#### 4.2.8.4. Infrastructure Layer
#### 4.2.8.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.8.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.8.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.8.6.2. Bounded Context Database Design Diagram
### 4.2.9. Bounded Context: Merchant
#### 4.2.9.1. Domain Layer
#### 4.2.9.2. Interface Layer
#### 4.2.9.3. Application Layer
#### 4.2.9.4. Infrastructure Layer
#### 4.2.9.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.9.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.9.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.9.6.2. Bounded Context Database Design Diagram
