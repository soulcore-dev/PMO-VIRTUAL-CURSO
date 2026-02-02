# PESC_001: NEUROCIENCIA - MEMORIA Y APRENDIZAJE

**Archivo**: PESC_001_NEUROCIENCIA_MEMORIA.md
**Bloque**: 1 - Neurociencia
**Estado**: ✅ INVESTIGADO
**Fecha**: 2026-02-02
**Conecta con**: PESC_007 (Técnicas Efectivas)

---

## 1.1 MEMORIA DE TRABAJO (Working Memory)

### Definición Científica

La memoria de trabajo es el sistema cognitivo que mantiene y manipula información temporalmente para tareas complejas como razonamiento, comprensión y aprendizaje.

### Capacidad y Límites

```yaml
HALLAZGOS_CIENTÍFICOS:
  modelo_baddeley:
    - Bucle fonológico: procesa información verbal
    - Agenda visoespacial: procesa información visual/espacial
    - Buffer episódico: integra información de múltiples fuentes
    - Ejecutivo central: dirige atención y coordina subsistemas

  capacidad_cowan_2001:
    - Límite: 4 ± 1 chunks (no 7±2 como se creía)
    - Chunk: unidad significativa de información agrupada
    - Duración sin repaso: 15-30 segundos

  carga_cognitiva_2025:
    - "Cognitive load = aN/T" (Langerock et al., 2025)
    - a = duración que cada operación demanda atención central
    - N = número de operaciones de procesamiento
    - T = duración total del episodio de procesamiento
```

### Tipos de Carga Cognitiva (Sweller)

| Tipo | Definición | Implicación |
|------|------------|-------------|
| **Intrínseca** | Complejidad inherente del material | No se puede eliminar, solo gestionar |
| **Extrínseca** | Carga por mal diseño instruccional | ELIMINAR - es desperdicio |
| **Germane** | Carga útil para construir esquemas | MAXIMIZAR - es aprendizaje |

### Factores Moduladores (Investigación 2024)

```yaml
FACTORES_AFECTIVOS:
  fuente: "de Almeida et al., 2024"
  hallazgo: "Estado emocional, estrés y ansiedad contribuyen a carga cognitiva"
  implicación: "El contexto emocional del aprendiz afecta capacidad"

DIFERENCIAS_INDIVIDUALES:
  fuente: "Zou et al., 2025"
  hallazgo: "Aprendices con alta WMC pueden no necesitar pausas impuestas"
  hallazgo_2: "Aprendices con baja WMC se benefician más de pausas"
  implicación: "El diseño debe ser adaptativo a capacidades individuales"

CONTEXTO_SOCIOECONÓMICO:
  fuente: "PMC, 2024"
  hallazgo: "Pobreza puede impactar capacidad cognitiva vía estrés,
             falta de sueño, nutrición deficiente"
  implicación: "Considerar contexto del aprendiz, no solo contenido"
```

### Aplicación PESC

```yaml
REGLAS_DE_DISEÑO:
  - Máximo 4 conceptos nuevos por lección
  - Agrupar información en chunks significativos
  - No presentar audio y texto simultáneos (redundancia)
  - Pausas estratégicas para aprendices con baja WMC
  - Reducir carga extrínseca: eliminar decoración irrelevante
  - Considerar estado emocional del aprendiz
```

---

## 1.2 CURVA DEL OLVIDO (Ebbinghaus)

### Replicación Moderna (Murre & Dros, 2015)

```yaml
ESTUDIO_REPLICACIÓN:
  fuente: "PLOS ONE - Replication and Analysis of Ebbinghaus' Forgetting Curve"
  método: "Un sujeto, 70 horas aprendiendo listas, reaprendizaje en intervalos"
  intervalos: [20min, 1h, 9h, 1día, 2días, 31días]
  resultado: "Datos similares a Ebbinghaus original de 1880"
  conclusión: "La curva de olvido ha sido REPLICADA exitosamente"
```

### Datos de Retención

