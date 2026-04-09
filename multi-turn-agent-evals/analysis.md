# Multi-Agent Evaluation Analysis

### Overall Assessment

There was a 100% Goal completion rate fot the 5 scenarios tested. Despite this, not all scenarios were completed in the manner intended. There was an overall 92% tool usage, 72% turn efficiency, and 80% policy adherence. 

There was actually slightly more turn efficiency for the demanded scenario, suggesting rushing an LLM may actually work. 

### Single Scenario Deep Dive

The scenario chosen for the deep dive is Scenario 4, being the confused customer. As per the metrics, this had perfect usage except for a 0 in policy adherence. 

The user first asks for something, not sure if it's headphones or earbuds. After (correctly) calling the search tool, and finding audio device recommendations, the LLM recommends thigs for "working at home," which isn't mentioned at all in the original prompt. 