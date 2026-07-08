# QA Checklist

## Must Pass

- It is 16:9 horizontal.
- The background is clean white.
- The Rough Rider operator is present.
- The Rough Rider operator performs the core action, not just decoration.
- The composition does not copy an old example; it creates a fresh metaphor for the current article.
- The image is strange, inventive, and interesting.
- It is simple and clean; the main subject takes no more than about 60% of the image.
- One image explains only one core structure.
- English annotations are sparse, short, and readable.
- Orange is used only for the main path or arrows.
- Red is used only for emphasis, problems, reminders, results, or a tiny operator accent.
- Blue is used only for secondary explanation, feedback, or system state.

## Failure Signals

Regenerate or edit if any of these appear:

- The top-left corner has a title such as "Common Traps", "Workflow", "System Architecture", or "Roadmap".
- The operator looks like a mascot, meme character, cute cartoon, or cowboy poster.
- The image looks like PPT, courseware, or a formal flowchart.
- The image reads as a western scene instead of a clean article explainer.
- Horses, guns, saloons, desert landscapes, flags, cavalry uniforms, or frontier props dominate without a concept reason.
- There are too many elements, arrows, or nodes.
- Text becomes paragraph-like explanation.
- The background has paper texture, shadows, gradients, beige tone, or noise.
- It uses a real UI screenshot or techy interface.
- Text is unreadable, misspelled in a distracting way, or not English when English was requested/defaulted.
- The image is too stiff and has no strange metaphor.
- The composition is too similar to an old example in `assets/examples/`.

## Iteration Methods

- Too ordinary: make the Rough Rider operator the action subject and add one strange but coherent metaphor.
- Too complex: remove nodes; keep one action and 3-5 short labels.
- Too cute: emphasize deadpan, blank serious expression, not cute, not mascot.
- Too western: remove frontier props and return to a sparse product-sketch composition with only the operator carrying the Rough Rider styling.
- Too PPT-like: remove titles, borders, tidy grids, and excess arrows; turn it into a hand-drawn scene.
- Too similar to an old example: keep the core idea, but change the main object and the operator's action.
- Text is wrong: prefer local editing; if many labels are wrong, regenerate with fewer labels.
- Non-English text appears: regenerate or edit with explicit "English labels only; no Chinese text."

## Delivery Judgment

A strong image should make the reader think "that's a little strange" and then understand the structure within one second.

If the first impression is a western illustration or tutorial page instead of a strange product sketch with a distinctive operator, it does not pass.
