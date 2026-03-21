# Plan: Update Website with Job Update

## Summary
Update wiguider.github.io to reflect Walid's current role as **Chief Technology Officer at Neural Factory** and add the **FairMind S.R.L.** position to the work history.

## Sources of Truth
- **Dates & titles**: LinkedIn profile (screenshot)
- **Descriptions & details**: [walidiguider.com](https://walidiguider.com/)

### LinkedIn dates (authoritative):
| Role | Company | Dates |
|------|---------|-------|
| Chief Technology Officer | Neural Factory | Oct 2025 – Present |
| Senior Artificial Intelligence Engineer | FairMind | Apr 2024 – Sep 2025 (1 yr 6 mos) |
| Senior Data Scientist | Stackhouse | Apr 2022 – Mar 2024 (2 yrs) |
| Senior Data Scientist | Athlos S.r.l. | Oct 2021 – Apr 2022 (7 mos) |

## Changes Required

### 1. Update `_config.yml` — Site-wide author metadata
- Change `employer` from `"Stackhouse"` to `"Neural Factory"`
- Change `bio` from `"Senior Data Scientist And Researcher"` to `"CTO & AI Researcher"`
- Change `description` from `"Senior Data Scientist And Researcher"` to `"CTO & AI Researcher"`

### 2. Update `_pages/about.md` — About/landing page
Rewrite the page to align with walidiguider.com content:
- **Opening**: CTO of Neural Factory S.R.L. — AI platform company accelerating Italian manufacturing SMEs
- **Background**: PhD computer scientist and entrepreneur, 12+ years building intelligent systems
- **Career narrative** (updated order):
  - Current: CTO at Neural Factory (Oct 2025 – Present)
  - Previous: Senior AI Engineer at FairMind S.R.L. (Apr 2024 – Sep 2025) — LLMs, Responsible AI, open-source models (Minerva-3B)
  - Stackhouse/Stellantis (Apr 2022 – Mar 2024)
  - Keep rest of career history (Athlos, AIBD/Abinsula/Eurecat, theShukran, Software Engineer)
- **Education**: Keep MS and PhD, add Bachelor's in Mathematics & CS from University of Rabat
- **Languages**: Keep Arabic, English, French, Italian

### 3. Update `_pages/cv.md` — CV/Resume page
- Update summary paragraph: "12+ years" instead of "about a decade", mention AI/ML leadership alongside Data Science
- **Add Chief Technology Officer at Neural Factory S.R.L.** (Oct 2025 – Present):
  - Leading technical vision of AI platform company for Italian manufacturing SMEs
  - Designed three-tier AI system: knowledge graphs + conversational analytics + autonomous agents
  - Strategic partnerships with Alphabridge and Easynet Group
  - *Tools:* Python, LangChain, AWS (Lambda, S3, ECS), Docker, MongoDB, FastAPI, Git
- **Add Senior Artificial Intelligence Engineer at FairMind S.R.L.** (Apr 2024 – Sep 2025):
  - Led R&D of generative AI platform for software development acceleration
  - Production-ready LLM systems for code generation, AI agents, model orchestration, guardrails
  - Contributed open-source models to HuggingFace (Minerva-3B-Instruct, multilingual adaptations)
  - Technical mentoring of junior engineers
  - *Tools:* Python, PyTorch, LangChain, HuggingFace, AWS, Docker, FastAPI, Git
- **Fix Stackhouse end date**: Apr 2024 → Mar 2024 (currently says "Apr 2024")
- Keep all other existing positions intact

### 4. Verify consistency
- Ensure all three files are consistent with each other
- Ensure dates flow correctly and don't overlap

## Files Modified
1. `_config.yml`
2. `_pages/about.md`
3. `_pages/cv.md`
