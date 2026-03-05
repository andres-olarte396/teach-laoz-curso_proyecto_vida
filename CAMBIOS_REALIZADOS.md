# PROMPT DE CAMBIOS REALIZADOS - PROYECTO CURSO DE VIDA

## CONTEXTO DEL PROYECTO

Curso completo de "Proyecto de Vida y Orientación Vocacional" para estudiantes de 15-18 años, con 16 horas de duración, organizado en 5 módulos (0-4) con 13 temas totales.

---

## CAMBIOS IMPLEMENTADOS

### 1. CREACIÓN DE DOCUMENTACIÓN PRINCIPAL

#### README.md (253 líneas)

Crear archivo README.md con la siguiente estructura completa:

**Encabezado:**

```markdown
# 🎯 Curso: Proyecto de Vida y Orientación Vocacional

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Módulos](https://img.shields.io/badge/m%C3%B3dulos-5-blue.svg)]()
[![Duración](https://img.shields.io/badge/duraci%C3%B3n-16%20horas-orange.svg)]()
```

**Descripción:**
Curso orientado a jóvenes entre 15-18 años para descubrir identidad, valores, talentos y construir plan de vida alineado con contexto personal y laboral.

**Módulos del curso:**

- **Módulo 0**: Preconceptos - Glosario de términos fundamentales
- **Módulo 1**: Autoconocimiento (Identidad, Valores, Talentos)
- **Módulo 2**: Contexto (FODA, Influencias, Futuro Laboral)
- **Módulo 3**: Exploración (Vocación, Rutas, Decisiones)
- **Módulo 4**: Planificación (Visión, Metas, Cronograma, Resiliencia)

**Estructura de archivos:**
Árbol completo mostrando:

```
├── course.json
├── INDICE.md
├── plan_curricular.md
├── cronograma.md
├── CURSO_COMPLETO.md
├── README.md
├── media/
│   ├── *.wav (13 archivos de audio)
│   └── *.png (imágenes)
└── modulos/
    ├── modulo_0/ (tema_0.1_preconceptos.md)
    ├── modulo_1/ (3 temas × 4 archivos)
    ├── modulo_2/ (3 temas × 4 archivos)
    ├── modulo_3/ (3 temas × 4 archivos)
    └── modulo_4/ (4 temas × 4 archivos)
```

**Metodología:**

- Aprendizaje experiencial
- Teoría breve + Ejercicios prácticos
- Evaluaciones formativas

**Estadísticas:**

- Total archivos: 72
- Líneas de contenido: 4,140+
- Audio: 13 archivos .wav
- Imágenes: 2 archivos .png

**Tags:**
#OrientaciónVocacional #ProyectoDeVida #Educación #Autoconocimiento #PlanificaciónCarrera

---

### 2. CORRECCIONES ORTOGRÁFICAS (26 archivos modificados)

**Errores corregidos:**

1. "Concerse" → "Conocerse" (tema_1.1**el_espejo_interior**contenido.md)
2. "tambaleará" → "se tambaleará" (tema_3.3**toma_de_decisiones_inteligente**contenido.md)
3. "Baje" → "Baja" (tema_4.1**vision_de_futuro**contenido.md)

---

### 3. ADICIÓN DE REFLEXIONES FINALES - ARCHIVOS DE CONTENIDO

Agregar al final de cada archivo `*_contenido.md` (13 temas) una sección:

```markdown
---

## REFLEXIÓN FINAL

**Pregunta de cierre:**
[Pregunta específica del tema]

**Acción concreta:**
[Acción práctica relacionada con el tema]
```

**Ejemplos por tema:**

- **Tema 1.1 (El Espejo Interior):**

  - Pregunta: "¿Qué área de tu 'Ventana de Johari' necesitas trabajar más?"
  - Acción: "Esta semana, pide feedback honesto a 3 personas de confianza"

- **Tema 2.1 (Mi Ecosistema):**

  - Pregunta: "¿Cuál es tu mayor fortaleza y cómo puedes usarla?"
  - Acción: "Completa tu matriz FODA personal"

- **Tema 3.2 (Exploración de Rutas):**

  - Pregunta: "¿Qué ruta académica se alinea mejor con tu perfil?"
  - Acción: "Investiga 3 opciones concretas"

