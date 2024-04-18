# social-ai
This is a repository of papers, resources, courses, and dissertations related to the multimodal and multidisciplinary goal of advancing socially-intelligent AI (Social-AI) agents. 

By [Leena Mathur](https://l-mathur.github.io), [Paul Liang](https://www.cs.cmu.edu/~pliang/), and [Louis-Philippe Morency](https://lti.cmu.edu/people/faculty/morency-louis-philippe.html) from the [MultiComp Lab](http://multicomp.cs.cmu.edu), [Language Technologies Institute](https://www.lti.cs.cmu.edu), and [Machine Learning Department](https://www.ml.cmu.edu) at CMU's [School of Computer Science](https://www.cs.cmu.edu).  

&#x1f4e3; If there are any topics, papers, datasets, courses, or dissertations you would like added, please feel free to make a pull request or email lmathur@andrew.cmu.edu. We welcome all contributions! 

# Social-AI Position Paper

The position paper [Advancing Social Intelligence in AI Agents: Technical Challenges and Open Questions](link) discusses core technical challenges, opportunities, and open questions towards building socially-intelligent AI (Social-AI) agents. Our paper is anchored in social intelligence concepts and progress in Social-AI across 6 computing communities: natural language processing, machine learning, computer vision, robotics, human-machine interaction (including human-computer interaction and human-robot interaction), and speech. This repository of resources will be continually updated with additional community resources. 


<p align="center">
  <img src="challenges.png" style="width: 60%;">
</p>


# Table of Contents

[Social Intelligence Foundations](#social-intelligence-foundations)

[Social-AI Research](#social-ai-research)

[Ethics and Safety](#ethics-and-safety)

[Benchmarks](#benchmarks)

[CMU Artificial Social Intelligence Course](#cmu-artificial-social-intelligence-course)

[Additional Courses Relevant to Social-AI](#additional-courses-relevant-to-social-ai)

[Workshops Relevant to Social-AI](#workshops-relevant-to-social-ai)

[Dissertations Relevant to Social-AI](#dissertations-relevant-to-social-ai)




# Social Intelligence Foundations

## What is a social entity? 

[The Construction of Social Reality](https://books.google.co.in/books?hl=en&lr=&id=zrLQwJCcoOsC&oi=fnd&pg=PR9&dq=+%22searle%22%22The+construction+of+social+reality%22&ots=1tfnSn_xwS&sig=EtU76LM_WRJ-23yLPwiC_70l5O4#v=onepage&q=%22searle%22%22The%20construction%20of%20social%20reality%22&f=false), 1995

[Social Ontology and the Philosophy of Society](https://www.degruyter.com/document/doi/10.1515/auk-1998-0201/html), Analyse & Kritik, 1998

[Making the Social World: The Structure of Human Civilization](https://books.google.co.in/books?hl=en&lr=&id=kz6R0eDZ5OEC&oi=fnd&pg=PT6&dq=Making+the+social+world:+The+struc-+ture+of+human+civilization&ots=AN5AhPIMQv&sig=ldXl1Ob-jw-j5te9o7jCxWMim9U#v=onepage&q=Making%20the%20social%20world%3A%20The%20struc-%20ture%20of%20human%20civilization&f=false), 2010

[Three Kinds of Social Kinds](https://onlinelibrary.wiley.com/doi/abs/10.1111/phpr.12020#:~:text=In%20this%20paper%2C%20I%20argue,attitudes%20that%20human%20beings%20have), Philosophy and Phenomenological Research, 2013

[Human Social Reality and Language](https://oaj.fupress.net/index.php/pam/article/view/7068), Phenomenology and Mind, 2012


## Social Intelligence Definitions and Competencies

### Defining and Measuring Social Intelligence

[Moral Principles in Education](https://books.google.com/books?hl=en&lr=&id=8V0WAAAAIAAJ&oi=fnd&pg=PR5&dq=Moral+principles+in+education&ots=h5BrGTREFx&sig=RQVZkn6IcfEAbMnojtFuZyA1VnE#v=onepage&q=Moral%20principles%20in%20education&f=false), 1909

[Moral Instruction through Social Intelligence](https://www.journals.uchicago.edu/doi/pdf/10.1086/211944), American Journal of Sociology, 1911

[Intelligence and Its Uses](https://harpers.org/archive/1920/01/intelligence-and-its-uses/), Harper's Magazine, 1920

[Measures of Social Intelligence](https://www.journals.uchicago.edu/doi/abs/10.1086/215342), American Journal of Sociology, 1930

[An Evaluation of the Attempts to Measure Social Intelligence](https://psycnet.apa.org/record/1937-03825-001), Psychological Bulletin, 1937

[Social Intelligence – A Review and Critical Discussion of Measurement Concepts](https://books.google.com/books?hl=en&lr=&id=iJibEAAAQBAJ&oi=fnd&pg=PA203&dq=Social+intelligence–a+review+and+critical+discussion+of+mea-+surement+concepts&ots=5Z-v4dX9md&sig=rmwUlZAY5P0vUCUhgHZ87doi3yA#v=onepage&q=Social%20intelligence–a%20review%20and%20critical%20discussion%20of%20mea-%20surement%20concepts&f=false), Emotional Intelligence: An International Handbook, 2005

[Theory and Measurement of Social Intelligence as a Cognitive Performance Construct](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=a34ce5d809e7858130961f64a957060a80423749), Susanne Weis PhD Dissertation, 2008

[New Findings about Social Intelligence](https://econtent.hogrefe.com/doi/abs/10.1027/1614-0001/a000106?journalCode=jid), Journal of Individual Differences, 2013

[The Social Shapes Test: A New Measure of Social Intelligence, Mentalizing, and Theory of Mind](https://www.sciencedirect.com/science/article/pii/S0191886919300479?casa_token=yVvFbldVo3cAAAAA:HNaSLHGrGkLjg-sfw4hH5XnH_Jyp6wlNs20qn23xcZrsHpJj7JdVlLXnI3mZrawP08jyHlc_4kM), Personality and Individual Differences, 2019

### Social Intelligence Competencies

**Social Perception, Knowledge, Memory, Reasoning, Creativity (Theory-of-Mind), Interaction**

We consider these 6 competencies to be core competencies of social intelligence, per perspectuves such as [Weis and Süß 2005](https://books.google.com/books?hl=en&lr=&id=iJibEAAAQBAJ&oi=fnd&pg=PA203&dq=Social+intelligence–a+review+and+critical+discussion+of+mea-+surement+concepts&ots=5Z-v4dX9md&sig=rmwUlZAY5P0vUCUhgHZ87doi3yA#v=onepage&q=Social%20intelligence–a%20review%20and%20critical%20discussion%20of%20mea-%20surement%20concepts&f=false), [Weis 2008](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=a34ce5d809e7858130961f64a957060a80423749), [Conzelmann, Weis, and Süß 2013](https://econtent.hogrefe.com/doi/abs/10.1027/1614-0001/a000106?journalCode=jid), and additional readings on social interaction. The study and identification of social intelligence competencies is an ongoing research area across cognitive science, psychology, and neuroscience. We will continually update this repository with new findings, and please feel free to add any additional resources below.

[Thinking about Ourselves and Others: Self-monitoring and Social Knowledge](https://psycnet.apa.org/record/1981-23734-001), Journal of Personality and Social Psychology, 1980

[A Theory of Social Interaction](https://books.google.com/books?hl=en&lr=&id=a1H91KqOs-kC&oi=fnd&pg=PA3&dq=%7BA+theory+of+social+interaction&ots=Ej0Ojp8SOC&sig=1HFQqg4gy4mEG-FsDmlTV0E6en8#v=onepage&q=%7BA%20theory%20of%20social%20interaction&f=false), 1988

[Social Perception](https://psycnet.apa.org/record/1991-97263-000), 1990

[Social Memory in Everyday Life: Recall of Self-events and Other-events](https://psycnet.apa.org/record/1991-26495-001), Journal of Personality and Social Psychology, 1991

[A Proposed Model for the Acquisition of Social Knowledge and Social Competence](https://onlinelibrary.wiley.com/doi/abs/10.1002/1520-6807(199304)30:2%3C143::AID-PITS2310300207%3E3.0.CO;2-P), Psychology in the Schools, 1993

[Self and Social Functions: Individual Autobiographical Memory and Collective Narrative](https://www.tandfonline.com/doi/abs/10.1080/741938203), Memory, 2003

[Interaction](https://books.google.com/books?hl=en&lr=&id=bjkTxML-wpEC&oi=fnd&pg=PA3&dq=Handbook+of+Symbolic+Interactionism+%222003%22+%22mccall%22&ots=01b92DQaDg&sig=EbDP7BMlpEsGElM8D1BuLpKdPnM#v=onepage&q=Handbook%20of%20Symbolic%20Interactionism%20%222003%22%20%22mccall%22&f=false), Chapter 13 within Handbook of Symbolic Interactionism, 2003

[Theory of Mind Development and Social Understanding](https://www.tandfonline.com/doi/abs/10.1080/02699939508409006), Cognition and Emotion, 2008 

[Can Social Interaction Constitute Social Cognition?](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(10)00146-4), Trends in Cognitive Science, 2010

[Bridging the Gap between Social Animal and Unsocial Machine: A Survey of Social Signal Processing](https://ieeexplore.ieee.org/abstract/document/5989788), IEEE Transactions on Affective Computing, 2011

[Nonverbal Signals](https://books.google.com/books?hl=en&lr=&id=ZNF1AwAAQBAJ&oi=fnd&pg=PR3-IA110&dq=Handbook+of+Interpersonal+Communication+2011+%22burgoon%22&ots=rpca5ZmnuG&sig=gcjBhZrQNWc78BhE7ACcqwq5l24#v=onepage&q=Handbook%20of%20Interpersonal%20Communication%202011%20%22burgoon%22&f=false), Handbook of Interpersonal Communication, 2011

[Social Signals: A Framework in Terms of Goals and Beliefs](https://link.springer.com/article/10.1007/s10339-012-0512-6), Cognitive Processing, 2012

[Constraint Satisfaction Processes in Social Reasoning](https://www.taylorfrancis.com/chapters/edit/10.4324/9781315799360-43/constraint-satisfaction-processes-social-reasoning-stephen-read-chadwick-snow-dan-simon), Proceedings of the 25th Annual Cognitive Science Society, 2003

[A Social Perspective on Theory of Mind](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781118963418.childpsy314), Handbook of Child Psychology and Developmental Science, 2015

[Data-driven Approaches in the Investigation of Social Perception](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2015.0367), Philosophical Transactions of the Royal Society B: Biological Sciences, 2016

[The Handbook of Multimodal-Multisensor Interfaces: Signal Processing, Architectures, and Detection of Emotion and Cognition-Volume 2](https://dl.acm.org/doi/abs/10.1145/3107990), ACM, 2018

[Reasoning Strategies Explain Individual Differences in Social Reasoning](https://psycnet.apa.org/record/2020-66295-001), Journal of Experimental Psychology: General, 2021


## Dimensions of Social Context



# Social-AI Research

## Rule-Based Approaches

[Modeling Social Action for AI Agents](https://www.sciencedirect.com/science/article/pii/S0004370298000563), Artificial Intelligence, 1998


## Nuanced Signals 
[Learning the Communication of Intent Prior to Physical Collaboration](https://ieeexplore.ieee.org/abstract/document/6343875), IEEE RO-MAN, 2012

## Multiple Perspectives 
[Shared Reality: Experiencing Commonality with Others' Inner States about the World](https://journals.sagepub.com/doi/full/10.1111/j.1745-6924.2009.01161.x), Perspectives on Psychological Science, 2009



## Agency and Adaptation 
[Active Preference-based Learning of Reward Functions](https://escholarship.org/content/qt88k894w7/qt88k894w7_noSplash_2563d21faeca7f97a4214d2a7323a5f7.pdf), RSS, 2017

[Affective Behavior Learning for Social Robot Haru with Implicit Evaluative Feedback](https://ieeexplore.ieee.org/abstract/document/9981752?casa_token=LB2Oz3LRw4gAAAAA:sGoGS-6K-4lg0ZLzjyv6NatByqxgOv5CBgFW9xbfarw1SRPJzJQl3x3wIgyslQ3ePw5hvgYpdg), IROS, 2022




## Example Applications (non-exhaustive)

[Human--AI collaboration Enables More Empathic Conversations in Text-based Peer-to-peer Mental Health Support](https://www.nature.com/articles/s42256-022-00593-2), Nature Machine Intelligence 2023

[Wellbeat: A Framework for Tracking Daily Well-being Using Smartwatches](https://ieeexplore.ieee.org/abstract/document/9171435?casa_token=jxEpPwG6dPEAAAAA:azmTqHO1g6CIVE08KOQ-vfap35mZ7oSif-7A7ssWjdy-ockdlKSiVvBulKdOjwPDw3ONma13yA), IEEE Internet Computing, 2020

[Social Robots in Hospitals: A Systematic Review](https://www.mdpi.com/2076-3417/11/13/5976), Applied Sciences, 2021

[Socially Assistive Robotics for Post-stroke Rehabilitation](https://link.springer.com/article/10.1186/1743-0003-4-5), Journal of NeuroEngineering and Rehabilitation, 2007

[Social Robot for Rehabilitation: Expert Clinicians and Post-stroke Patients’ Evaluation Following a Long-term Intervention](https://dl.acm.org/doi/abs/10.1145/3319502.3374797?casa_token=XyIjqL77s-oAAAAA:51cKWfPWpH_Sja5sR36GgvqbTWgwENmhBdurnj7qpPP7qW2B52IQfiT0MU6cLYPTYFcRLBYtNx4how), HRI, 2020

[Social and Emotional Skills Training with Embodied Moxie](https://arxiv.org/abs/2004.12962), arXiv, 2020

[Robots for Use in Autism Research](https://www.annualreviews.org/content/journals/10.1146/annurev-bioeng-071811-150036), Annual Review of Biomedical Engineering, 2012

[A Robotic Positive Psychology Coach to Improve College Students’ Wellbeing](https://ieeexplore.ieee.org/abstract/document/9223588?casa_token=L9NgMq2nwIoAAAAA:jBy0veFKVbdCcH6iAvc5kWNq5AHHpF5UhpRVgG5ae7Zub-SWwzDm0_wQJczkrbbP3f23LYxD5w), IEEE RO-MAN, 2020

[The Social Impact of a Robot Co-worker in Industrial Setting](https://dl.acm.org/doi/10.1145/2702123.2702181), CHI, 2015


# Core Technical Challenges in Social-AI

## Ambiguity in Constructs

## Nuanced Signals 

## Multiple Perspectives 

## Agency and Adaptation

# Ethics and Safety 

[Averting robot eyes](https://heinonline.org/HOL/Page?handle=hein.journals/mllr76&div=39&g_sent=1&casa_token=&collection=journals), Maryland Law Review, 2016

[Federated Continual Learning for Socially Aware Robotics](https://arxiv.org/abs/2201.05527)

# Benchmarks

| Dataset | Domain | Paper | Data|
|:-----------|:----------------------------|:------------:|:------------:|
|`Social-IQ`| multimodal video qa | [CVPR 2019 paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zadeh_Social-IQ_A_Question_Answering_Benchmark_for_Artificial_Social_Intelligence_CVPR_2019_paper.pdf) | [data + code](https://github.com/A2Zadeh/Social-IQ)
|`Social-IQ 2.0`| multimodal video qa | [ICCV 2023 Challenge](https://cmu-multicomp-lab.github.io/social-iq-2.0/) | [data + code](https://github.com/abwilf/Social-IQ-2.0-Challenge)
|`Social-IQa`| text qa | [EMNLP 2019 paper](https://arxiv.org/pdf/1904.09728.pdf) | [data + code](https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/social_iqa/README.md)
|`CMU-MOSEI`| multimodal sentiment and emotion intensity | [ACL 2018 paper](https://aclanthology.org/P18-1208.pdf) | [data + code](https://github.com/A2Zadeh/CMU-MultimodalSDK)
| `IEMOCAP` | multimodal emotional dyadic motion capture | [LREC 2008 paper](https://link.springer.com/content/pdf/10.1007/s10579-008-9076-6.pdf) | [data](https://sail.usc.edu/software/databases/) 




# CMU Artificial Social Intelligence Course
CMU also offers a new course [11:866: Artificial Social Intelligence](https://cmu-multicomp-lab.github.io/asi-course/spring2023/), most recently taught in Spring 2023. There are publicly-available [summaries](https://cmu-multicomp-lab.github.io/asi-course/spring2023/schedule/) from class discussions and reading lists for anyone interested in Social-AI topics. 

# Additional Courses Relevant to Social-AI



# Workshops Relevant to Social-AI


# Dissertations Relevant to Social-AI

[Communication Beyond Words: Grounding Visual Body Motion with Language](https://lti.cs.cmu.edu/sites/default/files/ahuja%2C%20chaitanya%20-%20Thesis.pdf), 2022, [Chaitanya Ahuja](https://chahuja.com)

[Towards Human-Centered Optimality Criteria](https://dspace.mit.edu/bitstream/handle/1721.1/140992/ghandeharioun-asma_gh-phd-MAS-2021-thesis.pdf?sequence=1&isAllowed=y), 2021, Asma Ghandeharioun

[Social and Affective Machine Learning](https://www.media.mit.edu/publications/social-and-affective-machine-learning/), 2019, [Natasha Jaques](https://natashajaques.ai) 

[A Bayesian Theory of Mind Approach to Nonverbal Communication for Human-Robot Interactions](https://www.media.mit.edu/publications/jinjoolee-phd-2017/), 2017, Jin Joo Lee

[Measuring college students' sleep, stress, mental health and wellbeing with wearable sensors and mobile phones](https://dspace.mit.edu/handle/1721.1/106066), 2016, Akane Sano




