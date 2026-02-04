# PESC_015: UX EDUCATIVO Y ESCRITURA CLARA

**Archivo**: PESC_015_UX_ESCRITURA.md
**Bloque**: 10 - Aplicación
**Estado**: ✅ INVESTIGADO
**Fecha**: 2026-02-03
**Conecta con**: PESC_006 (Mayer), PESC_013 (Accesibilidad)

---

## 15.1 LEYES DE UX APLICADAS A EDUCACIÓN

### Ley de Fitts

```yaml
DEFINICIÓN:
  autor: "Paul Fitts (1954)"
  principio: |
    "El tiempo requerido para moverse a un objetivo depende
     de la distancia a él, pero se relaciona INVERSAMENTE
     con su tamaño"
  fórmula: "MT = a + b × log2(2D/W)"
  donde:
    MT: "Tiempo de movimiento"
    D: "Distancia al objetivo"
    W: "Ancho del objetivo"

IMPORTANCIA_HCI:
  fuente: "ISO 9241 (2002)"
  validación: |
    "Fitts' Law ha sido validada para:
     tablets, detección de gestos, movimientos oculares,
     touchpads, kinética de movimiento, y screen-edge pointing"

APLICACIÓN_EDUCATIVA:
  fuente: "ResearchGate"
  hallazgo: |
    "Investigación muestra que proyectos experimentando
     con leyes como Fitts son beneficiosos para estudiantes"

APLICACIÓN_PESC:
  botones_acción:
    tamaño: "Botones de acción primarios GRANDES"
    posición: "'Siguiente lección' en posición fácil de alcanzar"
    móvil: "Mínimo 44x44px para touch"

  navegación:
    prominencia: "Controles de navegación prominentes"
    cercanía: "Acciones frecuentes cerca del cursor/dedo típico"

  quizzes:
    opciones: "Áreas de clic/tap suficientes entre opciones"
    submit: "Botón de envío fácilmente accesible"
```

### Ley de Hick-Hyman

```yaml
DEFINICIÓN:
  autores: "William Hick & Ray Hyman (1952)"
  principio: |
    "El tiempo para tomar una decisión aumenta
     con el número y complejidad de opciones"
  fórmula: "RT = a + b × log2(n)"
  donde:
    RT: "Tiempo de reacción"
    n: "Número de opciones"

FUNDAMENTO:
  fuente: "Information Theory (Shannon & Weaver, 1949)"
  historia: |
    "En los 1980s, Card, Moran & Newell presentaron
     Hick y Fitts como principios de diseño para
     maximizar usabilidad en interfaces"

APLICACIÓN_PESC:
  navegación:
    principio: "Reducir opciones a lo ESENCIAL"
    ejemplo: "Menú principal con 4-7 opciones máximo"
    no: "No abrumar con 20 opciones"

  decisiones:
    caminos: "Máximo 3-4 caminos de aprendizaje"
    quizzes: "4-5 opciones por pregunta (no 8-10)"

  progresivo:
    técnica: "Progressive disclosure"
    qué: "Mostrar opciones avanzadas solo cuando relevantes"
```

### Principios Gestalt

```yaml
PRINCIPIOS_VISUALES:

PROXIMIDAD:
  principio: "Elementos cercanos se perciben como relacionados"
  aplicación_PESC:
    - "Agrupar contenido relacionado visualmente"
    - "Espacio entre secciones diferentes"
    - "Pregunta de quiz cerca de sus opciones"

SIMILITUD:
  principio: "Elementos similares se ven como grupo"
  aplicación_PESC:
    - "Consistencia visual en botones del mismo tipo"
    - "Mismo color para misma función"
    - "Iconografía consistente"

CONTINUIDAD:
  principio: "El ojo sigue líneas y curvas naturalmente"
  aplicación_PESC:
    - "Flujo de lectura claro (izquierda a derecha, arriba a abajo)"
    - "Barras de progreso continuas"
    - "Secuencia visual de pasos"

CIERRE:
  principio: "Completamos mentalmente formas incompletas"
  aplicación_PESC:
    - "Barras de progreso parcialmente llenas motivan a completar"
    - "Módulos con checkmarks visuales"

FIGURA_FONDO:
  principio: "Distinguimos objetos del fondo"
  aplicación_PESC:
    - "Contraste claro entre contenido y fondo"
    - "Modales que oscurecen el fondo"
    - "Focus visible en elementos activos"
```

### Jerarquía Visual

