# Simon Debes - Portfolio

A minimal, professional portfolio built with Astro and Tailwind CSS.

## Features
- **Responsive Design**: Looks great on mobile, tablet, and desktop.
- **Configurable**: Easily update content via a single configuration file.
- **Clean UI**: Modern aesthetics with smooth animations and transitions.

## Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Development Server
```bash
npm run dev
```
The site will be available at `http://localhost:4321`.

### 3. Configuration
All personal information, projects, and skills are managed in `src/config.ts`. Simply update the `siteConfig` object to reflect your data.

```typescript
export const siteConfig = {
  name: "Your Name",
  title: "Your Title",
  // ...
};
```

### 4. Build for Production
```bash
npm run build
```
The production-ready site will be in the `dist/` directory.

## License
MIT
