<div align="center">

<img src="assets/logo.png" alt="Logo de StockVelia" width="130" height="130">

# STOCKVELIA

### Documentación oficial del proyecto

**Plataforma web de gestión de inventarios y control financiero para microempresas y PYMES**

<br>

![Estado](https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-6B21A8?style=for-the-badge)
![Metodologia](https://img.shields.io/badge/METODOLOG%C3%8DA-SCRUM-7C3AED?style=for-the-badge)
![Sprints](https://img.shields.io/badge/SPRINTS-5-4C1D95?style=for-the-badge)
![Historias](https://img.shields.io/badge/HISTORIAS%20DE%20USUARIO-20-6D28D9?style=for-the-badge)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

<br>

[Descripción](#1-descripción-del-proyecto) &nbsp;|&nbsp;
[Documentos](#4-catálogo-de-documentos) &nbsp;|&nbsp;
[Requisitos](#8-requisitos-del-sistema) &nbsp;|&nbsp;
[Arquitectura](#11-arquitectura-del-sistema) &nbsp;|&nbsp;
[API](#14-documentación-de-la-api) &nbsp;|&nbsp;
[Sprints](#16-gestión-del-proyecto-y-planeación-de-sprints)

</div>

<br>

---

## Índice

| N° | Sección | N° | Sección |
|:--:|---------|:--:|---------|
| 01 | [Descripción del proyecto](#1-descripción-del-proyecto) | 12 | [Diseño de la base de datos](#12-diseño-de-la-base-de-datos) |
| 02 | [Equipo de trabajo](#2-equipo-de-trabajo) | 13 | [Tecnologías utilizadas](#13-tecnologías-utilizadas) |
| 03 | [Estructura del repositorio](#3-estructura-del-repositorio) | 14 | [Documentación de la API](#14-documentación-de-la-api) |
| 04 | [Catálogo de documentos](#4-catálogo-de-documentos) | 15 | [Seguridad](#15-seguridad) |
| 05 | [Contexto y problema que resuelve](#5-contexto-y-problema-que-resuelve) | 16 | [Gestión del proyecto y sprints](#16-gestión-del-proyecto-y-planeación-de-sprints) |
| 06 | [Objetivos](#6-objetivos) | 17 | [Estimación de costos](#17-estimación-de-costos) |
| 07 | [Alcance y limitaciones](#7-alcance-y-limitaciones) | 18 | [Diagramas UML](#18-diagramas-uml) |
| 08 | [Requisitos del sistema](#8-requisitos-del-sistema) | 19 | [Interfaces y prototipos](#19-diseño-de-interfaces-y-prototipos) |
| 09 | [Casos de uso](#9-casos-de-uso) | 20 | [Estado de la documentación](#20-estado-de-la-documentación) |
| 10 | [Historias de usuario](#10-historias-de-usuario) | 21 | [Cómo usar este repositorio](#21-cómo-usar-este-repositorio) |
| 11 | [Arquitectura del sistema](#11-arquitectura-del-sistema) | 22 | [Créditos](#22-créditos) |

---

## Ficha del proyecto

| | |
|:--|:--|
| **Proyecto** | StockVelia |
| **Programa de formación** | Análisis y Desarrollo de Software |
| **Institución** | SENA - Centro de Gestión de Mercados, Logística y Tecnologías de la Información (CGMLTI) |
| **Ciudad** | Bogotá D.C., Colombia |
| **N° de ficha** | 3311976 / 3311983 |
| **Metodología** | Scrum, 5 sprints semanales |
| **Stack** | React, Node.js, Express, PostgreSQL |

---

## 1. Descripción del proyecto

StockVelia es una solución tecnológica integral compuesta por una aplicación web responsiva que automatiza, centraliza y optimiza la gestión de inventarios y el control de existencias en tiempo real para microempresas y PYMES.

A diferencia de un gestor de inventarios convencional, StockVelia opera como un asistente financiero inteligente: monitorea el flujo de mercancía, dispara alertas tempranas ante umbrales críticos de stock y centraliza la auditoría de todos los movimientos, permitiendo que un comerciante sin conocimientos técnicos avanzados tome control de los activos de su negocio desde cualquier dispositivo.

### Capacidades principales

| Módulo | Capacidad |
|--------|-----------|
| **Seguridad** | Registro de microempresa, roles (Administrador y Empleado), autenticación JWT y cifrado Bcrypt |
| **Catálogo** | Productos con categorías, precios, stock y stock mínimo |
| **Inventario** | Entradas y salidas transaccionales con validación de stock insuficiente |
| **Tiempo real** | Actualización de stock en todas las terminales mediante WebSockets |
| **Alertas** | Resaltado visual automático de productos con stock bajo |
| **Reportes** | Historial auditable, filtros por fecha y exportación a PDF y Excel |

---

## 2. Equipo de trabajo

| Integrante |
|------------|
| Ivonne Dayana Sanchez Contreras |
| Jaider Andrés González Ovalle |
| Alan Felipe Caro Olaya |
| Jonathan Andres Jimenez Aguilera |

**Roles Scrum definidos en la propuesta técnica:** Product Owner y Diseñador de Base de Datos; Scrum Master y Analista de Calidad (QA); Desarrollo Backend; Desarrollo Frontend y Diseño UX/UI.

**Presentado a:** Jeysson Contreras y Eduardo Foglia (documentación general); Inst. Freddy Ardila (propuesta técnica y planeación de sprints).

---

## 3. Estructura del repositorio

```text
Documentacion-StockVelia/
|
|-- assets/
|   `-- logo.png
|
|-- Cálculo de horas - Historias de Usuario - StockVelia.xlsx
|-- Daily - Stock Velia.xlsx
|-- Documentación de StockVelia.docx
|-- Documentación de StockVelia.pdf
|-- Estimación de Costos - StockVelia.xlsx
|-- Planeación de Sprints - StockVelia.pdf
|-- Plantilla Historias de Usuario - StockVelia.xlsx
|-- Priorización de Historias de Usuario - StockVelia.xlsx
|-- Propuesta Técnica StocVelia - 3311983.pdf
`-- README.md
```

---

## 4. Catálogo de documentos

| Documento | Formato | Descripción |
|-----------|:-------:|-------------|
| **Documentación de StockVelia** | DOCX / PDF | Documento maestro: análisis del problema, objetivos, requisitos, casos de uso, historias de usuario, UML, arquitectura, base de datos, interfaces, API y estructura del proyecto. Incluye versión editable y versión de lectura. |
| **Propuesta Técnica StocVelia** | PDF | Descripción de la solución, objetivos, alcance, planificación por sprints, cronograma de cinco semanas, fichas técnicas y presupuesto. |
| **Planeación de Sprints** | PDF | Planificación ágil con referencia al tablero de ClickUp del proyecto. |
| **Plantilla Historias de Usuario** | XLSX | Plantilla estandarizada de historias de usuario con criterios de aceptación. |
| **Priorización de Historias de Usuario** | XLSX | Matriz de priorización del backlog. |
| **Cálculo de horas** | XLSX | Estimación de horas de esfuerzo por historia de usuario y por sprint. |
| **Estimación de Costos** | XLSX | Modelo de costos: mano de obra, infraestructura, licencias e imprevistos. |
| **Daily - Stock Velia** | XLSX | Registro de las reuniones diarias (Daily Scrum). |

---

## 5. Contexto y problema que resuelve

Las microempresas y PYMES operan con márgenes estrechos y, en su mayoría, administran el inventario con cuadernos, hojas de cálculo desconectadas o memoria operativa. El problema central no es la falta de espacio para contar productos, sino el drenaje silencioso de capital operativo.

| Problema | Descripción |
|----------|-------------|
| **Fugas de dinero hormiga** | Pérdidas por productos caducados, deteriorados o diferencias de inventario no detectadas a tiempo |
| **Quiebres de stock** | Imposibilidad de prever el agotamiento de productos de alta rotación |
| **Capital atrapado** | Exceso de mercancía sin rotación que inmoviliza el flujo de caja |
| **Cero visibilidad financiera** | Registros manuales propensos a error que impiden reportes y auditorías confiables |

### Árbol de problemas

| Nivel | Descripción |
|-------|-------------|
| **Efectos** | Fugas financieras, quiebres de stock, dinero estancado y decisiones a ciegas |
| **Problema central** | Deficiente gestión y control operativo del inventario en microempresas |
| **Causas** | Métodos manuales (cuadernos y Excel), ausencia de alertas y cero trazabilidad |

---

## 6. Objetivos

### Objetivo general

Desarrollar y desplegar una plataforma web de gestión de inventarios y control financiero para microempresas y PYMES, orientada a blindar el capital operativo, automatizar el flujo de mercancías en tiempo real y mitigar las mermas comerciales.

### Objetivos específicos

1. Diseñar la arquitectura de seguridad y datos con un modelo relacional en PostgreSQL, autenticación JWT y cifrado Bcrypt.
2. Construir el núcleo transaccional en tiempo real con Node.js, Express y una interfaz responsiva en React.
3. Implementar el motor de alertas de stock mínimo y los módulos de reportes y exportación a PDF y Excel.
4. Validar usabilidad, seguridad y desempeño mediante pruebas de calidad (QA).

### Indicadores de éxito

| Indicador | Meta |
|-----------|------|
| Disponibilidad del sistema (uptime) | Mayor o igual al 99% en entornos de prueba cloud |
| Tiempo de respuesta de la interfaz | Menor a 2 segundos |
| Precisión de alertas de stock | 100% de disparo automático al cruzar el umbral mínimo |
| Consistencia transaccional | 0% de pérdida en pruebas de entradas y salidas simultáneas |
| Usabilidad (SUS) | Superior al 85% |

---

## 7. Alcance y limitaciones

<table>
<tr>
<th width="33%">Incluido</th>
<th width="33%">Excluido en esta versión</th>
<th width="34%">Limitaciones</th>
</tr>
<tr valign="top">
<td>

- Autenticación y roles
- Catálogo de productos y categorías
- Entradas y salidas en tiempo real
- Alertas por stock mínimo
- Historial y reportes PDF/Excel
- Despliegue HTTPS

</td>
<td>

- Pasarelas de pago
- Facturación electrónica
- App móvil nativa
- Integración con transportadoras
- Lectura por cámara
- IA predictiva
- Alertas por correo o SMS
- Nómina y RR.HH.

</td>
<td>

- Requiere internet estable
- Sin integración nativa con lectores láser o impresoras térmicas
- No sustituye un sistema contable

</td>
</tr>
</table>

---

## 8. Requisitos del sistema

<details open>
<summary><strong>Requisitos funcionales</strong></summary>

<br>

| Código | Módulo | Requisito |
|:------:|--------|-----------|
| RF-01 | Seguridad | Registro de usuarios con rol asignado |
| RF-02 | Seguridad | Autenticación segura con token JWT |
| RF-03 | Seguridad | Cierre de sesión con invalidación del token |
| RF-04 | Seguridad | Gestión de usuarios (CRUD con borrado lógico) |
| RF-05 | Catálogo | Registro de productos |
| RF-06 | Catálogo | Modificación de artículos |
| RF-07 | Catálogo | Baja lógica de productos |
| RF-08 | Inventario | Registro de entradas |
| RF-09 | Inventario | Registro de salidas con validación de disponibilidad |
| RF-10 | Inventario | Alertas de stock mínimo |
| RF-11 | Reportes | Historial de movimientos por fecha y producto |
| RF-12 | Reportes | Exportación a PDF y Excel |

</details>

<details>
<summary><strong>Requisitos no funcionales</strong></summary>

<br>

| Código | Categoría | Requisito |
|:------:|-----------|-----------|
| RNF-01 | Rendimiento | Consultas y vistas en menos de 2 segundos |
| RNF-02 | Seguridad | Contraseñas con hash Bcrypt, nunca en texto plano |
| RNF-03 | Seguridad | Comunicaciones cifradas con HTTPS |
| RNF-04 | Concurrencia | Aislamiento transaccional en PostgreSQL |
| RNF-05 | Usabilidad | Diseño responsivo para escritorio, tablet y móvil |
| RNF-06 | Mantenibilidad | Arquitectura modular y escalable |

</details>

<details>
<summary><strong>Requisitos de negocio</strong></summary>

<br>

| Código | Requisito |
|:------:|-----------|
| RN-01 | Mitigación de fugas financieras mediante auditoría de cada movimiento |
| RN-02 | Accesibilidad operativa sin costos ocultos |
| RN-03 | Curva de aprendizaje menor a 15 minutos |
| RN-04 | Trazabilidad y control por roles (RBAC) |

</details>

---

## 9. Casos de uso

| Código | Caso de uso | Actor principal |
|:------:|-------------|-----------------|
| CU-01 | Autenticación en el sistema | Administrador / Operador |
| CU-02 | Gestión de usuarios (CRUD) | Administrador |
| CU-03 | Registro de nuevo producto | Administrador / Operador |
| CU-04 | Registro de entrada de mercancía | Administrador / Operador |
| CU-05 | Registro de salida / venta | Administrador / Operador |
| CU-06 | Generación de alerta de stock mínimo | Sistema (automático) |
| CU-07 | Exportación de reportes | Administrador |

> [!NOTE]
> La especificación detallada de cada caso (precondiciones, flujo principal y flujos alternativos) se encuentra en la sección 5 del documento maestro.

---

## 10. Historias de usuario

El backlog contiene **20 historias de usuario** con un esfuerzo total de **89 puntos**.

<details open>
<summary><strong>Gestión de seguridad y usuarios</strong> (28 puntos)</summary>

<br>

| ID | Título | Rol | Puntos |
|:--:|--------|-----|:------:|
| HU-001 | Registro de microempresa y administrador | Emprendedor | 5 |
| HU-002 | Inicio de sesión seguro (JWT) | Usuario registrado | 8 |
| HU-003 | Cierre de sesión (Logout) | Usuario | 2 |
| HU-004 | Modificación de usuarios | Administrador | 5 |
| HU-005 | Eliminación de usuarios (borrado lógico) | Administrador | 3 |
| HU-006 | Control de acceso por roles | Sistema | 5 |

</details>

<details>
<summary><strong>Gestión de catálogo de productos</strong> (14 puntos)</summary>

<br>

| ID | Título | Rol | Puntos |
|:--:|--------|-----|:------:|
| HU-007 | Registro de productos con atributos completos | Administrador | 5 |
| HU-008 | Edición de productos existentes | Administrador | 3 |
| HU-009 | Eliminación de productos (borrado lógico) | Administrador | 3 |
| HU-010 | Consulta básica de productos | Usuario | 3 |

</details>

<details>
<summary><strong>Movimientos e inventario en tiempo real</strong> (23 puntos)</summary>

<br>

| ID | Título | Rol | Puntos |
|:--:|--------|-----|:------:|
| HU-011 | Registro de entradas (compras y devoluciones) | Usuario | 5 |
| HU-012 | Registro de salidas (ventas y bajas) | Usuario | 5 |
| HU-013 | Visualización de stock en tiempo real | Usuario | 8 |
| HU-014 | Configuración de inventario mínimo | Administrador | 2 |
| HU-015 | Sistema de alertas por bajo stock | Usuario | 3 |

</details>

<details>
<summary><strong>Reportes, exportación y búsqueda avanzada</strong> (24 puntos)</summary>

<br>

| ID | Título | Rol | Puntos |
|:--:|--------|-----|:------:|
| HU-016 | Generación de reportes generales | Administrador | 5 |
| HU-017 | Consulta de movimientos por rango de fechas | Usuario | 3 |
| HU-018 | Historial individual de producto | Usuario | 3 |
| HU-019 | Exportación de datos a PDF y Excel | Administrador | 8 |
| HU-020 | Búsqueda avanzada multi-criterio | Usuario | 5 |

</details>

> [!NOTE]
> Los criterios de aceptación completos están en la sección 6 del documento maestro y en los archivos de plantilla y priorización de historias de usuario.

---

## 11. Arquitectura del sistema

StockVelia adopta un **monolito modular basado en el patrón MVC**, con API REST para la comunicación síncrona y WebSockets para la sincronización en tiempo real.

```text
+---------------------------+        HTTPS / WSS        +---------------------------+
|   VISTA  (Frontend)       | <-----------------------> |   CONTROLADOR  (Backend)  |
|   React + Vite            |                           |   Node.js + Express       |
|   Socket.io client        |                           |   Socket.io server        |
+---------------------------+                           +-------------+-------------+
                                                                      |
                                                           Middlewares: JWT + RBAC
                                                                      |
                                                        +-------------v-------------+
                                                        |   MODELO  (Persistencia)  |
                                                        |   PostgreSQL              |
                                                        |   ACID + Triggers         |
                                                        +---------------------------+
```

| Capa | Tecnología | Responsabilidad |
|------|------------|-----------------|
| **Vista** | React + Vite | Presentación, formularios, catálogo, alertas y actualización reactiva |
| **Controlador** | Node.js + Express | Lógica de negocio, validación de datos y orquestación de peticiones |
| **Modelo** | PostgreSQL | Estructura de datos, integridad referencial, transacciones ACID y triggers |
| **Transversal** | Middlewares | Verificación de JWT, control de acceso por roles (RBAC) y sanitización |

### Justificación

| Criterio | Razón |
|----------|-------|
| Cohesión con el dominio | MVC separa de forma natural las vistas de inventario de los modelos transaccionales |
| Simplicidad operativa | Un monolito modular evita la sobreingeniería de microservicios para microempresas |
| Tiempo real | Los eventos de Socket.io propagan cada cambio a todas las terminales sin recargar |

---

## 12. Diseño de la base de datos

| Grupo | Tablas |
|-------|--------|
| **Nucleares** | `empresa`, `roles`, `permisos`, `roles_permisos`, `categorias`, `usuario` |
| **Operacionales** | `productos`, `movimientos_inventario` |
| **Soporte y seguridad** | `auditoria`, `tokens_blacklist`, `codigos_recuperacion` |

### Relaciones principales

| Origen | Cardinalidad | Destino |
|--------|:------------:|---------|
| `empresa` | 1 : N | `usuario` |
| `empresa` | 1 : N | `productos` |
| `roles` | 1 : N | `usuario` |
| `roles` | N : M | `permisos` (tabla `roles_permisos`) |
| `categorias` | 1 : N | `productos` |
| `productos` | 1 : N | `movimientos_inventario` |
| `usuario` | 1 : N | `movimientos_inventario` |
| `usuario` | 1 : N | `auditoria` |

### Modelo físico

- Identificadores `VARCHAR(20)` generados con la función PL/pgSQL `generar_id_formateado()`.
- Trigger `trg_actualizar_stock` que ejecuta `actualizar_stock()`: valida que no existan existencias negativas y recalcula el stock en cada inserción de `movimientos_inventario`.
- Restricciones `CHECK` sobre precio, stock, stock mínimo, cantidad y tipo de movimiento (`ENTRADA`, `SALIDA`, `BAJA`).
- Borrado lógico mediante campos de estado para preservar la trazabilidad histórica.

### Normalización

El diseño cumple la Tercera Forma Normal (3NF): valores atómicos (1NF), dependencia total de la clave primaria (2NF) y eliminación de dependencias transitivas mediante la separación de `empresa`, `categorias` y `permisos` (3NF).

---

## 13. Tecnologías utilizadas

| Capa | Tecnologías |
|------|-------------|
| **Lenguaje** | JavaScript (ES6+) |
| **Frontend** | React, Vite, React Router, Axios, CSS3 |
| **Backend** | Node.js, Express.js, Socket.io |
| **Seguridad** | JSON Web Token (JWT), Bcrypt |
| **Correo transaccional** | Nodemailer |
| **Base de datos** | PostgreSQL, pool de conexiones `pg` |
| **Reportes** | jsPDF, ExcelJS |
| **Infraestructura** | Contenedores, Nginx, VPS o PaaS en la nube, HTTPS con Let's Encrypt |
| **Control de versiones** | Git y GitHub |
| **Entorno de desarrollo** | Visual Studio Code |
| **Gestión ágil** | ClickUp |

---

## 14. Documentación de la API

> [!IMPORTANT]
> Los endpoints protegidos requieren el encabezado `Authorization: Bearer <token>`.

<details open>
<summary><strong>Autenticación</strong> <code>/api/auth</code></summary>

<br>

| Método | Endpoint | Descripción |
|:------:|----------|-------------|
| `POST` | `/api/auth/register` | Registra una empresa y su usuario administrador |
| `POST` | `/api/auth/login` | Autentica al usuario y genera un JWT con vigencia de 2 horas |
| `POST` | `/api/auth/forgot-password` | Envía por correo un código de 6 dígitos con vigencia de 15 minutos |
| `POST` | `/api/auth/reset-password` | Valida el código y restablece la contraseña |
| `POST` | `/api/auth/logout` | Revoca el token registrándolo en la lista negra |

</details>

<details>
<summary><strong>Productos</strong> <code>/api/productos</code></summary>

<br>

| Método | Endpoint | Descripción |
|:------:|----------|-------------|
| `POST` | `/api/productos` | Crea un producto verificando que el código no esté duplicado |
| `GET` | `/api/productos` | Lista los productos activos de la empresa |
| `PUT` | `/api/productos/:id` | Actualiza un producto |
| `DELETE` | `/api/productos/:id` | Eliminación lógica del producto |

</details>

<details>
<summary><strong>Categorías</strong> <code>/api/categorias</code></summary>

<br>

| Método | Endpoint | Descripción |
|:------:|----------|-------------|
| `POST` | `/api/categorias` | Crea una categoría |
| `GET` | `/api/categorias` | Lista las categorías en orden alfabético |

</details>

<details>
<summary><strong>Movimientos de inventario</strong> <code>/api/movimientos</code></summary>

<br>

| Método | Endpoint | Descripción |
|:------:|----------|-------------|
| `POST` | `/api/movimientos` | Registra una entrada, salida o baja de stock |
| `GET` | `/api/movimientos` | Obtiene el historial de movimientos de la empresa |

</details>

<details>
<summary><strong>Usuarios</strong> <code>/api/usuarios</code></summary>

<br>

| Método | Endpoint | Descripción |
|:------:|----------|-------------|
| `GET` | `/api/usuarios?id_empresa=` | Lista los usuarios de una empresa |
| `POST` | `/api/usuarios` | Crea un usuario secundario con validación de contraseña |
| `PUT` | `/api/usuarios/estado/:id` | Alterna el estado activo o inactivo de un usuario |

</details>

### Códigos de respuesta frecuentes

| Código | Significado |
|:------:|-------------|
| `200` / `201` | Operación exitosa / recurso creado |
| `400` | Datos inválidos, duplicados o stock insuficiente |
| `401` | Credenciales incorrectas o token ausente o revocado |
| `403` | Sin autorización, cuenta desactivada o token inválido |
| `404` | Recurso no encontrado |
| `423` | Cuenta bloqueada temporalmente |
| `500` | Error interno del servidor |

El detalle de cada endpoint (parámetros, request y response) está en la sección 15 del documento maestro.

---

## 15. Seguridad

| Mecanismo | Descripción |
|-----------|-------------|
| **Autenticación** | Tokens JWT firmados con expiración temporal |
| **Cierre de sesión seguro** | Invalidación del token mediante lista negra y limpieza del almacenamiento local |
| **Control de acceso (RBAC)** | Validación del rol en cada petición; acciones críticas restringidas al Administrador (respuesta 403) |
| **Protección de contraseñas** | Hash con Bcrypt; mínimo 6 caracteres, una mayúscula, una minúscula y un número |
| **Fuerza bruta** | Bloqueo temporal de la cuenta tras intentos fallidos consecutivos |
| **Cifrado en tránsito** | HTTPS para la API y WSS para WebSockets |
| **Integridad transaccional** | Transacciones ACID y trigger de validación de stock |
| **Borrado lógico** | Preserva la integridad referencial y la auditoría histórica |
| **Auditoría** | Tabla `auditoria` con el registro de acciones por usuario |

---

## 16. Gestión del proyecto y planeación de sprints

El proyecto se gestiona con Scrum en cinco sprints, uno por semana, según la Propuesta Técnica. El seguimiento de tareas se realiza en el tablero de ClickUp referenciado en `Planeación de Sprints - StockVelia.pdf`.

| Sprint | Enfoque | Historias de usuario | Puntos |
|:------:|---------|----------------------|:------:|
| **1** | Acceso y base de usuarios | HU-001, HU-002, HU-003, HU-006 | 20 |
| **2** | Administración de usuarios e historial | HU-004, HU-005, HU-017, HU-018 | 14 |
| **3** | Catálogo de productos | HU-007, HU-008, HU-009, HU-010 | 14 |
| **4** | Movimientos y stock | HU-011, HU-012, HU-013, HU-014 | 20 |
| **5** | Alertas, reportes, exportación y despliegue cloud | HU-015, HU-016, HU-019, HU-020 | 21 |
| | **Total** | **20 historias** | **89** |

### Hitos por semana

| Semana | Hito | Entregable principal |
|:------:|------|----------------------|
| 1 | Núcleo de seguridad y acceso | Base de datos inicial, API de registro y login, interfaces de autenticación |
| 2 | Panel de control de personal | Módulo de empleados con borrado lógico y filtros de auditoría por fechas |
| 3 | Estructura de catálogo maestro | Catálogo normalizado con búsqueda parcial y paginación desde el servidor |
| 4 | Motor transaccional de existencias | APIs de inventario con transacciones atómicas y validación de stock insuficiente |
| 5 | Sistema analítico y despliegue cloud | Alertas visuales, exportación PDF y Excel, QA y despliegue HTTPS en producción |

El seguimiento diario del equipo se registra en `Daily - Stock Velia.xlsx`.

---

## 17. Estimación de costos

El detalle financiero se encuentra en `Estimación de Costos - StockVelia.xlsx` y en la sección 7 de la Propuesta Técnica.

| Rubro | Descripción |
|-------|-------------|
| **Mano de obra** | Horas de desarrollo por perfil profesional y sprint |
| **Infraestructura** | VPS o hosting, dominio propio y certificado SSL (Let's Encrypt, gratuito) |
| **Licencias** | Herramientas de software |
| **Imprevistos** | Reserva del 10% sobre el costo por sprint |

Infraestructura anual estimada: servidor VPS $480.000 COP y dominio $60.000 COP, para un total de **$540.000 COP**.

---

## 18. Diagramas UML

| Diagrama | Propósito |
|----------|-----------|
| **Casos de uso** | Funciones del sistema por actor |
| **Clases** | Entidades persistentes, atributos y relaciones |
| **Secuencia** | Registro de una salida de inventario de extremo a extremo |
| **Actividades** | Flujo de control y alerta de stock mínimo |
| **Estados** | Ciclo de vida del producto: registrado, activo, crítico, agotado e inactivo |
| **Componentes** | Organización modular en capas |
| **Despliegue** | Topología en la nube: cliente, servidor de aplicación y base de datos gestionada |
| **Paquetes** | Organización del código: `config`, `controllers`, `models`, `routes`, `middlewares`, `utils` |
| **Entidad-Relación** | Modelo de datos relacional |

Las versiones gráficas están enlazadas dentro del documento maestro.

---

## 19. Diseño de interfaces y prototipos

| Módulo | Vista | Función |
|--------|-------|---------|
| **Autenticación** | `LoginView` / `RegisterView` | Ingreso seguro y registro de microempresa |
| **Panel de control** | `DashboardView` | Indicadores, valorización del inventario y alertas críticas |
| **Catálogo** | `CatalogView` | Búsqueda, filtros, alta, edición y baja lógica de productos |
| **Movimientos** | `InventoryMovementsView` | Registro de entradas, salidas y bajas |

**Prototipado:** wireframes de baja fidelidad para la estructura y jerarquía de la información, y mockups de alta fidelidad diseñados en Figma para validar la experiencia de usuario.

<details>
<summary><strong>Estructura del código fuente (referencia)</strong></summary>

<br>

```text
backend/
  src/
    config/        Conexión a base de datos (db.js) y correo (mailer.js)
    controllers/   Lógica de negocio (auth, productos, movimientos, etc.)
    models/        Esquemas y consultas
    routes/        Endpoints de la API REST
    middlewares/   Validación de JWT, RBAC y validadores
    utils/         Hashing, exportación PDF y Excel
frontend/
  src/
    components/
      Dashboard/   Stock, categorías, usuarios y reportes
    services/      Servicios de comunicación con Axios (api.js)
```

</details>

---

## 20. Estado de la documentación

| Sección del documento maestro | Estado |
|-------------------------------|:------:|
| 1. Introducción | Completa |
| 2. Análisis del problema | Completa |
| 3. Objetivos | Completa |
| 4. Levantamiento de requisitos | Completa |
| 5. Casos de uso | Completa |
| 6. Historias de usuario | Completa |
| 7. Diagramas UML | Completa |
| 8. Arquitectura del sistema | Completa |
| 9. Diseño de bases de datos | Completa |
| 10. Normalización | Completa |
| 11. Diseño de interfaces | Completa |
| 12. Prototipos | Completa |
| 13. Estructura del proyecto | Completa |
| 14. Tecnologías utilizadas | Completa |
| 15. APIs | Completa |
| 16 a 29. Seguridad, rendimiento, pruebas, gestión, versiones, instalación, manuales, mantenimiento, riesgos, mejoras, conclusiones, recomendaciones y bibliografía | Pendiente |

---

## 21. Cómo usar este repositorio

1. Para una visión general del proyecto, lea `Documentación de StockVelia.pdf`.
2. Para editar la documentación, utilice el archivo DOCX y vuelva a exportar el PDF al terminar.
3. Para el alcance, cronograma y presupuesto acordados, consulte `Propuesta Técnica StocVelia - 3311983.pdf`.
4. Para el backlog, la priorización y las estimaciones, utilice los archivos de Excel correspondientes.
5. Para el seguimiento del equipo, revise `Daily - Stock Velia.xlsx` y el tablero de ClickUp.

### Convenciones

- Mantener sincronizadas las versiones DOCX y PDF del documento maestro.
- Conservar el nombre de los archivos para no romper las referencias entre documentos.
- Registrar cada cambio relevante con un mensaje de commit descriptivo.

---

## 22. Créditos

<div align="center">

<img src="assets/logo.png" alt="StockVelia" width="70" height="70">

**StockVelia**

Proyecto desarrollado por aprendices del programa Análisis y Desarrollo de Software

**SENA - Centro de Gestión de Mercados, Logística y Tecnologías de la Información (CGMLTI)**

Bogotá D.C., Colombia

Ivonne Dayana Sanchez Contreras &nbsp;|&nbsp; Jaider Andrés González Ovalle &nbsp;|&nbsp; Alan Felipe Caro Olaya &nbsp;|&nbsp; Jonathan Andres Jimenez Aguilera

</div>