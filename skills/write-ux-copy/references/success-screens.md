# Success screens

## Definition

A success screen confirms that someone has completed a task or that the service has received their request. Use a dedicated screen when people need a clear end to a flow, details to keep, or an explanation of what happens next. For a small action such as copying a link, a brief notification is usually enough.

## Core technique

Finish this sentence from the product’s point of view: **“We can confirm that ___.”** Turn the answer into the heading. Then read it from the user’s point of view: **“Is my part done? What happens next? Do I need to keep anything?”** Include only the details that answer a relevant question.

| Intent | Sentence frame | Example |
| --- | --- | --- |
| Confirm a finished task | [What the person came to do] is complete. | **Your appointment is booked** · Tuesday, 8 June at 10:30 am · **Add to calendar** |
| Confirm receipt of a request | We’ve received [request]. [How the person will hear back]. | **We’ve received your application** · We’ll email you when there’s a decision. |
| Confirm a scheduled action | [Action] is scheduled for [date]. | **Your transfer is scheduled for 12 June** · €50 to Alex Morgan · **View transfer** |
| Give someone a record | [Outcome]. Here’s [what to keep or retrieve]. | **Your order is confirmed** · Order number 48216 · **View receipt** |

Check the verb against the latest status the product can verify. **Your transfer is scheduled**, **Your transfer has been sent**, and **Alex has received your transfer** describe three different milestones. Choose the one the system can confirm.

## Language rules

### Allowed

- **A heading that names the outcome.** Use words someone would use to describe what they just did. **Your table is booked** answers “Did my booking go through?” even if the person reads nothing else.
- **Details worth checking or keeping.** Show the date and time for an appointment, the amount and recipient for a transfer, or a reference number someone can use later. Give each value a recognizable label, such as **Booking reference**.
- **A specific next step when there is one.** Say who acts next. **We’ll email you when your order is ready** tells someone to wait. **Bring your booking reference when you collect your order** tells them what to do.
- **An action that follows naturally.** **View tickets**, **Download receipt**, and **Track application** each give someone a reason to continue. If their task is complete, the screen can also be a natural place to stop.

### Avoid

- **Generic success messages.** **Success!** and **All done!** leave the outcome unnamed. **Your subscription is canceled** answers the question that brought someone to the screen.
- **Turning a pending outcome into a promise.** Use **We’ve received your refund request** when review is still pending. Reserve **Your refund has been issued** for the point when the product can confirm that step.
- **Repeating the heading in the body.** Under **Your tickets are booked**, “You’ve successfully booked your tickets” adds little. **You can find them in My tickets** tells someone how to get back to them.
- **Making an optional action look required.** After checkout, **Continue** can leave someone wondering whether their order went through. **View order** makes the destination clear.

### Use with caution

- **Timing and delivery claims.** Use **We’ll email you within 2 working days** only when the service can meet that commitment. **We’ve sent your receipt to alex@example.com** requires confirmation that the email was sent.
- **Success while another step is required.** If someone still needs to verify their email before they can use their account, lead with **Check your email to finish signing up**. Calling the account ready would make it too easy to leave early.
- **Celebratory language.** **You finished the course!** fits a personal achievement. For a canceled booking or a closed account, a neutral confirmation usually fits the moment better.
