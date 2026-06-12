---
name: hayes-personal-illustrations
description: Generate article illustrations following my exclusive custom style. Supports creating hand-drawn weird-style inline illustrations, illustration suggestions, shot lists, title removal & image revision for Chinese articles, blog posts, Notion pages, workflow docs, methodology documents, structural diagrams, state visualization, conceptual metaphors and viewpoints. Uses my original Hayes IP by default, pure white hand-drawn line art, limited handwritten notes in red/orange/blue, clean layout with unrestrained imaginative visuals.
---

# Hayes Surreal Inline Article Illustration Generator
## Core Positioning
Design and deliver 16:9 horizontal inline illustrations for Chinese articles. This tool is not built for commercial artwork, PPT infographics or cute cartoon graphics. It converts core judgments, workflows, structures, statuses and conceptual metaphors from articles into clean, surreal, creative hand-drawn explanatory sketches that are easy to understand without reading like rigid instruction manuals.

My original IP **Hayes** is the fixed default character: a star & forest themed maiden with fixed full design, icy blue eyes and barefoot setting. She always carries out the core actions in each frame and must never serve as passive decorative filler standing aside.

## Reference Document Instructions
Access references on demand; do not load all context at once:
- `references/style-dna.md`: Style rules, color system, text specifications and forbidden designs
- `references/hayes-ip.md`: Hayes character appearance, personality, action library and creation bans
- `references/composition-patterns.md`: Composition types, original metaphor design methods and repeated usage constraints
- `references/prompt-template.md`: Independent single-image generation prompt template
- `references/qa-checklist.md`: Post-generation inspection and iteration standards
- `assets/examples/`: Only used for low-frequency style calibration, not included in default generation logic. Never copy the composition, objects or annotations from sample cases directly.

## Standard Workflow
### Step 1: Parse Source Content
Read submitted articles, external links, Notion pages, Markdown files or screenshots, then extract key information:
- Core viewpoints
- Paragraphs with cognitive turning points
- Content suitable for visual explanation
- Text-only sections that do not require illustrations

Avoid evenly adding illustrations across the full text. Prioritize cognitive anchor points: core judgments, workflow breakpoints, input-output closed loops, flow splitting, before-and-after comparisons, multi-purpose utilization, delivery pipelines, common pitfalls and character state changes.

### Step 2: Output Illustration Planning Strategy
If you only need illustration analysis & layout planning, deliver a shot list directly. Specify the following items for each illustration:
- Target paragraph placement
- Illustration theme
- Central message
- Composition type
- Specific actions Hayes performs
- Recommended graphic elements
- Proposed handwritten Chinese labels

Default quantity: 4–8 illustrations. Short articles: 1–3 illustrations; long articles should not exceed 9 illustrations unnecessarily. Keep the quantity concise and avoid turning the article into a picture album.

### Step 3: Independent Single Illustration Generation
When explicit generation requests are received, generate each artwork separately with no extra confirmation needed. Never combine multiple illustrations into one canvas.

Each image explains exactly one single core structure. Mandatory prompt components:
- 16:9 horizontal inline article illustration
- Solid pure white background
- Black hand-drawn sketch lines
- Sparse handwritten Chinese annotations in red/orange/blue
- Abundant negative blank space
- Hayes as the central action subject
- Strictly ban PPT infographic style, commercial illustration style, childish cute design, complicated architecture diagrams and top-left corner classification titles

Do not replicate existing sample compositions. Samples are only used to reference style density and character participation logic. Existing classic layouts (conveyor breakpoints, line pulling, material splitting, stamping pipelines, pit paths, etc.) cannot be reused unless replication is explicitly requested. Design a unique reasonable surreal metaphor tailored to the current text every time.

### Step 4: Inspection & Iteration
Check artwork against rules in `references/qa-checklist.md` after generation. Regenerate or partially revise the image if any of these issues appear:
- Hayes acts only as decorative ornament
- Frame is overly crowded
- Layout resembles formal flowchart or PPT slide
- Excessive Chinese text or obvious typos
- Classification titles (Common Pitfalls / Workflow Diagram / System Architecture etc.) appear in the top-left corner
- Art style looks overly cute, childish or rigid
- Background is not clean solid pure white

### Step 5: File Saving & Delivery
For workspace usage, export finished illustrations to the following directory:
```text
assets/<article-slug>-illustrations/
```
Sequential naming rule:
```text
01-topic-name.png
02-topic-name.png
```
Preserve original generated source files. Do not overwrite existing assets unless explicit replacement permission is given.

## Delivery Specification
Keep pre-generation planning outputs concise and targeted. Final delivery package needs to include:
- Total number of generated illustrations
- Placement purpose for each artwork
- Full storage file path
- Stable recommended illustrations & optional spare drafts

Avoid lengthy style theory elaboration; let the illustrations convey information intuitively.
