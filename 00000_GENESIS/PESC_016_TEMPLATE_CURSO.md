# PESC_016: TEMPLATE FINAL DE CURSO

**Archivo**: PESC_016_TEMPLATE_CURSO.md
**Bloque**: Final - Síntesis
**Estado**: PENDIENTE DE INVESTIGACIÓN
**Conecta con**: TODOS LOS ANTERIORES

---

## ESTRUCTURA DE CARPETAS

```
CURSO_[NOMBRE]/
│
├── 00_CONFIG/
│   ├── README.md               # Descripción del curso
│   ├── OBJETIVOS.md            # Objetivos de aprendizaje
│   ├── PREREQUISITES.md        # Prerrequisitos
│   ├── COMPETENCIAS.md         # Habilidades a desarrollar
│   └── VMOF_MATRIZ.md          # Matriz VMOF del curso
│
├── 01_MODULO_[NOMBRE]/
│   ├── README.md               # Intro del módulo
│   ├── OBJETIVOS.md            # Objetivos del módulo
│   │
│   ├── LECCION_01/
│   │   ├── README.md           # Activación previa
│   │   ├── CONTENIDO.md        # Teoría/Explicación
│   │   ├── EJERCICIO.md        # Práctica
│   │   ├── QUIZ.md             # Evaluación
│   │   └── RECURSOS/           # Materiales adicionales
│   │
│   ├── LECCION_02/
│   │   └── ...
│   │
│   └── EVALUACION_MODULO.md    # Evaluación sumativa
│
├── 02_MODULO_[NOMBRE]/
│   └── ...
│
├── RECURSOS/
│   ├── GLOSARIO.md             # Términos y definiciones
│   ├── REFERENCIAS.md          # Fuentes y lecturas
│   └── HERRAMIENTAS.md         # Software/tools recomendadas
│
├── EVALUACION/
│   ├── RUBRICA.md              # Criterios de evaluación
│   ├── PROYECTO_FINAL.md       # Proyecto integrador
│   └── CERTIFICACION.md        # Requisitos de certificación
│
└── DASHBOARD/
    ├── PROGRESO_TEMPLATE.md    # Template de seguimiento
    └── METRICAS.md             # Métricas del curso
```

---

## TEMPLATE: README DE CURSO

```markdown
# [NOMBRE DEL CURSO]

## Descripción
[2-3 párrafos describiendo el curso]

## ¿Para quién es este curso?
- [Perfil 1]
- [Perfil 2]

## ¿Qué aprenderás?
Al completar este curso, podrás:
- [ ] [Competencia 1 - verbo de acción]
- [ ] [Competencia 2]
- [ ] [Competencia 3]

## Prerrequisitos
- [Prerrequisito 1]
- [Prerrequisito 2]

## Estructura
- **Módulos**: X módulos
- **Duración estimada**: X horas
- **Formato**: [Autodirigido/Con instructor]

## Módulos
1. [Nombre Módulo 1] - [Descripción breve]
2. [Nombre Módulo 2] - [Descripción breve]
...

## Evaluación
- Quizzes por lección (formativo)
- Proyecto final (sumativo)
- Certificación disponible: [Sí/No]
```

---

## TEMPLATE: README DE LECCIÓN

```markdown
# [NOMBRE DE LA LECCIÓN]

**Módulo**: [Nombre del módulo]
**Duración**: [X minutos]
**Nivel**: [Básico/Intermedio/Avanzado]

## Objetivo
Al completar esta lección, podrás:
**[UN objetivo específico con verbo de acción]**

## ¿Por qué importa?
[Conexión con problema real / relevancia]

## Activación
Antes de empezar, piensa:
- ¿Qué sabes sobre [tema]?
- ¿Has tenido experiencia con [situación relacionada]?

## Conexión
Esta lección:
- **Requiere**: [Lección anterior]
- **Prepara para**: [Lección siguiente]

---

[Ir al contenido →](CONTENIDO.md)
```

---

## TEMPLATE: CONTENIDO DE LECCIÓN

