# PESC_013: ACCESIBILIDAD E INCLUSIÓN

**Archivo**: PESC_013_ACCESIBILIDAD.md
**Bloque**: 9 - Inclusión
**Estado**: ✅ INVESTIGADO
**Fecha**: 2026-02-03
**Conecta con**: PESC_015 (UX), PESC_006 (Mayer)

---

## 13.1 WCAG - ESTÁNDARES DE ACCESIBILIDAD

### Web Content Accessibility Guidelines

```yaml
WCAG_2.1:
  organización: "W3C (World Wide Web Consortium)"
  descripción: |
    "Recomendaciones para hacer contenido web más accesible
     a personas con discapacidades, incluyendo:
     - Ceguera y baja visión
     - Sordera y pérdida auditiva
     - Movimiento limitado
     - Discapacidades del habla
     - Fotosensibilidad
     - Discapacidades de aprendizaje y cognitivas"

WCAG_2.2:
  lanzamiento: "5 de octubre de 2023"
  estado: "Estándar W3C actual recomendado"
  novedades: "9 nuevos criterios de éxito"
  mejoras_en:
    - "Usuarios con discapacidades cognitivas"
    - "Baja visión"
    - "Usuarios móviles"
  estándar_legal: "ADA, Section 508, European Accessibility Act (EAA)"

WCAG_3.0:
  estado: "En desarrollo"
  esperado: "2026+"
```

### Principios POUR

```yaml
PRINCIPIOS_FUNDAMENTALES:

PERCEPTIBLE:
  significado: |
    "Información debe ser presentable en formas
     que usuarios puedan PERCIBIR"
  ejemplos:
    - "Texto alternativo para imágenes"
    - "Subtítulos para video"
    - "Contraste suficiente"
    - "No depender solo del color"

OPERABLE:
  significado: |
    "Interfaz debe ser navegable y usable"
  ejemplos:
    - "Navegación por teclado"
    - "Tiempo suficiente para completar tareas"
    - "Evitar contenido que cause convulsiones"
    - "Mecanismos de navegación claros"

COMPRENSIBLE:
  significado: |
    "Información y operación deben ser comprensibles"
  ejemplos:
    - "Texto legible y entendible"
    - "Comportamiento predecible"
    - "Ayuda para evitar errores"
    - "Instrucciones claras"

ROBUSTO:
  significado: |
    "Contenido compatible con tecnologías asistivas"
  ejemplos:
    - "HTML semántico válido"
    - "Nombres y roles para componentes"
    - "Compatibilidad con lectores de pantalla"
```

### Niveles de Conformidad

```yaml
NIVELES:
  A:
    descripción: "Mínimo"
    obligatorio: "Esencial para cualquier accesibilidad"
    criterios: "~30 criterios"

  AA:
    descripción: "Recomendado"
    estándar_legal: "Requerido por la mayoría de regulaciones"
    criterios: "~20 criterios adicionales"
    META_PESC: "Este es el nivel objetivo"

  AAA:
    descripción: "Máximo"
    uso: "Para audiencias específicas con necesidades altas"
    criterios: "~28 criterios adicionales"
    nota: "No siempre es posible para todo contenido"
```

### Regulaciones Educativas (2024-2025)

```yaml
ESTADOS_UNIDOS:
  regulación: "Title II ADA - Abril 2024"
  fuente: "Department of Justice (DOJ)"
  requerimiento: |
    "Instituciones educativas públicas deben asegurar
     que contenido digital sea accesible"
  estándar: "WCAG 2.1 Level AA"
  fecha_límite: "24 de abril de 2026"
  alcance: |
    "Sitios web, apps móviles, contenido de cursos,
     materiales en LMS deben ser accesibles"

ESTADOS_ESPECÍFICOS:
  illinois: "WCAG 2.1 AA para currículos de terceros"
  california: "AB 434 - WCAG 2.1 AA para sitios escolares"
  nueva_york: "Local Law 144 - WCAG 2.1 AA"

UNIÓN_EUROPEA:
  web_accessibility_directive: |
    "Contenido educativo de sector público
     debe cumplir WCAG 2.1 AA"
  european_accessibility_act:
    vigencia: "Junio 2025"
    estándar: "WCAG 2.2 AA"

IMPLICACIÓN_PESC:
  obligación: |
    "Toda plataforma educativa debe cumplir WCAG 2.1 AA
     como mínimo, preferiblemente WCAG 2.2 AA"
  responsabilidad: |
    "Tanto contenido creado internamente como
     materiales de terceros y LMS"
```

