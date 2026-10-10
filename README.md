# Umuseke Cafe - Landing Page Rebuild (Plain CSS vs. Tailwind CSS)

This repository contains two versions of the **Umuseke Cafe** landing page built as part of the Advanced Frontend Web Development coursework.

## Project Structure

* **`plain-css/`** — The initial landing page implementation built entirely with custom HTML and plain CSS (`style.css`).
* **`Tailwind-css/`** — The refactored landing page rebuilt completely using Tailwind CSS utility classes and compiled via the Tailwind CLI workflow.
* **`index.html`** — A root navigation portal allowing you to easily view and switch between both versions.

## Workflow Change Note

Transitioning from plain CSS to Tailwind CSS significantly impacted the development process:

* **Plain CSS Workflow:** 
  * Required writing individual rules, selectors, and layout properties from scratch inside a separate `style.css` file.
  * Involves constant context-switching between HTML markup and CSS style sheets to manage colors, spacing, and responsive media queries.
  * More prone to bloated stylesheets and maintaining custom class nomenclature.

* **Tailwind CSS Workflow:** 
  * Replaced custom stylesheets with utility classes applied directly within the HTML markup, speeding up UI composition.
  * Leveraged the Tailwind CLI compilation process (`tailwindcss -i src/tailwind.css -o dist/output.css --watch`) to generate optimized production stylesheets.
  * Utilized built-in design tokens, responsive breakpoints (`md:`, `lg:`), and state modifiers (`hover:`, `focus:`) for a more consistent and scalable design system.

## How to View Locally

1. Open the repository root folder in **Visual Studio Code**.
2. npm install and run dev
3. The localhost open and then we se a home page that have two button that drag user to a plain css or a tailwind css