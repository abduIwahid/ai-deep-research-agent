# AI Deep Research Agent

Give it a topic and it does the research workflow for you: it plans the investigation, breaks it into tasks, researches each one, and synthesizes everything into a structured report.

## What it does

- **Plans first** — turns a broad topic into a concrete, numbered research plan you can review
- **Executes task by task** — deep-dives each sub-topic using Gemini's stateful Interactions API, so context carries across steps
- **Synthesizes** — merges the findings into one coherent report
- **Visualizes** — can generate an infographic summarizing the research

## Tech stack

- **Streamlit** — web UI with live progress
- **Google Gemini (Interactions API)** — planning, research and synthesis with stateful conversations
- **google-genai SDK**

## Run it locally

```bash
pip install -r requirements.txt
streamlit run research_agent.py
```

Enter your Google API key (free from Google AI Studio) in the sidebar, type a topic, and watch the plan come together.

## Example topics

- "The current state of solid-state batteries"
- "How are small farms in Pakistan adopting drip irrigation?"
- "Compare RAG architectures for enterprise search in 2026"

## Author

**Abdul Wahid** — AI/ML Developer
[Portfolio](https://www.abdulwahid.me) · [GitHub](https://github.com/abduIwahid) · [LinkedIn](https://www.linkedin.com/in/abdu1wahid)

## Credits

Adapted from a template in the [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) collection by Shubham Saboo. Licensed under Apache-2.0 — see [LICENSE](LICENSE).
