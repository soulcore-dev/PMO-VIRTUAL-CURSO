# PESC_009: VMOF EDUCATIVO - VISUAL MATRICIAL ORIENTADO A FLUJO

**Archivo**: PESC_009_VMOF_EDUCATIVO.md
**Bloque**: 6 - Arquitectura Educativa
**Estado**: ✅ FRAMEWORK DEFINIDO
**Fecha**: 2026-02-03
**Conecta con**: PESC_016 (Template Final)

---

## CONCEPTO CENTRAL

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║   VMOF EDUCATIVO = VMOF de SOUL CORE aplicado a Pedagogía       ║
║                                                                   ║
║   "Todo curso es una matriz de conocimientos con flujos          ║
║    de aprendizaje y celdas que se activan progresivamente."      ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## TEMAS A INVESTIGAR

### 9.1 ESTRUCTURA MATRICIAL EDUCATIVA

```yaml
EJE_Y - DIMENSIONES_DEL_CONOCIMIENTO:
  Basado en: Anderson & Krathwohl (revisión de Bloom)

  Niveles:
    - [ ] Factual: Hechos, terminología, detalles
    - [ ] Conceptual: Categorías, principios, teorías
    - [ ] Procedimental: Técnicas, métodos, habilidades
    - [ ] Metacognitivo: Autoconocimiento, estrategias

EJE_X - NIVELES_DE_DOMINIO:
  Basado en: Bloom revisado + SOLO Taxonomy

  Niveles:
    - [ ] Reconocer: Identificar, recordar (pasivo)
    - [ ] Reproducir: Ejecutar con guía (guiado)
    - [ ] Producir: Crear sin guía (autónomo)
    - [ ] Transferir: Aplicar en nuevo contexto (experto)

CELDA = PUNTO_DE_APRENDIZAJE:
  Ubicación: [Dimensión, Nivel]
  Ejemplo: [Procedimental, Producir] = "Escribir código sin ayuda"
```

### 9.2 MATRIZ VMOF DE UN MÓDULO

```
                 │ Reconocer  │ Reproducir │ Producir  │ Transferir │
─────────────────┼────────────┼────────────┼───────────┼────────────┤
FACTUAL          │ Quiz       │ Completar  │ Generar   │ Aplicar    │
(términos)       │ términos   │ frases     │ ejemplos  │ a nuevo    │
─────────────────┼────────────┼────────────┼───────────┼────────────┤
CONCEPTUAL       │ Identificar│ Explicar   │ Comparar  │ Diseñar    │
(principios)     │ conceptos  │ con        │ y crear   │ nuevos     │
                 │            │ palabras   │           │ marcos     │
─────────────────┼────────────┼────────────┼───────────┼────────────┤
PROCEDIMENTAL    │ Ver demo   │ Seguir     │ Ejecutar  │ Adaptar a  │
(habilidades)    │            │ tutorial   │ solo      │ problema   │
                 │            │            │           │ nuevo      │
─────────────────┼────────────┼────────────┼───────────┼────────────┤
METACOGNITIVO    │ Tips de    │ Aplicar    │ Crear     │ Enseñar    │
(aprender a      │ estudio    │ estrategia │ plan      │ a otros    │
aprender)        │            │            │ propio    │            │
─────────────────┴────────────┴────────────┴───────────┴────────────┘
```

### 9.3 CRITERIOS DE ACTIVACIÓN DE CELDA

```yaml
FÓRMULA_PESC:
  Score = Comprensión + Práctica + Conexión + Retención

  Comprensión (0-5): ¿Puede explicarlo?
  Práctica (0-5): ¿Puede hacerlo?
  Conexión (0-5): ¿Lo relaciona con otros conceptos?
  Retención (0-5): ¿Lo recuerda después de tiempo?

ESTADOS_DE_CELDA:
  Score < 8:   🔴 NO_DOMINA
    - Acción: Repetir, más práctica
    - No avanzar a siguiente nivel

  Score 8-12:  🟡 EN_PROGRESO
    - Acción: Reforzar, ejercicios adicionales
    - Puede avanzar con supervisión

  Score 13-16: 🟢 DOMINA
    - Acción: Avanzar al siguiente nivel
    - Puede hacer solo

  Score 17-20: ⭐ MAESTRÍA
    - Acción: Puede enseñar a otros
    - Listo para transferencia
```

### 9.4 TIPOS DE FLUJO EN VMOF EDUCATIVO

