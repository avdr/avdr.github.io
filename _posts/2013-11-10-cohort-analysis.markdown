---
layout: default
title: Why you should look at cohorts
---
# <span style="color:red">DRAFT</span>
# Why you should look at cohorts

Imagine that an entrepreneur came to you and showed you this graph for an app we will call PinterestForDogs.

<img class="iborder" src="/assets/users_growth.png"/>

You would think PinterestForDogs is doing quite well, right? Well, it depends.

A common mistake entrepreneurs make is to focus too much on user growth. User growth is a necessary but not a sufficient condition for success. Often, a much more important question is: “Are you retaining the users you are acquiring?” Eventually, all user acquisition channels saturate. If the startup is unable to retain the users it acquires, the result is a hollowing out effect. It looks like a ring of fire expanding outwards. The fire burns out everything inside and the only activity that survives is at the edges.

<img class="iborder" src="/assets/brush_fire.jpg"/>

I learned this the hard way with our first product. This was a walkie-talkie app in which a user could record a short audio clip and send it to a friend. We saw good viral growth as users invited others. User retention, however, was not so great; people would be very excited initially but within a few weeks they would drop off. The end result was an app that was downloaded by millions but used by few.

If the product is growing fast, it is too easy to forget retention. But to be successful, the product needs repeated usage which can only come by establishing a lasting habit in users' minds. Nir Eyal has some great ideas around this theme using a framework called [desire engine](http://www.nirandfar.com/2012/03/how-to-manufacture-desire.html).

Given the importance of retention, how do we track it? In my experience, the best way to do this is by measuring retention rate through [cohort analysis](http://cohortanalysis.com). Let us define these terms.

### Cohort Analysis

A cohort is a group of people who share a particular characteristic over a period of time. An example is a group of users who joined on a particular day.
A cohort analysis follows these users actions over a period of time.

### Retention Rate

Th retention rate of a cohort for a period of time is the ratio of number of active users at the end of the period to the number of active users at the start of the period. The definition of an active user is usually very specific to the product. For our purposes, a user is active on a given day if he or she has visited the product on that day.

Let us continue with our example product, PinterestForDogs. We will measure the retention rate for two cohorts of 100 users, one cohort consisting of users who joined on January 1 and another who joined a week later on January 8.

Picture of a graph

The above graph shows that of the January 1 cohort, there were 100 visits on the day they joined, 90 a day later, 80 two days later and so on. The January 8 cohort did slightly worse, with 100 visits on the first day, but only 89 on the second day and 78 on the third day.

As you can see from the above example, the retention rate decays with time. The graph starts flattening in a few weeks and eventually plateaus. This final level consists of users that have become *hooked*: they have established a habit pattern to keep coming back to the product. These are your most interesting users.

Analytics platforms such as [Mixpanel](http://mixpanel.com) and [KissMetrics](http://kissmetrics.com) offer cohort analysis capabilities. There are also more specialized solutions such as [RJMetrics](http://rjmetrics.com).

## How is cohort analysis helpful?
* Critical data does not get drowned by external events. If you are just looking at the user growth, a mention by a blog may cause a huge spike in the user sign-ups but any pre-existing cohorts are not affected much.

* Cohorts give you actionable data. Why is the user retention weak? Could it be the onboarding? Do you need reminders to establish a consumption habit? By watching the cohort closely, you can get a good idea of what is going on in user's mind.

* You can compare cohorts. A common comparison is cohorts of users who joined at different times. If one cohort is doing better or worse than another, you can ask why.

* Cohort analysis naturally leads you to an intense focus on the consumer. If you are looking at a cohort of 100 users, these are actual live users. As you worry about this cohort, you start putting yourself in the user shoes.

* Keeps you honest. It is easy to drink your own kool-aid when you are experiencing heady user growth. Keeping a close eye on cohorts forces you to continue asking the right questions.

## What retention rate numbers should you expect?
The retention rates naturally vary by the industry. An e-commerce application that is able to monetize users well can probably live with much lower retention rate than a free social networking app that needs millions of active users to be interesting. The following numbers are applicable to mobile or web apps in the social networking/sharing space.

The number that I look at is the retention rate at the final plateau of users who are hooked. In the space that I am interested in, typically, 4 weeks is enough to establish the plateau level. After 4 weeks, if your retention rate is more than 20%, congratulations, you are done.  To compare these numbers for two successful companies in this space: Twitter and Pinterest, RJMetrics did some analysis and estimated their 4 week retention to be about _ and _.

Graph with permission

If your cohorts are retaining less than 5% of users after 4 weeks, the product is not working. You should take a hard look at the product. Is it something that users really want? Are your users getting confused? These are tough questions. The sooner you ask them the better your startup will be. If we look at the plateau retention rate of our example, PinterestForDogs, we see that it is only 3%. This implies that it is unlikely to succeed, even though the first graph of user growth looked great.
