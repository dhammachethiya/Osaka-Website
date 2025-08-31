# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Mahamevnawa Buddhist Monastery in Osaka, Japan. The project consists of a single-page application built with vanilla HTML, CSS, and JavaScript showcasing monastery information, programs, and services.

## Architecture

- **Single HTML File Structure**: The main website is contained in `index.html` with embedded CSS and JavaScript
- **Static Assets**: 
  - `Images/` directory contains monastery photos (22+ high-resolution JPG files)
  - `Logo.png` contains the monastery logo
  - `details.txt` contains content information about the monastery
- **Self-Contained Design**: No external dependencies, build tools, or package managers - everything is vanilla web technologies

## Development Workflow

Since this is a static website with no build process:

1. **Local Development**: Open `index.html` directly in a web browser to view changes
2. **Asset Management**: Images are referenced relatively from the `Images/` folder
3. **Content Updates**: Monastery details and program information can be updated directly in the HTML or referenced from `details.txt`

## Key Features & Structure

- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Smooth Scroll Navigation**: Internal anchor links with JavaScript smooth scrolling
- **Interactive Gallery**: Filterable image gallery with lightbox functionality  
- **CSS Variables**: Consistent theming using CSS custom properties for colors
- **Intersection Observer**: Fade-in animations triggered by scroll position

## Content Management

- **Monastery Information**: Details are embedded in HTML but source content is available in `details.txt`
- **Programs & Events**: Structured sections for daily, monthly, and annual programs
- **Image Gallery**: Uses both local images from `Images/` folder and external Unsplash URLs
- **Contact Information**: Real monastery address and contact details in Osaka

## Styling Architecture

- **CSS Organization**: Embedded styles organized by component (Navigation, Hero, Sections, Gallery, etc.)
- **Color Scheme**: Buddhist monastery theme with greens and gold accent colors
- **Typography**: Georgia serif font for traditional, serene aesthetic
- **Animation System**: CSS keyframes with JavaScript intersection observer for scroll-triggered animations

## No Build System Required

This project requires no compilation, bundling, or build processes. Changes can be made directly to the HTML file and viewed immediately in the browser.