---
layout: post
title:  "12 Years of Email"
date:   2015-10-18
categories:
---
# 12 Years of Email

A few years ago when I was working in a nonprofit co-working/maker space in California called the [Hacker Dojo](http://hackerdojo.com) I had a brief chat with another person working there. He was an Australian who had recently moved to the Bay Area. We exchanged the usual, vapid, Bay Area pleasantries: what start-up are you working on? etc. When he asked what I did, I told him I was actually a gainfully underemployed adjunct professor, doing a bit of research and consulting here and there (in hindsight, a handy euphemism for post-Ph.D. burnout and recovery). His response was: "oh, you must send a lot of emails". I shrugged, "Yeah, I guess so".

Since then, I've wondered a bit about my email habit and whether it's changed appreciably over the years. For instance: is it true that my job is (or was) largely about sending emails? If so, how do I feel about that? Are the quantity of emails I send or receive positively or negatively related to my productivity?

One day a few months ago, I started poking around my email data. Since I switched to Google for email in 2011, I was able to easily request and download the entire 5.6 GB of email data that Google has been holding on to for me. I augmented that data with an additional 3.5 GB of data that I had kept from when I ran my own email server and hosted my email (yes, I'm that kind of nerd). After a bit of work to synthesize the data, I have nearly 9 GB of emails which constitute the non-spam portion of all my email communications since sometime in early 2004.

I have to admit, as I started analyzing the data, I felt a bit strange about it. It was a pleasant project because it is a fairly large and interesting data set that also has personal meaning. Meanwhile, it also felt very odd to dissect my own communications, even in the aggregate. I was reminded of the simultanous excitement and repulsion of dissecting [owl pellets](https://en.wikipedia.org/wiki/Pellet_(ornithology)) in an early science class. Mostly, it just felt frivolous. On the other hand, I was emboldened by the amusing posts of a fellow CS professor who summarizes [his year in numbers](http://www.cs.unm.edu/~aaron/blog/archives/2014/12/2014_a_year_in.htm). And, ultimately, I decided to embrace the weirdness and allow myself a strange project. Doing so *has* taught me something about my own habits and presents an interesting perspective on my last 12 years. I'm glad to have done it and thankful that the Google data overlords still allow me to download my own data (certainly not the case for most companies). So here it is:

![All email since 2004](/images/email/all.jpg)

This first plot shows the number of emails sent and received per week, excluding spam, since 2004. Amidst spikes and gaps in the timeseries, there is a substantial increase in email sent and received in the middle of 2006. 2006 was the year after I got my undergraduate degree. That year I started doing research in a laboratory at [PSU](http://pdx.edu), did work for several organizations as a contractor or employee, and applied for graduate school. Also, while I had been involved since sometime in 2005, in 2006 I did a lot more work as a volunteer for the [Personal Telco Project](http://personaltelco.net), which both informed my later involvement in nonprofits and motivated much of the research in wireless networks that I would do in the coming years.

![Life Events v.s. Email](/images/email/events.jpg)

The second plot focuses on the period of time since 2010 and tries to call out some main effects. In the Fall of 2010, *A*, is when I returned to the US after four months in New Zealand. The gap at *B* is the three weeks that I was in Guatemala, visiting Becky and traveling around Central America. The increase after *B* is largely email to/from Becky when she and I were reuinited in Colorado. The huge spike at *C* is the Summer of 2012, when I was most actively managing [Boulder Food Rescue](http://boulderfoodrescue.org), living in a hammock, and riding my bike all the time. The ramp leading up to it is the period of activity during the first year while we were starting that nonprofit (also, a period of time where I was teaching and finishing my thesis). The gap at *D*, and the massive decrease that follows, is the period of time when I was moving to California and bike touring across Colorado, Utah, and Arizona. The small spike at *E* is when [Falling Fruit](http://fallingfruit.org) started to get a lot of press. The gap at *F* is the weeks I was living in the high Himalaya and doing research. The spike at *G* is May 2014, when I was working on the [crowdfunding campaign](https://www.barnraiser.us/projects/fallingfruit-org-mobilize-the-urban-harvest) for Falling Fruit's mobile application. Finally, the gap at *H* is the weeks I was bike touring with Nora and Sienna from San Francisco to the San Juans in Washington. The composition of the communication has also changed quite a bit with time. I made a [simple animated treemap](/folks2.html) to visualize the change in senders over time. My relationships, major collaborations, and a number of life events are also visible through that view of the data.

Since the beginning of 2015, there seems to be a decreasing trend, particularly in sent mail, which I assume is because my email at work is no longer included here. To understand how the total volume of email I've sent and recevied has changed over time, the following four plots provide daily sums (which are quite noisy) and a polynomial fit line, and monthly sums, with a linear fit line:

![Received by Day](/images/email/recv_day.jpg)

![Sent by Day](/images/email/sent_day.jpg)

![Received by Month](/images/email/recv_month.jpg)

![Sent by Month](/images/email/sent_month.jpg)

Using this view, it is clear to see that there is an increase in aggregate mail over time. In 2004,
I was sending and receiving between 2 and 3 emails per day. By 2007, I was receiving 22 emails per day
on average and sending 11. In 2012, the peak of my email activity in the last 12 years, I was receivng
58 emails per day on average and sending 20. This year, so far, I've received on average 48 emails per day
and sent 10. The following table summarizes the annual statistics.

{% include misc/email_table.html %}

So, do I send a lot of emails? Undeniably, yes, but it's relative. According to a bit of research available online [here](http://www.radicati.com/wp/wp-content/uploads/2013/04/Email-Statistics-Report-2013-2017-Executive-Summary.pdf) and [here](http://www.radicati.com/wp/wp-content/uploads/2011/05/Email-Statistics-Report-2011-2015-Executive-Summary.pdf), the number of business related emails is growing worldwide at a rate of about 7-8%, while non-business emails are staying steady or decreasing by as much as 3-4% per year. The claim seems to be that the reduction in personal email use corresponds to an increase in other forms of communication (text messages, online social networks, etc.). This seems like a reasonable explanation to me. In a business context, the typical person receives 58 (non spam) emails per day and sends 33.

In 2012, Fortune magazine [editorialized that email is a plague on business productivity](http://fortune.com/2012/10/08/stop-checking-your-email-now/). While I don't generally consume my analysis from Fortune magazine, I do think this article well articulates the common perception that email is a productivity sink. In analyzing my own email activity, what I've discovered is that while that may be the case for some fraction of my email, when taken in the aggregate, the spikes in my email correlate with periods of (professional and social) activity that I'm generally happy about. Email has been a primary function of my professional and social life for some time. Maybe it's because of my awkward position as a [boundary milennial](http://www.nytimes.com/2015/02/05/opinion/wait-what-im-a-millennial.html), or my profession. Nevertheless, I'm not sure I regret that time spent, particularly the positive email-facilitated process of organizing people (e.g., BFR's 150+ active volunteers), collaborating on projects (e.g., the spikes of communication with research collaborators, or memberships in email lists for open source software projects) and maintaining relationships, sometimes at distance (e.g., increased email activity with my partner when we are apart). I'm not sure there is another form of communication that would so easily enable these things. I guess I'm okay with email. Probably I even like it.
