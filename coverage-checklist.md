# HTML Coverage Checklist

This checklist compares the guide's 55 lessons, Q&A pages, examples, and element reference against the main authoring topics in the HTML Living Standard.

It tracks practical coverage for people writing HTML. `Covered` means a lesson introduces the topic. It does not mean every specification detail or every attribute value is documented.

## Current coverage

| Topic | Status | Existing coverage | What the status means |
| --- | --- | --- | --- |
| Document basics, HTML syntax, tags, attributes, comments, and character references | Covered | Lessons 01-10 | The guide explains document structure and common authoring syntax. Detailed parser recovery and conformance rules need more depth. |
| Headings, paragraphs, text meaning, quotations, links, URLs, and lists | Covered | Lessons 11-18 | Core text and navigation elements have lessons, questions, and examples. |
| Images, figures, responsive images, audio, video, iframes, SVG, and MathML | Partial | Lessons 19-25 | The common authoring patterns are covered. Image maps, canvas, object, and embed need focused explanations. |
| Tables and accessible table structure | Covered | Lessons 26-27 | Data tables, headers, captions, and accessible relationships are covered. |
| Forms, input types, labels, groups, selection controls, buttons, validation, submission, and autocomplete | Partial | Lessons 28-36 | The main form workflow is covered. A complete per-control attribute and behavior reference is still needed. |
| Semantic page structure, landmarks, accessibility, ARIA, language, and text direction | Partial | Lessons 37-42 | Practical usage is covered. HTML content categories, content models, and detailed nesting rules need a dedicated explanation. |
| Details, dialog, popover, templates, visibility, and interaction attributes | Partial | Lessons 43-47 | Common native features are covered. Custom elements and shadow DOM are introduced only lightly. |
| Icons, search and sharing metadata, and microdata | Partial | Lessons 48-50 | Common patterns are covered. The less common metadata and resource-link options are not exhaustively listed. |
| HTML safety, obsolete elements, validation, practice, and glossary | Covered | Lessons 51-55 | The guide covers practical safety, debugging, and review topics. |

## Remaining work

### 1. Add focused lessons for elements currently listed only briefly

- [ ] `<base>` and how it changes relative URLs and default link targets.
- [ ] `<map>` and `<area>` for image maps, including accessible names and coordinates.
- [ ] `<canvas>`, its fallback content, and its relationship to JavaScript.
- [ ] `<object>` and `<embed>`, including fallback content and practical limitations.
- [ ] `<output>`, `<meter>`, and `<progress>`, with examples showing their distinct meanings.
- [ ] `<ruby>`, `<rt>`, and `<rp>` for pronunciation and annotation.
- [ ] `<hgroup>` and `<menu>`, including when ordinary headings or lists are a better fit.
- [ ] `<wbr>` and useful line-break opportunities.
- [ ] `<del>` and `<ins>` for editorial changes. Existing examples show them, but they need a focused explanation of their attributes and meaning.

Add a lesson, matching Q&A page, and matching example for each selected topic. Update the README lesson table and chapter navigation at the same time.

### 2. Explain content categories and nesting rules

- [ ] Explain metadata, flow, sectioning, heading, phrasing, embedded, interactive, and palpable content in plain language.
- [ ] Show common allowed-parent and allowed-child rules, including paragraphs, lists, headings, links, buttons, and forms.
- [ ] Explain transparent content models and why some elements inherit their placement rules from their parent.
- [ ] Distinguish browser error recovery from valid, conforming markup.

### 3. Expand the attributes reference

- [ ] Keep the existing global-attribute lesson and create a searchable per-element attribute index.
- [ ] For each attribute, record its owning element, purpose, value type, Boolean or enumerated behavior, and any important constraints.
- [ ] Cover event-handler attributes separately as a security-sensitive topic, and recommend external scripts for normal authoring.

### 4. Cover document metadata and resource loading in more depth

- [ ] Explain common `<link>` relationships and which resource each one declares.
- [ ] Compare classic scripts, modules, `async`, and `defer`, including execution timing.
- [ ] Explain resource-related attributes such as `crossorigin`, `referrerpolicy`, `integrity`, `loading`, and `fetchpriority` where applicable.
- [ ] Explain the purpose and risks of `<base>` in the context of document URLs.

### 5. Deepen form coverage

- [ ] Document every standard `<input>` type and the attributes specific to each type.
- [ ] Cover successful controls, disabled and read-only controls, constraint validation, and form ownership.
- [ ] Explain submit buttons that override the form's action, method, encoding, or target.
- [ ] Add the distinct semantics and accessibility requirements for `<output>`, `<meter>`, and `<progress>`.

### 6. Clarify syntax, parsing, and conformance

- [ ] Explain optional start and end tags, void elements, quoted values, duplicate attributes, and character references.
- [ ] Describe common parse errors and how browsers recover from them.
- [ ] Add a focused HTML versus XHTML/XML syntax comparison, or explicitly mark XML serialization as outside this guide's scope.

## Scope boundary

The HTML Living Standard also specifies browser implementation details and APIs for documents, interaction, page loading, communication, workers, storage, and rendering. This repository is a practical HTML authoring guide, not a copy of the full browser platform specification. Add those subjects only when they help readers write, understand, or debug HTML documents.

## Audit notes

- The repository currently has 55 lesson files, 55 matching Q&A files, and 55 matching example files.
- Each lesson, Q&A, and example has chapter navigation, and the internal Markdown links were checked for missing targets.
- The element inventory was compared with the HTML Living Standard's conforming element index and section structure on 19 November 2026.
- Update this checklist whenever lessons, Q&A pages, examples, or the element reference change.
