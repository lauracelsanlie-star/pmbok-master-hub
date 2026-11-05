# PMBOK® & PMP Prep Hub - Plataforma Interactiva de Gestión de Proyectos

> Proyecto final para el curso de **Introducción a la IA y Vibecoding** - Tecnolochicas TC PRO.

🔗 **Enlace al sitio web en vivo:** [https://lauracelsanlie-star.github.io/pmbok-master-hub/](https://lauracelsanlie-star.github.io/pmbok-master-hub/)

---

## 📌 Descripción del Proyecto
Plataforma web didáctica orientada a facilitar la comprensión y aplicación práctica del estándar **PMBOK®** (Project Management Body of Knowledge) del PMI:
- **Explorador por Fases:** Desglose interactivo de los 5 Grupos de Procesos (Inicio, Planificación, Ejecución, Monitoreo y Cierre) con sus respectivos objetivos, procesos clave, ITTOs y ejemplos prácticos del mundo real.
- **Tarjetas Didácticas (Flashcards):** Módulo interactivo con efecto de giro 3D para dominar conceptos críticos de la certificación PMP (Ruta Crítica, Fast Tracking vs Crashing, EDT/WBS, Scope Creep, etc.).
- **Calculadora de Valor Ganado (EVM):** Análisis cuantitativo de costo y cronograma con diagnóstico ejecutivo automatizado (CV, SV, CPI, SPI, EAC).
- **Asistente Mentor PMP con IA:** Chat interactivo asistido por IA para guiar en situaciones reales de gestión.
- **Formatos y Plantillas Descargables:** Descarga directa de artefactos oficiales (Project Charter, Registro de Riesgos y Solicitudes de Cambio).

---

## 🛠️ Herramientas y Stack Tecnológico
- **Desarrollo y Asistencia de IA:** Gemini (Google DeepMind) bajo metodología de *Vibecoding*.
- **Estructura y Maquetación:** HTML5 semántico y Tailwind CSS (CDN).
- **Interactividad y Componentes:** JavaScript Vanilla y Lucide Icons.
- **Control de Versiones y Despliegue:** GitHub y GitHub Pages.

---

## 🧠 Ingeniería de Prompts (Ejemplo Estructurado)
A continuación se documenta el prompt principal utilizado para generar la arquitectura del sitio, siguiendo la estructura requerida:

* **Rol:** Desarrollador web frontend senior y asesor certificado en Gestión de Proyectos (PMP).
* **Contexto:** Creación de una plataforma educativa e interactiva para estudiantes y profesionales que preparan su certificación PMP y necesitan comprender los procesos del PMBOK con ejemplos del mundo real.
* **Tarea:** Diseñar y programar una aplicación web interactiva autocontenida con explorador de procesos, flashcards didácticas 3D, calculadora EVM funcional con diagnósticos gerenciales y plantillas descargables.
* **Restricciones:** Paleta corporativa sobria (azul marino y gris pizarra), sin librerías pesadas, diseño responsive y código limpio documentado.

---

## 🐞 Depuración y Corrección de Errores con IA
Durante el ciclo de desarrollo se resolvieron iterativamente los siguientes aspectos técnicos:
1. **Manejo de división por cero en EVM:** Se integraron validaciones condicionales para evitar que la calculadora mostrara `Infinity` o `NaN` al recibir valores en cero en `PV` o `AC`.
2. **Efecto 3D de Flashcards:** Se configuraron las propiedades `transform-style: preserve-3d` y `backface-visibility: hidden` para garantizar compatibilidad fluida entre navegadores móviles y de escritorio.
