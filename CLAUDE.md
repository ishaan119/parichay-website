# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-page HTML landing page for "Parichay" - a digital identity verification service. The website is built as a static HTML file with embedded CSS styling and no external dependencies or build processes.

## Architecture

- **Single HTML file**: `parichay_landing.html` contains the complete website
- **Embedded CSS**: All styles are contained within `<style>` tags in the HTML file
- **No JavaScript frameworks**: Pure HTML/CSS implementation
- **No build process**: Direct HTML file can be opened in browser

## Key Features

The landing page includes:
- Hero section with animated phone mockup
- Features grid showcasing use cases (delivery verification, dating safety, etc.)
- Trust/statistics section
- How it works step-by-step guide
- Call-to-action sections
- Responsive design for mobile devices

## Development Commands

Since this is a static HTML file, no build commands are needed:
- **View website**: Open `parichay_landing.html` directly in a web browser
- **Deploy**: Upload the HTML file to any web server or hosting service

## CSS Architecture

- Uses CSS Grid and Flexbox for layouts
- Gradient backgrounds and animations throughout
- Responsive breakpoints at 768px for mobile
- Custom CSS animations (shimmer, float, progress)
- Modern CSS features like backdrop-filter and CSS variables