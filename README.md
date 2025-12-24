# Análisis y Gestión del Riesgo (AGR)  
## Modelado de amenazas, metodologías de riesgo (CORAS, FAIR, Cornucopia), PIA y plan director

Repositorio con los entregables de la asignatura **Análisis y Gestión del Riesgo (AGR) – Ingeniería de la Ciberseguridad, URJC**.  
Recoge el desarrollo completo de un **caso práctico de análisis de riesgos** sobre una organización ficticia (ChaseMyCash), desde el contexto inicial hasta el **plan director de seguridad** y el **resumen ejecutivo**.

---

## Estructura del repositorio

```text
.
├── 01_Contexto/
│   ├── Caso practico - 2-1.pdf
│   └── Caso práctico 1 - AGR.pdf
├── 02_Metodologias/
│   ├── Modelado de amenazas.pdf
│   ├── CORAS.pdf
│   ├── Cornucopia.pdf
│   └── FAIR.pdf
├── 03_Gestion_y_Planes/
│   ├── PIA.pdf
│   ├── Plan director de seguridad.pdf
│   └── Plan de accion.pdf
├── Resumen Ejecutivo.pdf
├── Resumen Ejecutivo-1.pdf
├── Resumen Ejecutivo-2.pdf
├── Comparacion.pdf
├── Programa de ciberseguridad.pdf
└── README.md
```

---

## 1. [Caso practico - 2-1.pdf](./01_Contexto/Caso practico - 2-1.pdf)

Documento base con el **escenario de partida**:

- Descripción de la organización (sector, servicios que ofrece, canales digitales).
- Activos principales: información de clientes, sistemas de pago, aplicaciones web, etc.
- Actores interesados (stakeholders) y su relación con el servicio.
- Problema a resolver: exposición a brechas de datos, interrupción del servicio, impacto económico y reputacional.

---

## 2. [Caso práctico 1 - AGR.pdf](./01_Contexto/Caso práctico 1 - AGR.pdf)

Documento “marco” que integra todos los entregables de la práctica:

- Identificación de **activos**, **amenazas**, **vulnerabilidades** e **impactos**.
- Clasificación de activos por criticidad (confidencialidad, integridad, disponibilidad).
- Identificación de escenarios de riesgo prioritarios (por ejemplo, brecha de datos de clientes, denegación de servicio, fuga de código fuente, etc.).
- Resumen de resultados de las distintas metodologías de análisis (CORAS, Cornucopia, FAIR, PIA…).

---

## 3. [Modelado de amenazas.pdf](./02_Metodologias/Modelado de amenazas.pdf)

- Definición del **alcance** (sistemas, aplicaciones, datos).
- Identificación de **activos** y **dependencias**.
- Posible uso de diagramas de flujo de datos (DFD) o diagramas de componentes.
- Formulación de escenarios de amenaza estructurados (actor → vía de ataque → activo afectado → impacto).

---

## 4. [CORAS.pdf](./02_Metodologias/CORAS.pdf) – Metodología CORAS

Aplicación de la metodología **CORAS** para análisis de riesgos:

- Diagrama de activos y de amenazas.
- Descripción de vulnerabilidades y eventos no deseados.
- Estimación de **probabilidad** e **impacto** para cada escenario.
- Evaluación del nivel de riesgo y priorización de aquellos que superan los umbrales definidos.

---

## 5. [Cornucopia.pdf](./02_Metodologias/Cornucopia.pdf) – OWASP Cornucopia

Documento basado en el uso de **OWASP Cornucopia**, un juego de cartas orientado a:

- Identificar amenazas sobre aplicaciones web (autenticación, sesión, validación de entrada, criptografía, etc.).
- Relacionar cada carta con controles o requisitos de seguridad.
- Detectar debilidades adicionales alrededor del flujo de pagos, gestión de usuarios o gestión de sesiones.

Cornucopia es especialmente útil para completar amenazas que no salen en un análisis puramente técnico y para involucrar a perfiles de desarrollo/negocio.

---

## 6. [FAIR.pdf](./02_Metodologias/FAIR.pdf) – Cuantificación de riesgos

Aplicación del marco **FAIR (Factor Analysis of Information Risk)**:

- Descomposición de uno o varios **escenarios de riesgo** (por ejemplo, brecha de datos de clientes, denegación de servicio).
- Estimación de:
  - frecuencia de eventos de amenaza,
  - probabilidad de éxito,
  - magnitud de la pérdida (Loss Magnitude), incluyendo impactos primarios y secundarios.
- Obtención de **rangos de pérdida esperada** y comparación entre escenarios para priorizar.

FAIR aporta una visión **más cuantitativa**, útil para comunicar riesgo a negocio y dirección (coste esperado, orden de prioridades).

---

## 7. [Comparacion.pdf](./Comparacion.pdf) – Comparativa de metodologías

Documento de **comparación entre CORAS, Cornucopia y FAIR**:

- Ventajas y limitaciones de cada enfoque.
- Casos de uso en los que cada metodología encaja mejor:
  - CORAS → modelado gráfico y workshops.
  - Cornucopia → aplicaciones web y participación de equipos de desarrollo.
  - FAIR → análisis económico y priorización a alto nivel.
- Conclusiones sobre el uso combinado de varias metodologías para obtener una visión más completa.

---

## 8. [PIA.pdf](./03_Gestion_y_Planes/PIA.pdf) – Evaluación de impacto en privacidad

**Privacy Impact Assessment** aplicado al caso práctico:

- Identificación de datos personales tratados (datos de clientes, transacciones, etc.).
- Análisis de riesgos específicos sobre la **privacidad** (brechas de confidencialidad, usos no autorizados, retención excesiva).
- Revisión de principios (minimización de datos, limitación de propósito, conservación, etc.).
- Propuesta de medidas de mitigación ligadas a cumplimiento normativo (GDPR / LOPDGDD).

Este documento complementa el análisis de ciber-riesgo con una perspectiva orientada a **protección de datos personales**.

---

## 9. Plan director de seguridad y programa de ciberseguridad

### [Plan director de seguridad.pdf](./03_Gestion_y_Planes/Plan director de seguridad.pdf)

Define las **líneas estratégicas** de seguridad de la organización:

- Objetivos de seguridad alineados con negocio.
- Principios rectores (gobierno, cumplimiento, gestión de identidades, protección de datos, continuidad, etc.).
- Roadmap de alto nivel: qué áreas se deben fortalecer y en qué orden.

### [Programa de ciberseguridad.pdf](./Programa de ciberseguridad.pdf)

- Iniciativas concretas (proyectos de hardening, monitorización, formación, gestión de vulnerabilidades, etc.).
- Políticas de seguridad relevantes.
- Recursos humanos y roles implicados.
- Integración con el resto de procesos corporativos.

---

## 10. [Plan de accion.pdf](./03_Gestion_y_Planes/Plan de accion.pdf)

Documento operativo que resume:

- Controles/medidas a implantar o reforzar.
- Riesgos a los que responde cada medida.
- Prioridad (alta/media/baja) o horizonte temporal.
- Responsables y dependencias.

---

## 11. Resúmenes ejecutivos

Se incluyen varias versiones de **Resumen Ejecutivo**:

- [Resumen Ejecutivo.pdf](./Resumen Ejecutivo.pdf)
- [Resumen Ejecutivo-1.pdf](./Resumen Ejecutivo-1.pdf)
- [Resumen Ejecutivo-2.pdf](./Resumen Ejecutivo-2.pdf)
