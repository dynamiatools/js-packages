# Dynamia Tools - Javascript Packages

A monorepo containing JavaScript and TypeScript packages to build client-side applications powered by [Dynamia Tools](https://www.dynamiatech.com).  
These packages provide standard APIs, Vue 3 integrations, Nuxt 3 plugins, and utilities to rapidly create frontends based on Dynamia Tools metadata.

---

## 📦 Packages

| Package | Description |
|--------|-------------|
| `@dynamia.tools/core` | TypeScript client to interact with Dynamia Tools metadata APIs. |
| `@dynamia.tools/vue` | Vue 3 composables and components for rendering metadata-based UIs. |
| `@dynamia.tools/nuxt` | Nuxt 3 plugin for easy integration with Dynamia Tools. |
| `@dynamia.tools/utils` | Utility functions shared across packages. |

---

## 🧰 Tech Stack

- TypeScript
- pnpm (monorepo)
- Vue 3 / Nuxt 3
- Dynamia Tools Metadata API

---

## 🚀 Getting Started

Install dependencies:

```bash
pnpm install
```

Build all packages:
```bash
pnpm run build
```

Start development for a specific package:

```bash
cd packages/vue
pnpm run dev
```

## 📁 Monorepo Structure

```go
js-packages/
├── packages/
│   ├── core/     → Base TS client
│   ├── vue/      → Vue integration
│   ├── nuxt/     → Nuxt plugin
│   └── utils/    → Shared utilities
├── package.json
├── pnpm-workspace.yaml
└── README.md
```

### 📜 License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.

