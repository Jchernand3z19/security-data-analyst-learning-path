# Guía de Estudio — Días 01 al 03

# Día 01 — Cliente, Servidor y Ciclo HTTP

**🎯 Objetivo:** Comprender cómo se comunican un cliente y un servidor mediante HTTP, e identificar el método, el código de estado y el tipo de contenido de una respuesta.

**📚 Teoría:**
- [MDN — Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [MDN — HTTP Messages](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)
- [MDN — HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

**🛠️ Práctica Guiada:**

1. Abre Google Chrome o Firefox y visita `https://example.com`.
2. Presiona `F12) para abrir DevTools y selecciona la pestaña **Network**.
3. En los filtros de tipo de recurso, selecciona **Doc**. Esto reduce el ruido de solicitudes de imágenes, hojas de estilo y scripts, y permite concentrarse en el documento principal.
4. Recarga la página. Si la lista está vacía, confirma que Network estaba abierto antes de recargar.
5. Selecciona la solicitud cuyo nombre o URL corresponde a `example.com` y que representa el documento principal.
6. Abre **Headers** e identifica:
   - **Request Method:** debería aparecer `GET`.
   - **Status Code:** comprueba el código recibido; para una respuesta exitosa se espera `200 OK`.
   - **Response Headers → Content-Type:** identifica el tipo de contenido devuelto; normalmente será un tipo HTML, como `text/html`.
7. Registra el método, el estado y el valor de Content-Type. No confundas los encabezados de la solicitud (**Request Headers**) con los de la respuesta (**Response Headers**).
8. Explica qué hizo el navegador, qué recibió del servidor y cómo sabes que la respuesta fue exitosa.

**💡 Conceptos Clave:**
- **Cliente:** aplicación o dispositivo que inicia una solicitud; por ejemplo, un navegador.
- **Servidor:** sistema que recibe solicitudes y devuelve respuestas.
- **HTTP:** protocolo utilizado para intercambiar solicitudes y respuestas entre clientes y servidores.
- **Código de estado:** número que comunica el resultado de una solicitud HTTP; por ejemplo, `200 OK` indica éxito.

## 🏁 Evaluación y Evidencia

**Paso 1: Copia este prompt en un Chat de IA (ChatGPT/Claude):**

> Actúa como mi Tutor Técnico. Estoy en el Día 01 (Cliente, Servidor y Ciclo HTTP). Evalúame interactivamente:
> 1. Hazme 3 preguntas sobre los conceptos clave.
> 2. Plantea un escenario práctico: pídeme que invente una solicitud GET a la ruta `/perfil` y que explique qué código de estado esperaría si el servidor procesa correctamente la solicitud (`200 OK`).
> 3. Pídeme que describa el proceso de Cliente, Servidor y Ciclo HTTP paso a paso.
> Espera mis respuestas antes de avanzar. Al terminar, dame una nota del 1 al 10 y genera un bloque de código Markdown con el resumen de mi evaluación y feedback.

**Paso 2: Guarda tu evidencia en GitHub:**

Haz clic en este enlace para crear tu archivo de evidencia:

👉 **[Crear archivo `dia-01-evaluacion.md`](https://github.com/Jchernand3z19/security-data-analyst-learning-path/new/main/dia-01-evaluacion.md)**

*(Pega el resumen de la IA y haz clic en "Commit changes").*

---

# Día 02 — Modelo OSI y TCP/IP

**🎯 Objetivo:** Comprender cómo se organiza la comunicación de red mediante los modelos OSI y TCP/IP, y observar la conectividad y los saltos de red utilizando herramientas de terminal.

**📚 Teoría:**
- [Cloudflare — What is the OSI Model?](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
- [Cloudflare — What is TCP/IP?](https://www.cloudflare.com/learning/network-layer/what-is-the-tcp-ip-model/)
- [Microsoft — ping](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ping)
- [Microsoft — tracert](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/tracert)

**🛠️ Práctica Guiada:**

1. Abre CMD o PowerShell en Windows, o Terminal en Mac.
2. Ejecuta `ping google.com`.
3. Observa si el nombre se resuelve a una dirección IP y registra la IP que aparece.
4. Revisa si recibes respuestas, el tiempo aproximado de respuesta y si existe pérdida de paquetes. Si no hay respuesta, no concluyas automáticamente que Google está desconectado: algunas redes o equipos bloquean ICMP.
5. Detén el comando con `Ctrl + C) si continúa ejecutándose.
6. Para observar los saltos de red, ejecuta:
   - Windows: `tracert google.com`.
   - Mac: `traceroute google.com`.
7. Analiza la salida sin intentar identificar cada dispositivo. Concéntrate en el número de saltos, las IP visibles y los tiempos de respuesta.
8. Si aparecen asteriscos (`*`), registra que ese salto no respondió dentro del tiempo de espera. Esto no demuestra por sí solo que exista una interrupción: algunos dispositivos no responden a estas sondas.
9. Relaciona los resultados con el modelo OSI: considera la capa de red para el direccionamiento y enrutamiento, y las capas inferiores para la transmisión de datos.
10. Registra la IP observada, el resultado de ping y algunos saltos de traceroute/tracert. Explica qué información aporta cada comando y qué limitaciones tiene.

**💡 Conceptos Clave:**
- **Modelo OSI:** modelo de referencia de siete capas que organiza las funciones de comunicación de red.
- **Modelo TCP/IP:** conjunto de capas y protocolos que sustenta la comunicación en Internet.
- **ICMP:** protocolo de control y diagnóstico utilizado, entre otras funciones, por herramientas como ping.
- **Traceroute/Tracert:** herramienta que permite observar los saltos intermedios del recorrido hacia un destino de red.

## 🏁 Evaluación y Evidencia

**Paso 1: Copia este prompt en un Chat de IA (ChatGPT/Claude):**

> Actúa como mi Tutor Técnico. Estoy en el Día 02 (Modelo OSI y TCP/IP). Evalúame interactivamente:
> 1. Hazme 3 preguntas sobre los conceptos clave.
> 2. Plantea un escenario práctico: una página web carga, pero sus imágenes no aparecen. Pídeme que identifique qué capas del modelo OSI o componentes de comunicación podrían estar involucrados y qué comprobaría para investigar el problema.
> 3. Pídeme que describa el proceso de Modelo OSI y TCP/IP paso a paso y explique qué información aportan ping y tracert/traceroute.
> Espera mis respuestas antes de avanzar. Al terminar, dame una nota del 1 al 10 y genera un bloque de código Markdown con el resumen de mi evaluación y feedback.

**Paso 2: Guarda tu evidencia en GitHub:**

Haz clic en este enlace para crear tu archivo de evidencia:

👉 **[Crear archivo `dia-02-evaluacion.md`](https://github.com/Jchernand3z19/security-data-analyst-learning-path/new/main/dia-02-evaluacion.md)**

*(Pega el resumen de la IA y haz clic en "Commit changes").*

---

# Día 03 — DNS y Resolución de Nombres

**🎯 Objetivo:** Comprender cómo DNS relaciona los nombres de dominio con direcciones IP y utilizar `nslookup` para identificar el servidor DNS que responde y la dirección resuelta para un dominio.

**📚 Teoría:**
- [Cloudflare — What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [Cloudflare — DNS Records](https://www.cloudflare.com/learning/dns/dns-records/)
- [Microsoft — nslookup](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/nslookup)

**🛠️ Práctica Guiada:**

1. Abre CMD o PowerShell en Windows, o Terminal en Mac.
2. Ejecuta `nslookup google.com`.
3. En la salida, localiza **Server** y **Address** que aparecen al principio. Identifican el servidor DNS consultado y su dirección, respectivamente.
4. Busca la sección de respuesta. Identifica el nombre consultado y la dirección o direcciones IP que DNS devuelve para Google.
5. Distingue la IP del servidor DNS de la IP resuelta para `google.com`: son datos diferentes y cumplen funciones distintas.
6. Ejecuta `nslookup -type=A google.com` para consultar específicamente registros A.
7. Registra el servidor DNS, su IP y las direcciones IPv4 devueltas. Puede haber más de una dirección y los resultados pueden variar según la ubicación y el momento.
8. Explica por qué DNS se compara con una agenda telefónica de Internet: permite utilizar nombres fáciles de recordar en lugar de tener que memorizar direcciones IP.
9. Investiga el significado del error `ERR_NAME_NOT_RESOLVED`: relaciona el mensaje con un fallo al resolver el nombre, sin asumir una causa única.

**💡 Conceptos Clave:**
- **DNS (Domain Name System):** sistema que permite obtener información asociada a nombres de dominio, como direcciones IP.
- **Servidor DNS:** servidor que recibe consultas DNS y devuelve respuestas sobre nombres de dominio.
- **Registro A:** registro DNS que asocia un nombre con una dirección IPv4.
- **Resolución DNS:** proceso de consulta mediante el cual se obtiene información correspondiente a un nombre de dominio.

## 🏁 Evaluación y Evidencia

**Paso 1: Copia este prompt en un Chat de IA (ChatGPT/Claude):**

> Actúa como mi Tutor Técnico. Estoy en el Día 03 (DNS y Resolución de Nombres). Evalúame interactivamente:
> 1. Hazme 3 preguntas sobre los conceptos clave.
> 2. Plantea un escenario práctico: un navegador muestra el error `ERR_NAME_NOT_RESOLVED`. Pídeme que explique qué significa, qué podría estar fallando y cómo utilizaría `nslookup` para investigar. Pregúntame también qué tipo de registro DNS se utiliza para asociar un dominio con una dirección IPv4 (registro A).
> 3. Pídeme que describa el proceso de DNS y Resolución de Nombres paso a paso.
> Espera mis respuestas antes de avanzar. Al terminar, dame una nota del 1 al 10 y genera un bloque de código Markdown con el resumen de mi evaluación y feedback.

**Paso 2: Guarda tu evidencia en GitHub:**

Haz clic en este enlace para crear tu archivo de evidencia:

👉 **[Crear archivo `dia-03-evaluacion.md`](https://github.com/Jchernand3z19/security-data-analyst-learning-path/new/main/dia-03-evaluacion.md)**

*(Pega el resumen de la IA y haz clic en "Commit changes").*

---