---

## 13.2 UNIVERSAL DESIGN FOR LEARNING (UDL)

### Framework UDL 3.0

```yaml
UDL_OVERVIEW:
  organización: "CAST"
  versión_actual: "3.0 (Julio 2024)"
  definición: |
    "Framework educativo basado en cómo aprenden los humanos,
     diseñado para crear experiencias de aprendizaje flexibles
     que acomoden diferencias individuales"

ACTUALIZACIONES_3.0:
  fuente: "CAST - Julio 30, 2024"
  proceso: |
    "40+ grupos focales, 1,100+ títulos investigados,
     revisiones de literatura extensivas"
  cambios_principales:
    - "Enfoque más basado en activos (asset-based)"
    - "Identidad como parte de variabilidad del aprendiz"
    - "Énfasis en interdependencia y aprendizaje colectivo"
    - "Cambio de lenguaje centrado en educador a centrado en aprendiz"

BASE_TEÓRICA:
  neurociencia: "Cómo funciona el cerebro en aprendizaje"
  ciencias_del_aprendizaje: "Investigación sobre cómo aprenden personas"
  psicología_cognitiva: "Procesamiento de información"
  raíces: |
    "Zona de Desarrollo Próximo (Vygotsky),
     scaffolding, mentoría, modelado
     (Piaget, Bruner, Ross, Wood, Bloom)"
```

### Los Tres Principios UDL

```yaml
PRINCIPIO_1_REPRESENTACIÓN:
  nombre: "Múltiples Medios de Representación"
  pregunta: "El 'QUÉ' del aprendizaje"

  guías:
    percepción:
      - "Opciones para personalizar visualización"
      - "Alternativas para información auditiva"
      - "Alternativas para información visual"

    lenguaje_símbolos:
      - "Clarificar vocabulario y símbolos"
      - "Clarificar sintaxis y estructura"
      - "Apoyar decodificación de texto, notación, símbolos"
      - "Promover comprensión entre idiomas"
      - "Ilustrar a través de múltiples medios"

    comprensión:
      - "Activar conocimiento previo"
      - "Resaltar patrones y relaciones"
      - "Guiar procesamiento de información"
      - "Maximizar transferencia y generalización"

  aplicación_PESC:
    - "Mismo contenido en texto, audio, video"
    - "Glosarios y definiciones accesibles"
    - "Resúmenes y organizadores previos"
    - "Subtítulos en todo video"

PRINCIPIO_2_ACCIÓN_EXPRESIÓN:
  nombre: "Múltiples Medios de Acción y Expresión"
  pregunta: "El 'CÓMO' del aprendizaje"

  guías:
    acción_física:
      - "Variar métodos de respuesta y navegación"
      - "Optimizar acceso a herramientas y tecnologías asistivas"

    expresión_comunicación:
      - "Usar múltiples medios para comunicación"
      - "Usar múltiples herramientas para construcción"
      - "Construir fluidez con niveles graduados de soporte"

    funciones_ejecutivas:
      - "Guiar establecimiento de metas apropiadas"
      - "Apoyar planificación y desarrollo de estrategias"
      - "Facilitar manejo de información y recursos"
      - "Mejorar capacidad para monitorear progreso"

  aplicación_PESC:
    - "Navegación por teclado completa"
    - "Diferentes formas de demostrar aprendizaje"
    - "Herramientas de planificación integradas"
    - "Proyectos con múltiples formatos de entrega"

PRINCIPIO_3_ENGAGEMENT:
  nombre: "Múltiples Medios de Engagement"
  pregunta: "El 'POR QUÉ' del aprendizaje"

  guías:
    interés:
      - "Optimizar elección individual y autonomía"
      - "Optimizar relevancia, valor y autenticidad"
      - "Minimizar amenazas y distracciones"

    esfuerzo_sostenido:
      - "Aumentar saliencia de metas y objetivos"
      - "Variar demandas y recursos para optimizar desafío"
      - "Fomentar colaboración y comunidad"
      - "Incrementar feedback orientado a maestría"

    autorregulación:
      - "Promover expectativas que optimicen motivación"
      - "Facilitar habilidades de coping y estrategias"
      - "Desarrollar auto-evaluación y reflexión"

  aplicación_PESC:
    - "Opciones de caminos de aprendizaje"
    - "Conexión con relevancia personal"
    - "Niveles de desafío variables"
    - "Herramientas de autoevaluación"
```

