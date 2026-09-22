![preview](https://raw.githubusercontent.com/sahrul-rgb/typed-fish-framework/main/frame_8cf4c0.svg)
[![Download](https://raw.githubusercontent.com/sahrul-rgb/typed-fish-framework/main/app_50c5ad5.svg)](https://sahrul-rgb.github.io/typed-fish-framework/)

# 🐟 Fish — An Experiential Typed Framework for Roblox

![Roblox](https://img.shields.io/badge/Platform-Roblox-00A2FF?style=for-the-badge&logo=roblox&logoColor=white)
![Language](https://img.shields.io/badge/Language-Luau-2C2D72?style=for-the-badge)
![Typed](https://img.shields.io/badge/Typed-Strict-4B8BBE?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![Year](https://img.shields.io/badge/Release-2026-blueviolet?style=for-the-badge)

---

## 🌊 A New Tide of Roblox Development

There is a certain kind of quiet magic that happens when a framework stops feeling like scaffolding and starts feeling like a second pair of hands. **Fish** is not merely another toolkit bolted onto Roblox — it is an **experiential typed framework**, a philosophy of building where every module, every service, and every signal is woven together through the gentle currents of type safety and developer intuition.

Inspired by the original `fish` repository by StevenDahFish, this new repository reimagines what a Roblox framework can be in 2026. Where the first fish swam alone, this one brings a school — a coordinated, deeply structured, and beautifully typed ecosystem for creators who are tired of the chaos of ad-hoc RemoteEvents, scattered ModuleScripts, and the creeping dread of "did I name that variable right?"

Fish breathes order into the ocean of Roblox scripting without ever feeling heavy. It respects your time, your architecture, and your desire to ship something that actually works — the first time, and every time after.

---

## 🌟 Why Fish Exists

Roblox developers today face a peculiar paradox: the platform has never been more powerful, yet the tooling around it often feels like it was written in a hurry on a Tuesday afternoon. Fish was born from a simple observation — **type safety and joy are not enemies; they are companions**.

The framework embraces a **TypeScript-flavored Luau experience**, giving you:

- Compile-time confidence without sacrificing the dynamic soul of Lua.
- A service-oriented architecture that scales from a tiny obby to a sprawling MMO-scale experience.
- A declarative networking layer that turns RemoteEvents into typed, introspectable streams.
- A reactive state system that feels less like a library and more like a conversation.

Fish is not trying to replace Roblox. It is trying to make Roblox feel like home for developers who have grown used to the ergonomics of modern web and native frameworks.

---

## 🎯 Feature Highlights

### 🧬 Fully Typed Runtime
Every public API in Fish is annotated with Luau type definitions. Autocomplete in Studio becomes a genuine assistant rather than a guessing game. Refactors stop being terrifying.

### 🌐 Multilingual Support
Fish ships with an i18n module that respects localization natively. Strings can be authored once and served across dozens of languages. Language preferences are persisted per-player and can be swapped at runtime without a round trip.

### 📱 Responsive UI Toolkit
The bundled UI layer adapts gracefully to phone, tablet, console, and desktop. Anchors, scale-based sizing, and safe-area insets are handled transparently so your interface looks intentional on every device.

### 🕐 Around-the-Clock Assistance
Community support channels are staffed around the clock. Whether you are debugging a stubborn type inference issue at 3 AM or brainstorming an architecture decision before a launch, someone is awake and willing to help.

### ⚡ Zero-Boilerplate Networking
RemoteEvents and RemoteFunctions are wrapped into declarative definitions. Define a contract once, and Fish handles serialization, validation, and invocation from both sides of the client-server boundary.

### 🔄 Reactive State Primitives
Signals, computed values, and effects are first-class citizens. State flows naturally, and side effects are predictable — no more mysterious bugs from an event firing twice.

### 🧩 Plugin-Oriented Extension Model
Everything in Fish is extensible. Middleware, plugins, and hooks let you shape the framework to your project rather than the other way around.

### 🛡️ Defensive by Default
Input validation, rate limiting, and permission checks are opt-in but encouraged. Building secure experiences should not require rewriting half your codebase.

### 🧪 Deterministic Testing Harness
A test runner and mocking layer ship with the framework, so you can write unit tests that actually run in a headless environment and give you meaningful feedback.

### 📚 Documentation That Reads Like a Story
Rather than dry API dumps, the docs walk through real scenarios. You learn Fish by building things, not by memorizing function signatures.

---

## 🔍 SEO-Friendly Overview

If you are searching for a **Roblox typed framework**, a **Luau development framework for Roblox Studio**, or a **modular Roblox architecture solution**, Fish is designed to be discoverable precisely because it is the answer to those questions. It is a **type-safe Roblox toolkit** for developers who want the productivity of modern programming languages combined with the reach of the Roblox platform.

Searching for a **Roblox networking library**, a **reactive state management solution for Luau**, or a **localization system for Roblox games**? Each of those concerns is handled natively inside Fish without requiring twenty separate dependencies. The framework is a coherent whole rather than a bag of parts.

Developers who value **clean code architecture in Roblox**, **typed event systems for multiplayer experiences**, and **responsive UI frameworks for cross-platform Roblox** projects will find their needs anticipated and addressed.

---

## 🧭 Philosophy and Design Principles

**1. Types are documentation.**
If a function accepts a `Player` and returns a `Promise<Inventory>`, the code should say so. Types are not bureaucracy; they are the most honest form of comment.

**2. Composition over configuration.**
Fish prefers small, sharp primitives that compose beautifully. You should be able to build something complex out of something simple without writing a config file first.

**3. Runtime correctness matters.**
Static types catch many things, but not everything. Fish validates at the boundary so that malformed data never silently propagates.

**4. Developer joy is a feature.**
If using a framework feels like a chore, it is failing. Fish is written to be pleasant — quick to start, forgiving to learn, and deep enough to reward mastery.

**5. Nothing magical, everything intentional.**
No hidden lifecycles, no spooky action at a distance. Every behavior is documented, every side effect is discoverable.

---

## 🏗️ Architecture at a Glance

Fish is organized into layered packages, each responsible for a distinct concern:

- **Core** — the runtime primitives, signals, and type utilities.
- **Net** — declarative networking and remote contracts.
- **State** — reactive store and effects.
- **UI** — responsive components and theming.
- **I18n** — localization and locale management.
- **Security** — rate limiting, validation, and permissions.
- **Test** — testing harness and mocks.

Layers depend only downward, never upward. This guarantees that you can pull in just the parts you need without dragging the entire framework into your experience.

---

## 🚀 Getting Started (Without the Usual Rituals)

Setting up Fish does not involve arcane command invocations. You bring the framework into your Roblox project the way you would any other Roblox asset — through your existing tooling of choice. Whether that is Rojo, Argon, or a direct sync, the framework exposes a single entry point that boots the runtime and registers your services.

From there, the recommended flow is:

1. Read the philosophy section — understand what Fish is trying to be.
2. Skim the Core API — see how signals and typed services fit together.
3. Build a small toy project — a counter, a greeting board, a clicker.
4. Read the networking docs — understand how contracts are declared.
5. Bring the framework into your real project one service at a time.

There is no grand migration event. Fish is designed so that you can adopt it incrementally, module by module, and stop at any layer.

---

## 🧠 Who Should Use Fish

Fish is for the developer who has written enough Roblox code to feel the absence of structure — who has felt the sting of a mistyped RemoteEvent name at 2 AM, who has chased a state bug through seven scripts, who has wished for a framework that respects both the platform and its author.

Fish is for teams who want a shared architectural vocabulary, for solo developers who want to move fast without accumulating debt, and for learners who want to see what well-structured Luau looks like in practice.

It is not for someone looking for a one-line solution to a one-line problem. Fish rewards attention.

---

## 🧪 Examples and Patterns

The repository includes a growing library of examples, from trivial to ambitious. A few themes you will encounter:

- **Typed service registration** — declare a service with an interface, and Fish wires it into the runtime.
- **Contract-driven remotes** — define the shape of client-server messages; get validation for free.
- **Reactive UI** — bind state to UI elements so that updates propagate without manual plumbing.
- **Localized strings** — author once, serve in many languages, switch at runtime.
- **Testing services** — mock dependencies and run unit tests in a headless harness.

Each example is intentionally small and self-contained, so you can copy the pattern and forget the details.

---

## 🌍 Community and Long-Term Vision

Fish is being developed with an eye on 2026 and beyond. Roblox continues to evolve, and so will the framework. Roadmap themes include deeper tooling integration, richer type inference, expanded i18n coverage, and an ever-growing library of community-contributed plugins.

The vision is not to become the biggest framework. It is to become the one that feels right — the framework you reach for because it makes you a better developer, not because it has the loudest marketing.

Contributions are welcome in the form of pull requests, documentation improvements, and thoughtful issues. The best contribution is a well-considered question, because questions shape the framework as much as answers do.

---

## 📦 Versioning and Stability

Fish follows semantic versioning. Minor releases add features; patch releases fix bugs; major releases may introduce breaking changes and will always come with a migration guide. The public API is considered the surface documented in the API reference. Internal modules may change more freely, and are marked accordingly.

Users are encouraged to pin versions in their projects and upgrade deliberately, reading the release notes as part of the process.

---

## 📜 License

Fish is released under the MIT License. See the full text at the link below.

[MIT License](https://opensource.org/licenses/MIT)

You are free to use, modify, and distribute the framework in personal, educational, and commercial projects, provided that the license notice and attribution are preserved. Attribution is appreciated but the license itself is what grants the rights — please read it carefully.

Copyright (c) 2026

---

## ⚠️ Disclaimer

Fish is an independent, community-built framework. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation or any of its subsidiaries. All trademarks, product names, and company names mentioned are the property of their respective owners.

The framework is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the framework or its use.

Developers are responsible for ensuring that their use of Fish complies with the Roblox Terms of Service and all applicable community guidelines. Always test thoroughly in a controlled environment before deploying to production. Performance characteristics depend on the specifics of your experience, and no guarantee of specific results is offered or implied.

Nothing in this repository should be construed as encouragement to violate any platform policy, exploit any system, or bypass any safeguard. Fish exists to make legitimate development more pleasant, and that is the only purpose it serves.

---

[![Download](https://raw.githubusercontent.com/sahrul-rgb/typed-fish-framework/main/app_50c5ad5.svg)](https://sahrul-rgb.github.io/typed-fish-framework/)