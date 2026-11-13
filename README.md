# 🦀 FerroTrace

> [!CAUTION]
> **Nothing to see here yet—still under active realization and development.** 🚧


**FerroTrace** is an open-source, privacy-first static analysis and visual debugging tool built with **Rust**, **WebAssembly (WASM)**, and **Tree-sitter**. Designed for enterprise support teams and developers, it maps complex codebases into interactive flow diagrams and pinpoints runtime crashes directly on your execution graph—all without a single byte of code leaving your local machine.

---

### 🎯 The Vision

* **⚡ Blazing Fast & Local:** Powered by a Rust + WASM core engine. Parses massive enterprise files (Node.js, SAPUI5, React, Angular, Python) in milliseconds inside your browser or VS Code.
* **🔒 Zero Telemetry:** Built for strict enterprise compliance. No cloud servers, no tracking, and local obfuscated log reporting.
* **🗺️ Interactive Code Flows:** Automatically generates visual call graphs and data-flow diagrams using Mermaid.js.
* **🎯 Deep-Link Navigation:** Double-click any node in the visual graph to jump straight to that exact file and line number in VS Code.
* **🚨 Stack-Trace Pinpointing:** Feed a crash log into FerroTrace to automatically highlight the exact failing function node in red.

---

### 🛠️ Tech Stack

* **Core Engine:** Rust + `tree-sitter`
* **Compiler Target:** WebAssembly (`wasm-pack`)
* **IDE Integration:** TypeScript (VS Code Extension API)
* **Visualization:** Mermaid.js (POC) ➡️ Node-Based Graph Editor (Roadmap)

---

### 🚦 Current Status: Phase 1 (Core Engine)

* [ ] Rust + Tree-sitter multi-language dictionary (JS/TS/Python)
* [ ] WASM compilation pipeline
* [ ] VS Code Webview & Mermaid POC
* [ ] Deep-link code navigation & stack-trace error highlighting
* [ ] Local log obfuscator & privacy-first issue reporter

---

### 📄 License

Open-source under the [MIT License](LICENSE).
