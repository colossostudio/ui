# Colosso UI

Open source [React](https://react.dev) and [Tailwind CSS](https://tailwindcss.com) components and icons, meant to drop into a project and start from there.

The catalog lives at [ui.tcain.ai](https://ui.tcain.ai). Source is on GitHub at [colossostudio/ui](https://github.com/colossostudio/ui).

## What’s here

- **Components** — Accordion, buttons (simple and ripple), checkbox, inputs (pill and line), radio group, switches, tabs, and textarea. Each has a live preview, the source, and a usage example.
- **Icons** — SVG icons with copy-as-SVG and copy-as-JSX.
- Light and dark themes, stored in a `theme` cookie.

Components live in `components/ui/`. The catalog registry is `lib/components.ts`. Icons are listed in `components/icons.tsx`.

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

```bash
npm run build
npm start
```

## Stack

Next.js App Router, React, Tailwind CSS v4, TypeScript. Type is Suisse Intl (Regular and Medium), loaded from `public/assets/fonts/`.

## License

MIT. See [LICENSE](./LICENSE).
