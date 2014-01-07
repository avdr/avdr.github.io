---
layout: default
title: User actions and habit testing
---
# User actions and habit testing

### Outline notes
- User actions on a timeline
- Some actions are desireable from the company's point of view. Since each user comes at some acquisition cost, easy to see why habituation is so important
- We need to understand users but they are diverse. So its helpful to segment them and uderstand separately.
- One very useful dimension is how much is habituation.
- Typically useful to bucket into: uninterested, curious, habituated. They have different interaction lines.
- Collapse interactions lines into state diagrams and do funnel analysis. This can reveal bottlnecks
- Golden moment. Transition from curious to habituated. This can provide direction for new features. Re-engage with external triggers. Users are apathetic.


If you take each user and plot his actions on your product in a timeline you get something like the following figure. Time flows from the top to bottom. All users start with the action "start" indicated in yellow and continue to execute the different actions possible in the product.

Looking from the point of view your company, some of these user actions are more valuable. For instance, a desirable action could be an in-app purchase or an ad click. It could also be a non-monetary action like inviting a friend, curating some content, or any even which draws commitment or generates external triggers (see the hook model). In the timeline above, such desirable events are shown in green. How do we get more such events? One thing that is quite obvious from the timelines, is that the longer the timeline the more actions will be taken and in particular more of the desirable actions will be generated. Since user comes at some acquisition cost, it is much better to try to elongate the timelines rather than try to acquire lots of users with short timelines. This really drives home the point that the product lives or dies by its habituated users, something that the hook model strongly emphasizes.

To make sense of the myriad user timelines, it helps to segment the users into different buckets. While traditional segmentation around demographic lines is useful, for habit testing, it is crucial to divide the users into three classes:

1. *Uninterested*: These users somehow landed on the product but did not "get" it or do not care for it. As much as we would like to think that our app will change the whole world, the reality is that there will be a large class of users who will not be interested. In the timelines graph, these users will have the shortest timelines.

2. *Curious*: These users are intrigued by the app but not have given their full commitment. They may come back and try to figure out more of the app or they might just forget and be never seen again. These users have timelines of medium length.

3. *Habituated*: These are the users who understand the app, derive value from it and keep coming back. These are the most valuable users. Their timelines are theoretically infinite.

How do get more users to be habituated? We want to move the users from *uninterested* to *curious* and from *curious* to *habituated*. To understand the differences in th user behavior across the different segments, it is helpful to simplify and aggregate the user timelines. If you imagine aggregating timelines of similar users together and then collapsing common states in the form of a state machine, you get something like the following figure.

The state machine provides useful information. The weights on the edges of the graph indicate the percentage of users following that edge. This is useful in identifying potential bottlnecks. For instance, we notice in the above figure only 10% of the users proceed from initial information page to succesful registration. Perhaps this is indicative of some UX problem that is confusing the users on the information page. Further user testing on that page may turn up insights.

Looking at the state machines also reveals some key characteristics of each segments. Usually there are some milestones that users must cross to graduate from one segment to another. For instance, Twitter found that users stick around once they have followed at least 30 users. This insight was the reason Twitter decided to devote so much of their onboarding efforts to ensure that new users are following enough number of people. Identifying such "golden moments" in the life of the user are extremely valuable and should be used to drive the product direction.

## Summing up
