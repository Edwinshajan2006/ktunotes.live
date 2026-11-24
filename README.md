# KTUNOTES.LIVE

<div align="center">

### A community built for students, by students

[![Next.js](https://img.shields.io/badge/Framework-Next.js-111827?style=flat-square&logo=nextdotjs)](https://nextjs.org/)
[![React](https://img.shields.io/badge/UI-React-111827?style=flat-square&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-111827?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)

**[Visit KTUNOTES.LIVE](https://ktunotes.live)**

</div>

KTUNOTES.LIVE is a student-focused platform built to make academic resources easier to find and navigate, with a focus on the KTU 2024 scheme.

## Preview

The following recordings are maintained in this repository:

| Area | Preview |
|---|---|
| Home | ![Home page](home.gif) |
| Semester navigation | ![Semesters](semesters.gif) |
| Syllabus | ![Syllabus](syllabus.gif) |
| Previous question paper search | ![PYQ search](pyq.gif) |
| Upload notes | ![Upload notes](upload-notes.gif) |
| Other sections | ![Other sections](others.gif) |

## What it provides

- Semester-oriented navigation
- Syllabus browsing
- Previous question paper discovery
- Notes and study-resource sections
- A student-oriented interface for academic material

Refer to the live site for the current feature set and availability.

## Technology

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Next.js App Router

## Run locally

### Requirements

- Node.js 18 or later
- npm

### Setup

```bash
git clone https://github.com/Edwinshajan2006/ktunotes.live.git
cd ktunotes.live
npm install
npm run dev
```

Open the local URL printed by Next.js, usually `http://localhost:3000`.

### Production build

```bash
npm run build
npm start
```

## Architecture

```text
ktunotes.live/
├── app/          # App Router pages, layout and API routes
├── components/   # Reusable UI components
├── config/       # Application configuration
├── constants/    # Shared constants
├── features/     # Feature-oriented modules
├── hooks/        # Reusable React hooks
├── lib/          # Shared utilities
├── services/     # Service integrations
├── types/        # TypeScript types
└── public assets # GIFs and images in repository root
```

## Contributing

Before opening a pull request:

1. Keep changes focused and consistent with the existing structure.
2. Run the production build locally.
3. Include screenshots or a short recording for visible UI changes.
4. Do not commit secrets, API keys or private student information.

## Roadmap

- [ ] Add contributor and local-development documentation for external services
- [ ] Document resource submission and moderation workflows
- [ ] Add automated checks to pull requests
- [ ] Improve accessibility and mobile screenshots in the documentation

---

<div align="center">

**Made for students. Improved by the community.**

</div>
