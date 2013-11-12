---
layout: default
title: Why you should look at cohorts
---
# Why you should look at cohorts

Imagine that an entrepreneur came to you and showed you this graph.

<img class="iborder" src="/assets/users_growth.png"/>

You would think the startup is doing quite well, right? Well, not so fast.

A common mistake entrepreneurs make is focusing too much on user growth at the expense of engagement. They see a graph like the above and think that they have “arrived.” Turns out that there is more to the story. User growth is a necessary but not a sufficient condition for success. Often, a much more important question is: “Are you retaining the users you are acquiring?”

Eventually, most user acquisition channels saturate. If the startup is unable to retain the users it acquires, the result is a hollowing out effect. Think of a ring of fire expanding outwards. The fire burns out everything inside and the only activity that survives is at the edges.

<img class="iborder" src="/assets/brush_fire.jpg"/>

This is a hard lesson that I learned first hand. The first product that we launched was a walkie-talkie app that one could use to record a short audio clip and send it to a friend. We saw good viral growth as users invited their friends. User retention, however, was not so great; people would initially be very excited to use the app but in a few weeks would drop off. The end result was that although we grew to more than 1.5 million users, the residual activity remained small after a few months.

The lesson is to focus on user engagement and retention. The product needs to establish a lasting habit in users' minds. Nir Eyal has some great ideas around this using a framework called [desire engine](http://www.nirandfar.com/2012/03/how-to-manufacture-desire.html).

How do we measure user engagement and retention? In my experience, the best way to do measure user retention is by [cohort analysis](http://cohortanalysis.com).

## Cohort Analysis

A cohort is a group of people who share a particular characteristic over a period of time. An example cohort is a group of users who joined on a particular day.
A cohort analysis takes the cohort and follows their actions over a period of time. For instance, we could do a cohort analysis by tracking the number of app or site visits by users in the cohort. Let us take a concrete example by following two cohorts of 100 users, one cohort consisting of users who joined on January 1 and another who joined on January 8.

Picture of a graph

The above graph shows that of the January 1 cohort, there were 100 visits on day 0, 90 on day 1, 80 on day 2 and so on. The January 8 cohort did slightly worse, with 100 visits on day 0, but only 89 on day 1 and 78 on day 2.

The same cohort analysis can also be shown as a table:

Picture of a table

Cohorts can be used to track any metric of importance: app visits, number of shares, dollars spent, and so on. The cohort themselves can be grouped by any interesting characteristic: users coming from an ad channel, users with a particular demographic, users who have crossed some milestone in the app, and so on.

Jeremy Liew has a great [post](http://lsvp.com/2012/06/15/how-to-estimate-lifetime-value-for-an-ecommerce-business-sample-cohort-analysis/) walking through a sample cohort analysis tailored for e-commerce applications.

Most modern analytics platforms such as Mixpanel and KissMetrics have decent capabilities for analyzing cohorts. There are also more specialized solutions such as RJMetrics.

## How is cohort analysis helpful
* Critical data does not get drowned in external events. Suppose this is a press mention of your startup, or your app gets featured on the App Store. If you just looked at the user growth you would not be able to tell what is really going on.

* Cohorts give you very actionable data. Why is the user retention weak? Could it be the onboarding? Do you need reminders to establish a consumption habit? Or heaven forbid, is your product actually is not interesting? Combining some funnel analysis with your cohorts can give you very actionable insights.

* Another big benefit that I found in my startup, is that cohort analysis naturally leads you to an intense focus on the consumer. If you are looking at a cohort of 100 users, these are actual live users. You start putting yourself in the user shoes. As a user, why am I coming back the next day but not the day after that? I sometimes like to drill down to even a single user (of course you want to be sensitive to privacy considerations here).

* You can compare cohorts. One common methodology is to compare cohorts of users who joined at different times. If one cohort is doing better or worse than another, it gives good actionable data to debug any problems or identify successes.

## What cohort numbers should you expect
When we started our company, we had little idea on what numbers to expect from our cohorts. After looking at our own cohorts and comparing them to others in the industry, I have come up with some rules of thumb.

If your cohorts are retaining more than 30% users after two weeks, congratulations! If you can also find a scalable way to acquire new users and eventually figure out monetization, you are going to be quite successful. As a point of comparison, RJMetrics did some great analysis on Twiiter and Pinterest and estimated this two week retention to be about respectively.

Graph with permission

If your cohorts are retaining less than 10% of users after two weeks, something is not really working. You should take a hard look at the product, is it something that the users really want? Are your users getting confused? These are tough questions but indispensable. The sooner you ask them the better your startup will be.

There is a big range of gray area between 10% and 30%. The number will vary with your target audience,

## How to estimate your competitor's engagement

Given how crucial engagement is, won't it be awesome to be able to estimate engagement of a company of interest? This could be your competitor, or a company that you are researching for investing. If there is any public user activity that is available, you can easily fake a cohort analysis by selecting a random set of users and then following their public activity with time. The greatest difficulty here is making sure your sample is not biased in any way. But even imperfect data is better than no data. One quick check that I have done in the past is to pick a few users from recent posts or likes and follow their activity backwards in time. If there are not too many users who have been active for a while, that is a sure indication of poor retention. Granted that this is not a very rigorous analysis but often gives quick gut check data.

## Other engagement metrics

<!--
You should be only looking at cohorts

-- Entrepreneurs common mistake

-- Pitfalls of othis metrics

-- what is a cohort

-- How is that helpful
* Actionable
* Drilldown
* Customer focus

-- Mixpanel/Kissmetrics (link to and tweet)

Anything from RJMetrics?

-- Distibution vs engagement (link to)

-- Othis related metrics like Daily actives/Monthly actives, churn rate

-- Common retention rates for FB, Pinterest, Twitter

Can we estimate retention rates for Pinterest etc

-------------------------------------------------------------------

http://500hats.typepad.com/500blogs/2009/09/startup-metrics-for-pirates-seedcamp-2009-sept-2009-london.html

http://www.avc.com/a_vc/2009/10/the-cohort-analysis.html



-------
web design
https://news.ycombinator.com/item?id=1503710
-->