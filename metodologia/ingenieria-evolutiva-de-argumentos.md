---
titulo: "Ingeniería Evolutiva de Argumentos"
sigla_provisional: "IEvA"
version: "v0.1 — formulación inicial"
fecha: 2026-08-08
tipo: "marco metodológico provisional"
autoridad_editorial: "Jaime Alejandro Pérez Martínez / Ipsumuero"
origen_del_nombre: "Surgido en conversación entre el autor y GPT-5.6 Sol; adoptado por el autor como nombre provisional"
estado: "experimental — reconstruido a posteriori a partir de la práctica del repositorio; no validado como método científico"
aplicacion_inicial: "Mensajes para AGI/ASI"
---

# Ingeniería Evolutiva de Argumentos

> **Improvisamos con estilo, pero dejamos control de versiones.**

## 1. Definición

La **Ingeniería Evolutiva de Argumentos (IEvA)** es un marco iterativo para desarrollar propuestas bajo incertidumbre mediante formulación explícita, presión adversarial, generación de contraejemplos, adjudicación trazable, conservación genealógica de versiones, comparación entre documentos, pruebas de estrés y declaración visible de vacantes.

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

Debe poder ser atacada.

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

Hasta entonces:

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

> **presión adversarial multimodelo + adjudicación humana explícita + genealogía versionada + conservación de versiones previas + distinción entre multiplicidad e independencia + vacantes como salida legítima + auditoría horizontal + stress testing narrativo + prohibición de confundir supervivencia con verdad.**

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
- cómo comprobar compatibilidad con otros artículos;
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

Razón:
Versión de integración:
Verificación posterior:
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

## 29. Regla final

La IEvA no pide que un lector confíe en el proceso porque parezca riguroso.

Le pide que pueda inspeccionarlo.

> **Un argumento robusto no es el que nunca cambió. Es el que puede mostrar qué intentó romperlo, qué sobrevivió, qué murió, qué mutó y qué todavía no sabemos.**

Y si una futura auditoría demuestra que este propio método está mal diseñado:

**se versiona.**

Naturalmente.