- **Tema 4.4 (Resiliencia):**
  - Pregunta: "¿Qué obstáculo actual puedes ver como oportunidad?"
  - Acción: "Define tu Plan B y Plan C"

_(Aplicar patrón similar a los 13 temas)_

---

### 4. ADICIÓN DE RÚBRICAS Y REFLEXIONES - ARCHIVOS DE EJERCICIOS

Agregar al final de cada archivo `*_ejercicios.md` (13 temas):

#### A) Tabla de Rúbrica (100 puntos)

```markdown
---

## RÚBRICA DE EVALUACIÓN

| **Criterio**                          | **Excelente (90-100)**          | **Bueno (70-89)**  | **Suficiente (60-69)** | **Insuficiente (<60)** | **Puntos** |
| ------------------------------------- | ------------------------------- | ------------------ | ---------------------- | ---------------------- | ---------- |
| **Profundidad de reflexión** (30 pts) | Análisis profundo y personal    | Reflexión adecuada | Reflexión superficial  | Sin reflexión          | /30        |
| **Aplicación práctica** (25 pts)      | Ejemplos concretos y relevantes | Ejemplos generales | Ejemplos vagos         | Sin ejemplos           | /25        |
| **Claridad y estructura** (20 pts)    | Muy claro y organizado          | Claro              | Poco claro             | Confuso                | /20        |
| **Creatividad** (15 pts)              | Muy original                    | Original           | Poco original          | Sin creatividad        | /15        |
| **Compromiso** (10 pts)               | Totalmente comprometido         | Comprometido       | Algo comprometido      | Sin compromiso         | /10        |
| **TOTAL**                             |                                 |                    |                        |                        | **/100**   |
```

#### B) Reflexión Final del Ejercicio

```markdown
---

## REFLEXIÓN FINAL DEL EJERCICIO

Después de completar este ejercicio, responde:

1. **¿Qué descubriste sobre ti mismo/a?**
   
   _________________________________________________________________

2. **¿Qué fue lo más difícil del ejercicio?**
   
   _________________________________________________________________

3. **¿Cómo aplicarás lo aprendido en tu vida diaria?**
   
   _________________________________________________________________

4. **¿Qué acción concreta harás esta semana relacionada con este tema?**
   
   _________________________________________________________________

---

**Compromiso personal:**
Me comprometo a: ****\*\*\*\*****\*\*****\*\*\*\*****\_****\*\*\*\*****\*\*****\*\*\*\*****

Firma: **\*\*\*\***\_**\*\*\*\*** Fecha: **\*\*\*\***\_**\*\*\*\***
```

_(Aplicar a los 13 archivos de ejercicios)_

---

### 5. MENSAJE DE CIERRE FINAL DEL CURSO

Agregar al final del archivo `modulo_4/tema_4.4__resiliencia_y_adaptabilidad__ejercicios.md`:

```markdown
---

## 🎓 MENSAJE FINAL DEL CURSO

**¡Felicitaciones por completar tu Proyecto de Vida!**

Has recorrido un camino de autoconocimiento profundo:
- ✅ Conoces tu identidad, valores y talentos
- ✅ Entiendes tu contexto y el mundo laboral
- ✅ Has explorado rutas y tomado decisiones
- ✅ Tienes una visión, metas y un plan de acción
- ✅ Estás preparado/a para adaptarte y ser resiliente

**Recuerda:**
> "Tu Proyecto de Vida no es un destino fijo, es una brújula que te guía. Ajústala cuando sea necesario, pero nunca dejes de caminar hacia tu mejor versión."

**Este documento es TUYO. Guárdalo, revísalo cada 6 meses, actualízalo.**

---

**Última pregunta:**
¿Qué frase definiría tu Proyecto de Vida en este momento?

---

**Ahora... ¡Ve y constrúyelo! 🚀**
```

---

### 6. ENRIQUECIMIENTO DEL MÓDULO 0 - PRECONCEPTOS

Expandir `modulos/modulo_0/tema_0.1_preconceptos.md` con:

#### A) Definiciones adicionales de Valores/Ética/Normas

