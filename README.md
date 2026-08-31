RLS Enrichment Slides
A Claude skill that builds supplementary study slides alongside a professor's original Reduced Lecture Slides (RLS), adding teaching value the RLS alone doesn't provide, without ever altering the original slides.
What it does
Given an RLS deck plus supporting material (lecture transcript, professor notes, annotated slides, handouts), this skill identifies conceptual blocks where extra explanation, clarification, or synthesis would genuinely help a medical student, then builds enrichment slides in Claude Design and inserts them immediately after the relevant original page.

The original RLS is never edited, reflowed, or reordered. Enrichment slides only supplement it.
Inputs
Original RLS (slides, PDF, or images)
Optional supporting material: lecture transcript, professor notes, annotated slides, handouts
Target visual system/style to match, if one exists
Core principle
Every enrichment slide must pass this test before it's created.

Does this page help a medical student understand, interpret, integrate, apply, recognize, or remember the lecture better than the original RLS page alone?

If not, the slide isn't created. Extra source text being available is not itself a reason to add a slide.
What it builds
Enrichment slides can take the form of mechanism diagrams, comparison tables, directional-change maps, annotated images, graph interpretations, equation-to-physiology frameworks, diagnostic reasoning pathways, sequence/decision trees, integrated concept maps, or structured prose, whichever best fits the concept.

Slide titles name the medical concept itself, never the source material.
What it preserves
Mechanism steps, exact values/ranges/units/equations, exceptions and qualifiers, clinical examples, image-recognition features, graph and table details, professor explanations, and any explicitly emphasized or testable material. Content is reorganized and synthesized freely but never trimmed for density; crowded slides are split rather than compressed.
What it won't create
Raw transcript dumps, source-completeness appendices, slides that restate the RLS, generic "exam cue" boxes, unsupported outside teaching, or model-inferred "high-yield" claims presented as professor emphasis.
Workflow
Read the RLS and all supplied source material, identify conceptual blocks
For each block, apply the core-principle test to decide whether enrichment is warranted
For warranted slides, choose the best-fitting format and draft content
Build the slide in Claude Design, inserted after the relevant original RLS page
Re-check each slide against the quality test before finalizing; redesign, split, or cut as needed
Installation
Claude Design shares the skills system used across Claude.ai. To install this skill:

Go to Settings > Customize > Skills in Claude
Click "Add custom skill"
Upload the SKILL.md file, or a ZIP of the skill folder (the ZIP must contain the folder itself at the root, not just the SKILL.md file)
Toggle the skill on

Once installed, it's available to Claude Design sessions automatically. (Source: Anthropic Help Center, "How to create custom skills" and "Use skills in Claude")
Usage
Trigger it by asking to enrich an RLS, expand a lecture deck with transcript or notes content, or build a combined deck in Claude Design. Pasting a transcript/notes alongside an RLS and asking for enrichment slides is enough to trigger the skill directly.

