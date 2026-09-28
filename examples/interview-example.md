# Example run

This example uses a made-up business. Every detail in the emails comes from the user's answers in the interview.

## The interview (condensed)

### Round 1: product

The product is LedgerLite, a bookkeeping service for small clinics that does the work for them. It closes the monthly books within 5 days, so the owner stops doing them on weekends. It doesn't file taxes, which stays with the clinic's accountant. Priya sends the emails from LedgerLite.

### Round 2: audience and pain

The targets are dental, physio and vet clinics, and the owner reads the email. In their words: "I spend every second Sunday matching receipts." Owners the user spoke to said they lose 6 to 8 hours a month and miss claims.

### Round 3: proof and offer

LedgerLite has had 3 clinics on board for 6 months, and one of them found $4,200 in unclaimed expenses. Email 1 offers a free review of last month's books. Email 2 brings a sample month-end report built from the clinic's public information. Email 3 adds the first month free and a one-off clean-up of last quarter. The cap is 4 new clinics this month.

### Round 4: logistics and voice

The ask is a 15-minute call. The sending tool has {{companyName}}, {{personalization}} and custom fields. The voice is casual, owner to owner, and the emails go out 2 days apart.

### The brief Claude played back

LedgerLite closes clinic books in 5 days, for owners of dental, physio and vet clinics who lose weekends to receipts. One of its 3 clinics recovered $4,200. Email 1 offers a free review, email 2 a sample report, and email 3 the first month free plus a clean-up. The cap is 4 clinics this month.

The user confirmed it, and Claude started writing.

## Segment wording

| Category | {{biz}} | {{biz_plural}} | {{customers}} |
|---|---|---|---|
| Dental | dental clinic | dental clinics | patients |
| Physiotherapy | physio clinic | physio clinics | patients |
| Veterinary | vet clinic | vet clinics | pet owners |

## Email 1, variant A

Subject: {{companyName}} month-end

Hi {{companyName}} team,

{{personalization}}

Does month-end at your {{biz}} still land on a Sunday? Receipts in one pile, bank statements in another, and the claims you meant to file slip past. Owners we've spoken to say it costs them 6 to 8 hours a month.

LedgerLite does your books for you and closes them within 5 days of month-end. One of the 3 clinics we work with found $4,200 in expenses they had never claimed.

This month we're offering 4 {{biz_plural}} a free review of last month's books. It costs nothing, and you keep the findings whether or not you sign up for the monthly subscription.

If that sounds like your Sundays, let me know when you're available this week and let's talk over a 15-minute call.

Priya
LedgerLite

## Email 1, variant B

Variant B changes only the subject line, to `sundays at {{companyName}}`. The bet is that a subject about the owner's lost weekend gets more replies than one about the task.
