# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal GitHub Pages website for Nahuel Matias hosted at `matiasaraujo.ar`. It's a modern, responsive single-page application showcasing personal information, skills, and contact details.

## Project Structure

- `index.html` - Main single-page application with embedded CSS and JavaScript
- `assets/images/` - Profile photo (also used as the social preview image)
- `assets/papers/` - Published papers linked from the Education section
- `CNAME` - Custom domain configuration for `matiasaraujo.ar`
- `LICENSE` - GNU General Public License v3.0

## Technology Stack

- **Frontend**: Modern HTML5, CSS3 with CSS Grid/Flexbox, Vanilla JavaScript
- **Styling**: CSS Custom Properties (CSS Variables), responsive design with mobile-first approach
- **Icons**: Font Awesome 6.4.0 (via CDN)
- **Fonts**: Inter font family (via Google Fonts)
- **Color Palette**: Dark theme with Cyan (#00D9FF), Purple (#8B5CF6), Green (#00FF88) accents over deep navy (#0A0E27, #0F172A)

## Development Workflow

This is a static site deployed via GitHub Pages with no build process required.

### Making Changes
- Edit `index.html` directly for content, styling, or functionality changes
- All CSS is embedded in the `<style>` tag within the HTML file
- JavaScript is embedded in the `<script>` tag at the bottom of the HTML file
- Changes are automatically deployed when pushed to the main branch

### Key Features Implemented
- Responsive design with mobile breakpoints
- Smooth scrolling navigation
- Hover effects and animations
- Fixed header with scroll effects
- Social media links (LinkedIn, GitHub, Email)
- Mobile hamburger navigation menu
- Open Graph / Twitter Card meta tags for link previews
- Motto quote band, Experience timeline, Education section (MBT + Mingo final project), Skills showcase
- English/Spanish language switch
- Contact section with social links

### Customization Areas
- Personal information in the hero section
- About me content and profile image (`assets/images/profile-photo.jpg`, 600x600)
- Skills cards with icons and descriptions
- Social media links and contact information
- Color scheme via CSS custom properties

### Deployment
- Automatic deployment through GitHub Pages
- Custom domain configured via CNAME file pointing to `matiasaraujo.ar`
- No manual deployment steps required

## Internationalization

- English text lives in the HTML markup (default, used by search engines)
- Spanish strings live in the `translations.es` object in the `<script>` tag, keyed by each element's `data-i18n` attribute
- When adding or editing visible text, add a `data-i18n` key and update both the markup and `translations.es`
- Language defaults to the browser language (Spanish if it starts with `es`) and the choice is stored in `localStorage`

## Content Management

When updating personal information:
- Hero section: Name, title, and description
- About section: Personal bio and achievements
- Experience section: Roles, dates and highlights (source: LinkedIn profile)
- Education section: Degrees, final project and courses
- Skills section: Technical expertise and descriptions
- Contact section: Social media links and contact methods
- Update LinkedIn URL to match actual profile
- Update email address to preferred contact method

## License

This project is licensed under GNU General Public License v3.0.