# Actividad de GitHub Classroom: Propuesta de Práctica Temática Pequeña

## 1) Título

**Diseño de Propuesta: Mini Herramienta en Terminal (ARM64, C, Python o Bash)**

> Puedes ajustar el nombre final de tu proyecto. Ejemplos: 
> - Mini Toolkit en ARM64
> - Asistente de Estudio en Terminal
> - Reporteador de Información del Sistema
> - Organizador de Archivos
> - Juego de Aprendizaje en Línea de Comandos

---

## 2) Descripción general

En esta actividad **vas a diseñar la propuesta de un proyecto pequeño** con enfoque técnico y documental.  
La meta es que planees bien tu práctica antes de programar mucho código.

Debes elegir **un lenguaje principal**:
- ARM64 Assembly
- C
- Python
- Bash

### Regla importante sobre alcance
- Tu proyecto debe ser **pequeño, claro y realizable** en poco tiempo.
- Si eliges **ARM64 Assembly**, se recomienda que sea para programas **muy pequeños** (por ejemplo: operaciones básicas, lectura de argumentos simples o manejo mínimo de archivos/texto).

### Prioridad de la actividad
1. Documentación de la idea.
2. Justificación técnica y académica.
3. Estructura del repositorio.
4. Plan de pruebas.
5. Código mínimo opcional para demostrar viabilidad.

> Esta práctica está diseñada para poder trabajarse con herramientas gratuitas (como Codex en plan libre u otras IA con límites), evitando complejidad innecesaria.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir **como mínimo**:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcional (si decides incluir demo técnica):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta estructura base:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Instrucciones de desarrollo de la propuesta

### Paso A: Define el problema
En `docs/propuesta.md` explica:
- Nombre tentativo del proyecto.
- Problema que quieres resolver.
- Usuario objetivo.
- Alcance pequeño (qué sí hará y qué no hará).
- Lenguaje seleccionado y por qué.

### Paso B: Describe el caso de uso
En `docs/caso_de_uso.md` incluye:
- Escenario realista de uso.
- Entradas esperadas.
- Salidas esperadas.
- Flujo básico de ejecución (inicio → proceso → resultado).

### Paso C: Planea la estructura del repo
En `docs/estructura_repositorio.md` documenta:
- Carpetas y archivos propuestos.
- Función de cada archivo.
- Convención de nombres.
- Cómo se ejecutaría (comando principal).

### Paso D: Diseña el plan de pruebas
En `docs/plan_de_pruebas.md` describe:
- Al menos 5 casos de prueba.
- Para cada caso: objetivo, entrada, resultado esperado.
- Casos de borde (ejemplo: entrada vacía o parámetro inválido).

---

## 6) Restricciones técnicas

Para mantener el proyecto viable:
- No usar frameworks pesados.
- No usar APIs pagadas.
- No usar bases de datos.
- No usar servicios en la nube.
- No usar contenedores.
- Evitar dependencias complejas.

Se espera una solución de terminal o línea de comandos con bajo acoplamiento.

---

## 7) Criterios de evaluación (rúbrica sugerida)

- **Claridad de la propuesta (25%)**
  - Objetivo bien definido y alcance realista.
- **Calidad de documentación (30%)**
  - Documentos completos, ordenados y entendibles.
- **Diseño técnico del repositorio (20%)**
  - Estructura coherente con el caso de uso.
- **Plan de pruebas (15%)**
  - Casos suficientes, bien planteados y verificables.
- **Viabilidad técnica (10%)**
  - El proyecto puede implementarse con esfuerzo razonable.

---

## 8) Recomendaciones por lenguaje

- **ARM64 Assembly**: ideal para ejercicios mínimos de lógica y sistema; mantén alcance muy controlado.
- **C**: buena opción para utilidades pequeñas y control explícito de entrada/salida.
- **Python**: útil para prototipos rápidos y scripts de automatización.
- **Bash**: excelente para tareas de sistema y automatización simple en terminal.

---

## 9) Entrega final

Sube tu repositorio a GitHub Classroom con toda la documentación solicitada.  
Si agregas código, que sea una **prueba mínima funcional** alineada a tu propuesta.

---

## 10) Plantilla breve para `docs/propuesta.md`

Puedes usar esta guía inicial:

```markdown
# Propuesta de Proyecto

## 1. Título tentativo

## 2. Lenguaje principal
(ARM64 Assembly / C / Python / Bash)

## 3. Problema a resolver

## 4. Usuario objetivo

## 5. Objetivo general

## 6. Alcance
### Incluye
- 
### No incluye
- 

## 7. Justificación técnica

## 8. Plan de implementación mínima
- Paso 1:
- Paso 2:
- Paso 3:
```
