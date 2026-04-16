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
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Alcantara Cruz, Rodrigo Alonso** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Quincho Gamarra, Paulo Percy** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Valerio Garcia, Adrian Emanuel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Antonio Loayza, Luiggi Jeremy Jouvenel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] <br><br> **Oroncoy Almeyda, Alejandro Daniel** <br> **AV1:** [Acción] <br> **TB1:** [Acción] <br> **AV2:** [Acción] <br> **TB2:** [Acción] | [pending...] |

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language
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
