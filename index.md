---
title: Simulating Language
description: Academic year 2023/2024
---

*N.B. If you are auditing this course and have not yet been added to the Simulating Language Team, please get in touch with Simon Kirby on teams and ask to be added to the Team and assigned a lab group ASAP. Thanks!*

This is the webpage for the Honours/MSc course Simulating Language, running in academic year 2023/2024. We will add links to materials (readings, videos, code) to this page; you will need to use Learn for electronic submission of your assessed work, and to keep an eye out for any course announcements.


## Course summary

In this course we are going to be using simulation models to study language. People use various types of models in linguistics for a number of purposes; in this course we are going to focus using models to study how processes of learning, communication and evolution shape linguistic systems, and we'll primarily be using agent-based Bayesian models (don't worry, we'll explain what that means!).

This is a practical course: you'll be running and tinkering with code for computational models written in python. You don't need to be programmer to take the course - no programming knowledge is assumed, and we are doing everything in the simplest way we can think of, building from the ground up. But you will be doing stuff with code, so you have to be prepared to give it a go, dive in, and try stuff out. Don't worry, we'll help you figure it out.

## The teaching team

[Simon Kirby](https://simonkirby.net/) is the lecturer for this course. The best way to get in touch with me is after a lecture, or by messaging on Teams. Please don't email.

## Structure of the course

The course is based around a series of ten lectures, which take place one per week. Each lecture is followed by a programming practical, which you attempt in your own time, and get help with in a drop-in lab session. Each lecture may have readings associated with it.

### Readings

The week-by-week reading content is at the bottom of this page. The readings consist of our notes plus a mix of journal papers and book chapters.

For some of the lectures the reading is flagged up as being **pre-reading**, i.e. we will assume you have done this preparatory work prior to the lecture and will design the lecture accordingly (i.e. we might refer to stuff in the preparatory materials or ask you questions about it).

You should always complete the reading materials and attend/watch the lecture before attempting the programming practical or attending the drop-in lab classes - the practicals involve playing with models that implement the ideas covered in the readings and lecture recordings, so will make a lot more sense when you have that context.


### Lectures

- Lectures are **Fridays 15.10 - 16:00** in F.21, 7 George Square

Lectures start in week 1, i.e. the first lecture is Friday 19th January. Lectures will be recorded and appear on Learn.

### Practicals and drop-in labs

- Labs are in 4.02, Appleton tower (Mondays, Wednesdays and Thursdays).

You can attempt the programming practical on your own, but we provide the drop-in labs at set times each week where you can come and get our help to figure out problems. You should come to the drop-in labs if you need help with a specific problem, but you are also welcome to just turn up in drop-in labs to hang out and work through things on your own with us in the background - some people find that having set times helps them focus.

You will be assigned a lab group that will take place at one of the following times starting in week 2:
- Mondays 11:10 - 13:00 
- Wednesdays 13:10 - 15:00 
- Thursdays 13:10 - 15:00 


### Chat on Teams

In addition to asking questions in lectures and drop-in labs, we will set up channels on Teams for you to ask questions. If you have a question that you can't ask live, Teams (rather than email) is our preferred way for you to get in touch.

## Assessment

The two assignments involve a mix of practical work and written sections and have the following deadlines:

- 7th March at noon (released 26th February)
- 18th April at noon (released 1st April)

*IMPORTANT* we will only answer questions about the assignments for 4 days following the release of the assignment, and questions *must* be posted on the Teams channel so that everyone can see the answers! No further questions about the assignments will be answered after this. We have struggled with getting this right over the years, with some years people asking questions after other people have already submitted, which feels unfair, and other years not answering questions at all, which also felt unfair. I hope this year we've got the balance right!

For UG students, each assessment is weighted equally for the final marks. For PG students, the first assessment is worth 30% and the second is worth 70%.

## Course Materials

Dates for lectures and labs shown in brackets. Please note that we will only post the answers for each lab the week following the lab. So please do have a go yourself, and come along to the lab sessions if you get stuck! 

N.B. The numbers below indicate the order of the sections of the course, but it's possible that lectures may move. Note that there are 11 weeks in the teaching semester to fit 10 lectures into, which allows a bit of flexibility.

### 1. Introduction

- Pre-lecture reading: [Introduction to modelling](simlang_reading_1.md)
- [Lecture slides](lecture_slides/lecture1.pdf) (Jan 19)
- Programming practical: [Introduction to Python](simlang_lab_1.md) (Jan 22, 24, 25)


<!--
### 2. Concept learning

- Pre-lecture reading: [More on Bayes' Rule](simlang_reading_2.md)
- [Lecture slides](lecture_slides/lecture2.pdf) (Sep 30)
- Programming practical: [Word learning](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab2.ipynb) (Oct 3, 5, 6)
- Answers to Practical: [Word learning answers](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab2_answered.ipynb)

### 3. Frequency learning and regularisation

- No new reading - catch up on the readings on Bayes, or read [Xu & Tenenbaum (2007)](https://psycnet-apa-org.ezproxy.is.ed.ac.uk/fulltext/2007-05396-002.html), covered in the previous lecture, for yourself.
- [Lecture slides](lecture_slides/lecture3.pdf) (Oct 7)
- Programming practical: [Frequency learning and regularisation](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab3.ipynb) (Oct 10, 12, 13)
- Answers to Practical: [Frequency learning and regularisation answers](https://nbviewer.org/github/smkirby/simlang2022/blob/main/lab3_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_3_walkthrough/1_1pyq2qg1)


### 4. Cultural evolution by iterated learning

- [Lecture slides](lecture_slides/lecture4.pdf) (Oct 14)
  - [Video of uniform prior](lecture_slides/lecture4_videos/posterior_uniform.mp4)
  - [Video of regularity prior](lecture_slides/lecture4_videos/posterior_regularity.mp4)
  - [Code for generating these videos](https://nbviewer.org/github/smkirby/simlang2022-23/blob/gh-pages/lecture_slides/lecture4_videos/lecture4_figures.ipynb)
- Post-lecture reading (read this directly after the lecture, not before): [Bayesian iterated learning](simlang_reading_4.md)
- Programming practical: [Bayesian iterated learning](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab4.ipynb) (Oct 17, 19, 20)
- *Logarithms for the concerned*: a supplementary walkthrough in three parts
  - [online slides](https://centre-for-language-evolution.github.io/simlang2021/LogExplainer.slides.html#/)
  - [notebook](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/LogExplainer.ipynb)
- Answers to practical [Bayesian iterated learning](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab4_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_4_walkthrough/1_kv20uefj)


### 5. Communication and the RSA model

- Reading: [The Rational Speech Act model](simlang_reading_5.md)
- [Lecture slides](lecture_slides/lecture5.pdf) (Oct 21)
- Programming practical: [The Rational Speech Act model](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab5.ipynb) (Oct 24, 26, 27)
- Answers to Practical: [The Rational Speech Act model](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab5_answered.ipynb)


### 6. Compositionality: the origins of structure

- Reading: [The evolution of compositionality](simlang_reading_6.md)
- [Lecture slides](lecture_slides/lecture6.pdf) (Oct 28)
- Programming practical: [Compositionality](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab6.ipynb) (Oct 31, Nov 2, 3)
- Answers to Practical: [Compositionality](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab6_answered.ipynb)
- [Walkthrough video](https://media.ed.ac.uk/media/lab_6_walkthrough/1_cv3bptoq)


### 7. Hierarchical models and learning the prior

- Reading: [Hierarchical models and learning to learn](simlang_reading_7.md)
- [Lecture slides](lecture_slides/lecture7.pdf) (Nov 4)
- Programming practical: [Hierarchical learning](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab7.ipynb) (Nov 7, 9, 10)
- Answers to Practical: [Hierarchical learning](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab7_answered.ipynb)



### 8. Innateness and culture

- Reading: [Innateness and culture in the evolution of language](simlang_reading_8.md)
- [Lecture slides](lecture_slides/lecture8.pdf) (Nov 11)
- Programming practical: [Convergence to the prior](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab8.ipynb) (Nov 14, 16, 17)
- Answers to Practical: [Convergence to the prior](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab8_answered.ipynb)


### 9. Biological and cultural evolution together

- Reading: [Gene-culture co-evolution](simlang_reading_9.md)
- [Lecture slides](lecture_slides/lecture9.pdf) (Nov 18)
- Programming practical: [Co-evolutionary modelling](https://nbviewer.org/github/smkirby/simlang2022-23/blob/main/lab9.ipynb) (Nov 21, 23, ~~24~~)
- Answers to Practical: [Co-evolutionary modelling](lab9_answered.html)



### 10. This view of language

- Reading: [Overview of this view of language](simlang_reading_10.md)
- [Lecture slides](lecture_slides/lecture10.pdf) (~~Nov 25~~)
- Catch up labs (Nov 28, ~~30~~, Dec 1)


--->
## Re-use

This page was written by Simon Kirby, based on https://centre-for-language-evolution.github.io/simlang2021/, written by Kenny Smith and Simon Kirby. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).