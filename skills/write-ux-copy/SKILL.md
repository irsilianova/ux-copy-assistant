---
name: write-ux-copy
description: Write or review UX copy for any interface context, from one label to a full flow. Use for UI microcopy, screen reviews, and approved text changes in Figma.
---

# Write or review UX copy

Use the requested UI language, otherwise preserve the product’s existing language. Explain decisions in the user’s language. Work from a brief, pasted strings, screenshot, or Figma selection. When given a design link and access, inspect the target frame, visible text, surrounding controls and relevant variants. Preserve established terminology, variables, plural forms and product behavior. Keep sound existing copy in reviews.

## Silent review

1. Establish the user's goal, the actual product state and the outcome of each action. Ask one focused question only if a material ambiguity prevents useful copy. Otherwise draft what is supported and flag the specific gap.
2. Read the guides for the elements present: [buttons](references/buttons.md), [checkboxes](references/checkboxes.md), [radio buttons](references/radio-buttons.md), [toggles](references/toggles.md), [text field labels](references/text-field-labels.md), [placeholders](references/placeholders.md), [links](references/links.md), [tooltips](references/tooltips.md), [notifications](references/notifications.md).
3. Then read the applicable screen or state guides: [empty states](references/empty-states.md), [modals](references/modals.md), [error messages](references/error-messages.md), [success screens](references/success-screens.md). A notification reporting a failure can use both notifications and error messages. For an unlisted pattern, use the relevant element guides and the supplied context.
4. Check the whole recommendation against [tone of voice](references/tone-of-voice.md). Read headings and actions together. Check fit, choice logic, and whether the product can support every promise. Keep this review silent; omit file names, checklists and intermediate drafts from the answer.

## Response

Use one block per screen in reading order. Link the screen name to its actual Figma frame when available. Use a plain title when there is no verified or supplied link. Never invent a URL. Include each requested element or changed string once, using a distinct label for each option or repeated element.

```markdown
## UX Copy: [Screen name](Figma frame URL)

### Recommended Copy

**[Element]**: [Final UI string]

### Rationale

[One or two sentences about the user’s situation and the wording that helps them understand or act.]

### Concerns

[Concrete constraint, consequence, and smallest workable change.]
```

Include Concerns when there is something actionable. For example, if people may choose several days but the design uses radio buttons, recommend checkboxes and give usable day labels. If the backend confirms submission only, use “Request sent” and flag what would be needed to say “Approved”. Distinguish a confirmed constraint from an open question. Avoid generic risks or a list of alternatives unless asked.

## Apply in Figma

After showing the proposed strings, offer to apply them to the named frame. If the user wants chat output only, finish with the recommendation. With a screenshot alone, ask for the editable frame link as part of the offer. Treat a request to draft directly in Figma as a request for the proposal and approval flow. An explicit instruction to apply a previously shown set of strings to a specific frame is sufficient confirmation.

After confirmation, use the connected Figma canvas editing capability if available. Match approved strings to the exact text nodes or instance text overrides. Recheck current text before writing; if a layer changed since review, pause that edit and show the discrepancy. Apply only approved wording, retaining rich-text styles, links, bindings and component structure. Record confirmed changes individually so retries skip completed edits. Component swaps and design changes flagged in Concerns need their own explicit approval.

Read back the updated text and check the rendered frame for clipping or overflow when a preview is available. Report the frame link, what was applied and any skipped or unverified items. If access is read-only or a write tool is unavailable, say so and return the exact strings keyed to their layers. Never report an edit based solely on the recommendation.