```markdown
### 🧭 VALORES

**Definición:** Principios fundamentales y universales que guían el comportamiento humano hacia el bien común y la realización personal.

**Características:**

- Son abstractos y profundos
- Orientan decisiones en momentos de incertidumbre
- Ejemplos: Honestidad, Libertad, Justicia, Respeto

**Función:** Actúan como "brújula interior" que señala el norte moral.

---

### ⚖️ ÉTICA

**Definición:** Conjunto de principios morales que determinan lo que está bien o mal desde una perspectiva racional y universal.

**Características:**

- Se basa en el razonamiento filosófico
- Trasciende culturas y épocas
- Ejemplos: No dañar, ser justo, actuar con integridad

**Función:** Proporciona el marco teórico para evaluar acciones humanas.

---

### 📜 NORMAS

**Definición:** Reglas explícitas establecidas por una institución, sociedad o grupo para regular la convivencia.

**Características:**

- Son concretas y específicas
- Tienen consecuencias claras (premios/castigos)
- Ejemplos: Leyes, reglamentos escolares, códigos de conducta

**Función:** Traducen valores y ética en comportamientos observables y exigibles.

---

### 🎯 PRINCIPIOS

**Definición:** Verdades fundamentales que sirven como base para el razonamiento y la acción en áreas específicas.

**Características:**

- Son más concretos que los valores pero menos que las normas
- Guían metodologías y sistemas
- Ejemplos: Principio de reciprocidad, principio de subsidiariedad

**Función:** Conectan valores abstractos con prácticas concretas.

---

### 🔄 ACTITUDES

**Definición:** Disposiciones mentales y emocionales relativamente estables hacia personas, objetos o situaciones.

**Características:**

- Son subjetivas y variables
- Se forman por experiencia y aprendizaje
- Ejemplos: Optimismo, empatía, perseverancia

**Función:** Traducen valores en tendencias de comportamiento cotidiano.
```

#### B) Tabla Comparativa

```markdown
---

## 📊 TABLA COMPARATIVA: VALORES vs ÉTICA vs NORMAS vs PRINCIPIOS vs ACTITUDES

| **Aspecto**      | **Valores**          | **Ética**  | **Normas**              | **Principios** | **Actitudes** |
| ---------------- | -------------------- | ---------- | ----------------------- | -------------- | ------------- |
| **Naturaleza**   | Abstracta            | Filosófica | Concreta                | Fundamental    | Psicológica   |
| **Alcance**      | Universal            | Universal  | Contextual              | General        | Personal      |
| **Origen**       | Cultural/Existencial | Razón      | Autoridad               | Lógica         | Experiencia   |
| **Flexibilidad** | Alta                 | Media      | Baja                    | Media          | Alta          |
| **Ejemplo**      | Libertad             | No mentir  | "Prohibido fumar"       | Reciprocidad   | Optimismo     |
| **Sanción**      | Interna (conciencia) | Moral      | Externa (multa/castigo) | Lógica         | Emocional     |
```

#### C) Resumen Memorable

```markdown
---

## 💡 RESUMEN MEMORABLE

**Piensa en un edificio:**

- 🏛️ **VALORES** = Los cimientos invisibles (lo que sostiene todo)
- 📚 **ÉTICA** = El plano arquitectónico (el diseño del bien)
- 📋 **NORMAS** = El reglamento de construcción (reglas específicas)
- 🧩 **PRINCIPIOS** = Las columnas estructurales (sostienen el peso)
- 🎨 **ACTITUDES** = La decoración interior (cómo se vive el espacio)

**En tu Proyecto de Vida:**

- Tus **VALORES** determinan QUÉ es importante
- Tu **ÉTICA** determina QUÉ está bien
- Las **NORMAS** determinan QUÉ se permite
- Tus **PRINCIPIOS** determinan CÓMO actuar
- Tus **ACTITUDES** determinan CÓMO te sientes haciéndolo
```

---

### 7. FORMATO MARKDOWN - CORRECCIONES

**Archivo:** `modulos/modulo_2/tema_2.1__mi_ecosistema__contenido.md`

**Error encontrado (línea 12):** Header vacío `#` antes de imagen

**Corrección aplicada:**

```markdown
# ANTES (incorrecto):

Tu entorno influye en tu crecimiento tanto como tu ADN.

#

![FODA Personal](../../media/brujula_foda.png)

# DESPUÉS (correcto):

Tu entorno influye en tu crecimiento tanto como tu ADN.

![FODA Personal](../../media/brujula_foda.png)
```

---

### 8. FORMATO CHECKBOX EN EVALUACIONES (11 archivos)

