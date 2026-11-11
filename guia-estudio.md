# Guía de estudio — 90 sesiones

Esta guía desarrolla las 90 sesiones respetando el orden y el contenido operativo de `curriculum/session-plan.md`. Los objetivos, herramientas, recursos, prácticas y evidencias se mantienen vinculados a esa fuente. Cada sesión conserva los 90 minutos curriculares: 10 min de recuperación, 20 min de explicación, 35 min de práctica guiada, 15 min de ejercicio individual y 10 min para evidencia/reflexión. El ejercicio individual es una transferencia breve de la práctica del día, no una tarea adicional. Cuando el plan fuente no especifica un recurso, la guía lo indica en lugar de inventarlo. Trabaja solo con datos sintéticos y entornos propios o autorizados.

---

# Día 01 — Cliente, servidor, solicitud, respuesta y ciclo HTTP

**Objetivo de aprendizaje:** Explicar cliente, servidor, solicitud, respuesta y ciclo HTTP.

**Teoría y recurso:** [MDN: Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Anotar una solicitud/respuesta ficticia; separar método, ruta, cabeceras, estado y cuerpo.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Explicar cliente, servidor, solicitud, respuesta y ciclo HTTP.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Anotar una solicitud/respuesta ficticia; separar método, ruta, cabeceras, estado y cuerpo.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama del ciclo y glosario de 8 términos.

**Evidencia verificable:** Diagrama del ciclo y glosario de 8 términos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 01. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Explicar cliente, servidor, solicitud, respuesta y ciclo HTTP. La práctica es: Anotar una solicitud/respuesta ficticia; separar método, ruta, cabeceras, estado y cuerpo. La evidencia que debo producir es: Diagrama del ciclo y glosario de 8 términos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 01](evaluaciones.md#evaluación-día-01).

---

# Día 02 — Métodos, códigos de estado y cabeceras frecuentes

**Objetivo de aprendizaje:** Interpretar métodos, códigos de estado y cabeceras frecuentes.

**Teoría y recurso:** [MDN: HTTP methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods), [status](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status), [headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Clasificar ejemplos GET/POST y estados 200, 301, 400, 401, 403, 404, 429 y 500.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Interpretar métodos, códigos de estado y cabeceras frecuentes.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Clasificar ejemplos GET/POST y estados 200, 301, 400, 401, 403, 404, 429 y 500.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla método/estado/cabecera y cuándo aplican.

**Evidencia verificable:** Tabla método/estado/cabecera y cuándo aplican.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 02. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Interpretar métodos, códigos de estado y cabeceras frecuentes. La práctica es: Clasificar ejemplos GET/POST y estados 200, 301, 400, 401, 403, 404, 429 y 500. La evidencia que debo producir es: Tabla método/estado/cabecera y cuándo aplican. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 02](evaluaciones.md#evaluación-día-02).

---

# Día 03 — DNS y el recorrido básico de una solicitud web

**Objetivo de aprendizaje:** Explicar DNS y el recorrido básico de una solicitud web.

**Teoría y recurso:** [Cloudflare: What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/), [MDN: How the Web works](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/How_the_web_works)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Seguir un caso ficticio: nombre de dominio, resolución DNS, conexión, solicitud HTTP y respuesta; distinguir DNS de HTTP.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Explicar DNS y el recorrido básico de una solicitud web.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Seguir un caso ficticio: nombre de dominio, resolución DNS, conexión, solicitud HTTP y respuesta; distinguir DNS de HTTP.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama del recorrido y glosario de DNS, IP, dominio, puerto y protocolo.

**Evidencia verificable:** Diagrama del recorrido y glosario de DNS, IP, dominio, puerto y protocolo.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 03. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Explicar DNS y el recorrido básico de una solicitud web. La práctica es: Seguir un caso ficticio: nombre de dominio, resolución DNS, conexión, solicitud HTTP y respuesta; distinguir DNS de HTTP. La evidencia que debo producir es: Diagrama del recorrido y glosario de DNS, IP, dominio, puerto y protocolo. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 03](evaluaciones.md#evaluación-día-03).

---

# Día 04 — Identificación, autenticación y autorización

**Objetivo de aprendizaje:** Diferenciar identificación, autenticación y autorización.

**Teoría y recurso:** [Microsoft: Authentication vs. authorization](https://learn.microsoft.com/en-us/entra/identity-platform/authentication-vs-authorization)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Clasificar escenarios ficticios de inicio de sesión, permisos y denegación; identificar qué evidencia permite concluir cada caso.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Diferenciar identificación, autenticación y autorización.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Clasificar escenarios ficticios de inicio de sesión, permisos y denegación; identificar qué evidencia permite concluir cada caso.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla identidad/autenticación/autorización y ejemplos 401/403.

**Evidencia verificable:** Tabla identidad/autenticación/autorización y ejemplos 401/403.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 04. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Diferenciar identificación, autenticación y autorización. La práctica es: Clasificar escenarios ficticios de inicio de sesión, permisos y denegación; identificar qué evidencia permite concluir cada caso. La evidencia que debo producir es: Tabla identidad/autenticación/autorización y ejemplos 401/403. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 04](evaluaciones.md#evaluación-día-04).

---

# Día 05 — Cookies, sesiones y autenticación en HTTP

**Objetivo de aprendizaje:** Diferenciar cookies, sesiones y autenticación en HTTP.

**Teoría y recurso:** [MDN: HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Analizar ejemplos ficticios de Secure, HttpOnly, SameSite, expiración y sesión; identificar riesgos de exposición y límites de una cookie.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Diferenciar cookies, sesiones y autenticación en HTTP.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Analizar ejemplos ficticios de Secure, HttpOnly, SameSite, expiración y sesión; identificar riesgos de exposición y límites de una cookie.
- Puedes justificar la evidencia que guardas y qué demuestra: Ficha comparativa y lista de datos que nunca deben compartirse.

**Evidencia verificable:** Ficha comparativa y lista de datos que nunca deben compartirse.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 05. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Diferenciar cookies, sesiones y autenticación en HTTP. La práctica es: Analizar ejemplos ficticios de Secure, HttpOnly, SameSite, expiración y sesión; identificar riesgos de exposición y límites de una cookie. La evidencia que debo producir es: Ficha comparativa y lista de datos que nunca deben compartirse. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 05](evaluaciones.md#evaluación-día-05).

---

# Día 06 — JSON y HTML como formatos de respuesta

**Objetivo de aprendizaje:** Reconocer JSON y HTML como formatos de respuesta.

**Teoría y recurso:** [MDN: JSON](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/JSON), [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Inspeccionar respuestas sintéticas; validar estructura, tipos, campos ausentes y diferencia entre contenido y metadatos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Reconocer JSON y HTML como formatos de respuesta.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Inspeccionar respuestas sintéticas; validar estructura, tipos, campos ausentes y diferencia entre contenido y metadatos.
- Puedes justificar la evidencia que guardas y qué demuestra: JSON anotado y checklist de validación.

**Evidencia verificable:** JSON anotado y checklist de validación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 06. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Reconocer JSON y HTML como formatos de respuesta. La práctica es: Inspeccionar respuestas sintéticas; validar estructura, tipos, campos ausentes y diferencia entre contenido y metadatos. La evidencia que debo producir es: JSON anotado y checklist de validación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 06](evaluaciones.md#evaluación-día-06).

---

# Día 07 — Tráfico web normal con DevTools y sintetizar la fase

**Objetivo de aprendizaje:** Inspeccionar tráfico web normal con DevTools y sintetizar la fase.

**Teoría y recurso:** [Chrome DevTools: Network](https://developer.chrome.com/docs/devtools/network/), [MDN: HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)

**Herramientas:** Navegador web (Chrome o Firefox) + DevTools; editor de texto gratuito

**Práctica guiada (35 min):**

Inspeccionar una página propia o demo permitida; describir DNS (si está disponible), solicitud, respuesta y estado sin copiar cookies/tokens; resolver caso con 200/401/403/404/429/500.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Inspeccionar tráfico web normal con DevTools y sintetizar la fase.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Inspeccionar una página propia o demo permitida; describir DNS (si está disponible), solicitud, respuesta y estado sin copiar cookies/tokens; resolver caso con 200/401/403/404/429/500.
- Puedes justificar la evidencia que guardas y qué demuestra: Captura saneada o tabla, diagrama de recorrido y miniinforme con límites de conclusión.

**Evidencia verificable:** Captura saneada o tabla, diagrama de recorrido y miniinforme con límites de conclusión.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 07. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Inspeccionar tráfico web normal con DevTools y sintetizar la fase. La práctica es: Inspeccionar una página propia o demo permitida; describir DNS (si está disponible), solicitud, respuesta y estado sin copiar cookies/tokens; resolver caso con 200/401/403/404/429/500. La evidencia que debo producir es: Captura saneada o tabla, diagrama de recorrido y miniinforme con límites de conclusión. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 07](evaluaciones.md#evaluación-día-07).

---

# Día 08 — Tablas, filas, claves y relaciones SQL

**Objetivo de aprendizaje:** Explicar tablas, filas, claves y relaciones SQL.

**Teoría y recurso:** [SQLBolt: Lessons 1–3](https://sqlbolt.com/)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community

**Práctica guiada (35 min):**

Crear mentalmente y luego consultar tablas sintéticas de productos, tiendas y observaciones.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Explicar tablas, filas, claves y relaciones SQL.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear mentalmente y luego consultar tablas sintéticas de productos, tiendas y observaciones.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama relacional y definición de claves.

**Evidencia verificable:** Diagrama relacional y definición de claves.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 08. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Explicar tablas, filas, claves y relaciones SQL. La práctica es: Crear mentalmente y luego consultar tablas sintéticas de productos, tiendas y observaciones. La evidencia que debo producir es: Diagrama relacional y definición de claves. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 08](evaluaciones.md#evaluación-día-08).

---

# Día 09 — Consultar datos con SELECT, WHERE, ORDER BY y LIMIT

**Objetivo de aprendizaje:** Consultar datos con SELECT, WHERE, ORDER BY y LIMIT.

**Teoría y recurso:** [SQLBolt: SELECT](https://sqlbolt.com/lesson/select_queries_introduction)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community

**Práctica guiada (35 min):**

Resolver consultas sobre dataset sintético y predecir resultados antes de ejecutarlas.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Consultar datos con SELECT, WHERE, ORDER BY y LIMIT.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resolver consultas sobre dataset sintético y predecir resultados antes de ejecutarlas.
- Puedes justificar la evidencia que guardas y qué demuestra: Archivo SQL con 6 consultas y resultados.

**Evidencia verificable:** Archivo SQL con 6 consultas y resultados.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 09. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Consultar datos con SELECT, WHERE, ORDER BY y LIMIT. La práctica es: Resolver consultas sobre dataset sintético y predecir resultados antes de ejecutarlas. La evidencia que debo producir es: Archivo SQL con 6 consultas y resultados. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 09](evaluaciones.md#evaluación-día-09).

---

# Día 10 — Combinar tablas con JOIN

**Objetivo de aprendizaje:** Combinar tablas con JOIN.

**Teoría y recurso:** [SQLBolt: JOIN](https://sqlbolt.com/lesson/6)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community

**Práctica guiada (35 min):**

Unir productos y categorías; comparar INNER y LEFT JOIN con claves faltantes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Combinar tablas con JOIN.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Unir productos y categorías; comparar INNER y LEFT JOIN con claves faltantes.
- Puedes justificar la evidencia que guardas y qué demuestra: Consultas comentadas y explicación de filas excluidas.

**Evidencia verificable:** Consultas comentadas y explicación de filas excluidas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 10. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Combinar tablas con JOIN. La práctica es: Unir productos y categorías; comparar INNER y LEFT JOIN con claves faltantes. La evidencia que debo producir es: Consultas comentadas y explicación de filas excluidas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 10](evaluaciones.md#evaluación-día-10).

---

# Día 11 — Resumir datos con agregaciones, GROUP BY y HAVING

**Objetivo de aprendizaje:** Resumir datos con agregaciones, GROUP BY y HAVING.

**Teoría y recurso:** [SQLBolt: Aggregates](https://sqlbolt.com/lesson/select_queries_with_aggregates)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community

**Práctica guiada (35 min):**

Calcular conteos, mínimos, máximos y promedios por producto/tienda.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Resumir datos con agregaciones, GROUP BY y HAVING.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Calcular conteos, mínimos, máximos y promedios por producto/tienda.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla resumen y validación manual de 3 resultados.

**Evidencia verificable:** Tabla resumen y validación manual de 3 resultados.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 11. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Resumir datos con agregaciones, GROUP BY y HAVING. La práctica es: Calcular conteos, mínimos, máximos y promedios por producto/tienda. La evidencia que debo producir es: Tabla resumen y validación manual de 3 resultados. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 11](evaluaciones.md#evaluación-día-11).

---

# Día 12 — Consultas parametrizadas y separar código de datos

**Objetivo de aprendizaje:** Aplicar consultas parametrizadas y separar código de datos.

**Teoría y recurso:** [Python sqlite3: placeholders](https://docs.python.org/3/library/sqlite3.html)

**Herramientas:** Python 3 + VS Code; módulo sqlite3 integrado

**Práctica guiada (35 min):**

Comparar concatenación insegura con consulta parametrizada usando SQLite local.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Aplicar consultas parametrizadas y separar código de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Comparar concatenación insegura con consulta parametrizada usando SQLite local.
- Puedes justificar la evidencia que guardas y qué demuestra: Ejemplo seguro ejecutable y explicación.

**Evidencia verificable:** Ejemplo seguro ejecutable y explicación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 12. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Aplicar consultas parametrizadas y separar código de datos. La práctica es: Comparar concatenación insegura con consulta parametrizada usando SQLite local. La evidencia que debo producir es: Ejemplo seguro ejecutable y explicación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 12](evaluaciones.md#evaluación-día-12).

---

# Día 13 — Causa, impacto y prevención de SQL injection

**Objetivo de aprendizaje:** Explicar causa, impacto y prevención de SQL injection.

**Teoría y recurso:** [OWASP: SQL Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Analizar ejemplos escritos; no atacar sitios ni ejecutar payloads contra servicios reales.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Explicar causa, impacto y prevención de SQL injection.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Analizar ejemplos escritos; no atacar sitios ni ejecutar payloads contra servicios reales.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz causa/impacto/control con ejemplo inocuo.

**Evidencia verificable:** Matriz causa/impacto/control con ejemplo inocuo.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 13. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Explicar causa, impacto y prevención de SQL injection. La práctica es: Analizar ejemplos escritos; no atacar sitios ni ejecutar payloads contra servicios reales. La evidencia que debo producir es: Matriz causa/impacto/control con ejemplo inocuo. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 13](evaluaciones.md#evaluación-día-13).

---

# Día 14 — Y normalizar entradas de datos

**Objetivo de aprendizaje:** Validar y normalizar entradas de datos.

**Teoría y recurso:** [OWASP: Input Validation](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Definir reglas de tipo, longitud, rango, formato y valores permitidos para campos sintéticos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Validar y normalizar entradas de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir reglas de tipo, longitud, rango, formato y valores permitidos para campos sintéticos.
- Puedes justificar la evidencia que guardas y qué demuestra: Especificación de validación y casos límite.

**Evidencia verificable:** Especificación de validación y casos límite.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 14. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Validar y normalizar entradas de datos. La práctica es: Definir reglas de tipo, longitud, rango, formato y valores permitidos para campos sintéticos. La evidencia que debo producir es: Especificación de validación y casos límite. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 14](evaluaciones.md#evaluación-día-14).

---

# Día 15 — Mínimo privilegio en bases de datos

**Objetivo de aprendizaje:** Aplicar mínimo privilegio en bases de datos.

**Teoría y recurso:** [OWASP: Database Security](https://cheatsheetseries.owasp.org/)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Diseñar roles ficticios lector, analista y administrador; asignar solo permisos necesarios.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Aplicar mínimo privilegio en bases de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Diseñar roles ficticios lector, analista y administrador; asignar solo permisos necesarios.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz rol-permiso y justificación.

**Evidencia verificable:** Matriz rol-permiso y justificación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 15. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Aplicar mínimo privilegio en bases de datos. La práctica es: Diseñar roles ficticios lector, analista y administrador; asignar solo permisos necesarios. La evidencia que debo producir es: Matriz rol-permiso y justificación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 15](evaluaciones.md#evaluación-día-15).

---

# Día 16 — Utilidad y riesgos de auditoría de consultas

**Objetivo de aprendizaje:** Identificar utilidad y riesgos de auditoría de consultas.

**Teoría y recurso:** [OWASP Logging Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Diseñar campos de auditoría útiles sin registrar contraseñas, tokens ni datos innecesarios.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Identificar utilidad y riesgos de auditoría de consultas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Diseñar campos de auditoría útiles sin registrar contraseñas, tokens ni datos innecesarios.
- Puedes justificar la evidencia que guardas y qué demuestra: Esquema de log y revisión de privacidad.

**Evidencia verificable:** Esquema de log y revisión de privacidad.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 16. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Identificar utilidad y riesgos de auditoría de consultas. La práctica es: Diseñar campos de auditoría útiles sin registrar contraseñas, tokens ni datos innecesarios. La evidencia que debo producir es: Esquema de log y revisión de privacidad. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 16](evaluaciones.md#evaluación-día-16).

---

# Día 17 — Un caso integrado de consultas seguras

**Objetivo de aprendizaje:** Resolver un caso integrado de consultas seguras.

**Teoría y recurso:** [SQLite: SELECT](https://www.sqlite.org/lang_select.html), [SQLBolt](https://sqlbolt.com/)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Consultar dataset sintético, detectar anomalías simples y justificar filtros y joins.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Resolver un caso integrado de consultas seguras.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Consultar dataset sintético, detectar anomalías simples y justificar filtros y joins.
- Puedes justificar la evidencia que guardas y qué demuestra: Script SQL reproducible y hallazgos.

**Evidencia verificable:** Script SQL reproducible y hallazgos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 17. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Resolver un caso integrado de consultas seguras. La práctica es: Consultar dataset sintético, detectar anomalías simples y justificar filtros y joins. La evidencia que debo producir es: Script SQL reproducible y hallazgos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 17](evaluaciones.md#evaluación-día-17).

---

# Día 18 — Los conocimientos de la fase 1

**Objetivo de aprendizaje:** Demostrar los conocimientos de la fase 1.

**Teoría y recurso:** Revisión de recursos de sesiones 1–17.

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community; editor de texto

**Práctica guiada (35 min):**

Resolver un caso nuevo sin copiar la solución; explicar decisiones y límites.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Demostrar los conocimientos de la fase 1.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resolver un caso nuevo sin copiar la solución; explicar decisiones y límites.
- Puedes justificar la evidencia que guardas y qué demuestra: Evaluación, consultas verificadas e informe de controles.

**Evidencia verificable:** Evaluación, consultas verificadas e informe de controles.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 18. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Demostrar los conocimientos de la fase 1. La práctica es: Resolver un caso nuevo sin copiar la solución; explicar decisiones y límites. La evidencia que debo producir es: Evaluación, consultas verificadas e informe de controles. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 18](evaluaciones.md#evaluación-día-18).

---

# Día 19 — Variables, tipos, condiciones y bucles en Python

**Objetivo de aprendizaje:** Usar variables, tipos, condiciones y bucles en Python.

**Teoría y recurso:** [Python Tutorial](https://docs.python.org/3/tutorial/)

**Herramientas:** Python 3 + VS Code

**Práctica guiada (35 min):**

Procesar una lista de observaciones sintéticas y clasificar valores.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Usar variables, tipos, condiciones y bucles en Python.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Procesar una lista de observaciones sintéticas y clasificar valores.
- Puedes justificar la evidencia que guardas y qué demuestra: Script comentado y salida esperada.

**Evidencia verificable:** Script comentado y salida esperada.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 19. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Usar variables, tipos, condiciones y bucles en Python. La práctica es: Procesar una lista de observaciones sintéticas y clasificar valores. La evidencia que debo producir es: Script comentado y salida esperada. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 19](evaluaciones.md#evaluación-día-19).

---

# Día 20 — Funciones, módulos y manejar errores

**Objetivo de aprendizaje:** Crear funciones, módulos y manejar errores.

**Teoría y recurso:** [Python: Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html)

**Herramientas:** Python 3 + VS Code

**Práctica guiada (35 min):**

Convertir validaciones repetidas en funciones y manejar entradas inválidas.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Crear funciones, módulos y manejar errores.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Convertir validaciones repetidas en funciones y manejar entradas inválidas.
- Puedes justificar la evidencia que guardas y qué demuestra: Módulo pequeño y 3 casos de prueba.

**Evidencia verificable:** Módulo pequeño y 3 casos de prueba.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 20. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Crear funciones, módulos y manejar errores. La práctica es: Convertir validaciones repetidas en funciones y manejar entradas inválidas. La evidencia que debo producir es: Módulo pequeño y 3 casos de prueba. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 20](evaluaciones.md#evaluación-día-20).

---

# Día 21 — Y escribir CSV y JSON

**Objetivo de aprendizaje:** Leer y escribir CSV y JSON.

**Teoría y recurso:** [Python: csv](https://docs.python.org/3/library/csv.html), [json](https://docs.python.org/3/library/json.html)

**Herramientas:** Python 3 + VS Code

**Práctica guiada (35 min):**

Leer archivo sintético y exportar registros normalizados a CSV/JSON.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Leer y escribir CSV y JSON.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Leer archivo sintético y exportar registros normalizados a CSV/JSON.
- Puedes justificar la evidencia que guardas y qué demuestra: Archivos de entrada/salida y conteos.

**Evidencia verificable:** Archivos de entrada/salida y conteos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 21. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Leer y escribir CSV y JSON. La práctica es: Leer archivo sintético y exportar registros normalizados a CSV/JSON. La evidencia que debo producir es: Archivos de entrada/salida y conteos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 21](evaluaciones.md#evaluación-día-21).

---

# Día 22 — Tipos, nulos y duplicados con reglas explícitas

**Objetivo de aprendizaje:** Limpiar tipos, nulos y duplicados con reglas explícitas.

**Teoría y recurso:** [Pandas: missing data](https://pandas.pydata.org/docs/user_guide/missing_data.html)

**Herramientas:** Python 3 + VS Code + pandas (biblioteca gratuita)

**Práctica guiada (35 min):**

Perfilar un CSV; separar inválidos sin descartarlos silenciosamente.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Limpiar tipos, nulos y duplicados con reglas explícitas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Perfilar un CSV; separar inválidos sin descartarlos silenciosamente.
- Puedes justificar la evidencia que guardas y qué demuestra: Reporte antes/después y reglas.

**Evidencia verificable:** Reporte antes/después y reglas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 22. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Limpiar tipos, nulos y duplicados con reglas explícitas. La práctica es: Perfilar un CSV; separar inválidos sin descartarlos silenciosamente. La evidencia que debo producir es: Reporte antes/después y reglas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 22](evaluaciones.md#evaluación-día-22).

---

# Día 23 — Una API pública/autorizada con HTTP

**Objetivo de aprendizaje:** Consumir una API pública/autorizada con HTTP.

**Teoría y recurso:** [Requests: Quickstart](https://requests.readthedocs.io/en/latest/user/quickstart/)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Consultar endpoint de demostración permitido; revisar estado, JSON y timeout.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Consumir una API pública/autorizada con HTTP.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Consultar endpoint de demostración permitido; revisar estado, JSON y timeout.
- Puedes justificar la evidencia que guardas y qué demuestra: Script y respuesta saneada.

**Evidencia verificable:** Script y respuesta saneada.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 23. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Consumir una API pública/autorizada con HTTP. La práctica es: Consultar endpoint de demostración permitido; revisar estado, JSON y timeout. La evidencia que debo producir es: Script y respuesta saneada. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 23](evaluaciones.md#evaluación-día-23).

---

# Día 24 — Paginación, límites y reintentos responsables

**Objetivo de aprendizaje:** Manejar paginación, límites y reintentos responsables.

**Teoría y recurso:** [Google API: errors](https://cloud.google.com/apis/design/errors)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Simular paginación y backoff; detener reintentos ante errores permanentes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Manejar paginación, límites y reintentos responsables.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Simular paginación y backoff; detener reintentos ante errores permanentes.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama de flujo y pruebas.

**Evidencia verificable:** Diagrama de flujo y pruebas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 24. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Manejar paginación, límites y reintentos responsables. La práctica es: Simular paginación y backoff; detener reintentos ante errores permanentes. La evidencia que debo producir es: Diagrama de flujo y pruebas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 24](evaluaciones.md#evaluación-día-24).

---

# Día 25 — Secretos y variables de entorno

**Objetivo de aprendizaje:** Gestionar secretos y variables de entorno.

**Teoría y recurso:** [GitHub: secrets](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions), [Python os.environ](https://docs.python.org/3/library/os.html#os.environ)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Leer una variable ficticia desde entorno; comprobar que nunca se imprime.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Gestionar secretos y variables de entorno.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Leer una variable ficticia desde entorno; comprobar que nunca se imprime.
- Puedes justificar la evidencia que guardas y qué demuestra: Ejemplo de configuración segura y checklist.

**Evidencia verificable:** Ejemplo de configuración segura y checklist.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 25. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Gestionar secretos y variables de entorno. La práctica es: Leer una variable ficticia desde entorno; comprobar que nunca se imprime. La evidencia que debo producir es: Ejemplo de configuración segura y checklist. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 25](evaluaciones.md#evaluación-día-25).

---

# Día 26 — Esquemas y contratos de datos

**Objetivo de aprendizaje:** Validar esquemas y contratos de datos.

**Teoría y recurso:** [JSON Schema](https://json-schema.org/learn/getting-started-step-by-step)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Definir campos, tipos, requeridos y restricciones para observaciones de precio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Validar esquemas y contratos de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir campos, tipos, requeridos y restricciones para observaciones de precio.
- Puedes justificar la evidencia que guardas y qué demuestra: Esquema y conjunto válido/inválido.

**Evidencia verificable:** Esquema y conjunto válido/inválido.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 26. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Validar esquemas y contratos de datos. La práctica es: Definir campos, tipos, requeridos y restricciones para observaciones de precio. La evidencia que debo producir es: Esquema y conjunto válido/inválido. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 26](evaluaciones.md#evaluación-día-26).

---

# Día 27 — Logging estructurado sin datos sensibles

**Objetivo de aprendizaje:** Implementar logging estructurado sin datos sensibles.

**Teoría y recurso:** [Python logging](https://docs.python.org/3/library/logging.html), [OWASP Logging](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Registrar inicio, conteos, duración y errores resumidos con datos sintéticos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Implementar logging estructurado sin datos sensibles.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Registrar inicio, conteos, duración y errores resumidos con datos sintéticos.
- Puedes justificar la evidencia que guardas y qué demuestra: Log JSON y revisión de exposición.

**Evidencia verificable:** Log JSON y revisión de exposición.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 27. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Implementar logging estructurado sin datos sensibles. La práctica es: Registrar inicio, conteos, duración y errores resumidos con datos sintéticos. La evidencia que debo producir es: Log JSON y revisión de exposición. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 27](evaluaciones.md#evaluación-día-27).

---

# Día 28 — Pruebas unitarias básicas

**Objetivo de aprendizaje:** Escribir pruebas unitarias básicas.

**Teoría y recurso:** [Python unittest](https://docs.python.org/3/library/unittest.html)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Probar funciones de validación para entradas correctas, nulas y límites.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Escribir pruebas unitarias básicas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Probar funciones de validación para entradas correctas, nulas y límites.
- Puedes justificar la evidencia que guardas y qué demuestra: Suite con pruebas positivas y negativas.

**Evidencia verificable:** Suite con pruebas positivas y negativas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 28. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Escribir pruebas unitarias básicas. La práctica es: Probar funciones de validación para entradas correctas, nulas y límites. La evidencia que debo producir es: Suite con pruebas positivas y negativas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 28](evaluaciones.md#evaluación-día-28).

---

# Día 29 — Errores HTTP y respuestas inesperadas

**Objetivo de aprendizaje:** Gestionar errores HTTP y respuestas inesperadas.

**Teoría y recurso:** [Requests: errors and exceptions](https://requests.readthedocs.io/en/latest/user/quickstart/#errors-and-exceptions)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Simular timeout, 404, 429 y JSON inválido; asignar respuesta apropiada.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Gestionar errores HTTP y respuestas inesperadas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Simular timeout, 404, 429 y JSON inválido; asignar respuesta apropiada.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de errores y comportamiento probado.

**Evidencia verificable:** Tabla de errores y comportamiento probado.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 29. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Gestionar errores HTTP y respuestas inesperadas. La práctica es: Simular timeout, 404, 429 y JSON inválido; asignar respuesta apropiada. La evidencia que debo producir es: Tabla de errores y comportamiento probado. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 29](evaluaciones.md#evaluación-día-29).

---

# Día 30 — Linaje y trazabilidad

**Objetivo de aprendizaje:** Documentar linaje y trazabilidad.

**Teoría y recurso:** [OpenLineage: documentation](https://openlineage.io/docs/)

**Herramientas:** Python 3 + VS Code; bibliotecas estándar y Requests cuando corresponda

**Práctica guiada (35 min):**

Definir fuente, timestamp, identificador, versión de transformación y destino.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Documentar linaje y trazabilidad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir fuente, timestamp, identificador, versión de transformación y destino.
- Puedes justificar la evidencia que guardas y qué demuestra: Registro de linaje de extremo a extremo.

**Evidencia verificable:** Registro de linaje de extremo a extremo.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 30. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Documentar linaje y trazabilidad. La práctica es: Definir fuente, timestamp, identificador, versión de transformación y destino. La evidencia que debo producir es: Registro de linaje de extremo a extremo. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 30](evaluaciones.md#evaluación-día-30).

---

# Día 31 — Anomalías simples sin confundirlas con incidentes

**Objetivo de aprendizaje:** Detectar anomalías simples sin confundirlas con incidentes.

**Teoría y recurso:** [NIST: SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Python 3 + VS Code; hoja de cálculo LibreOffice Calc (gratuita)

**Práctica guiada (35 min):**

Calcular rangos y variaciones en datos sintéticos; explicar umbrales.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Detectar anomalías simples sin confundirlas con incidentes.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Calcular rangos y variaciones en datos sintéticos; explicar umbrales.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de anomalías y limitaciones.

**Evidencia verificable:** Tabla de anomalías y limitaciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 31. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Detectar anomalías simples sin confundirlas con incidentes. La práctica es: Calcular rangos y variaciones en datos sintéticos; explicar umbrales. La evidencia que debo producir es: Tabla de anomalías y limitaciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 31](evaluaciones.md#evaluación-día-31).

---

# Día 32 — Completitud, validez y consistencia

**Objetivo de aprendizaje:** Medir completitud, validez y consistencia.

**Teoría y recurso:** [Great Expectations: Core concepts](https://docs.greatexpectations.io/docs/core/introduction/)

**Herramientas:** Python 3 + VS Code; hoja de cálculo LibreOffice Calc (gratuita)

**Práctica guiada (35 min):**

Definir métricas de calidad para campos obligatorios, precios y moneda.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Medir completitud, validez y consistencia.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir métricas de calidad para campos obligatorios, precios y moneda.
- Puedes justificar la evidencia que guardas y qué demuestra: Reporte de calidad con denominadores claros.

**Evidencia verificable:** Reporte de calidad con denominadores claros.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 32. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Medir completitud, validez y consistencia. La práctica es: Definir métricas de calidad para campos obligatorios, precios y moneda. La evidencia que debo producir es: Reporte de calidad con denominadores claros. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 32](evaluaciones.md#evaluación-día-32).

---

# Día 33 — Integridad y deduplicación

**Objetivo de aprendizaje:** Controlar integridad y deduplicación.

**Teoría y recurso:** [SQLite: constraints](https://www.sqlite.org/lang_createtable.html)

**Herramientas:** SQLite + DB Browser for SQLite (gratuito) o DBeaver Community

**Práctica guiada (35 min):**

Definir clave de negocio y restricciones; comparar duplicados exactos y potenciales.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Controlar integridad y deduplicación.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir clave de negocio y restricciones; comparar duplicados exactos y potenciales.
- Puedes justificar la evidencia que guardas y qué demuestra: Reglas, resultados y excepciones.

**Evidencia verificable:** Reglas, resultados y excepciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 33. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Controlar integridad y deduplicación. La práctica es: Definir clave de negocio y restricciones; comparar duplicados exactos y potenciales. La evidencia que debo producir es: Reglas, resultados y excepciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 33](evaluaciones.md#evaluación-día-33).

---

# Día 34 — Pipeline pequeño para PharmaTracker

**Objetivo de aprendizaje:** Construir pipeline pequeño para PharmaTracker.

**Teoría y recurso:** [Python: venv](https://docs.python.org/3/library/venv.html), [CSV](https://docs.python.org/3/library/csv.html)

**Herramientas:** Python 3 + VS Code + SQLite

**Práctica guiada (35 min):**

Encadenar lectura, validación, transformación y exportación sobre datos sintéticos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Construir pipeline pequeño para PharmaTracker.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Encadenar lectura, validación, transformación y exportación sobre datos sintéticos.
- Puedes justificar la evidencia que guardas y qué demuestra: Pipeline reproducible desde cero.

**Evidencia verificable:** Pipeline reproducible desde cero.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 34. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Construir pipeline pequeño para PharmaTracker. La práctica es: Encadenar lectura, validación, transformación y exportación sobre datos sintéticos. La evidencia que debo producir es: Pipeline reproducible desde cero. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 34](evaluaciones.md#evaluación-día-34).

---

# Día 35 — Seguridad y calidad del pipeline

**Objetivo de aprendizaje:** Revisar seguridad y calidad del pipeline.

**Teoría y recurso:** [OWASP: Secure Coding](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/)

**Herramientas:** Python 3 + VS Code + SQLite

**Práctica guiada (35 min):**

Revisar secretos, logs, entradas, dependencias, errores y trazabilidad.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Revisar seguridad y calidad del pipeline.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Revisar secretos, logs, entradas, dependencias, errores y trazabilidad.
- Puedes justificar la evidencia que guardas y qué demuestra: Checklist con hallazgos y correcciones.

**Evidencia verificable:** Checklist con hallazgos y correcciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 35. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Revisar seguridad y calidad del pipeline. La práctica es: Revisar secretos, logs, entradas, dependencias, errores y trazabilidad. La evidencia que debo producir es: Checklist con hallazgos y correcciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 35](evaluaciones.md#evaluación-día-35).

---

# Día 36 — Fase 2 y documentar resultados

**Objetivo de aprendizaje:** Evaluar fase 2 y documentar resultados.

**Teoría y recurso:** Revisión de recursos de sesiones 19–35.

**Herramientas:** Python 3 + VS Code + SQLite

**Práctica guiada (35 min):**

Ejecutar el pipeline con un dataset nuevo y justificar los rechazos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar fase 2 y documentar resultados.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Ejecutar el pipeline con un dataset nuevo y justificar los rechazos.
- Puedes justificar la evidencia que guardas y qué demuestra: Evaluación, pruebas y README actualizado.

**Evidencia verificable:** Evaluación, pruebas y README actualizado.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 36. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar fase 2 y documentar resultados. La práctica es: Ejecutar el pipeline con un dataset nuevo y justificar los rechazos. La evidencia que debo producir es: Evaluación, pruebas y README actualizado. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 36](evaluaciones.md#evaluación-día-36).

---

# Día 37 — Granularidad y modelo dimensional

**Objetivo de aprendizaje:** Definir granularidad y modelo dimensional.

**Teoría y recurso:** [Microsoft Learn: star schema](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Definir hechos y dimensiones para observaciones de precio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Definir granularidad y modelo dimensional.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Definir hechos y dimensiones para observaciones de precio.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama y declaración de granularidad.

**Evidencia verificable:** Diagrama y declaración de granularidad.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 37. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Definir granularidad y modelo dimensional. La práctica es: Definir hechos y dimensiones para observaciones de precio. La evidencia que debo producir es: Diagrama y declaración de granularidad. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 37](evaluaciones.md#evaluación-día-37).

---

# Día 38 — Relaciones y cardinalidad correctamente

**Objetivo de aprendizaje:** Configurar relaciones y cardinalidad correctamente.

**Teoría y recurso:** [Microsoft Learn: relationships](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-relationships-understand)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Analizar claves duplicadas y elegir dirección de filtro.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Configurar relaciones y cardinalidad correctamente.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Analizar claves duplicadas y elegir dirección de filtro.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama de relaciones y pruebas.

**Evidencia verificable:** Diagrama de relaciones y pruebas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 38. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Configurar relaciones y cardinalidad correctamente. La práctica es: Analizar claves duplicadas y elegir dirección de filtro. La evidencia que debo producir es: Diagrama de relaciones y pruebas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 38](evaluaciones.md#evaluación-día-38).

---

# Día 39 — Datos reproduciblemente con Power Query

**Objetivo de aprendizaje:** Transformar datos reproduciblemente con Power Query.

**Teoría y recurso:** [Microsoft Learn: Power Query](https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Documentar tipos, nulos, duplicados y pasos aplicados.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Transformar datos reproduciblemente con Power Query.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Documentar tipos, nulos, duplicados y pasos aplicados.
- Puedes justificar la evidencia que guardas y qué demuestra: Pasos de transformación y conteos.

**Evidencia verificable:** Pasos de transformación y conteos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 39. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Transformar datos reproduciblemente con Power Query. La práctica es: Documentar tipos, nulos, duplicados y pasos aplicados. La evidencia que debo producir es: Pasos de transformación y conteos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 39](evaluaciones.md#evaluación-día-39).

---

# Día 40 — Medidas DAX y contexto de filtro

**Objetivo de aprendizaje:** Comprender medidas DAX y contexto de filtro.

**Teoría y recurso:** [Microsoft Learn: DAX overview](https://learn.microsoft.com/en-us/dax/dax-overview)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Crear medidas sencillas y comparar medida con columna calculada.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Comprender medidas DAX y contexto de filtro.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear medidas sencillas y comparar medida con columna calculada.
- Puedes justificar la evidencia que guardas y qué demuestra: Medidas y resultados explicados.

**Evidencia verificable:** Medidas y resultados explicados.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 40. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Comprender medidas DAX y contexto de filtro. La práctica es: Crear medidas sencillas y comparar medida con columna calculada. La evidencia que debo producir es: Medidas y resultados explicados. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 40](evaluaciones.md#evaluación-día-40).

---

# Día 41 — Métricas de precios y variaciones

**Objetivo de aprendizaje:** Calcular métricas de precios y variaciones.

**Teoría y recurso:** [DAX function reference](https://learn.microsoft.com/en-us/dax/)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Calcular mínimo, máximo, promedio y cambio entre observaciones comparables.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Calcular métricas de precios y variaciones.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Calcular mínimo, máximo, promedio y cambio entre observaciones comparables.
- Puedes justificar la evidencia que guardas y qué demuestra: Diccionario de métricas y cálculo manual.

**Evidencia verificable:** Diccionario de métricas y cálculo manual.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 41. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Calcular métricas de precios y variaciones. La práctica es: Calcular mínimo, máximo, promedio y cambio entre observaciones comparables. La evidencia que debo producir es: Diccionario de métricas y cálculo manual. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 41](evaluaciones.md#evaluación-día-41).

---

# Día 42 — Indicadores y detectar errores de calidad

**Objetivo de aprendizaje:** Conciliar indicadores y detectar errores de calidad.

**Teoría y recurso:** [Microsoft Learn: data reduction](https://learn.microsoft.com/en-us/power-bi/guidance/import-modeling-data-reduction)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Comparar resultados del modelo con SQL/hoja de cálculo independiente.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Conciliar indicadores y detectar errores de calidad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Comparar resultados del modelo con SQL/hoja de cálculo independiente.
- Puedes justificar la evidencia que guardas y qué demuestra: Conciliación y diferencias explicadas.

**Evidencia verificable:** Conciliación y diferencias explicadas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 42. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Conciliar indicadores y detectar errores de calidad. La práctica es: Comparar resultados del modelo con SQL/hoja de cálculo independiente. La evidencia que debo producir es: Conciliación y diferencias explicadas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 42](evaluaciones.md#evaluación-día-42).

---

# Día 43 — Páginas orientadas a preguntas analíticas

**Objetivo de aprendizaje:** Diseñar páginas orientadas a preguntas analíticas.

**Teoría y recurso:** [Microsoft Learn: report design](https://learn.microsoft.com/en-us/power-bi/create-reports/service-dashboards-design-tips)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Bocetar una página de resumen y una de detalle con jerarquía visual.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Diseñar páginas orientadas a preguntas analíticas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Bocetar una página de resumen y una de detalle con jerarquía visual.
- Puedes justificar la evidencia que guardas y qué demuestra: Wireframe y preguntas que responde.

**Evidencia verificable:** Wireframe y preguntas que responde.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 43. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Diseñar páginas orientadas a preguntas analíticas. La práctica es: Bocetar una página de resumen y una de detalle con jerarquía visual. La evidencia que debo producir es: Wireframe y preguntas que responde. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 43](evaluaciones.md#evaluación-día-43).

---

# Día 44 — Filtros, segmentadores y navegación

**Objetivo de aprendizaje:** Usar filtros, segmentadores y navegación.

**Teoría y recurso:** [Microsoft Learn: filters](https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-report-filter)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Diseñar filtros por fecha, ciudad, tienda y producto.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Usar filtros, segmentadores y navegación.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Diseñar filtros por fecha, ciudad, tienda y producto.
- Puedes justificar la evidencia que guardas y qué demuestra: Reporte de prueba y casos de filtro.

**Evidencia verificable:** Reporte de prueba y casos de filtro.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 44. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Usar filtros, segmentadores y navegación. La práctica es: Diseñar filtros por fecha, ciudad, tienda y producto. La evidencia que debo producir es: Reporte de prueba y casos de filtro. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 44](evaluaciones.md#evaluación-día-44).

---

# Día 45 — Propósito y límites de RLS

**Objetivo de aprendizaje:** Explicar propósito y límites de RLS.

**Teoría y recurso:** [Microsoft Learn: row-level security](https://learn.microsoft.com/en-us/fabric/security/service-admin-row-level-security)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Diseñar roles ficticios y probar filtros con datos sintéticos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Explicar propósito y límites de RLS.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Diseñar roles ficticios y probar filtros con datos sintéticos.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz RLS y casos de prueba.

**Evidencia verificable:** Matriz RLS y casos de prueba.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 45. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Explicar propósito y límites de RLS. La práctica es: Diseñar roles ficticios y probar filtros con datos sintéticos. La evidencia que debo producir es: Matriz RLS y casos de prueba. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 45](evaluaciones.md#evaluación-día-45).

---

# Día 46 — Mínimo acceso a informes y modelos

**Objetivo de aprendizaje:** Aplicar mínimo acceso a informes y modelos.

**Teoría y recurso:** [Microsoft Learn: permissions](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-share-dashboards)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Comparar roles de workspace, permisos de modelo y compartir reportes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Aplicar mínimo acceso a informes y modelos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Comparar roles de workspace, permisos de modelo y compartir reportes.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de acceso y riesgos.

**Evidencia verificable:** Matriz de acceso y riesgos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 46. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Aplicar mínimo acceso a informes y modelos. La práctica es: Comparar roles de workspace, permisos de modelo y compartir reportes. La evidencia que debo producir es: Matriz de acceso y riesgos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 46](evaluaciones.md#evaluación-día-46).

---

# Día 47 — Campos y reducir exposición

**Objetivo de aprendizaje:** Clasificar campos y reducir exposición.

**Teoría y recurso:** [Microsoft Learn: sensitivity labels](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-overview)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Clasificar campos ficticios y decidir cuáles son necesarios para el análisis.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Clasificar campos y reducir exposición.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Clasificar campos ficticios y decidir cuáles son necesarios para el análisis.
- Puedes justificar la evidencia que guardas y qué demuestra: Inventario de campos y justificación.

**Evidencia verificable:** Inventario de campos y justificación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 47. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Clasificar campos y reducir exposición. La práctica es: Clasificar campos ficticios y decidir cuáles son necesarios para el análisis. La evidencia que debo producir es: Inventario de campos y justificación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 47](evaluaciones.md#evaluación-día-47).

---

# Día 48 — Anonimización y seudonimización

**Objetivo de aprendizaje:** Diferenciar anonimización y seudonimización.

**Teoría y recurso:** [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Transformar identificadores ficticios y discutir riesgo de reidentificación.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Diferenciar anonimización y seudonimización.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Transformar identificadores ficticios y discutir riesgo de reidentificación.
- Puedes justificar la evidencia que guardas y qué demuestra: Ejemplo y límites documentados.

**Evidencia verificable:** Ejemplo y límites documentados.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 48. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Diferenciar anonimización y seudonimización. La práctica es: Transformar identificadores ficticios y discutir riesgo de reidentificación. La evidencia que debo producir es: Ejemplo y límites documentados. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 48](evaluaciones.md#evaluación-día-48).

---

# Día 49 — Riesgos de exportación y compartición

**Objetivo de aprendizaje:** Evaluar riesgos de exportación y compartición.

**Teoría y recurso:** [Microsoft Learn: export data](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-export-data)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Crear escenarios de exportación y controles de distribución.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar riesgos de exportación y compartición.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear escenarios de exportación y controles de distribución.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz escenario/control.

**Evidencia verificable:** Matriz escenario/control.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 49. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar riesgos de exportación y compartición. La práctica es: Crear escenarios de exportación y controles de distribución. La evidencia que debo producir es: Matriz escenario/control. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 49](evaluaciones.md#evaluación-día-49).

---

# Día 50 — Definiciones, medidas y propietarios

**Objetivo de aprendizaje:** Documentar definiciones, medidas y propietarios.

**Teoría y recurso:** [Microsoft Learn: semantic models](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-understand)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Crear diccionario de métricas con fórmula, propósito y limitaciones.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Documentar definiciones, medidas y propietarios.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear diccionario de métricas con fórmula, propósito y limitaciones.
- Puedes justificar la evidencia que guardas y qué demuestra: Diccionario de datos y métricas.

**Evidencia verificable:** Diccionario de datos y métricas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 50. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Documentar definiciones, medidas y propietarios. La práctica es: Crear diccionario de métricas con fórmula, propósito y limitaciones. La evidencia que debo producir es: Diccionario de datos y métricas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 50](evaluaciones.md#evaluación-día-50).

---

# Día 51 — Accesibilidad, claridad y usabilidad

**Objetivo de aprendizaje:** Revisar accesibilidad, claridad y usabilidad.

**Teoría y recurso:** [Microsoft Learn: report accessibility](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-accessibility-creating-reports)

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Evaluar títulos, contraste, orden de lectura y alternativas a color.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Revisar accesibilidad, claridad y usabilidad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Evaluar títulos, contraste, orden de lectura y alternativas a color.
- Puedes justificar la evidencia que guardas y qué demuestra: Checklist de accesibilidad y mejoras.

**Evidencia verificable:** Checklist de accesibilidad y mejoras.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 51. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Revisar accesibilidad, claridad y usabilidad. La práctica es: Evaluar títulos, contraste, orden de lectura y alternativas a color. La evidencia que debo producir es: Checklist de accesibilidad y mejoras. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 51](evaluaciones.md#evaluación-día-51).

---

# Día 52 — Fase 3 y revisar modelo

**Objetivo de aprendizaje:** Evaluar fase 3 y revisar modelo.

**Teoría y recurso:** Revisión de recursos de sesiones 37–51.

**Herramientas:** Power BI Desktop (gratuito, en Windows) + archivos CSV; SQLite/LibreOffice Calc para conciliación cuando corresponda

**Práctica guiada (35 min):**

Defender el modelo, reconciliar 3 métricas y explicar límites de seguridad.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar fase 3 y revisar modelo.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Defender el modelo, reconciliar 3 métricas y explicar límites de seguridad.
- Puedes justificar la evidencia que guardas y qué demuestra: Evaluación y paquete de evidencia.

**Evidencia verificable:** Evaluación y paquete de evidencia.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 52. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar fase 3 y revisar modelo. La práctica es: Defender el modelo, reconciliar 3 métricas y explicar límites de seguridad. La evidencia que debo producir es: Evaluación y paquete de evidencia. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 52](evaluaciones.md#evaluación-día-52).

---

# Día 53 — Un evento real de laboratorio con vocabulario MITRE ATT&CK, sin convertir la etiqueta en confirmación de incidente

**Objetivo de aprendizaje:** Clasificar un evento real de laboratorio con vocabulario MITRE ATT&CK, sin convertir la etiqueta en confirmación de incidente.

**Teoría y recurso:** [MITRE ATT&CK T1110.001](https://attack.mitre.org/techniques/T1110/001/), [guía del laboratorio](../labs/phase-04-log-analysis/attack-context.md)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

Analizar el fallo SSH sintético que Wazuh 4.9.0 asoció con la regla 5710 (nivel 5) y T1110.001 — Password Guessing. Separar log observado, etiqueta y conclusión.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Clasificar un evento real de laboratorio con vocabulario MITRE ATT&CK, sin convertir la etiqueta en confirmación de incidente.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Analizar el fallo SSH sintético que Wazuh 4.9.0 asoció con la regla 5710 (nivel 5) y T1110.001 — Password Guessing. Separar log observado, etiqueta y conclusión.
- Puedes justificar la evidencia que guardas y qué demuestra: Ficha del evento con regla, nivel, técnica, confianza y evidencia faltante.

**Evidencia verificable:** Ficha del evento con regla, nivel, técnica, confianza y evidencia faltante.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 53. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Clasificar un evento real de laboratorio con vocabulario MITRE ATT&CK, sin convertir la etiqueta en confirmación de incidente. La práctica es: Analizar el fallo SSH sintético que Wazuh 4.9.0 asoció con la regla 5710 (nivel 5) y T1110.001 — Password Guessing. Separar log observado, etiqueta y conclusión. La evidencia que debo producir es: Ficha del evento con regla, nivel, técnica, confianza y evidencia faltante. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 53](evaluaciones.md#evaluación-día-53).

---

# Día 54 — El mapeo log → técnica ATT&CK a partir de la alerta validada

**Objetivo de aprendizaje:** Construir el mapeo log → técnica ATT&CK a partir de la alerta validada.

**Teoría y recurso:** [MITRE ATT&CK T1110.001](https://attack.mitre.org/techniques/T1110/001/), [guía del laboratorio](../labs/phase-04-log-analysis/attack-context.md)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

Completar SSH-01: fallo SSH → Credential Access → T1110.001; verificar `rule.mitre.id` y registrar `srcip` / `srcuser`.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Construir el mapeo log → técnica ATT&CK a partir de la alerta validada.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Completar SSH-01: fallo SSH → Credential Access → T1110.001; verificar `rule.mitre.id` y registrar `srcip` / `srcuser`.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla/CSV con evento, regla 5710, nivel 5, técnica, fuente, confianza y datos faltantes.

**Evidencia verificable:** Tabla/CSV con evento, regla 5710, nivel 5, técnica, fuente, confianza y datos faltantes.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 54. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Construir el mapeo log → técnica ATT&CK a partir de la alerta validada. La práctica es: Completar SSH-01: fallo SSH → Credential Access → T1110.001; verificar `rule.mitre.id` y registrar `srcip` / `srcuser`. La evidencia que debo producir es: Tabla/CSV con evento, regla 5710, nivel 5, técnica, fuente, confianza y datos faltantes. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 54](evaluaciones.md#evaluación-día-54).

---

# Día 55 — Consultar en Wazuh la alerta de fallo SSH ya ingerida y documentar sus campos

**Objetivo de aprendizaje:** Consultar en Wazuh la alerta de fallo SSH ya ingerida y documentar sus campos.

**Teoría y recurso:** [Checklist SIEM](../templates/lab-validation-checklist.md), [Wazuh 4.9 documentation](https://documentation.wazuh.com/4.9/)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

En Discover, filtrar la alerta de regla 5710 y revisar `srcip`, `srcuser`, `rule.id`, `rule.level` y `rule.mitre.id`.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Consultar en Wazuh la alerta de fallo SSH ya ingerida y documentar sus campos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: En Discover, filtrar la alerta de regla 5710 y revisar `srcip`, `srcuser`, `rule.id`, `rule.level` y `rule.mitre.id`.
- Puedes justificar la evidencia que guardas y qué demuestra: Captura saneada y tabla de campos con valores observados; no inventar valores si no aparecen.

**Evidencia verificable:** Captura saneada y tabla de campos con valores observados; no inventar valores si no aparecen.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 55. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Consultar en Wazuh la alerta de fallo SSH ya ingerida y documentar sus campos. La práctica es: En Discover, filtrar la alerta de regla 5710 y revisar `srcip`, `srcuser`, `rule.id`, `rule.level` y `rule.mitre.id`. La evidencia que debo producir es: Captura saneada y tabla de campos con valores observados; no inventar valores si no aparecen. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 55](evaluaciones.md#evaluación-día-55).

---

# Día 56 — Consultar y agregar alertas Wazuh por IP, usuario y técnica

**Objetivo de aprendizaje:** Consultar y agregar alertas Wazuh por IP, usuario y técnica.

**Teoría y recurso:** [Wazuh 4.9 documentation](https://documentation.wazuh.com/4.9/)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

Usar filtros `rule.id:5710` y `rule.mitre.id:T1110.001`; agrupar por `srcip` y `srcuser`.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Consultar y agregar alertas Wazuh por IP, usuario y técnica.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Usar filtros `rule.id:5710` y `rule.mitre.id:T1110.001`; agrupar por `srcip` y `srcuser`.
- Puedes justificar la evidencia que guardas y qué demuestra: Consultas guardadas y tabla agregada; conciliación con el evento sintético.

**Evidencia verificable:** Consultas guardadas y tabla agregada; conciliación con el evento sintético.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 56. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Consultar y agregar alertas Wazuh por IP, usuario y técnica. La práctica es: Usar filtros `rule.id:5710` y `rule.mitre.id:T1110.001`; agrupar por `srcip` y `srcuser`. La evidencia que debo producir es: Consultas guardadas y tabla agregada; conciliación con el evento sintético. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 56](evaluaciones.md#evaluación-día-56).

---

# Día 57 — Calidad de los documentos de alerta Wazuh

**Objetivo de aprendizaje:** Evaluar calidad de los documentos de alerta Wazuh.

**Teoría y recurso:** [OWASP Logging](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html), [Wazuh 4.9 documentation](https://documentation.wazuh.com/4.9/)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

Medir completitud de `srcip`, `srcuser`, `rule.mitre.id`; revisar nulos, duplicados y formatos inconsistentes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar calidad de los documentos de alerta Wazuh.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Medir completitud de `srcip`, `srcuser`, `rule.mitre.id`; revisar nulos, duplicados y formatos inconsistentes.
- Puedes justificar la evidencia que guardas y qué demuestra: Reporte de calidad con denominadores, excepciones y conteos antes/después.

**Evidencia verificable:** Reporte de calidad con denominadores, excepciones y conteos antes/después.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 57. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar calidad de los documentos de alerta Wazuh. La práctica es: Medir completitud de `srcip`, `srcuser`, `rule.mitre.id`; revisar nulos, duplicados y formatos inconsistentes. La evidencia que debo producir es: Reporte de calidad con denominadores, excepciones y conteos antes/después. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 57](evaluaciones.md#evaluación-día-57).

---

# Día 58 — Dashboard de reporting sobre la alerta SSH y sus dimensiones

**Objetivo de aprendizaje:** Construir dashboard de reporting sobre la alerta SSH y sus dimensiones.

**Teoría y recurso:** [Wazuh Dashboard documentation](https://documentation.wazuh.com/4.9/user-manual/wazuh-dashboard/index.html), [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Docker Desktop + navegador web (Chrome o Firefox) + Wazuh Dashboard 4.9.0

**Práctica guiada (35 min):**

Visualizar alertas por periodo, regla/nivel, `srcip`, `srcuser` y `rule.mitre.id`; incluir filtro de regla 5710.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Construir dashboard de reporting sobre la alerta SSH y sus dimensiones.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Visualizar alertas por periodo, regla/nivel, `srcip`, `srcuser` y `rule.mitre.id`; incluir filtro de regla 5710.
- Puedes justificar la evidencia que guardas y qué demuestra: Dashboard/capturas saneadas y diccionario de métricas con límites.

**Evidencia verificable:** Dashboard/capturas saneadas y diccionario de métricas con límites.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 58. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Construir dashboard de reporting sobre la alerta SSH y sus dimensiones. La práctica es: Visualizar alertas por periodo, regla/nivel, `srcip`, `srcuser` y `rule.mitre.id`; incluir filtro de regla 5710. La evidencia que debo producir es: Dashboard/capturas saneadas y diccionario de métricas con límites. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 58](evaluaciones.md#evaluación-día-58).

---

# Día 59 — Filtrar y agregar eventos

**Objetivo de aprendizaje:** Filtrar y agregar eventos.

**Teoría y recurso:** Documentación de consulta de la plataforma validada

**Herramientas:** Wazuh Dashboard 4.9.0 en navegador web

**Práctica guiada (35 min):**

Contar eventos por tipo, resultado y alias ficticio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Filtrar y agregar eventos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Contar eventos por tipo, resultado y alias ficticio.
- Puedes justificar la evidencia que guardas y qué demuestra: Consulta, tabla agregada y conciliación.

**Evidencia verificable:** Consulta, tabla agregada y conciliación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 59. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Filtrar y agregar eventos. La práctica es: Contar eventos por tipo, resultado y alias ficticio. La evidencia que debo producir es: Consulta, tabla agregada y conciliación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 59](evaluaciones.md#evaluación-día-59).

---

# Día 60 — Resumir comportamiento por ventanas temporales

**Objetivo de aprendizaje:** Resumir comportamiento por ventanas temporales.

**Teoría y recurso:** [Python datetime](https://docs.python.org/3/library/datetime.html)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Agrupar fallos sintéticos por alias y ventana de diez minutos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Resumir comportamiento por ventanas temporales.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Agrupar fallos sintéticos por alias y ventana de diez minutos.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla temporal con conteos y parámetros.

**Evidencia verificable:** Tabla temporal con conteos y parámetros.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 60. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Resumir comportamiento por ventanas temporales. La práctica es: Agrupar fallos sintéticos por alias y ventana de diez minutos. La evidencia que debo producir es: Tabla temporal con conteos y parámetros. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 60](evaluaciones.md#evaluación-día-60).

---

# Día 61 — Coincidencias y falsos positivos potenciales

**Objetivo de aprendizaje:** Cuantificar coincidencias y falsos positivos potenciales.

**Teoría y recurso:** [Google SRE: Monitoring](https://sre.google/sre-book/monitoring-distributed-systems/)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Comparar grupos normales y atípicos en el dataset.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Cuantificar coincidencias y falsos positivos potenciales.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Comparar grupos normales y atípicos en el dataset.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de conteos y nota de limitaciones.

**Evidencia verificable:** Matriz de conteos y nota de limitaciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 61. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Cuantificar coincidencias y falsos positivos potenciales. La práctica es: Comparar grupos normales y atípicos en el dataset. La evidencia que debo producir es: Matriz de conteos y nota de limitaciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 61](evaluaciones.md#evaluación-día-61).

---

# Día 62 — Enriquecer datos con contexto descriptivo permitido

**Objetivo de aprendizaje:** Enriquecer datos con contexto descriptivo permitido.

**Teoría y recurso:** [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Añadir etiquetas ficticias de activo, entorno y criticidad.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Enriquecer datos con contexto descriptivo permitido.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Añadir etiquetas ficticias de activo, entorno y criticidad.
- Puedes justificar la evidencia que guardas y qué demuestra: Dataset enriquecido y diccionario de campos.

**Evidencia verificable:** Dataset enriquecido y diccionario de campos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 62. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Enriquecer datos con contexto descriptivo permitido. La práctica es: Añadir etiquetas ficticias de activo, entorno y criticidad. La evidencia que debo producir es: Dataset enriquecido y diccionario de campos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 62](evaluaciones.md#evaluación-día-62).

---

# Día 63 — Secuencias temporales con claves disponibles

**Objetivo de aprendizaje:** Analizar secuencias temporales con claves disponibles.

**Teoría y recurso:** [Python datetime](https://docs.python.org/3/library/datetime.html)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Agrupar por alias/request_id y revisar timestamps inválidos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar secuencias temporales con claves disponibles.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Agrupar por alias/request_id y revisar timestamps inválidos.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de secuencias y excepciones.

**Evidencia verificable:** Tabla de secuencias y excepciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 63. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar secuencias temporales con claves disponibles. La práctica es: Agrupar por alias/request_id y revisar timestamps inválidos. La evidencia que debo producir es: Tabla de secuencias y excepciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 63](evaluaciones.md#evaluación-día-63).

---

# Día 64 — Comunicar patrones observados en datos de eventos

**Objetivo de aprendizaje:** Comunicar patrones observados en datos de eventos.

**Teoría y recurso:** [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Resumir qué, cuándo, volumen, cobertura e incertidumbre.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Comunicar patrones observados en datos de eventos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resumir qué, cuándo, volumen, cobertura e incertidumbre.
- Puedes justificar la evidencia que guardas y qué demuestra: Informe analítico breve basado en datos.

**Evidencia verificable:** Informe analítico breve basado en datos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 64. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Comunicar patrones observados en datos de eventos. La práctica es: Resumir qué, cuándo, volumen, cobertura e incertidumbre. La evidencia que debo producir es: Informe analítico breve basado en datos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 64](evaluaciones.md#evaluación-día-64).

---

# Día 65 — Escenarios con criterios de impacto documentados

**Objetivo de aprendizaje:** Comparar escenarios con criterios de impacto documentados.

**Teoría y recurso:** [NIST SP 800-30 Rev. 1](https://csrc.nist.gov/pubs/sp/800/30/r1/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Analizar una tabla sintética de impacto/probabilidad y explicar supuestos.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Comparar escenarios con criterios de impacto documentados.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Analizar una tabla sintética de impacto/probabilidad y explicar supuestos.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz comparativa y resumen de criterios.

**Evidencia verificable:** Matriz comparativa y resumen de criterios.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 65. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Comparar escenarios con criterios de impacto documentados. La práctica es: Analizar una tabla sintética de impacto/probabilidad y explicar supuestos. La evidencia que debo producir es: Matriz comparativa y resumen de criterios. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 65](evaluaciones.md#evaluación-día-65).

---

# Día 66 — La distribución y calidad de registros asociados a casos ficticios

**Objetivo de aprendizaje:** Analizar la distribución y calidad de registros asociados a casos ficticios.

**Teoría y recurso:** [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Agrupar registros por caso ficticio, periodo y categoría, sin ejecutar flujos de respuesta.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar la distribución y calidad de registros asociados a casos ficticios.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Agrupar registros por caso ficticio, periodo y categoría, sin ejecutar flujos de respuesta.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de casos, cobertura y limitaciones.

**Evidencia verificable:** Tabla de casos, cobertura y limitaciones.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 66. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar la distribución y calidad de registros asociados a casos ficticios. La práctica es: Agrupar registros por caso ficticio, periodo y categoría, sin ejecutar flujos de respuesta. La evidencia que debo producir es: Tabla de casos, cobertura y limitaciones. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 66](evaluaciones.md#evaluación-día-66).

---

# Día 67 — Periodos de conservación por tipo de dato

**Objetivo de aprendizaje:** Comparar periodos de conservación por tipo de dato.

**Teoría y recurso:** [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Resumir volumen y antigüedad de eventos sintéticos por categoría.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Comparar periodos de conservación por tipo de dato.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resumir volumen y antigüedad de eventos sintéticos por categoría.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de retención propuesta y volumen estimado.

**Evidencia verificable:** Tabla de retención propuesta y volumen estimado.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 67. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Comparar periodos de conservación por tipo de dato. La práctica es: Resumir volumen y antigüedad de eventos sintéticos por categoría. La evidencia que debo producir es: Tabla de retención propuesta y volumen estimado. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 67](evaluaciones.md#evaluación-día-67).

---

# Día 68 — Exposición de campos sensibles en registros

**Objetivo de aprendizaje:** Medir exposición de campos sensibles en registros.

**Teoría y recurso:** [OWASP Logging](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Revisar logs sintéticos y contar campos que requieren exclusión o enmascaramiento.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Medir exposición de campos sensibles en registros.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Revisar logs sintéticos y contar campos que requieren exclusión o enmascaramiento.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de exposición y log sintético saneado.

**Evidencia verificable:** Tabla de exposición y log sintético saneado.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 68. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Medir exposición de campos sensibles en registros. La práctica es: Revisar logs sintéticos y contar campos que requieren exclusión o enmascaramiento. La evidencia que debo producir es: Tabla de exposición y log sintético saneado. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 68](evaluaciones.md#evaluación-día-68).

---

# Día 69 — Triage como estructura de datos, sin ejecutar respuesta activa

**Objetivo de aprendizaje:** Documentar triage como estructura de datos, sin ejecutar respuesta activa.

**Teoría y recurso:** [Plantilla de ticket sintético](../labs/phase-04-log-analysis/triage-data-template.md), [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final)

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Completar ticket con caso sintético; separar observación, hipótesis y campos faltantes/sobrantes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Documentar triage como estructura de datos, sin ejecutar respuesta activa.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Completar ticket con caso sintético; separar observación, hipótesis y campos faltantes/sobrantes.
- Puedes justificar la evidencia que guardas y qué demuestra: Ticket rellenado, tabla de datos faltantes/sobrantes e informe breve.

**Evidencia verificable:** Ticket rellenado, tabla de datos faltantes/sobrantes e informe breve.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 69. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Documentar triage como estructura de datos, sin ejecutar respuesta activa. La práctica es: Completar ticket con caso sintético; separar observación, hipótesis y campos faltantes/sobrantes. La evidencia que debo producir es: Ticket rellenado, tabla de datos faltantes/sobrantes e informe breve. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 69](evaluaciones.md#evaluación-día-69).

---

# Día 70 — Resultados de análisis de datos de seguridad

**Objetivo de aprendizaje:** Presentar resultados de análisis de datos de seguridad.

**Teoría y recurso:** Revisión de recursos de sesiones 53–69.

**Herramientas:** Python 3 + VS Code + archivos CSV; Wazuh Dashboard 4.9.0 cuando se consulte la alerta

**Práctica guiada (35 min):**

Resolver un caso de datos nuevo y justificar filtros, métricas y límites.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Presentar resultados de análisis de datos de seguridad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resolver un caso de datos nuevo y justificar filtros, métricas y límites.
- Puedes justificar la evidencia que guardas y qué demuestra: Paquete de consultas, tablas y reporte ejecutivo.

**Evidencia verificable:** Paquete de consultas, tablas y reporte ejecutivo.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 70. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Presentar resultados de análisis de datos de seguridad. La práctica es: Resolver un caso de datos nuevo y justificar filtros, métricas y límites. La evidencia que debo producir es: Paquete de consultas, tablas y reporte ejecutivo. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 70](evaluaciones.md#evaluación-día-70).

---

# Día 71 — Roles y responsabilidades de gobierno

**Objetivo de aprendizaje:** Definir roles y responsabilidades de gobierno.

**Teoría y recurso:** [DAMA: overview](https://www.dama.org/cpages/body-of-knowledge)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Asignar roles propuestos a un flujo de datos ficticio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Definir roles y responsabilidades de gobierno.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Asignar roles propuestos a un flujo de datos ficticio.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de roles y responsabilidades.

**Evidencia verificable:** Matriz de roles y responsabilidades.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 71. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Definir roles y responsabilidades de gobierno. La práctica es: Asignar roles propuestos a un flujo de datos ficticio. La evidencia que debo producir es: Matriz de roles y responsabilidades. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 71](evaluaciones.md#evaluación-día-71).

---

# Día 72 — Inventario y clasificación de datos

**Objetivo de aprendizaje:** Crear inventario y clasificación de datos.

**Teoría y recurso:** [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Inventariar campos de PharmaTracker y clasificar sensibilidad/propósito.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Crear inventario y clasificación de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Inventariar campos de PharmaTracker y clasificar sensibilidad/propósito.
- Puedes justificar la evidencia que guardas y qué demuestra: Inventario de datos.

**Evidencia verificable:** Inventario de datos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 72. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Crear inventario y clasificación de datos. La práctica es: Inventariar campos de PharmaTracker y clasificar sensibilidad/propósito. La evidencia que debo producir es: Inventario de datos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 72](evaluaciones.md#evaluación-día-72).

---

# Día 73 — Catálogo, metadatos y definiciones

**Objetivo de aprendizaje:** Documentar catálogo, metadatos y definiciones.

**Teoría y recurso:** [W3C: Data Catalog Vocabulary](https://www.w3.org/TR/vocab-dcat-3/)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Crear ficha de dataset con propietario, frecuencia, formato y limitaciones.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Documentar catálogo, metadatos y definiciones.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear ficha de dataset con propietario, frecuencia, formato y limitaciones.
- Puedes justificar la evidencia que guardas y qué demuestra: Entrada de catálogo.

**Evidencia verificable:** Entrada de catálogo.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 73. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Documentar catálogo, metadatos y definiciones. La práctica es: Crear ficha de dataset con propietario, frecuencia, formato y limitaciones. La evidencia que debo producir es: Entrada de catálogo. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 73](evaluaciones.md#evaluación-día-73).

---

# Día 74 — Trazar linaje desde origen hasta reporte

**Objetivo de aprendizaje:** Trazar linaje desde origen hasta reporte.

**Teoría y recurso:** [OpenLineage](https://openlineage.io/docs/)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Dibujar fuentes, transformaciones, almacenamiento y consumo analítico.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Trazar linaje desde origen hasta reporte.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Dibujar fuentes, transformaciones, almacenamiento y consumo analítico.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama de linaje y puntos de control.

**Evidencia verificable:** Diagrama de linaje y puntos de control.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 74. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Trazar linaje desde origen hasta reporte. La práctica es: Dibujar fuentes, transformaciones, almacenamiento y consumo analítico. La evidencia que debo producir es: Diagrama de linaje y puntos de control. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 74](evaluaciones.md#evaluación-día-74).

---

# Día 75 — Reglas de calidad y aceptación

**Objetivo de aprendizaje:** Definir reglas de calidad y aceptación.

**Teoría y recurso:** [Great Expectations](https://docs.greatexpectations.io/docs/core/introduction/)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Especificar umbrales y tratamiento de excepciones para observaciones de precio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Definir reglas de calidad y aceptación.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Especificar umbrales y tratamiento de excepciones para observaciones de precio.
- Puedes justificar la evidencia que guardas y qué demuestra: Catálogo de reglas y criterios de aceptación.

**Evidencia verificable:** Catálogo de reglas y criterios de aceptación.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 75. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Definir reglas de calidad y aceptación. La práctica es: Especificar umbrales y tratamiento de excepciones para observaciones de precio. La evidencia que debo producir es: Catálogo de reglas y criterios de aceptación. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 75](evaluaciones.md#evaluación-día-75).

---

# Día 76 — Privacidad desde el diseño y minimización

**Objetivo de aprendizaje:** Aplicar privacidad desde el diseño y minimización.

**Teoría y recurso:** [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Revisar campos y eliminar los que no aportan al propósito.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Aplicar privacidad desde el diseño y minimización.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Revisar campos y eliminar los que no aportan al propósito.
- Puedes justificar la evidencia que guardas y qué demuestra: Análisis de necesidad y minimización.

**Evidencia verificable:** Análisis de necesidad y minimización.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 76. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Aplicar privacidad desde el diseño y minimización. La práctica es: Revisar campos y eliminar los que no aportan al propósito. La evidencia que debo producir es: Análisis de necesidad y minimización. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 76](evaluaciones.md#evaluación-día-76).

---

# Día 77 — Propósito, retención y eliminación

**Objetivo de aprendizaje:** Definir propósito, retención y eliminación.

**Teoría y recurso:** [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Proponer reglas de retención para datos sintéticos y documentar eliminación verificable.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Definir propósito, retención y eliminación.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Proponer reglas de retención para datos sintéticos y documentar eliminación verificable.
- Puedes justificar la evidencia que guardas y qué demuestra: Registro de retención propuesto.

**Evidencia verificable:** Registro de retención propuesto.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 77. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Definir propósito, retención y eliminación. La práctica es: Proponer reglas de retención para datos sintéticos y documentar eliminación verificable. La evidencia que debo producir es: Registro de retención propuesto. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 77](evaluaciones.md#evaluación-día-77).

---

# Día 78 — Control de acceso y revisiones periódicas

**Objetivo de aprendizaje:** Diseñar control de acceso y revisiones periódicas.

**Teoría y recurso:** [NIST SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Crear matriz de acceso por rol y frecuencia de revisión.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Diseñar control de acceso y revisiones periódicas.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear matriz de acceso por rol y frecuencia de revisión.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de acceso y revisión.

**Evidencia verificable:** Matriz de acceso y revisión.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 78. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Diseñar control de acceso y revisiones periódicas. La práctica es: Crear matriz de acceso por rol y frecuencia de revisión. La evidencia que debo producir es: Matriz de acceso y revisión. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 78](evaluaciones.md#evaluación-día-78).

---

# Día 79 — Registros sintéticos asociados a eventos de riesgo desde la perspectiva de datos

**Objetivo de aprendizaje:** Analizar registros sintéticos asociados a eventos de riesgo desde la perspectiva de datos.

**Teoría y recurso:** [NIST SP 800-92](https://csrc.nist.gov/pubs/sp/800/92/final)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Resumir volúmenes, periodos, categorías y calidad de registros de un caso ficticio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar registros sintéticos asociados a eventos de riesgo desde la perspectiva de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resumir volúmenes, periodos, categorías y calidad de registros de un caso ficticio.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla analítica e informe de cobertura, sin procedimiento de respuesta.

**Evidencia verificable:** Tabla analítica e informe de cobertura, sin procedimiento de respuesta.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 79. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar registros sintéticos asociados a eventos de riesgo desde la perspectiva de datos. La práctica es: Resumir volúmenes, periodos, categorías y calidad de registros de un caso ficticio. La evidencia que debo producir es: Tabla analítica e informe de cobertura, sin procedimiento de respuesta. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 79](evaluaciones.md#evaluación-día-79).

---

# Día 80 — Riesgo, impacto y evidencia de control

**Objetivo de aprendizaje:** Evaluar riesgo, impacto y evidencia de control.

**Teoría y recurso:** [NIST SP 800-30 Rev. 1](https://csrc.nist.gov/pubs/sp/800/30/r1/final)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Valorar riesgos del pipeline y distinguir control existente/propuesto.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar riesgo, impacto y evidencia de control.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Valorar riesgos del pipeline y distinguir control existente/propuesto.
- Puedes justificar la evidencia que guardas y qué demuestra: Registro de riesgos con riesgo residual.

**Evidencia verificable:** Registro de riesgos con riesgo residual.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 80. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar riesgo, impacto y evidencia de control. La práctica es: Valorar riesgos del pipeline y distinguir control existente/propuesto. La evidencia que debo producir es: Registro de riesgos con riesgo residual. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 80](evaluaciones.md#evaluación-día-80).

---

# Día 81 — Metadatos y cobertura de políticas de datos

**Objetivo de aprendizaje:** Analizar metadatos y cobertura de políticas de datos.

**Teoría y recurso:** [NIST SP 800-12 Rev. 1](https://csrc.nist.gov/pubs/sp/800/12/r1/final)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Clasificar registros sintéticos de políticas por propósito, propietario, versión y fecha de revisión.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar metadatos y cobertura de políticas de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Clasificar registros sintéticos de políticas por propósito, propietario, versión y fecha de revisión.
- Puedes justificar la evidencia que guardas y qué demuestra: Tabla de metadatos y reporte de cobertura.

**Evidencia verificable:** Tabla de metadatos y reporte de cobertura.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 81. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar metadatos y cobertura de políticas de datos. La práctica es: Clasificar registros sintéticos de políticas por propósito, propietario, versión y fecha de revisión. La evidencia que debo producir es: Tabla de metadatos y reporte de cobertura. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 81](evaluaciones.md#evaluación-día-81).

---

# Día 82 — Fuentes y proveedores de datos

**Objetivo de aprendizaje:** Evaluar fuentes y proveedores de datos.

**Teoría y recurso:** [NIST Cybersecurity Supply Chain Risk Management](https://csrc.nist.gov/projects/cyber-supply-chain-risk-management)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Puntuar permiso, confiabilidad, disponibilidad, límites y trazabilidad de fuentes.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Evaluar fuentes y proveedores de datos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Puntuar permiso, confiabilidad, disponibilidad, límites y trazabilidad de fuentes.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de evaluación de fuentes.

**Evidencia verificable:** Matriz de evaluación de fuentes.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 82. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Evaluar fuentes y proveedores de datos. La práctica es: Puntuar permiso, confiabilidad, disponibilidad, límites y trazabilidad de fuentes. La evidencia que debo producir es: Matriz de evaluación de fuentes. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 82](evaluaciones.md#evaluación-día-82).

---

# Día 83 — Cumplimiento con límites explícitos

**Objetivo de aprendizaje:** Revisar cumplimiento con límites explícitos.

**Teoría y recurso:** [NIST Privacy Framework](https://www.nist.gov/privacy-framework)

**Herramientas:** LibreOffice Calc + VS Code/editor Markdown + archivos CSV

**Práctica guiada (35 min):**

Crear checklist de preguntas y señalar qué requiere revisión legal especializada.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Revisar cumplimiento con límites explícitos.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Crear checklist de preguntas y señalar qué requiere revisión legal especializada.
- Puedes justificar la evidencia que guardas y qué demuestra: Checklist con exclusiones y pendientes.

**Evidencia verificable:** Checklist con exclusiones y pendientes.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 83. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Revisar cumplimiento con límites explícitos. La práctica es: Crear checklist de preguntas y señalar qué requiere revisión legal especializada. La evidencia que debo producir es: Checklist con exclusiones y pendientes. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 83](evaluaciones.md#evaluación-día-83).

---

# Día 84 — Arquitectura y alcance de PharmaTracker

**Objetivo de aprendizaje:** Definir arquitectura y alcance de PharmaTracker.

**Teoría y recurso:** [C4 model](https://c4model.com/)

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Dibujar contexto, contenedores y flujos; separar implementado de propuesto.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Definir arquitectura y alcance de PharmaTracker.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Dibujar contexto, contenedores y flujos; separar implementado de propuesto.
- Puedes justificar la evidencia que guardas y qué demuestra: Diagrama de arquitectura y alcance.

**Evidencia verificable:** Diagrama de arquitectura y alcance.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 84. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Definir arquitectura y alcance de PharmaTracker. La práctica es: Dibujar contexto, contenedores y flujos; separar implementado de propuesto. La evidencia que debo producir es: Diagrama de arquitectura y alcance. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 84](evaluaciones.md#evaluación-día-84).

---

# Día 85 — Controles de extracción y validación

**Objetivo de aprendizaje:** Documentar controles de extracción y validación.

**Teoría y recurso:** [OWASP Input Validation](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html)

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Trazar controles de origen, formato, esquema, duplicados y errores.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Documentar controles de extracción y validación.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Trazar controles de origen, formato, esquema, duplicados y errores.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de controles de extracción.

**Evidencia verificable:** Matriz de controles de extracción.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 85. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Documentar controles de extracción y validación. La práctica es: Trazar controles de origen, formato, esquema, duplicados y errores. La evidencia que debo producir es: Matriz de controles de extracción. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 85](evaluaciones.md#evaluación-día-85).

---

# Día 86 — La clasificación de campos de almacenamiento y metadatos de acceso

**Objetivo de aprendizaje:** Analizar la clasificación de campos de almacenamiento y metadatos de acceso.

**Teoría y recurso:** [GitHub: secure use](https://docs.github.com/en/actions/security-for-github-actions/security-guides/security-hardening-for-github-actions)

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Resumir campos sensibles, roles autorizados y atributos de trazabilidad en un conjunto ficticio.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar la clasificación de campos de almacenamiento y metadatos de acceso.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Resumir campos sensibles, roles autorizados y atributos de trazabilidad en un conjunto ficticio.
- Puedes justificar la evidencia que guardas y qué demuestra: Matriz de campos/roles y reporte de exposición.

**Evidencia verificable:** Matriz de campos/roles y reporte de exposición.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 86. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar la clasificación de campos de almacenamiento y metadatos de acceso. La práctica es: Resumir campos sensibles, roles autorizados y atributos de trazabilidad en un conjunto ficticio. La evidencia que debo producir es: Matriz de campos/roles y reporte de exposición. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 86](evaluaciones.md#evaluación-día-86).

---

# Día 87 — Calidad, precios y trazabilidad

**Objetivo de aprendizaje:** Analizar calidad, precios y trazabilidad.

**Teoría y recurso:** Revisión de sesiones 31–34 y 72–75.

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Reconciliar observaciones sintéticas, cambios de precio y linaje.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Analizar calidad, precios y trazabilidad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Reconciliar observaciones sintéticas, cambios de precio y linaje.
- Puedes justificar la evidencia que guardas y qué demuestra: Reporte analítico reproducible.

**Evidencia verificable:** Reporte analítico reproducible.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 87. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Analizar calidad, precios y trazabilidad. La práctica es: Reconciliar observaciones sintéticas, cambios de precio y linaje. La evidencia que debo producir es: Reporte analítico reproducible. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 87](evaluaciones.md#evaluación-día-87).

---

# Día 88 — Elaborar reporte de riesgos y recomendaciones

**Objetivo de aprendizaje:** Elaborar reporte de riesgos y recomendaciones.

**Teoría y recurso:** [NIST SP 800-30 Rev. 1](https://csrc.nist.gov/pubs/sp/800/30/r1/final)

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Priorizar riesgos y vincular cada recomendación con evidencia y responsable propuesto.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Elaborar reporte de riesgos y recomendaciones.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Priorizar riesgos y vincular cada recomendación con evidencia y responsable propuesto.
- Puedes justificar la evidencia que guardas y qué demuestra: Informe ejecutivo de riesgos.

**Evidencia verificable:** Informe ejecutivo de riesgos.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 88. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Elaborar reporte de riesgos y recomendaciones. La práctica es: Priorizar riesgos y vincular cada recomendación con evidencia y responsable propuesto. La evidencia que debo producir es: Informe ejecutivo de riesgos. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 88](evaluaciones.md#evaluación-día-88).

---

# Día 89 — Auditar repositorio y reproducibilidad

**Objetivo de aprendizaje:** Auditar repositorio y reproducibilidad.

**Teoría y recurso:** [GitHub: secure repository](https://docs.github.com/en/code-security)

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Verificar documentación, dependencias, secretos, pruebas y pasos de reproducción.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Auditar repositorio y reproducibilidad.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Verificar documentación, dependencias, secretos, pruebas y pasos de reproducción.
- Puedes justificar la evidencia que guardas y qué demuestra: Checklist de auditoría y lista de brechas.

**Evidencia verificable:** Checklist de auditoría y lista de brechas.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 89. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Auditar repositorio y reproducibilidad. La práctica es: Verificar documentación, dependencias, secretos, pruebas y pasos de reproducción. La evidencia que debo producir es: Checklist de auditoría y lista de brechas. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 89](evaluaciones.md#evaluación-día-89).

---

# Día 90 — Evaluación final y retrospectiva

**Objetivo de aprendizaje:** Presentar evaluación final y retrospectiva.

**Teoría y recurso:** Revisión de todas las fuentes relevantes.

**Herramientas:** VS Code/editor Markdown + Git y GitHub; LibreOffice Calc para tablas cuando corresponda

**Práctica guiada (35 min):**

Explicar arquitectura, controles, métricas, riesgos y límites ante preguntas nuevas.

**Ejercicio individual (15 min):**

Repite el procedimiento con un segundo ejemplo o registro sintético distinto. No copies el primer resultado: documenta qué cambiaste, qué resultado esperabas y qué comprobaste. Si la práctica no permite crear un segundo caso, explica el mismo procedimiento con tus propias palabras y señala una limitación.

**Criterios de dominio:**

- Puedes explicar con tus palabras el objetivo: Presentar evaluación final y retrospectiva.
- Puedes ejecutar o describir la práctica sin omitir sus pasos principales: Explicar arquitectura, controles, métricas, riesgos y límites ante preguntas nuevas.
- Puedes justificar la evidencia que guardas y qué demuestra: Paquete final, evaluación y plan de mejora.

**Evidencia verificable:** Paquete final, evaluación y plan de mejora.

## Evaluación interactiva

Copia este prompt en un chat de IA:

> Actúa como mi tutor técnico para el Día 90. Evalúame de forma interactiva y espera mi respuesta antes de hacer la siguiente pregunta. El objetivo es: Presentar evaluación final y retrospectiva. La práctica es: Explicar arquitectura, controles, métricas, riesgos y límites ante preguntas nuevas. La evidencia que debo producir es: Paquete final, evaluación y plan de mejora. Haz lo siguiente: (1) formula tres preguntas distintas que comprueben los conceptos y decisiones concretas de este objetivo; (2) plantea un caso nuevo, con datos sintéticos, en el que deba aplicar la práctica; (3) pídeme que explique cómo comprobaría que mi evidencia es correcta y qué limitaciones tiene. No reveles las respuestas antes de que responda. Al final, califica de 1 a 10 usando estos criterios: comprensión del objetivo, aplicación correcta, justificación y calidad de la evidencia. Indica aciertos, errores concretos y qué debo repasar. No inventes herramientas ni requisitos que no aparecen en el plan de estudio.

**Registrar resultado:** [Evaluación del Día 90](evaluaciones.md#evaluación-día-90).

---
