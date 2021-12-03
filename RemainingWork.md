## Video Presentation
Approx. 5 min video describing your project (motivation, methods, what you learned, what's next).
Some examples are at https://www.youtube.com/c/ICSEconf/videos - look at the 8 min ones. 

The [Old] rubric is:

5 marks: creativity and visual appeal (talking over a slide deck is not very exciting; interpretive dance presentation fun)
10 marks: captures idea of study: motivation, methods, findings described clearly and obviously. 
5 marks: short discussion of implications for practice: what you learned, what's next

The new rubric is:

### Creativity (5 pts)
Presentation is interesting and engaging:

- This will be a joined effort I imagine. Right now the plan is to make it a PSA style presentation.
### Explains context (5 pts):
Presentation captures the context and problem/research question of the study, including previous work:

- Apparently Neil intended to mark our project a lot more heavily on the related works than he had indicated (as seen in the feedback for our interim report). I believe we should do a deep dive to find any other research we can and connect it to our project. This will be a big part of the final report too.
### Results and approach (5 pts)
Presentation concisely summarizes the approach and key results:

- We should all understand our results better (especially the bayesian results)
- Neha will do approach:
    - Survival analysis on subset of the software heritage graph using revision activity as a measure of health
    - Kaplan Meier Estimator
    - Cox proportional Hazards Model
    - Bayesian Inference (mention reasoning for chosen distribution)
- Manish will do results:
    - Explain KM curves, show Bayesian curves
    - Explain Cox results

### Discusses implication (5 pts):
Presentation clearly explains implications, including ethical, of the results on practice and research:

## Final Report

We should address the seeming contradiction between KM results and Cox (namely the host-type, which is discussed by Ali et al. and the commit_freq), the Cox model gives more weight to the beginning section of the curve (where the majority of the projects are still in the study).