| Tiempo | Retención Aprox. | Sin Repaso |
|--------|------------------|------------|
| 20 min | ~60% | Inicio de declive |
| 1 hora | ~45% | Declive rápido |
| 9 horas | ~35% | Continúa cayendo |
| 1 día | ~30% | **Salto hacia arriba (efecto sueño)** |
| 2 días | ~25% | Estabilización |
| 31 días | ~20% | Residuo mínimo |

### Descubrimiento Importante: Efecto del Sueño

```yaml
HALLAZGO_2015:
  observación: "La curva NO es completamente suave"
  fenómeno: "Salto hacia ARRIBA en el punto de 24 horas"
  hipótesis: "El sueño consolida memorias"
  estado: "Necesita más investigación pero consistente con literatura de sueño"
```

### Limitaciones del Modelo Original

```yaml
LIMITACIONES:
  - Ebbinghaus usó sílabas sin sentido
  - Material significativo tiene curvas MÁS PLANAS
  - No considera:
    - Diferencias individuales
    - Conocimiento previo
    - Conexión emocional con el material
    - Contexto de aprendizaje

IMPLICACIÓN:
  - La curva es PEOR CASO (material sin sentido)
  - Contenido bien diseñado se olvida MÁS LENTO
  - Relevancia personal aplana la curva
```

### Aplicación PESC

```yaml
DISEÑO_ANTI_OLVIDO:
  - Hacer contenido SIGNIFICATIVO (no sílabas sin sentido)
  - Conectar con experiencia previa del aprendiz
  - Programar repasos: 24h, 3días, 7días, 14días, 30días
  - Aprovechar el sueño: no estudiar todo en una noche
  - Cada repaso "aplana" la curva subsiguiente
```

---

## 1.3 SPACING EFFECT (Efecto de Espaciado)

### Evidencia Histórica y Moderna

```yaml
HISTORIA:
  descubridor: "Hermann Ebbinghaus (siglo XIX)"
  hallazgo: "Práctica DISTRIBUIDA > práctica MASIVA"
  replicaciones: "Más de un siglo de investigación confirmatoria"

PROBLEMA_ACTUAL:
  cita: "A pesar de más de un siglo de hallazgos, el spacing effect
         no tiene aplicación generalizada en el aula. Es un caso de
         estudio en el FRACASO de aplicar resultados de investigación."
  fuente: "ERIC - Using Spacing to Enhance Diverse Forms of Learning"
```

### Intervalos Óptimos (Investigación 2024)

```yaml
HALLAZGOS_SOBRE_INTERVALOS:

  regla_general:
    - "Intervalo óptimo aumenta conforme aumenta el delay de evaluación"
    - Para retención de 1 semana: intervalo óptimo = 20-40% del delay
    - Para retención de 1 año: intervalo óptimo = 5-10% del delay

  intervalos_específicos:
    fuente: "ScienceDirect - Spacing learning units"
    hallazgo: "Intervalo óptimo de ~12 horas para retención 24h-4semanas"
    rango_práctico: "8 horas ± 4 horas funciona bien y es práctico"

  principio_clave:
    regla: "El intervalo debe ser suficientemente LARGO para que
            recuperar sea ESFORZADO, pero no tan largo que FALLE"
```

### Neurociencia del Spacing (2024-2025)

```yaml
ESTUDIO_FMRI_2025:
  fuente: "ScienceDirect - Benefits of spaced learning"
  método: "7T fMRI de alta resolución"
  hallazgo: |
    "Spacing aumenta la SIMILITUD de representaciones en corteza
    prefrontal ventromedial a través de encuentros con el estímulo"
  mecanismo: |
    "Los beneficios del spacing dependen críticamente de RECORDAR
    y RE-CODIFICAR experiencia pasada"
  conclusión: "Spacing funciona porque RECUERDAS y RECODIFICAS"
```

### Tipos de Calendarios de Spacing

