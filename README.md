# Statistical Rethinking 2024 Resources

This is a list of resources that have been mentioned during the Statistical Rethinking course in places such as the online discussion, Discord chat, lectures, etc


# Workflow



## Misc
|Name/Link|Description|
|:---|:---|
|[Bayesian Workflow (Gelman et al 2020)](https://doi.org/10.48550/arXiv.2011.01808)|100p paper on Bayesian workflow, Gelman is also working on a book version of this|
|[Telling Stories with Data (Alexander)](https://tellingstorieswithdata.com/)|post-stratification with code included, but also generally about statistical communication, programming, and modeling|
|[Regression and Other Stories (Gelman, Hill, Vehtari 2020)](https://avehtari.github.io/ROS-Examples/)|Site has a link to pdf of book|
|[Active Statistics (Gelman, Vehtari 2024)](https://avehtari.github.io/ActiveStatistics/)|Book designed to accompany Regression and Other Stories, hundreds of stories, activities, and discussion problems on applied statistics and causal inference|
|[Towards A Principled Bayesian Workflow (Betancourt 2020)](https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html)||
|[Bayesian Statistics without Frequentist Language (McElreath, 2017)](https://youtu.be/yakg94HyWdE?si=07mPP8LngVbmbOpl)|Building a model slowly over time and then adding complexity|


## Planning
|Name/Link|Description|
|:---|:---|
|[What Is Your Estimand? Defining the Target Quantity Connects Statistical Evidence to Theory (Lundberg, Johnson, Stewart 2021)](https://doi.org/10.1177/00031224211004187)|Every quantitative study must be able to answer the question: what is your estimand?|
|[Modeling Social Behavior: Mathematical and Agent-Based Models of Social Dynamics and Cultural Evolution (Smaldino 2023)](https://press.princeton.edu/books/paperback/9780691224145/modeling-social-behavior) ([worldcat](https://search.worldcat.org/title/1362499377))|How to build agent based models and interrogate them, former McElreath student|
|[Models of Social Dynamics](https://www.youtube.com/watch?v=ISDcJDerFN4)|Intro  lecture series on agent based modeling by by Paul Smaldino|


## Reporting Results

|Name/Link|Description|
|:---|:---|
|[Hypothetical Outcome Plots Outperform Error Bars and Violin Plots for Inferences About Reliability of Variable Ordering (Hullman, Resnick, Adar 2015)](https://doi.org/10.1371/journal.pone.0142444)|[2023 Lecture 20](https://youtu.be/qwF-st2NGTU?feature=shared&t=4691) ([slides](https://github.com/rmcelreath/stat_rethinking_2024/blob/main/slides/Lecture_20-horoscopes.pdf))|
|[*How Charts Lie: Getting Smarter About Visual Information* by Alberto Cairo](https://search.worldcat.org/en/title/1137807427)|[2023 Lecture 20](https://youtu.be/qwF-st2NGTU?feature=shared&t=4691) ([slides](https://github.com/rmcelreath/stat_rethinking_2024/blob/main/slides/Lecture_20-horoscopes.pdf))|

# Applied Examples
|Name/Link|Description|
|:---|:---|
|[Ordinal Regression Models in Psychology: A Tutorial (Burkner, Vuorre 2019)](https://doi.org/10.1177/2515245918823199)|Applied ordered categorical outcome model, general intro with practical example|
|[Estimating Monotonic Effects with brms (Burkner 2023)](https://cran.r-project.org/web/packages/brms/vignettes/brms_monotonic.html)|Applied ordered categorical predictor model|
|[Parkinson’s Disease Patients Treated by Subthalamic Deep Brain Stimulation (Jech et al 2019)](https://doi.org/10.3389/fnagi.2022.886491)|Applied ordered categorical outcome model in clinical neuroscience, a first attempt, authors would do things differently now|
|[Analysis of pain-intensity measurements (Skovlund, Breivik 2016)](https://dx.doi.org/10.1016/j.sjpain.2016.08.005)|Modeling visual analog scores|
|[A Probability Model for Golf Putting (Gelman, 2002)](www.stat.columbia.edu/~gelman/research/published/golf.pdf) and [Model building and expansion for golf putting (Gelman 2022)](https://mc-stan.org/users/documentation/case-studies/golf.html)|Example of getting away from interpreting coefficients|
|[Multilevel Regression and Poststratification Case Studies](https://bookdown.org/jl5522/MRP-case-studies/)|post-stratification case studies|
|[Perfect Counterfactuals for Epidemic Simulations (Kaminsky, Keegan, Metcalf, Lessler 2019)](https://doi.org/10.1098%2Frstb.2018.0279)||
|[High rate of extrapair paternity in a human population demonstrates diversity in human reproductive strategies (Scelza et al 2020)](https://doi.org/10.1126/sciadv.aay6195)|[2023 Lecture 17](https://youtu.be/mt9WKbQJrI4?si=1Uh-H8jJ_e2OkQdo&t=2419) ([slides](https://github.com/rmcelreath/stat_rethinking_2024/blob/main/slides/Lecture_17-measurement.pdf))|

# Causal Inference and DAGs
|Name/Link|Description|
|:---|:---|
|[A Crash Course in Good and Bad Controls (Cineli, Forney, Pearl 2021)](https://doi.org/10.1177/00491241221099552)|[Lecture 6 - Good and Bad Controls](https://youtu.be/uanZZLlzKHw?si=y4bZWQ4WoHqMy7k7&t=2631) (43:55)|
|[The Book of Why: The New Science of Cause and Effect (Pearl, Mackenzie 2018)](https://search.worldcat.org/en/title/1003311466)|[2023 Lecture 06](https://youtu.be/uanZZLlzKHw?si=T5xThhuhujC0wvIq&t=868) ([slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-06?slide=17))|
|[Causal Inference in Statistics: A Primer (Pearl 2016)](https://www.wiley.com/en-us/Causal+Inference+in+Statistics%3A+A+Primer-p-9781119186847)|Causal inference primer by Judea Pearl, recommended next reading after Rethinking course for more causal inference|
|[Causal foundations of bias, disparity and fairness (Traag, Waltman 2022)](https://doi.org/10.48550/arXiv.2207.13665)|[2023 Lecture 09](https://youtu.be/Zi6N3GLUJmw?si=lDeJwrPj7TuqjmFG&t=526) ([slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-09?slide=10)) and [2023 Lecture 10](https://youtu.be/jokxu18egu0?si=_MnzdmORMZwa5etG&t=1166) ([slides](https://speakerdeck.com/rmcelreath/statistical-rethinking-2023-lecture-10?slide=16))|
|[ggdag R package](https://cran.r-project.org/web/packages/ggdag/vignettes/intro-to-ggdag.html)| A tidyverse extension of the dagitty R package |
|[A Causal Framework for Cross-Cultural Generalizability (Deffner, Rohrer, McElreath 2022)](http://dx.doi.org/10.1177/25152459221106366)|Selection bias represented by DAGs|
|[Graphical Causal Models for Survey Inference (Schuessler, Selb 2021)](https://doi.org/10.1177/00491241231176851)|sampling (survey non-response) bias and post-stratification|
|[Bayesian Networks (Scutari, Denis 2021)](https://www.bnlearn.com/book-crc-2ed/)|About Bayesian network learning, but also has other ways to draw DAGs|
|[TikZ latex package](https://tikz.org/)|Latex package used for drawing DAGs, can export to pdf|
|[Causal Inference: What If (Hernan, Robins 2020)](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)|online book with printed version pending|
|[Probabilistic Graphical Models course by Daphne Koller (Stanford)](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=ProbabilisticGraphicalModels)|Plate notation pops up in Bayesian statistics but never really explained. It's another version of DAGs. This course does go into it|
|[Probabilistic Graphical Models Specialization in Coursera by Daphne Koller](https://www.coursera.org/specializations/probabilistic-graphical-models)|Plate notation pops up in Bayesian statistics but never really explained. It's another version of DAGs. This course does go into it|

# MCMC (Markov chain Monte Carlo)
|Name/Link|Description|
|:---|:---|
|[MCMC Interactive Gallery](https://chi-feng.github.io/mcmc-demo/app.html)|Visualization of Hamiltonian Monte Carlo (HMC)|
|[Bulk effective sample size (bulk-ESS)](https://mc-stan.org/posterior/reference/ess_bulk.html)|ess_bulk as a new diagnostic replacing n_eff|

# Model Comparison and Selection
|Name/Link|Description|
|:---|:---|
|[Nabiximols treatment efficiency - Improved LOO computation (Vehtari 2024)](https://users.aalto.fi/~ave/casestudies/Nabiximols/nabiximols.html#improved-loo-computation)|Example of model comparison using non-ideal models. Generally, comparisons using models with known flaws useful for incremental model development, exploring what other models to try, and informative in and of itself|
|[Projective inference in high-dimensional problems: Prediction and feature selection (Piironen, Paasiniemi, Vehtari 2020)](https://doi.org/10.1214/20-EJS1711)|Procedure fitting a reference model and comparing with simpler models via algorithm that is less computationally intensive than refitting every model. Authors have a related [`projpred`](https://mc-stan.org/projpred/) R package|

# Myths and Bad Habits
|Name/Link|Description|
|:---|:---|
|[What's Wrong with Change In General?](https://hbiostat.org/bbr/change.html#sec-change-gen)|Explanation of why in general change scores are a bad idea. A section of *Biostatistics for Biomedical Research* online book by Frank Harrell|
|[Analyzing ordinal data with metric models: What could possibly go wrong? (Liddell, Kruschke 2018)](https://doi.org/10.1016/j.jesp.2018.08.009)|dangers of analyzing ordinal data such as likert scales with a metric model|
|[How conditioning on post-treatment variables can ruin your experiment and what to do about it (Montgomery, Nyhan, Torres 2018)](https://doi.org/10.1111/ajps.12357)|Dangers of conditioning on post-treatment variables|
|[Randomisation is not about balance, nor about homogeneity but about randomness](https://errorstatistics.com/2020/04/20/s-senn-randomisation-is-not-about-balance-nor-about-homogeneity-but-about-randomness-guest-post/)|blog post about what randomization is for|
|[Seven myths of randomisation in clinical trials](https://doi.org/10.1002/sim.5713)|article by same author as above|
|[Common Probability Problems Arise from Simple Invariances (Frank 2017)](https://www.youtube.com/watch?v=c5kmJfDJhJY)|technical|

# Priors
|Name/Link|Description|
|:---|:---|
|[Bayesian Inference without Probability Density Functions (Goodrich 2021)](https://www.youtube.com/watch?v=_wfZSvasLFk)|Framework for using priors created by eliciting quantiles from subject matter experts|
|[Quantile Function Stan Code](https://github.com/bgoodri/StanCon2020/blob/master/quantile_functions.stan)|Using priors created by eliciting quantiles from subject matter experts, Ben Goodrich is someone that works on this|
|[Hybrid elicitation and quantile-parametrized likelihood (Perepolkin, Goodrich, Sahlin 2023)](https://doi.org/10.1007/s11222-023-10325-0)|Using priors created by eliciting quantiles from subject matter experts|

# Probability Theory
|Name/Link|Description|
|:---|:---|
|[Probability Theory as Logic (Jaynes 1990)](https://bayes.wustl.edu/etj/articles/prob.as.logic.pdf)|epistemological vs. ontological assumptions in statistics. Technical|
|[Probability Theory: The Logic of Science (Jaynes 1995 posthumously?)](https://bayes.wustl.edu/etj/prob/)|epistemological vs. ontological assumptions in statistics. Technical, rough, and weird in places. First few chapters relevant|
|[Jaynes bibliography with pdfs](https://bayes.wustl.edu/etj/node1.html)|


# Survival Analysis/Event History/Time Analysis
|Name/Link|Description|
|:---|:---|
|[*Applied Longitudinal Data Analysis* by Singer and Willett](https://doi.org/10.1093/acprof:oso/9780195152968.001.0001)|Textbook with in-depth treatment but not a modern approach to estimation|
|[Informed Bayesian Survival Analysis (Bartos, Aust, Haaf 2022)](https://doi.org/10.1186/s12874-022-01676-9)|Relevant BMC Medical Research Methodology article|
|[Hierarchical Bayesian continuous time dynamic modeling (Driver, Voelkle 2018)](https://doi.org/10.1037/met0000168)|Continuous time dynamic model analysis approach|
|[Hierarchical Continuous Time Dynamic Modelling for Psychology and the Social Sciences (Driver 2017)](https://edoc.hu-berlin.de/bitstream/handle/18452/19659/dissertation_driver_charles.pdf)|Dissertation by same author as above (may be easier for beginner to read than above article)|

# Tutorials and Guides
|Name/Link|Description|
|:---|:---|
|[A guide to modeling proportions with Bayesian beta and zero-inflated beta regression models](https://doi.org/10.59350/7p1a4-0tw75)|Tutorial on modeling outcomes that range from 0-1|
|[Hierarchical Modeling (Betancourt, 2020)](https://betanalpha.github.io/assets/case_studies/hierarchical_modeling.html)|technical, more about the funnel problem and multilevel models, examples of when centered vs non-centered models are better|
|[Complex models and reparameterization - Box 11.2 Cholesky factorization](https://vasishth.github.io/bayescogsci/book/ch-complexstan.html#sec-corrstan)|More in-depth explanation of how Cholesky factorization works|
|[Entropy (for data science) Clearly Explained](https://youtu.be/YtebGVx-Fxw)|Information entropy derivation explained as surprise|

# Misc Specific Topics
|Name/Link|Description|
|:---|:---|
|[Steve Frank papers](https://stevefrank.org/pub-topic.html)|He has papers on which generative models correspond to which probability distributions|
|[Regression Modeling Strategies (Harrel 2015 and 2024)](https://hbiostat.org/rmsc/)|Chapter 2.4 tackles splines|
|[Visualizing the differences between Bayesian posterior predictions, linear predictions, and the expectation of posterior predictions (Heiss, 2022)](https://doi.org/10.59350/xge39-emt86)||
|[Prediction can be safely used as a proxy for explanation in causally consistent Bayesian generalized linear models (Scholz, Burkner 2022)](https://doi.org/10.48550/arXiv.2210.06927)|models under misspecification|
|[White House "Nelson" memo](https://www.whitehouse.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-access-Memo.pdf)|future requirement that publications and research data arising from US federal funds be made publicly accessible immediately upon publication|
|[Bayesian Data Analysis (Gelman, Vehtari, et al 2021)](https://www.stat.columbia.edu/~gelman/book/)|Gaussian processes don't scale well, so fast approximations are used. This book contains a derivation of approximations of Gaussian proccesses. Also has a birthday example of Gaussian processes|
|[Bayesian workflow book - Birthdays (Vehtari 2020)](https://avehtari.github.io/casestudies/Birthdays/birthdays.html)|Case study page for birthday example above|
|[Deep Neural Networks as Gaussian Processes (Sohl-Dickstein et al 2017)](https://doi.org/10.48550/arXiv.1711.00165)|link between Gaussian proesses and neural networks|


# Misc General
|Name/Link|Description|
|:---|:---|
|[International Conference on Multilevel Analysis](https://multilevel.fss.uu.nl/)||
|[Elements of Evolutionary Anthropology](https://elevanth.org/blog/)|McElreath blog, "Occasional text on evolutionary anthropology, statistical inference, and the intersection of the two."|
|[Stan forums](https://discourse.mc-stan.org/)|Online community for applied statistical models|







