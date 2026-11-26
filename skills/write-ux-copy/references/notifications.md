# Notifications

## Definition

An in-app notification tells someone what happened, what a current condition means for them, or what they can do next. A **toast** or **snackbar** gives brief feedback, often after an action. A **banner** communicates a condition affecting a page, feature, or the whole service. An **inline notification** sits beside the part of the interface it concerns.

## Core technique

Start with the question someone has at that moment. Lead with the answer. Add a consequence or next step only when it helps. The bold words are the notification copy.

| Intent | Sentence frame | Example |
| --- | --- | --- |
| Confirm an action · Toast | What happened to [item]? | **Draft saved** |
| Offer a reversal · Snackbar | [Result]. I can [action]. | **File archived** · **Undo** |
| Explain an ongoing condition · Banner | What’s happening, and how does it affect me? | **You’re offline. Changes will sync when you’re back online.** |
| Help someone recover · Inline notification | What went wrong here, and what can I do? | Beside an upload, **This file is too large. Choose one under 10 MB.** |

Test the copy against its placement. If a toast disappears before someone reads it, can they still finish the task? If they need the message to fix a problem, keep it visible near the affected part of the interface.

## Language rules

### Allowed

- **A specific outcome.** **Link copied** or **Invite sent to Sam** confirms what happened. For a simple success, that can be the whole message.
- **A title and body with different jobs.** Let the title name the condition and the body explain its effect. **Storage is full** → **Your files are safe, but new uploads are paused.**
- **An action that resolves the situation.** Under the storage message, **Manage storage** names a useful next step. For an interrupted upload that can succeed on another attempt, **Try again** works.

### Avoid

- **Severity labels as the whole message.** **Warning** names a category. **Your session ends in 2 minutes** tells someone what needs attention.
- **Blame or an invented cause.** If all the product knows is that an upload failed, say **Couldn’t upload the file**. Mention the connection only when the product can identify it as the cause.
- **Instructions that disappear too soon.** If someone must update their payment method to keep a subscription active, show the message somewhere they can return to. A temporary toast alone is easy to miss.

### Use with caution

- **Time estimates and promises.** Use **Changes will sync when you’re back online** only if syncing happens automatically. If the person needs to retry, say **You’re offline. Try again when you’re back online.**
- **Undo and retry actions.** Offer **Undo** only when the action can be reversed. Offer **Try again** only when repeating the same action could help. An oversized file needs a different file, so **Choose another file** is the more useful action.
- **Broad announcements.** Match the wording to the actual scope. **Comments are temporarily unavailable** is more useful than **The service is unavailable** when people can still read and edit their documents.
