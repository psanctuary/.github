---
marp: true
theme: default
paginate: true
size: 16:9
title: Welcome to Psanctuary
description: A first walk through Psanctuary's proposals, procedures, decks and reading room, for a newcomer and their AI helper.
style: |
  /* Tone: the four shades of the organisation's family, from my-template/proposals-template/TONES.md (bare hex, no #).
     The ground is the DEEP shade mixed into near-black, headings are the TINT with a PRIMARY rule, so every family
     reads on the dark ground, purple included. Do not hand-edit colours below; change the four placeholders. */
  section { background: color-mix(in srgb, #134e4a 32%, #0b0d12); color: #eef0f3; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-size: 25px; padding: 52px 64px 56px; border-left: 10px solid #0d9488; }
  section::after { color: color-mix(in srgb, #ccfbf1 60%, #6b7280); font-size: 0.6em; }
  section h1 { color: #ccfbf1 !important; border-bottom: 3px solid #0d9488; padding-bottom: 8px; font-size: 1.45em; margin-bottom: 0.45em; }
  section h2 { color: color-mix(in srgb, #0d9488 45%, white) !important; font-size: 1.1em; margin: 0.2em 0 0.4em; }
  strong { color: #ccfbf1; }
  a { color: color-mix(in srgb, #0d9488 40%, white); text-decoration: underline; text-decoration-color: #0f766e; }
  code { background: color-mix(in srgb, #134e4a 70%, #1f2937); color: #ccfbf1; padding: 1px 6px; border-radius: 4px; font-size: 0.82em; }
  pre { background: color-mix(in srgb, #134e4a 45%, #111318); color: #ccfbf1; border: 1px solid #0f766e; border-radius: 8px; padding: 12px 16px; font-size: 0.68em; line-height: 1.35; }
  pre code { background: transparent; color: inherit; padding: 0; font-size: 1em; }
  table { border-collapse: collapse; width: 100%; font-size: 0.74em; }
  section table th { background: #134e4a; color: #ccfbf1; padding: 6px 10px; text-align: left; border: 1px solid #0f766e; }
  section table td { background: color-mix(in srgb, #134e4a 22%, #14161c); color: #eef0f3; padding: 5px 10px; border: 1px solid color-mix(in srgb, #0f766e 45%, #14161c); }
  blockquote { border-left: 4px solid #0d9488; background: color-mix(in srgb, #134e4a 40%, #111318); color: #eef0f3; padding: 8px 16px; margin: 0.6em 0; font-style: normal; }
  li { margin: 0.18em 0; }
  .small { font-size: 0.66em; color: color-mix(in srgb, #ccfbf1 55%, #6b7280); }
  .fill { color: #0b0d12; background: #ccfbf1; padding: 0 6px; border-radius: 3px; }
  .shades { display: flex; height: 14px; margin: 18px 0 0; border-radius: 3px; overflow: hidden; }
  .shades span { flex: 1; }
  .s1 { background: #134e4a } .s2 { background: #0f766e } .s3 { background: #0d9488 } .s4 { background: #ccfbf1 }
  section.lead { border-left: none; background: linear-gradient(135deg, #134e4a 0%, color-mix(in srgb, #134e4a 30%, #0b0d12) 75%); justify-content: center; }
  section.lead h1 { border: none; font-size: 2.3em; color: #ffffff !important; margin-bottom: 0.1em; }
  section.lead h2 { color: #ccfbf1 !important; font-weight: 400; font-size: 1.15em; }
  section.lead .kicker { color: #ccfbf1; letter-spacing: 0.25em; font-size: 0.6em; font-weight: 700; opacity: .85; }
---

<!--
  Psanctuary's newcomer deck, filled 2026-10-31 from my-template/decks-template/welcome.marp.md in teal
  (0d9488 134e4a 0f766e ccfbf1), with the reading-room slide and the last slide written for Psanctuary.
  Render: decks-template/README.md ("Render it"). Commit the .md, .html and .pdf together.
-->
<!-- _class: lead -->
<!-- _paginate: false -->

<span class="kicker">WELCOME</span>

# Welcome to Psanctuary

## Where the proposals, the procedures and the decks live, how a change travels, and how to answer

<span class="small">A first walk for a newcomer, and for the AI helper beside them. Every slide points at a real page; the deck only shows the order to open them in.</span>

<span class="small">Members bringing an AI helper: its first page is [WELCOME-FOR-YOUR-HELPER.md](https://github.com/psanctuary/.github-private/blob/main/WELCOME-FOR-YOUR-HELPER.md), in the members' home (private; it opens when you are signed in).</span>

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# What you will find here

| Kind | What it is | Where |
|---|---|---|
| **Proposals** (members) | *should we?* One folder, one page, a PDF beside it | [psanctuary/proposals](https://github.com/psanctuary/proposals) |
| **Procedures** (SOPs) | *this is how we do it now*, approved versions tagged | [the procedures' public twin](https://github.com/psanctuary/ops-standard-operating-procedures-public) |
| **Decks** | walk-throughs like this one, for a call or a first look | [psanctuary/.github, decks/](https://github.com/psanctuary/.github/tree/main/decks) |
| **The reading room** | one place that gathers what members and visitors read | [psanctuary.github.io/reading-room-public](https://psanctuary.github.io/reading-room-public/) |

> Everything Psanctuary writes wears the same colour, these four shades, so you can tell whose page it is before you read a word.

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# Five words, and you can find your way

| Word | Means |
|---|---|
| **Repository** | a folder that remembers every change and who made it |
| **`preview` and `main`** | the rehearsal copy and the live copy of the same folder |
| **Promote** | the pull request that moves rehearsal to live; a person with the role merges it |
| **Public twin** | a public copy that carries only the pages marked public; nobody edits it by hand |
| **Issue** | a conversation thread: the easiest way to ask or answer |

<span class="small">You never need to type a branch command. You read, you comment, and you say yes or no.</span>

---

# How a proposal reads

1. **TL;DR**: five lines, the only part you have to read.
2. **What is offered**: how things are today, beside what is proposed.
3. **Decisions log**: what was chosen, when, and by whom. Yours stay blank until you choose.
4. **Asks**: usually none, sometimes one.
5. **Sources, and what could not be confirmed**: folded away, never hidden.

Every proposal comes as a **PDF for your eyes** and the **markdown it was made from** for your helper's. Start with **000 Start here** in [psanctuary/proposals](https://github.com/psanctuary/proposals).

---

# Procedures: how we do it now

- A procedure is named `SOP-<Department>-<ID>-<name>`: `SOP-OPS-001` is the first operations procedure.
- It is a **draft** until the officers tag an approved version; the tag is the approval.
- Each one opens with a badge row: the number in **Psanctuary's colour**, its status, the date it last changed, and **For** in the slate every organisation shares.
- Every procedure is also a PDF, rendered on each push.

> Read **SOP-OPS-001 "How a change travels"** first. It is the road on the next slide but one, in full.

<span class="small">The procedures visitors may read: [the procedures' public twin](https://github.com/psanctuary/ops-standard-operating-procedures-public).</span>

---

# The reading room, and your helper

- **Two rooms, one door.** The public lane, [psanctuary.github.io/reading-room-public](https://psanctuary.github.io/reading-room-public/), is open to anyone: the decks and the procedures marked public. The members' room, [psanctuary/reading-room](https://github.com/psanctuary/reading-room), gathers the drafts: proposals, procedures and decks, each as a page and a PDF. Open it while signed in to GitHub.
- If the members' room shows **404**, you are signed out or not yet in the **readers** team: ask the stewards (the last slide says how).
- **Your helper** (Claude, ChatGPT, any of them) can read the same pages once it is connected with your permission, never more than you can. Point it at the markdown, not the PDF. Members: its first page is [WELCOME-FOR-YOUR-HELPER.md](https://github.com/psanctuary/.github-private/blob/main/WELCOME-FOR-YOUR-HELPER.md) (private, so it opens only when you are signed in).

> A good first question for your helper: *"Read 000 Start here and tell me what is waiting for my answer."*

---

# The road a change travels

```
  an edit  ──→  preview  (the rehearsal: read it here, comment here)
                   │
                   │  "Promote: <what>"  pull request, preview into main
                   │  a person with the role merges it
                   ▼
                  main  (the live copy)
                   │
                   │  automatic sync: only pages marked public
                   ▼
            the public twin  (what visitors see)
```

- If a link to `main` still shows old words while someone says the change is done, it is on `preview`: the Promote has not been merged yet.
- A page that is not marked public never leaves the private repository, on any branch.

---

# How to answer

| You want to… | Do this |
|---|---|
| say yes, no, or "not yet" to a proposal | open an **issue** titled with its number, or ask a steward to note it in the decisions log |
| comment on a change before it goes live | comment on the **Promote** pull request |
| ask a question about a procedure | open an issue in the procedures repository, naming the SOP |
| ask your helper to answer for you | let it draft; **you** read it and post it under your name |
| get access, or more of it | ask the stewards (the last slide), with your GitHub username |

> There is no wrong door. A question in the wrong place gets moved, not lost.

---

# Who to ask

**The stewards.** Write to [info@psanctuary.org](mailto:info@psanctuary.org) or use [the contact form](https://www.psanctuary.org/contact), and include your GitHub username. For GitHub itself (access, the machinery, anything stuck) the technical steward is **Christopher W** ([@drasticstatic](https://github.com/drasticstatic)).

- for access to the members' reading room, the proposals or the procedures
- when a link shows 404, or a page looks out of date
- when you are not sure where an answer belongs

<span class="small">Where to start next: **000 Start here** in [psanctuary/proposals](https://github.com/psanctuary/proposals), then **SOP-OPS-001** in [the procedures' public twin](https://github.com/psanctuary/ops-standard-operating-procedures-public), then the reading room at [psanctuary.github.io/reading-room-public](https://psanctuary.github.io/reading-room-public/).</span>

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>
