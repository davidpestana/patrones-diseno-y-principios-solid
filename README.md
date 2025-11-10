# 🧩 Curso: Patrones de Diseño y Principios SOLID

Este repositorio contiene **todo el material del curso**, listo para ejecutarse directamente en **GitHub Codespaces**.
No hace falta instalar nada: solo haces *fork*, abres el Codespace y empiezas a ejecutar los notebooks.

---

## 🚀 Cómo empezar

1️⃣ Haz **fork** del repo en tu cuenta de GitHub.

2️⃣ En tu fork, pulsa **“Code → Create Codespace on main”**.

3️⃣ Espera a que el entorno cargue (unos minutos).

4️⃣ Abre el primer notebook dentro de `modulo01-solid/`.

5️⃣ Verifica que el kernel activo sea **Deno (TypeScript)**.

6️⃣ Ejecuta celda a celda (▶️) y sigue las instrucciones.


Todo el entorno está automatizado: no tienes que instalar Deno ni Jupyter manualmente.

---

## 💡 Dinámica del curso

El curso está diseñado en formato **interactivo**.
Cada notebook incluye:

| Tipo de bloque | Descripción                                         |
| -------------- | --------------------------------------------------- |
| 🧠 Conceptos   | Explicaciones cortas y visuales.                    |
| 💻 Ejemplos    | Código ejecutable en TypeScript.                    |
| 🧩 Ejercicios  | Retos guiados para que escribas tu propia solución. |
| ✅ Soluciones   | Código resuelto con explicación.                    |
| 🧾 Resumen     | Síntesis de los conceptos vistos.                   |

El objetivo es **aprender haciendo**, con teoría mínima y práctica continua.
Puedes pausar y retomar cuando quieras; cada notebook es independiente.

---

## 📘 Estructura del temario

```
modulo01-solid/
 ├─ 1.1_introduccion_SOLID.ipynb
 └─ 1.2_principios_SOLID_en_accion.ipynb

modulo02-patrones-intro/
 ├─ 2.1_introduccion_patrones.ipynb
 └─ 2.2_catalogo_gof.ipynb

modulo03-creacionales/
 ├─ 3.1_singleton_factory.ipynb
 └─ 3.2_builder_prototype.ipynb

modulo04-estructurales/
 ├─ 4.1_adapter_facade.ipynb
 └─ 4.2_composite_decorator.ipynb

modulo05-comportamiento/
 ├─ 5.1_strategy_observer.ipynb
 └─ 5.2_command_chain_state.ipynb

modulo06-antipatrones/
 ├─ 6.1_antipatrones_y_refactorizacion.ipynb
 └─ 6.2_revision_final_y_test.ipynb
```

Cada módulo se centra en un bloque de conocimiento progresivo:
de los **principios SOLID**, pasando por **patrones de diseño**, hasta **antipatrones y refactorización**.

---

## 🎯 Objetivos

* Comprender los **principios SOLID** y cómo aplicarlos correctamente.
* Conocer y utilizar los principales **patrones de diseño** (creacionales, estructurales y de comportamiento).
* Detectar **antipatrones** y corregirlos con refactorización.
* Diseñar software **mantenible, extensible y legible**.

---

## 🗓️ Planificación recomendada (3 sesiones)

### 🕐 Sesión 1 — Fundamentos y SOLID

**Duración:** ~3h30
**Notebooks:** 1.1, 1.2, 2.1
**Objetivo:** Entender los cinco principios SOLID y la idea general de los patrones de diseño.

---

### 🕑 Sesión 2 — Patrones creacionales y estructurales

**Duración:** ~3h30
**Notebooks:** 3.1, 3.2, 4.1, 4.2
**Objetivo:** Aprender cómo crear objetos correctamente y estructurar sistemas mediante composición y desacoplamiento.

---

### 🕒 Sesión 3 — Patrones de comportamiento y antipatrones

**Duración:** ~3h
**Notebooks:** 5.1, 5.2, 6.1, 6.2
**Objetivo:** Aplicar patrones de interacción entre objetos, reconocer malas prácticas y realizar el test final del curso.

---

## ⚙️ Consejos prácticos

* Ejecuta cada celda en orden; muchas construyen ejemplos progresivos.
* Si el kernel Deno no aparece, ejecuta:
  `deno jupyter --install --force`
* Si algo falla, reinicia el kernel (menú “Kernel → Restart”).
* Guarda tus progresos en tu fork; así mantienes tus resultados y ejercicios.

---

## 🧩 Evaluación final

El último notebook (`6.2_revision_final_y_test.ipynb`) incluye un **test interactivo** de repaso y ejercicios prácticos.
No hay calificación automática, pero puedes validar tus respuestas con las soluciones propuestas.

---

## 👨‍🏫 Autor y espíritu del curso

Este material ha sido creado por **David Pestana Perdomo**, con un enfoque totalmente práctico y orientado a desarrolladores y arquitectos que buscan **mejorar la calidad del diseño de su código**.

> “Un buen diseño no solo funciona, sino que evoluciona con facilidad.”
> — Robert C. Martin (Uncle Bob)