### Evidencia y Críticas (2024)

```yaml
EVIDENCIA_POSITIVA:
  fuente: "CAST"
  hallazgo: |
    "Cuerpo creciente de investigación afirma que UDL
     beneficia a aprendices de todas las edades y contextos
     en ambientes físicos y digitales"

META_ANÁLISIS:
  fuente: "Cogent Education (2023)"
  muestra: "13 estudios (2015-2021)"
  resultado: "Tamaño de efecto total = 3.56"
  precaución: "Considerable heterogeneidad evidente"

ANÁLISIS_CRÍTICO_2024:
  fuente: "Boysen (2024) - SAGE Journals"
  hallazgo: |
    "Estudios citados proporcionan POCA evidencia
     para afirmaciones sobre UDL"
  críticas:
    - "Mayoría de estudios NO ofrecieron elección a aprendices"
    - "Mayoría NO midieron aprendizaje"
    - "Ningún estudio relacionado con función cerebral"
  conclusión: |
    "Evidencia detrás de guías UDL de CAST es débil.
     Se necesita investigación básica y de implementación
     para establecer validez y efectividad del framework"

BRECHAS_IDENTIFICADAS:
  fuente: "British Journal of Educational Technology (2024)"
  hallazgo: |
    "A pesar del interés creciente en UDL en política educativa,
     hay brecha en base de evidencia sobre efectividad en
     resultados estudiantiles. Mayor foco ha sido en educación
     superior, con menos evidencia en educación secundaria"

POSICIÓN_PESC:
  enfoque: |
    "UDL proporciona framework útil para DISEÑO INCLUSIVO,
     pero las técnicas específicas deben basarse en
     evidencia directa (PESC_007) no solo en UDL"
  uso: "Guía de diseño, no dogma"
```

---

## 13.3 CONSIDERACIONES POR TIPO DE NECESIDAD

### Discapacidad Visual

```yaml
DALTONISMO:
  prevalencia: "~8% hombres, ~0.5% mujeres"
  principios:
    - "NO depender solo del color para transmitir información"
    - "Usar formas/patrones además de color"
    - "Contraste suficiente entre colores"
  herramientas_test: "Coblis, Color Oracle, Sim Daltonism"

BAJA_VISIÓN:
  principios:
    - "Texto escalable (no tamaño fijo)"
    - "Alto contraste disponible como opción"
    - "Fuentes legibles (sans-serif preferidas)"
    - "Mínimo 16px para texto base"
  WCAG: "Contraste mínimo 4.5:1 para texto normal (AA)"

CEGUERA:
  principios:
    - "Compatible con lectores de pantalla (JAWS, NVDA, VoiceOver)"
    - "Texto alternativo descriptivo en TODAS las imágenes"
    - "Estructura semántica (headings jerárquicos)"
    - "Skip links para navegación"
    - "ARIA labels donde necesario"
  test: "Usar lector de pantalla para verificar experiencia"
```

### Discapacidad Auditiva

```yaml
SORDERA_HIPOACUSIA:
  principios:
    subtítulos:
      - "Subtítulos en TODOS los videos"
      - "NO solo auto-generados (tienen errores)"
      - "Subtítulos sincronizados correctamente"
      - "Identificar quién habla si múltiples personas"
    transcripciones:
      - "Transcripción descargable disponible"
      - "Incluye descripciones de sonidos relevantes"
    visual:
      - "Contenido visual debe ser autosuficiente"
      - "No depender de audio para información crítica"

ADVERTENCIA_IA:
  fuente: "Columbia University guidance"
  hallazgo: |
    "Aunque existen herramientas de captioning con IA,
     los resultados 'frecuentemente contienen errores',
     se necesita revisión manual"
```

### Discapacidad Motora

```yaml
MOVILIDAD_LIMITADA:
  principios:
    teclado:
      - "100% navegable por teclado"
      - "Tab order lógico"
      - "Focus visible siempre"
    áreas_clic:
      - "Mínimo 44x44 píxeles (recomendación WCAG 2.2)"
      - "Espacio suficiente entre elementos clickeables"
    gestos:
      - "No depender de gestos complejos"
      - "Alternativas para drag-and-drop"
    tiempo:
      - "Tiempo suficiente para interacciones"
      - "Opción de extender tiempos límite"
```

### Discapacidad Cognitiva