Convertir todas las opciones de respuesta en archivos `*_evaluacion.md` de formato simple a checkboxes:

**ANTES:**

```markdown
1. **Pregunta de ejemplo:**
   a) Opción A
   b) Opción B
   c) Opción C
   d) Opción D
```

**DESPUÉS:**

```markdown
1. **Pregunta de ejemplo:**
   - a) Opción A
   - b) Opción B
   - c) Opción C
   - d) Opción D
```

**Archivos modificados (11):**

- modulo_1. tema_1.1, 1.2, 1.3 (evaluacion.md)
- modulo_2: tema_2.1, 2.2, 2.3 (evaluacion.md)
- modulo_3: tema_3.1, 3.3 (evaluacion.md)
- modulo_4: tema_4.1, 4.2, 4.4 (evaluacion.md)

---

## RESUMEN DE CAMBIOS POR TIPO DE ARCHIVO

### Archivos `*_contenido.md` (13 archivos)

- ✅ Correcciones ortográficas (3 instancias)
- ✅ Sección "REFLEXIÓN FINAL" agregada
- ✅ Corrección formato Markdown (1 archivo)

### Archivos `*_ejercicios.md` (13 archivos)

- ✅ Tabla de rúbrica de 100 puntos
- ✅ Sección "REFLEXIÓN FINAL DEL EJERCICIO" con 4 preguntas
- ✅ Compromiso personal con firma
- ✅ Mensaje final de curso (solo tema 4.4)

### Archivos `*_evaluacion.md` (11 archivos)

- ✅ Formato checkbox en todas las opciones de respuesta

### Archivos de documentación

- ✅ README.md creado (253 líneas)

### Archivo de preconceptos

- ✅ modulo_0/tema_0.1_preconceptos.md enriquecido con:
  - Definiciones de Valores, Ética, Normas, Principios, Actitudes
  - Tabla comparativa
  - Resumen memorable

---

## ESTADÍSTICAS FINALES

- **Total de archivos modificados:** 41 archivos
- **Total de archivos creados:** 1 archivo (README.md)
- **Líneas agregadas:** ~483 líneas
- **Commits realizados:** 6 commits
- **Cambios ortográficos:** 3 correcciones
- **Cambios pedagógicos:** 26 archivos (rubrica + reflexiones)
- **Cambios de formato:** 12 archivos (11 evaluaciones + 1 contenido)

---

## PROMPT PARA REPLICAR EN OTRO PROYECTO

```
Tienes un curso educativo con múltiples módulos y temas. Cada tema tiene 4 archivos:
contenido.md, ejercicios.md, evaluacion.md, guion.md

Realiza las siguientes mejoras:

1. Crea README.md con badges, descripción, estructura de archivos, metodología y estadísticas

2. Revisa ortografía en todos los archivos *_contenido.md y corrige errores

3. Agrega al final de cada *_contenido.md:
   - Sección "REFLEXIÓN FINAL"
   - Pregunta de cierre personalizada
   - Acción concreta relacionada con el tema

4. Agrega al final de cada *_ejercicios.md:
   - Tabla de rúbrica de 100 puntos con 5 criterios
   - Sección "REFLEXIÓN FINAL DEL EJERCICIO" con 4 preguntas
   - Compromiso personal con espacio para firma y fecha

5. Convierte opciones de respuesta en *_evaluacion.md a formato checkbox:
   De: "a) Opción"
   A: "- a) Opción"

6. Enriquece glosario/preconceptos con definiciones detalladas de conceptos clave

7. Valida formato Markdown:
   - Sin headers vacíos (#)
   - Sin espacios incorrectos en enlaces
   - Tablas correctamente formateadas

8. Agrega mensaje final motivacional en el último ejercicio del curso

Mantén coherencia pedagógica y tono cercano apropiado para la audiencia objetivo.
```

---

## NOTAS IMPORTANTES

- ✅ Todos los cambios mantienen la estructura original de archivos
- ✅ No se eliminaron contenidos existentes
- ✅ Se respetó el tono pedagógico del curso
- ✅ Las rúbricas son consistentes en todos los temas
- ✅ El formato Markdown es compatible con GitHub
- ✅ Los checkboxes funcionan en visualizadores Markdown estándar

---

**Fin del documento de cambios realizados**
