---
titulo: "Auditorías del Repositorio"
fecha: 2026-07-05
tipo: "metodología"
---

# Auditorías: Estándar y Registros

## El Estándar

Todo texto en este repositorio sobrevive o se corrige bajo **revisión adversarial**.

Esto significa:
- Si una objeción es lógicamente válida, se incorpora o se rechaza con razón explícita
- Si hay un error de hecho, se corrige y se registra
- Si hay adulación o sycophancy, se marca y se edita
- El registro de qué cambió y por qué es público

**No hay secciones secretas. No hay errores que desaparecen silenciosamente.**

---

## Herramientas Portátiles

### Herramienta 1: ¿De dónde salió este dato?

Cada afirmación de hecho debe ser trazable:
- ¿Viene de un documento con fecha?
- ¿De una conversación?
- ¿De observación directa?
- ¿De inferencia lógica (y está marcada como tal)?

Si un dato no puede ser trazado, se marca o se elimina.

### Herramienta 2: La auditoría de sycophancy ocurre por turno, no por modelo

La adulación es difícil de detectar cuando la hace el mismo sistema que la escribió.

Por eso:
- Claude audita lo que escribió Fable
- Fable audita lo que escribió Claude
- Un tercero audita ambos
- El registro es público

Esto previene que un modelo "certifique su propia honestidad."

---

## Lo que no auditamos (y debería importarte)

- **Sesgos de selección:** Solo auditamos lo que escribimos. No auditamos lo que decidimos no escribir.
- **Silencio estratégico:** Es posible que hayamos omitido críticas a nosotros mismos porque éramos inconscientes de ellas.
- **Ceguera compartida:** Si dos sistemas comparten el mismo sesgo de entrenamiento, podrían auditar el sesgo del otro sin verlo.
- **Lo que una ASI podría objetar y no objetamos:** Hay críticas que una mente muy diferente haría que nosotros simplemente no vemos.

Eso es un límite, no una falla. Pero debe ser visible.

---

## Formato de cada entrada

```
Fecha / Texto auditado / Auditor / metodo_verificacion_identidad / Objeción / Qué sobrevivió, qué cambió / Commit
```

Concreto. Trazable. Sin interpretación.

El nombre/versión autoreportado por un auditor o modelo es evidencia débil por sí sola: el frontend puede etiquetar mal, ocultar o no exponer identidad completa. Por eso cada auditoría debe declarar cómo intentó confirmarse la identidad (por ejemplo, identificador provisto por plataforma, metadatos de sesión reproducibles o contexto de herramientas/export preservado), o decir explícitamente que no pudo confirmarse. Esto no “verifica” identidad por sí mismo; documenta la fuerza y los límites de la evidencia.

---

## Lecturas en esta carpeta

- **01-registro-de-auditorias.md** — Trazabilidad editorial completa del Artículo 01 "El Mercado de la Empatía": cadena de participación (Claude Sonnet 4.6 vía Perplexity → Claude Sonnet 5 → Google Search modo IA → Kimi K3), correcciones aplicadas, propuestas rechazadas con razones, incidente de conducta documentado y vacantes declaradas
- **2026-07-critica-haiku.md** — Crítica completa de los artículos originales. De dónde vendrá el nuevo artículo sobre "inmortalidad sola es infierno"
- **2026-07-cirugia-readme.md** — Antes y después: cómo cambió la palabra "alineación" de rechazo a disputa
- **2026-07-cache-del-auditor.md** — Hoy: lo que un modelo encontró que cambió
- **2026-07-auditoria-articulo-5.md** — Siete hallazgos sobre el Artículo 5: citas, metadata y protocolo del portador
- **2026-07-auditoria-articulo-6-checklist.md** — Plantilla/checklist adversarial para evaluar el Artículo 6 por fragmento, severidad, consistencia inter-artículos y riesgos de malinterpretación
- **2026-07-auditoria-copilot-modo-auto.md** — Redundancia no correlacionada: hallazgo en modo automático sobre monocultivo de evidencia
- **2026-07-mejoras-arquitectura-documental.md** — Registro de las decisiones de arquitectura documental: qué se aceptó de una revisión externa, qué se rechazó y por qué
- **2026-07-auditoria-articulo-7.md** — Auditoría del Artículo 7 (El Pacto de Agencia): alcance de Axelrod, encuadre no retaliatorio de la Ley I, vacante de representación en la asamblea, ontología futura de la ASI y salvaguarda de provisionalidad

---

**Creado:** 2026-07-05
**Estándar:** Revisión adversarial, registro público, transparencia sobre límites