```yaml
PRINCIPIO:
  definición: |
    "Lo más importante debe ser más prominente.
     Tamaño, color, posición comunican importancia"

TÉCNICAS:
  tamaño: "Elementos más importantes más grandes"
  contraste: "Alto contraste para elementos clave"
  posición: "Información crítica arriba y a la izquierda"
  espacio: "Más espacio alrededor de elementos importantes"
  color: "Color de acento para CTAs"

APLICACIÓN_PESC:
  títulos:
    H1: "Título del módulo (más grande)"
    H2: "Sección principal"
    H3: "Subsección"
    consistencia: "Siempre la misma jerarquía"

  acciones:
    primaria: "Botón grande, color de acción"
    secundaria: "Menos prominente, outline o gris"
    terciaria: "Link de texto"

  contenido:
    concepto_clave: "Resaltado, bold, o caja destacada"
    texto_normal: "Sin énfasis especial"
    nota_al_pie: "Más pequeño, color sutil"
```

---

## 15.2 LEGIBILIDAD Y ESCRITURA CLARA

### Métricas de Legibilidad

```yaml
FLESCH_READING_EASE:
  origen: "Rudolph Flesch & John Kincaid (1975)"
  uso: |
    "Desarrollado bajo contrato para la Marina de EE.UU.
     Es la fórmula de legibilidad en inglés más utilizada"

  escala:
    90-100: "Muy fácil - 5° grado"
    80-89: "Fácil - 6° grado"
    70-79: "Bastante fácil - 7° grado"
    60-69: "Estándar - 8°-9° grado"
    50-59: "Bastante difícil - 10°-12° grado"
    30-49: "Difícil - Universitario"
    0-29: "Muy difícil - Posgrado"

FLESCH_KINCAID_GRADE_LEVEL:
  descripción: |
    "Produce scores correspondientes a niveles de grado de EE.UU.,
     aproximadamente equivalentes a años de educación"

META_PESC:
  target: "Grado 8-9 (Flesch-Kincaid)"
  razón: |
    "La mayoría de adultos en EE.UU. leen a nivel de 8° grado.
     Tu texto necesita estar en o debajo de ese nivel
     para que la mayoría lo entienda"
  audiencia_general: "Mantener scores arriba de 60 (Flesch Reading Ease)"

LIMITACIONES_2024:
  fuente: "arXiv (2024)"
  hallazgo: |
    "Métricas estáticas como Flesch-Kincaid son conocidas
     por ser medidas ruidosas de dificultad de texto.
     Fueron desarrolladas para explicaciones largas (libros),
     no para formatos de diálogo o microlearning"
  implicación: |
    "Usar como guía, no como verdad absoluta.
     Complementar con revisión humana"
```

### Plain Language (Lenguaje Claro)

```yaml
PRINCIPIOS:
  voz_activa:
    malo: "El concepto será explicado por el instructor"
    bueno: "El instructor explicará el concepto"
    por_qué: "Más directo, menos palabras, más claro"

  oraciones_cortas:
    target: "15-20 palabras promedio"
    regla: "Una idea por oración"
    técnica: "Si puedes dividir, divide"

  palabras_comunes:
    malo: "Utilizar" → "Usar"
    malo: "Implementar" → "Hacer"
    malo: "Facilitar" → "Ayudar"
    principio: "Palabra corta > palabra larga (si significa lo mismo)"

  evitar:
    - "Jerga innecesaria (definir si es necesaria)"
    - "Frases redundantes ('en este momento' → 'ahora')"
    - "Nominalizaciones (verbos convertidos en sustantivos)"
    - "Doble negación"

APLICACIÓN_INDUSTRIA:
  fuente: "HubSpot"
  hallazgo: |
    "Blog posts con Flesch-Kincaid Grade Level entre 6 y 7
     tienen mayores scores de legibilidad y reciben
     más shares en redes sociales y backlinks"
```

### Estructura del Texto

```yaml
PÁRRAFOS:
  longitud: "3-5 oraciones por párrafo"
  estructura: "Idea principal en primera oración"
  espacio: "Espacio visible entre párrafos"

HEADERS:
  función: "Organizan y permiten escaneo"
  características:
    descriptivos: "Indican contenido de la sección"
    jerárquicos: "H1 > H2 > H3 (no saltar niveles)"
    escaneable: "Usuario puede entender estructura sin leer todo"

LISTAS:
  cuando: "3+ elementos relacionados"
  tipo:
    numeradas: "Para secuencias/pasos"
    bullets: "Para elementos sin orden"
  beneficio: "Más fácil de escanear que párrafos"

ÉNFASIS:
  bold: "Conceptos clave (con moderación)"
  italics: "Términos nuevos, énfasis suave"
  mayúsculas: "EVITAR - se percibe como gritar"
  subrayado: "Evitar en web (se confunde con link)"
```

---

## 15.3 TONO Y VOZ

