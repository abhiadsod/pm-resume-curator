# PM Resume Curator
### A Skill-as-a-Product for Product Managers

---

## What Is This?

**PM Resume Curator** is an AI-powered resume system built specifically for Product Managers.

It does three things most resume tools don't:

1. **Builds your Candidate Profile once** — and reuses it across every JD you apply to. No re-entering your history every time.
2. **Decodes the PM Persona a JD is looking for** before writing a single line — so your resume is built around what the role actually needs, not a generic PM template.
3. **Tailors every resume to the specific role** — keywords, framing, story selection, and structure all calibrated to the JD.

---

## The PM Persona Decoder

Every time you paste a JD, the system runs a **PM Persona Decoder** before writing anything.

It identifies the PM archetype the role is looking for:

> **Primary Persona:** Technical / Platform PM
> **Secondary Persona:** Enterprise / B2B
> *This JD wants someone who can own API-layer decisions, earn engineering trust, and navigate complex integrations. Technical credibility is the entry ticket here — business metrics matter but come second.*

This tells you *why* your resume is structured the way it is — and helps you walk into the interview knowing exactly what story to lead with.

---

## What's in This Pack

```
pm-resume-curator/
├── README.md                 ← You are here
├── 01_engine.md              ← The resume strategy engine (paste into any AI tool)
└── 02_candidate_profile.md   ← Your career profile template
```

---

## How to Use It

### First Time (Profile Setup)

**Step 1.** Open your AI tool of choice (Claude, ChatGPT, Gemini, or any other).

**Step 2.** Paste the contents of `01_engine.md` as your first message (or as a system prompt if your tool supports it).

**Step 3.** The system will ask: *Do you have an existing resume?*
- **Yes** → Paste it. The system extracts what it can automatically.
- **No** → The system interviews you, section by section.

**Step 4.** Complete the interview. The system builds your **Candidate Profile** and shows it to you for review.

**Step 5.** **Save your Candidate Profile.** Copy it and store it in `02_candidate_profile.md`. You'll never have to answer those questions again.

---

### Every Time After (Resume Generation)

**Step 1.** Paste `01_engine.md` into your AI tool.

**Step 2.** Paste your saved `02_candidate_profile.md` immediately after.

**Step 3.** Paste the JD for the role you're applying to.

**Step 4.** The system runs the **PM Persona Decoder**, then drafts a tailored, ATS-optimized resume.

**Step 5.** Review the draft + the **"Why this resume works"** notes at the end.

---

## Installing as a Claude Skill (Optional)

If you use Claude and want this as a persistent skill:

1. Download the `.skill` file from the release.
2. In Claude, go to **Settings → Skills → Install from file**.
3. Upload the `.skill` file.
4. The PM Resume Curator is now always available — just start a conversation with your Candidate Profile and a JD.

---

## What You Get in Every Resume Session

- **PM Persona Decoder** — identifies the PM archetype the JD is targeting
- **JD Analysis** — top keywords, ATS signals, match gaps
- **Tailored Resume Draft** — structured, keyword-optimized, calibrated to the decoded persona
- **"Why This Resume Works"** — 3–5 bullet strategic rationale after every draft
- **Format variants on request** — ATS plain text, 1-page, 2-page, cover letter

---

## Tips for Best Results

- The richer your Candidate Profile, the better every resume will be. Don't skip the metrics and proof points section.
- Be honest about what you can and can't claim — the system is designed to work with scope and complexity signals when hard numbers aren't available.
- Run the Persona Decoder output before your interview, not just before submitting — it tells you what story to lead with in the room.
- Update your Candidate Profile when you change roles, ship something significant, or earn a new credential. It compounds over time.

---

## About This Project

Built by a Senior PM with 12+ years across healthcare, FinTech, SaaS, and manufacturing — who got tired of rebuilding the same resume from scratch for every application.

**PM Resume Curator** is free to use and distribute. If it helps you land a role, pay it forward — share it with another PM who's in the hunt.

---

*Have feedback or want to contribute improvements? Connect on LinkedIn.*
