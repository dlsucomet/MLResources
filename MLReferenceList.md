# Machine Learning Reference List
Here's a curated list of references/resources that you can use to teach yourself Machine Learning, annotated with prerequisites and recommendations to help you choose. It's a work in progress and I'll be updating it every so often, so be sure to keep checking!

# Courses
A list of highly recommended short courses and lecture video series.

## Mathematics for Machine Learning
Machine Learning requires some mathematical prerequisites for you to understand what's going on. Generally, experience with statistics, probability, linear algebra, and multivariate calculus are hard requirements. Reading papers and books are super hard without the prerequisites, so we cannot stress how important it is to go through them first! If you're pressed with time, I recommend running through just CMU 10-606. Otherwise, the other things listed would provide really good resources. 

* [(CMU 10-606) Mathematical Background for Machine Learning](https://www.youtube.com/playlist?list=PL7y-1rk2cCsAqRtWoZ95z-GMcecVG5mzA) - Teaches the mathematical foundations needed to explore Machine Learning. Highly recommended for people who want to get into ML. While previous experience on the subjects are helpful, they are not thoroughly required. Recommended for beginners. Take this first if you are unsure on where to go! ***Prerequisite: Previous Statistics/Calculus/Linear Algebra would be helpful. ST-STAT/MODESTA, CCSCAL2, and ADVDISC would be great, but not hard required.***

* [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Probably my favorite Linear Algebra short course online. 3Blue1Brown teaches super well, and does so in so many perspectives. Recommended for beginners. ***Prerequisite: None***

* [Computational Linear Algebra](http://www.fast.ai/2017/07/17/num-lin-alg/) - Here's a more practical Linear Algebra offering from fast.ai, which does a top-down approach teaching you the essence of the subject by showing you the practical side, then going to the theoretical side. Good for people who'd want to do more coding instead of pen-and-paper gauss jordan elimination. Recommended for intermediate students. ***Prerequisite: Supposedly none. Requires you to know Numpy.***

* [Linear Algebra Review](http://www.cs.cmu.edu/~zkolter/course/linalg/index.html) - A refresher of the guts of Linear Algebra. Recommended to take it only if you've taken a Linear Algebra course before as it's not as in depth as other offerings. Recommended for intermediate students. ***Prerequisite: A previous Linear Algebra course. ADVDISC would work. Do note that this is just a refresher.***

* [(CMU 10-705) Intermediate Statistics](http://www.stat.cmu.edu/~larry/=stat705/) - Works nicely as a theoretical take on statistical theory. Coers topics such as bayesian inference and nonparametric testing. This is not a basic statistics course, and is intended for a deep dive in intermediate statistics! Recommended for intermediate students. ***Prerequisite: Statistics and Probability. Some ADVSTAT should work.***

## Introduction to Machine Learning
Main course meal. Assumes the required mathematical background is met, ideally CMU 10-606 has been taken as a precursor. Go take CMU 10-701. 

* [(CMU 10-701) Introduction to Machine Learning](http://www.cs.cmu.edu/~mgormley/courses/10701-f16/schedule.html) - My current go-to recommendation for Introduction to Machine Learning. Solid offering from Carnegie Mellon. Recommended for beginners. ***Prerequisite: Statistics, Calculus, and Linear Algebra. CMU 10-606 is recommended as a precursor. In terms of DLSU subjects, ADVDISC, ADVSTAT, and CCSCAL2 would suffice.***

* [(CS229) Intrduction to Machine Learning](https://www.youtube.com/playlist?list=PLA89DCFA6ADACE599) - Stanford's Introduction to Machine Learning course series. Used to be my go-to, but it's a tad bit outdated (the video quality says it all). Would rather go to CMU 10-701 unless you wanna see Andrew Ng prove theorems on six blackboards at once. Recommended for beginners. ***Prerequisite: Statistics, Calculus, and Linear Algebra. CMU 10-606 is recommended as a precursor. In terms of DLSU subjects, ADVDISC, ADVSTAT, and CCSCAL2 would suffice.***

* [(CS155) Introduction to Machine Learning](https://www.youtube.com/playlist?list=PLuz4CTPOUNi644ypoxzP1frkPYVHdjDJU) - Caltech's Introduction to Machine Learning Course. Stan recommends it, Yisong Yue teaches super good daw. Recommended for beginners. ***Prerequisite: Statistics, Calculus, and Linear Algebra. CMU 10-606 is recommended as a precursor. In terms of DLSU subjects, ADVDISC, ADVSTAT, and CCSCAL2 would suffice.***

## Natural Language Processing
Course series on Natural Language Processing and computational linguistics. I learned from CS224N, and I highly recommend you take it too.

* [(CS224N) Introduction to Natural Language Processing with Deep Learning](https://www.youtube.com/playlist?list=PLqdrfNEc5QnuV9RwUAhoJcoQvu4Q46Lja) - A class from the legendary Christopher Manning of the Stanford NLP Group. My go-to recommendation for NLP-Deep Learning. Recommended for intermediate students. ***Prerequisite: An Intro to ML course, preferably CMU 10-701. A Deep Learning course is also recommened, even if Manning teaches some DL in the course itself.*** 

## Computer Vision
*Coming Soon*

## Data Science
*Coming Soon*

# Books
Some of my highly recommended books. 

## Machine Learning and Deep Learning
* [Deep Learning](https://github.com/dlsucomet/MLResources/blob/master/books/Deep%20Learning.pdf) by Ian Goodfellow, Yoshua Bengio, and Aaron Courville (2016) - Written by some of the greatest names in AI Research today, this book is the best I can recommend for an introduction to Deep Learning.

* [Pattern Recognition and Machine Learning](https://github.com/dlsucomet/MLResources/blob/master/books/Pattern%20Recognition%20and%20Machine%20Learning.pdf) by Christopher Bishop (2006) - The OG Machine Learning Book. A tad bit outdated, but it does work really great as a classical machine learning textbook.

## Data Science
*Coming Soon*

# Conference and Journal Papers
Seminal papers on various topics. Super good to read even if you're working in another area of Machine Learning/Deep Learning. Sorted via year.

## Convex Optimization for Neural Networks
* [Adam: A Method for Stochastic Optimization (Kingma & Ba, 2014)](https://arxiv.org/abs/1412.6980) - "Hehe alam mo Blaise diba the best optimizer for neural networks is Adam tapos my dog is named Adam hihi cute diba!" (Courtney Ngo, 2018)
* [Dropout: A Simple Way to Prevent Neural Networks From Overfitting (Srivastava, 2014)](http://jmlr.org/papers/volume15/srivastava14a.old/srivastava14a.pdf) - Probably the most important regularization technique of our time. Started as a master's thesis, now it's on every deep learning framework. This is the paper we all aspire to write.

## Deep Learning and Natural Language Processing
* [Attention Is All You Need (Vaswani, et al., 2017)](https://arxiv.org/abs/1706.03762) - Replaces the need for super deep Recurrent/Convolutional mechanisms in your sequence models by using pure attention mechanisms. I've read four state-of-the-art NLP papers of differing NLP tasks. They all use Attention. It's truly all you need.

## Generative Models and Adversarial Networks
* [Generative Adversarial Networks (Goodfellow, et al., 2014)](https://arxiv.org/abs/1406.2661) - Touted by Yann LeCun as the "most interesting idea in ML in the last 10 years," the GAN is a framework for training generative models in an adversarial setting. The most important contribution by my favorite deep learning researcher, and arguably his best.

# Blogs and Podcasts
A collection og blogs, blog posts, and podcasts that talk ML and Deep Learning.

## Blog Posts
* [The Matrix Calculus You Need For Deep Learning](http://explained.ai/matrix-calculus/index.html) - A "paper" attempting to explain all the matrix calculus you need to understand deep learning. The learning curve might be a tad bit too steep so I suggest it as a side-material when taking a math course.