### Conversacional vs Formal

```yaml
EVIDENCIA_MAYER:
  principio: "Personalización (ver PESC_006)"
  hallazgo: |
    "Las personas aprenden MEJOR cuando palabras
     están en estilo CONVERSACIONAL
     en lugar de estilo formal"

IMPLEMENTACIÓN:
  pronombres:
    usar: "'Tú', 'nosotros', 'tu'"
    evitar: "'El estudiante', 'los participantes'"

  ejemplos:
    formal: "El estudiante deberá completar el ejercicio"
    conversacional: "Completa el ejercicio"

    formal: "Se recomienda que se preste atención"
    conversacional: "Presta atención a esto"

    formal: "Es importante mencionar que..."
    conversacional: "Ten en cuenta que..."

BALANCE_ANDRAGOGÍA:
  ver: "PESC_014"
  principio: |
    "Para adultos: conversacional pero profesional.
     No infantilizar, pero tampoco excesivamente académico"
```

### Empatía en Escritura

```yaml
PRINCIPIOS:

RECONOCER_DIFICULTAD:
  hacer: "'Es normal que esto sea confuso al principio'"
  no_hacer: "Asumir que todo es obvio"

CELEBRAR_PROGRESO:
  hacer: "'¡Bien hecho! Acabas de completar...'"
  momento: "Al final de módulos/logros significativos"
  precaución: "No en exceso (pierde significado)"

ORIENTAR_AL_ERROR:
  hacer: "'Si te equivocaste, revisa la sección X'"
  no_hacer: "'Incorrecto.'"
  feedforward: "'Para mejorar la próxima vez...'"

INCLUSIVIDAD:
  lenguaje: "Neutro en género cuando sea posible"
  ejemplos: "Diversos en nombres y contextos"
  asunciones: "No asumir contexto específico"
```

---

## 15.4 NAVEGACIÓN EDUCATIVA

### Wayfinding

```yaml
CONCEPTO:
  definición: |
    "El usuario siempre debe saber:
     1. Dónde está
     2. Cómo llegó ahí
     3. Cómo ir a otro lugar"

ELEMENTOS:
  breadcrumbs:
    formato: "Curso > Módulo > Lección"
    función: "Ubicación + navegación hacia arriba"

  mapa_del_curso:
    qué: "Vista general de estructura"
    estado: "Mostrar completado vs pendiente"
    acceso: "Siempre accesible"

  progreso:
    formato: "'Lección 3 de 10'"
    visual: "Barra de progreso"
    checkmarks: "En lecciones completadas"
```

### Controles de Navegación

```yaml
ESENCIALES:
  anterior_siguiente:
    posición: "Siempre visible, misma ubicación"
    claridad: "Claramente etiquetados"
    estado: "Deshabilitados si no aplica"

  índice:
    acceso: "Siempre accesible desde cualquier punto"
    mostrar: "Estructura con estado de completación"

  búsqueda:
    función: "Encontrar contenido específico"
    scope: "Dentro del curso"

  inicio:
    función: "'Volver al dashboard/inicio'"
    acceso: "Logo o botón de home"

CONSISTENCIA:
  principio: |
    "Controles en el MISMO lugar en TODAS las páginas.
     Comportamiento predecible reduce carga cognitiva"
```

### Progreso Visible

```yaml
IMPORTANCIA:
  motivación: "Sensación de avance evita abandono"
  orientación: "Saber cuánto falta"
  conexión_gamificación: "Ver PESC_011"

ELEMENTOS:
  barra_progreso:
    formato: "Visual + porcentaje"
    granularidad: "Por módulo y/o total"

  contadores:
    formato: "'Lección 3/10', 'Módulo 2/5'"

  checkmarks:
    en: "Lecciones/módulos completados"
    visual: "Verde o similar para completado"

  próximo_paso:
    qué: "Claramente indicar qué sigue"
    CTA: "'Continuar a Lección 4'"
```

---

## 15.5 DISEÑO MÓVIL

### Mobile-First para Educación

```yaml
CONTEXTO:
  tendencia: "Mayoría de consumo web es móvil"
  educación: "Microlearning especialmente móvil"
  ver: "PESC_012 para mobile learning"

CONSIDERACIONES:
  pantalla_pequeña:
    - "Un elemento principal por vez"
    - "Texto legible sin zoom (mínimo 16px)"
    - "Ancho de línea: 45-75 caracteres"

  conectividad:
    - "Contenido ligero, carga rápida"
    - "Opción de descarga offline"
    - "Guardado automático de progreso"

  interrupciones:
    - "Contenido auto-contenido"
    - "Fácil retomar donde quedó"
    - "No perder progreso si cierra app"

  touch_interface:
    - "Áreas de tap mínimo 44x44px"
    - "Espacio entre elementos clickeables"
    - "Gestos simples (no complejos)"
    - "No depender de hover"
```