```yaml
FLUJO_SECUENCIAL:
  Descripción: Lineal, un tema después de otro
  Uso: Contenido con prerrequisitos estrictos
  Diagrama:
    A → B → C → D

FLUJO_PARALELO:
  Descripción: Múltiples tracks simultáneos
  Uso: Contenido independiente que converge
  Diagrama:
    A → B ─┐
           ├→ E (Integración)
    C → D ─┘

FLUJO_CONDICIONAL:
  Descripción: Caminos según prerrequisitos/nivel
  Uso: Rutas adaptativas
  Diagrama:
    ¿Prerrequisito?
      │
      ├─ Sí → Avanzar
      └─ No → Reforzar → ¿Prerrequisito?

FLUJO_CÍCLICO (Spacing):
  Descripción: Repasos periódicos
  Uso: Retención a largo plazo
  Diagrama:
    Aprender → 1d → 3d → 7d → 30d
                         ↑
                         └─────────────┘

FLUJO_ADAPTATIVO:
  Descripción: Ajuste dinámico según desempeño
  Uso: Personalización
  Diagrama:
    Evaluación → ¿Score?
                   │
      ├─ Bajo → Reforzar → Re-evaluar
      ├─ Medio → Práctica adicional
      └─ Alto → Avanzar / Profundizar
```

### 9.5 VISUALIZACIÓN VMOF

```yaml
HERRAMIENTA: Mermaid (nativo de SOUL CORE)

DIAGRAMAS_A_USAR:
  - graph: Flujos y dependencias
  - flowchart: Procesos de decisión
  - gantt: Timeline de módulos
  - mindmap: Mapa de conceptos
  - stateDiagram: Estados del estudiante

DASHBOARD_DE_PROGRESO:
  - Matriz coloreada (🔴🟡🟢⭐)
  - % de celdas activadas
  - Próximas celdas a activar
  - Repasos pendientes
```

### 9.6 INTEGRACIÓN VMOF + OTRAS TÉCNICAS

```yaml
VMOF + BLOOM:
  - Eje X incluye niveles de Bloom
  - Cada celda tiene verbo de Bloom asociado

VMOF + SPACING:
  - Flujo cíclico para cada celda dominada
  - Calendario automático de reactivación

VMOF + RETRIEVAL:
  - Cada celda tiene su quiz de recuperación
  - Score incluye retrieval exitoso

VMOF + POA:
  - Celda = Método de una clase
  - Flujo = Herencia y dependencias
  - Dashboard = Observer pattern
```

---

## PLANTILLA DE DASHBOARD ESTUDIANTE

```yaml
MÓDULO: [Nombre]
FECHA: [Fecha]
ESTUDIANTE: [ID]

MATRIZ_DE_PROGRESO:
┌────────────┬────────────┬────────────┬────────────┬────────────┐
│            │ Reconocer  │ Reproducir │ Producir   │ Transferir │
├────────────┼────────────┼────────────┼────────────┼────────────┤
│ Factual    │ ⭐ 18/20   │ 🟢 14/20   │ 🟡 10/20   │ ⬜ -       │
├────────────┼────────────┼────────────┼────────────┼────────────┤
│ Conceptual │ 🟢 15/20   │ 🟡 11/20   │ ⬜ -       │ ⬜ -       │
├────────────┼────────────┼────────────┼────────────┼────────────┤
│ Procedural │ 🟢 16/20   │ 🟡 9/20    │ ⬜ -       │ ⬜ -       │
├────────────┼────────────┼────────────┼────────────┼────────────┤
│ Metacog.   │ 🟡 12/20   │ ⬜ -       │ ⬜ -       │ ⬜ -       │
└────────────┴────────────┴────────────┴────────────┴────────────┘

PRÓXIMAS_CELDAS: [Conceptual, Reproducir], [Procedural, Reproducir]
REPASOS_PENDIENTES: [Factual, Reconocer] - hace 7 días
PROGRESO_TOTAL: 6/16 celdas (37.5%)
```

---

## METADATOS

```yaml
ARCHIVO: PESC_009_VMOF_EDUCATIVO.md
LÍNEAS: ~270
ESTADO: ✅ FRAMEWORK DEFINIDO - Matriz VMOF original PESC
ANTERIOR: PESC_008_POA_FRAMEWORK.md
SIGUIENTE: PESC_010_EVALUACION.md
```

---

🧬 **CONECTA →** [PESC_010_EVALUACION.md](PESC_010_EVALUACION.md)
