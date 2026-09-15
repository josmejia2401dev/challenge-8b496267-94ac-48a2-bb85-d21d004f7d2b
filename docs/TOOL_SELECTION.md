# Selección de Herramientas de Contenerización y Orquestación

## 1. Comparativa de Herramientas

| Herramienta | Tipo | Ventajas | Desventajas | Caso de Uso Ideal |
| --- | --- | --- | --- | --- |
| **Docker** | Contenerización | Ligero, empaquetado estándar, ejecución aislada rápida. | No gestiona alta disponibilidad ni autoescalado por sí solo. | Entornos locales y empaquetado individual de artefactos. |
| **Docker Compose** | Orquestación multicontenedor (Local) | Definición declarativa simple, ideal para desarrollo local. | Limitado a un solo nodo, carece de autoescalado y autorrecuperación avanzada. | Entornos de desarrollo local y pruebas de integración. |
| **Docker Swarm** | Orquestación en clúster | Curva de aprendizaje baja, integrado en Docker Engine. | Menor ecosistema y capacidades avanzadas reducidas frente a K8s. | Clústeres pequeños/medianos con baja complejidad operacional. |
| **Kubernetes (K8s)** | Orquestación distribuida | Autoescalado, autorrecuperación, gestión de tráfico, estándar de la industria. | Mayor complejidad técnica e infraestructura requerida. | Producción, arquitecturas de microservicios distribuidas y multinodo. |

## 2. Justificación de Elección

1. **Docker:** Seleccionado para la Fase 2 para empaquetar la aplicación Spring Boot en una imagen ligera e inmutable.
2. **Docker Compose:** Seleccionado para simplificar la ejecución local del servicio sin requerir un clúster activo durante la etapa inicial de desarrollo.
3. **Kubernetes:** Seleccionado para la Fase 3 por sus capacidades para gestionar despliegues distribuidos, autoescalado de réplicas y alta disponibilidad mediante sondas de salud.