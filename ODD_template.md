# ODD

## 1. Purpose and patterns

Questions: What is the purpose of the model? What patterns are used to determine how useful the model is for its purpose?
Answer: ... 

## 2. Entities, state variables, and scales

Questions: What kinds of entities are in the model? By what state variables, or attributes, are these entities characterized? What are the temporal and spatial resolutions and extents of the model? 
Answer: ... 

Most ABMs include the following types of entities:
    * Agents/individuals.
    * Spatial units (e.g., grid cells). 
    * Environment. 
    * Collectives.  

In describing spatial and temporal scales and extents (the amount of space and time represented in a simulation), it is important to specify what the model’s units represent in reality. For example: “One time step represents one year and simulations were run for 100 years. One grid cell represents 1 ha and the model landscape comprised 1,000 x 1,000 ha; i.e., 10,000 square kilometers”.

## 3. Process overview and scheduling

Questions: Who (i.e., what entity) does what, and in what order? When are state variables updated? How is time modeled, as discrete steps or as a continuum over which both continuous processes and discrete events can occur? Except for very simple schedules, one should use pseudo-code to describe the schedule in every detail, so that the model can be re-implemented from this code. Ideally, the pseudo-code corresponds fully to the actual code used in the program implementing the ABM.
Answer: ... 

## 4. Design concepts

Questions: There are eleven design concepts. Most of these were discussed extensively by Railsback (2001) and Grimm and Railsback (2005; Chapter. 5), and are summarized here via the following questions:  
Basic principles. Which general concepts, theories, hypotheses, or modeling approaches are underlying the model’s design? Explain the relationship between these basic principles, the complexity expanded in this model, and the purpose of the study. How were they taken into account? Are they used at the level of submodels (e.g., decisions on land use, or foraging theory), or is their scope the system level (e.g., intermediate disturbance hypotheses)? Will the model provide insights about the basic principles themselves, i.e. their scope, their usefulness in real-world scenarios, validation, or modification? Does the model use new, or previously developed, theory for agent traits from which system dynamics emerge (e.g., ‘individual-based theory’ as described by Grimm and Railsback 2005)?
Answer: ... 

### Emergence 

What key results or outputs of the model are modeled as emerging from the adaptive traits, or behaviors, of individuals? 
Answer: ... 

### Adaptation

What adaptive traits do the individuals have? What rules do they have for making decisions or changing behavior in response to changes in themselves or their environment? 
Answer: ... 
### Objectives. 

If adaptive traits explicitly act to increase some measure of the individual's success at meeting some objective, what exactly is that objective and how is it measured? 
Answer: ... 

### Learning 

Many individuals or agents (but also organizations and institutions) change their adaptive traits over time as a consequence of their experience? If so, how?  
Answer: ... 

### Prediction 

Prediction is fundamental to successful decision-making; if an agent’s adaptive traits or learning procedures are based on estimating future consequences of decisions, how do agents predict the future conditions (either environmental or internal) they will experience? 
Answer: ... 
### Sensing 
What internal and environmental state variables are individuals assumed to sense and consider in their decisions? What state variables of which other individuals and entities can an individual perceive; 
Answer: ... 

### Interaction 
What kinds of interactions among agents are assumed? 
Answer: ... 

### Stochasticity 
What processes are modeled by assuming they are random or partly random? 
Answer: ... 

### Collectives 
Do the individuals form or belong to aggregations that affect, and are affected by, the individuals? 
Answer: ... 

### Observation 
What data are collected from the ABM for testing, understanding, and analyzing it, and how and when are they collected? A
Answer: ... 

## 5. Initialization

Questions: What is the initial state of the model world, i.e., at time t = 0 of a simulation run? In detail, how many entities of what type are there initially, and what are the exact values of their state variables (or how were they set stochastically)? Is initialization always the same, or is it allowed to vary among simulations? Are the initial values chosen arbitrarily or based on data? References to those data should be provided.
Answer: ...

## 6. Input data
Question: Does the model use input from external sources such as data files or other models to represent processes that change over time?
Answer: ...

## 7. Submodels
Questions: What, in detail, are the submodels that represent the processes listed in ‘Process overview and scheduling’? What are the model parameters, their dimensions, and reference values? How were submodels designed or chosen, and how were they parameterized and then tested?
Answer: ...


