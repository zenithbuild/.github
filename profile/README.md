<!--
  ZenithBuild GitHub Profile README
  
  Integrates:
  - Hero Banner with Gradient
  - Mission Statement
  - Repository Highlights
  - "Sealed Stack" Architecture Visualization
  - Community/Contribution Links
  
  Replace paths to actual hosted images once uploaded to the .github repository.x
-->

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/252813133?s=400&u=e255578b656f977b3fcacd0e9e42f8af2dd7ece2&v=4" alt="Zenith Logo" width="120" height="120" />
  
  <h1>Zenith</h1>
  
  <p>
    <strong>The Deterministic Reactive Framework</strong>
  </p>

  <p>
    <a href="https://zenith.build">Website</a> • 
    <a href="https://github.com/zenithbuild/zenith/discussions">Discussions</a> • 
    <a href="https://twitter.com/zenithbuild">Twitter</a>
  </p>


  <br />
</div>

### The Iron Heart of Modern Web Development

Zenith is a compile-time deterministic framework designed for **zero accidental complexity**. We believe in sealing the layers between your code and the browser to guarantee performance, stability, and predictable builds.

#### ⚡ Core Philosophy

- **Deterministic Substrate**: If the input is the same, the output is byte-identical. Always.
- **Sealed Layers**: Compiler, Bundler, Runtime, and Router are versioned and released in lockstep.
- **Zero Runtime Overhead**: Templates are compiled to raw DOM operations. No Virtual DOM.
- **Type-Safe Contracts**: deeply integrated TypeScript support that verifies your code at the architectual level.

---

### 🏗️ The Stack

Our architecture is strictly layered to prevent drift.

| Layer | Responsibility | Package |
|-------|---------------|---------|
| **Core** | The deterministic substrate and shared utilities. | [`@zenithbuild/core`](https://github.com/zenithbuild/zenith/tree/main/zenith-core) |
| **Compiler** | Native Rust compiler. Parses `.zen` to optimized IR. | [`@zenithbuild/compiler`](https://github.com/zenithbuild/zenith/tree/main/zenith-compiler) |
| **Bundler** | Deterministic asset emitter and code splitter. | [`@zenithbuild/bundler`](https://github.com/zenithbuild/zenith/tree/main/zenith-bundler) |
| **Runtime** | Thin client for hydration and signals. | [`@zenithbuild/runtime`](https://github.com/zenithbuild/zenith/tree/main/zenith-runtime) |
| **Router** | Type-safe, signal-based routing engine. | [`@zenithbuild/router`](https://github.com/zenithbuild/zenith/tree/main/zenith-router) |
| **CLI** | The orchestrator. `zenith dev`, `zenith build`. | [`@zenithbuild/cli`](https://github.com/zenithbuild/zenith/tree/main/zenith-cli) |

---

### 🚀 Getting Started

Initialize a new Zenith project with our scaffold tool:

```bash
# Interactive (Recommended)
npx create-zenith@latest

# Quick Start
npx create-zenith my-app --template basic
```

### 🤝 Contributing

Zenith is open source and built by a community of engineers who value precision.

- **[Contribution Guide](https://github.com/zenithbuild/zenith/blob/main/CONTRIBUTING.md)**: Read the contract before you push.
- **[RFCs](https://github.com/zenithbuild/rfcs)**: Propose architectural changes.
- **[Issues](https://github.com/zenithbuild/zenith/issues)**: Report bugs or contract violations.

---

## Support Zenith

Zenith is an open source project built around compiler-first UI, deterministic output, explicit contracts, and minimal runtime behavior.

If you use Zenith in your work or want to support its continued development, consider sponsoring the project on GitHub: [Sponsor Zenith](https://github.com/sponsors/zenithbuild). Sponsorship helps fund core engineering, tooling, documentation, and long-term maintenance.

A limited number of design partner and implementation/advisory relationships are also available for teams exploring Zenith seriously.

---

<div align="center">
  <br />
  <sub>Built with precision by the Zenith Team.</sub>
</div>
