# PESC_008: POA - PROGRAMACIÓN ORIENTADA AL APRENDIZAJE

**Archivo**: PESC_008_POA_FRAMEWORK.md
**Bloque**: 6 - Arquitectura Educativa
**Estado**: ✅ FRAMEWORK DEFINIDO
**Fecha**: 2026-02-03
**Conecta con**: PESC_009 (VMOF Educativo)

---

## CONCEPTO CENTRAL

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║   POA = Aplicar principios de Ingeniería de Software             ║
║         a la Arquitectura de Cursos Educativos                   ║
║                                                                   ║
║   "Si puedo diseñar software escalable y mantenible,             ║
║    puedo diseñar cursos escalables y mantenibles."               ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## TEMAS A INVESTIGAR

### 8.1 PRINCIPIOS SOLID → EDUCACIÓN

```yaml
S - SINGLE_RESPONSIBILITY:
  Software: Una clase, una responsabilidad
  Educación: Una lección, un objetivo

  Implementación:
    - [ ] Cada lección tiene UN objetivo principal
    - [ ] No mezclar múltiples competencias
    - [ ] Si necesitas más, divide en lecciones

  Aplicación_PESC:
    - Máximo 1-2 objetivos por lección
    - "Al completar esta lección, podrás [UNA cosa]"

O - OPEN/CLOSED:
  Software: Abierto para extensión, cerrado para modificación
  Educación: Base estable que puede extenderse

  Implementación:
    - [ ] Módulos base que no cambian
    - [ ] Extensiones opcionales (profundización)
    - [ ] No modificar lo fundamental para añadir

  Aplicación_PESC:
    - Lección base + "Para profundizar" opcional
    - Tracks adicionales sin modificar core

L - LISKOV_SUBSTITUTION:
  Software: Subclases sustituibles por superclase
  Educación: Módulos intercambiables del mismo nivel

  Implementación:
    - [ ] Diferentes caminos para mismo objetivo
    - [ ] Ejemplos sustituibles
    - [ ] Formatos alternativos (video, texto, audio)

  Aplicación_PESC:
    - Ofrecer contenido en múltiples formatos
    - Diferentes ejemplos según contexto del estudiante

I - INTERFACE_SEGREGATION:
  Software: Interfaces pequeñas y específicas
  Educación: Competencias bien definidas y específicas

  Implementación:
    - [ ] Habilidades atómicas, no genéricas
    - [ ] "Sabe programar" → "Sabe escribir un loop for"
    - [ ] Competencias verificables

  Aplicación_PESC:
    - Lista específica de "podrás hacer"
    - Cada habilidad es evaluable individualmente

D - DEPENDENCY_INVERSION:
  Software: Depender de abstracciones, no implementaciones
  Educación: Depender de conceptos, no de herramientas específicas

  Implementación:
    - [ ] Enseñar principios, no solo procedimientos
    - [ ] "Concepto de loop" antes de "for en Python"
    - [ ] Transferible entre contextos

  Aplicación_PESC:
    - Principio primero, herramienta después
    - "¿Por qué?" antes de "¿Cómo?"
```

### 8.2 PATRONES DE DISEÑO → EDUCACIÓN

```yaml
FACTORY:
  Software: Crear objetos sin especificar clase exacta
  Educación: Generar ejercicios/ejemplos según contexto

  Aplicación_PESC:
    - Generador de ejercicios por nivel
    - Ejemplos adaptados al área del estudiante

BUILDER:
  Software: Construir objeto complejo paso a paso
  Educación: Construir competencia compleja paso a paso

  Aplicación_PESC:
    - Skill tree visible
    - Cada paso construye sobre el anterior

OBSERVER:
  Software: Notificar cambios a dependientes
  Educación: Sistema de tracking de progreso

  Aplicación_PESC:
    - Notificaciones de progreso
    - Alertas de repaso (spacing)
    - Dashboard actualizado

STRATEGY:
  Software: Familia de algoritmos intercambiables
  Educación: Diferentes caminos de aprendizaje

  Aplicación_PESC:
    - Track rápido vs track profundo
    - Camino visual vs camino textual
    - Rutas según objetivo final

TEMPLATE_METHOD:
  Software: Esqueleto de algoritmo, pasos específicos variables
  Educación: Estructura fija de lección, contenido variable

  Aplicación_PESC:
    - Toda lección sigue: Activación → Contenido → Práctica → Evaluación
    - Contenido cambia, estructura no

COMPOSITE:
  Software: Tratar individual y grupo uniformemente
  Educación: Módulos compuestos de lecciones compuestas de conceptos

  Aplicación_PESC:
    - Curso > Módulo > Lección > Concepto
    - Misma estructura en todos los niveles

DECORATOR:
  Software: Añadir funcionalidad sin modificar original
  Educación: Añadir recursos sin cambiar lección base

  Aplicación_PESC:
    - Lección base + ejercicios extra (decorator)
    - Lección base + recursos avanzados (decorator)
```

