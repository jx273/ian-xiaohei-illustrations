# Hayes Personal Illustrations
> Transform judgments, workflows, statuses and metaphors from Chinese articles into clean, hand-drawn, surreal inline illustrations with solid white backgrounds.
>
> 16:9 horizontal layout | Hayes exclusive IP | Pure white hand sketch | Sparse Chinese annotations in red, orange & blue | Custom Codex Skill

---

## Repository Overview
Hayes Personal Illustrations is a custom Codex Skill designed to guide AI Agents to generate inline illustrations for Chinese articles, posts, blogs, Notion pages and methodology documents.

This is not a generic illustration prompt bundle nor a PPT infographic template. Its core logic: first extract cognitive anchor points from your text, then convert one single judgment, workflow, structure, state or metaphor into a memorable 16:9 hand-drawn explanatory sketch.

The default built-in visual IP is **Hayes**, my original star-and-forest themed young girl character with fixed full design, icy blue eyes and barefoot setting. Hayes is never a mascot, sticker or background ornament standing idly in the corner. Instead, she acts as a serious operator executing surreal functional tasks within the visualized system.

One-sentence summary:
**Instead of simply attaching a random picture to an article, the AI visualizes one key cognitive action extracted from your writing.**

---

## Intended Users
This tool is perfectly suited for people who:
- Write Chinese articles and need inline illustrations and embedded artwork
- Create knowledge-based content, methodology documents and AI workflow materials
- Wish to visualize abstract judgments into tangible metaphors
- Prefer a lighter, more surreal illustration style with unique personal branding compared to standard PPT infographics
- Build content production pipelines on Codex and aim to reuse a unified consistent visual language

This repository is **NOT suitable** for users who:
- Require commercial illustrations, brand key visuals or refined flat design artwork
- Need formal PPT infographics, complex architecture diagrams or rigid flowcharts
- Want cartoon-style characters, cute IP designs or meme sticker packs
- Intend to squeeze full paragraphs of explanations or complete course slides into a single image
- Demand fully editable vector source files

---

## Deliverables Generated
Default outputs:
- 16:9 horizontal inline article illustrations (PNG format)
- Shot list containing 4–8 suggested illustrations for one full article
- For each illustration: theme, core message, structure type, Hayes’ specific actions and recommended Chinese annotations
- Final PNG images saved to the workspace path: `assets/<article-slug>-illustrations/`

Items this skill **will NOT produce**:
- PPTX / PDF / Keynote presentation files
- Editable SVG / HTML / Canvas graphics
- Commercial posters or cover key visuals
- Text-heavy infographics packed with lengthy descriptions

---

## Visual Style Specifications
This skill adheres strictly to my custom Hayes surreal inline illustration style:
- Solid pure white background; no paper grain, cream tint, shadows or gradients
- Thin hand-drawn black outlines with subtle natural line wobble
- Ample negative space; main subject occupies only 40%–60% of the canvas
- Limited handwritten Chinese annotations colored in red, orange and blue
- Each illustration conveys exactly one single action, structure, state or metaphor
- Hayes must perform the core action; she cannot serve merely as decorative filler
- Surreal, creative and clean aesthetic; no childish styling or overly cute character design

---

## Installation Guide
Clone the repository locally:
```bash
git clone https://github.com/[YOUR_GITHUB_USERNAME]/hayes-personal-illustrations.git
cd hayes-personal-illustrations
```

Copy the skill folder to your Codex skills directory:
```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./hayes-personal-illustrations "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Call the skill directly inside Codex after installation:
```text
Use $hayes-personal-illustrations to design and generate 5 surreal inline illustrations featuring the Hayes IP for this Chinese article.
```

---

## Usage Instructions
### Option 1: Generate Illustration Planning Shot List Only
```text
Use $hayes-personal-illustrations, skip image generation for now.
Analyze this article and output a shot list of roughly 5 illustrations.
For each entry, specify the target placement paragraph, theme, core meaning, structure type, Hayes’ actions and suggested Chinese annotations.

<Paste your full article content here>
```

### Option 2: Directly Generate Full Article Illustrations
```text
Use $hayes-personal-illustrations to create 4 surreal inline illustrations for the attached article.
Requirements: 16:9 horizontal ratio, pure white background, black hand-drawn outlines, limited handwritten Chinese notes in red/orange/blue.

<Paste your full article content here>
```

### Option 3: Generate a Single Standalone Concept Illustration
```text
Use $hayes-personal-illustrations to create one inline illustration for the concept: "Trust cannot be declared verbally; it is built piece by piece with solid evidence".
Keep the layout surreal and clean, and assign Hayes to carry out the core action entirely.
```

### Option 4: Edit Existing Illustrations (Remove Titles / Miswritten Text)
```text
Use $hayes-personal-illustrations to edit this illustration. Delete the top-left title "Workflow Diagram" and retain all other visual elements unchanged.
```

More prompt examples are available at [examples/prompts.md](examples/prompts.md).

---

## End-to-End Workflow
1. Parse input content: full articles, Markdown text, Notion pages, screenshots or standalone concepts
2. Extract core viewpoints, cognitive turning points, workflow structures and text segments suitable for visualization
3. Output a structured shot list, selecting exactly one cognitive anchor point per illustration
4. Assign a structure category for each piece: Workflow / Partial System View / Before-After Comparison / Character State / Conceptual Metaphor / Layered Methodology / Route Map / Comic Panel
5. Design an original low-tech, logically sound surreal physical metaphor unique to your text
6. Assign the core interactive action to the Hayes IP character
7. Call the image generation model separately for every single illustration
8. Conduct full QA inspection against the checklist: pure white background, sufficient blank space, meaningful Hayes actions, proper Chinese annotations, non-PPT aesthetic, no copied sample layouts
9. Export final PNG files, then report the usage scenario and storage file path

---

## Repository Directory Structure
```text
.
├── README.md
├── LICENSE
├── NOTICE.md
├── assets/
│   └── personal-qr-code.jpg
├── examples/
│   ├── images/
│   │   ├── 01-two-breakpoints.png
│   │   ├── 02-sort-by-purpose.png
│   │   └── ...
│   └── prompts.md
└── hayes-personal-illustrations/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── assets/
    │   └── examples/
    └── references/
        ├── style-dna.md
        ├── hayes-ip.md
        ├── composition-patterns.md
        ├── prompt-template.md
        └── qa-checklist.md
```

Only the subfolder below needs to be installed into Codex:
```text
hayes-personal-illustrations/
```

The root-level README, LICENSE, NOTICE and examples folders are documentation files for GitHub sharing only.

---

## Important Notes
- Keep all handwritten Chinese annotations short for stable generation results.
- One illustration visualizes exactly one core structure; avoid turning articles into dense instruction manuals.
- Hayes must drive the primary action in each frame. If the illustration still makes complete sense after removing Hayes, the character is reduced to unnecessary decoration and requires revision.
- Sample preview images are for calibrating line weight, negative space usage, restrained color scheme and character interaction logic only; never duplicate their layouts directly.
- AI image models may produce typos, erroneous labels, style drift or unwanted extra titles; perform manual checks after generation completes.
- If severe Chinese character errors appear, reduce the number of annotations and regenerate the artwork.

---


## License
Released under the MIT License. Refer to the full terms in [LICENSE](LICENSE).

