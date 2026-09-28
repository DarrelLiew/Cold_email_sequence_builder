---
name: cold-email-sequence-builder
description: Interview the user about their product, audience, proof and offer, then write a 3-email cold outreach sequence with A/B variants, escalating offers and real scarcity, and humanize the copy before delivering. Use for any B2B cold email campaign.
---

# Cold Email Sequence Builder

Write a 3-email cold outreach sequence with an A and a B variant for every email. The sequence is pain-first, each email is a bigger deal than the last, every claim is real, and the copy reads like a person wrote it.

The expertise comes from the interview. Never draft a single line of copy until the interview is done. Generic input produces generic copy.

## Phase 1: Interview (always first)

Run the interview in 4 short rounds using AskUserQuestion (up to 4 questions per round). Offer sensible options for each question and let the user type their own answer. If AskUserQuestion is not available, ask the same questions in plain text, one round at a time.

Before asking, check what you already know from the conversation, attached files, or connected tools (CRM, sending tool, lead lists). Only ask for what is missing, and confirm anything you inferred.

### Round 1: The product
1. What is the product or service, in one sentence a customer would understand?
2. What does it actually change for the customer (time saved, revenue won, cost removed, risk reduced)?
3. What does it NOT do, or where does it fall short? (Used for honest risk reversal, never hidden.)
4. Who is sending the emails, and what is the company name for the sign-off?

### Round 2: The audience and their pain
1. Which business types are you targeting? (List every segment, e.g. dental clinics, law firms, yoga studios.)
2. Who reads the email: owner, manager, or a specific role?
3. What is the main pain, in the prospect's own words if you have heard them say it? Describe a specific moment in their day or week when it happens.
4. What does that pain cost them (customers lost, hours wasted, money spent), and how do you know?

### Round 3: Proof and offer
1. What proof do you have? Options: case study with numbers, pilot results, testimonials, quotes from prospect conversations, credentials, none yet. Never invent proof. If there is none, the sequence frames the offer honestly as a pilot or early-access programme.
2. What is the free offer in email 1 (e.g. free review, free audit, trial), and what is the paid product they could sign up for afterwards?
3. What new asset or value can email 2 bring (e.g. personalised demo, audit, mockup, teardown)?
4. What extra value can email 3 stack on top (e.g. a free add-on, bonus service, extended guarantee)? And what is the real scarcity cap you will actually enforce (e.g. 5 spots this month)?

### Round 4: Logistics and voice
1. What should prospects do next: a short call, a reply, an in-person visit, or something else?
2. Which sending tool, and which personalisation variables do your leads have (e.g. {{companyName}}, {{firstName}}, {{personalization}}, custom fields)?
3. Voice: casual owner-to-owner, or more formal? Any words, phrases or punctuation you never want used? A past email or post you wrote yourself helps.
4. Timing between emails (default: 2 days, then 2 days).

After the interview, play back a 5-line brief (product, audience, pain, proof, offer ladder plus scarcity) and ask the user to confirm or correct it before writing.

## Phase 2: Segment wording

Never use one generic noun for every prospect. Use the words each owner would use for their own business, via per-lead variables derived from each lead's category:

- {{biz}}: singular noun for their business (e.g. dental clinic, law firm, yoga studio, CrossFit box).
- {{biz_plural}}: plural form (watch irregular plurals: academies, boxes, businesses).
- {{offering}}: what their customers enquire about (e.g. appointments, consultations, classes, memberships).
- {{customers}}: what they call their customers (e.g. patients, clients, students, members).
- Add others only if the copy needs them (e.g. {{trial}} for the first thing a new customer books).

Rules:
- Map every lead category to these values before writing. Mixed or unclear categories get the broader term.
- Never start a sentence with a lowercase variable. Place it mid-sentence.
- Never append letters to a variable ({{trial}}s). Use the plural variable or reword.
- If per-lead idea lines or links are used, every lead must have them filled. Write sensible segment defaults for any blanks.

## Phase 3: The sequence

Emails 2 and 3 go in the same thread (blank subject) so they read as replies, not reminders.

Each email answers a different objection:
- Email 1: "Is this even my problem?"
- Email 2: "It will take effort, and it might not work."
- Email 3: "I cannot justify the cost."

