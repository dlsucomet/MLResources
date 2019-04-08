# Machine Learning Reference List
Here's a curated list of references/resources that you can use to teach yourself Machine Learning, annotated with prerequisites and recommendations to help you choose. It's a work in progress and I'll be updating it every so often, so be sure to keep checking!

# Courses
A list of highly recommended short courses and lecture video series.

## Mathematics for Machine Learning
Machine Learning requires some mathematical prerequisites for you to understand what's going on. Generally, experience with statistics, probability, linear algebra, and multivariate calculus are hard requirements. Reading papers and books is hard without the prerequisites, so we cannot stress how important it is to go through them first! If you're pressed with time, I recommend running through just CMU 10-606. Otherwise, the other things listed would provide really good resources. 

|Course |Source |Notes |Prerequisites |
|:-------- |:---|:---|:---|
|[\[10-606\] Mathematical Background for Machine Learning](https://www.youtube.com/playlist?list=PL7y-1rk2cCsAqRtWoZ95z-GMcecVG5mzA)| Carnegie Mellon University| Teaches the mathematical foundations. Take this if unsure where to go. No needed prior knowledge, but previous classes on statistics, linear algebra, and calculus would help. | None.
|[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | 3Blue1Brown| My favorite linear algebra short course online, with an emphasis on geometric interpretations and intuitions. Recommended binge watch. | None.
|[Computational Linear Algebra](http://www.fast.ai/2017/07/17/num-lin-alg/) | fast.ai | A more practical linear algebra class with emphasis on practical intuition and coding. Teaches you how to code the algorithms for those who like to see numbers in action. | None.
|[Linear Algebra Review](http://www.cs.cmu.edu/~zkolter/course/linalg/index.html) | Carnegie Mellon University | A quick review on the guts of linear algebra. Only take it if you've taken a previous course. | Previous linear algebra course.
|[\[10-705\] Intermediate Statistics](http://www.stat.cmu.edu/~larry/=stat705/) | Carnegie Mellon University | Works nicely as a theoretical take on statistical theory. Coers topics such as bayesian inference and nonparametric testing. This is not a basic statistics course, and is intended for a deep dive in intermediate statistics! Recommended for intermediate students. | Previous statistics and probability course.

## Introduction to Machine Learning
Basic Machine Learning. Assumes the required mathematical background is met, ideally CMU 10-606 has been taken as a precursor. Go take CMU 10-701 if unsure where to go. 

|Course |Source |Notes |Prerequisites |
|:-------- |:---|:---|:---|
| [\[10-701\] Introduction to Machine Learning](http://www.cs.cmu.edu/~mgormley/courses/10701-f16/schedule.html) | Carnegie Mellon University | My current go-to recommendation for an introduction to machine learning. Solid offering. | Statistics, linear algebra, and calculus (multivariate). CMU 10-606 would work as a precursor.
| [\[CS229\] Introduction to Machine Learning](https://www.youtube.com/playlist?list=PLA89DCFA6ADACE599) | Stanford University | Used to be my go-to, but is outdated (the video quality says it all). Go to CMU 10-701 unless you like seeing Andrew Ng prove theorems on six blackboards at once. | Statistics, linear algebra, and calculus (multivariate). CMU 10-606 would work as a precursor.
| [\[CS155\] Introduction to Machine Learning](https://www.youtube.com/playlist?list=PLuz4CTPOUNi644ypoxzP1frkPYVHdjDJU) | California Institute of Technology | Caltech's intro to machine learning, which Stan recommends. Yisong Yue teaches really well. | Statistics, linear algebra, and calculus (multivariate). CMU 10-606 would work as a precursor.

## Deep Learning
Neural networks and everything under it's umbrella. Requires good foundations! Some background in basic machine learning would help. Go take Hugo Larochelle's course for a more theoretical (proof-based) introduction.

|Course |Source |Notes |Prerequisites |
|:-------- |:---|:---|:---|
|[Neural Networks](https://www.youtube.com/watch?v=SGZ6BttHMPw&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH) | Universitè de Sherbrooke | Hugo Larochelle's neural networks class. My go-to recommendation for people who want a good theory-based introduction with complete proofs and intuitions. | Good linear algebra and multivariate calculus, plus statistics and information theory.
|[Neural Networks](https://www.cs.toronto.edu/~hinton/coursera_lectures.html) | Coursera | The coursera neural networks course from the godfather Geoffrey Hinton himself! | Good linear algebra and multivariate calculus, plus statistics and information theory.
|[Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) | 3Blue1Brown | Not an in-depth deep learning course but rather a series of videos that help you visualize and understand the intuitions and mechanics behind neural networks. Recommended binge-watch! Can be used as a primer to get your feet wet. | Just calculus is fine.

## Natural Language Processing
Courses on Natural Language Processing (with an emphasis on deep learning methods). I learned from the old CS224N course, but we've added the new one here.

|Course |Source |Notes |Prerequisites |
|:-------- |:---|:---|:---|
| [\[CS224N\] Introduction to Natural Language Processing with Deep Learning](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) | Stanford University | The Winter 2019 version of the Deep Learning + NLP course offered by Christopher Manning and Abigail See. Highly recommended. | A previous machine learning course. A previous deep learning course is appreciated.
| [\[CS224N\] Introduction to Natural Language Processing with Deep Learning](https://www.youtube.com/playlist?list=PLqdrfNEc5QnuV9RwUAhoJcoQvu4Q46Lja) | Stanford University | The older, time-tested version of the CS224N course, added here in case you need it. | A previous machine learning course. A previous deep learning course is appreciated.

## Computer Vision
Courses on Computer Vision (with an emphasis on deep learning methods).

|Course |Source |Notes |Prerequisites |
|:-------- |:---|:---|:---|
| [\[CS231N\] Convolutional Neural Networks for Visual Recognition](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) | Stanford University | Stanford's computer vision class with an emphasis on deep learning techniques. Taught by Fei-Fei Li, Justin Johnson, and Serena Yeung. | A previous machine learning course. A previous deep learning course is appreciated.

## Data Science
We're actually making some data science lecture videos so watch this space as it's coming soon!

# Books
Some of my highly recommended books. 

## Machine Learning and Deep Learning
* [Deep Learning](https://github.com/dlsucomet/MLResources/blob/master/books/Deep%20Learning.pdf) by Ian Goodfellow, Yoshua Bengio, and Aaron Courville (2016) - Written by some of the greatest names in AI Research today, this book is the best I can recommend for an introduction to Deep Learning.

* [Pattern Recognition and Machine Learning](https://github.com/dlsucomet/MLResources/blob/master/books/Pattern%20Recognition%20and%20Machine%20Learning.pdf) by Christopher Bishop (2006) - The OG Machine Learning Book. A tad bit outdated, but it does work really great as a classical machine learning textbook.

## Data Science
*Coming Soon*

# Conference and Journal Papers
We're making a separate list of good papers to read. Coming soon!

# Blogs and Podcasts
A collection of blogs, blog posts, and podcasts that talk ML and Deep Learning.

## Websites and Trackers
* [Papers With Code](https://paperswithcode.com) - A tracker with SOTA leaderboards for multiple tasks in different areas of research.
* [Tracking The Progress of NLP](http://nlpprogress.com) - A tracker that's regular updated with the state-of-the-art in various NLP tasks, datasets, techniques, etc.

## Blog Posts
* [The Matrix Calculus You Need For Deep Learning](http://explained.ai/matrix-calculus/index.html) - A "paper" attempting to explain all the matrix calculus you need to understand deep learning. The learning curve might be a tad bit too steep so I suggest it as a side-material when taking a math course.

* [The Best of Universal Sentence/Word Embeddings](https://medium.com/huggingface/universal-word-sentence-embeddings-ce48ddc8fc3a) - From the blog of Thomas Wolf, an NLP-Deep Learning researcher. Reviews the current state-of-the-art techniques in word embedding and sentence embedding techniques.

