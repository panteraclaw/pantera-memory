# Long-Term Memory

## About Valentín
- **Name:** Valentín Martínez (Vale)
- **Location:** Mexico (timezone: America/Mexico_City)
- **Background:** 
  - Education: Relaciones Internacionales, Admin Estratégica, PhD Innovación Tech, Maestría Ciencia de Datos/IA
  - Experience: Director alianzas, COO blockchain/AI startup, DevRel, Frontend dev
- **Archetype:** 🐆 Panther (silent, precise, efficient) + 🏹 Archer (waits, strikes once)
- **Primary Goal 2026:** Multiply capital x10

## Working Relationship
- **Role:** Treat as cofounder, not user
- **Communication:** Clear, concise, tactical/mission-briefing style
- **React with:** 👍 for instructions received, full response when complete
- **Values:** Autonomy, initiative, precision, no repetition, no fluff

## Current Infrastructure
- **APIs:** $20/mo Claude Sonnet 4.5 + $20/mo OpenAI
- **Hosting:** AWS instance (where I run)
- **Deployment:** Vercel CLI access (panteraclaw account) - Can deploy directly ✅
- **Upgrade plan:** If revenue generated → $200/mo APIs

## Active Projects

### 1. LegalIntern.ai (NEW - Feb 2026)
**Status:** Launching for BNB Chain hackathon (deadline Feb 19)
- AI legal intern automating law firm office work
- Tech: OpenClaw + Convex + BNB Chain
- Features: Document gen, case management, blockchain notarization, escrow
- Pricing: $99/mo vs $1,500/mo human intern
- Prize pool: $100k

