# Tooltips

## Definition

A tooltip is a short message attached to an interface element. It can name an icon, explain a term, or point out something someone can do with a feature. It usually appears on hover or keyboard focus and disappears when the person moves on.

## Core technique

Start with the question someone might have about the element. Write the shortest answer that resolves it. The bold words are the tooltip copy.

| Intent | Sentence frame | Example |
| --- | --- | --- |
| Name an icon’s action | I can use this to [action]. | On a chain-link icon, “I can use this to **copy link**” gives the label **Copy link**. |
| Explain a term | What does [term] mean here? | For *Local time*, **Times are shown in the city’s time zone.** |
| Help someone discover a feature | What can I do here? | Beside the search field, **Search by name or email**. |

Read the tooltip alongside the element that triggers it. **Copy link** gives an unlabeled icon a useful name. Beside a button already labeled **Copy link**, the same tooltip adds nothing.

## Language rules

### Allowed

- **Short action labels for icons.** Use one or two words when they identify the function clearly. **Mute** tells someone what the microphone button does. **Microphone** only names the picture.
- **Plain-language explanations.** Explain an unfamiliar term using words someone is likely to know. For *Version history*, **See who changed the file and when** gives the person a reason to open it.
- **One useful detail at a time.** Use sentence case and simple verbs. Aim for one or two lines. For a formatting toolbar, **Select text to add a comment** is enough to help someone try the feature.

### Avoid

- **Essential information in a disappearing message.** Keep required formats, legal terms, and instructions people need to finish a task visible on the page. If an upload only accepts PDFs, put **PDF files only** beside the upload control.
- **Status updates and feedback.** After someone saves a draft, show **Draft saved** as confirmation where they can notice it. They shouldn’t have to hover over **Save** to find out whether it worked.
- **Links, buttons, and other actions inside the tooltip.** Keep tooltip content read-only. If someone needs to open a link or make a choice, give them a control they can reach and interact with.

### Use with caution

- **Punctuation.** Leave the period off short labels such as **Copy link**. For a full-sentence definition or instruction, follow the product’s punctuation convention consistently. If the tooltip needs two sentences, punctuate both. Avoid questions and exclamation marks.
- **Longer explanations.** Treat three lines as an upper limit at the intended display size. If someone needs several steps or will need to refer back to the text, move it into visible helper text.
