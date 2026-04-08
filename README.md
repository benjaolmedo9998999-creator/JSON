# JSON
= Que es json
= Estrucura basica
= Tipo de datos soportados

Actividad: 
Crear un ejmplo basico persona.Contendra nombre edad gmail y el id.Se debera cargar al menos 10 persona


--------------------------------------------------------------------------------------------------------

##  Manejo de Datos con JSON

###  ¿Qué es JSON?
**JSON** (*JavaScript Object Notation*) es un formato de texto ligero utilizado para el intercambio de datos. Es un estándar independiente del lenguaje, lo que permite que aplicaciones desarrolladas en diferentes tecnologías (como Python, JS o PHP) se comuniquen entre sí de forma sencilla.

###  Estructura Básica
Se basa en dos estructuras:
1. **Colección de pares clave/valor:** En Python se asocian a *diccionarios* `{ }`.
2. **Lista ordenada de valores:** En Python se asocian a *listas* `[ ]`.

###  Tipos de Datos Soportados
| Tipo | Descripción |
| :--- | :--- |
| **String** | Cadenas de texto entre comillas dobles `" "` |
| **Number** | Valores numéricos (enteros o flotantes) |
| **Boolean** | Valores lógicos `true` o `false` |
| **Array** | Listas de elementos entre corchetes `[ ]` |
| **Object** | Conjunto de pares clave/valor entre llaves `{ }` |
| **Null** | Representa un valor vacío o inexistente |

---

### Estructura de Datos (Personas)
Ejemplo de un archivo `datos.json` que contiene un listado de 10 usuarios:

```json
[
  { "id": 1, "nombre": "Lucas Gómez", "edad": 24, "gmail": "lucas.gomez@gmail.com" },
  { "id": 2, "nombre": "Sofía Paz", "edad": 29, "gmail": "sofia.paz@gmail.com" },
  { "id": 3, "nombre": "Martín Vera", "edad": 31, "gmail": "m.vera@gmail.com" },
  { "id": 4, "nombre": "Lucía Fernández", "edad": 22, "gmail": "lucia.f@gmail.com" },
  { "id": 5, "nombre": "Diego Ruiz", "edad": 27, "gmail": "druiz@gmail.com" },
  { "id": 6, "nombre": "Elena Soler", "edad": 35, "gmail": "elena.soler@gmail.com" },
  { "id": 7, "nombre": "Mateo Rojas", "edad": 19, "gmail": "m.rojas@gmail.com" },
  { "id": 8, "nombre": "Clara Ortiz", "edad": 26, "gmail": "clara.ortiz@gmail.com" },
  { "id": 9, "nombre": "Bruno Silva", "edad": 40, "gmail": "bruno.s@gmail.com" },
  { "id": 10, "nombre": "Julia Méndez", "edad": 23, "gmail": "j.mendez@gmail.com" }
]
