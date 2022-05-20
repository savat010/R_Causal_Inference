# R_Causal_Inference

# Background
The Castle Doctrine is a law which states that individuals have the right to use reasonable force, including deadly force, to protect themselves against an intruder in their home. Between 2000 and 2010, twenty-one states expanded the castle doctrine by permitting lethal force to be used outside the home in some places. This new expansion of the castle doctrine was called ‘Stand your Ground.’ This expansion meant that victims no longer had a duty to retreat in public places if they felt threatened. Instead, they could retaliate in lethal self-defense. 

# Analysis
In the paper titled Does Strengthening Self Defense Law Deter Crime or Escalate Violence, authors Cheng Cheng and Mark Hoekstra used FBI data to analyze the impact of the expansion of the Castle Doctrine on Homicides in the United States using a difference-in-differences approach. In this analysis, our team expanded Cheng and Hoekstra’s analysis to discover how the implementation of Stand Your Ground affected robberies in Florida using a **synthetic control using the Lasso method** approach. We chose to analyze the effect of the Stand Your Ground Law in Florida because it was the first state to expand the Castle Doctrine. According to the FBI data, the law passed in 2006 in Florida.

# Overview of Data
This analysis used the same data that Cheng and Hoekstra used from the fbi.gov website to analyze the affect of the Castle Doctrine on robberies. The data is panel data, consisting of crime rates between the years of 2000 and 2010 for fifty states.

The treatment group is Florida and the control group is the states which did not pass the Stand Your Ground Law until after 2010 (30 states). The output variable is robbery per 100,000 state population. Each unit of observation is "robberies per 100,000 state population - year," meaning we have multiple observations for robberies per 100,00 state population over years of time.
