---
layout: default
title: Why you should look at cohorts
---
# <span style="color:red">DRAFT</span>
# Why you should look at cohorts

Imagine that an entrepreneur came to you and showed you this graph.

<img class="iborder" src="/assets/users_growth.png"/>

You would think the startup is doing quite well, right? Well, it depends.

A common mistake entrepreneurs make is to focus too much on user growth. User growth is a necessary but not a sufficient condition for success. Often, a much more important question is: “Are you retaining the users you are acquiring?” Eventually, all user acquisition channels saturate. If the startup is unable to retain the users it acquires, the result is a hollowing out effect. It looks like a ring of fire expanding outwards. The fire burns out everything inside and the only activity that survives is at the edges.

<img class="iborder" src="/assets/brush_fire.jpg"/>

I learned this the hard way with our first product. This was a walkie-talkie app in which a user could record a short audio clip and send it to a friend. We saw good viral growth as users invited others. User retention, however, was not so great; people would be very excited initially but within a few weeks they would drop off. The end result was an app that was downloaded by millions but used by few after some months.

If the product is growing fast, it is too easy to forget retention. But to be successful, the product needs repeated usage which can only come by establishing a lasting habit in users' minds. Nir Eyal has some great ideas around this theme using a framework called [desire engine](http://www.nirandfar.com/2012/03/how-to-manufacture-desire.html).

Given the importance of retention, how do we track it? In my experience, the best way to do this is by measuring retention rate through [cohort analysis](http://cohortanalysis.com). Let us define these terms.

## Cohort Analysis

A cohort is a group of people who share a particular characteristic over a period of time. An example is a group of users who joined on a particular day.
A cohort analysis follows these users actions over a period of time.

## Retention Rate

Th retention rate of a cohort for a period of time is the ratio of number of active users at the end of the period to the number of active users at the start of the period. The definition of an active user is usually very specific to the product. For our purposes, a user is active on a given day if he or she has visited the product on that day.

Let us examine a concrete example by following two cohorts of 100 users, one cohort consisting of users who joined on January 1 and another who joined a week later on January 8.

Picture of a graph

The above graph shows that of the January 1 cohort, there were 100 visits on the day they joined, 90 a day later, 80 two days later and so on. The January 8 cohort did slightly worse, with 100 visits on the first day, but only 89 on the second day and 78 on the third day.

The same data can also be shown as a table:

Picture of a table

Cohorts can be used to track any metric of importance: app visits, number of shares, dollars spent, and so on. The cohort themselves can be grouped by any interesting characteristic: users coming from an ad channel, in a particular demographic, who have crossed some milestone in the app, etc.

Analytics platforms such as [Mixpanel](http://mixpanel.com) and [KissMetrics](http://kissmetrics.com) offer cohort analysis capabilities. There are also more specialized solutions such as [RJMetrics](http://rjmetrics.com).

## How is cohort analysis helpful?
* Critical data does not get drowned by external events. If you are just looking at the user growth, a mention by a blog may cause a huge spike in the user sign-ups but any pre-existing cohorts are not affected much.

* Cohorts give you actionable data. Why is the user retention weak? Could it be the onboarding? Do you need reminders to establish a consumption habit? By watching the cohort closely, you can get a good idea of what is going on in user's mind.

* You can compare cohorts. A common comparison is cohorts of users who joined at different times. If one cohort is doing better or worse than another, you can ask why.

* Cohort analysis naturally leads you to an intense focus on the consumer. If you are looking at a cohort of 100 users, these are actual live users. As you worry about this cohort, you start putting yourself in the user shoes.

* Keeps you honest. It is easy to drink your own kool-aid when you are experiencing heady user growth. Keeping a close eye on cohorts forces you to continue asking the right questions.

## What retention numbers should you expect?
When we started our company, I had little idea on what numbers to expect from our cohorts. After looking at our own cohorts and comparing them to others in the industry, I have come up with some rules of thumb.

If your cohorts are retaining more than 30% users after two weeks, congratulations, you can claim victory over the retention problem. For comparison with Twitter and Pinterest, RJMetrics did some great analysis and estimated their two week retention to be about _ and _.

Graph with permission

If your cohorts are retaining less than 10% of users after two weeks, the product is not working. You should take a hard look at the product, is it something that users really want? Are your users getting confused? These are tough questions. The sooner you ask them the better your startup will be.

There is a big gray area between 10% and 30%. The number will vary with your target audience.

## How to estimate your competitor's retention?

Given how crucial retention is, would it not be awesome if you could estimate that of a competitor, or a company that you are researching? If there is any public user activity that is available, you can approximate a cohort analysis by selecting a random set of users and then following their public activity with time. The difficulty here is making sure your sample is not biased in any way. But even imperfect data is better than no data. One quick check that I have done in the past is to pick a few users from recent posts or likes and follow their activity backwards in time. If there are few users who have been active for a while, that is a sure indication of poor retention. This is not a very rigorous analysis but often gives useful data.

## Other measurement methods
* Churn rate: this is the percentage of users who become inactive (churn out) in a period of time. Thus, a churn rate of 60% in two weeks means that two weeks after sign up, 60% of the users never come back.
* Ratio of daily active users to monthly active users. If there is good repeat usage, this ratio will be high as more of the daily active users will keep coming back.

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