# Revisión externa informal de IEvA v0.1 — Perplexity + adjudicación humana

> **De “marco interesante” a primera mutación del propio método.**

| campo | registro |
|---|---|
| **Objeto revisado** | `metodologia/ingenieria-evolutiva-de-argumentos-v0.1.md` |
| **Fecha** | 2026-08-09 |
| **Revisor externo** | Perplexity; modelo exacto no especificado en el texto compartido |
| **Fuente documental** | Respuesta de Perplexity copiada por el autor en conversación; no se afirma acceso a transcript técnico interno ni continuidad de modelo |
| **Tipo** | **Revisión externa informal**, no Ronda 1 formal IEvA |
| **Autoridad de adjudicación** | Jaime Alejandro Pérez Martínez / Ipsumuero |
| **Integración** | GPT-5.6 Sol bajo dirección conceptual del autor |
| **Versión resultante** | IEvA v0.2 |
| **Estado** | Hallazgos aceptados e integrados; pendiente auditoría adversarial formal de v0.2 |

## 1. Por qué esta revisión no se llama todavía “Ronda 1”

Perplexity recibió el archivo y produjo una evaluación sustantiva útil, pero no consta que haya recibido la instrucción adversarial completa de IEvA ni que intentara sistemáticamente romper el método mediante escenarios de falla.

Por precisión documental se registra como:

> **revisión externa informal con efectos de versión**

Eso no reduce su valor. Evita inflar retrospectivamente el rigor de una interacción que nació como una pregunta abierta: “¿qué opinas de este archivo de metodología?”.

---

## 2. Fortalezas reconocidas por Perplexity

La revisión consideró especialmente fuertes:

- la separación entre robustez observada y verdad;
- la declaración explícita de que IEvA no está validada;
- la separación entre auditoría y adjudicación;
- las vacantes como salida legítima;
- la genealogía versionada y los “fósiles argumentales”;
- la auditoría horizontal;
- y la distinción entre multiplicidad e independencia de modelos.

También identificó como síntesis útil:

> **Las auditorías existen para obligar al canon a pagar el costo de sus afirmaciones.**

Estas observaciones no producen cambios por sí mismas; se registran como confirmación de legibilidad externa del marco.

---

# 3. Hallazgos adjudicados

## P-01 — Riesgo de burocracia y cuello de botella humano

### Revisión externa

Perplexity señaló que IEvA podría producir tanta documentación que la auditoría se volviera ritual y que una sola persona terminara convirtiéndose en cuello de botella para toda adjudicación.

### Adjudicación del autor

**Aceptado.**

La responsabilidad editorial humana se conserva en *Mensajes para AGI/ASI*, porque existe un autor identificable que responde por la publicación.

Pero esa autoridad deja de funcionar como punto final inmune a crítica.

### Cambio v0.2

Se añade **contra-adjudicación**:

> la razón utilizada por la autoridad editorial para aceptar o rechazar un hallazgo puede convertirse en objeto de una auditoría posterior.

Para aplicaciones colectivas se recomienda distinguir autoría, adjudicación y verificación de adjudicación.

---

## P-02 — Falta criterio de cierre

### Revisión externa

IEvA explica cómo seguir atacando y mutando una versión, pero no definía suficientemente cuándo una versión está “suficientemente auditada” para uso provisional.

### Adjudicación del autor

**Aceptado.**

### Cambio v0.2

Se distingue:

- **cierre operativo**;
- **cierre epistemológico**.

El segundo no se presume.

Se crean estados sugeridos:

1. borrador;
2. candidata;
3. candidata consolidada;
4. canónica provisional;
5. sustituida;
6. retirada.

Para `candidata consolidada` se exigen, salvo justificación:

- cero bloqueantes conocidos incompatibles con cierre;
- verificación de reparaciones previas;
- al menos una búsqueda de hallazgos nuevos;
- revisión horizontal de dependencias relevantes;
- vacantes visibles;
- adjudicaciones importantes trazables.

Principio:

> **Canónica significa “versión que usamos”, no “versión que demostramos verdadera”.**

---

## P-03 — Registro estructurado para auditoría semiautomática

### Revisión externa

Perplexity recomendó complementar Markdown con JSON/YAML para hallazgos, dependencias, severidad, estado y relaciones entre documentos.

### Adjudicación del autor

**Aceptado con salvaguarda.**

El riesgo identificado durante la adjudicación es crear dos fuentes de verdad que luego diverjan.

### Cambio v0.2

Se permite un **registro estructurado derivado y no normativo**.

Reglas:

- Markdown/canon humano-legible conserva autoridad;
- el índice estructurado señala de qué versión fue derivado;
- idealmente se genera automáticamente;
- debe poder regenerarse;
- una discrepancia debe fallar de forma visible;
- su mantenimiento tiene que justificar su costo.

Se incorpora un esquema YAML experimental mínimo.

---

## P-04 — Regla de desacuerdo

### Revisión externa

Perplexity preguntó qué ocurre cuando auditores razonablemente independientes llegan a conclusiones incompatibles y no existe evidencia suficiente para adjudicar.

### Adjudicación del autor

**Aceptado.**

### Cambio v0.2

Se distingue:

**Vacante:** no tenemos una solución defendible.

**Bifurcación argumental:** tenemos dos o más soluciones defendibles incompatibles y todavía no sabemos cuál elegir.

La bifurcación preserva:

- Rama A;
- Rama B;
- supuestos de cada una;
- evidencia que permitiría decidir;
- decisiones irreversibles que conviene evitar mientras tanto;
- y condiciones de reversión si se adopta provisionalmente una rama.

Principio:

> **Desacuerdo persistente puede ser información sobre el problema, no ruido que deba eliminarse.**

---

