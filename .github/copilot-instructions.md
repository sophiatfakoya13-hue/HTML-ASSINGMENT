# Copilot Instructions for HTML 101 Project

## Project Overview
This is a beginner-level static HTML website project for ALT SCHOOL, demonstrating basic HTML elements and structure. The site focuses on Nigerian cuisine (Jollof Rice) and includes practice pages for forms, tables, and navigation.

## Architecture
- **Static HTML Pages**: Multiple `.html` files in root and `about/` subdirectory
- **Assets Organization**: Media files stored in `Assets/` with subfolders (`Images/`, `Video/`, `audio/`)
- **No Build System**: Direct browser viewing, no compilation or server required

## Key Patterns
- **HTML Structure**: Standard DOCTYPE with `<html lang="en">`, meta charset UTF-8, and responsive viewport
- **Page Titles**: Descriptive titles matching content (e.g., "How To Make ClassicNigerian Jollof Rice")
- **Navigation**: Relative links for internal pages (e.g., `<a href="../new.html">Home</a>`)
- **Forms**: Basic forms with labels, inputs, and selects (see `new.html` for examples)
- **Tables**: Simple data tables with `<th>` headers and `<td>` data cells
- **Sections**: Use `<section>` tags to group related content

## File Naming Conventions
- Use lowercase for filenames (e.g., `index.html`, `new.html`)
- Avoid inconsistent capitalization (note: `Index.html` exists but should be `index.html`)

## Asset Usage
- Images: Store in `Assets/Images/` (e.g., `jollof rice.jpeg`)
- Audio: Store in `Assets/audio/` (e.g., `.mp3` files)
- Video: Store in `Assets/Video/` (e.g., `.mp4` files)
- Reference assets with relative paths from HTML files

## Development Workflow
- Edit HTML files directly in any text editor
- Preview by opening files in web browser
- No linting or validation tools currently used
- Manual testing by clicking links and submitting forms

## Common Tasks
- Adding new pages: Create `.html` file, include standard head structure, link from existing pages
- Adding media: Place in appropriate `Assets/` subfolder, reference with relative paths
- Updating navigation: Use relative paths like `../` for parent directory navigation</content>
<parameter name="filePath">/Users/macbook/Documents/Randoms/Projects/ALT SCHOOL/HTML 101/.github/copilot-instructions.md