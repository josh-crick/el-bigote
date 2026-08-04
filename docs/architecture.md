# Project Architecture

## Overview

The El Bigote website is built using Next.js, React, TypeScript, and Tailwind CSS.

The project seperates routing, reusable components, content, and utilities to create a maintainable structure.

---

# Folder Structure

## app/

Responsible for application routes and layouts.

---

## components/

Reusable react components.

### layout/

Global components shared across pages.

Examples:

- Navbar
- Footer

### sections/

Large content sections/

Examples:

- Hero
- About
- Gallery

### ui/

Small reusable interface elements.

Examples:

- Buttons
- Cards
- Containers

---

## data/

Static content.

Examples:

- Menu items
- Testimonials

---

## lib/

Shared helper functions.

---

## types/

Shared TypeScript types.

---

# Development Principles

## Component Responsibility

Each component should have one clear purpose.

## Maintainability

Code should be organised so future changes are easy to make.

## Reusability

Common patterns should become reusable components.