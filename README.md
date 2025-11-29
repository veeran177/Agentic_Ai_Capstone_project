# Agentic_Ai_Capstone_project
Enterprise Data-Insights Agent for Bank Marketing Campaigns

# Enterprise Data-Insights Agent for Bank Marketing Campaigns

**Track:** Enterprise Agents  
**Author:** YOUR_NAME

## Summary
This project demonstrates an Agentic system that automates business intelligence on the Bank Marketing dataset. The agent ingests data, performs EDA, constructs preprocessing pipelines, trains models, evaluates them, and generates an executive summary. It demonstrates Agent Development Kit concepts: tools, sequential and loop agents, session & memory, and observability.

## Features demonstrated (≥3)
- Tools: custom EDA / preprocessing / training tools.
- Sessions & Memory: persistent `agent_memory_capstone.json`.
- Sequential & Loop Agents: `agent_pipeline_run` and `improvement_loop`.
- Observability: logging to `agent_trace.log`.
- LLM adapter stub for natural-language summaries (replace stub with Gemini call for bonus).

## How to run
1. Add `bank-full.csv` to Kaggle dataset inputs (or upload to `/mnt/data/`).  
2. Open the Kaggle Notebook and run cells top-to-bottom.  
3. Outputs produced:
   - `agent_artifacts.json`: training trace & metrics.
   - `executive_summary.txt`: NL summary (LLM stub).
   - `agent_memory_capstone.json`: memory & session info.
   - `agent_trace.log`: logs.

## How this maps to Capstone rubric
- **Track:** Enterprise Agents — data-driven business solution.  
- **Pitch & value:** reduces manual analysis time; produces actionable insights for marketing campaigns.  
- **Implementation:** Includes agentic features, clean modular code, and documentation.  
- **Extension:** Replace `llm_summarize` with Gemini/OpenAI client for effective LLM use; deploy to Cloud Run or Agent Engine for runtime.

## Future improvements
- Replace LLM stub with Gemini API for NL generation and reasoning.  
- Persistent vector DB for long-term memory retrieval.  
- Multi-agent orchestration with separate microservices and A2A messaging.  
- Add fairness/federated checks and feature drift monitoring.