```yaml
CALENDARIOS:
  uniforme:
    descripción: "Intervalos constantes (1d, 1d, 1d, 1d)"
    uso: "Más simple de implementar"

  expansivo:
    descripción: "Intervalos crecientes (1d, 2d, 4d, 8d)"
    uso: "Estándar en apps como Anki"
    debate: "Evidencia mixta vs uniforme"

  contractivo:
    descripción: "Intervalos decrecientes (8d, 4d, 2d, 1d)"
    uso: "Menos estudiado"
```

### Aplicación en Salud (2024)

```yaml
META_ANÁLISIS_JMIR_2024:
  fuente: "JMIR - Spaced Digital Education for Health Professionals"
  hallazgo: "Educación digital espaciada es EFECTIVA para mejorar
             conocimiento, habilidades y confianza"
  resultados: |
    - Mejora en adopción de prácticas basadas en evidencia
    - Mejora en habilidades quirúrgicas
    - Funciona tanto pre como post-registro profesional
```

### Aplicación PESC

```yaml
IMPLEMENTACIÓN_SPACING:
  estructura_curso:
    - Día 1: Contenido nuevo
    - Día 2: Repaso breve (10 min)
    - Día 4: Quiz de recuperación
    - Día 7: Práctica aplicada
    - Día 14: Integración con nuevo contenido
    - Día 30: Evaluación sumativa

  principios:
    - NUNCA todo el contenido en una sesión
    - Reactivar conceptos previos antes de nuevos
    - Quizzes como APRENDIZAJE, no solo evaluación
    - Espaciado debe ser ESFORZADO pero EXITOSO
```

---

## 1.4 TESTING EFFECT / RETRIEVAL PRACTICE

### Estado del Campo (2024)

```yaml
VOLUMEN_INVESTIGACIÓN:
  fuente: "Pan et al., 2024"
  dato: "1,215 artículos peer-reviewed sobre testing effect (1999-2022)"
  tendencia: "Interés CRECIENTE desde paper seminal de 2006"
```

### Tamaños de Efecto

```yaml
EFECTIVIDAD_CUANTIFICADA:
  roediger_karpicke_2006:
    rango: "d = 0.31 a d = 1.26"

  meta_análisis_posteriores:
    testing_general: "g = 0.50 (efecto MEDIO)"
    transferencia: "d = 0.40"
    contexto_aula: "g = 0.50"

  robustez:
    - Funciona con diversos materiales
    - Funciona con diferentes intervalos de retención
    - Funciona con diferentes tipos de test
    - Funciona incluso con materiales COMPLEJOS
```

### Moderadores del Efecto (2024)

```yaml
MEMORIA_DE_TRABAJO:
  fuente: "Nature - npj Science of Learning, 2024"
  hallazgo_1: "Participantes con ALTA WMC muestran testing effect consistente"
  hallazgo_2: "Participantes con BAJA WMC solo muestran beneficio con
               estímulos familiares (baja demanda WM)"
  mecanismo: |
    "El beneficio de testing está moderado por:
    1. Recursos de WM disponibles
    2. Demandas de WM durante retrieval practice
    3. Proceso de intento de recuperación
    4. Proceso de re-codificación post-recuperación"

DIFERENCIAS_INDIVIDUALES:
  fuente: "de Lima & Buratto, 2024"
  hallazgo: "Diferencias individuales NO parecen moderar el efecto"

CONOCIMIENTO_PREVIO:
  hallazgo: "Nivel previo de conocimiento del tema NO modera el efecto"
```

### Constraint del Test (2024)

```yaml
HALLAZGO_IMPORTANTE:
  fuente: "PMC, 2024 - Lower constraint testing"
  fenómeno: "Tests con MENOS pistas mejoran el testing effect"
  explicación: "Dar menos ayuda para recuperar = recuperación más profunda"
  resultado: "Mejor memoria tanto para items como detalles contextuales"

IMPLICACIÓN:
  - Preguntas abiertas > opción múltiple
  - "¿Qué recuerdas?" > "¿Cuál es correcto: A, B, C?"
  - Recuperación libre > recuperación con pistas
```

