# Consent Press

A modern web platform built with Astro and Sanity CMS, managed through a Turborepo monorepo.

## 🏗️ Project Structure

This is a monorepo containing:

- `apps/web`: The main website built with [Astro](https://astro.build)
- `apps/studio`: Content management system powered by [Sanity](https://www.sanity.io)

## 🚀 Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- pnpm (v10.11.1 or later)

### Installation

1. Clone the repository
2. Install dependencies:
```bash
pnpm install
```

### Development

Run the development servers:

```bash
# Run all apps
pnpm dev

# Run specific apps
pnpm dev --filter @consent-press/web
pnpm dev --filter @consent-press/studio
```

### Building

```bash
pnpm build
```

### Linting

```bash
pnpm lint
```

## 🛠️ Tech Stack

- **Build System**: Turborepo
- **Package Manager**: pnpm
- **Frontend**: Astro
- **CMS**: Sanity Studio
- **Styling**: Styled Components

## 📝 License

ISC
