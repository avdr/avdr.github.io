---
layout: default
title: User actions and habit testing
---
# User actions and habit testing

<link rel="stylesheet" type="text/css" href="style.css" />
<script src="d3.v3.min.js"></script>
<div class="graph"></div>
<script src="timeline.js"></script>

If you take each user and plot his actions on your product in a timeline, you get something like the following figure. Time flows from the top to bottom. All users start with the action "start" indicated in yellow and continue to execute the different actions possible in the product.

Looking from the point of view your company, some of these user actions are more valuable. For instance, a desirable action could be an in-app purchase or an ad click. It could also be a non-monetary action like inviting a friend, curating some content, or any even which draws commitment or generates external triggers (see the [](hook model)). In the given figure, such events are shown in green. How do we get more of such events? One thing that is quite obvious from the timelines, is that the longer the timeline the more actions will be taken and more of the desirable actions will be generated. Since user comes at some acquisition cost, it is much better to try to elongate the timelines rather than try to acquire lots of users with short timelines. This really drives home the point that the product lives or dies by its habituated users, something that the hook model strongly emphasizes.

To analyze the timelines, it helps to segment the users into different buckets. While traditional segmentation around demographic lines is useful, for habit testing, it is crucial to divide the users into three classes:

1. *Casual*: These users somehow landed on the product but have not yet “gotten” it. As much as we would like to think that our app will change the whole world, the reality is that there will be a large class of users who will be casual. In the timelines graph, these users will have the shortest timelines.

2. *Curious*: These users are intrigued by the app but not have given their full commitment. They may come back and try to figure out more of the app or they might just forget and be never seen again. These users have timelines of medium length.

3. *Habituated*: These are the users who understand the app, derive value from it and keep coming back. These are the most valuable users. Their timelines are theoretically infinite.

How do get more users to be habituated? We want to move the users from *casual* to *curious* and from *curious* to *habituated*. This is where [](habit testing) framework becomes really useful. We first identify the habituated users by their long timelines. First, we make a reality check. If the percentage of habituated users is less than 5%, the product is not really working and we should go back to the drawing board.

Studying the timelines of habituated users can often reveal key milestones that such users have crossed. These milestones are indespensable in driving new features and the product direction. If we can design our product to provide more opportunities for users to cross these milestones, more of them are likely to get habituated. For instance, Twitter found that following at least 30 people is crucial for users to stick around. They used this knowledge to change the way new users are onboarded to ensure that users follow enough people.

Sometimes timelines reveal that a lot of users stop at a certain step. This may be an indication of user confusion. We can do funnel analysis to identify sharp drop-offs and change the product design accordingly. This analysis is especially useful for the onboarding process for new users. This can help in getting more users to graduate to the *curious* bucket.

## Summing up
Segmenting users by their degree of habit forming should be part of the product design process. Looking at the user timelines, identifying key milestones, doing funnel analysis, lead to more informed product decisions and more users getting habituated to the product.