### Email 1: Pain first, then offer
Flow: personalisation, problem, cost, solution, credibility, offer, CTA.
1. Greeting with the company name, then a personalised line about something real in their business. Shows you did your homework.
2. Problem as a direct question about a specific scene from their week. Open straight with the question ("Does month-end at your {{biz}} still land on a Sunday?"), then add 1 or 2 concrete details of the scene.
3. The cost of that problem, from a source they would trust (what you have heard from owners like them, or your own data).
4. Solution in one sentence, named, tied directly to that pain. Say what it does for them, not the deal.
5. Credibility: how it has helped businesses like theirs, with a real number if you have one. If there is no proof yet, say it is a pilot.
6. Offer plus scarcity. Say what they get free, and that they keep it whether or not they sign up for the paid product (name it, e.g. "the monthly subscription"). This removes the "what's the catch" worry.
7. Optional: one line on who you are, if the email does not already make it clear.
8. CTA that names the action and a time window, tied back to the pain. Example: "If that sounds like your Sundays, let me know when you're available this week and let's talk over a 15-minute call."

Subject lines: 2 to 5 words, lowercase, include the company name, look like an internal message.

### Email 2: New asset, remove the effort objection
1. "Following up on my last note." then straight into something new built for them, with at most one link.
2. Done for you: what is already set up, and the little you need from them. Name the cost they avoid.
3. Ongoing effort removed: who maintains it.
4. One line contrasting other options as a category (strong A/B candidate).
5. Risk reversal: what happens when it goes wrong or does not know the answer, stated honestly.
6. CTA tied to the outcome, with a time window.

### Email 3: Breakup with the biggest value stack
1. Open with "Last one from me."
2. A real quote or frustration you have heard from owners like them about a cost they already carry.
3. The new value added to the offer that removes that cost.
4. Reframe what they are overpaying for today.
5. Scarcity with the real cap, plus the current offer.
6. Specific CTA.
7. Graceful exit: say you will not follow up again, and wish them well by name.

## Offer escalation and scarcity

- Each email must feel like a bigger deal than the last. Escalate the value stack, not only the discount.
- If a free period shrinks, the stack must grow so the overall deal still reads as bigger.
- Scarcity must be a cap the user will actually enforce. Later emails land days or weeks after they are written, so every claim must be true on the day it is received. Prefer caps phrased as policy ("We're only taking on 10 clients this quarter").

## Style rules

- The prospect's pain before your product. Never open with the solution.
- Plain English, in the voice agreed in the interview. Default: conversational, owner to owner, contractions fine.
- Paragraphs of 1 to 3 sentences. Email 1 up to about 150 words, emails 2 and 3 up to about 130.
- Use the prospect's industry nouns.
- "We" for the sender, "you" and "your team" for the prospect.
- Numerals for numbers.
- One CTA per email, naming a specific action and a time window.
- Criticise competitors as a category, never by brand name.
- Plain text, at most one link per email, no images, no bold, no emojis.

## Do not use (plus anything the user bans in the interview)

Punctuation
- Em dashes and en dashes used as punctuation. Use a full stop, comma or colon.
- Exclamation marks.

Openers
- "Quick question:", "Hope this finds you well", "I hope you're doing well", "I wanted to reach out", "I came across your...", "My name is...", "I'm reaching out because".
- Follow-up fillers: "Just checking in", "Circling back", "Bumping this", "Following up on my previous email to see if", "Touching base".
- Fake-candid hooks: "Honestly?", "Here's the thing", "Real talk", "Let's be honest", "What if I told you", "Imagine if".

Calls to action
- "Worth a look?", "Worth a chat?", "Worth a quick call?", "Open to a quick chat?", "Does this make sense?", "Thoughts?", "Interested?", "Would love to hop on a call", "Let me know if you have any questions", "Looking forward to hearing from you".

Sales and AI vocabulary
- revolutionary, game-changing, game-changer, cutting-edge, seamless, effortless, unlock, supercharge, elevate, empower, transform, streamline, leverage, robust, innovative, synergy, solution(s), pain points, take your business to the next level, in today's fast-paced world, delve, crucial, pivotal, landscape, testament, showcase, vibrant.

Structures
- "It's not just X, it's Y" and "Not only X, but also Y".
- Forced lists of three ("faster, smarter, better").
- Strings of short dramatic fragments ("No setup. No stress. No excuses.").
- Clipped endings in place of a clause ("No guessing." "Zero hassle.").
- Generic positive sign-offs ("Excited to help you grow").

Content
- One generic noun for every business type.
- Invented statistics, case studies, testimonials, quotes or scarcity.
- Vague sources ("studies show", "experts agree"). Name the source, or use what you heard from owners, or cut it.

## Phase 4: Humanize pass (always, before showing the user)

Run every email and every variant through this pass before delivering. The goal is copy that reads like the sender typed it on their phone between meetings.

