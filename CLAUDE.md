# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project containing two independent web applications:

1. **AI싱크클럽 Landing Page** (`index.html`) - A one-page landing site for AI Think Club community
2. **Calculator** (`calculator.html`) - A web-based calculator application

Both applications share a consistent design system based on Liner style with purple gradient themes.

## File Structure

```
/
├── index.html          # AI싱크클럽 landing page (main)
├── style.css           # Styles for landing page
├── calculator.html     # Calculator application
├── calculator.css      # Styles for calculator
└── calculator.js       # Calculator logic and event handlers
```

## Design System

Both pages use a consistent Liner-style design:
- **Primary gradient**: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- **Card backgrounds**: White with `border-radius: 24px` and soft shadows
- **Accent backgrounds**: `#f7f8fa`
- **Typography**: System fonts with negative letter-spacing for modern look
- **Interactions**: Smooth transitions and hover effects

## Running the Project

No build process required. Simply open HTML files in a web browser:

```bash
# Open landing page
open index.html

# Open calculator
open calculator.html
```

## Making Changes

When modifying styles:
- Landing page styles → edit `style.css`
- Calculator styles → edit `calculator.css`
- Maintain design consistency between both applications

When adding new features to calculator:
- UI changes → `calculator.html`
- Logic changes → `calculator.js` (uses vanilla JavaScript)
- The calculator object is globally available and handles all operations
