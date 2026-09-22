![preview](https://raw.githubusercontent.com/ayan682/roblox-engine-api-surface/main/splash_35f8.svg)
# 🌌 OpenEngine Atlas — Independent Roblox Engine API Surface Mirror

An independent, community-driven cartography of the Roblox Engine API surface. Think of it as a star chart for developers navigating the vast constellation of engine classes, services, datatypes, and events that power experiences on the Roblox platform. This atlas is not affiliated with, endorsed by, or sponsored by Roblox Corporation — it is a third-party observational profile maintained for documentation, tooling, and educational purposes.

[![Download](https://raw.githubusercontent.com/ayan682/roblox-engine-api-surface/main/fetch_8fcb.svg)](https://ayan682.github.io/roblox-engine-api-surface/)

---

## 🧭 What Is OpenEngine Atlas?

OpenEngine Atlas is a meticulously curated, machine-readable and human-friendly snapshot of the public Roblox Engine API surface. Where the official documentation functions as a living manual, OpenEngine Atlas functions as a *historical ledger and reflection pool* — capturing the shape of the API at meaningful points in time, cross-referencing classes, tracking deprecations, and offering developers an alternate lens through which to understand the engine.

If the Roblox Engine is a sprawling city, this repository is the illustrated map: every district (service), every landmark (class), every alleyway (event), and every bridge (callback) documented with intent.

It is designed for:

- 🛠️ Tooling authors who build autocompletion, linters, and static analyzers for Luau and Roblox Studio ecosystems.
- 📚 Documentation archivists who want to observe how the API evolves release over release.
- 🧪 Educators and students learning the anatomy of a modern game engine API.
- 🤖 AI and ML engineers training models that reason about engine semantics.
- 🔍 Curious developers who simply want a second opinion on "how does this class actually behave?"

---

## ✨ Feature Highlights

A repository is only as valuable as the journeys it enables. Below is a tour of what OpenEngine Atlas brings to your workbench.

### 🗺️ Comprehensive API Surface Capture
Every class, service, datatype, enum, event, callback, property, and function that forms the public Roblox Engine API surface is catalogued. Nested hierarchies are preserved. Inheritance chains are visible. This is not a flat dump — it is a structured graph.

### 🧩 Machine-Readable and Human-Readable Formats
The same dataset is exposed in multiple representations: structured data suitable for ingestion by tooling, and prose-oriented documentation suitable for reading on a rainy afternoon. You choose the lens; the atlas holds the same truth.

### 🕰️ Historical Diff Tracking
Watch the API evolve. New classes appear, deprecated members fade, defaults shift like tectonic plates. Historical snapshots let you answer the question, "When did this behavior change?" — a question that plagues developers every day.

### 🌐 Multilingual Documentation Layer
Summaries and annotations can be surfaced in multiple languages, so a developer in São Paulo, Seoul, or Stockholm can read the same conceptual explanation in the language they think in. Multilingual support is a first-class citizen here.

### 🎨 Responsive, Accessible Presentation
The companion viewer is built to behave gracefully on phones, tablets, desktops, and even terminal-based browsers. Color contrast, keyboard navigation, and screen-reader semantics have been considered — because an atlas should be readable by everyone.

### 🔔 Change Notification Feeds
Subscribe to structured change feeds that alert you when relevant parts of the surface mutate. Whether you care only about a specific subsystem or the whole galaxy, you can tailor the signal-to-noise ratio.

### 🧠 Semantic Search and Tagging
Search for "asynchronous data retrieval," and the atlas returns not only the obvious candidates but also related classes, patterns, and historical analogues. Tags such as *input*, *networking*, *rendering*, and *persistence* thread together concepts that span services.

### 🧱 Composable Modules
Every subsystem is packaged as an independently consumable module. Pull in only what you need; leave the rest of the galaxy untouched.

### 🕛 Around-the-Clock Steward Support
A rotating cast of maintainers and community stewards keeps an eye on the atlas at all hours, so issues, corrections, and enhancement requests don't sit in the dark for long. Support is a continuous heartbeat, not a business-hours footnote.

### 🔒 Non-Invasive, Read-Only Philosophy
OpenEngine Atlas never touches a live session. It observes, records, and reflects. Nothing here can alter a running experience, and nothing here asks for privileged credentials.

### 📤 Export Pipelines
Export the atlas into formats convenient for your downstream pipeline — be it a schema store, a documentation generator, or a dataset for analysis.

---

## 🚀 Getting the Atlas Into Your Hands

[![Download](https://raw.githubusercontent.com/ayan682/roblox-engine-api-surface/main/fetch_8fcb.svg)](https://ayan682.github.io/roblox-engine-api-surface/)

The distribution is intentionally unbundled from any single package manager ritual. The atlas can be obtained through the following channels:

- 📦 **Release Archive** — periodic bundles containing a full snapshot of the surface, formatted for offline consultation.
- 🧬 **Repository Cloning** — for developers who prefer to track the living tree and pull changes incrementally.
- 🌐 **Hosted Mirror** — a read-only endpoint that serves the latest stabilized snapshot for programmatic access.
- 📚 **Documentation Portal** — the human-facing facade where prose, examples, and cross-links are rendered.

Because the atlas is intended to be composable, you are encouraged to vendor the pieces you need rather than swallowing the entire galaxy. Select what you want, discard the rest.

---

## 🧭 Repository Layout

The tree is organized along conceptual axes rather than chronological ones:

- `engine/` — the heart of the atlas. Classes, services, datatypes, enums, and their relationships.
- `history/` — chronological snapshots and diff annotations between them.
- `docs/` — the prose layer, including conceptual guides and cross-references.
- `schemas/` — structural definitions that describe the shape of the atlas itself.
- `tools/` — helper utilities for exploring, validating, and exporting the atlas.
- `locales/` — multilingual translation packs for the documentation layer.
- `feeds/` — generated change-feed outputs suitable for subscription.
- `notes/` — maintainer notes, rationale, and edge-case commentary.

Every folder is designed to be understandable in isolation, but the true value emerges when they are consulted together.

---

## 🔍 SEO-Friendly Topic Coverage

OpenEngine Atlas is naturally keyword-rich because the domain is keyword-rich. Topics that appear frequently across the repository include: Roblox Engine API reference, Luau type definitions, engine class hierarchy, service discovery, Roblox scripting reference, event and callback catalogues, datatype references, deprecation tracking, API surface evolution, developer tooling for Roblox, static analysis support, autocompletion datasets, engine semantics, and community documentation efforts.

The language is chosen to be discoverable without becoming spammy. Sentences remain intelligible to humans first and search engines second.

---

## 🛡️ Correctness, Confidence, and Caveats

Every dataset carries a confidence annotation. Some entries are marked as *observed*, some as *inferred*, and some as *community-reported*. This triple taxonomy prevents the atlas from pretending to a certainty it does not possess. When conflicting reports exist, both are recorded with their provenance, and the discrepancy is flagged for future resolution.

Corrections are welcome. The atlas improves the way all good cartography improves: one accurate pencil stroke at a time.

---

## 🤝 Contributing

Contributions come in many shapes:

- 🧾 Reporting an inaccuracy with a supporting reference.
- 🧭 Suggesting a new cross-reference between related classes.
- 🌍 Providing a translation for a documentation page.
- 🧪 Writing a test that guards against a specific regression in structure.
- 📝 Refining prose for clarity without altering meaning.

Before contributing, review the style guide and the taxonomy of confidence. Contributions that respect the existing structure are merged more quickly than those that reinvent it.

---

## 🗓️ Roadmap for 2026

The year 2026 holds an ambitious itinerary:

- 🧭 A fully navigable graph view of the entire class hierarchy.
- 📊 Longitudinal analytics over API surface growth.
- 🌐 Additional locales, with an emphasis on underrepresented languages.
- 🧠 Deeper semantic tagging powered by structured ontologies.
- 📡 Real-time change feeds with filtering by subsystem and severity.
- 🧱 A stable plugin interface for third-party exploration tools.

The roadmap is a living document; entries are reordered as community priorities shift.

---

## ⚖️ Disclaimer

OpenEngine Atlas is an independent, third-party project. It is not affiliated with, endorsed by, sponsored by, or otherwise connected to Roblox Corporation. All trademarks, service marks, and product names referenced remain the property of their respective owners. The atlas reflects an *observational* view of the public API surface and does not claim authoritative status. Where the official documentation and this atlas disagree, the official documentation should be treated as the source of record for production decisions. Use of this repository is at your own discretion; the maintainers offer no warranty of fitness for any particular purpose.

Any code paths, descriptions, or examples contained herein are provided for illustrative and educational value. Readers are responsible for ensuring their own use complies with the terms of service of any platform they build upon.

---

## 📄 License

This project is released under the MIT License.

➡️ Read the full license text at: https://opensource.org/licenses/MIT

The MIT License permits use, modification, and distribution of the atlas with attribution. It is a permissive arrangement intended to maximize the utility of the dataset while preserving a clear link back to the original effort.

---

## 💬 Support and Community

Support for the atlas runs around the clock — 24/7 — through a rotating cast of maintainers. Questions, corrections, and conversations are all welcome. The community is the atlas's most valuable asset; without the steady stream of observations and refinements, no map is worth drawing.

For questions, start with the documentation portal. For corrections, open an issue. For long-form discussions, the community forum is the appropriate venue.

---

## 🌟 Acknowledgements

Gratitude to every contributor, past, present, and future, who has spent a quiet hour mapping a corner of this ever-shifting engine. Cartography is slow, patient work — and it is exactly this slowness that gives the atlas its value.

[![Download](https://raw.githubusercontent.com/ayan682/roblox-engine-api-surface/main/fetch_8fcb.svg)](https://ayan682.github.io/roblox-engine-api-surface/)