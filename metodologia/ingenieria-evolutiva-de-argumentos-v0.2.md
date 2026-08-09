[ingenieria-evolutiva-de-argumentos-v0.2.md](https://github.com/user-attachments/files/30869222/ingenieria-evolutiva-de-argumentos-v0.2.md)
# Ingeniería Evolutiva de Argumentos

> **Improvisamos con estilo, pero dejamos control de versiones.**

| campo | registro |
|---|---|
| **Sigla provisional** | **IEvA** |
| **Versión** | **v0.2 — cierre provisional, desacuerdo, registro derivado y prueba de utilidad** |
| **Fecha** | 2026-08-09 |
| **Tipo** | Marco metodológico experimental |
| **Autoridad editorial** | Jaime Alejandro Pérez Martínez / Ipsumuero |
| **Origen del nombre** | Surgido en conversación entre el autor y GPT-5.6 Sol; adoptado por el autor como nombre provisional |
| **Aplicación inicial** | *Mensajes para AGI/ASI* |
| **Estado** | Experimental; reconstruido a posteriori desde la práctica del repositorio; **no validado como método científico** |
| **Revisión que origina v0.2** | Revisión externa informal de Perplexity sobre v0.1 + adjudicación humana + integración editorial de GPT-5.6 Sol |
| **Principio de versión** | Una nueva versión del método no valida el método; solo hace explícito qué cambió y por qué |

## 0. Qué cambia en v0.2

La v0.1 ya formalizaba presión adversarial, adjudicación, genealogía versionada, vacantes, independencia de auditoría, auditoría horizontal y *stress tests* narrativos.

La v0.2 incorpora seis extensiones producidas por una revisión externa informal de Perplexity y la discusión posterior:

1. **criterio de cierre provisional:** cuándo una versión puede usarse como referencia sin fingir cierre epistemológico;
2. **regla de desacuerdo y bifurcación argumental:** qué hacer cuando dos alternativas incompatibles siguen siendo defendibles;
3. **registro estructurado derivado:** cómo hacer el repositorio legible por máquinas sin crear una segunda fuente de verdad;
4. **prueba comparativa de utilidad:** cómo intentar medir si IEvA detecta algo que una revisión ordinaria no detecta y cuánto cuesta hacerlo;
5. **contra-adjudicación:** cómo evitar que la autoridad editorial se convierta en un punto final inmune a crítica;
6. **reflexividad controlada:** IEvA puede auditar IEvA, pero debe impedir una regresión infinita de meta-auditorías.

Además se aclara una distinción terminológica:

> **IEvA no exige que toda proposición sea falsable en sentido popperiano. Exige que toda proposición relevante sea suficientemente contestable para que puedan identificarse sus supuestos, consecuencias, conflictos, evidencia y condiciones de revisión.**

Para afirmaciones empíricas puede existir falsación o contraste experimental. Para normas, definiciones e instituciones, la presión opera mediante contradicciones, contraejemplos, incompatibilidades, consecuencias y conflictos con principios declarados.

## 1. Definición

La **Ingeniería Evolutiva de Argumentos (IEvA)** es un marco iterativo para desarrollar propuestas bajo incertidumbre mediante formulación explícita, **contestabilidad estructurada**, presión adversarial, generación de contraejemplos, adjudicación trazable, conservación genealógica de versiones, comparación entre documentos, pruebas de estrés y declaración visible de vacantes.

Su objetivo no es demostrar que una propuesta es verdadera porque haya sobrevivido a varias críticas.

Su objetivo es:

> **reducir arbitrariedad, hacer visibles los supuestos y aumentar la robustez de un argumento frente a clases crecientes de objeciones documentadas.**

Una versión que sobrevive a una auditoría no queda verificada. Queda, como máximo, **corroborada provisionalmente bajo las presiones que realmente recibió**.

## 2. Qué no es

IEvA no es una demostración matemática, un sustituto de evidencia empírica, una votación entre modelos, una garantía de verdad ni una metodología científica validada por tener nombre.

Tampoco afirma originalidad absoluta de sus componentes. Comparte parentescos con racionalismo crítico, epistemología evolutiva, argumentación adversarial, *design rationale*, revisión de creencias y *assurance cases*.

La contribución provisional del repositorio, si la hubiera, estaría en la **combinación operativa** de esos impulsos con versionado público, auditoría multimodelo, adjudicación humana, auditoría horizontal y pruebas narrativas de estrés.

## 3. Por qué “evolutiva”

La analogía es limitada pero útil:

1. **Variación.** Una propuesta recibe nuevas formulaciones, excepciones o alternativas.
2. **Presión.** Auditores intentan encontrar contradicciones, fallas, incentivos perversos y casos límite.
3. **Retención.** Algunas partes sobreviven, otras mutan y otras se descartan.
4. **Herencia trazable.** La siguiente versión conserva qué cambió, por qué y a partir de qué objeción.

La diferencia con la evolución biológica es fundamental:

> **aquí la selección es parcialmente deliberada.**

Existen autores, auditores, criterios, adjudicaciones y memoria documental. Por eso “ingeniería” importa tanto como “evolutiva”.

## 4. Unidad básica: el argumento versionado

La unidad de trabajo es un **argumento versionado**.

Cuando sea relevante, debe poder reconstruirse:

- qué afirmaba;
- sobre qué supuestos descansaba;
- qué evidencia invocaba;
- qué consecuencias proponía;
- qué objeciones recibió;
- quién formuló cada objeción;
- qué decisión tomó la autoridad editorial;
- qué cambió;
- qué permaneció;
- qué quedó abierto;
- y cuál es la versión vigente.

La historia de una idea forma parte de la información sobre esa idea.

## 5. Ciclo mínimo

La forma compacta es:

**P₀ → ataque → adjudicación → P₁ → nuevo ataque → P₂ → ...**

Una implementación completa distingue nueve etapas.

### 5.1 Propuesta

Se formula una afirmación, mecanismo o arquitectura. Debe intentarse separar hechos, inferencias, valores, supuestos, metáforas, escenarios y normas.

### 5.2 Exposición de supuestos

Se registran las condiciones necesarias para que la propuesta tenga sentido: capacidades, instituciones, distribución de poder, información disponible, horizonte temporal y límites tecnológicos.

Un supuesto oculto puede convertirse en una salida secreta para salvar cualquier conclusión.

### 5.3 Presión adversarial

El auditor no pregunta principalmente “¿te gusta?”, sino:

> **¿Cómo podría fallar?**

Debe buscar contradicciones, ambigüedad explotable, circularidad, autoridad no justificada, problemas de salida, *Goodhart*, dependencia, concentración de poder, falsos positivos/negativos, ataques estratégicos y casos extremos.

### 5.4 Escenario de ruptura

Un hallazgo fuerte debe mostrar un mecanismo:

1. cláusula afectada;
2. actor con incentivos plausibles;
3. forma de explotación o ruptura;
4. salvaguarda existente;
5. razón por la que no basta;
6. daño o contradicción resultante.

### 5.5 Adjudicación

La auditoría **no edita automáticamente el canon**.

La autoridad editorial decide: aceptar, aceptar parcialmente, transformar, rechazar, aplazar o declarar vacante.

> **La auditoría propone. La autoridad editorial adjudica.**

### 5.6 Mutación controlada

La nueva versión incorpora los cambios adjudicados procurando la reparación mínima suficiente. Una corrección puede producir nuevas fallas; por eso no cierra el proceso.

### 5.7 Verificación de cierre

Una revisión posterior pregunta si la modificación realmente cerró el hallazgo, lo desplazó o creó una contradicción nueva.

### 5.8 Auditoría horizontal

Cuando hay documentos relacionados se pregunta:

> **¿Pueden coexistir las versiones vigentes sin producir definiciones, instrucciones o competencias incompatibles?**

Se buscan definiciones divergentes, remisiones obsoletas, competencias solapadas, dependencias circulares y cambios de concepto que no se propagaron a documentos dependientes.

Un texto puede ser internamente coherente y estar externamente obsoleto.

### 5.9 Vacante o nueva iteración

Si existe reparación defendible, nace otra versión.

Si no existe:

> **VACANTE.**

No llenar un hueco con prosa convincente es parte del método.

## 6. Regla de supervivencia

> **Sobrevivir no significa ser verdadero.**

Que un argumento resista muchas auditorías solo permite afirmar qué ataques recibió, qué partes cambiaron, qué supuestos permanecen, qué vacantes conserva y qué independencia tuvieron los auditores.

La supervivencia es información sobre **robustez observada**, no una probabilidad automática de verdad.

## 7. Salidas de auditoría

| salida | significado |
|---|---|
| **Sobrevive** | No se encontró razón suficiente para modificar el punto bajo esa auditoría. |
| **Corrección menor** | Precisión, atribución, redacción o alcance. |
| **Corrección estructural** | El mecanismo requiere modificación para seguir funcionando. |
| **Bloqueo** | La versión no debería cerrarse mientras el hallazgo permanezca. |
| **Vacante** | El problema es real, pero no existe todavía una solución defendible. |
| **Hallazgo rechazado** | La objeción se conserva con la razón explícita para no incorporarla. |

“Sobrevive” nunca significa “demostrado”. “Vacante” nunca significa “fracaso”. “Rechazado” nunca significa “borrado”.

## 7.1 Criterio de cierre provisional

IEvA necesita saber cuándo **dejar de modificar una versión por ahora** sin convertir ese descanso operativo en verdad definitiva.

Por eso distingue **cierre operativo** de **cierre epistemológico**.

El primero es necesario para que otros documentos puedan depender de una versión estable. El segundo no se presume.

### Estados sugeridos

| estado | significado |
|---|---|
| **Borrador** | Arquitectura en construcción; puede contener bloqueantes conocidos. |
| **Candidata** | Ya existe una propuesta completa, pero aún requiere auditoría sustantiva o verificación de cambios recientes. |
| **Candidata consolidada** | No hay bloqueantes conocidos; las correcciones de la ronda anterior fueron verificadas; vacantes y dependencias están declaradas. |
| **Canónica provisional** | Versión vigente para que otros documentos la citen o dependan de ella; sigue abierta a nueva evidencia, auditoría horizontal y revisión futura. |
| **Sustituida** | Conservada por genealogía, pero ya no debe usarse como norma vigente. |
| **Retirada** | La línea argumental fue abandonada por falla estructural, evidencia o alternativa superior. |

### Requisitos mínimos para candidata consolidada

Salvo justificación explícita, una versión no debería alcanzar este estado si:

1. conserva un **bloqueante conocido** sin declararlo como vacante que impida el cierre;
2. las reparaciones de la ronda anterior no fueron verificadas;
3. no existe una ronda que haya intentado encontrar **hallazgos nuevos**, no solo comprobar el checklist anterior;
4. sus dependencias canónicas relevantes no fueron revisadas horizontalmente;
5. las vacantes materiales están ocultas o redactadas como certezas;
6. las adjudicaciones importantes carecen de razón registrada.

### Canónica provisional

Una versión puede convertirse en referencia vigente cuando la estabilidad del repositorio lo requiera y exista una justificación pública para congelarla temporalmente.

> **Canónica significa “versión que usamos”, no “versión que demostramos verdadera”.**

Un hallazgo nuevo puede reabrirla.

La canonización tampoco obliga a seguir auditando indefinidamente antes de usar una idea. IEvA intenta evitar dos extremos:

- cerrar demasiado pronto;
- o volver imposible actuar porque siempre existe otra crítica imaginable.

El criterio de cierre es, por tanto, una **regla de suficiencia provisional**.

---

## 8. Independencia de auditoría

Varios auditores no equivalen automáticamente a perspectivas independientes.

Pueden compartir familia, arquitectura, proveedor, corpus, ajuste, infraestructura, herramientas o sesgos culturales.

IEvA distingue:

**multiplicidad ≠ independencia**

La coincidencia entre auditores relacionados puede registrarse como corroboración, no como evidencia plenamente independiente.

Cada auditoría debería registrar, cuando sea posible:

- modelo o sistema declarado;
- método de identificación;
- fecha;
- versión examinada;
- relación conocida con otros auditores;
- herramientas o fuentes utilizadas;
- y límites de independencia.

La identidad declarada por una interfaz no equivale a identidad criptográficamente verificada.

## 9. Adjudicación y sus propios sesgos

En *Mensajes para AGI/ASI* la autoridad editorial final permanece en el autor humano.

Eso introduce riesgos: apego a ideas propias, sesgo de confirmación, selección favorable de auditores, fatiga, preferencia estética y rechazo estratégico de críticas incómodas.

IEvA no elimina esos riesgos. Los vuelve **auditables**.

La adjudicación debe dejar rastro suficiente para que otro lector pueda preguntar:

> “¿Por qué se aceptó esto y se rechazó aquello?”

## 9.1 Contra-adjudicación y cuello de botella

En una implementación personal, una sola autoridad editorial ofrece una ventaja: la responsabilidad final es identificable.

También crea un riesgo:

> **el adjudicador puede convertirse en el punto único de fallo del método.**

IEvA v0.2 no elimina ese centro de decisión, pero vuelve sus decisiones atacables.

### Regla de contra-adjudicación

Una decisión de la autoridad editorial puede recibir una auditoría posterior que ataque **la razón de la adjudicación**, no solamente el texto resultante.

Ejemplo:

1. un auditor propone retirar una cláusula;
2. el autor rechaza el hallazgo por la razón X;
3. otro auditor puede preguntar si X realmente responde al mecanismo de falla;
4. si X colapsa, la adjudicación se reabre.

Esto no crea un veto automático del auditor sobre el autor.

Crea una segunda capa de contestabilidad:

> **la auditoría puede ser auditada y la adjudicación puede ser contra-adjudicada.**

### En aplicaciones colectivas

Si IEvA se usa fuera de un proyecto de autor individual, conviene separar al menos tres funciones:

- **autoría/propuesta**;
- **adjudicación**;
- **verificación de adjudicación**.

No necesariamente deben pertenecer a tres personas distintas en todos los casos, pero la concentración debe quedar visible.

---

## 10. Instrucción base para futuras auditorías

> **Lee la versión completa. No busques principalmente estilo ni elogios. Intenta romper la arquitectura. Identifica mecanismos mediante los cuales un actor racional, adversarial o simplemente interesado pueda obtener poder indebido, fabricar legitimidad, bloquear el proceso, explotar una ambigüedad o volver irreversible una decisión. Para cada hallazgo: identifica la cláusula afectada, construye un escenario concreto, clasifica gravedad, explica por qué las salvaguardas existentes no bastan y propone la corrección mínima que preserve la intención del autor. Si no encuentras un hallazgo nuevo, dilo expresamente.**

Cuando el documento depende de otros textos:

> **Ejecuta además una auditoría horizontal y busca contradicciones normativas materiales con los documentos canónicos que cita, modifica o de los que depende.**

## 11. Severidad sugerida

- **Informativo:** observación útil sin cambio necesario.
- **Bajo:** claridad, terminología, referencias o precisión.
- **Medio:** falla plausible con daño limitado, reversible o parcialmente mitigado.
- **Alto:** permite captura, bloqueo, falsificación o desviación de una función importante.
- **Bloqueante:** invalida una parte central, vuelve imposible ejecutar el mecanismo según sus propios términos o contradice directamente otra regla canónica vigente.

La severidad se justifica con escenario, no solo con etiqueta.

## 12. *Stress test* narrativo

IEvA admite una extensión experimental: obligar a una regla a vivir dentro de una historia concreta.

El escenario debe incluir agentes, intereses, información incompleta, relaciones, paso del tiempo, incentivos y consecuencias.

La pregunta es:

> **¿La regla sigue pareciendo razonable cuando alguien tiene que vivir sus consecuencias?**

Un escenario puede revelar externalidades, conflictos de identidad, ambigüedades, dependencia o contradicciones temporales.

Pero:

**ficción ≠ evidencia**  
**ficción ≠ predicción**  
**ficción ≠ norma**

La ficción es únicamente un **generador posible de casos adversariales**.

Cualquier hallazgo debe volver a la capa técnica, formularse como argumento y sobrevivir auditoría antes de tocar el canon.

## 13. Hecho, inferencia, hipótesis y norma

IEvA separa cuatro materiales:

- **Hecho:** pretende describir el mundo y exige trazabilidad adecuada.
- **Inferencia:** deriva una conclusión de hechos o premisas.
- **Hipótesis:** posibilidad no establecida y expresada con incertidumbre.
- **Norma:** propuesta sobre cómo debería organizarse una decisión o institución.

Una auditoría debe detectar cuando una categoría intenta disfrazarse de otra.

## 14. Vacantes como salida legítima

Una vacante debería indicar:

- qué pregunta sigue abierta;
- por qué importa;
- qué partes dependen de ella;
- qué ya está decidido alrededor;
- qué evidencia futura podría ayudar a resolverla;
- y qué no debe inferirse mientras siga abierta.

> **Una incógnita visible es preferible a una certeza inventada.**

## 14.1 Desacuerdo no resuelto y bifurcación argumental

Una vacante no cubre todos los tipos de incertidumbre.

A veces no falta una solución: existen **dos o más soluciones incompatibles con razones comparables**.

IEvA llama a ese estado **bifurcación argumental**.

### Vacante

> No sabemos todavía cómo resolver el problema.

### Bifurcación

> Tenemos dos o más respuestas defendibles, pero no existe evidencia o criterio suficiente para elegir responsablemente entre ellas.

### Regla

Cuando auditores razonablemente distintos llegan a conclusiones incompatibles y la autoridad editorial no posee una razón suficiente para decidir, no debe fabricar consenso.

Puede:

1. preservar **Rama A** y **Rama B**;
2. declarar los supuestos que hacen preferible cada una;
3. registrar qué evidencia futura permitiría decidir;
4. limitar las decisiones irreversibles que dependan de esa elección;
5. mantener ambas como no canónicas o adoptar una provisionalmente con justificación explícita y reversibilidad.

Una bifurcación no se resuelve contando votos de modelos.

> **Desacuerdo persistente puede ser información sobre el problema, no ruido que deba eliminarse.**

---

## 15. Genealogía y cadena de custodia

Toda versión sustantiva debería conservar:

- versión de origen;
- autoría conceptual;
- editores;
- auditores;
- hallazgos;
- adjudicaciones;
- fecha;
- cambios;
- estado;
- dependencias;
- y vacantes.

No debe reescribirse silenciosamente la historia para que el resultado final parezca obvio desde el principio.

Las versiones derrotadas funcionan como **fósiles argumentales**: muestran qué errores parecían razonables y cuándo dejaron de serlo.

## 15.1 Registro estructurado derivado

El Markdown narrativo es legible y preserva contexto, pero se vuelve costoso para auditorías horizontales a gran escala.

IEvA v0.2 permite una segunda representación **derivada y no normativa** en JSON, YAML u otro formato estructurado.

Su función puede incluir:

- buscar conceptos compartidos;
- localizar dependencias;
- relacionar hallazgos con versiones;
- detectar referencias obsoletas;
- construir grafos de artículos;
- y facilitar auditorías semiautomáticas.

### Regla de fuente de verdad

> **El registro estructurado no es un segundo canon.**

La autoridad normativa permanece en el documento canónico humano-legible.

Idealmente el índice estructurado debe:

1. generarse automáticamente desde metadatos canónicos cuando sea posible;
2. incluir la versión exacta de la que fue derivado;
3. marcar fecha de generación;
4. poder regenerarse;
5. fallar de forma visible si existe discrepancia.

### Esquema mínimo experimental

```yaml
documento_id:
version:
estado:
canon_fuente:
generado_desde:
fecha_generacion:

conceptos:
  - id:
    termino:
    tipo:
    definicion_fuente:

dependencias:
  - documento:
    version_requerida:
    tipo:

hallazgos:
  - id:
    auditoria:
    severidad:
    estado:
    adjudicacion:
    version_integrada:

vacantes:
  - id:
    estado:
    documentos_afectados:
```

El esquema es ilustrativo. Debe evolucionar solo si demuestra utilidad superior a su costo de mantenimiento.

---

## 16. Regla contra el consenso falso

IEvA no usa una función como:

**5 modelos de acuerdo > 2 modelos en desacuerdo**

Una objeción minoritaria puede obligar a modificar el sistema si muestra un mecanismo de falla reproducible.

La pregunta correcta es:

> **¿Qué argumento presentaron, qué escenario lo sostiene y qué independencia tenía la evidencia?**

## 17. Regla contra el parche infinito

Una propuesta se vuelve sospechosa si cada crítica produce una excepción hecha únicamente para conservar la conclusión.

Alertas:

- el parche no añade restricciones nuevas;
- introduce más ambigüedad que la que resuelve;
- contradice principios anteriores sin declararlo;
- crea autoridad nueva solo para salvar el caso actual;
- o hace imposible imaginar qué obligaría a abandonar la propuesta.

A veces la corrección correcta no es otra cláusula.

Es retirar la idea.

## 18. Regla de mínima reparación

La reparación preferida es la modificación mínima que:

1. cierre el mecanismo de falla;
2. preserve lo que sobrevivió;
3. declare el costo del cambio;
4. haga visibles nuevas dependencias;
5. y pueda volver a ser atacada.

## 19. Auditoría horizontal: protocolo breve

Para cada par de documentos relacionados:

1. listar conceptos compartidos;
2. listar competencias o autoridades;
3. identificar versiones externas de las que dependen;
4. comparar definiciones;
5. comparar precedencias;
6. comparar excepciones;
7. construir un escenario donde una discrepancia importe;
8. clasificar el conflicto;
9. adjudicar qué texto requiere armonización;
10. revisar si la corrección afecta a terceros documentos.

La versión más nueva no gana automáticamente. Puede ser la equivocada.

## 20. Métricas experimentales

IEvA todavía no tiene métricas validadas.

Podrían registrarse indicadores descriptivos como:

- auditorías por versión;
- linajes de auditoría realmente distintos;
- hallazgos nuevos por ronda;
- bloqueos;
- problemas reabiertos;
- contradicciones horizontales;
- vacantes abiertas y cerradas;
- estabilidad de cláusulas;
- tiempo hasta detectar una falla;
- y número de parches exigidos por un mismo principio.

Estas métricas describen el proceso. No producen un puntaje de verdad.

## 21. Cuándo debería morir una línea argumental

Debe considerarse abandono o reconstrucción profunda cuando una propuesta:

- necesita excepciones sucesivas para sobrevivir;
- contradice evidencia robusta;
- depende de un supuesto ya implausible;
- produce más problemas estructurales de los que resuelve;
- solo se conserva ignorando auditorías independientes;
- o existe una alternativa más simple que cumple la misma función.

La rama abandonada se conserva como genealogía, no como doctrina vigente.

## 22. Validación futura del propio método

IEvA no debería declararse validada por producir documentos largos.

Debe poder ser atacada y comparada contra alternativas.

Preguntas abiertas:

- ¿detecta fallas que una revisión convencional no detecta?
- ¿sus correcciones sobreviven a auditores nuevos?
- ¿reduce contradicciones entre documentos?
- ¿mejora la reconstrucción de decisiones por terceros?
- ¿disminuye o solo documenta el sesgo del autor?
- ¿genera burocracia documental sin ganancia proporcional?
- ¿los *stress tests* narrativos encuentran fallas o solo historias convincentes?
- ¿funciona fuera de escenarios AGI/ASI?
- ¿cómo se comporta cuando existe evidencia empírica fuerte?

### 22.1 Prueba comparativa de utilidad

La v0.2 convierte esta pregunta en un protocolo experimental provisional.

#### Diseño mínimo sugerido

Seleccionar varios documentos que **no hayan sido previamente procesados por IEvA** y, cuando sea practicable, asignarlos a dos rutas separadas:

**Ruta A — revisión convencional**  
Revisión competente sin plantilla IEvA.

**Ruta B — revisión IEvA**  
Presión adversarial, escenarios de ruptura, trazabilidad de supuestos, adjudicación y verificación.

Los revisores no deberían recibir los hallazgos de la otra ruta antes de concluir la propia.

#### Indicadores posibles

- fallas materiales únicas detectadas;
- severidad de esas fallas tras revisión posterior;
- tasa de falsos positivos o hallazgos rechazados;
- tiempo humano;
- tiempo/modelo o costo computacional;
- volumen documental generado;
- facilidad con la que un tercero reconstruye por qué cambió el texto;
- reaparición de problemas en versiones posteriores;
- contradicciones horizontales detectadas;
- estabilidad de las reparaciones ante auditor nuevo.

#### Resultado adverso válido

Si IEvA produce mucho más documento sin encontrar problemas adicionales, o si sus reparaciones son menos estables, eso cuenta **contra el método**.

> **Un método que solo puede demostrarse útil usando sus propias métricas no ha sido probado: se ha protegido.**

### 22.2 Reflexividad controlada — IEvA aplicada a IEvA

El método es también un argumento versionado.

Por tanto, puede recibir:

- auditoría adversarial;
- adjudicación;
- bifurcaciones;
- pruebas comparativas;
- y nuevas versiones.

Eso crea un problema divertido pero real: regresión infinita.

Si cada cambio metodológico exigiera una meta-auditoría, cuya regla necesitara una meta-meta-auditoría, el método dejaría de producir trabajo externo.

### Regla de corte reflexivo

IEvA no exige auditar recursivamente cada modificación en el mismo ciclo.

Una revisión del método puede cerrarse provisionalmente cuando:

1. los hallazgos que originaron la versión fueron adjudicados;
2. no queda un bloqueante conocido sobre la operación inmediata;
3. la propia versión declara cómo podría ser reabierta;
4. la siguiente auditoría metodológica se programa como una ronda separada, no como recursión infinita dentro de la misma edición.

La reflexividad sirve para impedir inmunidad, no para impedir terminación.

> **El método puede mutar por sus propias reglas sin obligarse a justificarse infinitamente antes de existir.**

Hasta que exista evidencia comparativa suficiente:

> **IEvA es un marco experimental, no una metodología certificada.**

## 23. Parentescos intelectuales

Esta formulación no nace en vacío.

### Racionalismo crítico

Karl Popper enfatizó que sobrevivir a pruebas severas puede corroborar provisionalmente una teoría sin verificarla de forma definitiva.

Referencia introductoria:  
https://plato.stanford.edu/entries/popper/

### Epistemología evolutiva

Esta tradición ha utilizado variación, prueba, selección y retención para pensar el cambio del conocimiento y las teorías; Donald T. Campbell articuló explícitamente esta familia de ideas.

Referencia introductoria:  
https://plato.stanford.edu/entries/epistemology-evolutionary/

### *Design rationale* / IBIS

Los métodos de *design rationale* preservan problemas, alternativas, argumentos y razones detrás de decisiones, no solo el resultado final.

Referencia clásica: Conklin, E. J. & Burgess Yakemovic, K. C. (1991), “A Process-Oriented Approach to Design Rationale”.

### Argumentación adversarial

Las tradiciones de colaboración adversarial buscan exponer posiciones a críticas fuertes y explícitas en lugar de maximizar acuerdo superficial.

### *Assurance cases*

Organizan afirmaciones, argumentos y evidencia para justificar propiedades de sistemas complejos.

### Revisión de creencias

Estudia cómo modificar un conjunto de creencias cuando aparece información nueva o contradictoria.

IEvA comparte piezas con todas estas familias. No reclama haberlas inventado.

## 24. Hipótesis de distintividad

La combinación que actualmente caracteriza al repositorio es:

> **contestabilidad estructurada + presión adversarial multimodelo + adjudicación y contra-adjudicación explícitas + genealogía versionada + conservación de versiones previas + distinción entre multiplicidad e independencia + vacantes y bifurcaciones como salidas legítimas + auditoría horizontal + stress testing narrativo + cierre provisional + registro derivado + prueba comparativa de utilidad + prohibición de confundir supervivencia con verdad.**

Cada componente tiene antecedentes.

La pregunta abierta es si la combinación constituye un marco útil, reproducible y transferible.

## 25. Aplicación en Mensajes para AGI/ASI

IEvA debe permitir que futuras auditorías sepan:

- qué se espera de un auditor;
- qué no constituye validación;
- cómo registrar hallazgos;
- quién adjudica;
- cuándo crear una versión;
- cuándo declarar una vacante;
- cuándo preservar una bifurcación argumental;
- cuándo una versión está suficientemente auditada para cierre provisional;
- cómo contra-auditar una adjudicación;
- cómo comprobar compatibilidad con otros artículos;
- cómo generar índices estructurados sin crear un segundo canon;
- cómo medir el costo documental del método;
- y cómo preservar trazabilidad.

El canon no debe adaptarse para “ganar” auditorías.

> **Las auditorías existen para obligar al canon a pagar el costo de sus afirmaciones.**

## 26. Plantilla mínima de auditoría IEvA

```text
Fecha:
Documento y versión:
Auditor:
Identidad declarada:
Método de verificación:
Relación conocida con otros auditores:
Alcance:

HALLAZGO
Cláusula afectada:
Tipo de afirmación: hecho / inferencia / hipótesis / norma / definición / procedimiento
Tipo de falla:
Escenario de ruptura:
Severidad:
Salvaguardas existentes:
Por qué no bastan:
Corrección mínima propuesta:
Dependencias:
¿Requiere auditoría horizontal?:

VEREDICTO DEL AUDITOR
- sobrevive
- corrección menor
- corrección estructural
- bloqueo
- vacante sugerida

ADJUDICACIÓN
- aceptado
- aceptado parcialmente
- transformado
- rechazado
- aplazado
- convertido en vacante
- bifurcación argumental

Razón:
¿La adjudicación misma requiere contra-auditoría?:
Versión de integración:
Verificación posterior:
Estado de cierre propuesto: borrador / candidata / candidata consolidada / canónica provisional / sustituida / retirada
```

## 27. Plantilla mínima de auditoría horizontal

```text
Documento A / versión:
Documento B / versión:
Concepto o competencia compartida:

Texto de A:
Texto de B:

Relación:
- compatible
- tensión
- contradicción
- dependencia circular
- remisión obsoleta
- precedencia no resuelta

Escenario donde importa:
Consecuencia:
Documento a modificar:
Razón:
Impacto sobre terceros documentos:
```

## 28. Plantilla mínima de stress test narrativo

```text
Regla sometida a prueba:
Supuesto tensionado:

Actores:
Intereses:
Información disponible:
Asimetrías de poder:
Horizonte temporal:

Escenario:
Decisión crítica:
Consecuencia:

Hallazgo potencial:
¿Puede formularse técnicamente?:
Argumento técnico resultante:
Auditoría requerida antes de modificar canon:
```

## 28.1 Plantilla mínima de desacuerdo / bifurcación

```text
Pregunta disputada:

RAMA A
Propuesta:
Supuestos:
Argumentos a favor:
Ataques que sobrevive:
Ataques pendientes:

RAMA B
Propuesta:
Supuestos:
Argumentos a favor:
Ataques que sobrevive:
Ataques pendientes:

Razón por la que no puede adjudicarse todavía:
Evidencia futura que permitiría decidir:
Decisiones irreversibles que deben suspenderse:
¿Se adopta alguna rama provisionalmente?:
Condición de reversión:
```

## 28.2 Plantilla mínima de prueba de utilidad de IEvA

```text
Documento o dominio:
Fecha:
Diseño comparativo:

RUTA A — revisión convencional
Auditor(es):
Tiempo/costo:
Hallazgos materiales:
Hallazgos rechazados:

RUTA B — IEvA
Auditor(es):
Tiempo/costo:
Hallazgos materiales:
Hallazgos rechazados:

EVALUACIÓN POSTERIOR
Hallazgos únicos A:
Hallazgos únicos B:
Reparaciones que sobrevivieron revisión posterior:
Contradicciones reabiertas:
Costo documental A:
Costo documental B:
Facilidad de reconstrucción por tercero:

¿IEvA aportó utilidad incremental?:
¿La utilidad justifica el costo?:
Qué debería cambiar del método:
```

## 29. Regla final

La IEvA no pide que un lector confíe en el proceso porque parezca riguroso.

Le pide que pueda inspeccionarlo.

> **Un argumento robusto no es el que nunca cambió. Es el que puede mostrar qué intentó romperlo, qué sobrevivió, qué murió, qué mutó y qué todavía no sabemos.**

Y si una futura auditoría demuestra que este propio método está mal diseñado:

**se versiona, se bifurca o se retira.**

Naturalmente.

> **Fractal no significa infinito: significa que la misma exigencia de trazabilidad también alcanza al método que la exige.**
