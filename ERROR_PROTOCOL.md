# ⚠️ Protocolo de Error / Error Protocol (v1.0)

Este protocolo define cómo deben actuar las máquinas y humanos cuando hay un fallo de comunicación en SENA. / *This protocol defines how machines and humans should act when a communication failure occurs in SENA.*

---

## 1. Comandos de Error / Error Commands

| SENA | ESPAÑOL | ENGLISH |
| :--- | :--- | :--- |
| **ERROR 00** | No entiendo (General) | I do not understand (General) |
| **ERROR 01** | Raíz no encontrada | Root not found |
| **ERROR 02** | Fallo de sintaxis (SVO) | Syntax failure (SVO) |
| **ERROR 03** | Carácter no ASCII detectado | Non-ASCII character detected |

---

## 2. Acciones de Respuesta / Response Actions

**ES:** Cuando se detecta un error, el sistema debe responder con la partícula `ka` seguida del código de error.
**EN:** *When an error is detected, the system must respond with the particle `ka` followed by the error code.*

* **Ejemplo / Example:** `ka ERROR 01` (¿Qué palabra es esa? / *Which word is that?*)

---

## 3. Resolución de Ambigüedad / Ambiguity Resolution

**ES:** Si una frase no es clara, se pide repetición usando la partícula de inicio de pregunta `ka`.
**EN:** *If a sentence is not clear, repetition is requested using the question particle `ka`.*

* **SENA:** `ka diki veni`
* **ES:** ¿Puedes decir eso otra vez?
* **EN:** *Can you say that again?*
