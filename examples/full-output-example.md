# Example: full output from the skill

This is what the skill hands back after the interview in [interview-example.md](interview-example.md). LedgerLite is a made-up business.

## 1. Confirmed brief

- Product: LedgerLite closes a clinic's monthly books within 5 days, done for them. It does not file taxes.
- Audience: owners of dental, physio and vet clinics.
- Pain: "I spend every second Sunday matching receipts." It costs them 6 to 8 hours a month and missed claims.
- Proof: 3 clinics for 6 months. One found $4,200 in unclaimed expenses.
- Offer ladder: free review of last month's books, then a sample month-end report, then the first month free plus a free clean-up of last quarter. Cap: 4 new clinics this month.

## 2. Overview

| Email | Send day | Subject A | Subject B | B test changes | Offer | CTA |
|---|---|---|---|---|---|---|
| 1 | Day 0 | {{companyName}} month-end | sundays at {{companyName}} | Subject line only | Free review of last month's books | 15-minute call this week |
| 2 | Day 2 | (reply in thread) | (reply in thread) | Contrast line | Sample month-end report built for them | 15-minute call this week |
| 3 | Day 4 | (reply in thread) | (reply in thread) | Opening hook: quote vs cost framing | First month free plus free clean-up of last quarter | 15-minute call this week |

## 3. The emails

Character counts are for the body, rendered for a dental clinic, not counting the greeting and sign-off.

### Email 1, variant A (802 characters)

Subject: {{companyName}} month-end

Hi {{companyName}} team,

{{personalization}}

Does month-end at your {{biz}} still land on a Sunday? Receipts in one pile, bank statements in another, and the claims you meant to file slip past. Owners we've spoken to say it costs them 6 to 8 hours a month.

LedgerLite does your books for you and closes them within 5 days of month-end. One of the 3 clinics we work with found $4,200 in expenses they had never claimed.

This month we're offering 4 {{biz_plural}} a free review of last month's books. It costs nothing, and you keep the findings whether or not you sign up for the monthly subscription.

If that sounds like your Sundays, let me know when you're available this week and let's talk over a 15-minute call.

Priya
LedgerLite

### Email 1, variant B

Same body. Subject: `sundays at {{companyName}}`

Hypothesis: a subject about the owner's lost weekend gets more replies than one about the task.

### Email 2, variant A (701 characters)

Subject: (blank, sends as a reply)

Hi {{companyName}} team,

Following up on my last note. We put together a sample month-end report for your {{biz}}, built from the information on your website: [link]

It shows what you'd get from us every month. It only needs a little more information from you to be complete, and you don't have to sort anything first.

After that, your LedgerLite bookkeeper handles every month-end, so there's nothing for you to maintain. Most bookkeeping software still leaves the matching to you.

We don't file taxes. That stays with your accountant, and we send them clean books to work from.

If you'd like to see how many Sundays this gives back, let me know when you're available this week and let's talk over a 15-minute call.

Priya
LedgerLite

### Email 2, variant B

Same body, with the contrast line changed to: "Most bookkeeping software still leaves the matching to you, and most freelancers disappear at tax season."

Hypothesis: naming two alternatives the owner has probably tried lands harder than one.

### Email 3, variant A (619 characters)

Subject: (blank, sends as a reply)

Hi {{companyName}} team,

Last one from me.

Something we keep hearing from clinic owners: "I spend every second Sunday matching receipts."

So for the 4 {{biz_plural}} that join this month, we'll clean up last quarter's books for free, on top of your first month free.

That's the backlog most owners pay someone extra to untangle at tax time, cleared before your first report lands.

We're only taking on 4 new clinics this month. If you'd like one of the spots, let me know when you're available this week and let's talk over a 15-minute call.

If it's not for you, no worries at all, and I won't reach out again. Good luck with {{companyName}}.

Priya
LedgerLite

### Email 3, variant B

Same body, with the opening quote replaced by: "Owners we've spoken to lose 6 to 8 hours a month to their books. That's close to 2 working weeks a year."

Hypothesis: putting the lost time in yearly terms makes the cost harder to ignore than a quote.

## 4. Segment wording

| Category | {{biz}} | {{biz_plural}} | {{customers}} |
|---|---|---|---|
| Dental | dental clinic | dental clinics | patients |
| Physiotherapy | physio clinic | physio clinics | patients |
| Veterinary | vet clinic | vet clinics | pet owners |

## 5. Pre-send checklist

- [ ] Every lead has {{companyName}}, {{personalization}}, {{biz}} and {{biz_plural}} filled
- [ ] Every lead has its own sample report link for email 2
- [ ] Personalisation lines are 120 characters or less
- [ ] Clinics you're already talking to are removed from the sequence
- [ ] The cap of 4 clinics is still true on the day email 3 lands
- [ ] No dashes, no "!", nothing from the "Do not use" list
- [ ] Stop on reply is switched on in the sending tool
