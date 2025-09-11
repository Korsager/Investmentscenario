# Investmentscenario

The prompt is a series of prompts that build on each other. It is important to provide as much information as possible.
For optimal use, you will need a paid subscription or access to the LLM's API to maximize token usage. 

The prompt could break in the free version, and limit results.


Prompt 1: Multiple regression model
- You will need to provide a dependent variable and independent variables
  _The Dependent variable will change based on the independent variables. In prompt 1, we measure the correlation_
  _It is recommended to use the stock price as the dependent variable_
  _Limit independent variables to 13 in the free version_
  _Based on the variables data on at least a 20-year horizon_

Prompt 2: Identify 100 events (75 long-term & 25 short-term)
- You will need to prepare various documents
    - Financial analysis
    - Sentiment analysis
    - Investment timeframe
    - Investment target price
    - Investment thesis

The prompt is identifying potential events that would affect the independent variables.

Prompt 3: Analyse the link between events
- No extra documents required
- The prompt is analyzing a potential chain of events, probability, and the impact on the dependent variable

Prompt 4: Event tree for worst, base, and best case
- No extra documents required
The prompt is identifying the lower and upper 5% percentiles, and the average based event scenario as the best case

Prompt 5: Re-evaluation of sentiment scoring for each case
- Provide sentiment scoring results and sentiment analysis
The prompt will redo the sentiment scoring for worst, base, and best cases for comparison to identify strength and risk factors.

The sentiment scoring can be adjusted in terms of the categories, the definition of the categories, and the scoring range definition.
