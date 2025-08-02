# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Ambrose Canvas, a marine canvas solutions company. The site features a modern, responsive design showcasing services, gallery, and contact information.

## Architecture

- **Static HTML/CSS/JS**: Single-page application with no build process
- **Frontend Structure**:
  - `index.html`: Main page with hero section, services grid, image gallery, and contact modal
  - `script.js`: Interactive functionality including gallery navigation, modal handling, form validation, and scroll animations
  - `styles.css`: Responsive styling with CSS custom properties, animations, and mobile-first design

## Development

Since this is a static website with no build tools or package management:

- **Local Development**: Open `index.html` directly in a browser or use a local server
- **No Build Process**: Files can be edited directly and refreshed in browser
- **No Dependencies**: Pure vanilla HTML/CSS/JavaScript with no external libraries

## Key Features

- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Interactive Gallery**: Auto-advancing image carousel with manual navigation
- **Quote Modal**: Form validation and modal functionality
- **Smooth Animations**: Intersection Observer for fade-in effects and CSS animations
- **Navigation**: Smooth scrolling between sections with dynamic nav background

## CSS Architecture

- Uses CSS custom properties for consistent theming
- Responsive breakpoints at 768px
- BEM-like class naming for components
- Modular sections: navigation, hero, services, gallery, modal, forms

## JavaScript Functionality

- Intersection Observer for scroll-triggered animations
- Gallery management with automatic progression
- Modal state management with body scroll lock
- Form validation with email regex
- Smooth scroll navigation between sections