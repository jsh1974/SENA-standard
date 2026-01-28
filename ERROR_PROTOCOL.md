# ⚠️ Protocolo de Error / Error Protocol (v1.0)

Este protocolo define la respuesta lógica ante fallos de comunicación. / *This protocol defines the logical response to communication failures.*

---

## 1. Comandos de Error / Error Commands

| SENA | ESPAÑOL | ENGLISH |
| :--- | :--- | :--- |
| **ERROR 00** | No entiendo | I do not understand |
| **ERROR 01** | Raíz no encontrada | Root not found |
| **ERROR 02** | Fallo de sintaxis (SVO) | Syntax failure (SVO) |
| **ERROR 03** | Carácter no ASCII detectado | Non-ASCII character detected |

---

## 2. Uso de la partícula de pregunta / Use of the question particle

**ES:** SENA no utiliza signos de interrogación. Toda duda o petición de clarificación comienza con la partícula `ka`.
**EN:** *SENA does not use question marks. Any doubt or request for clarification begins with the `ka` particle.*

* **Ejemplo de error / Error example:** `ka ERROR 01`
* **Petición de repetición / Request for repetition:** `ka diki veni`

---

## 3. Formato de carácteres / Character format

**ES:** Solo se permite el set de carácteres ASCII estándar. El uso de cualquier otro símbolo provocará un ERROR 03.
**EN:** *Only the standard ASCII character set is allowed. Using any other symbol will trigger an ERROR 03.*
