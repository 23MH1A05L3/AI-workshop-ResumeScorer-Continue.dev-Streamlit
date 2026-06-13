## Day 5 of AI - workshop — Resume Scorer Streamlit and Continue.dev

**Live URL:** https://<your-app>.streamlit.app
**Code:** [app.py](app.py)
**Acceptance log:** [acceptance_log.md](acceptance_log.md)
**Tools used:** Continue.dev + Gemini 2.5 Flash + Streamlit Community Cloud

### Features
- Fit score with rationale
- 4-axis bar chart breakdown
- Missing skills + free learning resources

### Reflection (3 lines)
- **Vibe vs engineered:** This is vibe-coded. To productionise, I would add caching, error handling on Gemini failures, rate limiting per user.
- **What Continue.dev did well:** scaffolded the Streamlit layout fast.
- **What I had to fix:** Continue.dev forgot to add the 4 sub-score fields to the Gemini prompt itself; I had to add them.
