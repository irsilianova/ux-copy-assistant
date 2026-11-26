# Error messages

## Definition

An error message explains what prevented someone from completing a task and how they can move forward. A field error may need only a correction. A failed operation may also need to explain what happened to the person’s work.

## Core technique

Start with two questions: **What does the product know went wrong? What can the person do about it?** Include the cause when it’s known and helps them choose their next step.

| Intent | Sentence frame | Example |
| --- | --- | --- |
| Complete a missing field | Enter [missing information]. | Under **Email address**: **Enter your email address** |
| Correct a value | [What would make this entry valid?] | Under **Verification code**: **Enter all 6 digits** |
| Resolve a conflict | [What changed or is unavailable]? [What can I choose instead?] | **That time slot was just booked. Choose another time.** |
| Recover from a failed operation | Couldn’t [action]. [What happened to my work?] [Next step]. | **Couldn’t send your reply** · Your draft is saved. · **Try again** |

Read the message once as someone trying to recover. **Invalid file** leaves the next step open. **Choose a PNG or JPG** gives a precise correction *if file type is what failed*. An oversized JPG needs a size limit instead.

## Language rules

### Allowed

- **Lead with the fix when it explains the problem.** Under **Verification code**, **Enter all 6 digits** covers both the missing information and the correction. A separate **Invalid code** heading adds little.
- **Name the operation that failed.** **Couldn’t save your changes** gives someone more to work with than **Something went wrong**, even when the cause is unknown.
- **Clarify what happened to the work.** If an upload failed but the file is still attached, **Your file is still attached** tells someone they can retry without finding it again. Include that reassurance only when it’s true.

### Avoid

- **Blame.** **You entered the wrong date** leaves the person guessing. If the end date is too early, say **Choose an end date after the start date**.
- **Invented explanations.** A failed save doesn’t prove the person is offline. Mention the connection only if the product can verify that it’s the cause.
- **A retry that can’t work.** Re-uploading the same oversized file will fail again. Give the accepted limit and an action such as **Choose another file**.

### Use with caution

- **“Try again.”** It’s useful when repeating the action could succeed. If the outcome is uncertain and retrying could duplicate a booking, direct the person to check their bookings first.
- **Technical details.** Include an error code when someone can use it, such as when contacting support. Lead with the problem and next step so understanding the code is optional.
