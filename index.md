We host a fully virtual half-day workshop colocated with the [AIED 2020](https://aied2020.nees.com.br/#/) conference to discuss specific algorithmic and machine learning issues for optimizing human learning.

<div id="logos" class="responsive">
    <a href="https://www.kyoto-u.ac.jp/en/"><img src="/static/img/kyoto.png" /></a>
    <a href="https://team.inria.fr/sequel/"><img src="/static/img/inria.jpg" /></a>
    <a href="http://www.centralesupelec.fr/en"><img src="/static/img/cs.png" /></a>
</div>

# Motivation

**What should we learn next?** In this current era where digital access to knowledge is cheap and user attention is expensive, a number of online applications have been developed for learning. These platforms collect a massive amount of data over various profiles, that can be used to improve learning experience: intelligent tutoring systems can infer what activities worked for different types of students in the past, and apply this knowledge to instruct new students. In order to learn effectively and efficiently, the experience should be adaptive: the sequence of activities should be tailored to the abilities and needs of each learner, in order to keep them stimulated and avoid boredom, confusion and dropout. In the context of reinforcement learning, we want to learn a policy to administer exercises or resources to individual students.

Educational research communities have proposed models that predict mistakes and dropout, in order to detect students that need further instruction. Such models are usually calibrated on data collected in an offline scenario, and may not generalize well to new students. There is now a need to design online systems that continuously learn as data flows, and self-assess their strategies when interacting with new learners. These models have been already deployed in online commercial applications (ex. streaming, advertising, social networks) for optimizing interaction, click-through-rate, or profit. Can we use similar methods to enhance the performance of teaching in order to promote lifetime success? When optimizing human learning, which metrics should be optimized? Learner progress? Learner retention? User addiction? The diversity or coverage of the proposed activities? What the issues inherent to adapting the learning process in online settings, in terms of privacy, fairness (disparate impact, inadvertent discrimination), and robustness to adversaries trying to game the system?

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

The conference starts on Monday July 6 at **1 PM UTC+1** (see your [local time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Optimizing+Human+Learning+WASL+2020&iso=20200706T13&p1=60&ah=4) here).

Pacific  |  Eastern   |  Morocco  |  Central Europe  |  Japan     |
---------|------------|-----------|------------------|------------|------------------------------------------------------------------------------------------------------------------------------
UTC-7       |  UTC-4        |  UTC+1        |  UTC+2               |  UTC+9         |
5:00 AM  |  8:00 AM   |  1:00 PM  |  2:00 PM         |  9:00 PM   |  Welcome and Introduction
5:30 AM  |  8:30 AM   |  1:30 PM  |  2:30 PM         |  9:30 PM   |  Invited talk: [Teaching Categories to Human Learners with Visual Explanations](https://arxiv.org/pdf/1802.06924.pdf) [[intro video]](https://www.youtube.com/watch?v=bD0v4szglg0) [[slides]](https://jiji.cat/wasl2020/slides-visual-mac-aodha.pdf)<br />[Oisin Mac Aodha](https://homepages.inf.ed.ac.uk/omacaod/), University of Edinburgh
6:00 AM  |  9:00 AM   |  2:00 PM  |  3:00 PM         |  10:00 PM  |  [Non-compensatory Knowledge Tracing with Local Variational Approximation](https://jiji.cat/wasl2020/non-compensatory-kt-final.pdf) [[slides]](https://jiji.cat/wasl2020/slides-non-compensatory-kt-tamano.pdf)<br />Hiroshi Tamano, NEC & The Graduate University for Advanced Studies, Japan
         |            |           |                  |            |  15 min break
6:45 AM  |  9:45 AM   |  2:45 PM  |  3:45 PM         |  10:45 PM  |  Invited talk: [Teaching Multiple Concepts to a Forgetful Learner](https://arxiv.org/pdf/1805.08322.pdf)<br />[Yuxin Chen](https://yuxinchen.org/), University of Chicago [[slides]](https://jiji.cat/wasl2020/slides-forgetful-chen.pdf)
7:15 AM  |  10:15 AM  |  3:15 PM  |  4:15 PM         |  11:15 PM  |  [Adaptive Quiz Generation Using Thompson Sampling](https://jiji.cat/wasl2020/adaptive-quiz-generation.pdf)<br />[Fuhua Lin](http://oscar.athabascau.ca/), Athabasca University, Canada [[slides]](https://jiji.cat/wasl2020/slides-thompson-lin.pdf)
         |            |           |                  |            |  15 min break
8:00 AM  |  11:00 AM  |  4:00 PM  |  5:00 PM         |  12:00 AM  |  Open Discussion
8:30 AM  |  11:30 AM  |  4:30 PM  |  5:30 PM         |  12:30 AM  |  End

# Registration

The Optimizing Human Learning workshop will be held online via BigBlueButton.

[**Register now**](https://attendify.co/aied-2020-hYsvyTU) by selecting **Workshop Four**.

Price is 11.25 GBP for students (tax included), 21.50 GBP for others. It includes a small registration fee.

# Important Dates

June 20 – [AoE](https://www.timeanddate.com/time/zones/aoe)

:   Deadline for paper submissions - [CFP on EasyChair](https://easychair.org/my/conference?conf=wasl2020)

June 27

:   Notification for acceptance

July 5

:   Camera-ready version due

July 6 1pm-5pm (GMT+1) (see your [local time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Optimizing+Human+Learning+WASL+2020&iso=20200706T13&p1=60&ah=4) here)

:   Optimizing Human Learning Workshop

# Call for Papers

Short papers

:    Between 2 and 3 pages

Full papers

:    Between 4 and 6 pages

Submissions will be made through [EasyChair](https://easychair.org/my/conference?conf=wasl2020) and should follow the [LNCS format](http://www.springer.com/fr/computer-science/lncs/conference-proceedings-guidelines).

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

[Jill-Jênn Vie](https://jilljenn.github.io), Inria Lille, France  
[Fabrice Popineau](http://fabrice.popineau.net/), CentraleSupélec & LRI, France  
[Hisashi Kashima](https://hkashima.github.io/index_e.html), Kyoto University, Japan  
Benoît Choffin, CentraleSupélec & LRI, France