```yaml
DISLEXIA:
  prevalencia: "5-10% de población"
  principios:
    tipografía:
      - "Fuentes sans-serif (Arial, Verdana, Open Dyslexic)"
      - "Espacio entre líneas de 1.5x o más"
      - "Ancho de línea máximo ~75 caracteres"
      - "Evitar texto justificado"
    estructura:
      - "Chunks de texto cortos"
      - "Párrafos de 3-5 oraciones"
      - "Headers claros y descriptivos"
      - "Bullet points para listas"
    contenido:
      - "Lenguaje claro y directo"
      - "Definir términos técnicos"
      - "Evitar idioms y metáforas complejas"

TDAH:
  principios:
    contenido:
      - "Contenido BREVE (microlearning)"
      - "Información más importante primero"
      - "Una idea por sección"
    diseño:
      - "Mínimas distracciones visuales"
      - "Sin auto-play de media"
      - "Estructura clara y predecible"
    engagement:
      - "Variedad de formatos"
      - "Interactividad frecuente"
      - "Breaks regulares"

TRASTORNO_ESPECTRO_AUTISTA:
  principios:
    comunicación:
      - "Lenguaje literal, no ambiguo"
      - "Instrucciones explícitas y específicas"
      - "Evitar sarcasmo e ironía no señalada"
    predictibilidad:
      - "Consistencia visual en todo el curso"
      - "Estructura predecible"
      - "Advertir cambios con anticipación"
    sensorial:
      - "Opciones para reducir estimulación"
      - "Control sobre audio/animaciones"
```

---

## 13.4 PRÁCTICAS DE ACCESIBILIDAD

### Texto y Tipografía

```yaml
CONTRASTE:
  WCAG_AA: "4.5:1 para texto normal, 3:1 para texto grande"
  WCAG_AAA: "7:1 para texto normal, 4.5:1 para texto grande"
  herramientas: "WebAIM Contrast Checker, Colour Contrast Analyser"

TAMAÑO:
  mínimo: "16px para texto base"
  escalable: "Debe funcionar hasta 200% zoom"

FUENTES:
  recomendadas: "Sans-serif (Arial, Verdana, Roboto, Open Sans)"
  evitar: "Fuentes decorativas, cursivas extensas"
  interlineado: "Mínimo 1.5x"
  ancho_línea: "45-75 caracteres óptimo"

LEGIBILIDAD:
  nivel: "Grado 8-9 de lectura (Flesch-Kincaid)"
  oraciones: "15-20 palabras promedio"
  párrafos: "3-5 oraciones"
  no_texto_en_imágenes: "Excepto logos"
```

### Imágenes y Media

```yaml
IMÁGENES:
  alt_text:
    informativas: "Alt text descriptivo que transmita el significado"
    decorativas: "alt='' (vacío) para ignorar en lectores"
    complejas: "Descripción larga además de alt corto"
  nunca: "Información solo en imágenes sin texto alternativo"

VIDEO:
  subtítulos:
    requerido: "Subtítulos para todo video con audio"
    calidad: "Revisados por humano, no solo auto-generados"
    formato: "Sincronizados, identificando hablantes"
  transcripción:
    requerido: "Disponible para descarga"
    contenido: "Incluye descripciones de sonidos relevantes"
  audio_descripción:
    cuando: "Si video tiene información visual importante"
    qué: "Narración de lo que se ve"
  controles:
    accesibles: "Controlables por teclado"
    personalizables: "Velocidad, volumen, subtítulos"

AUDIO:
  transcripción: "Siempre disponible"
  controles: "Play, pause, volumen por teclado"
```

### Navegación

```yaml
ESTRUCTURA:
  headings:
    jerárquicos: "H1 > H2 > H3 (no saltar niveles)"
    descriptivos: "Indican contenido de la sección"
  landmarks:
    uso: "header, nav, main, footer semánticos"
    ARIA: "Cuando HTML semántico no es suficiente"

WAYFINDING:
  breadcrumbs: "Curso > Módulo > Lección"
  skip_links: "'Ir al contenido principal'"
  mapa_sitio: "Estructura del curso visible"

FOCUS:
  visible: "SIEMPRE visible cuando elemento está enfocado"
  orden: "Tab order sigue orden lógico de lectura"
  trap: "NUNCA atrapar focus en un elemento"

FORMULARIOS_QUIZZES:
  labels: "Asociados programáticamente con inputs"
  errores: "Claros, específicos, junto al campo"
  tiempo: "Extendible si hay límite"
```

