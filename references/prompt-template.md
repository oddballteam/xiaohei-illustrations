# Image Prompt Template

Generate each image separately. Replace variables from the article content. Do not combine multiple images into one.

```text
Generate one standalone 16:9 horizontal English article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten English annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
Restrained Rough Rider-inspired operator, replacing the little black operator. Small compact diagram-friendly figure, skull-like or mask-like face, hollow dark eyes, wide-brim hat, simple scarf with a small red/orange accent, blank serious expression, slightly uneven hand-drawn body shape. The operator must perform the core conceptual action, not decorate the scene. Make the operator serious, deadpan, useful, and slightly strange, not cute. Do not westernize the whole image; keep the sparse product-sketch system composition.

Theme:
{article illustration theme}

Structure type:
{structure type: Workflow / System Partial / Before-After / Role State / Conceptual Metaphor / Method Layers / Map Route / Mini Comic Sequence}

Core idea:
{the core idea this image should express}

Composition:
{specific scene: where the Rough Rider operator is, what the operator is doing, main objects, how information or action flows}

Suggested elements:
{element 1} / {element 2} / {element 3} / {element 4}

English handwritten labels:
{label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use:
Black for main line art and the operator. Orange for main flow/path/arrows and optional tiny scarf/hat accent. Red only for key warnings/problems/results or a small operator accent. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten English labels, preferably 1-4 words each. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not use Chinese labels unless explicitly requested. Do not make it a formal diagram, course slide, or dense explainer. Do not add horses, guns, saloons, desert landscapes, flags, cavalry uniforms, or frontier props by default. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## Image Editing Prompts

Remove a top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Increase strangeness:

```text
Regenerate this illustration with the same core meaning and simple layout, but make the Rough Rider operator more central to the conceptual action. The operator should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, English-labeled, and not cute. Do not turn the whole image into a western scene.
```
