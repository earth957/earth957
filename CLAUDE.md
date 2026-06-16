# Pyaw — English Learning App for Burmese Speakers

## Project Overview
Pyaw (ပြော, meaning "speak") is a web-based English learning app built for a Burmese-speaking relative. The goal is a simple, friendly experience that meets learners where they are — in their native language.

## Tech Stack
- **Frontend**: Vue 3 + TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite

## Key Features
- Interactive English lessons with Burmese-language guidance
- Vocabulary builder with Burmese translations
- Clean, minimal UI optimized for beginners

## Project Structure
```
src/
  components/   # Reusable UI components
  views/        # Page-level views (Home, Lessons, Vocab)
  assets/       # Icons, images, fonts
```

## Dev Commands
```bash
npm install     # Install dependencies
npm run dev     # Start dev server (localhost:5173)
npm run build   # Production build
```

## Notes for Claude Code
- Keep UI simple and accessible — the target user is a non-technical beginner
- Burmese language strings go in a dedicated i18n file (do not hardcode inline)
- Prefer small, focused components over large monolithic files
