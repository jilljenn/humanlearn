We host a physical full-day workshop colocated with the [LAK 2024](https://www.solaresearch.org/events/lak/lak24/) conference to discuss specific algorithmic and machine learning issues for optimizing human learning.

<div id="logos" class="responsive">
    <a href="https://www.kyoto-u.ac.jp/en/"><img src="static/img/kyoto.png" /></a>
    <a href="https://team.inria.fr/soda/"><img src="static/img/inria.png" /></a>
    <a href="http://www.centralesupelec.fr/en"><img src="static/img/cs.png" /></a>
</div>

# Motivation

**What should we learn next?** In this current era where digital access to knowledge is cheap and user attention is expensive, a number of online applications have been developed for learning. These platforms collect a massive amount of data over various profiles, that can be used to improve learning experience: intelligent tutoring systems can infer what activities worked for different types of students in the past, and apply this knowledge to instruct new students. In order to learn effectively and efficiently, the experience should be adaptive: the sequence of activities should be tailored to the abilities and needs of each learner, in order to keep them stimulated and avoid boredom, confusion and dropout. In the context of reinforcement learning, we want to learn a policy to administer exercises or resources to individual students.

Educational research communities have proposed models that predict mistakes and dropout, in order to detect students that need further instruction. Such models are usually calibrated on data collected in an offline scenario, and may not generalize well to new students. There is now a need to design online systems that continuously learn as data flows, and self-assess their strategies when interacting with new learners. These models have been already deployed in online commercial applications (ex. streaming, advertising, social networks) for optimizing interaction, click-through-rate, or profit. Can we use similar methods to enhance the performance of teaching in order to promote lifetime success? When optimizing human learning, which metrics should be optimized? Learner progress? Learner retention? User addiction? The diversity or coverage of the proposed activities? What are the issues inherent to adapting the learning process in online settings, in terms of privacy, fairness (disparate impact, inadvertent discrimination), and robustness to adversaries trying to game the system?

Student modeling for optimizing human learning is a rich and complex task that gathers methods from machine learning, cognitive science, educational data mining and psychometrics. This workshop welcomes researchers and practitioners in the following topics (this list is not exhaustive):

- abstract representations of learning
- additive/conjunctive factor models
- adversarial learning
- causal models
- cognitive diagnostic models
- deep generative models such as deep knowledge tracing
- item response theory
- models of learning and forgetting (spaced repetition)
- multi-armed bandits
- multi-task learning
- reinforcement learning

# Program

The conference starts on Tuesday March 19 at **9 AM JST**.

[Keynote](https://drive.google.com/file/d/1dCWJULUOYIMv57pnLXxqn5faKlQgHf45/view?usp=sharing)
:   
[**Towards building a simulated agent** [slides]](https://drive.google.com/file/d/1dCWJULUOYIMv57pnLXxqn5faKlQgHf45/view?usp=sharing)  
[Aritra Ghosh](https://arghosh.github.io/) (Meta), [Andrew Lan](https://people.umass.edu/~andrewlan/) (University of Massachussetts Amherst)

Tutorial 1
:   
[**Adaptive Learning Systems and their Overall Effectiveness in Learning Gains** [slides]](https://drive.google.com/file/d/1tUTqfaiR9D9UHtAtn3SW-w3UBpEigW0f/view?usp=sharing)  
[Yizhu Gao](https://people.coe.uga.edu/yizhu-gao/) (University of Georgia)

Tutorial 2
:   
[**Challenges in Educational Recommender Systems** [slides]](https://drive.google.com/file/d/1u4qK0l-S3StxsYmztzT1m4n8JHEYJ9YS/view?usp=sharing)  
[Yong Zheng](https://itm.iit.edu/zheng/index.html) (Illinois Institute of Technology)

Tutorial 3
:   
[**Contextual Bandits and Reinforcement Learning with Human Feedback** [slides]](/static/slides/wasl2024.pdf)  
[Jill-Jênn Vie](https://jjv.ie) (Inria, France)

# Registration

The Optimizing Human Learning workshop will be held in Kyoto.

[**Register now**](https://www.solaresearch.org/events/lak/lak24/registration/)

# Important Dates

Dec 16 (extended), 2023 – [AoE](https://www.timeanddate.com/time/zones/aoe)

:   Deadline for paper submissions - CFP on [EasyChair](https://easychair.org/conferences/?conf=wasl2024)

January 13, 2024 or before

:   Notification of acceptance

Feb 5, 2024

:   Early bird registration

March 19, 2024, 9 AM JST

:   Optimizing Human Learning Workshop

# Call for Papers

Short papers

:    Between 2 and 3 pages

Full papers

:    Between 4 and 6 pages

Submissions can be made through [EasyChair](https://easychair.org/conferences/?conf=wasl2024) and should follow the [LNCS format](http://www.springer.com/fr/computer-science/lncs/conference-proceedings-guidelines).

# Workshop Topics

- How to put the student in optimal conditions to learn? e.g. incentives, companion agents, etc.
- When optimizing human learning, which metrics should be optimized?
    - The progress of the learner?
    - The diversity or coverage of the proposed activities?
    - Fast recovery of what the student does not know?
    - Can a learning platform be solely based on addiction, maximizing interaction?
- What kinds of activities give enough choice and control to the learner to benefit their learning (adaptability vs. adaptivity)?
- Do the strategies differ when we are teaching to a group of students? Do we want to enhance social interaction between learners?
- What feedback should be shown to the learner in order to allow reflective learning? e.g. visualization, learning map, score, etc. (Should a system provide a fake feedback in order to encourage the student more?)
- What student parameters are relevant? e.g. personality traits, mood, context (is the learner in class or at home?), etc.
- What explicit and implicit feedbacks does the learner provide during the interaction?
- What models of learning are relevant? E.g. cognitive models, modeling forgetting in spaced repetition.
- What specific challenges from the ML point of view are we facing with these data?
- Do we have enough datasets? What kinds of datasets are missing? In particular, aren’t the current datasets too focused on STEM disciplines?
- How to guarantee fairness/trustworthiness of AI systems that learn from interaction with students? This is especially critical for systems that learn online.

# Datasets

- Duolingo
    - [Shared Task on Second Language Acquisition Modeling (SLAM)](http://sharedtask.duolingo.com)
    - [Half-Life Regression](https://github.com/duolingo/halflife-regression)
- Mnemosyne
    - [3GB Dataset](https://archive.org/details/20140127MnemosynelogsAll.db)
    - [Leitner Queue Network](https://github.com/rddy/leitnerq)
- ASSISTments
    - [2009–2015](https://sites.google.com/site/assistmentsdata/home/assistment-2009-2010-data)
    - [2017 Longitudinal Data Mining Competition](https://sites.google.com/view/assistmentsdatamining)
- [PLSC DataShop](http://pslcdatashop.web.cmu.edu)
    - [KDD Cup 2010](https://pslcdatashop.web.cmu.edu/KDDCup/downloads.jsp)
- [Adaptive Learning group at Masaryk University](https://www.fi.muni.cz/adaptivelearning/?a=data)
	- [RoboMission](https://github.com/adaptive-learning/adaptive-learning-research/tree/master/data/robomission-2019-12)
- [EdNet dataset](https://github.com/riiid/ednet)

# Organizers

To contact us, join our Google group: [optimizing-human-learning](https://groups.google.com/forum/#!forum/optimizing-human-learning)

## Workshop Chairs

[Yizhu Gao](https://people.coe.uga.edu/yizhu-gao/), University of Georgia  
Samuel Girard, Inria, France  
[Hisashi Kashima](https://hkashima.github.io/index_e.html), Kyoto University, Japan  
[Fabrice Popineau](http://fabrice.popineau.net/), CentraleSupélec & LRI, France  
[Jill-Jênn Vie](https://jjv.ie), Inria, France  
[Yong Zheng](https://itm.iit.edu/zheng/index.html), Illinois Institute of Technology, USA

## Program Committee

[Hisashi Kashima](https://hkashima.github.io/index_e.html), Kyoto University, Japan  
[Fabrice Popineau](http://fabrice.popineau.net/), CentraleSupélec & LRI, France  
[Jill-Jênn Vie](https://jjv.ie), Inria, France  
[Jacob Whitehill](https://www.wpi.edu/people/faculty/jrwhitehill), Worcester Polytechnic Institute, USA
