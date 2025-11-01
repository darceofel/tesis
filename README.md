# Plantilla de Tesis (LaTeX)

Este repositorio contiene los fuentes LaTeX para una tesis y una presentación, organizados para que puedas reutilizarlos como plantilla para tu propio trabajo académico.

Resumen rápido:

- Proyecto principal de tesis: `texProject/` (archivo principal: `texProject/main.tex`).
- Presentación (diapositivas): `texPresentation/` (archivo principal: `texPresentation/main.tex`).
- Bibliografía: `texProject/referencias.bib`.

Cómo usarlo (rápido):

1. Instala una distribución LaTeX (por ejemplo MacTeX o TeX Live).
2. Abre una terminal y sitúate en la carpeta `texProject/` o `texPresentation/`.
3. Compila con `latexmk -pdf main.tex` (recomendado) o el flujo clásico `pdflatex` → `biber` → `pdflatex` (si usas BibLaTeX/Biber).

Requisitos recomendados

- Una distribución LaTeX reciente (MacTeX en macOS o TeX Live en Linux/Windows).
- `latexmk` y `biber` si usas el flujo automático.

Enlaces útiles que incluí originalmente

- [Cómo instalar LaTeX (video guía)](https://www.youtube.com/watch?v=Mty0vHb0knI)
- [Autenticación/instalación de GitHub CLI (gh)](http://cli.github.com/)

Estructura del repositorio

- `texProject/` — Fuentes de la tesis (capítulos, figura, bibliografía). Edita `main.tex` para personalizar la portada y metadatos.
- `texPresentation/` — Fuentes para una presentación (Beamer u otra clase).

Usar esto como plantilla para tu tesis

- Haz una copia del folder `texProject/` o clona el repositorio y trabaja en una rama nueva.
- Actualiza `main.tex` (título, autor, universidad, fecha) y la portada correspondiente.
- Sustituye `referencias.bib` por tu archivo de bibliografía o añádelo en formato BibTeX/BibLaTeX.
- Compila varias veces hasta que las referencias y el índice queden bien.

Contacto y licencia

Si usas esta plantilla para tu tesis, cita la fuente y mantén las referencias apropiadas. Este repositorio está pensado para uso académico y personal; adapta la licencia a tu preferencia si vas a redistribuirlo (por ejemplo MIT o CC-BY).

Si quieres que añada instrucciones más detalladas (por ejemplo, pasos exactos para macOS, Docker, o CI de GitHub Actions para compilar PDFs), dime qué formato prefieres y lo añado.

---

(Versión breve del README actualizada para que sea fácil de entender y usar como plantilla de tesis.)
