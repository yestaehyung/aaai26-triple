# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for the TRIPLE (Theory-Driven Integration of Planned and Habitual Behaviors for LLM-based Personalization) research framework. The website showcases research presented at AAAI 2026 on integrating dual-process theory into LLM-based user modeling using Theory of Planned Behavior (TPB) and habit theory.

**Live Website**: https://yestaehyung.github.io/aaai26-triple

## Architecture

This is a static HTML website using the Bulma CSS framework with minimal JavaScript interactions:

- **Frontend Framework**: Pure HTML/CSS/JS with Bulma CSS framework
- **Structure**: Single-page application with sections for abstract, framework overview, main results, and profile examples
- **Styling**: Based on Bulma framework with custom CSS overrides in `static/css/index.css`
- **JavaScript**: Minimal interactivity using jQuery for navigation and image interpolation features
- **Images**: Research figures and diagrams stored in `static/images/`

## Key Files

- `index.html` - Main website content and structure
- `static/css/index.css` - Custom styling overrides
- `static/js/index.js` - Interactive features (navbar, carousel)
- `static/images/` - Research figures, tables, and diagrams
- `static/files/` - PDF files (paper and supplementary materials)
- `README.md` - Project documentation and citation information

## Development

Since this is a static website, development is straightforward:

1. **Local Development**: Open `index.html` directly in a browser or serve via any static file server
2. **Content Updates**: Edit `index.html` directly for text content changes
3. **Styling**: Modify `static/css/index.css` for visual changes
4. **Assets**: Add new images to `static/images/` and reference them in HTML

## Deployment

The website is deployed via GitHub Pages at https://yestaehyung.github.io/aaai26-triple. Any changes pushed to the main branch will automatically update the live site.

## Content Structure

The website follows an academic paper presentation format:

- Hero section with title, authors, and links to paper/code/supplementary materials
- Abstract highlighting dual-process theory integration
- Framework Overview section explaining:
  - Habitual Behavior Profile (automatic, routine behaviors)
  - Intentional Behavior Profile (TPB-based: attitude, subjective norm, perceived behavioral control)
  - Behavioral Rationale (synthesis of habit and intention)
- Main Results from LaMP benchmark evaluation
- Profile Example demonstrating habit-intention interaction
- BibTeX citation for AAAI 2026

## Citation Format

The website is licensed under Creative Commons Attribution-ShareAlike 4.0 and is adapted from the Nerfies project template.

## Github

When you are commiting, do not include Claude Code.