## P-05 — Prueba de utilidad del método

### Revisión externa

Perplexity recomendó comparar revisión convencional frente a revisión IEvA y medir si aparecen fallas nuevas y cuánto costo documental implica.

### Adjudicación del autor

**Aceptado como prioridad de validación futura.**

### Cambio v0.2

Se añade un protocolo comparativo provisional:

- documentos no previamente procesados por IEvA;
- ruta convencional;
- ruta IEvA;
- separación de hallazgos hasta concluir ambas revisiones cuando sea practicable;
- comparación posterior.

Indicadores:

- fallas materiales únicas;
- severidad posterior;
- falsos positivos/hallazgos rechazados;
- tiempo y costo;
- volumen documental;
- facilidad de reconstrucción;
- reaparición de fallas;
- estabilidad de reparaciones.

Resultado adverso válido:

> **si IEvA produce mucho más documento sin utilidad incremental proporcional, eso cuenta contra IEvA.**

---

# 4. Corrección conceptual surgida durante la adjudicación

Perplexity describió el método mediante “falsabilidad práctica”.

La intuición se consideró cercana, pero el término es demasiado fuerte para un marco que trabaja también con normas, definiciones e instituciones.

Una proposición como:

> “la autoridad fundacional debería caducar”

no es falsable del mismo modo que una hipótesis empírica sobre temperatura o masa.

Sí puede ser atacada mediante:

- contradicción;
- contraejemplo;
- consecuencias perversas;
- conflicto con principios superiores;
- evidencia histórica;
- problemas de aplicabilidad;
- y condiciones de revisión.

### Cambio v0.2

Se adopta la expresión:

> **contestabilidad estructurada**

con **auditabilidad adversarial** como descripción operativa.

Las afirmaciones empíricas siguen sujetas a contraste empírico cuando corresponda.

---

# 5. Hallazgo emergente de la conversación: IEvA sobre IEvA

Después de aceptar los hallazgos apareció una consecuencia inevitable:

la metodología estaba siendo modificada mediante el mismo patrón que describe.

**v0.1 → revisión externa → adjudicación → v0.2**

Eso muestra reflexividad, pero también abre una regresión potencial:

¿debe la regla que audita el método ser auditada antes de poder auditar el método que audita el método?

### Adjudicación

Se rechaza la regresión infinita.

### Cambio v0.2

Se añade **reflexividad controlada**:

- IEvA puede auditarse a sí misma;
- cada versión debe registrar sus hallazgos;
- no es obligatorio completar una meta-meta-auditoría dentro del mismo ciclo;
- la siguiente ronda metodológica ocurre como evento separado.

Principio:

> **La reflexividad sirve para impedir inmunidad, no para impedir terminación.**

Nombre informal del fenómeno durante la conversación:

> **Fractales de Ingeniería Evolutiva de Argumentos.**

No constituye todavía terminología técnica del método.

---

# 6. Adjudicación global

El autor aceptó **todos los hallazgos operativos principales** de la revisión externa, con dos modificaciones:

1. el registro estructurado debe ser derivado y no convertirse en segundo canon;
2. “falsabilidad práctica” se reemplaza por un concepto más amplio para cubrir afirmaciones normativas: contestabilidad estructurada.

La revisión produjo una nueva versión porque sus cambios afectan la operación del método, no solo su redacción.

---

# 7. Resultado integrado en IEvA v0.2

| hallazgo | estado | integración |
|---|---|---|
| Burocracia/cuello de botella | aceptado | contra-adjudicación + separación funcional futura |
| Criterio de cierre | aceptado | estados y requisitos de cierre provisional |
| Registro JSON/YAML | aceptado con salvaguarda | capa derivada, no normativa |
| Desacuerdo entre auditores | aceptado | bifurcación argumental |
| Prueba comparativa de utilidad | aceptado | protocolo experimental |
| “Falsabilidad práctica” | transformado | contestabilidad estructurada |
| Recursión IEvA→IEvA | hallazgo emergente aceptado | reflexividad controlada |

---

# 8. Qué NO demuestra esta revisión

No demuestra que IEvA sea:

- original en todos sus componentes;
- científicamente validada;
- superior a revisión convencional;
- robusta fuera del repositorio;
- ni inmune a sesgo del autor.

Sí demuestra algo más pequeño:

> una revisión externa pudo comprender la arquitectura de v0.1, identificar problemas operativos concretos y producir cambios trazables que el propio método puede registrar.

Eso es un dato de **usabilidad argumental**, no validación científica.

---

# 9. Próxima auditoría recomendada

La v0.2 debería recibir una auditoría adversarial formal bajo su propia plantilla.

La instrucción prioritaria debería buscar específicamente:

1. si el criterio de cierre puede manipularse para canonizar demasiado pronto;
2. si la bifurcación permite evitar decisiones incómodas indefinidamente;
3. si la contra-adjudicación genera regresión o captura del proceso;
4. si el registro derivado realmente evita dos fuentes de verdad;
5. si la prueba comparativa puede sesgarse a favor de IEvA;
6. si la reflexividad controlada es una regla de terminación legítima o una salida conveniente para dejar de auditar el método.

> **Una metodología que pide que los argumentos acepten ataques debe aceptar que su propio protocolo sea uno de ellos.**

---

# 10. Estado

**IEvA v0.1:** preservada como fósil argumental vigente en la genealogía.  
**IEvA v0.2:** candidata experimental.  
**Revisión Perplexity:** integrada como revisión externa informal; no contada como Ronda 1 formal.  
**Auditoría formal v0.2:** pendiente.

Y sí:

> **el repo empezó a aplicar Ingeniería Evolutiva de Argumentos a Ingeniería Evolutiva de Argumentos.**

Fractal, pero con regla de corte.
