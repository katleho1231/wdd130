# Copilot Instructions for WDD130 Codebase

## Overview
This codebase is a static website project for WDD 130 coursework. It consists of HTML, CSS, and image assets organized by week and topic. There is no build system, backend, or automated test workflow; all development is done directly in source files.

## Directory Structure
- `index.html`: Main landing page.
- `README.md`: Brief project description.
- `images/`: Global image assets.
- `styles/`: Global CSS styles.
- `week01/`, `week02/`, ...: Weekly folders containing HTML exercises, images, and styles for each topic.

## Key Patterns & Conventions
- **File Organization:**
  - Each week has its own folder with related HTML, images, and CSS files.
  - Images for a week are in `images/` subfolders within each week.
  - CSS for a week is in `styles/` subfolders within each week.
- **HTML/CSS:**
  - No frameworks or preprocessors are used; only vanilla HTML and CSS.
  - Use relative paths for images and styles (e.g., `images/abidjan-ivory-coast.jpeg`, `styles/box-model.css`).
  - Keep markup simple and semantic for educational clarity.
- **Naming:**
  - Filenames use lowercase and hyphens (e.g., `favorite-city.html`, `box-model-solution.css`).
  - Image files may have `.jpg`, `.jpeg`, `.png`, or `.webp` extensions.

## Developer Workflow
- **Editing:**
  - Open HTML files in a browser to preview changes.
  - Edit CSS and HTML directly; no build or deploy steps required.
- **Debugging:**
  - Use browser dev tools for layout and style debugging.
  - Check image and stylesheet paths carefully; broken links are common.
- **Adding Content:**
  - Place new exercises in the appropriate weekly folder.
  - Add images to the relevant `images/` subfolder.
  - Add styles to the relevant `styles/` subfolder.

## Examples
- To add a new HTML exercise for week 03:
  - Create `week03/new-exercise.html`.
  - Add supporting images to `week03/images/`.
  - Add styles to `week03/styles/`.
- To reference an image in HTML:
  ```html
  <img src="images/abidjan-ivory-coast.jpeg" alt="Abidjan Temple">
  ```

## No External Dependencies
- No npm, Python, or other package managers are used.
- No automated tests or CI/CD pipelines are present.

## Guidance for AI Agents
- Focus on clear, simple HTML/CSS edits and additions.
- Maintain the existing folder and naming conventions.
- Do not introduce frameworks, build tools, or backend code.
- Reference images and styles using correct relative paths.
- If unsure about file placement, follow the pattern used in previous weeks.
