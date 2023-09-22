---
layout: inner
title: "Week 01"
---


## Intro

This week will be mostly about planning and inspirations. We will go together through the schedule, evaluation criteria, talk about the basis of ML and have a look at different examples of ML projects. We'll also have a look at some of the tools we are going to use during the class.


## Schedule

|Time         |Desc                                            |
|---          |---                                             |
|1 h          | [Intro](#intro)                                |
|10 mins      | Break                                          |
|30 mins      | [Tools](#tools)                                |
|15 mins      | [Preparation work](#preparation-work)          |
|5 mins       | [Exit ticket](#exit-ticket)                    |


## Intro

* Me / Class
    * [:tv: intro](https://digitalideation.github.io/digcre_h2301/slides/intro_part01.html)
    * Class
    * Philosophy
        * [Peer Learning](https://42.fr/en/what-is-42/the-42-method/)
        * [Three before me](https://practices.learningaccelerator.org/strategies/3-before-me)
        * Different levels -> Help others, produce content for the class.
    * [History](#going-further)
    * [Tools](#tools)
    * Relax VS Strict / Expectations
    * Produce content that can be shared
* You
    * Questions / Expectations
        * Write down your questions / expectations
        * Research driven by questions
    * Getting help
        * How to ask for help
        * Pair programming
        * [Code of conduct](https://digitalideation.github.io/digcre_h2301#academic-integrity) (OSS, etc...)
    * Giving feedback:
        * Exit ticket 3 Questions at the end of each class
        * Critique and Feedback: interactive


## Preparation work

* Watch the [NN - Intro videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) from 3blue1brown.
* Complete the notebooks in _"Working with Notebooks in Colab"_ (in the section _"More Resources"_) from the [intro to colaboratory notebook](https://colab.research.google.com/notebooks/intro.ipynb)
* Start [learning python the hard way](https://learnpythonthehardway.org/python3/), the full book is available in the [resource folder :books:](https://digitalideation.github.io/digcre_h2301/resources/LearnPython3theHardWay.pdf)
* Read more about [the history of Machine Learning](https://cloud.withgoogle.com/build/data-analytics/explore-history-machine-learning/)
* Get [inspired](https://mlart.co/)!

The goal this week is to:

1) Start understanding how a NN work  
2) get familiar with Colab and Python 


## Going further

* [History - Longer history of Machine Learning](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/)
* [Math - Essence of Linear Algebra](https://www.3blue1brown.com/essence-of-linear-algebra)
* [Math - Linear Algebra CheatSheet](https://towardsdatascience.com/linear-algebra-cheat-sheet-for-deep-learning-cd67aba4526c)
* [NN - Intro](https://ujjwalkarn.me/2016/08/09/quick-intro-neural-networks/)
* [NN - Visualisation](http://scs.ryerson.ca/~aharley/vis/fc/)
* [ML - Getting started](https://www.youtube.com/watch?v=I74ymkoNTnw)
* [NN - From scratch (Python)](https://iamtrask.github.io/2015/07/12/basic-python-network/)
* [NN - From scratch (Python)](https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6)
* [NN - From scratch (Processing)](https://medium.com/typeme/lets-code-a-neural-network-from-scratch-part-1-24f0a30d7d62)


## Tools

### Code editor

If you don’t have a code editor, please install one. Some suggestions (in no particular order)
- [Sublime Text](https://www.sublimetext.com)
- [Visual Studio](https://code.visualstudio.com)
- [Atom](https://atom.io) 

### Web server

We will need a simple web server to run the experiments locally. Some suggestions 
- If you have node.js/npm installed you can use _live-server_: `npm install -g live-server`
- [Other recommended options](https://github.com/digitalideation/hslu-ml-workshop#web-server)

### Colab

[__Colaboratory__](https://colab.research.google.com/), or "Colab" for short, allows you to write and execute Python in your browser, with 
- Zero configuration required
- Free access to GPUs
- Easy sharing



### Conda

[__Conda__](https://conda.io) is an open source package management system and environment management system that runs on Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their dependencies. Conda easily creates, saves, loads and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

### Pytorch

[__Pytorch__](https://pytorch.org) PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab (FAIR). It is free and open-source software released under the Modified BSD license.
- [Tutorials](https://pytorch.org/tutorials/)
- [Pytorch Beginners](https://github.com/L1aoXingyu/pytorch-beginner)

### Tensorflow.js

A **JavaScript** library with a more advanced set of options, also for the web.
- [Getting Started](https://js.tensorflow.org/#getting-started)
- [Tutorials](https://js.tensorflow.org/tutorials/)
- [Keynote](https://www.youtube.com/watch?v=YB-kfeNIPCE)
- [Examples](https://github.com/tensorflow/tfjs-examples)
- [Video Tutorials](https://github.com/tensorflow/tfjs/blob/master/GALLERY.md#video-tutorials)

### Keras

Keras is a high-level neural networks API, written in **Python** and capable of running on top of **TensorFlow, CNTK, or Theano**. It was developed with a focus on enabling fast experimentation
- [Getting Started](https://keras.io/#getting-started-30-seconds-to-keras)
- [Tutorials](https://blog.keras.io/index.html)

### ML5.js

ML5.js is a simple **JavaScript** ML library for the web based on tensorflow.js. 
- [Getting started](https://ml5js.org/docs/getting-started)
- [Experiments](https://ml5js.org/en/experiments)
- [Git source](https://github.com/ml5js)

### P5.js

[__p5.js__ ](https://p5js.org/) is a high level creative programming framework with an [intuitive API](https://p5js.org/reference/). If some of you have used Processing before you should be confortable using p5.js. To get familiar with p5 you can go through this list of tutorials / guides:
- [P5 Learn](https://p5js.org/learn/)
- [P5 Wiki](https://github.com/processing/p5.js/wiki/)
- [Creative Coding](https://creative-coding.decontextualize.com/)
- [Shiffman's Foundation of programming in js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
- [P5js reference](https://p5js.org/reference/)

### Magenta.js

Magenta.js is a collection of **TypeScript** libraries for doing inference with pre-trained Magenta models. All libraries are published as npm packages.
- [Demos](https://magenta.tensorflow.org/demos)
- [Blog](https://magenta.tensorflow.org)
