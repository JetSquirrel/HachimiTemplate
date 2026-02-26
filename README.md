# HachimiTemplate

A minimal Astro blog template inspired by [Bear Blog](https://bearblog.dev/).

## Features

- No JavaScript hydration
- Minimal CSS
- Serif typography
- Single column layout
- Markdown-driven content
- Pure SSG (Static Site Generation)

## Project Structure

```
src/
 ├── content/
 │    ├── config.ts
 │    └── blog/
 │         └── hello-world.md
 ├── layouts/
 │    └── Base.astro
 └── pages/
      ├── index.astro
      └── [...slug].astro
```

## Getting Started

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```