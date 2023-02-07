---
layout: page
title: Syllabus
description: Course policies and information pertaining to Deep Learning for Robot Perception and Manipulation at the University of Minnesota.
nav_order: 2
---

# Course Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About

Robots need to see and understand their world to be able to interact with objects and perform useful tasks autonomously. Perception is the essential first step in the process for endowing robots to perform autonomously.  Autonomous robots need to make sense of their sensory observations to represent the world around them – and enable their reasoning and action to a goal. Visual perception with cameras as sensors has matured due to the recent advancements in neural networks – which is especially true for performing visual recognition tasks such as object classification, detection, pose estimation, grasp pose detection, etc. 

This course aims to cover the necessary background of neural-network-based deep learning for robot perception – building on advancements in computer vision and enabling – for enabling robots to dexterously manipulate physical objects. During the first part of this course, students will learn to implement, train and debug their own neural networks. During the second part of this course, students will explore recent emerging topics in deep learning for robot perception and manipulation.  This exploration will include analysis of research publications in the area, building up to reproducing one of these publications for implementation as a final course project.

This course builds on and is indebted to these existing courses (as a “star” and a "fork" in the open source sense):
- [University of Michigan - EECS 498-007 / 598-005: Deep Learning for Computer Vision](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/schedule.html){:target="_blank"} instructed by [Justin Johnson](https://web.eecs.umich.edu/~justincj/){:target="_blank"}
- [Stanford - CS231n: Deep Learning for Computer Vision](http://cs231n.stanford.edu/index.html){:target="_blank"} instructed by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li){:target="_blank"} and [Andrej Karpathy](https://karpathy.ai/){:target="_blank"}


## Topics and Course Structure

The first half of the course will cover deep learning fundamentals in computer vision catered to robot perception problems.

- Linear classifiers
- Stochastic gradient descent
- Fully-connected networks
- Convolutional networks
- Pose estimation

The second half of the course will switch to seminar style covering following advanced topics in robot perception and manipulation via discussing publications.

- 3D vision in robotics
- Object perception for robot manipulation
- Neural radiance fields for perception
- Robot grasp pose detection

## Prerequisites

- Strongly encouraged prerequisites:
  - Linear Algebra, Calculus, and Probability
  - Programming fluency in data structures in a classical programming language is essential.  
  - Prior experience with the [Python programming language](https://www.python.org/) is strongly recommended.

- Recommended prerequisites: 
  - CSCI 5511 - Artificial Intelligence I
  - CSCI 5521 - Machine Learning Fundamentals
    - Familiarity with concepts from machine learning will be helpful.
  - CSCI 5551 - Introduction to Intelligent Robotic Systems

## Textbook

There is no required textbook for this course, however optional readings will be suggested from the textbook, ["Deep Learning" by Ian Goodfellow and Yoshua Bengio and Aaron Courville](https://www.deeplearningbook.org){:target="_blank"}.

## Lectures

Lectures will take place in-person on **Tuesdays and Thursdays from 2:30-3:45 PM CT in Rapson Hall 58**. 
Remote access will be made available for the following reasons:
- Weather impediment: Zoom link will be sent out via email prior to the lecture
- Health reasons: Email kdesingh@umn.edu before the lecture with the reason to attend via Zoom, to obtain the meeting ID and password. 

## Discussion Sections

There will be no discussion section for this class. However, I will link to the discussion posted by instructors from the University of Michigan after every Thursday's lecture to the calendar. Students are encouraged to see view them.

## Programming Projects

You will complete 5 programming [projects](/CSCI5980-Spr23-DeepRob/projects/) over the course of the semester. All projects will be implemented using Python, Pytorch and Google Colab.

## Final Project

Instead of a final exam at the end of the semester, you will complete a final project working in groups of 1 to 3 students.

The final project will entail five core deliverables: (1) a written review of a paper (2) an in-class paper presentation, (3) reproducing the published results of an existing deep learning paper, (4) extending the chosen paper's methods and (5) documenting your reproduction and extension in a written report.

The objective of the final project is for you to gain experience with state of the art approaches in deep learning and a sense of how research in the area is conducted.

## Quizzes

Throughout the semester, there will be a total of 16 quizzes administered through [gradescope](https://www.gradescope.com/courses/481744){:target="_blank"}. These quizzes will be posted before lecture sections throughout the semester and be available to take until the beginning of lecture that same day. Quizzes will be released at 7:00AM CT and must be submitted by 2:30PM CT. Each quiz will have a 15 minute time limit. Each quiz will consist of 1 or 2 short questions within the scope of previously covered lectures and graded projects.

## Grading Policy

Course grades will be determined according to the following criteria:

 - Project 0:     12%
 - Project 1:     12%
 - Project 2:     12%
 - Project 3:     12%
 - Project 4:     12%
 - Final Project:
   - Project proposal document: 2%
   - In-class presentation on research topic-paper(s): 5%
   - Paper Reproduction: 12%
      - Algorithmic extension to obtain results on new data/idea/technique
   - Video and poster: 3%
   - Final report: 2%
 - 16 Pre-Lecture Quizzes: 16% (1% each)

## Collaboration Policy

The free flow of discussion and ideas is encouraged. <b> But, everything you turn in must be your own work </b>, and you must note the names of anyone you collaborated with on each problem and cite resources that you used to learn about the problem. If you have any doubts about whether a particular action may be construed as cheating, ask the instructor for clarification before you do it. Cheating in this course will result in a grade of F for course and the [University policies](https://communitystandards.umn.edu/avoid-violations/avoiding-scholastic-dishonesty) will be followed.

No code can be communicated, including verbally. Explicit use of external sources must be clearly cited.

## Students with Disabilities
If you have a disability for which you are or may be requesting an accommodation, you are encouraged to contact both your instructor and [Disability Resources Center](https://disability.umn.edu/) (DRC).

## Discussion Forum

The [Ed Stem](https://edstem.org/us/courses/31008/discussion/){:target="_blank"} discussion forum is available for discussion of course materials including lectures and projects. This forum will be shared across course offerings at the University of Michigan and the University of Minnesota. <b>Students are not required to participate, use or join the Ed Stem forum.</b> Students may opt-in to join the forum using this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSelLeqIUKBxQvqqp6LFs2fSYfzy9D_QCcvtXc302hnm6oF1EA/viewform?usp=sharing){:target="_blank"}.

<b>Any discussion of quizzes and verbatim code on the Ed Stem forum must be posted privately.</b>