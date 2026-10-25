# CSS Meme Slider 🎭📊

A responsive, fully interactive meme carousel website engineered entirely with **pure HTML5 and CSS3, without using a single line of JavaScript**. The project uses advanced CSS selectors and native structural bindings to synchronously cycle layouts, control active element styles, and manage multi-viewport scaling behaviors.

🔗 **[Live Demo](https://morevna.github.io/cssMemeSlider/)**

---

## 🛠️ Tech Stack & Architecture

- **Core Engine:** Semantic HTML5 layout architecture.
- **Styling & Logic:** Pure CSS3 (CSS Grid, Flexbox), zero preprocessors (`.css` format only).
- **State Handling:** Functional input routing via `<input type="radio">` paired with custom structural sibling combinations (`:checked ~ .slide`).
- **Layout Integrity:** 100% relative length constraints (`rem`, `%`, `vw`, `vh`, `fr`) achieving elastic fluid scaling.

---

## 🚀 Key Technical Features

- **Zero-JavaScript State Machine:** Replaced typical programmatic runtime scripts entirely by leveraging native radio button form inputs. Managing interactive toggles maps immediate visual alterations directly across the element tree.
- **Synchronized Slide & Caption Transitions:** Configured complex, fluid layout transforms and animations. Activating interactive nodes smoothly translates both photographic meme blocks and independent text node strings concurrently.
- **Strict DOM Flow Adherence:** Designed the complete grid structure within the document's natural static layout stream. Avoided rigid coordinate offsets (`position: absolute/fixed`, `top`, `left`, `float`) to maintain pristine adaptive layout behavior.
- **Enhanced Interactive Hitboxes:** Enlarged control navigation targets using padded bounding layers to guarantee consistent UX feedback on pointing devices.
- **Pseudo-Element Elimination Architecture:** Built the application without relying on CSS pseudo-elements (`::before`, `::after`), demonstrating clean implementation using exclusively native structural tags and interactive pseudo-classes (`:hover`, `:active`).
- **Responsive Elastic Adaptation:** Engineered custom responsive grid alignments adjusting layouts gracefully down to mobile viewports (minimum 500px thresholds) with fluid bounding margins.

