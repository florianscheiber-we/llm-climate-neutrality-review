# llm-climate-neutrality-review

1. create key at openrouter.ai
2. put following line in terminal in project folder: 
LLM_ROUTER_API_KEY=<openrouter-key> python3 abstract-screening.py reference_list_paper_stage1.csv output.csv --provider router --model openai/gpt-4o-mini

NB: other models can be used, gpt-4o-mini is quite cheap though
