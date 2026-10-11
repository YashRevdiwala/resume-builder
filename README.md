# Resume Builder

A lightweight, browser-based resume builder for creating, editing, and printing a polished resume from structured JSON data.

## Overview

This project is a static web app built with vanilla HTML, CSS, and JavaScript. It lets you:

- edit resume sections in a live sidebar
- update contact details, skills, experience, projects, and education
- import/export the resume as JSON
- reset to the default profile
- print the resume as a PDF with print-friendly styling
- persist changes in local browser storage

## Project structure

- [index.html](index.html) — page structure and the editor sidebar
- [script.js](script.js) — rendering logic, data handling, import/export, and state management
- [styles.css](styles.css) — visual design, layout, responsive behavior, and print rules
- [data.json](data.json) — default resume content used by the app

## Features

- Live resume preview with sidebar editor controls
- JSON-based source data for easy editing and export
- Offline-safe fallback data when the JSON file cannot be fetched
- Print-ready layout using CSS print styles
- Local storage persistence for custom edits
- Responsive design for browser preview and PDF export

## Notes

- There is no backend, database, or build step.
- The app is intentionally dependency-free and runs directly in a browser.
- The default resume data lives in [data.json](data.json), and the fallback data is mirrored in [script.js](script.js).
