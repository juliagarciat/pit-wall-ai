# Pit Wall AI — Simulador de Estrategia F1

Aplicación de simulador de estrategia de carrera de Fórmula 1 en un único archivo `index.html` (HTML5 + CSS3 + JavaScript Vanilla).

## Reglas Estrictas del Proyecto
- **Archivo Único:** Toda la interfaz, estilos CSS y lógica JavaScript deben estar contenidos exclusivamente dentro de `index.html`.
- **Cero Dependencias:** Queda strictly prohibido usar frameworks o librerías externas (sin Bootstrap, Tailwind, React, Chart.js ni CDNs).
- **Aislamiento de Directorio:** No salir bajo ninguna circunstancia del directorio de trabajo del proyecto.
- **Idioma:** Todos los textos de la interfaz, comentarios del código y mensajes de error deben redactarse en español.
- **Validación de Entradas:** Validar rigurosamente los campos antes de calcular (vuelta actual <= vueltas totales, posición entre 1 y 20, deltas numéricos válidos).
- **Calidad de Código:** Funciones pequeñas, modulares, de responsabilidad única y con nombres descriptivos. Prohibido el uso de `eval()`.
- **Modelo Matemático de Físicas:** El cálculo del tiempo por vuelta debe aplicar la fórmula exacta:
  `tiempo_vuelta = tiempo_base + delta_compuesto + (degradacion * (edad_neumatico ^ 1.15)) - efecto_combustible`