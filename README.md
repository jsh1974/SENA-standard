# 🌐 SENA Language Specification (v1.1)
**ES:** Sencillo · Eficiente · Neutro · ASCII  
**EN:** *Simple · Efficient · Neutral · ASCII*

---

## 1. Introducción / Introduction
**ES:** SENA es un protocolo de comunicación lógico diseñado para humanos y máquinas. Su objetivo es eliminar la ambigüedad y reducir la complejidad del lenguaje natural.  
**EN:** *SENA is a logical communication protocol designed for humans and machines. Its goal is to eliminate ambiguity and reduce the complexity of natural language.*

---

## 2. Reglas de Oro / Core Rules
1. **Sintaxis / Syntax (SVO):** Sujeto + Verbo + Objeto / *Subject + Verb + Object*.
2. **Verbos / Verbs:** El verbo es invariable. El tiempo lo define una partícula / *Verbs are invariable. Tense is defined by a particle*.
3. **Neutralidad / Neutrality:** No existe el género gramatical. `ta` es universal / *No grammatical gender. `ta` is universal*.
4. **Plural:** Se añade `-s` al final de la palabra / *Add `-s` at the end of the word*.
5. **Adjetivos / Adjectives:** Siempre después del sustantivo / *Always after the noun* (`domo granda`).
6. **Ortografía / Orthography:** Solo caracteres ASCII estándar. Sin signos de puntuación innecesarios / *Standard ASCII characters only. No unnecessary punctuation marks*.

---

## 3. Gramática Técnica / Technical Grammar

### Partículas de Tiempo / Temporal Particles
- `nu` : **ES:** Presente / **EN:** *Present*
- `pa` : **ES:** Pasado / **EN:** *Past*
- `fu` : **ES:** Futuro / **EN:** *Future*
- `ja` : **ES:** Completado / **EN:** *Completed*
- `si` : **ES:** Condicional / **EN:** *Conditional*

### Pregunta y Negación / Question and Negation
- `ka` : **ES:** Partícula de inicio para preguntas. No usar signos / **EN:** *Start particle for questions. Do not use marks*.
- `no` : **ES:** Negación simple / **EN:** *Simple negation*.

---

## 4. Diccionario de Raíces / Roots Dictionary
**ES:** El estándar cuenta actualmente con 120 raíces base. Consultar `roots.json` para la base completa.  
**EN:** *The standard currently features 120 base roots. Check `roots.json` for the full database.*

| SENA | ESPAÑOL | ENGLISH |
| :--- | :--- | :--- |
| **esi** | ser / estar | to be |
| **faki** | hacer | to do / make |
| **homo** | persona | person |
| **vola** | querer | to want |
| **sapi** | saber | to know |
| **pax** | paz | peace |

---

## 5. Muestra de Texto / Text Sample
**SENA:** ka ta nu faki labo bon  
**ES:** ¿Él hace bien el trabajo?  
**EN:** *Does he do the work well?*

**SENA:** mi pa faki un idea nova  
**ES:** Yo hice una idea nueva.  
**EN:** *I made a new idea.*