### 8.3 POO → EDUCACIÓN

```yaml
CLASE = CONCEPTO:
  Propiedades:
    - [ ] Definición
    - [ ] Ejemplos
    - [ ] Aplicaciones
    - [ ] Errores comunes

  Métodos:
    - [ ] Ejercicios
    - [ ] Prácticas
    - [ ] Evaluaciones

  Constructor:
    - [ ] Activación de conocimiento previo
    - [ ] Prerrequisitos

HERENCIA = PRERREQUISITOS:
  - [ ] "Esta lección EXTIENDE [lección anterior]"
  - [ ] Conocimiento heredado del padre
  - [ ] No repetir lo que ya sabe (heredado)

POLIMORFISMO = CONTEXTOS:
  - [ ] Mismo concepto, diferente contexto
  - [ ] "Suma" en matemáticas vs en programación vs en contabilidad
  - [ ] Transferencia de aprendizaje

ENCAPSULAMIENTO = MÓDULOS:
  - [ ] Cada módulo es autocontenido
  - [ ] Interfaz clara (qué aprenderás, qué podrás hacer)
  - [ ] Implementación oculta (cómo se enseña internamente)

ABSTRACCIÓN = NIVELES:
  - [ ] Diferentes niveles de detalle
  - [ ] Vista de alto nivel primero
  - [ ] Profundizar según necesidad

COMPOSICIÓN = ESTRUCTURA:
  - [ ] Cursos compuestos de módulos
  - [ ] Módulos compuestos de lecciones
  - [ ] Lecciones compuestas de conceptos
  - [ ] Favorece composición sobre herencia
```

### 8.4 CLEAN ARCHITECTURE → CURSOS

```yaml
CAPAS:
  Presentación: Interfaz del curso (videos, texto, UI)
  Lógica: Estructura pedagógica (secuencia, evaluación)
  Datos: Contenido (conceptos, ejemplos, ejercicios)
  Persistencia: Tracking (progreso, notas, historial)

REGLA_DE_DEPENDENCIA:
  - Capas internas no conocen capas externas
  - Contenido no depende de cómo se presenta
  - Misma lógica, diferentes presentaciones

APLICACIÓN_PESC:
  - Contenido reutilizable en diferentes formatos
  - Separar qué enseñar de cómo presentarlo
```

---

## ESTRUCTURA POA DE UN CURSO

```yaml
CURSO (Aplicación):
  ├── config/
  │   ├── objectives.md      # Objetivos del curso
  │   ├── prerequisites.md   # Dependencias
  │   └── competencies.md    # Interfaces de habilidades
  │
  ├── modules/
  │   ├── module_01/
  │   │   ├── README.md      # Constructor (activación)
  │   │   ├── concepts/      # Clases (propiedades)
  │   │   ├── exercises/     # Métodos
  │   │   └── tests/         # Unit tests (evaluación)
  │   └── module_02/
  │       └── ...
  │
  ├── shared/
  │   ├── glossary.md        # Definiciones reutilizables
  │   └── templates/         # Plantillas
  │
  └── tests/
      └── integration/       # Tests de integración (proyecto final)
```

---

## FUENTES A CONSULTAR

```yaml
LIBROS:
  - [ ] "Clean Code" - Robert Martin
  - [ ] "Design Patterns" - Gang of Four
  - [ ] "Clean Architecture" - Robert Martin

ANALOGÍAS_A_DESARROLLAR:
  - [ ] Refactoring = Mejora de lecciones
  - [ ] Code Review = Peer review de contenido
  - [ ] Technical Debt = Deuda pedagógica
  - [ ] CI/CD = Mejora continua de cursos
```

---

## METADATOS

```yaml
ARCHIVO: PESC_008_POA_FRAMEWORK.md
LÍNEAS: ~280
ESTADO: ✅ FRAMEWORK DEFINIDO - Arquitectura original PESC
ANTERIOR: PESC_007_TECNICAS_EFECTIVAS.md
SIGUIENTE: PESC_009_VMOF_EDUCATIVO.md
```

---

🧬 **CONECTA →** [PESC_009_VMOF_EDUCATIVO.md](PESC_009_VMOF_EDUCATIVO.md)
