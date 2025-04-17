
# SRU Global Logistics

A modern, responsive website for SRU Global Logistics, a company specializing in logistics, transport, and shipping services.

## Overview

This project is built with HTML, CSS (using Tailwind CSS), and vanilla JavaScript to create a fast, responsive, and user-friendly website for a logistics company.

## Features

- Responsive design that works on all devices
- Testimonial carousel with auto-slide functionality
- Mobile-friendly navigation menu
- Back-to-top button for better user experience
- Modern UI with Tailwind CSS

## Tech Stack

- HTML5
- CSS3 with Tailwind CSS v4.0
- Vanilla JavaScript
- NPM for package management

## Project Structure

```
sru-global/
├── css/
│   ├── input.css     # Tailwind input file
│   └── styles.css    # Compiled CSS
├── js/
│   └── main.js       # Main JavaScript file
├── package.json      # Project dependencies
├── package-lock.json # Dependency lock file
└── index.html        # Main HTML file
```
````

The MEAN stack references in the `.gitignore` file should be removed since they're not relevant to this project. Here's the corrected version:

````gitignore path=.gitignore mode=EDIT
# Dependencies
node_modules/
npm-debug.log
yarn-debug.log
yarn-error.log

# Environment variables
.env
.env.local
.env.*.local

# IDE - VSCode
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
.history/*

# System Files
.DS_Store
Thumbs.db

# Build output
/dist
