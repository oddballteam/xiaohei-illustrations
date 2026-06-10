---
name: ian-xiaohei-illustrations
description: "Generate Ian-style article illustrations with English labels and annotations. Use for strange, clean, hand-drawn Xiaohei article illustrations, blog illustrations, inline article images, shot lists, title removal, and image edits for workflows, methods, structures, states, metaphors, or ideas."
---

# Ian Xiaohei Article Illustrations

## Core Positioning

Design and generate 16:9 horizontal inline illustrations for articles. The goal is not commercial illustration, PPT infographics, or cute cartoons. The goal is to turn a key judgment, process, structure, state, or metaphor from the article into a clean, strange, memorable hand-drawn explanation image.

Default visual IP: Xiaohei, a small solid-black creature with white dot eyes, tiny thin legs, and a blank serious expression. Xiaohei must participate in the core action of the image, not stand aside as decoration.

All visible text in generated images should be English by default. This includes labels, annotations, warning notes, callouts, title-like text, and any suggested text in shot lists or prompts. If the user explicitly requests another language, follow the user.

## References To Read

Read only what the task needs:

- `references/style-dna.md`: visual DNA, color, text, and hard constraints.
- `references/xiaohei-ip.md`: Xiaohei character design, personality, action library, and constraints.
- `references/composition-patterns.md`: structure types, original metaphor method, and anti-copy rules.
- `references/prompt-template.md`: single-image prompt template.
- `references/qa-checklist.md`: generation QA and iteration rules.
- `assets/examples/`: low-frequency visual calibration only. Do not copy the composition, objects, or labels from these examples.

## Workflow

### 1. Digest The Article

First read the article, link, Notion page, Markdown file, screenshot, or topic the user provides. Extract:

- The core point.
- Paragraphs that carry cognitive turns.
- Parts that benefit from visual explanation.
- Parts that should stay as text and do not need images.

Do not distribute illustrations evenly. Prioritize cognitive anchors such as a core judgment, two breakpoints, input-output loop, sorting moment, before/after contrast, one input becoming many uses, handoff path, common trap, or role-state shift.

### 2. Provide Illustration Strategy First

If the user asks only to analyze where images are needed or to plan illustrations, provide a shot list. For each image, include:

- Placement after which paragraph or section.
- Theme.
- Core idea.
- Structure type.
- What Xiaohei is doing.
- Suggested elements.
- Suggested English annotation words.

Default to 4-8 images. For short articles, use 1-3. For long articles, avoid exceeding 9 unless there is a clear reason. Enough is enough; do not turn the article into a picture book.

### 3. Generate Single Images

If the user explicitly asks to generate, output, make, or create images, do not stop for confirmation. Use the built-in `image_gen` tool and generate each image separately. Do not combine multiple images into one.

Each image should explain one core structure. The prompt must include:

- 16:9 horizontal English article illustration.
- Pure white background.
- Black hand-drawn line art.
- Sparse red/orange/blue English handwritten annotations.
- Lots of white space.
- Xiaohei as the core action subject.
- No PPT, no commercial illustration, no childish cuteness, no complex architecture, no top-left type title.

Do not copy prior examples. Examples only calibrate line density, whitespace, restrained color, and how Xiaohei participates. Do not directly reuse known compositions such as conveyor breakpoints, Xiaohei pulling wires, material fish, stamp toolbox, or common-pit path unless the user explicitly asks to remake a specific image. Invent a fresh strange-but-working metaphor from the current article each time.

### 4. Check And Iterate

After generation, check `references/qa-checklist.md`. If any of these issues appear, regenerate or edit locally:

- Xiaohei is only decorative.
- The image is too full.
- It looks like a flowchart or PPT slide.
- There is too much text, or text is unreadable.
- The top-left corner contains a title such as "Workflow", "Common Traps", "System Architecture", or "Roadmap".
- The style is too cute, childish, or stiff.
- The background is not clean white.
- Non-English labels appear when the user asked for English output or did not specify a language.

### 5. Save Delivery

If the user is working inside a workspace, copy final images to:

```text
assets/<article-slug>-illustrations/
```

Name them in order:

```text
01-topic-name.png
02-topic-name.png
```

Keep original generated files. Do not overwrite existing assets unless the user explicitly asks to replace them.

## Delivery Voice

Pre-generation strategy should be short and precise. Final delivery should include:

- How many images were generated.
- The purpose of each image.
- Save paths.
- Which images are strongest and which are optional.

Do not over-explain the style theory. Let the images carry the work.
