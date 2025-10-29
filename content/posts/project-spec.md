---
title: "Project Specification for this Website"
date: 2025-10-29T10:00:00-05:00
draft: false
---

## Project Overview

This project is a personal blog website built with the Hugo static site generator and styled with Tailwind CSS. The website is designed to be a simple, clean, and responsive blog that is easy to maintain and update.

## Key Technologies

*   **Hugo:** A fast and flexible static site generator written in Go.
*   **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
*   **PostCSS:** A tool for transforming CSS with JavaScript plugins.
*   **Autoprefixer:** A PostCSS plugin to add vendor prefixes to CSS.
*   **npm:** A package manager for JavaScript.

## Project Structure

The project follows a standard Hugo project structure:

*   `archetypes`: Contains templates for new content files.
*   `assets`: Contains the site's assets, such as CSS and JavaScript.
*   `content`: Contains the site's content, written in Markdown.
*   `layouts`: Contains the site's templates, written in HTML.
*   `static`: Contains static files, such as images and fonts.

## Build Process

The website is built using a combination of Hugo and npm scripts. The `npm run build:css` script uses the Tailwind CSS CLI to build the CSS, and the `hugo` command builds the website.
