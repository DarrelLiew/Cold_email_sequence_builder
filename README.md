# Cold Email Sequence Builder

A Claude skill that interviews you about your business first, then writes a 3-email cold outreach sequence with A/B variants for every email.

AI can write cold emails in seconds. Without expertise behind it, they read like every other AI email in the inbox. This skill puts the expertise in first: it asks the questions a good copywriter would ask, then writes from your answers, not from a blank prompt.

Built by [Cortex Lab AI](https://cortexlabs.tech) in Singapore.

## What it does

1. **Interviews you in 4 short rounds**: your product, your audience and their pain, your proof and offer, and your logistics and voice.
2. **Plays back a 5-line brief** for you to confirm before any copy is written.
3. **Writes 3 emails, each with an A and a B variant**, where every email handles a different objection:
   - Email 1: "Is this even my problem?"
   - Email 2: "It will take effort, and it might not work."
   - Email 3: "I cannot justify the cost."
4. **Makes every email a bigger deal than the last**, with scarcity only if it is real.
5. **Uses the right words for each prospect** (dental clinic, law firm, pilates studio) through per-lead variables, instead of one generic noun for everyone.
6. **Gives you a pre-send checklist**, and if your sending tool is connected to Claude, offers to load the sequence for you.

## The principles behind it

- Lead with their pain, not your product.
- Flow for the first email: personalisation, problem, solution, credibility, offer.
- One objection per email, and a bigger offer each time.
- Every call to action names a specific action and a time window. No "Worth a chat?".
- Scarcity must be a cap you will actually enforce.
- Never invent proof. No case study yet? Say it is a pilot.
- Copy is a guess until it is tested. Change one thing per A/B test and judge on replies, not opens.

## Install

**Claude Code**

```bash
git clone https://github.com/DarrelLiew/Cold_email_sequence_builder.git
cp -r Cold_email_sequence_builder/cold-email-sequence-builder ~/.claude/skills/
```

Restart Claude Code. The skill is picked up automatically.

**Claude app (Cowork, claude.ai)**

1. Download `cold-email-sequence-builder-skill.zip` from the [latest release](../../releases).
2. In Claude, make sure **Code execution and file creation** is on (Settings, then Capabilities).
3. Go to **Customize, then Skills**. Click **+**, then **Create skill**, then **Upload a skill**, and choose the zip.
4. Make sure the skill is switched on. Works on Free, Pro, Max, Team and Enterprise plans.

## Use it

Ask Claude something like:

> Help me write a cold email sequence for my bookkeeping service.

Claude will start the interview. Answer as specifically as you can. The more real detail you give (what customers actually say, real numbers, real limits), the better the copy.

See [`examples/interview-example.md`](examples/interview-example.md) for what a run looks like.

## Repo contents

```
cold-email-sequence-builder/
├── cold-email-sequence-builder/
│   └── SKILL.md              # the skill itself
├── examples/
│   └── interview-example.md  # a sample run
├── README.md
└── LICENSE
```

## Feedback

I am not an email marketing expert, and this will improve with real campaign data. If you run it, open an issue with what worked, what did not, and your reply rates. Pull requests welcome.

## License

MIT. Use it, change it, ship it.
