# MidwifeSense AI — Digital Showcase
## SE4051 Trends in Digital Media — Final Project
### Kumarage M.B.S.I.E | IT22606556 | SLIIT 2025

---

## Folder Structure

```
midwifesense-showcase/
│
├── index.html                  ← Main entry point (hosted file)
│
├── assets/
│   ├── css/
│   │   └── style.css           ← (if extracted from index.html)
│   ├── js/
│   │   └── main.js             ← (if extracted from index.html)
│   └── images/
│       ├── mockup-screen.png   ← App screenshot / Figma export
│       ├── dashboard.png       ← Dashboard UI screenshot
│       ├── alert-screen.png    ← Alert screen screenshot
│       └── architecture.png   ← System architecture diagram
│
├── sections/
│   └── (all sections are inside index.html as one-page layout)
│       ├── #hero               ← Project Identity
│       ├── #problem            ← Problem & Need
│       ├── #solution           ← Solution Overview
│       ├── #demo               ← Visual / Interactive Media + Prototype
│       ├── #results            ← Research & Validation
│       ├── #commercialize      ← Commercialization & Future Potential
│       └── #downloads          ← Resource Repository
│
├── docs/
│   ├── thesis-draft.pdf        ← IT22606556_Thesis_Draft.docx (converted)
│   ├── abstract.pdf            ← 1-page research abstract
│   ├── research-poster.pdf     ← A1 research poster
│   └── sus-evaluation.xlsx     ← SUS questionnaire results (n=18)
│
├── README.md                   ← This file — structure + prompts used
└── submission.txt              ← Hosted URL (for LMS submission)
```

---

## Prompts Used to Generate This Project

### Prompt 1 — Initial Build Request
**What was uploaded:**
- `Final_Project___MG__2026_.pdf` — Assignment brief (SE4051)
- `IT22606556_Thesis_Draft__1_.docx` — Full thesis draft

**Prompt given to Claude:**
> *(Files were uploaded with no explicit text — Claude read both documents and understood the task automatically)*

**What Claude did:**
- Read the assignment PDF to extract all 8 required sections and rubric criteria
- Extracted the full thesis using `extract-text` tool
- Read the frontend-design SKILL.md for design direction
- Built a complete single-page `index.html` covering all 8 sections with:
  - Animated phone mockup with real vitals data
  - Live SVG blood pressure trend chart
  - System architecture diagram
  - Alert workflow visualization
  - Trilingual interface demo (Sinhala, Tamil, English)
  - ML performance results table with real thesis data
  - 4-phase commercialization roadmap
  - 8 resource download cards

---

### Prompt 2 — Assignment Coverage Audit
**Prompt given to Claude:**
> "according to assignment document is all covered?"

**What Claude did:**
- Re-examined the assignment PDF section by section
- Cross-checked all 8 required sections against the built website
- Cross-checked all 5 rubric criteria (each 20 marks)
- Identified gaps:

| Gap | Section Affected | Severity |
|-----|-----------------|----------|
| No real app screenshots / Figma mockups | Section 4 — Visual Media | ⚠️ High |
| No demo video embed | Section 5 — Prototype | ⚠️ High |
| No use-case storyboard | Section 4 — Visual Media | ⚠️ Medium |
| No methodology phases visual | Section 6 — Research | ⚠️ Medium |
| Supervisor name missing | Section 1 — Identity | ℹ️ Low |
| Download links are placeholder (#) | Section 8 — Downloads | ℹ️ Low |

---

### Prompt 3 — Folder Structure with Prompts
**Prompt given to Claude:**
> "i need folder structure with prompt used"

**What Claude did:**
- Created the full recommended folder structure for the project
- Documented all prompts used throughout the session
- Generated this README.md as a reference document

---

## Recommended Next Steps Before Submission

1. **Export your Figma screens** → save to `assets/images/`
2. **Record a demo video** → upload to YouTube → embed in `#demo` section
3. **Add the storyboard** (use-case visual) to the demo section
4. **Update download links** in `index.html` to point to real files in `docs/`
5. **Host the project** using one of:
   - GitHub Pages (free, recommended)
   - Netlify (drag & drop, free)
   - Vercel (free)
6. **Copy hosted URL** → paste into `submission.txt` → upload to LMS

---

## Hosting on GitHub Pages (Quickest Method)

```bash
# 1. Create a new GitHub repository (e.g. midwifesense-showcase)
# 2. Upload all files keeping this folder structure
# 3. Go to: Settings → Pages → Source → main branch → / (root)
# 4. Your site will be live at:
#    https://your-username.github.io/midwifesense-showcase/
```

---

## Assignment Details

| Field | Value |
|-------|-------|
| Module | SE4051 — Trends in Digital Media |
| Assignment | Final Project — Research Project Digital Showcase |
| Student | Kumarage M.B.S.I.E |
| Index No. | IT22606556 |
| Degree | B.Sc. (Hons) IT — Interactive Media |
| Institution | SLIIT, Sri Lanka |
| Deadline | 10th May 2026, 1800 hrs |
| Weightage | 15% of overall grade |
| Supervisor | Mr. Aruna Ishara Gamage |
