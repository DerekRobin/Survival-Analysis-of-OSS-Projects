# PSA: Recognizing the Signs of a Healthy Open Source Project
## Derek Robinson, Keanelek Enns, Neha Koulecar, and Manish Sihag
## University of Victoria, Canada

*PSA music begins, fade into video*

**Derek:**

Are you a new developer trying to make a name for yourself in the open source community?

Do the projects you work on end up abandoned in a matter of months?

What on Earth are you supposed to do about it?

Fear not, this public service announcement is for you!

Today we will discuss how to recognize the signs of a healthy open source project, so you can choose where you spend your time wisely.

...

**Manish:**

...

**Neha:**

...

**Keanu:**

### For Your Consideration
#### DISCLAIMER:
It is important to understand that software development is a complex subject, and there is rarely a "one size fits all" solution to any of its problems.

This study measured health of a project in terms of how long it was revised for, with the assumption that longer is better, but the metrics used here may not apply to all software projects, such as closed projects, where a longer duration is associated with higher cost, and is usually not desirable [6].

As discussed by Samoladas et al., success can be measured in many ways [5], perhaps a project coordinator measures the success of their project by the recognition and notoriety it affords them and does not care about the longevity of the project.

### Implications on Practice

The results of this study, and the studies it is based on, give developers of open source software insights into which projects are likely to receive long term attention from other developers.

Understanding 
- These results may affect how developers choose which projects they work on. Perhaps there are more ethical projects that do not have a large number of developers or major releases, etc. The hope is that this study would not deter developers from helping good causes simply based on how well the project is already doing. Maybe that developer can make the difference between the survival of that project and its death.
- Maybe the results should not be interpretted as "find projects that already have lots of support", but rather "give support to the projects that mean the most to you so you can prolong their life". Maybe the former is a valid reason too, but probably shouldn't be the only deciding factor.

### Implications on Research

This study has multiple implications on previous and future research:

- The results shown here affirm the results of other studies that imply a healthy community of developers is among the most crucial indicators of whether a project will survive for an extended period of time.

- Though our results are similar qualitatively, there were quantitative discrepencies between our results and the results of the original authors.
It is possible that some differences in our results arose due to the non-reproducable nature of the studied dataset (cite software heritage and perils of mining git), but the most likely cause of these differences is a variation in approaches for data retrieval and analysis tools.
We therefore call for researchers to improve the replicability of their studies by providing artifacts.

- To our knowledge, this is the first known application of a Bayesian approach to survival analysis on open source software.
Prior distributions were chosen based on survival analysis done in other domains (cite kelter and McElreath), but more investigation as to whether these priors are effective in this domain should be done.
In the future, the models created by this study should be used to predict durations of open source software projects in other datasets to measure their predictive power and the degree to which they are fitted to the studied data.

That's right, today we learned that there is no I in team, and there is a statistically significant probability that your project won't make it in the long run if you don't have a team.

*Outro Plays*

Now that you can recognize the attributes of a long-lasting open source project, get out there and make your efforts count!