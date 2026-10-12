# Tampa Turf website demo

An isolated, responsive website concept built with Next.js App Router, TypeScript, React, and Tailwind CSS. The green garden design uses locally hosted licensed stock photography and a simple project-enquiry path.

## Setup and verification

Use the checked-in pnpm lockfile with pnpm 10:

```sh
pnpm install --frozen-lockfile --ignore-scripts
pnpm run lint
pnpm run typecheck
pnpm run build
```

No local preview server was started during this work. Development and start scripts bind to localhost when deliberately invoked.

## Content and form boundaries

Only the business name supplied through the repository URL is confirmed. Service categories are proposed and disclosed on the page; the business must confirm offerings and availability. Stock photos are inspiration, not photographs of completed client work. See IMAGE_CREDITS.md for sources and license. The demo contains no invented testimonials, licenses, statistics, prices, offers, phone numbers, or business addresses.

The enquiry form validates sample details in the browser and changes local React state. It sends and stores nothing. There is no contact integration, analytics, external imagery, or external font service. Confirm approved content and contact details before connecting submissions or publishing.

The page includes responsive navigation, keyboard focus, a skip link, reduced-motion support, native FAQ disclosures, labeled fields, and a live form-status message. Interactive browser verification remains pending; no browser or live-server checks are claimed.

General educational reference for turf maintenance and drainage terminology: https://www.syntheticturfcouncil.org/page/glossary . This source does not verify the business or its services.

## Verification record

Completed on 2026-10-11 with Node 24.15.0 and pnpm 10.18.1:

- Dependency installation succeeded with all declared dependencies retained.
- Lint passed with zero errors and zero warnings after the PostCSS export cleanup.
- Strict TypeScript check passed.
- Production build passed and prerendered the home page and icon.
- Prospective source, config, and lockfile review found no common credential-pattern matches or environment files.

The installer reported ESLint 9.39.3 as unsupported; its declared dependency range remains unchanged. Browser interaction checks remain pending. No preview server, deployment, or real form submission was performed.

Build-generated next-env.d.ts is ignored as recommended by Next.js: https://nextjs.org/docs/app/api-reference/config/typescript . Strict TypeScript remains enabled; the build added the standard allowJs setting and development-type include path.

## Photography update — 2026-10-12

Hero and all three service illustrations replaced with licensed stock photography. Sources, license, optimization, and usage limits are documented in [IMAGE_CREDITS.md](IMAGE_CREDITS.md). Existing marketing copy, navigation, FAQs, and local-only enquiry behavior are preserved.

Photography update: lint, strict typecheck, and production build passed. Original photos were inspected; live browser checks remain pending.

## Estimate and callback refinement — 2026-10-12

Estimate-first navigation and hero CTAs, service-specific project prefill, repeated estimate actions, and a short three-field form (name, email or callback number, optional project details). Inline SVG replaces arrow and decorative star glyphs. Mobile actions and inputs have larger targets and 16px input text.

No verified business phone exists in the project sources, so no invented number or direct-call link is displayed. Request a callback opens the phone-contact variant of the same local-only proof-of-concept form. No backend or integration is required for this demo.

Lint, strict typecheck, and production build passed. Built HTML confirms two inputs plus one optional textarea, visible estimate/callback actions, and no form backend action. Licensed assets and credits are unchanged. Live browser interaction checks were not run; no local server or manual deployment was started.
