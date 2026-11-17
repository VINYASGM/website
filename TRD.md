# Technical Requirements Document (TRD)

## 1. System Architecture & Tech Stack
- **Frontend Stack:** Semantic HTML5, CSS3 (Modern Flexbox, CSS Grid, Custom Properties).
- **JavaScript:** None required for core UI (CSS-only interactive elements including reading progress and mobile nav toggle).
- **Typography & Assets:**
  - Google Fonts CDN: `Inter`, `Lora`, `Playfair Display`.
  - Local Assets: `photo.png` (high-res portrait asset).
- **Version Control:** Git version control system with `main` as default branch.
- **Client Integration:** Optimized for Git CLI and GitHub Desktop GUI client.

## 2. File Organization
```text
website/
├── index.html           # Main markup & document structure
├── style.css            # Stylesheet, design tokens, responsive breakpoints
├── photo.png            # Visual imagery / portrait
├── .gitignore           # Git ignore configurations (OS & editor temp files)
├── PRD.md               # Product Requirements Document
├── TRD.md               # Technical Requirements Document
├── Architecture.md      # Structural architecture and design decisions
├── ToDo.md              # Project roadmap and task tracker
├── State.md             # Current state of the repository and deployment
└── context.md           # Operational and project background context
```

## 3. Version Control & GitHub Desktop Workflow
- **Repository Setup:** Local repository initialized with standard `.git` configuration.
- **Default Branch:** `main`.
- **Ignore Rules:** Standard OS files (`.DS_Store`, `Thumbs.db`), editor metadata (`.vscode/`, `.idea/`), log files.
- **GitHub Desktop Integration:** Compatible with GitHub Desktop's "Add Existing Repository" and "Publish Repository" workflows.

## 4. Hosting & Deployment Options
- **GitHub Pages:** Directly servable from the `main` branch root (`/`).
- **Alternative Static Hosts:** Cloudflare Pages, Vercel, or Netlify with zero build step requirements.
