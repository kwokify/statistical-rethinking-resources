# Statistical Rethinking 2024 Resources

This is a list of resources that have been mentioned during the Statistical Rethinking course in places such as the online discussion, Discord chat, lectures, etc


# Workflow
|Name/Link|Description|
|:---|:---|
|[Bayesian Workflow (Gelman et al 2020)](https://doi.org/10.48550/arXiv.2011.01808)|100p paper on Bayesian workflow, Gelman is also working on a book version of this|
|[Telling Stories with Data (Alexander)](https://tellingstorieswithdata.com/)|post-stratification with code included, but also generally about statistical communication, programming, and modeling|
|[Regression and Other Stories (Gelman, Hill, Vehtari 2020)](https://avehtari.github.io/ROS-Examples/)|Site has a link to pdf of book|
|[Towards A Principled Bayesian Workflow (Betancourt 2020)](https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html)|
|[Bayesian Statistics without Frequentist Language (McElreath, 2017)](https://youtu.be/yakg94HyWdE?si=07mPP8LngVbmbOpl)|Building a model slowly over time and then adding complexity|

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

# Bad Habits
|Name/Link|Description|
|:---|:---|
|[What's Wrong with Change In General?](https://hbiostat.org/bbr/change.html#sec-change-gen)|Explanation of why in general change scores are a bad idea. A section of *Biostatistics for Biomedical Research* online book by Frank Harrell|
|[Analyzing ordinal data with metric models: What could possibly go wrong? (Liddell, Kruschke 2018)](https://doi.org/10.1016/j.jesp.2018.08.009)|dangers of analyzing ordinal data such as likert scales with a metric model|
|[How conditioning on post-treatment variables can ruin your experiment and what to do about it (Montgomery, Nyhan, Torres 2018)](https://doi.org/10.1111/ajps.12357)|Dangers of conditioning on post-treatment variables|

# Causal Inference and DAGs
|Name/Link|Description|
|:---|:---|
|[A Crash Course in Good and Bad Controls (Cineli, Forney, Pearl 2021)](https://doi.org/10.1177/00491241221099552)| |[Lecture 6 - Good and Bad Controls](https://youtu.be/uanZZLlzKHw?si=y4bZWQ4WoHqMy7k7&t=2631) (43:55)|
|[ggdag R package](https://cran.r-project.org/web/packages/ggdag/vignettes/intro-to-ggdag.html)| A tidyverse extension of the dagitty R package |
|[A Causal Framework for Cross-Cultural Generalizability (Deffner, Rohrer, McElreath 2022)](http://dx.doi.org/10.1177/25152459221106366)|Selection bias represented by DAGs|
|[Graphical Causal Models for Survey Inference (Schuessler, Selb 2021)](https://doi.org/10.1177/00491241231176851)|sampling (survey non-response) bias and post-stratification|
|[Bayesian Networks (Scutari, Denis 2021)](https://www.bnlearn.com/book-crc-2ed/)|Book with other ways to draw DAGs|
|[TikZ latex package](https://tikz.org/)|Latex package used for drawing DAGs, can export to pdf|
|[Causal Inference in Statistics (Pearl 2016)](https://www.wiley.com/en-us/Causal+Inference+in+Statistics%3A+A+Primer-p-9781119186847)|Causal inference primer by Judea Pearl|
|[Causal Inference: What If (Hernan, Robins 2020)](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)|online book with printed version pending|

# Probability Theory
|Name/Link|Description|
|:---|:---|
|[Probability Theory as Logic (Jaynes 1990)](https://bayes.wustl.edu/etj/articles/prob.as.logic.pdf)|epistemological vs. ontological assumptions in statistics. Technical|
|[Probability Theory: The Logic of Science (Jaynes 1995 posthumously)](https://bayes.wustl.edu/etj/prob/)|epistemological vs. ontological assumptions in statistics. Technical, rough, and weird in places. First few chapters relevant|Discord. [Jaynes bibliography with pdfs](https://bayes.wustl.edu/etj/node1.html)|
|[Jaynes bibliography with pdfs](https://bayes.wustl.edu/etj/node1.html)||

# MCMC
|Name/Link|Description|
|:---|:---|
|[MCMC Interactive Gallery](https://chi-feng.github.io/mcmc-demo/app.html)|Visualization of Hamiltonian Monte Carlo (HMC)|
|[Bulk effective sample size (bulk-ESS)](https://mc-stan.org/posterior/reference/ess_bulk.html)|ess_bulk as a new diagnostic replacing n_eff|

# Survival Analysis/Event History/Time Analysis
|Name/Link|Description|
|:---|:---|
|[*Applied Longitudinal Data Analysis* by Singer and Willett](https://doi.org/10.1093/acprof:oso/9780195152968.001.0001)|Textbook with in-depth treatment but not a modern approach to estimation|
|[Informed Bayesian Survival Analysis (Bartos, Aust, Haaf 2022)](https://doi.org/10.1186/s12874-022-01676-9)|Relevant BMC Medical Research Methodology article|
|[Hierarchical Bayesian continuous time dynamic modeling (Driver, Voelkle 2018)](https://doi.org/10.1037/met0000168)|Continuous time dynamic model analysis approach|
|[Hierarchical Continuous Time Dynamic Modelling for Psychology and the Social Sciences (Driver 2017)](https://edoc.hu-berlin.de/bitstream/handle/18452/19659/dissertation_driver_charles.pdf)|Dissertation by same author as above (may be easier for beginner to read than above article)|


# Misc Specific Topics
|Name/Link|Description|
|:---|:---|
|[Randomisation is not about balance, nor about homogeneity but about randomness](https://errorstatistics.com/2020/04/20/s-senn-randomisation-is-not-about-balance-nor-about-homogeneity-but-about-randomness-guest-post/)
|blog post about what randomization is for|
|[Seven myths of randomisation in clinical trials](https://doi.org/10.1002/sim.5713)
|article by same author as above|
|[Complex models and reparameterization](https://vasishth.github.io/bayescogsci/book/ch-complexstan.html#sec-corrstan)
|Further explanation of how Cholesky factorization works?|
|[What Is Your Estimand? Defining the Target Quantity Connects Statistical Evidence to Theory (Lundberg, Johnson,   Stewart 2021)](https://doi.org/10.1177/00031224211004187)||
|[Entropy (for data science) Clearly Explained](https://youtu.be/YtebGVx-Fxw)|Information entropy derivation explained as surprise|
|[Steve Frank papers](https://stevefrank.org/pub-topic.html)|He has papers on on which generative models correspond to which probability distributions|
|[Common Probability Problems Arise from Simple Invariances (Frank 2017)](https://www.youtube.com/watch?v=c5kmJfDJhJY)||
|[Regression Modeling Strategies (Harrel 2015 and 2024)](https://hbiostat.org/rmsc/)|Chapter 2.4 tackles splines|
|[Visualizing the differences between Bayesian posterior predictions, linear predictions, and the expectation of posterior predictions (Heiss, 2022)](https://doi.org/10.59350/xge39-emt86)||
|[A guide to modeling proportions with Bayesian beta and zero-inflated beta regression models](https://doi.org/10.59350/7p1a4-0tw75)|Tutorial on modeling outcomes that range from 0-1|
|[Prediction can be safely used as a proxy for explanation in causally consistent Bayesian generalized linear models (Scholz, Burkner 2022)](https://doi.org/10.48550/arXiv.2210.06927)|models under misspecification|
|[Perfect counterfactuals for epidemic simulations (Metcalf et al 2019)](https://doi.org/10.1098%2Frstb.2018.0279)||
|[Hierarchical Modeling (Betancourt, 2020)](https://betanalpha.github.io/assets/case_studies/hierarchical_modeling.html)|technical, more about the funnel problem and multilevel models, examples of when centered vs non-centered models are better|
|[White House "Nelson" memo](https://www.whitehouse.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-access-Memo.pdf)|future requirement that publications and research data arising from US federal funds be made publicly accessible immediately upon publication|

# Misc General
|Name/Link|Description|
|:---|:---|
|[International Conference on Multilevel Analysis](https://multilevel.fss.uu.nl/)||
|[Elements of Evolutionary Anthropology](https://elevanth.org/blog/)|McElreath blog, "Occasional text on evolutionary anthropology, statistical inference, and the intersection of the two."|













