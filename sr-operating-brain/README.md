# sr-operating-brain

The operating system for SubjectReport's day-to-day agent workflow.

```
sr-operating-brain/
├── CLAUDE.md                  ← identity + business context (auto-loaded) — NEEDS CONTENT, see note below
├── goals/
│   ├── goals.md                ← active goals with metrics
│   └── archive/                ← completed goals
├── data/
│   ├── orders/
│   │   └── open-orders.md      ← every open transcript with 48hr deadline
│   ├── transcripts/            ← completed Prospect Edge evaluations
│   ├── programs/                ← 6-week program enrollees
│   ├── athletes/                ← SR Active Profile candidates
│   └── interviews/              ← discovery call and placement session notes
├── skills/
│   ├── srvoice/
│   │   └── SKILL.md            ← how SubjectReport writes
│   ├── evaluation-processing/
│   │   └── SKILL.md            ← transcript → family-facing summary
│   └── reporting/
│       └── SKILL.md            ← weekly and monthly report formats
├── workflows/
│   ├── daily.md                 ← run every session
│   ├── weekly.md                ← Monday planning + Friday review
│   └── monthly.md               ← report generation + goal review
├── feedback/
│   ├── feedback-log.md          ← YOU write here
│   └── improvements.md          ← agent logs what changed and why
└── output/
    ├── content/                  ← social posts, course content
    ├── reports/                  ← transcripts, weekly reports, session logs
    └── sequences/                ← GHL email sequences, SM upsell flows
```

## Note on CLAUDE.md

This file is referenced as auto-loaded identity + business context, but no content for it was provided yet. Add it at the repo root with SubjectReport's identity, business model, and any context the agent should always have loaded.
