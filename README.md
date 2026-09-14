# Implementación de Infraestructura de Contenedores en Proyectos Java

El equipo de desarrollo de backend necesita implementar una infraestructura de contenedores robusta y escalable para sus proyectos Java. La solución debe considerar las diferencias, ventajas y desventajas de usar Docker y Kubernetes, y debe ser capaz de manejar la contenerización y orquestación de contenedores en un ambiente distribuido.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Implementa Plataformas de Contenedores enfocados en Docker y Kubernetes |
| **Nivel** | advanced-l3 |
| **Tipo** | mixed |
| **Tiempo estimado** | 8-10 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Exploración y Selección de Herramientas

**Objetivo:** Identificar las herramientas de contenerización y orquestación más adecuadas para el proyecto.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Investiga y compara las características, ventajas y desventajas de Docker, Docker Compose, Docker Swarm y Kubernetes.
- Evalúa las necesidades del proyecto y selecciona las herramientas que mejor se ajusten.

**Entregable:** Documento que detalle las herramientas seleccionadas y la justificación de la elección.

<details>
<summary>Pistas de conocimiento</summary>

- Considera la escalabilidad, la facilidad de uso y la integración con otros servicios al evaluar las herramientas.
- Piensa en cómo las herramientas seleccionadas pueden mejorar la eficiencia y la gestión de los contenedores.

</details>

### Fase 2: Configuración y Despliegue de Contenedores

**Objetivo:** Configurar y desplegar contenedores utilizando las herramientas seleccionadas.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Crea un Dockerfile para tu aplicación Java.
- Configura Docker Compose para orquestar tus contenedores.
- Despliega tus contenedores en un entorno de desarrollo.

**Entregable:** Contenedores funcionando en un entorno de desarrollo.

<details>
<summary>Pistas de conocimiento</summary>

- Asegúrate de que tu Dockerfile incluya todas las dependencias necesarias para tu aplicación.
- Utiliza Docker Compose para definir y ejecutar tus servicios en contenedores.

</details>

### Fase 3: Orquestación y Gestión de Contenedores

**Objetivo:** Configurar y gestionar la orquestación de contenedores utilizando Kubernetes.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Configura un clúster de Kubernetes.
- Despliega tus aplicaciones en Kubernetes.
- Gestiona y escala tus contenedores en el clúster.

**Entregable:** Aplicaciones desplegadas y gestionadas en un clúster de Kubernetes.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza los manifests de Kubernetes para definir y desplegar tus aplicaciones.
- Aprovecha las capacidades de escalado y gestión de Kubernetes para optimizar tus contenedores.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es Docker y cómo difiere de Kubernetes?
- **paraQueSirve**: ¿Para qué sirve Docker Compose en la orquestación de contenedores?
- **comoSeUsa**: ¿Cómo se usa Kubernetes para gestionar contenedores en un ambiente distribuido?
- **erroresComunes**: ¿Cuáles son los errores comunes al desplegar contenedores con Docker y Kubernetes?
- **queDecisionesImplica**: ¿Qué decisiones implica la elección de Docker frente a Kubernetes para un proyecto específico?

## Criterios de Evaluacion

- Seleccionar las herramientas de contenerización y orquestación más adecuadas para el proyecto.
- Configurar y desplegar contenedores utilizando Docker y Docker Compose.
- Configurar y gestionar la orquestación de contenedores utilizando Kubernetes.

## Como trabajar con un asistente de IA

- **AGENTS.md** — instrucciones nativas del repo (Cursor, Codex, Copilot, Gemini, Claude Code). Abrí el proyecto y el agente las carga solo.
- **PROMPT_MEJORA.md** — el mismo prompt, para copiar y pegar en un chat (claude.ai, ChatGPT, etc.).

---

*Reto generado automaticamente por Challenge Generator - Pragma*
