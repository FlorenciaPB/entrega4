

Este proyecto explora la transformación de información visual y estadística en experiencia sonora interactiva utilizando tecnologías web modernas como **Web Audio API** y elementos multimedia HTML5.



📋 Descripción del Proyecto

El módulo se compone de dos herramientas interactiva de sonificación:

 1. 🎨 Sonificador de Imágenes (Sintetizador Interactivo)
Convierte los valores cromáticos (RGB) de una imagen cargada por el usuario en parámetros musicales en tiempo real:
- **Rojo (R) → Volumen:** Mapea la intensidad cromática con la amplitud y fuerza de ataque de la nota
- **Verde (G) → Frecuencia / Nota:** Mapea el tono hacia notas musicales cuantizadas en una **Escala Pentatónica Mayor** (C3 a C6) para mantener armonía constante sin disonancias.
- **Azul (B) → Timbre / Sustain:** Controla el filtro paso bajo (*lowpass*) y el tiempo de resonancia (*decay*), definiendo si el tono del piano suena suave, cálido o brillante.

 2. 📊 Sonificador de Datos Académicos en Chile
Transformación sonora de datos estadísticos nacionales sobre la distribución de académicos en Chile por sexo (femenino y masculino), nivel profesional, técnico superior y técnico medio.
- **Audio generado:** Pista de audio compuesta mediante sonificación de datos.


 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Interfaz retro-consola responsiva construida con tipografía *Fredoka* y diseño basado en CSS Grid / Flexbox.
- **JavaScript (ES6+):** Manipulación de Canvas 2D (`getImageData`) y eventos del cursor.
- **Web Audio API:** Síntesis de audio en tiempo real mediante osciladores (`triangle`, `sine`), filtros `biquadFilter` y nodos de ganancia (`gainNode`) con envolvente exponencial.