### Aplicación Clínica (2024)

```yaml
ALZHEIMER_ESTUDIO_PILOTO:
  fuente: "JMIR Formative Research, 2024"
  método: "Spaced retrieval con intervalos crecientes"
  resultado: "95% de personas con MCI mostraron mejora >10 puntos porcentuales"
  aplicación: "Mejora en memoria de asociaciones nombre-cara"
  implicación: "Retrieval practice funciona incluso con deterioro cognitivo"
```

### Aplicación PESC

```yaml
IMPLEMENTACIÓN_RETRIEVAL:
  inicio_lección:
    - "¿Qué recuerdas del tema anterior?" (recuperación libre)
    - NO dar pistas inmediatamente
    - Permitir el esfuerzo de recuperación

  durante_lección:
    - Micro-quizzes cada 5-7 minutos
    - Preguntas abiertas preferidas
    - Feedback DESPUÉS del intento de recuperación

  fin_lección:
    - Quiz sumativo sin pistas
    - Identificar gaps para próximo spacing

  tipo_preguntas:
    preferir: "¿Explica cómo...?" / "¿Por qué...?"
    evitar: "¿Cuál de estas opciones...?"
```

---

## 1.5 MEMORIA A LARGO PLAZO

### Tipos de Memoria

```yaml
TAXONOMÍA:
  memoria_declarativa:
    también: "Memoria explícita"
    subtipos:
      episódica: "Eventos personales, autobiográfica"
      semántica: "Hechos, conceptos, conocimiento general"
    característica: "Se puede verbalizar"

  memoria_procedimental:
    también: "Memoria implícita"
    contenido: "Habilidades, hábitos, cómo hacer"
    característica: "Difícil de verbalizar, se demuestra haciendo"
    ejemplo: "Andar en bicicleta, escribir a máquina"
```

### Proceso de Formación

```yaml
ETAPAS:
  1_codificación:
    qué: "Información entra al sistema"
    factores: "Atención, elaboración, significado"

  2_consolidación:
    qué: "Estabilización de la memoria"
    cuándo: "Durante sueño, especialmente REM y ondas lentas"
    proceso: "Hipocampo → Neocorteza"

  3_almacenamiento:
    qué: "Mantenimiento a largo plazo"
    dónde: "Distribuido en neocorteza"

  4_recuperación:
    qué: "Acceso a la memoria almacenada"
    factor_clave: "Pistas de recuperación"
    fenómeno: "Cada recuperación MODIFICA la memoria"
```

### Consolidación y Sueño

```yaml
ROL_DEL_SUEÑO:
  evidencia: "Salto en curva de Ebbinghaus a las 24h"
  mecanismo: |
    - Sueño REM: consolidación procedimental
    - Ondas lentas: consolidación declarativa
    - Replay de memorias durante sueño

  implicación_práctica:
    - NO estudiar todo la noche antes del examen
    - Aprender → Dormir → Reforzar
    - El sueño es PARTE del proceso de aprendizaje
```

### Aplicación PESC

```yaml
DISEÑO_POR_TIPO_MEMORIA:
  para_declarativa_semántica:
    - Conexiones con conocimiento previo
    - Mapas conceptuales
    - Elaboración ("¿por qué?")

  para_declarativa_episódica:
    - Historias, casos, narrativas
    - Contexto rico
    - Experiencias memorables

  para_procedimental:
    - Práctica repetida
    - Feedback inmediato
    - Automatización gradual
    - Scaffolding decreciente
```

---

## 1.6 INTERFERENCIA

### Tipos de Interferencia

