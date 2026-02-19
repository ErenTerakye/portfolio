# Eren Terakye — Portfolio

Personal portfolio and digital business card built with Astro and Tailwind CSS.

**Live:** https://erenterakye.com

## Stack

- [Astro](https://astro.build) — static site framework
- [Tailwind CSS v4](https://tailwindcss.com) — utility-first styling
- [Inter](https://fonts.google.com/specimen/Inter) — typeface

## Features

- EN / TR language support via Astro i18n
- Dark / light mode with system preference detection and manual toggle
- Scroll-triggered fade-in animations
- SEO — meta description, Open Graph, Twitter Card, canonical URL
- Custom favicon, 404 page, robots.txt

## Project Structure

```
src/
├── components/
│   ├── LanguagePicker.astro
│   └── ThemeToggle.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   ├── index.astro       (English /)
│content = 