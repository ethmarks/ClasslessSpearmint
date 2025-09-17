# ClasslessSpearmint

A classless CSS stylesheet that brings the sleek spearmint aesthetic of [my personal website](https://ethmarks.github.io/) to raw HTML elements. Drop it into any HTML document for instant, beautiful styling.

## What is Classless CSS?

[Classless CSS](https://css-tricks.com/no-class-css-frameworks/) is a one-size-fits-all, drop-in solution that styles raw HTML elements directly. It's designed to make unstyled HTML look professional and polished without any effort from the developer, perfect for quick prototypes and demos.

## Features

- ✨ **Beautiful Design**: Inspired by my personal website's Spearmint theme with a dark background and teal accents
- 🎨 **Comprehensive Coverage**: Styles most common HTML elements including forms, tables, and media
- 🔌 **Plug and Play**: Extremely easy to implement - works on any HTML page
- 📦 **Zero Dependencies**: Just one CSS file - no JavaScript, no frameworks
- 📱 **Responsive**: Looks great on all screen sizes

## Quick Start

### HTML

Add this line to your HTML `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ethmarks/ClasslessSpearmint@main/classlessspearmint.css">
```

### CSS

Add this line to the top of any CSS stylesheet:

```css
@import url("https://cdn.jsdelivr.net/gh/ethmarks/ClasslessSpearmint@main/classlessspearmint.css");
```

## Design System

### Colors

- **Background**: Deep dark (`#121212`) with subtle teal gradients
- **Text**: Light gray (`#e0e0e0`) with secondary text in medium gray
- **Accent**: Teal (`#8fdfd4`) used for headings, links, and interactive elements
- **Borders**: Subtle white transparency for elegant separation

### Typography

- **Primary Font**: Nunito - Clean, readable sans-serif
- **Secondary Font**: Sen - Used for headings and buttons
- **Monospace**: Fira Code - For code blocks and inline code

### Interactive Elements

- **Smooth Transitions**: 0.2s ease transitions on hover states
- **Focus Indicators**: Accessible outline styling with teal accent
- **Button Effects**: Subtle lift animation with accent shadows

## Styled Elements

ClasslessSpearmint provides beautiful styling for most standard HTML elements:

### Typography
- Headings (`h1-h6`) with teal accent colors
- Paragraphs with optimal line spacing
- Links with hover effects
- Emphasis (`em`, `strong`, `mark`)

### Layout
- Blockquotes with accent border
- Horizontal rules
- Code blocks with syntax highlighting support
- Preformatted text blocks

### Tables
- Clean, modern table design
- Zebra striping for readability
- Hover effects on rows
- Styled headers with accent colors

### Forms
- Input fields with focus states
- Buttons with hover animations
- Select dropdowns with custom arrows
- Fieldsets and legends
- Placeholder text styling

### Media
- Responsive images
- Styled figures with captions
- iframe support
