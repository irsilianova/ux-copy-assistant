# Modals

## Definition

A modal is a dialog that brings one task, decision, or piece of information into focus. Someone completes or dismisses it before returning to the underlying screen. The heading establishes the task, the body adds details needed for the decision, and the buttons name the available actions.

## Core technique

Read the heading and buttons together. Can someone tell what they’re deciding and what each button will do? Then check the body for any consequence they need to know before choosing.

| Intent | Sentence frame | Example |
| --- | --- | --- |
| Complete a small task | I want to [task]. When I’m done, I can [action]. | **Rename playlist** · Field: **Playlist name** · Buttons: **Save changes** / **Cancel** |
| Confirm a consequential action | Do I want to [action]? What happens if I do? | **Delete “Road trip”?** · The playlist will be deleted. The songs will stay in your library. · **Delete playlist** / **Keep playlist** |
| Resolve an interrupted task | If I leave now, what happens to [work]? | **Discard your edits?** · Your changes since the last save will be lost. · **Discard edits** / **Keep editing** |

## Language rules

### Allowed

- **A heading that names the task or decision.** Use **Rename playlist** for a short form and **Delete “Road trip”?** for a confirmation. Including the item name helps someone catch a mistaken selection.
- **Body copy that changes the decision.** Whether deleting a playlist also deletes its songs is worth explaining. For a straightforward rename, the heading and field label may already be enough.
- **Buttons with distinct outcomes.** Under **Cancel this booking?**, use **Cancel booking** and **Keep booking**. Each label makes sense even if someone skims the body.

### Avoid

- **Generic confirmation copy.** **Are you sure?** with **Yes** and **No** makes someone remember which action opened the dialog. Put the action and its object in the heading.
- **Three versions of the same sentence.** **Delete playlist?** → “Do you want to delete this playlist?” → **Delete playlist** adds a line without adding information. Explain a consequence or omit the body.
- **Unrelated decisions.** A modal about discarding edits should resolve what happens to those edits. An invitation to enable backups can wait until the person finishes the task.

### Use with caution

- **Destructive verbs.** Match the wording to the product’s behavior. **Remove from playlist**, **Move to trash**, and **Delete permanently** describe different outcomes.
- **Generic dismissal labels.** **Close** works when someone is simply leaving an informational modal. **Keep editing** is more useful when closing the modal returns them to unfinished work.
