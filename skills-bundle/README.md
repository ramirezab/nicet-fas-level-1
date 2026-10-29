# Paquete de skills

Colección de 50 skills de Claude (cada una en su carpeta con un archivo `SKILL.md`). Incluye las usadas en los proyectos de GRC Abogados y GRC Empresarial y otras obtenidas de fuentes externas.

**Licencias:** las skills de terceros conservan su licencia y autoría originales. Esta colección se publica sin garantía. Si alguna autoría requiere atribución, se agrega aquí.

## Cómo usarlas
Copia las carpetas de `skills/` a `~/.claude/skills/` (o a `.claude/skills/` dentro de un proyecto).

## Índice

| Skill | Descripción |
| --- | --- |
| `accessibility` | Design, implement, and audit accessible UI to WCAG 2.2 Level AA across Web, iOS, and Android — semantic ARIA roles and labels, accessibility traits and hints, f |
| `animate` | Build an animation from scratch, making the decisions in the order that determines whether it feels right — should it animate at all, what purpose, which tool,  |
| `animate-expo` | Build animations in React Native and Expo, making the decisions in the order that determines whether they feel right — should it animate, which thread it runs o |
| `animation-performance` | Keep web animations inside the frame budget — animate composite-only properties, keep motion off the main thread when the page is busy, and find the cause when  |
| `animation-vocabulary` | Reverse-lookup glossary that turns a vague description of a web animation or motion effect into its exact term ("the bouncy thing when a popover opens" → Pop in |
| `apple-design` | Apple's approach to interface design and fluid, physical motion, translated for the web. Use when building or reviewing gesture-driven UI, spring animations, dr |
| `article-writing` | Write articles, guides, blog posts, tutorials, newsletter issues, and other long-form content in a distinctive voice derived from supplied examples or brand gui |
| `ask-sonner` | Guide to Sonner, the React toast library — install and wire up the Toaster, pick the right toast() call, promise and loading toasts, updating, dismissing and pe |
| `brand` | Brand voice, visual identity, messaging frameworks, asset management, brand consistency. Activate for branded content, tone of voice, marketing assets, brand co |
| `brand-discovery` | Run a structured, resumable multi-session brand identity interview across 8 modules (purpose, positioning, audience, personality, voice, narrative, founder tens |
| `brand-voice` | Build a source-derived writing style profile from real posts, essays, launch notes, docs, or site copy, then reuse that profile across content, outreach, and so |
| `break-ui` | Try to break a piece of UI by feeding it worst-case data — long names, unbreakable emails, one-letter names, missing fields, huge counts, zero items, long label |
| `browser-qa` | Run automated post-deploy UI verification with a browser automation MCP (claude-in-chrome, Playwright, or Puppeteer): console-error and Core Web Vitals smoke ch |
| `click-path-audit` | Trace every user-facing button/touchpoint through its full state change sequence to find bugs where functions individually work but cancel each other out, produ |
| `content-engine` | Create platform-native content systems for X, LinkedIn, TikTok, YouTube, newsletters, and repurposed multi-platform campaigns. Use when the user wants social po |
| `crosspost` | Multi-platform content distribution across X, LinkedIn, Threads, and Bluesky. Adapts content per platform using content-engine patterns. Never posts identical c |
| `design-system` | Token architecture, component specifications, and slide generation. Three-layer tokens (primitive→semantic→component), CSS variables, spacing/typography scales, |
| `e2e-testing` | Playwright E2E testing patterns, Page Object Model, configuration, CI/CD integration, artifact management, and flaky test strategies. Use when writing Playwrigh |
| `emil-design-eng` | This skill encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, and the invisible details that make software feel great. |
| `fal-ai-media` | Unified media generation via fal.ai MCP — image, video, and audio. Covers text-to-image (Nano Banana), text/image-to-video (Seedance, Kling, Veo 3), text-to-spe |
| `find-animation-opportunities` | Search a codebase or UI for places that don't animate but should, and reject everything that shouldn't. Read-only; it proposes motion with exact values, it does |
| `frontend-a11y` | Accessibility patterns for React and Next.js — semantic HTML, ARIA attributes, form labeling, keyboard navigation, focus management, and screen reader support.  |
| `frontend-design-direction` | Set an ECC-specific frontend design direction for production UI work. Use when building or improving websites, dashboards, applications, components, landing pag |
| `frontend-patterns` | Frontend development patterns for React, Next.js, state management, performance optimization, and UI best practices. Use when building or reviewing React or Nex |
| `frontend-slides` | Create stunning, animation-rich HTML presentations from scratch or by converting PowerPoint files. Use when the user wants to build a presentation, convert a PP |
| `improve-animations` | Survey a codebase's animation and motion code as a senior motion advisor, then produce a prioritized audit and self-contained implementation plans for other age |
| `make-interfaces-feel-better` | Design engineering principles for making interfaces feel polished. Use when building UI components, reviewing frontend code, implementing animations, hover stat |
| `market-research` | Conduct market research, competitive analysis, investor due diligence, and industry intelligence with source attribution and decision-oriented summaries. Use wh |
| `marketing-campaign` | End-to-end marketing campaign planning and execution. Covers audience research, positioning, campaign angle definition, landing page copy, email sequences, soci |
| `mobile-native` | Make a web app feel native on a phone — the small CSS and meta-tag fixes that separate "a website in a browser" from something that feels installed. Covers stic |
| `motion-advanced` | Advanced motion patterns for React / Next.js — drag & drop, gestures, text animations, SVG path drawing, custom hooks, imperative sequences (useAnimate), loader |
| `motion-foundations` | Motion tokens, spring presets, performance rules, device adaptation, accessibility enforcement, and SSR safety for React / Next.js using motion/react. Foundatio |
| `motion-patterns` | Production-ready animation patterns for React / Next.js — button, modal, toast, stagger, page transitions, exit animations, scroll, and layout — built on motion |
| `pick-ui-library` | Pick the right library for a given frontend task from a curated, opinionated list — numbers, OTP inputs, charts, command menus, virtualization, drag and drop, t |
| `prototype` | Build multiple genuinely different versions of a UI piece you describe, rendered behind a visual picker so you can flip through them live and promote the one th |
| `react-patterns` | React 18/19 patterns including hooks discipline, server/client component boundaries, Suspense + error boundaries, form actions, data fetching, state management  |
| `react-performance` | React and Next.js performance optimization patterns adapted from Vercel Engineering's React Best Practices (https://github.com/vercel-labs/agent-skills). Organi |
| `remotion-video-creation` | Best practices for Remotion - Video creation in React. 29 domain-specific rules covering 3D, animations, audio, captions, charts, transitions, and more. Use whe |
| `review-animations` | Reviews animation and motion code against a high craft bar derived from Emil Kowalski's design engineering philosophy. Default to flagging; approval is earned. |
| `seo` | Audit, plan, and implement SEO improvements across technical SEO, on-page optimization, structured data, Core Web Vitals, and content strategy. Use when the use |
| `taste` | - |
| `ui-demo` | Record polished UI demo videos using Playwright. Use when the user asks to create a demo, walkthrough, screen recording, or tutorial video of a web application. |
| `ui-styling` | Create beautiful, accessible user interfaces with shadcn/ui components (built on Radix UI + Tailwind), Tailwind CSS utility-first styling, and canvas-based visu |
| `ui-ux-pro-max` | UI/UX design intelligence for web, mobile, and desktop. This skill should be used when designing, building, reviewing, or fixing interfaces, including pages, co |
| `video-editing` | AI-assisted video editing workflows for cutting, structuring, and augmenting real footage. Covers the full pipeline from raw capture through FFmpeg, Remotion, E |
| `videodb` | Ingest, index, search, edit, and monitor video and audio with the VideoDB Python SDK — upload from files, URLs, or RTSP feeds, build spoken and scene indexes wi |
| `vite-patterns` | Vite build tool patterns including config, plugins, HMR, env variables, proxy setup, SSR, library mode, dependency pre-bundling, and build optimization. Activat |
| `watch` | Watch a video (URL or local path). Downloads with yt-dlp, extracts auto-scaled frames with ffmpeg, pulls the transcript from captions (or local WhisperX / cloud |
| `watermelon-ui` | Discover and install free, source-backed React UI from Watermelon. Use when a user needs a component, block, dashboard, template, design inspiration, or a compo |
| `write-swift` | How to write modern Swift well — modeling with value types, Swift 6 data-race safety and approachable concurrency (@concurrent, main-actor-by-default, actors, t |