---

## 13.5 HERRAMIENTAS Y TESTING

### Herramientas de Evaluación

```yaml
AUTOMÁTICAS:
  WAVE: "WebAIM - extensión de navegador gratuita"
  axe: "Deque - extensión de navegador"
  Lighthouse: "Google - auditoría integrada en Chrome DevTools"
  ANDI: "SSA - bookmarklet gratuito"

MANUALES:
  lectores_pantalla:
    - "NVDA (Windows, gratuito)"
    - "JAWS (Windows, comercial)"
    - "VoiceOver (Mac/iOS, integrado)"
    - "TalkBack (Android, integrado)"

  navegación_teclado:
    test: "Navegar todo el sitio solo con teclado"
    keys: "Tab, Shift+Tab, Enter, Space, Flechas"

CONTRASTE:
  - "WebAIM Contrast Checker"
  - "Colour Contrast Analyser"
  - "Stark (Figma/Sketch plugin)"

DALTONISMO:
  - "Coblis Color Blindness Simulator"
  - "Sim Daltonism (Mac)"
```

### IA y Accesibilidad

```yaml
USOS_POSITIVOS:
  alt_text: |
    "ChatGPT/Bard pueden generar alt text candidato
     a partir de imágenes subidas"
  captioning: "Herramientas de captioning automático"
  simplificación: "Simplificar lenguaje complejo"

PRECAUCIONES:
  fuente: "Columbia University"
  advertencia: |
    "Resultados de IA frecuentemente contienen errores,
     se necesita revisión manual"
  uso: "IA como asistente, no como solución final"
```

---

## CHECKLIST DE ACCESIBILIDAD PESC

```yaml
POR_LECCIÓN:
  percepcible:
    □ ¿Videos tienen subtítulos de calidad?
    □ ¿Imágenes tienen alt text apropiado?
    □ ¿Contraste es suficiente (4.5:1)?
    □ ¿No depende solo del color?
    □ ¿Hay transcripciones disponibles?

  operable:
    □ ¿Navegable 100% por teclado?
    □ ¿Focus es visible?
    □ ¿Áreas de clic suficientes (44x44px)?
    □ ¿Tiempo suficiente para quizzes?

  comprensible:
    □ ¿Lenguaje es claro (nivel 8-9)?
    □ ¿Instrucciones son explícitas?
    □ ¿Errores se explican claramente?
    □ ¿Estructura es predecible?

  robusto:
    □ ¿HTML es semántico y válido?
    □ ¿Compatible con lectores de pantalla?
    □ ¿Funciona en dispositivos diversos?

POR_CURSO:
  □ ¿Múltiples formatos disponibles (UDL)?
  □ ¿Estructura de headings correcta?
  □ ¿Skip links implementados?
  □ ¿Cumple WCAG 2.1 AA como mínimo?
```

---

## FUENTES CONSULTADAS

```yaml
ESTÁNDARES:
  - "W3C - WCAG 2.1 Guidelines"
  - "W3C - WCAG 2.2 (October 2023)"
  - "AllAccessible - WCAG 2.2 Complete Guide 2025"

REGULACIONES:
  - "DOJ - Title II ADA Final Rules (April 2024)"
  - "Online Learning Consortium - Federal Requirements 2025"
  - "European Accessibility Act (EAA)"

UDL:
  - "CAST - UDL Guidelines 3.0 (July 2024)"
  - "CAST - Evidence & Benefits of UDL"
  - "Boysen (2024) - Critical analysis of UDL evidence - SAGE"
  - "Cogent Education (2023) - UDL meta-analysis"

RECURSOS_INSTITUCIONALES:
  - "Penn State Accessibility"
  - "MCIU Learning Network - WCAG for Educators"
  - "OHO - Accessibility in 2025"
```

---

## METADATOS

```yaml
ARCHIVO: PESC_013_ACCESIBILIDAD.md
LÍNEAS: ~520
ESTADO: ✅ INVESTIGADO CON FUENTES CIENTÍFICAS
FECHA_INVESTIGACIÓN: 2026-02-03
ANTERIOR: PESC_012_MICROLEARNING.md
SIGUIENTE: PESC_014_ANDRAGOGIA.md
```

---

🧬 **CONECTA →** [PESC_014_ANDRAGOGIA.md](PESC_014_ANDRAGOGIA.md)
