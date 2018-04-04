Open questions in info-metrics and its applications across fields

## Group 1
  
- How change is measured, how rates of change are measured, what is time?
- Time from physics should be universally useful to other fields, but there could be other notions of time (e.g. number of events that have occurred) in specific fields that could be more useful there
- Time could be information-based: time "dilation" depending on how much is going on
- Picking the right time simplifies solutions
- Different notions of time could provide different insights
- reference states: from what to what; this could be discipline independent
- how do you pick relevant variables beyond years of trial and error?

## Group 2

- If you adopt info-metrics as rational inference, how do you know it's going to work? i.e. having good out of sample fit
    - If you don't get good fit, Jaynes says you need more or different constraints
- High dimensional cases are hard to fit with info-metrics, you could reduce the dimension of the data with PCA

## Group 3

- Computational issues
    - How do we make info entropy as a prior computationally efficient
    - Why is it that statisticians don't care about MaxEnt?
    - How do we deal with data reduction or compression to get metrics that are useful
    - How do we marry graph theory to queuing theory (as used in Bell Labs)?
- Broadening info-metrics
    - How do broaden the reach of maxent methods so that we can share methods across fields? How do you get people to understand maxent methods? and implement?
      - large deviation theory puts info-metrics in the framework of efficient estimation and could help make maxent more understandable
    - How do we frame questions in an amenable way for analysis
    - How do we make info-metric methods meaningful outside of physics
    - How do we identify experiments in order to maximize information acquisition? (identify constraints for models)

## Group 4

- What is the minimal information I need in order to connect subsystems?
- How do I infer with MaxEnt the links between sub-systems that are themselves well described by MaxEnt?


## Group at large

- If we had a new definition of complexity, what would we gain?
- Can we use complexity to decide how parameter-rich our models should be?
- Can non-parametric Bayes be a way to make model selection self-consistent with penalization of over-parameterization?
- Trying to prothsletize info-metrics
    - statistical equilib model vs ODE model: people think the ODE is causal, they don't know how to interpret the statistical equilibrium. needs to be linked generally to complex systems
    - still not clear how to apply maxent to Markov process
    - does maxent have a problem with big data?
    - philosophical differences between maxent as statistical mechanical tool, constrained by moments, and general inference tool constrained by any kind of information
    - making clear the assumptions and limitations of info-metrics as applied e.g. to prediction vs. model selection
    - easy to sell to areas with sparse data that need to imput micro-scale values
    - there should be a good wikipedia page about all this!
    - should we re-package Jaynes in a way that data scientists would like (e.g. machine learning)?
    - cross entropy could be an easier starting point in explaining info-metric approaches
    - we never know if we ever really have answers to our scientific questions, only probabilities---this leads naturally to adopting info-metric techniques
- strong similarities between ecology and economics w.r.t. maxent applicaitons
- there have been many successful applications of information entropy across fields! implies that this is the universal method---and that's because it's not a discipline-specific tool, it's a tool for reasoning
- what's the form of the entropy function---not just its maximum
- if there are different notions of time between systems, when we want to connect those systems, how do we reconcile their times?
- is maxent a tool for theory generation or data imputation?
- what does maxent tell us about the system when it fits the data well? when it fits the data poorly?
- finding the right constraints is key and not trivial

