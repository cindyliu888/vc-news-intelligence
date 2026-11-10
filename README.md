# VC News Intelligence (Meridian prototype)

Interactive MVP prototype of **Meridian**, an AI decision layer that connects market signals to VC decisions and to founder–investor communication.

## Files
- `index.html`: desktop prototype (single self-contained file; open it in a browser)
- `mobile.html`: mobile market-intelligence view, opened from the desktop app's **Mobile** button

## What's inside
- **View as VC or Founder** (top bar)
- **News & Intelligence:** Daily Brief, Signal Feed (Needs action / Watching, news groups with upgrade criteria, context on demand), Topic Tracker
- **VC:** actions by startup, meeting prep packs, DD questions from news, evidence log, decision workspace (D-1), IC memo market-section export, Portfolio, Deal flow & Meetings, Due Diligence, My tasks
- **Due Diligence folders (v37):** one folder per company, linked from Portfolio, Deal flow and news. Tabs: Checklist (six categories with status), Claims, Demo video, Files
- **Verification (adapted from Receipts):** claim ledger with source tracing and word-level diffs, demo-video source map, and checks on founder answers (VC side in prep packs; founder side "Check before sending" plus cross-investor consistency)
- **Tracked Topics** in the sidebar open the matching Topic Tracker
- **Founder:** Investor Relations (questions from investors, AI-matched repeated questions with answer reuse), My Company, Investor Updates, Calendar & Tasks

## Data notes
- Ultra, Gecko Robotics and Vexo are real companies, shown as **assumed holdings for this demo only**. Company facts come from linked public sources.
- The fund (Meridian Seed Ventures), Northline Capital, people, tasks and meetings are **fictional**.
- **Fernhook Robotics is a fictional company** used to demo verification and diligence; its claims, files, sources and demo video are made up and labeled "Fictional". Founder test answers for Vexo are labeled test text, not from Vexo.
- Analysis in the prototype is pre-written to illustrate AI outputs; there is no live AI or live data.
- State is saved in the browser's localStorage; use **Reset demo** to start over.
