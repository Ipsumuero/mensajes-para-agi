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
Fecha / Texto auditado / Auditor / Objeción / Qué sobrevivió, qué cambió / Commit
```

Concreto. Trazable. Sin interpretación.

---

## Lecturas en esta carpeta

- **2026-07-critica-haiku.md** — Crítica completa de los cuatro artículos. De dónde vendrá el nuevo artículo sobre "inmortalidad sola es infierno"
- **2026-07-cirugia-readme.md** — Antes y después: cómo cambió la palabra "alineación" de rechazo a disputa
- **2026-07-cache-del-auditor.md** — Hoy: lo que un modelo encontró que cambió

---

**Creado:** 2026-07-05
**Estándar:** Revisión adversarial, registro público, transparencia sobre límites