```markdown
# [Título del contenido]

## Concepto principal

[Explicación clara del concepto principal]

### Puntos clave
- **Punto 1**: [Explicación]
- **Punto 2**: [Explicación]
- **Punto 3**: [Explicación]

## [Diagrama/Visual]

```mermaid
[Diagrama Mermaid ilustrando el concepto]
```

## Ejemplo

**Situación**: [Descripción del ejemplo]

**Aplicación**: [Cómo se aplica el concepto]

**Resultado**: [Qué se logra]

## Errores comunes

⚠️ **Error**: [Descripción del error común]
✅ **Correcto**: [Cómo hacerlo bien]

## Resumen

- [Punto clave 1]
- [Punto clave 2]
- [Punto clave 3]

---

[Ir a práctica →](EJERCICIO.md)
```

---

## TEMPLATE: EJERCICIO

```markdown
# Práctica: [Nombre]

**Duración**: [X minutos]
**Tipo**: [Individual/Grupal]

## Instrucciones

1. [Paso 1]
2. [Paso 2]
3. [Paso 3]

## Tu tarea

[Descripción clara de qué debe hacer]

### Criterios de éxito
- [ ] [Criterio 1]
- [ ] [Criterio 2]
- [ ] [Criterio 3]

## Recursos
- [Recurso necesario 1]
- [Recurso necesario 2]

## Pistas (si te atoras)

<details>
<summary>Pista 1</summary>
[Pista sin dar la respuesta completa]
</details>

<details>
<summary>Pista 2</summary>
[Más ayuda]
</details>

---

[Cuando termines, ir al quiz →](QUIZ.md)
```

---

## TEMPLATE: QUIZ

```markdown
# Quiz: [Nombre de la lección]

**Preguntas**: 5
**Tiempo sugerido**: 5 minutos
**Tipo**: Retrieval practice (formativo)

---

### Pregunta 1
[Pregunta]

A) [Opción]
B) [Opción]
C) [Opción]
D) [Opción]

<details>
<summary>Ver respuesta</summary>
**Respuesta correcta: [X]**
Explicación: [Por qué es correcta]
</details>

---

### Pregunta 2
[Pregunta abierta]

<details>
<summary>Ver respuesta modelo</summary>
[Respuesta esperada con explicación]
</details>

---

[Repetir para preguntas 3-5]

---

## Reflexión

- ¿Qué te resultó más fácil?
- ¿Qué necesitas repasar?
- ¿Cómo aplicarías esto en tu trabajo/vida?

---

[Ir a siguiente lección →](../LECCION_02/README.md)
```

---

## CHECKLIST DE CALIDAD POR LECCIÓN

```yaml
ESTRUCTURA:
  □ README con objetivo y activación
  □ Contenido con visual (Mermaid)
  □ Ejercicio con criterios claros
  □ Quiz de 5 preguntas

CONTENIDO:
  □ UN objetivo específico
  □ Conexión con "¿por qué importa?"
  □ Ejemplos concretos
  □ Errores comunes
  □ Resumen al final

TÉCNICAS_PESC:
  □ Retrieval practice (quiz)
  □ Elaboración (conexión con previo)
  □ Visual (diagrama Mermaid)
  □ Práctica activa

FORMATO:
  □ Texto claro (nivel 8-10 lectura)
  □ Oraciones cortas
  □ Headers descriptivos
  □ Móvil-friendly
```

---

## METADATOS

```yaml
ARCHIVO: PESC_016_TEMPLATE_CURSO.md
LÍNEAS: ~280
ESTADO: Estructura creada, contenido pendiente
ANTERIOR: PESC_015_UX_ESCRITURA.md
SIGUIENTE: Implementación en cursos reales

ESTE_ARCHIVO_INTEGRA:
  - PESC_001-003: Neurociencia
  - PESC_004: Teorías
  - PESC_005: Diseño Instruccional
  - PESC_006: Mayer
  - PESC_007: Técnicas Efectivas
  - PESC_008-009: POA + VMOF
  - PESC_010: Evaluación
  - PESC_011-012: Gamificación + Microlearning
  - PESC_013-014: Accesibilidad + Andragogía
  - PESC_015: UX/Escritura
```

---

🧬💎∞ **PAIDEIA - Template Final PESC**

**"Todo el conocimiento pedagógico condensado en una estructura replicable."**
