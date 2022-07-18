---
layout: post
title:  "You are wrong and the problem is with your assumptions"
date:   2022-07-18 08:30:00 +0100
categories: blog
---

## Intro

I think that to deliver great software to clients we as software developers quite often need to make some assumptions about the final product because we are unable to prepare a solution that will be universal to anyone and in any given case.

For example, we quite often assume that our users will have two hands, good eyesight, could read a certain language, etc. Usually, those assumptions are correct in the beginning, but later we are reciving angry reviews of our products because users cannot use our solutions at all.

**Good software developers think that they need to make good assumptions about the software, but great developers don't afraid to change assumptions often to make sure that final products will fully satisfy end users.**

I asked Ash Furrow 3 questions about assumptions to check if he agrees with me or not.

## Questions

1. How to define good assumptions while creating new software products to deliver what clients expect?
2. How you should estimate the work that we need to deliver based on assumptions that are still not verified by a client?
3. What is the most important characteristic of a World Class Software Developer?

### 1. How do define good assumptions while creating new software products to deliver what clients expect?

To deliver any kind of software product we should start with a backlog. A list of requirements and usually User Stories that will define a mandatory behavior of the software. However, this will lead to a standard waterfall approach, where all the documentation is provided at the beginning and the final product is delivered at the end. Usually, the Client is disappointed, because he received a product that didn't match his/her expectations.

How we can handle this? Being agile means that we will deliver prototypes to the Client quickly and often. For example, we could skip the Backend implementation completely and show customers only the working Frontend with mocked data (any clickable demo will do, the first prototype could be even on paper). By doing that, we will receive feedback from the customer very early and we will be able to identify which assumptions were wrong and correct them. 

Seems very promising in the beginning, but this leads us to two more problems: how to estimate the final product when we don't have the final specification and how to charge the Client for every change. There are entire books written about such a topic so I won't focus on that here. Ash concludes that we need to be agile in software development because this is currently the fastest solution to verify clients' assumptions.  

The important note is that with every prototype that we will show to the Client we need to get feedback, verify assumptions, do another step and then work on the next prototype.  **Most of the feedback can be received from only 5 users.** Prototype is built with an intention to get feedback and then it can be thrown away but it will allow clarifying the assumptions and communicating with the Client much more efficiently.

A good analogy is with a typical car. If the Client wants us to build a car, then we can assume that we need 4 tries, because everybody knows how many tires have a typical car. However, after the first prototype client could notice that he must be able to drive with a huge load therefore he needs a pickup with a double set of tires, so we need to have 6 tires instead of 4. That's only one wrong assumption, but the cost of buying tires for our product jumped by 50%. This happens in software development quite often.

It is hard to build universal products ie. not every car serves the same purpose, therefore we have sedans, pickups, hatchbacks, etc. but as software developers, **we need to expect changes in the future**. Quite often clients expect an amphibious car (a car that can swim) and this is what we should know as soon as possible. Therefore, just build the first prototype and give it to the client. If the client will try to drive it over the lake, then you will know that. Thankfully, that is the only prototype, so nobody should be harmed while getting feedback.

### 2. How you should estimate the work that we need to deliver based on assumptions that are still not verified by a client?

Estimates are not there to give the customers the exact time that is needed to complete the product. Estimates are there for the development team to be better to estimate over time. After every sprint (usually every 2 weeks) the dev team could talk about those estimates and discuss why something that was estimated for 2h took 4h to complete. If everybody will be able to understand the reason for that, then every one of them will be able to estimate better over time. It helps to communicate better in the team and they will be able to estimate tasks in the next sprint much better.

In my regular practice I noticed that usually, the estimates are wrong because the chunk of work was simply too big. We tried to solve that, by splitting the task into smaller pieces of work and estimating them independently. The sum of the individual estimates is quite often bigger than the initial estimate of the main task. 

A second good piece of advice is to use Fibonacci numbers instead of a number of hours, so numbers like 1,2,3,5,8,13, etc. where a bigger number means that you will need more time to deliver it. However, we never use numbers above 10. If you think that a task needs 13 points to complete, probably you should split it into two smaller ones and estimate them instead.

### 3. What is the most important characteristic of a World Class Software Developer?

In the past, I often felt that I was like a boat on a very big ocean, with no land on the horizon and I literally didn't know where I should go. The wind was blowing always from a different direction and I was reacting to it and adjusting sails to the wind, but the main direction was still not clear. It took me a few years in the IT industry to realize that I was always following the same goal. After delivering any kind of software I understood that **the most important in software development is the user** that will be using it at the end.

That's why it is so important to show them the prototypes and verify the initial assumptions and adjust them as soon as only possible. World-Class Software Developer therefore must always see the final vision on the horizon. If you get new information or expectations during the development process you need to react to them and **be able to self-correct yourself** so that in the end - every single time, you will be able to provide a product that will satisfy your customers.

# Summary

Assumptions help us to simplify the Software Development process, but we need to verify them as soon as possible. As World Class Software Developer you need to be able to adjust quickly to new requirements because initial assumptions could change during the process.

