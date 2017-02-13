---
layout: "post"
title: "When to use Machine Learning?"
date: "2017-02-05 18:46"
---

Should I get started with “Machine Learning” to improve my situation?

If you are trying to pick an action based on a problem you are facing, how should you approach it? You have heard a lot or a little about “Machine Learning.” Here’s my personal story to help you decide.

As a software programmer, when I want solve a problem, I try to figure out a way to automate it. Being a machine learning engineer, I begin comparing to the oldest problem solving method: deterministic programming.

![Malai Running](/assets/2017-02-04-When to Use Machine Learning/malai_running.jpg)

Being active is my passion. Everyday, I decide whether to go outside for a run outdoors. Situations that influence my decision are:

1. Is it raining outside?

    - Yes --> Don't run
    - No --> I think I can run.

2. Time of the day?

    - Is it 10 P.M to 5 A.M --> Dont' run. Too dark outside.
    - 5 A.M to 7 A.M --> I think I can run.
    - 8 A.M to 9 A.M --> Am I working from home? I think I can run.
    - 9-5 P.M --> Don't run. Office work.
    - 5 P.M -7 P.M --> I think I can run.
    - 7 P.M - 9 P.M --> if it is not too dark then I can run.
    - 9 P.M - 10 P.M --> After dinner, I don't run.

3. Do I have to drop my son in school?

    - Is it Morning school drop time ( 8.30 A.M to 9 A.M) --> Dont run
    - Is it evening school pickup time (4.45 P.M to 5.15 P.M) --> Dont run.
    - Other times. I think I can run.

4. What is the temperature outside?

    - 50-80F --> I think I can run.
    - 80F-110F --> I don't think I can run. Too hot.
    - 0F - 50F --> I am not running.

If I do this deterministically, then I will end up with lot of "If" conditions for all the permutations of combinations that are possible .  With just 4 attributes, it is getting complex. Imagine having hundreds of attributes influencing whether I want to run or not. This is where machine learning will save my day. (Did I mention that I am a lazy programmer? Good code is better than more code.).  

A machine learning model "projects past on future" to “learn” whether I will run outside or not. With historical data of my running (Map my run, Garmin, Fitbit, Apple Watch) + publicly available weather data, I can train a machine learning model (classification problem) to decide whether I want to run or not. A set of machine learning algorithms will approximate a decision boundary for this problem. Output from the machine learning algorithm is probability for 2 classes: a) run or b) don’t run.

Do you see? Machine learning rocks. This story is perfect for a supervised classification problem.

#### By Malaikannan Sankarasubbu: [Click here for more information](http://malaikannan.io/)
