# llm-climate-neutrality-review


## abstract screening
1. create key at openrouter.ai (or contact Florian Scheiber for key)
2. put following line in terminal in project folder: 
LLM_ROUTER_API_KEY=<openrouter-key> python3 abstract-screening.py reference_list_papers/reference_list_paper_stage1.csv output.csv --provider router --model <modelname>
--> abstracts are screened
NB: available <modelname> can be found in openrouter_available_models.rtf

## compare abstract results with Cadima
1. open compare_abstract_results_cadima_llm
2. change LLM_RUN_OUTPUT and CADIMA_STAGE according to your analysis
3. comparision_categories.json and overlap_info.json are created as well as overview output in Console

