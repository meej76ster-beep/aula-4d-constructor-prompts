# Registro de cambios (Changelog)

Todos los cambios relevantes de **Aula 4D · Constructor de Prompts Pedagógicos con IA** se documentan en este archivo siguiendo el estándar [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y [Versionado Semántico (SemVer)](https://semver.org/lang/es/).

## [v2.2.1] - 2026-11-21

### Cambiado
- **Licenciamiento comercial por suscripción:** sustitución de la referencia anterior `CC BY-NC-SA 4.0` por **© 2026 Todos los derechos reservados · Licencia Comercial Propietaria por Suscripción (EULA)** en el pie de página de la aplicación y en `README.md`.

### Añadido
- **Archivo [`LICENSE`](./LICENSE):** documento legal con los términos de licencia propietaria por suscripción para **María Esther Espinoza Juárez · E-PARTNER CLASS**.

---

## [v2.2.0] - 2026-11-21

### Añadido
- **Identidad visual oficial de E-PARTNER CLASS:** integración de `LogoOficial_EpartnerClass.png` e `Icono_EpartnerClass.png` en barra superior, portada (`Hero`), pie de página y favicon oficial.
- **Soporte claro/oscuro e independencia offline:** contenedor `.logo-plate` con contraste cuidado en ambos temas y carga híbrida en Base64 para que el archivo HTML único siga funcionando 100 % sin conexión incluso fuera de la carpeta del proyecto.
- **Organización de activos del repositorio:** incorporación de `assets/logo-epartnerclass.png`, `assets/icono-epartnerclass.png` y `.gitignore` (resguardando `Imagen corporativa/` fuera del repositorio público).

---

## [v2.1.0] - 2026-11-20

### Corregido
- **Diagrama SVG del banner (`Portada`):** ampliación de `viewBox` a `460×320`, re-centrado del núcleo humano (`Criterio Docente`) y ensanchamiento simétrico de las cuatro tarjetas de `136 px` a `166 px` para evitar el desbordamiento del texto *«Contexto y andamiaje»* dentro del rectángulo amarillo (`D2 · Describir`).
- **Contraste en botones primarios:** sustitución de `✨` por `✦` en los botones amarillos de inicio rápido para asegurar lectura nítida sobre fondo `#F3BA40`.

### Añadido
- **Control de versiones del proyecto:** creación de `CHANGELOG.md`, metadato `<meta name="version" content="2.1.0">`, indicación discreta de versión en el pie de página y publicación de etiqueta anotada `v2.1.0` en Git.

---

## [v2.0.0] - 2026-11-20

### Cambiado
- **Rediseño integral UX/UI 2026 + ISO 9241:** eliminación de ruido visual mediante barra superior translúcida con 4 pestañas limpias (`Portada`, `Buenas prácticas`, `Ejemplos`, `Constructor`), uso puntual de la paleta **E-PARTNER CLASS** y revelación progresiva en acordeones opcionales.
- **Asistente guiado 1 paso a la vez (`Constructor`):** inicio 100 % en blanco con stepper de 6 pasos (`0 Encuadre → 1 Delegar → 2 Describir → 3 Discernir → 4 Diligencia → 5 Resultado`) y panel lateral deslizable de vista previa en tiempo real.

### Añadido
- **Selector flexible de participantes (Paso 0 · Encuadre):** tres modos seleccionables (*Entorno educativo* con 6 niveles y subniveles dinámicos, *Fuera del entorno escolar* con rangos/edades y ámbito no formal, y *Ambos: Nivel + Edad*).
- **Galería de ejemplos comparados:** tres casos completos (*Efecto invernadero*, *Salud comunitaria* y *Tutor socrático para adultos*) con contraste *Prompt genérico vs. Prompt 4D* y opción *Adaptar en el Constructor*.
- **Preparación para GitHub Pages:** incorporación de `index.html` y `README.md`.

---

## [v1.0.0] - 2026-11-20

### Añadido
- Primera versión funcional de **Aula 4D · Constructor de Prompts Pedagógicos con IA** como archivo HTML único 100 % autónomo con paleta **E-PARTNER CLASS**, cobertura de las 4D (Anthropic + Google for Education), marcos UNESCO / OCDE / UE & UNICEF, selector multiherramienta y estudio de resultado con exportación y sugerencias de uso.
