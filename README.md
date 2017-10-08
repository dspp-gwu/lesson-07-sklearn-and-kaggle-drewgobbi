# sklearn & kaggle

For this week, well be doing something a little different.  We are going to use a nice data science challenge from Kaggle.  To understand how well we do, we will also use an evaluation metric called the ROC.  To learn about the ROC, pleased: 

Listen to this episode of the linear digressions podcast: [Rock the ROC Curve](http://lineardigressions.com/episodes/2017/1/29/rock-the-roc-curve)

And as you get ready to launch your project, you may want to ponder what you can do with data science. 

# What can I do with Data Science? 

Now that we're getting to the core tool we'll use, scikit learn, it's worth reviewing what we can do with this tool.  The heart of data science involves predictive algorithms.  Can we predict some outcome in the future? There are a few types of things that flow fairly easily and directly from this: 

- Early Warning: Can I predict where rats are most likely to infest? Can I detect which children are being exposed to lead?  Can I predict which officer is likely to use of force in an unauthorized manner? Can I detect where watermains are likely to fail? 
- Resource Prioritization: Can I determine how to prioritize restaurants to inspect with potential health and safety violations? Can I determine how to prioritize home inspections for lead?  Can I prioritize which officers get assignments or interventions that reduce their risk of an adverse event? 
- Scheduling and Assignment: Can I improve the scheduling and assignment of police cruisers/medics/ambulances/fire trucks responding to an incident? Can I better assign officers to times and places where crime is likely to be high? 
- Routing: Can I route an incoming 911/311/service request call more efficiently/effectively? Can I give inspectors a geographically more efficient map of inspections to complete on a daily basis? 

Relatedly, there are a two additional related goals that move us a little more closely to public policy: 

- Policy & Practice Recommendations: Can I recommend ways to improve maternal healthy, outcomes for returning citizens, educational outcomes, etc.?
- Impact Evaluation: Can I evaluate the impact of a policy, program, or practice? 

These are harder, because they often involve detailed evaluation design questions. Essentially they take the tools of data science and use them to inform existing problems. These are often layered on top of or drawn from a predictive model.  So, for example, if we find that officers are most likely to be involved in adverse incidents if the are scheduled for night shift, respond to a high number of violent offenses, and have particular supervisors.  Possible recommendations include rotating officers out of night shifts where possible, reducing the number of violent incidents any single officer responds to, and an intervention with the supervisor. Each of these could then be evaluated using different data science techniques so that we can try to draw a causal inference about how effective the intervention was.  

And, finally, there are a number of policy considerations that need to be considered when deploying models to serve public policies. 

- Is the model public and transparent?  Even if the data cannot be revealed, is it clear what kind of information is being employed? 
- Is there a human feedback mechanism for the model? 
- Can the model adapt to changes over time?  What if it stops being predictive? 
- Is the model being regularly evaluated?  If so how and by whom?  Are the results of these evaluations made public? 
- What kinds of harms could the model cause?  Does it trigger penalties or punishments?   

Keeping all of this in mind should inform the types of models you want to build.  That said, your model doesn't have to solve all the world's problems or be perfect; you just need to know its limitations. 
