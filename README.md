# Temario completo

Duración total estimada: ≈18 meses (≈78 semanas) estudiando 1 hora al día (7 h/semana).
(He diseñado el plan para avanzar paso a paso, con objetivos semanales pequeños, ejercicios prácticos y mini-proyectos frecuentes; al final de cada fase hay un proyecto grande para integrar lo aprendido.)

## Indice

- [Ir a ver el prompt utilizado](#prompt-utilizado)
- [Ir a la fase 1](#fase-1)
- [Ir a la fase 2](#fase-2)
- [Ir a la fase 3](#fase-3)
- [Ir a la fase 4](#fase-4)
- [Ir a la fase 5](#fase-5)
- [Ir a la fase 6](#fase-6)
- [Ir a la fase 7](#fase-7)
- [Ir a la fase 8](#fase-8)
- [Ir a la fase 9](#fase-9)
- [Ir a la fase 10](#fase-10)
- [Ir a la fase 11](#fase-11)
- [Ir a la fase 12](#fase-12)
- [Requisitos de paso entre fases](#requisitos-de-paso-entre-fases-resumen)
- [Ejercicios prácticos y mini-proyectos](#ejercicios-prácticos-y-mini-proyectos-resumen)
- [Recomendaciones de herramientas y recursos](#recomendaciones-de-herramientas-y-recursos)
- [Buenas prácticas de seguridad](#buenas-prácticas-de-seguridad-resumen-práctico)
- [Errores comunes de principiantes](#errores-comunes-de-principiantes-y-cómo-evitarlos)
- [Hábitos para estudiar 1 hora diaria](#hábitos-y-técnicas-para-estudiar-1-hora-diaria)
- [Preparar proyectos para trabajo o freelance](#cómo-preparar-proyectos-para-conseguir-trabajo-y-clientes-freelance)
- [Recursos sugeridos](#recursos-sugeridos-rápidos)

---

## FASE 1 

[Ir a ver la carpeta de la fase 1](./Phase01)

### Fundamentos de computación y programación (Semanas 1–6) — 6 semanas

Objetivo de la fase: Entender qué es programar, cómo funciona una computadora y los conceptos básicos que sostienen todo lo demás.

#### Semana 1

[Ir a ver la carpeta de la semana 1](./Phase01/Week01/README.md)

- Qué es la programación — definición, paradigma imperativo vs declarativo.

- Cómo funciona una computadora a alto nivel — CPU, memoria, disco, sistema operativo.

- Ejercicio práctico: escribe en una nota (puede ser texto) 5 ejemplos de problemas que querrías automatizar y dibuja el "input → proceso → output".

#### Semana 2

[Ir a ver la carpeta de la semana 2](./Phase01/Week02/README.md)

- Sistema operativo y terminal — ¿qué es la terminal? conceptos: procesos, archivos, permisos.

- Introducción a Linux básico (navegar carpetas, comandos ls, cd, cat, mkdir, rm, cp, mv).

- Ejercicio práctico: en tu sistema (o una VM/WSL) crea una carpeta aprendizaje y practica comandos; toma nota de 10 comandos usados.

#### Semana 3

[Ir a ver la carpeta de la semana 3](./Phase01/Week03/README.md)

- ¿Cómo funciona Internet? TCP/IP, modelos OSI simplificado.

- DNS: qué hace, resolución de nombres.

- Ejercicio práctico: usa ping, nslookup/dig (o nslookup en Windows) hacia google.com y registra los resultados; explica qué hizo DNS.

#### Semana 4

[Ir a ver la carpeta de la semana 4](./Phase01/Week04/README.md)

- HTTP/HTTPS — requests/responses, métodos (GET, POST, PUT, DELETE), códigos de estado.

- Cliente vs servidor; qué es una API.

- Ejercicio práctico: usa el navegador y las herramientas de devtools (Network) para inspeccionar una petición GET y POST en una página simple.

#### Semana 5

[Ir a ver la carpeta de la semana 5](./Phase01/Week05/README.md)

- Estructura de un proyecto de software a alto nivel — - archivos, dependencias, versiones.

- Concepto de entorno de desarrollo: IDE/editor, terminal, git.

- Ejercicio práctico: instala VSCode (o usa tu editor preferido) y crea un archivo hola_mundo.txt, súbelo a una carpeta local y verifica con la terminal.

#### Semana 6

[Ir a ver la carpeta de la semana 6](./Phase01/Week06/README.md)

- Buenas prácticas iniciales: organizar carpetas, nombrado, documentación mínima (README).

- Mini-proyecto: escribe un documento README.md que explique quién eres, qué quieres aprender y un plan semanal para el próximo mes. Sube el README a una carpeta local.

---

Habilidades que debes dominar antes de Fase 2: uso básico de terminal, nociones de Internet/HTTP, capacidad de organizar archivos y documentar.

---

## FASE 2 

### Fundamentos del desarrollo web (Semanas 7–14) — 8 semanas

Objetivo: Aprender HTML, CSS, estructura web y cómo se sirven páginas desde un servidor.

#### Semana 7

- HTML básico: estructura de un documento, etiquetas html, head, body, h1..h6, p, a, img, ul/ol.

- Ejercicio práctico: crear index.html con título, párrafo y una lista de tus habilidades.

#### Semana 8

- HTML avanzado: formularios (form, input, label, select), semantic tags (header, footer, main, nav, section).

- Ejercicio práctico: crea un formulario de contacto simple (nombre, correo, mensaje).

#### Semana 9

- CSS básico: selectores, cajas, modelo de caja (box model), margenes, padding, display.

- Ejercicio práctico: añade un archivo styles.css y dale estilo al index.html.

#### Semana 10

- Layouts con CSS: Flexbox y Grid (conceptos clave y cuándo usar cada uno).

- Ejercicio práctico: crea una página con un header, sidebar y contenido usando Flexbox.

#### Semana 11

- Buenas prácticas de HTML/CSS: accesibilidad básica (alt, labels), responsive (meta viewport), mobile-first.

- Ejercicio práctico: adapta tu página para que se vea bien en móvil (prueba en devtools).

#### Semana 12

- Cómo funciona el navegador internamente (rendering, DOM, CSSOM, reflow/repaint).

- Ejercicio práctico: usa console para manipular el DOM (pequeñas pruebas desde devtools).

#### Semana 13

- Introducción a JavaScript (qué es, dónde corre — navegador y servidor).

- Primeros scripts: `<script>` inline y externo, console.log, variables simples.

- Ejercicio práctico: añade un pequeño script que valide el formulario de contacto (campo obligatorio).

#### Semana 14

- Mini-proyecto de la fase: Landing page personal (una página index.html + styles.css + main.js) que muestre tu CV, formulario de contacto y sea responsive.

- Entregable: alojar localmente y documentar el proyecto en un README.

---

Habilidades requeridas para la Fase 3: HTML semántico, CSS (Flex/Grid), base de DOM y scripts simples.

---

## FASE 3 

### JavaScript profundo (Semanas 15–28) — 14 semanas

Objetivo: Dominar JavaScript moderno (ES6+), entender cómo funciona internamente y preparar la base para React.

#### Semana 15

- Tipos, variables (let, const), operadores, control de flujo (if, switch).

- Ejercicio práctico: pequeño script que calcule y muestre en consola la tabla de multiplicar de un número.

#### Semana 16

- Funciones, ámbito (scope), hoisting, closures (introducción).

- Ejercicio práctico: crear una función que genere IDs únicos (usa closures).

#### Semana 17

- Arrays y objetos: métodos comunes (map, filter, reduce).

- Ejercicio práctico: dado un array de objetos personas, filtra mayores de edad y crea lista de nombres.

#### Semana 18

- Asincronía: callbacks, Promises, async/await.

- Ejercicio práctico: simula una llamada a una API con fetch y maneja la respuesta con async/await.

#### Semana 19

- Módulos ES6 (import/export) y bundlers básicos (concepto — no profundizar aún).

- Ejercicio práctico: divide tu código en módulos y cárgalos con type="module".

#### Semana 20

- Manipulación avanzada del DOM y eventos (delegación de eventos).

- Ejercicio práctico: crea una lista dinámica donde puedes agregar/borrar items sin recargar la página.

#### Semana 21

- Patrones de diseño simples en JS: módulo, fábrica, pub/sub (concepto).

- Ejercicio práctico: implementa un pequeño pub/sub para comunicar módulos en tu app.

#### Semana 22

- Error handling, debugging (devtools), profiling básico de rendimiento.

- Ejercicio práctico: utiliza breakpoints y arregla un bug intencional en un script.

#### Semana 23

- Testing básico en JS: conceptos de unit testing, introducción a Jest (concepto y por qué).

- Ejercicio práctico: escribir 2 tests simples (ej.: función suma y validación de email) — lectura guiada.

#### Semana 24

- ESNext y conceptos avanzados: iterables, generadores (introducción), proxies (idea).

- Ejercicio práctico: crear un iterable personalizado.

#### Semana 25

- Tooling moderno: npm, package.json, scripts básicos, linting (ESLint) y formateo (Prettier).

- Ejercicio práctico: inicializa un package.json, instala ESLint y configura una regla sencilla.

#### Semana 26

- Accesibilidad y buenas prácticas de UX en JS interactivo.

- Ejercicio práctico: añade soporte de teclado y roles ARIA al formulario.

#### Semana 27

- Mini-proyecto: To-Do App con persistencia local (localStorage), pruebas unitarias básicas y linting activo.

- Entregable: repo con README, tests y scripts npm.

#### Semana 28

- Revisión y refactor del To-Do (mejorar estructura de carpetas, módulos, documentación).

- Checklist de habilidades DOM/JS para avanzar a React.

---

Habilidades requeridas para la Fase 4/React: JS ES6+, asincronía, módulos, DOM, testing básico, npm tooling.

---

## FASE 4 

### Control de versiones y colaboración (Semanas 29–31) — 3 semanas

Objetivo: Dominar Git, GitHub y flujo de trabajo colaborativo.

#### Semana 29

- Git local: init, add, commit, status, log.

- Ejercicio práctico: versiona tu To-Do App, haz commits atómicos y escribe buenos mensajes.

#### Semana 30

- Branching, merging, rebase (conceptos), resolución de conflictos, .gitignore.

- Ejercicio práctico: crea una rama feature/x, realiza cambios, simula conflicto y resuélvelo.

#### Semana 31

- GitHub: repos remotos, PRs, issues, README profesional, GitHub Pages (para frontend).

- Ejercicio práctico: sube tu repo a GitHub y abre un Pull Request desde una rama; crea Issues para mejoras.

---

Habilidades requeridas antes de avanzar: uso fluido de Git, manejo de PRs y ramas.

---

## FASE 5 

### Python desde cero (Semanas 32–40) — 9 semanas

Objetivo: Aprender Python con foco en backend, buenas prácticas y pruebas.

#### Semana 32

- Introducción a Python: sintaxis, variables, tipos, intérprete vs scripts.

- Ejercicio práctico: instala Python, ejecuta python -V y un script hola.py.

#### Semana 33

- Control de flujo, funciones, comprensión de listas.

- Ejercicio práctico: script que lea una lista de precios y calcule promedio/mediana.

#### Semana 34

- Estructuras (listas, dicts, sets), manejo de archivos.

- Ejercicio práctico: parsea un CSV simple y muestra resumen.

#### Semana 35

- Programación orientada a objetos (clases, objetos, herencia).

- Ejercicio práctico: modela una clase Usuario con métodos para autenticar.

#### Semana 36

- Entornos virtuales (venv), pip, requirements.txt.

- Ejercicio práctico: crea un entorno virtual y un pequeño requirements.txt.

#### Semana 37

- Testing en Python con pytest, conceptos de mocks básicos.

- Ejercicio práctico: escribe tests para la clase Usuario.

#### Semana 38

- Tipado estático opcional con typing, buenas prácticas de código (PEP8).

- Ejercicio práctico: añade anotaciones a funciones y usa flake8/pylint.

#### Semana 39

- Asincronía en Python: asyncio básico.

- Ejercicio práctico: script asincrónico que haga N tareas simuladas.

#### Semana 40

- Mini-proyecto: API simple local usando Flask (o sin framework) que exponga endpoints CRUD en memoria.

- Entregable: repo con README, tests y cómo ejecutar.

---

Habilidades requeridas para la Fase 6: Python sólido básico, entornos virtuales, testing.

---

## FASE 6 

### APIs con FastAPI (Semanas 41–50) — 10 semanas

Objetivo: Construir APIs robustas, tipadas y documentadas con FastAPI; entender internals y ASGI.

#### Semana 41

- Introducción a FastAPI: por qué, arquitectura ASGI vs WSGI, uvicorn.

- Ejercicio práctico: crea tu primer endpoint GET con FastAPI y ejecútalo con uvicorn.

#### Semana 42

- Rutas, path/query params, request/response models con Pydantic.

- Ejercicio práctico: endpoint POST con validación Pydantic.

#### Semana 43

- Dependencias, middlewares y manejo de errores.

- Ejercicio práctico: añade middleware de logging y manejo de excepciones personalizado.

#### Semana 44

- Autenticación y autorización básica (JWT conceptualmente).

- Ejercicio práctico: implementar login que emita JWT y endpoint protegido.

#### Semana 45

- Testing de APIs con pytest y httpx / TestClient.

- Ejercicio práctico: escribir tests para endpoints CRUD.

#### Semana 46

- Performance y concurrencia (async endpoints, límites de conexión).

- Ejercicio práctico: convierte endpoints CPU-bound y IO-bound a async donde corresponda.

#### Semana 47

- Documentación automática (OpenAPI, Swagger UI) y versionado de API.

- Ejercicio práctico: comprueba Swagger UI, añade descripciones y ejemplos.

#### Semana 48

- Buenas prácticas de diseño de APIs RESTful; introducción a GraphQL (nota conceptual).

- Ejercicio práctico: refactoriza rutas para ser RESTful (nombres, status codes).

#### Semana 49

- Seguridad para APIs: rate limiting (concepto), CORS, validación de entrada, sanitización.

- Ejercicio práctico: configura CORS correctamente y agrega validaciones más estrictas.

#### Semana 50

- Proyecto de la fase: Backend de tareas (Task Manager) con FastAPI: endpoints CRUD, autenticación JWT, tests, documentación.

- Entregable: repo listo para desplegar (Dockerfile básico incluido).

---

Habilidades requeridas para la Fase 7: creación de APIs REST sólidas, testing, autenticación y seguridad básica.

---

## FASE 7 

### Bases de datos (SQL y NoSQL) (Semanas 51–56) — 6 semanas

Objetivo: Diseñar y trabajar con bases de datos relacionales y documentos; integrar con FastAPI.

#### Semana 51

- Conceptos SQL: tablas, relaciones, normalización (1ª–3ª forma normal).

- Ejercicio práctico: diseña esquema para Task Manager (usuarios, tareas, proyectos).

#### Semana 52

- SQL práctico con PostgreSQL: SELECT, JOIN, GROUP BY, índices.

- Ejercicio práctico: instala localmente (o usa Docker) PostgreSQL y crea tablas; inserta/consulta datos.

#### Semana 53

- ORM: SQLAlchemy (conceptos), migraciones (Alembic).

- Ejercicio práctico: integrar SQLAlchemy con FastAPI para modelos del Task Manager.

#### Semana 54

- NoSQL: conceptos (documentos, colecciones), cuando usar NoSQL vs SQL; MongoDB o Supabase's Realtime (concepto).

- Ejercicio práctico: modela un caso donde usarías NoSQL (ej.: eventos o logs).

#### Semana 55

- Transacciones, integridad referencial, backup/restore.

- Ejercicio práctico: simula una transacción y muestra rollback con SQLAlchemy.

#### Semana 56

- Mini-proyecto: Task Manager completo con persistencia en PostgreSQL, migraciones y tests de integración.

- Entregable: repo que pueda inicializar la DB y correr tests.

---

Habilidades requeridas: diseño relacional, uso de PostgreSQL, integración ORM, decidir entre SQL/NoSQL.

---

## FASE 8 

### React (Semanas 57–70) — 14 semanas

Objetivo: Dominar React (hooks, gestión de estado, rendimiento), entender cómo funciona internamente y conectar con APIs.

#### Semana 57

- Introducción: componentes, JSX, props, estado local.

- Ejercicio práctico: crea componentes Header, TodoList, TodoItem.

#### Semana 58

- Hooks básicos: useState, useEffect.

- Ejercicio práctico: consume la API del Task Manager y muestra tareas.

#### Semana 59

- Enrutamiento con react-router (concepto y práctica).

- Ejercicio práctico: añade rutas para Home, Tasks, Login.

#### Semana 60

- Gestión de estado global: contexto (Context API) y cuándo usarlo.

- Ejercicio práctico: implementa autenticación persistente con Context.

#### Semana 61

- Librerías de estado (concepto): Redux / Zustand — cuándo y por qué (elige una para aprender).

- Ejercicio práctico: implementa un store simple (por ejemplo con Zustand).

#### Semana 62

- Formularios complejos y validación (react-hook-form o similar).

- Ejercicio práctico: formulario de crear/editar tarea con validaciones.

#### Semana 63

- Componentización avanzada, composición y patrones (HOC, render props — teoría).

- Ejercicio práctico: refactoriza componentes para reusabilidad.

#### Semana 64

- Performance: memoización (React.memo, useMemo, useCallback), lazy loading.

- Ejercicio práctico: mejora rendimiento de lista de tareas con virtualización.

#### Semana 65

- Testing en React: React Testing Library y pruebas end-to-end (introducción a Cypress).

- Ejercicio práctico: escribir tests para componente TodoItem y un test e2e simple.

#### Semana 66

- Styling moderno: CSS-in-JS, módulos CSS, Tailwind (opcional).

- Ejercicio práctico: aplica estilos consistentes y accesibles.

#### Semana 67

- SSR/SSG conceptos (Next.js) — ¿qué cambia respecto a SPA?

- Ejercicio práctico: leer y entender cuándo usar SSR; pequeña demo conceptual.

#### Semana 68

- Integración con APIs: manejo de tokens, refresh tokens, interceptores.

- Ejercicio práctico: consumir FastAPI protegida con JWT desde React y manejar expiración.

#### Semana 69

- Seguridad en frontend: XSS, CSRF (conceptos), almacenamiento seguro de tokens.

- Ejercicio práctico: revisar y corregir cómo guardas tokens (evitar localStorage si aplica).

#### Semana 70

- Proyecto de la fase: Frontend del Task Manager en React, conectado al backend FastAPI, con autenticación, tests y deploy listo.

- Entregable: repo con README y scripts de build.

---

Habilidades requeridas para la Fase 9: componentes, hooks, state management, testing y consumo seguro de APIs.

---

## FASE 9 

### Seguridad web y testing avanzado (Semanas 71–74) — 4 semanas

Objetivo: Aprender buenas prácticas de seguridad y testing profesional.

#### Semana 71

- Seguridad en APIs: OWASP Top 10 (resumen), validación, rate limiting, protección de datos sensibles.

- Ejercicio práctico: evalúa tu Task Manager con checklist OWASP y corrige al menos 3 puntos.

#### Semana 72

- Autenticación avanzada: OAuth2 (concepto), refresh tokens, revocación de tokens.

- Ejercicio práctico: implementar refresh token seguro en FastAPI (concepto + demo).

#### Semana 73

- Testing avanzado: integración continua (CI) básico con GitHub Actions, pipelines de tests.

- Ejercicio práctico: configura workflow que ejecute tests de backend y frontend en cada PR.

#### Semana 74

- Seguridad de bases de datos y backups: cifrado en reposo, usuarios/roles, gestión de credenciales.

---

Ejercicio práctico: crea roles en PostgreSQL y restringe permisos según principio de privilegio mínimo.

---

## FASE 10 

### Arquitectura de software y buenas prácticas profesionales (Semanas 75–77) — 3 semanas

Objetivo: Concebir sistemas mantenibles, escalables y profesionales.

#### Semana 75

- Patrones arquitectónicos: monolito modular, microservicios (pros/cons), hexagonal/clean architecture.

- Ejercicio práctico: diseña (diagrama) arquitectura para una versión escalable del Task Manager.

#### Semana 76

- Observabilidad: logs estructurados, métricas, tracing (concepto).

- Ejercicio práctico: añade logging estructurado y métricas básicas en FastAPI.

#### Semana 77

- Gestión de proyectos y preparación profesional: cómo presentar proyectos, preparar CV técnico y portfolio, prácticas freelance (contratos, fijar precios).

- Ejercicio práctico: redacta la página “Proyectos” de tu portfolio con 3 proyectos listos para mostrar a clientes.

---

Habilidades requeridas antes de Docker/Deployment: diseño arquitectónico básico y observabilidad mínima.

---

## FASE 11 

### Docker, CI/CD y deployment (Semanas 78–82) — 5 semanas

Objetivo: Contenerizar, desplegar y automatizar despliegues en entornos reales; aprender Vercel, Supabase y Render.

#### Semana 78

- Docker: imágenes, contenedores, Dockerfile, docker-compose.

- Ejercicio práctico: dockeriza tu FastAPI y PostgreSQL con docker-compose.

#### Semana 79

- CI/CD: pipelines, automatizar builds y despliegues (GitHub Actions ejemplos).

- Ejercicio práctico: pipeline que construya imagen Docker y ejecute tests.

#### Semana 80

- Despliegue frontend con Vercel (configurar producción, dominios).

- Ejercicio práctico: deploy de tu frontend React a Vercel.

#### Semana 81

- Base de datos gestionada con Supabase (autenticación, storage, Realtime).

- Ejercicio práctico: mover la DB a Supabase (o usar su servicio) y conectar backend.

#### Semana 82

- Despliegue de backend con Render u otra alternativa (Heroku/Cloud Run conceptualmente).

- Ejercicio práctico: deploy de FastAPI (contenerizada) en Render y señalar variables de entorno/secretos.

---

Nota: también incluye aprender a usar GitHub Actions para desplegar automáticamente a Vercel/Render.

---

## FASE 12 

### Proyecto Full Stack profesional para portafolio (Semanas 83–90) — 8 semanas

Objetivo: Construir un proyecto profesional, documentado, testeado, desplegado y listo para mostrar a empleadores/freelance.

#### Semanas 83–86 (4 semanas)

- Planificación: Requisitos, historias de usuario, arquitectura, DB schema.

- Desarrollo: Frontend React + Backend FastAPI + PostgreSQL (hosted en Supabase), autenticación, roles (admin/user), tests.

- Entregables parciales: endpoints documentados, UI flows, tests unitarios.

#### Semanas 87–90 (4 semanas)

- Hardening: seguridad, logging, métricas, backup DB, escalabilidad básica.

- Deployment final: frontend en Vercel, backend en Render, DB en Supabase; configurar CI/CD, dominio, SSL, documentación final y video demo.

---

Entregable final: repo público (o privado con demo), README profesional, video de 3–5 minutos mostrando la app.

---

## Requisitos de paso entre fases (resumen)

- Antes de Phase 2: terminal básico, conceptos Internet/HTTP.
- Antes de Phase 3: HTML/CSS y manipulación DOM básica.
- Antes de Phase 5: JS ES6+ y manejo de módulos.
- Antes de Phase 6: Python básico y testing.
- Antes de Phase 8: JS avanzado y consumo de APIs.
- Antes de Phase 11: APIs testeadas y contenedorización básica.

---

## Ejercicios prácticos y mini-proyectos (resumen)

- Cada 2–3 semanas: mini-proyecto que combine lo aprendido (p. ej. landing page, To-Do, Task Manager backend, Task Manager frontend).

- Al final de cada fase: un proyecto más grande (ver FASEs) totalmente documentado y con tests.

- Mantén un repo por proyecto y un README claro con instrucciones de ejecución, tests y despliegue.

--- 

## Recomendaciones de herramientas y recursos

- Editor: VSCode.

- Terminal / OS: Linux (Ubuntu) o WSL en Windows.

- Git + GitHub para control de versiones y portfolio. GitHub

- Python (última 3.x estable). Python

- FastAPI para backend. FastAPI

- React para frontend. React

- Docker para contenerización. Docker

- Vercel / Supabase / Render ya mencionados arriba.

- Cursos y documentación oficiales (FastAPI docs, React docs, Python docs), y plataformas: freeCodeCamp, MDN Web Docs (HTML/CSS/JS), Real Python (para Python), y tutoriales prácticos en YouTube + documentación oficial.

---

## Buenas prácticas de seguridad (resumen práctico)

- Nunca almacenar secretos en repositorios; usar variables de entorno o secret managers.

- Validar siempre la entrada en el backend (no confiar en el frontend).

- Usar HTTPS siempre en producción.

- Tokens: usar access + refresh tokens; guardar access token en memoria si es posible y refresh token en HttpOnly cookie.

- Principio de mínimo privilegio para DB: crear usuarios con permisos limitados.

- Sanitizar salidas y prevenir XSS/CSRF (usar cabeceras Content-Security-Policy, SameSite cookies).

- Hacer backups regulares y probar restauraciones.

- Limitar tasa de peticiones (rate limiting) y monitorear logs.

---

## Errores comunes de principiantes y cómo evitarlos

- Querer aprender todo a la vez: divide en pasos pequeños (tu 1 h/día ya lo hace).

- No escribir código diariamente: la práctica diaria (aunque 1 h) es crucial.

- Ignorar tests y documentación: escribe tests desde el inicio; facilita debugging.

- No versionar el trabajo: crea repos para cada proyecto y commitea frecuentemente.

- Guardar secretos en código: usa .env y variables de entorno.

- Mala estructura de carpetas: sigue convenciones y separa responsabilidades.

- Optimizar prematuramente: primero funcionalidad correcta, luego rendimiento.

- Cómo evitarlos: checklist semanal, revisiones de código (aunque solo sea auto-revisión) y pequeños objetivos diarios.

---

## Hábitos y técnicas para estudiar 1 hora diaria

- Técnica Pomodoro adaptada: 50 min de foco, 10 min de repaso/nota (o 45/15 si te distraes).

- Divide la hora: 40 min práctica (codificar), 10 min lectura/concepto, 10 min resumen/escribir lo aprendido.

- Diario técnico: cada día escribe 3 cosas aprendidas y 1 problema encontrado.

- Revisión semanal (30–60 min) para consolidar y planear la semana siguiente.

- Usa bloqueadores de distracciones (Forest, Focus To-Do) y un ambiente limpio.

- Aprende con proyecto real desde el principio — aplicar lo aprendido acelera retención.

---

## Cómo preparar proyectos para conseguir trabajo y clientes freelance

- Cada proyecto en GitHub con README claro, instrucciones de instalación, vídeo demo y capturas.

- Proyectos pequeños pero completos (auth, CRUD, tests, deploy) > muchos ejemplos incompletos.

- Portfolio online (simple site) con enlaces a repos y a apps desplegadas.

- Preparar una versión “case study” por proyecto explicando requisitos, decisiones técnicas y retos.

- Para freelance: contratos simples, tarifas por hora/proyecto, políticas de revisiones, forma de entrega y facturación.

- Practica entrevistas técnicas: algoritmos básicos + explicar decisiones de arquitectura.

---

## Recursos sugeridos (rápidos)

- MDN Web Docs — HTML/CSS/JS

- Documentación oficial de FastAPI — tutoriales y ejemplos

- React Docs — tutorial oficial

- freeCodeCamp, Real Python, Python official docs

- Cursos prácticos (YouTube: Traversy Media, The Net Ninja)

- GitHub Learning Lab para prácticas de Git y GitHub

---

## Prompt utilizado

Actúa como un ingeniero de software senior, arquitecto de sistemas y mentor de programación con más de 30 años de experiencia formando desarrolladores desde nivel principiante hasta nivel profesional.

Tu tarea es crear para mí un roadmap extremadamente detallado para convertirme en un desarrollador Full Stack profesional especializado en:

* Frontend: React
* Backend: FastAPI con Python

Mi contexto:

* Soy un principiante absoluto y no tengo conocimientos de programación.
* Solo puedo estudiar 1 hora al día (7 horas a la semana).
* Mi objetivo es llegar a trabajar como programador y también poder hacer trabajos freelance.
* Quiero una formación profunda (nivel ingeniero), entendiendo no solo cómo usar las herramientas sino también cómo funcionan internamente.
* Me distraigo con facilidad, por lo que el plan debe estar dividido en objetivos pequeños y claros para cada semana.

El roadmap debe comenzar desde los fundamentos más básicos de la computación y el desarrollo web, incluyendo conceptos como:

* Qué es la programación
* Cómo funciona una computadora
* Cómo funciona internet
* HTTP y HTTPS
* DNS
* Cliente y servidor
* Qué es una API
* Arquitectura web
* HTML
* CSS
* JavaScript
* Git y GitHub
* Terminal y Linux básico
* Python
* FastAPI
* React
* Bases de datos (SQL y NoSQL)
* Testing
* Seguridad web
* Arquitectura de software
* Docker
* Deployment
* Buenas prácticas profesionales
* Cómo preparar proyectos para conseguir trabajo y clientes freelance

También quiero aprender a desplegar y trabajar con herramientas modernas usadas en proyectos reales, incluyendo:

* Vercel
* Supabase
* Render

Estas herramientas deben integrarse en los proyectos del roadmap para aprender a desplegar aplicaciones frontend, backend y bases de datos en entornos reales.

Requisitos del roadmap:

1. Debe estar estructurado por fases, meses y semanas.
2. Debe indicar la duración total estimada considerando que estudio 1 hora diaria.
3. No debes saltarte ningún concepto fundamental.
4. Debes explicar exactamente qué debo aprender en cada semana.
5. Debes incluir ejercicios prácticos.
6. Debes incluir mini proyectos frecuentes.
7. Debes incluir proyectos grandes al final de cada fase.
8. Debes indicar qué habilidades debo dominar antes de pasar a la siguiente fase.
9. Debes incluir recomendaciones de herramientas y recursos.
10. Debes incluir buenas prácticas de seguridad para proteger APIs, aplicaciones y bases de datos.
11. Debes explicar errores comunes de principiantes y cómo evitarlos.
12. Debes incluir hábitos o técnicas para estudiar programación de forma eficiente con solo 1 hora diaria.

Formato de salida esperado:

Duración total estimada: X años / meses

FASE 1 — Fundamentos de computación y programación

Semana 1

* Concepto
* Concepto
* Ejercicio práctico

Semana 2

* Concepto
* Concepto
* Ejercicio práctico

Semana 3  
`...`

FASE 2 — Fundamentos del desarrollo web  
`...`

FASE 3 — JavaScript  
`...`

FASE 4 — Control de versiones (Git y GitHub)  
`...`

FASE 5 — Backend con Python  
`...`

FASE 6 — APIs con FastAPI  
`...`

FASE 7 — Bases de datos  
`...`

FASE 8 — React  
`...`

FASE 9 — Seguridad Web  
`...`

FASE 10 — Arquitectura de software  
`...`

FASE 11 — Docker y deployment  
`...`

FASE 12 — Proyecto Full Stack profesional para portafolio  
`...`

El roadmap debe ser extremadamente claro, progresivo y pensado para alguien que comienza desde cero pero quiere llegar a un nivel profesional sólido.

Si la respuesta es demasiado larga, divídela en varias partes.

---

[Volver al índice](#temario-completo)