1. Read each email aloud in your head. Mark anything a busy owner would not say out loud.
2. Check it against the "Do not use" list, then against these AI tells:
   - Inflated importance ("a pivotal moment for your business").
   - Sales adjectives (boasts, stunning, renowned, world-class).
   - Long verbs where "is", "has" or "does" would do ("serves as", "stands as", "offers a").
   - -ing tails that add fake depth ("..., ensuring your team stays focused").
   - Filler ("in order to", "due to the fact that", "at this point in time", "it's important to note").
   - Stacked hedges ("could potentially help").
   - Overused hyphenated pairs (data-driven, end-to-end, best-in-class).
   - Leftover chatbot text ("Here is your email", "I hope this helps").
3. Match the user's voice. If they gave a writing sample, match its sentence length, word choice and quirks, even when that breaks a default here. If they rewrote any of your drafts, treat their version as the style guide for the rest.
4. Vary the rhythm. Mix short and medium sentences. Avoid every sentence being the same length.
5. Ask two questions before finalising:
   - "What still sounds AI-generated?"
   - "Did I add or drop any fact, number, name, quote or claim?" Any addition not from the interview is an error. Fix it.
6. Search the final text for "—", "–" and "!" and remove them.

Deliver only the humanized version. Do not show the before and after unless the user asks.

## A/B testing

- Write an A and a B for every email.
- Change one element per test and keep everything else word for word.
- State the hypothesis for each test in one line.
- Test ideas: subject line, pain scene, proof type, offer framing (free time vs dollar value), cost framing (monthly vs annual), competitor contrast line, CTA type.
- Judge on positive reply rate, not opens. Wait for 100 to 150 sends per variant before picking a winner; with smaller lists, treat results as a signal only.

## Output

1. The confirmed 5-line brief.
2. Overview table: email, send day, subject A and B, what the B test changes, offer, CTA.
3. Full copy for every variant, humanized, with personalisation variables in place.
4. Segment wording table: each lead category mapped to its variable values.
5. Pre-send checklist:
   - Every lead has every variable and link filled
   - Warm leads (already talking to you) are removed from the cold sequence
   - Every claim and scarcity line will be true on the day it lands
   - No items from the "Do not use" list, no dashes, no "!"
6. If the user's sending tool is connected, offer to load it: one step per email with the agreed delays, both variants per step, blank subject on follow-ups, stop on reply switched on. Set the segment variables on every lead, then re-check that none are missing.

## Template skeleton (fill from the interview, never ship as is)

Email 1
Subject A: {{companyName}} [pain topic]
Subject B: [alternative angle] at {{companyName}}

Hi {{companyName}} team,

{{personalization}}

Does [specific scene of the pain] still happen at your {{biz}}? [1 or 2 concrete details of the scene.] Owners we've spoken to say it costs them [cost].

[Product] [does what, in one sentence tied to the pain]. [Proof with a real number, or honest pilot framing.]

This month we're offering [cap] {{biz_plural}} [free offer]. It costs nothing, and you keep [what they get] whether or not you sign up for [paid product].

If that sounds like [the pain in their words], let me know when you're available this week and let's talk over a [length] call.

[Sender first name]
[Company]

Email 2
Hi {{companyName}} team,

Following up on my last note. We put together [new asset built for them]: [link]

[What is already done for them, and the little you need.] [Cost they avoid.]

[Who maintains it.] [Category contrast line.]

[Honest risk reversal.]

[Outcome-tied CTA with a time window.]

Email 3
Hi {{companyName}} team,

Last one from me.

[Real quote or frustration about a cost they carry.]

[New value stacked on the offer.] [Reframe what they overpay for.]

[Real scarcity cap plus current offer.] [Specific CTA.]

If it's not for you, no worries at all, and I won't reach out again. Good luck with {{companyName}}.

## Reference: a finished email 1 (fictional business)

Subject: {{companyName}} month-end

Hi {{companyName}} team,

{{personalization}}

Does month-end at your {{biz}} still land on a Sunday? Receipts in one pile, bank statements in another, and the claims you meant to file slip past. Owners we've spoken to say it costs them 6 to 8 hours a month.

LedgerLite does your books for you and closes them within 5 days of month-end. One of the 3 clinics we work with found $4,200 in expenses they had never claimed.

This month we're offering 4 {{biz_plural}} a free review of last month's books. It costs nothing, and you keep the findings whether or not you sign up for the monthly subscription.

If that sounds like your Sundays, let me know when you're available this week and let's talk over a 15-minute call.

Priya
LedgerLite