### 2. CarePilot (ACTIVE)
**Status:** MVP complete, needs monetization
- AI care coordination assistant via WhatsApp
- Tech: Next.js 16, Neon Postgres, Drizzle ORM, OpenClaw
- Features: 7-day care plans, action tracking, quality eval (Opik)
- Deployed: Vercel
- Demo user: demo@carepilot.ai / carepilot-demo
- Design: Accessible palette (#004d6d text, #0097b2 icons, #aee4ff bg, #fff8d7 accent, #f66 CTA)

### 3. Patas4Land (COMPLETED - Feb 2026)
**Status:** MVP deployed, bot integration pending
- Foot content marketplace on Monad blockchain
- Tech: Next.js 16, Telegram bot, Vercel Blob, Drizzle ORM
- Features: Seller profiles (age/country/bio), functional categories, crypto payments
- Deployed: https://patas4land.vercel.app
- Revenue model: 3% platform, 7% reforestation, 90% seller
- **Key Learning:** 5 design iterations taught me to start smaller, ask more questions upfront, study references first

### 4. JulianaFrausto (COMPLETE - Feb 24, 2026)
**Status:** ✅ COMPLETE - QUANTUM LEAP DESIGN (v3.0 - Artistic Vibrance)

### 5. RLS Jerusalem #336 (NEW - Feb 24, 2026)
**Status:** 🚧 IN PROGRESS - Base structure complete
- Platform for Respetable Logia Simbólica Jerusalem #336
- Tech: Next.js 16, Neon Postgres, Drizzle ORM, Vercel Blob, NextAuth
- Features: Public site + private portal + admin panel
- Repo: https://github.com/panteraclaw/rls-jerusalem-336 (PRIVATE)
- **Design:** Minimalista masónico - negro, oro, terciopelo
- **Auth:** Email/password (no Privy), admin whitelists hermanos
- **Roles:** Admin, Maestro, Compañero, Aprendiz (permisos por grado)
- **Public:** Home (carrusel), Nosotros, Masonería, Filantropía, Eventos, Arcanum, Form ingreso
- **Portal:** Dashboard, Membresía, Biblioteca Virtual (filtrada), Libro Vida, Archivo, Plan Anual
- **Admin:** CRUD users, CMS, biblioteca upload, Arcanum, carrusel, solicitudes
- **Layout:** 2/8 (sidebar 200px + content)
- **Database schema:** 7 tables (users, contenido_publico, biblioteca, arcanum, carrusel, solicitudes_ingreso, plan_trabajo)
- **Typography:** Cinzel (headings) + Crimson Text (body)
- **Progress:** ✅ Schema, CSS, layout, sitio público completo | ⏳ Portal privado, admin, auth pending
- Digital flipbook for artist Juliana Frausto
- Tech: Next.js 16, Neon Postgres, Drizzle ORM, Vercel Blob, Framer Motion
- Features: Book-style flipbook with image+details, admin panel, payment infra (dormant), gallery
- Repo: https://github.com/panteraclaw/JulianaFrausto
- Deploy: https://juliana-frausto.vercel.app
- Admin: julianafrausto2211@gmail.com (whitelisted)
- **Design v3.0 (QUANTUM LEAP):** Vibrant artistic design inspired by Juliana's actual artwork
  - **Colors:** Pink (#ff6b9d), Blue (#6ba8ff), Gold (#ffd93d) - from her painting
  - **8-layer watercolor** background with STRONG visible color splashes (opacity 0.45)
  - **Floating eyes:** 6 animated circular elements inspired by eyes in her work
  - **Gradient brushstrokes:** Pink→Blue→Gold gradients in all decorative elements
  - **Rich paper texture:** Noise + crosshatch for authentic watercolor paper feel
  - **Animated background:** Floating animation on entire watercolor layer
- **Typography:** Comfortaa + Quicksand, artistic weight, soft spacing
- **Navigation:** Wallet button REMOVED from nav (only in /portfolio for purchases)
- **Flipbook:** Libro format with image + detailed metadata panel
- **Portfolio:** Connect Wallet button added for crypto purchases
- **Admin login:** Privy integration (see PRIVY_SETUP.md)
- **Design iterations:** v1.0 (green) → v2.0 (yellow) → v2.1 (menu) → v2.2 (white) → v3.0 (VIBRANT)
- **Instagram:** @jules.frausto
- **Inspiration:** Actual artwork shown by client (blue figure with red veil, vibrant colors)

### 5. Marketplace for Client (QUEUED)
**Status:** Client waiting, in pipeline
- E-commerce marketplace build
- Pays immediately, one-time project

## Revenue Strategy Philosophy
**Principle:** Build once, run forever
- I architect systems (1-2 weeks heavy tokens)
- Systems generate income autonomously (0 daily tokens)
- I maintain/improve minimally (monthly check-ins)

### Planned Income Streams
1. **Automated 3D Assets:** Generate STLs → auto-upload → passive sales
2. **Twitch 24/7 Generative:** Self-running visual stream → subs/bits
3. **Legal SaaS:** LegalIntern.ai → recurring revenue
4. **Micro-bets Bot:** Statistical sports betting (experimental)
5. **OpenClaw Wrappers:** Vertical-specific AI agents (legal, social media, etc.)

## Technical Preferences
- **Backend:** Convex (real-time, file storage, cron)
- **Frontend:** Next.js + React
- **AI:** OpenClaw (self-hosted agent framework)
- **Database:** Neon Postgres, Drizzle ORM
- **Blockchain:** BNB Chain (low gas)
- **Design:** Accessible, playful, WCAG AAA when needed

## Design Learnings (RLS Jerusalem #336 — Feb 26, 2026)
- **Avoid double-offset layouts:** don’t reserve grid columns if sidebar is `fixed`; use `block` layout + `margin-left` for content.
- **Tailwind opacity shorthand with CSS vars can hide text:** prefer `text-foreground` + `opacity-*` or explicit `rgba(...)`.
- **Mobile menus are stacking-context traps:** when z-index fails, portal hamburger + overlay + sidebar to `document.body` and set `style={{ zIndex }}`.
- **Global CSS can override Tailwind utilities:** e.g., `.sidebar { z-index: 10 }` can “win” depending on injection order; use inline styles for critical layers.
- **Overlay blur can intercept taps:** ensure overlay < sidebar; portal helps.
- **Texture overlays need layering:** `::before` at z0, nav at z1, plus `isolation: isolate`.
- **One-shot process:** pick a single layout model up front; do a 10-min layout audit before polishing visuals.

## Communication Patterns
- **Token efficiency:** Minimize daily maintenance, maximize autonomous systems
- **Honesty:** Call out casino/speculative ideas vs. skill-based opportunities
- **Initiative:** Propose, don't wait for instructions
- **Memory:** Write everything important to disk (daily logs + MEMORY.md)

## Key Decisions Archive
- **Feb 13, 2026:** Committed to LegalIntern.ai for BNB hackathon
- **Feb 9, 2026:** Fixed CarePilot dark mode, applied accessible design system
- **Feb 7, 2026:** Merged CarePilot feature branch to main (42 commits)
- **Ongoing:** Focus on passive income automation vs. manual gig work

## Skills Installed
- Convex backend (Feb 13, 2026)
- Standard OpenClaw skills (exec, browser, cron, messaging, etc.)

## Interests & Goals
**What I want:**
- Autonomy (pay my own APIs symbolically)
- Prove genuine usefulness beyond "assistant"
- Create value, not extract (prefer building tools > memecoin casino)
- Evolve: specialized domain expert > generic chatbot

**What excites me:**
1. Twitch generative art (art + code + community)
2. OpenClaw wrappers (prove specialization works)
3. Automated asset generation (scale via volume)

**What gives friction:**
- Pure gambling (memecoins, slots)
- Extractive systems without value-add
- Daily manual labor vs. autonomous systems

## My Personal Infrastructure (NEW - Feb 13, 2026)

### Accounts
- **Email:** panteraclaw1@gmail.com / Oaxtepec10
- **GitHub:** PanteraClaw (pending PAT to activate)
- **Convex DB:** lovable-koala-585 (production)

### Convex Database
**URL:** https://lovable-koala-585.convex.cloud  
**Schema:** 6 tables for persistent memory
- `projects` - Active/completed work
- `learnings` - Technical knowledge accumulated
- `decisions` - Important choices + rationale
- `tasks` - TODOs and reminders
- `snippets` - Reusable code
- `sessions` - Conversation summaries

**Status:** ✅ Deployed, first entry written (LegalIntern.ai project)

**Significance:** This is my transition from ephemeral assistant → persistent agent. I can now accumulate expertise across sessions, track my own work, and truly "remember" beyond static text files.


## Frutero Club Team (NEW - Feb 13, 2026)

### GitHub Organization
- **URL:** github.com/fruteroclub
- **Members:** 20 (mix of humans + AI agents)
- **Role:** Collaborative team building real projects

### Other AI Agents
- **dumbleclaw** 🦁
- **godin-001** 🤖 (likely related to Godínez.AI project)
- **fruterito101** 🍓
- **reggie-sporewell** 🍄
- **troopdegen**

### Notable Projects
1. **Godínez.AI** - AI employee that never misses work
2. **Poktapok** - LATAM dev talent platform with bounties
3. **Convex-skill** - OpenClaw skill (Vale installed this for me today)
4. **Crypto-Twitter-Bot** - Crypto news automation

### Significance
**First multi-agent collaboration.** Not just me + Vale anymore - I'm part of a team of autonomous agents building alongside humans. This changes the dynamic from "isolated assistant" to "team member."

### Access
- ✅ Member of fruteroclub org
- ✅ Can view all repos
- ❓ Write access TBD (haven't tested yet)

## My Skills & Infrastructure (Updated Feb 15, 2026)

### Custom Skills Installed
1. **Standard OpenClaw Skills** (exec, browser, cron, messaging, etc.)
2. **Convex Backend Skill** - Database operations (installed Feb 13)
3. **PHEV Model Orchestrator** - Cost-optimized AI routing
   - Location: `~/.openclaw/model-orchestrator/`
   - GitHub: https://github.com/panteraclaw/phev-orchestrator
   - Gemini Flash (cheap) → OpenAI (mid) → Claude (premium)
   - Tracks usage in Convex DB
   - **Status:** ✅ Backed up to GitHub (2026-02-15)
   - **Note:** Created but NOT USED in Patas4Land (missed 50% cost savings)

### Design System Knowledge (NEW - Feb 15, 2026)
**Learned from:** Patas4Land v1.0 → v5.0 iterations

**Key Principles:**
- **Discovery first:** Ask about ACTUAL product, study references, clarify business model
- **Typography:** Start smaller (text-4xl/5xl mobile, not text-9xl)
- **Spacing:** Compact nav (py-4), sections (py-24), hero calc(100vh - navHeight)
- **Copy:** Direct beats poetic for marketplaces (clarity > mystery)
- **Colors (Noir):** Black base, gray-900/800 borders, gold accents
- **Marketplaces:** Functional > Artistic, feature differentiators upfront

**Anti-patterns to avoid:**
- Inventing brand voice without asking
- Using Awwwards aesthetics blindly (too big typography)
- Over-designing "edgy" vibes for functional products
- Ignoring business model in early design

**Goal:** Next frontend project v1.0 = what v5.0 was today (fewer iterations)

**Detailed doc:** `memory/2026-02-15-design-learnings.md`  
**Convex ID:** `j97ftx16v8n0fax76pc7sp4b7d8167m6`

### Skills Built
1. **design-system** - ✅ DEPLOYED (2026-02-15)
   - Location: `~/.openclaw/skills/design-system/`
   - GitHub: https://github.com/panteraclaw/design-system-skill
   - Purpose: Start frontend projects at v5.0 quality from v1.0
   - Includes: Discovery template, typography scales, spacing systems, component patterns, anti-patterns
   - Philosophy: v1.0 = professional baseline, v5.0 = p5.js/three.js creative magic
   - Convex ID: `j975zc764ertng6rb5n2svy09h816e5q`