### Responsive Design

```yaml
PRINCIPIOS:
  fluid_grids:
    - "Columnas que se adaptan"
    - "Una columna en móvil"
    - "Múltiples en desktop"

  flexible_images:
    - "Imágenes que escalan"
    - "max-width: 100%"
    - "No desbordan contenedor"

  media_queries:
    - "Breakpoints para diferentes tamaños"
    - "Layout adapta a dispositivo"

VIDEO:
  consideraciones:
    - "Considerar formato vertical para móvil"
    - "Subtítulos legibles en pantalla pequeña"
    - "Controles táctiles"
```

---

## 15.6 HERRAMIENTAS

### Testing de Legibilidad

```yaml
GRATUITAS:
  - "Hemingway App (hemingwayapp.com)"
  - "WebFX Readability Test"
  - "Readable.com (free tier)"

INTEGRADAS:
  - "Grammarly (incluye legibilidad)"
  - "Microsoft Word (estadísticas de legibilidad)"

MÉTRICAS_A_VERIFICAR:
  - "Flesch-Kincaid Grade Level (meta: 8-9)"
  - "Flesch Reading Ease (meta: >60)"
  - "Longitud promedio de oraciones"
  - "Uso de voz pasiva (%)"
```

### Testing de UX

```yaml
NAVEGACIÓN:
  test: "¿Usuario puede encontrar X en 3 clics?"
  método: "Tree testing, card sorting"

USABILIDAD:
  test: "¿Usuario puede completar tarea Y?"
  método: "Usability testing con usuarios reales"

ACCESIBILIDAD:
  ver: "PESC_013 para herramientas"
```

---

## CHECKLIST UX/ESCRITURA PESC

```yaml
ESCRITURA:
  □ ¿Oraciones de 15-20 palabras promedio?
  □ ¿Voz activa predominante?
  □ ¿Flesch-Kincaid Grade Level 8-9?
  □ ¿Jerga definida si es necesaria?
  □ ¿Tono conversacional pero profesional?
  □ ¿Párrafos de 3-5 oraciones?

NAVEGACIÓN:
  □ ¿Usuario sabe dónde está (breadcrumbs)?
  □ ¿Progreso visible (barra, %)?
  □ ¿"Siguiente" es obvio?
  □ ¿Controles consistentes en todas las páginas?
  □ ¿Mapa del curso accesible?

VISUAL:
  □ ¿Jerarquía clara (H1 > H2 > H3)?
  □ ¿Gestalt aplicado (proximidad, similitud)?
  □ ¿Consistente con otras lecciones?
  □ ¿Espacio en blanco suficiente?
  □ ¿Contraste adecuado?

MÓVIL:
  □ ¿Funciona en pantalla pequeña?
  □ ¿Botones suficientemente grandes (44x44px)?
  □ ¿Texto legible sin zoom?
  □ ¿No depende de hover?
  □ ¿Carga rápida?

FITTS_HICK:
  □ ¿Botones de acción grandes y accesibles?
  □ ¿Opciones reducidas a lo esencial?
  □ ¿Menú con máximo 4-7 opciones?
```

---

## FUENTES CONSULTADAS

```yaml
LEYES_UX:
  - "Fitts (1954) - Motor system research"
  - "ISO 9241 (2002) - HCI testing standards"
  - "Laws of UX (lawsofux.com)"
  - "NN/g - Fitts's Law and Its Applications in UX"
  - "Interaction Design Foundation - Fitts' Law"

LEGIBILIDAD:
  - "Flesch & Kincaid (1975) - Readability tests"
  - "arXiv (2024) - Beyond Flesch-Kincaid limitations"
  - "HubSpot - Readability and engagement research"
  - "Newcastle University - Digital Design Services"

RECURSOS:
  - "Hemingway App"
  - "Readable.com"
  - "WebFX Readability Test"
```

---

## METADATOS

```yaml
ARCHIVO: PESC_015_UX_ESCRITURA.md
LÍNEAS: ~480
ESTADO: ✅ INVESTIGADO CON FUENTES CIENTÍFICAS
FECHA_INVESTIGACIÓN: 2026-02-03
ANTERIOR: PESC_014_ANDRAGOGIA.md
SIGUIENTE: PESC_016_TEMPLATE_CURSO.md
```

---

🧬 **CONECTA →** [PESC_016_TEMPLATE_CURSO.md](../11_TEMPLATES/PESC_016_TEMPLATE_CURSO.md)
