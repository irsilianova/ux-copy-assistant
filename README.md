# UX Copy Assistant

Write or review UX copy for any interface context. Send a screen brief, a screenshot, existing strings, or a link to a Figma frame. Include the language, what the person is trying to do and any known product constraints.

## Try it

“Review the reminder settings on this frame. People can choose several days. Write the labels in English and explain your recommendations in Russian.”

The assistant returns Recommended Copy and a short Rationale. Concerns flags a concrete control mismatch, missing product fact or layout constraint when relevant. For example, a multi-day selection shown with radio buttons would call for checkboxes.

## Editing a design

Review the proposed strings, then confirm the frame and the changes you want applied. The assistant can update the approved text layers through the remote Figma MCP server when connected with canvas editing access. Follow the host’s Figma sign-in flow with an account that can edit the target file. With a screenshot or read-only access, use the layer-by-layer copy in chat.

## Package contents

The workflow is in `skills/write-ux-copy/SKILL.md`. Its `references/` directory contains the approved Markdown guides for nine interface elements, four screen or state patterns, and tone of voice. The assistant consults them in that order. To revise guidance for future runs, update the bundled reference and release the updated plugin.
