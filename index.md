---
title: Home
permalink: /index.html
weight: -1
---



## Bayesian optimization for science and engineering


Bayesian optimization (BO) is a recent subfield of machine learning comprising a collection of methodologies for the efficient optimization of expensive black-box functions.  BO techniques work by fitting a model to black-box function data and then using the model's predictions to decide where to collect data next, so that the optimization problem can be solved using only a small number of function evaluations. The resulting methods are characterized by their high sample-efficiency when compared to alternative black-box optimization algorithms, enabling the solution of new challenging problems. For example, in recent years, BO has become a popular tool in the machine learning community for the excellent performance attained in the problem of hyperparameter tuning, with important results both in academia and industry. This success has made BO a crucial player in the current trend of “automatic machine learning”. 

As new BO methods have been developed, the area of applicability has been continuously expanding. While the problem of hyperparameter tuning permeates all disciplines, the field has moved towards more specific problems in science and engineering requiring of new advanced methodology. Today, Bayesian optimization is the most promising approach for accelerating and automating science and engineering. Therefore, we have chosen this year's theme for the workshop to be "Bayesian optimization for science and engineering".

We enumerate below a few of the recent directions in which BO methodology is being pushed forward to address specific problems in science and engineering:

- Beyond Gaussian processes. While GPs are the default choice in BO, specific problems in science and engineering require to collect larger amounts of complex data. In these settings, it is necessary to use alternative models to capture complex patterns with higher accuracy. For example, Bayesian neural networks or deep Gaussian processes. How can we do efficient BO with these type of models?

- Optimization in structured domains. Many problems in science and engineering require to perform optimization in complex spaces which are different from the typical box-constrained subset of the real coordinate space. For example, how can we efficiently optimize over graphs, discrete sequences, trees, computer programmes, etc.?

- Safe optimization. Critical applications in science and engineering may include configurations in the search space that may be unsafe or harmful and may lead to system failure. How can we perform efficient BO while avoiding these unsafe settings?

- Incorporating domain specific knowledge. In many optimization settings there is available a lot of domain specific information that can be used to build bespoke BO methods with significantly better performance than its off-the-shelf counterparts. How can we easily encode and transfer available knowledge into BO methods in an easy and fast manner?

- Optimization with structured output response. In specific cases, each black-box may produce additional output values besides an estimate of the objective function. For example, when tuning a simulator, besides the final output value, we may also obtain structured data related to the execution trace of the simulator. How can design BO methods that automatically exploit this extra structured output?

- Scalability and fast evaluations. Recent problems require to collect a massive amount of data in parallel and at cost that is usually lower than in typical BO problems. How can we design efficient BO methods that collect very large batches of data in parallel? How can we automatically adjust the cost of BO methods so that they are efficient even when the data collection is not highly expensive?

The target audience for this workshop consists of both industrial and academic practitioners of Bayesian optimization as well as researchers working on theoretical and practical advances in model based optimization across different engineering areas. We expect that this pairing of theoretical and applied knowledge will lead to an interesting exchange of ideas and stimulate an open discussion about the long term goals and challenges of the Bayesian optimization community.

The main goal of the workshop is to serve as a forum of discussion and to encourage collaboration between the diverse set of scientist that develop and use Bayesian optimization and related techniques. Researchers and practitioners in Academia are welcome, as well people form the wider optimization, engineering and probabilistic modeling communities.

Topics:
* Bayesian optimization
* Sequential experimental design and bandits
* Applications, in industry or academia, and other scientific disciplines
* Related areas, e.g., active learning, reinforcement learning


## Invited speakers and panelists

- [Peter Frazier](https://people.orie.cornell.edu/pfrazier/) (Cornell/Uber)
- [Yutian Chen](http://yutianchen.com) (Deepmind)
- [Romy Lorenz](http://www.romylorenz.com) (Imperial College London)
- [Andreas Krause](https://las.inf.ethz.ch/krausea) (ETH Zurich)
- [David Ginsbourger](http://www.ginsbourger.ch/) (Idiap Research Institute, Switzerland)
- [Stefanie Jegelka](http://people.csail.mit.edu/stefje/) (MIT)

Panel moderator:
- [Philipp Hennig](https://pn.is.tuebingen.mpg.de/person/phennig) (Max Plank Institute for Intelligent Systems) 


## Organizers

- [José Miguel Hernández-Lobato](https://jmhl.org) (University of Cambridge)
- [Javier Gonzalez](http://javiergonzalezh.github.io/) (Amazon)
- [Ruben Martinez-Cantin](http://webdiis.unizar.es/~rmcantin/) (SigOpt)


## Important dates

- Submission deadline: 3 November 2017 (11:59 pm Pacific).
- Notification: 17 November 2017.
- Camera ready: 1 December 2017.
- Workshop: 9 December 2017.
 
