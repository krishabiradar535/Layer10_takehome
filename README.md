# Layer10 Take-Home — Grounded Long-Term Memory

Structured extraction, deduplication, and a queryable memory graph built on `psf/requests` GitHub issues.

## Files

| File | Description |
|------|-------------|
| `layer10_final(1).ipynb` | Main pipeline |
| `app.py` | Streamlit interactive UI after running the code |
| `memory_graph(1).json` | Serialized memory store (entities, claims, evidence, artifacts) |
| `context_examples(1).json` | Example retrieved context packs for 6 queries |
| `memory_graph_overview.png` | Static overview graph |

## Setup

3 free API keys needed:
- `GROQ_API_KEY` — [console.groq.com](https://console.groq.com)
- `GITHUB_TOKEN` — [github.com/settings/tokens](https://github.com/settings/tokens)
- `NGROK_TOKEN` — [dashboard.ngrok.com](https://dashboard.ngrok.com)

Add these in the notebook, instructions are in the video submitted.