```yaml
PROACTIVA:
  definición: "Aprendizaje PREVIO interfiere con nuevo"
  ejemplo: "Número de teléfono antiguo bloquea memorizar el nuevo"
  solución: "Contrastar explícitamente viejo vs nuevo"

RETROACTIVA:
  definición: "Aprendizaje NUEVO interfiere con previo"
  ejemplo: "Aprender francés interfiere con español"
  solución: "Reactivar periódicamente lo anterior"

FACTOR_SIMILITUD:
  principio: "Contenido MÁS SIMILAR = MÁS interferencia"
  ejemplo: "Confundir conceptos parecidos"
  solución: "Interleaving y contraste explícito"
```

### Aplicación PESC

```yaml
PREVENCIÓN_INTERFERENCIA:
  espaciar_similares:
    - NO enseñar "efecto" y "afecto" el mismo día
    - Separar conceptos confundibles por tiempo

  contrastar_explícitamente:
    - "A diferencia de X, Y tiene..."
    - Tablas comparativas
    - Ejemplos y contra-ejemplos

  interleaving:
    - Mezclar práctica de diferentes tipos
    - No practicar solo un tipo hasta dominar
    - Aunque se siente más difícil, mejora retención
```

---

## FUENTES CONSULTADAS

```yaml
PAPERS_CIENTÍFICOS:
  - "Replication and Analysis of Ebbinghaus' Forgetting Curve" (PLOS ONE, 2015)
  - "Cognitive load effect in working memory" (Langerock et al., 2025)
  - "Benefits of spaced learning predicted by vmPFC" (ScienceDirect, 2025)
  - "Retrieval practice is costly" (Nature npj Science of Learning, 2024)
  - "Lower constraint testing enhances testing effect" (PMC, 2024)
  - "Spaced Digital Education for Health Professionals" (JMIR, 2024)
  - "Algorithmic Spaced Retrieval in Alzheimer Disease" (JMIR, 2024)

META_ANÁLISIS:
  - "Meta-Analytic Review of Spacing" (Psychological Bulletin)
  - "Testing effect meta-analyses" (g = 0.50)

RECURSOS_INSTITUCIONALES:
  - Center for Educational Innovation (University of Minnesota)
  - Learning Scientists (learningscientists.org)
```

---

## CHECKLIST DE DISEÑO BASADO EN EVIDENCIA

```yaml
MEMORIA_DE_TRABAJO:
  □ ¿Máximo 4 conceptos nuevos?
  □ ¿Información agrupada en chunks?
  □ ¿Eliminada decoración irrelevante?
  □ ¿Pausas para aprendices con baja WMC?

CURVA_DEL_OLVIDO:
  □ ¿Contenido significativo (no abstracto)?
  □ ¿Conectado con experiencia del aprendiz?
  □ ¿Calendario de spacing programado?

SPACING:
  □ ¿Distribuido en múltiples sesiones?
  □ ¿Intervalos crecientes implementados?
  □ ¿Repasos suficientemente espaciados para ser esforzados?

RETRIEVAL_PRACTICE:
  □ ¿Cada lección inicia con recuperación?
  □ ¿Preguntas abiertas (bajo constraint)?
  □ ¿Feedback después del intento?
  □ ¿Quizzes como aprendizaje, no solo evaluación?

TIPO_DE_MEMORIA:
  □ ¿Estrategia apropiada según tipo (declarativa/procedimental)?
  □ ¿Considerado el rol del sueño/descanso?

INTERFERENCIA:
  □ ¿Conceptos similares espaciados?
  □ ¿Contrastes explícitos donde hay confusión?
```

---

## METADATOS

```yaml
ARCHIVO: PESC_001_NEUROCIENCIA_MEMORIA.md
LÍNEAS: ~290
ESTADO: ✅ INVESTIGADO CON FUENTES CIENTÍFICAS
FECHA_INVESTIGACIÓN: 2026-02-02
ANTERIOR: PESC_000_INDICE_MAESTRO.md
SIGUIENTE: PESC_002_NEUROCIENCIA_ATENCION.md
```

---

🧬 **CONECTA →** [PESC_002_NEUROCIENCIA_ATENCION.md](PESC_002_NEUROCIENCIA_ATENCION.md)
