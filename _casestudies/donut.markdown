---
layout: study
title:  'Donut'
description: 'Using a Donut to How Explain Psychology Could &ldquo;Predict Success&rdquo;'
date: 2020-07-28 08:55:27 -0400
image: ''
---
One of the things that drew me to Hireology in the beginning was the idea that that you could "predict success".  The original software was built around this idea, and was very prescriptive about what you should ask a candidate during interviews.

## Background

Of course, every job is different, and so the system needed to know the details of the job you were wanting to hire for so it could understand how to find the best hire. So when a hiring manager went to open a job, they were prompted with a 35 true/false questionnaire to complete, and then the job would be open and ready for people to apply.

Behind the scenes, the questions were attached to 67 &ldquo;elements of success&rdquo; which&mdash;when grouped together&mdash;identified which competencies were important to a job and which were not. This effectively meant that the job had a shape, if you will, when plotted on a radial chart:

RADIAL CHART OF JOB

The interviews questions were then generated to help find a candidate that best matched the shape of the job. The more aligned the shape of the candidate is to the shape of the job, the more likely the candidate would be successful.

RADIAL CHART OF JOB + CANDIDATE

## Problem

Now, you are probably thinking to yourself &ldquo;What does all that mean?&rdquo; And that was exactly the problem: We were asking the user to jump through this questionnaire every time they opened a job, but we never explained in the app _why_ they had to do this, and how important it was to making sure they made a great hire for the job.

This was the issue that Margot, our Vice President of Product at the time, brought to me. We needed to help the user understand why the questions were important, why the interviews included certain questions and a particular scoring pattern, all while not diving too deep into the I/O psych aspect.

I had two man concerns coming into this problem.

First, it took about 30 minutes for Margot to explain this in such a way that I had a grasp of what was going on. Obviously, having a user dedicate 30 minutes wasn't something we thought was wise.

Second, I didn't feel that the radial charts above were immediately intuitive. Radials are not a typical chart type, and so I was worried we would have to spend time explaining the basics of how to read the chart before we could get to the message it was trying to convey.

## Solution

Enter the &ldquo;donut&rdquo;.

I started with how to represent which competencies were more important to a job than others. I quickly settled on a pie chart, as I felt it did a great job of meeting that objective while also being more familiar to the user than a radial.

PIE CHART OF JOB vs RADIAL

So now we are communicating which competencies are important to a job. The next piece was how to help the user understand how the candidate they just interviewed was aligning with this particular job. Each question in an interview tied back to one of the competencies, and was scored on a simple scale of great, good, OK, and poor. 

This is where the color of each wedge came in. Normally, the colors are used just to help someone see the individual slices more easily. In this case, though, we associated each of the possible answers to a color - green for great, red for poor, etc - and then applied those colors to each of the competencies.

COLORED PIE CHART

Finally, there was a score, which was what the user was used to seeing now when they completed an interview. To help connect the score to this new chart, I wanted them to appear as tightly coupled as possible. And so, we carved out the center of the pie chart to drop the score into, and found ourselves with the donut.

DONUT

## Results

Once the donut was in place and marketed, we saw a 25% increase in scoring of interviews in both existing ane new users. In addition, 

## Missed Opportunities

As can sometimes happen, the longer term vision for the donut being used across the app did not pan out as was originally intended.

We had intended to allow users to be able to see the donut as they completed job setup, so they could see how the application was analyzing their answers and the type of candidate that would be a good fit. Ideally, this could cause the user to go back and reevaluate some of the questions if they thought that one competency was either over or under rated.

In addition, we had planned to roll out an upgraded version of the donut that would reveal which questions were part of which competency, and see how the overall score was being influenced by the answers to those questions.

OTHER DONUT

There was some debate on this implementation, as there was concern that this would allow hiring managers to game the interview in order to present a candidate as a better fit than they actually were.

Ultimately, though, we never got a chance to validate that concern, as we began to pivot away from the prescriptive nature of the software towards allowing significantly more configurability, thus allowing companies with an established hiring process to implement what they wanted instead of having to reconfigure to fit our model.

## Summary

The donut was a success in both getting usage of a feature up as well as providing users with a better understanding of how the underlying system worked. Had priorities not shifted, I believe that it would have become a defining feature for Hireology.