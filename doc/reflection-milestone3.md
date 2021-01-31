reflection-milestone3.md
================
Cheuk Ho, Hazel Jiang, Anita Li, Ivy Zhang
30/01/2021

The dashboard we created in R offers users three options of filtering
`Department`, `Gender` and `Age` to see how different factors (`Monthly
Income`, `Work Life Balance`, `Business Travel` and `Environment
Satisfaction`) contributes to employee attrition based on IBM employee
satisfaction survey data. We made our dashboard interactive so users
could see the attrition among the 4 key factors for different employee
segments, which could help our users to develop their action plan for
next step.

We are able to implement most of what we have in the proposal to the
dashboard, and our users are able to see the attrition in proportions
among the `WorkLife Balance`, `Environment Satisfaction` and `Frequency
of Business Travel` plots and different quantile information in the
`Monthly Income` plot by playing with our filters. In addition to that,
we also add tooltips in each plots, which makes our plots more user
friendly.

However, during our implementation of our proposal, we encountered some
problems as well. The first problem is that we could not clear our
filters. If we clear any filters, instead of being empty plots, our
plots will stay with the result from the latest plots with information
in it. Another problem we have is that we are not able to add legend to
the plots. Right now, we are using strings with different colors to
present attrited /not attrited, we are hoping to find other ways like
using `cowplot` or using different column output to bring back the
legend.

We haven’t received any feedbacks yet, but comparing to what we have
done using Python, we implement a better color scheme of our plots,
which makes the presentation more pleasant. However, we still believe
that for future improvements, it can be useful to add one or two empty
plots that allow users to choose the variables (numerical and
categorical) to plot against attrition offering them more flexibility in
exploring the data base on their needs and interests.
