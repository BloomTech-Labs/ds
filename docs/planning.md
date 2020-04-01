# Planning

Plans can be flexible and iterative. We don't expect DS students to stick to your original plan — but we do expect you to make one.  [President Eisenhower is famously quoted:](https://quoteinvestigator.com/2017/11/18/planning/) _"In preparing for battle I have always found that plans are useless, but planning is indispensable."_ This is true of DS too!

## Translate user problems into DS problems

DS students should participate in creating low-fidelity mockups, to get shared understanding, and make products that make a difference. This is recommended in [Stakeholder-Driven Data Science at Warby Parker:](https://blog.dominodatalab.com/stakeholder-driven-data-science-warby-parker/)

> First and foremost, we start with mockups to verify that if we put this deliverable in front of a decision maker, could they actually do something different.
> 
> We then spend some time thinking about the business value for a project. We then do rapid iteration, using fake data or using messy data. Just to say, “Hey, can we align on exactly what this thing is going to look like before we go and do all the hard work of all the data cleaning?
> 
> Just saying, “Here’s a couple of outputs that some different kinds of models could tell you. Which of these outputs is most useful to you?”
> 
> Finally, then we do the part that’s actually data science in the traditional sense.
> 
> I have found that becoming passionate about delivering data science products back to stakeholders can be just as satisfying as getting the correct math. If we do that, we’re going to wind up in a place where data science is a really respected, mature discipline that gets the attention and budget it deserves.

## What data is available?

_[Building Machine Learning Powered Applications](https://mlpowered.com/pdf/BMLPA_Chapter_1.pdf)_ lists these "levels of data availability, from best-case scenario to most challenging":

- **Labeled** data exists. 
- **Weakly labeled** data exists. "Some datasets contain labels that are not exactly a modeling target, but somewhat correlated with it. Playback and skip history for a music streaming service are examples of a weakly labeled dataset for predicting whether a user dislikes a song." 
- **Unlabeled** data exists. "This means we need to label the dataset, find a model that can learn from unlabeled data, or do a little bit of both."
- We need to **acquire** data.

What level of data is available for your product?

## How will you measure success?

As part of the planning process, teams must decide, how will we measure success on our problem?

For example, a recommender system could be evaluated with a variety of metrics, including:

- Precision, the % of products recommended that you like. Minimizes false positives.
- Recall, the % of products you'd like that are recommended. Minimizes false negatives.

Whenever possible, align metrics to the decision-making context and optimize for impact, such as increased sales from your recommender system. [Dollars are a great metric.](https://alexgude.com/blog/machine-learning-metrics-interview/) 

Then, using the metric you chose, [begin with baselines.](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa) What's the simplest heuristic you can use? For example, what if you just always recommended the most popular product to everyone? What would your evaluation metrics look like then? Can you make a model to beat this baseline?


## Plot your progress

Track your team's progress like [how the EFF tracks AI research progress](https://www.eff.org/ai/metrics) — with time on the x-axis, an evaluation metric on the y-axis, and a datapoint for each attempt, compared to some baseline:

![](https://user-images.githubusercontent.com/7278219/71922887-bd063980-3183-11ea-8930-33462eee48c0.png)

We care less about the end result (how high the metric goes at the end of the project) and more about the effort rate (how many attempts are made to iterate early). Your line's slope measures your learning rate.

## Choose your next step

The team's project plan doesn't need to be detailed, but individual next steps do.

At any given time, all DS students should have identified a concrete, detailed, tactical, specific next step. 

Labs Managers don't want to micromanage or disrupt flow. We just want to know, do you know what to do next, and how to do it? Or are you stuck?

Knowing _what_ to do next can be harder than the "how." Students have learned the skills they need during core instruction, but Labs is the first time that most students put all the pieces together in a multi-week, cross-functional, team project. 

So, you can use checklists and flowcharts, like [this data analysis checklist](https://www.kdnuggets.com/2015/03/jtleek-elements-data-analytic-style.html) and [visualization checklist](https://stephanieevergreen.com/updated-data-visualization-checklist/), to help you be productive and deliver quality work.


## Resources
- Emmanuel Ameisen, [Building Machine Learning Powered Applications: Going from Idea to Product, Preface & Chapter 1](https://mlpowered.com/pdf/BMLPA_Chapter_1.pdf), free 40 page PDF
- Google, [People + AI Guidebook, Chapter 1: User Needs + Defining Success](https://pair.withgoogle.com/chapter/user-needs/)
- Max Shron, [Stakeholder-Driven Data Science at Warby Parker](https://blog.dominodatalab.com/stakeholder-driven-data-science-warby-parker/), 30 minute video with transcript
- Jacqueline Nolis, [You're Not Paid to Model](https://youtu.be/tF-EY4MugWo), 25 minute video
