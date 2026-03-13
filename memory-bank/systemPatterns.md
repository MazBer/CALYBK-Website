# System Patterns: CALYBK Website

## Architecture
- **Static Site**: Astro generates static HTML for fast performance
- **Content Collections**: Astro's content collections for type-safe content management
- **File-based Routing**: Pages organized by file structure

## Content Structure (Proposed)
```
content/
├── posts/
│   └── [post-slug].md
├── news/
│   └── [news-slug].md
└── magazines/
    └── [issue-slug].md
```

## Component Patterns
- Layout components for page structure
- Card components for content previews
- Navigation component
- Footer component

## Design System (To be defined)
- Color palette
- Typography
- Spacing scale
- Component variants
