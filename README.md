# Hotel Feedback Form

Semantic HTML form for structured guest feedback collection.

## Architecture

- **Layout** — `<header>` for intro + `<main>` for content isolation
- **Form** — POST method with external action endpoint
- **Grouping** — Multiple `<fieldset>` + `<legend>` for logical sections

## Input Controls

- Text & Email — `<input type="text">`, `<input type="email">` with required + placeholder
- Number — `<input type="number">` with min/max constraints
- Radio — Grouped via `name` attribute for single selection
- Checkbox — Multiple selection for choice reasons
- Select — Dropdown with pre-selected default
- Textarea — Multi-line feedback input

## Accessibility & Integrity

- Label-input pairing via `for`/`id`  
- Native validation (`required`, `type`, `min/max`)  
- Semantic structure for screen reader support

Pure HTML implementation — no CSS applied yet.

Focus: Data structure integrity before presentation layer.


