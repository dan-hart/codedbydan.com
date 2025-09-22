# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal website (codedbydan.com) built with vanilla HTML, CSS, and JavaScript. The site serves as Dan Hart's professional portfolio and includes a separate landing page for the "Frankly" iOS app.

## Architecture

- **Main Site**: Root `index.html` with Bootstrap 3 styling and jQuery-based interactions
- **Frankly App Landing**: Separate subdirectory (`frankly/`) with its own HTML and CSS
- **Static Assets**: Images, CSS, and JavaScript files organized in dedicated directories
- **Deployment**: Static site hosted via GitHub Pages (CNAME file present)

## Development

This is a static website with no build process or dependencies. All files are served directly.

### File Structure
- `index.html` - Main portfolio page
- `frankly/` - Frankly app landing page with separate styling
- `css/` - Bootstrap and custom styles
- `js/` - jQuery, Bootstrap, and custom JavaScript
- `img/` - Images and screenshots
- `CNAME` - GitHub Pages domain configuration

### Making Changes
- Edit HTML files directly for content updates
- Modify `css/style.css` for main site styling
- Modify `frankly/styles.css` for Frankly page styling
- Test changes by opening HTML files in a browser

### Deployment
Site automatically deploys via GitHub Pages when changes are pushed to the `master` branch.
- Never use javascript on this website