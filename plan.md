# Plan: Update Website with Job Update

## Summary
Update wiguider.github.io to match the content on walidiguider.com, reflecting Walid's current role as **CTO & Co-founder at Neural Factory S.R.L.** and adding the **FairMind S.R.L.** position.

## Source of Truth
Using [walidiguider.com](https://walidiguider.com/) as the authoritative source for dates, titles, and descriptions.

## Changes Required

### 1. Update `_config.yml` — Site-wide author metadata
- Change `employer` from `"Stackhouse"` to `"Neural Factory"`
- Change `bio` from `"Senior Data Scientist And Researcher"` to `"CTO & Co-founder | AI Researcher"`
- Change `description` from `"Senior Data Scientist And Researcher"` to `"CTO & Co-founder | AI Researcher"`

### 2. Update `_pages/about.md` — About/landing page
Rewrite the page to align with walidiguider.com content:
- **Opening**: CTO & Co-founder of Neural Factory S.R.L. — AI platform company accelerating Italian manufacturing SMEs
- **Background**: PhD computer scientist and entrepreneur, 12+ years building intelligent systems
- **Career narrative** (updated order):
  - Current: CTO & Co-founder at Neural Factory S.R.L. (Apr 2024 – Present)
  - Previous: Senior AI Engineer at FairMind S.R.L. (Apr 2024 – Sep 2025) — LLMs, Responsible AI, open-source models (Minerva-3B)
  - Stackhouse/Stellantis (Mar 2022 – Feb 2024)
  - Keep rest of career history (Athlos, AIBD/Abinsula/Eurecat, theShukran, Software Engineer)
- **Education**: Keep MS and PhD, add Bachelor's in Mathematics & CS from University of Rabat
- **Languages**: Keep Arabic, English, French, Italian

### 3. Update `_pages/cv.md` — CV/Resume page
- Update summary paragraph: "12+ years" instead of "about a decade", mention AI/ML leadership alongside Data Science
- **Add CTO & Co-founder at Neural Factory S.R.L.** (Apr 2024 – Present):
  - Leading technical vision of AI platform company for Italian manufacturing SMEs
  - Designed three-tier AI system: knowledge graphs + conversational analytics + autonomous agents
  - Strategic partnerships with Alphabridge and Easynet Group
  - *Tools:* Python, LangChain, AWS (Lambda, S3, ECS), Docker, MongoDB, FastAPI, Git
- **Add Senior AI Engineer at FairMind S.R.L.** (Apr 2024 – Sep 2025):
  - Led R&D of generative AI platform for software development acceleration
  - Production-ready LLM systems for code generation, AI agents, model orchestration, guardrails
  - Contributed open-source models to HuggingFace (Minerva-3B-Instruct, multilingual adaptations)
  - Technical mentoring of junior engineers
  - *Tools:* Python, PyTorch, LangChain, HuggingFace, AWS, Docker, FastAPI, Git
- **Fix Stackhouse dates**: Mar 2022 – Feb 2024 (currently says Apr 2022 – Apr 2024)
- **Fix Stackhouse description**: Add "Stellantis" branding to match walidiguider.com
- Keep all other existing positions intact

### 4. Verify consistency
- Ensure all three files are consistent with each other and with walidiguider.com
- Ensure dates flow correctly

## Files Modified
1. `_config.yml`
2. `_pages/about.md`
3. `_pages/cv.md`
