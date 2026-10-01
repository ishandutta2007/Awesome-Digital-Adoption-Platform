# Awesome-Digital-Adoption-Platform

# Top Digital Adoption Platform (DAP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on In-App Guidance, User Onboarding & Feature Adoption*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Adoption Platforms (DAP)**. These tools provide in-app guidance, interactive product tours, onboarding checklists, and user analytics to help organizations drive software adoption and reduce support burden.

**Examples** include WalkMe, Whatfix, Pendo, Userlane, Appcues, Inline Manual, Userpilot, Apty, Nickelled, Guidde, UserGuiding, ClickLearn, SAP Enable Now, and Stonly (the category leaders).

**Open-source emphasis**: The open-source ecosystem for product tours is mature and widely adopted. **Driver.js**, **React Joyride**, **Shepherd.js**, and **Intro.js** collectively power onboarding experiences across hundreds of thousands of applications . This section is heavily expanded with active projects for self-hosted tours, guided onboarding, and analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[WalkMe](https://www.walkme.com/)**  
  The pioneer and market leader in digital adoption, founded in 2011. Enterprise-grade platform covering employee onboarding, customer onboarding, process automation, and analytics. Pricing starts at ~$1,500/month for Growth tier, with enterprise deployments reaching $30K+ annually .

- **[Whatfix](https://whatfix.com/)**  
  Enterprise DAP known for ease of use and on-demand support widgets. Strong for Salesforce, SuccessFactors, ServiceNow, and Oracle deployments. Offers on-premise deployment for data sovereignty requirements .

- **[Pendo](https://www.pendo.io/)**  
  Product analytics-first platform with in-app guides, NPS, and user segmentation. Free tier for up to 500 monthly active users. Popular with product teams wanting both analytics and guidance in one tool .

- **[Userlane](https://www.userlane.com/)**  
  DAP focused on enterprise software adoption with interactive step-by-step guides and analytics.

- **[Appcues](https://www.appcues.com/)**  
  Product-led growth platform with no-code onboarding flows, in-app messaging, and NPS. Mobile SDKs available.

- **[Inline Manual](https://inlinemanual.com/)**  
  DAP with interactive walkthroughs, tooltips, and knowledge base integration.

- **[Userpilot](https://userpilot.com/)**  
  Product growth platform with onboarding checklists, feature adoption, and user analytics. Popular with B2B SaaS companies.

- **[Apty](https://apty.ai/)**  
  DAP focused on enterprise application adoption with process automation and compliance features.

- **[Nickelled](https://nickelled.com/)**  
  Interactive walkthrough software for onboarding and training with analytics.

- **[Guidde](https://guidde.com/)**  
  AI-powered platform for creating how-to videos and guides from screen recordings.

- **[UserGuiding](https://userguiding.com/)**  
  No-code product adoption platform with onboarding flows, checklists, and analytics.

- **[ClickLearn](https://clicklearn.com/)**  
  DAP specializing in enterprise software training and documentation, with multi-format content generation.

- **[SAP Enable Now](https://www.sap.com/products/enable-now.html)**  
  SAP's native DAP for SAP applications, providing in-app guidance, training content, and performance support .

- **[Stonly](https://stonly.com/)**  
  Interactive guidance and decision-tree based support platform.

## Open-Source GitHub Projects

- **[Driver.js](https://github.com/kamranahmedse/driver.js)**  
  The lightweight champion at just **3KB gzipped** with **4.3M monthly downloads** and **26.3K GitHub stars** as of 2026 . MIT licensed, framework-agnostic vanilla JavaScript with TypeScript support. Features product tours, element highlighting, hints, and contextual help. Used by Red Hat, GitKraken, and Fiverr . **Limitations**: No state persistence, no analytics integration, no multi-page tour support . Best for simple feature highlighting where bundle size is critical.

- **[React Joyride](https://github.com/gilbarbara/react-joyride)**  
  The most widely installed React-specific tour library with **603K weekly npm downloads** . MIT licensed, **37KB gzipped**. Provides `steps` array API with customizable components and accessible focus trapping . **React 19 compatibility concerns**: Internal state management conflicts with concurrent rendering; multiple GitHub issues report step flickering and overlay glitches in strict mode . Best for quick prototypes and legacy React codebases.

- **[Shepherd.js](https://github.com/shipshapecode/shepherd)**  
  The most capable framework-agnostic option with **12.6K GitHub stars** . **25KB gzipped**. Clean imperative API with excellent scrolling and positioning logic. Supports React, Vue, Angular, and Ember through wrapper packages . **Licensing caveat**: AGPL-3.0 requires open-sourcing any application using it, or purchasing a commercial license ($50 lifetime for up to 5 projects, $300 for unlimited) . Used by Drupal, LogSeq, and SimplePlanner .

- **[Intro.js](https://github.com/usablica/intro.js)**  
  The veteran since 2013 with **8KB gzipped** and stable API . AGPL-3.0 licensed with commercial option at $9.99/site . Vanilla JavaScript with no dependencies, using `data-intro` and `data-title` HTML attributes . Community TypeScript types exist but aren't core-maintained. Best for jQuery-era applications and server-rendered pages.

- **[Tour Kit](https://github.com/domidex01/tour-kit)**  
  Headless architecture with composable packages, **under 8KB core** with zero runtime dependencies . MIT licensed (Pro: $99 one-time). Native React 18+ and 19 support with full TypeScript and WCAG 2.1 AA accessibility. Tours, hints, checklists, analytics, announcements, surveys, and scheduling are separate packages. Works with any component library: shadcn/ui, Radix, Tailwind, or custom systems . **Limitation**: No visual builder — you write JSX .

- **[Reactour](https://github.com/elrumordelaluz/reactour)**  
  React-specific tour library born in 2017, prioritizing SVG and CSS for masking . Split into three packages: `@reactour/mask`, `@reactour/popover`, and `@reactour/tour`. Provides `useTour` hook for controlling tours from any component, with `withTour` HOC for class components . TypeScript-rewritten.

- **[Onboarding (react-onboarding)](https://github.com/alexvcasillas/react-onboarding)**  
  Logic-focused onboarding library for React that provides no UI components — only logical components (Onboarding, Step, Field, Info, End) that you tie to your own UI library . Aimed at full onboarding processes with validations and multi-step forms rather than simple tours.

- **[guidegen](https://www.npmjs.com/package/guidegen)**  
  Open-source CLI tool that generates in-app tours from documentation (SRS Markdown files) and can render MP4 videos from tours . Features a `PageAgent` cursor that moves to controls and clicks/types, `<Guide>` component for Next.js and React, `<GuideWidget>` floating button, and video generation via Playwright and FFmpeg . Supports TTS narration. Actively maintained (August 2026).

### Additional Strong Open-Source Options

- **react-onboarding (alexvcasillas)** — Full onboarding process library with Step, Field, Info, and End components for building validated multi-step flows .
- **r-onboarding** — Super-slim, fully-typed onboarding component for React .
- **react-onboarding (simple wizard)** — Simple Wizard component for React with 389 monthly downloads .

**Frameworks for building custom DAP solutions**: Combine **Driver.js** for lightweight highlighting and tours (3KB, MIT, no dependencies) , **Shepherd.js** for framework-agnostic tours with rich positioning (if AGPL is acceptable or commercial license purchased) , or **Tour Kit** for React 18+ projects needing headless, accessible, composable tours . Use **guidegen** for documentation-driven tour generation and video export . For React-specific projects, **React Joyride** remains the most widely adopted despite React 19 compatibility concerns . Note that true enterprise DAP platforms with process automation, employee training, SOC 2 compliance, and cross-application analytics remain primarily commercial territory; open-source libraries provide strong tour and onboarding foundations that require integration for complete digital adoption programs .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Digital adoption tools may inject scripts into your application and collect user behavior data. Self-hosted solutions require proper security hardening and privacy compliance (GDPR, CCPA).
- Open-source tour libraries vary significantly in features. Evaluate gaps in analytics, state persistence, multi-page tours, and accessibility before deployment. AGPL-licensed tools (Shepherd.js, Intro.js) require commercial licenses for closed-source applications .
- The open-source ecosystem provides strong tour and onboarding foundations, but enterprise process automation, cross-application analytics, and SOC 2 compliance remain primarily commercial offerings.

---

**Made for product managers, UX teams, customer success leaders, and developers building onboarding experiences.**  
Let's make digital adoption more open, transparent, and user-friendly.
