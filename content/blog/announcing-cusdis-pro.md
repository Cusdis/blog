---
title: "Announcing Cusdis Pro plan"
date: 2023-07-13
---

On an evening in April 2021, I started to write a commenting system for my blog, similar to Disqus. My goal was simple: to create a smaller and more easily integrated alternative to Disqus. I named it [Cusdis](https://cusdis.com), which is Disqus spelled backwards.

After just one week of coding, I opened the project to the public and posted it on Hacker News before going to bed. As usual, I assumed that the project would be ignored.

But in the middle of the night, my phone woke me up with notifications from many emails. I then realized that Cusdis had made it to the front page of Hacker News, and even the CEO of Vercel had tweeted about my project. The GitHub stars began to accumulate, and many people offered to contribute to the project.

The project was open-source, and I deployed a free version on Vercel for people to use. However, as the usage grew, I had to subscribe to Vercel Pro for $20/month and SendGrid for $20/month.

Fortunately, I also set up an OpenCollective to accept donations for the project, which currently provides enough funding to keep the project running for a while.

After that, I slowed down the development of Cusdis because I had a full-time job and did not have enough energy to continue. Although I had some ideas to implement, I could not devote myself to them.

Recently, I left my job and had more time, so I decided to continue maintaining Cusdis. A user messaged me on Twitter, saying that Cusdis met their needs, but they were not sure if the project was still being maintained. They offered to pay for using it. So, I decided to try to create a paid plan for Cusdis and see if I could turn it into a sustainable commercial project.

After redesigning the project and integrating a payment channel, I launched a $5/month paid plan. The free version has some limitations, such as 

  - Allowing only 1 site to be created
  - Approving up to 100 comments per month (which should be sufficient for small blogs)
  - 10 Quick Approve actions per month (which is convenient for approving comments on a mobile phone without logging in). 
  
However, for $5 per month, these limitations are removed.

If there are people willing to pay for using Cusdis, I will implement some of the features that I have been wanting to do for a long time, such as notifying the commenters via email when their comments are replied to and redesigning the comment widget, which currently looks too ugly. Another idea is to turn Cusdis into a Headless comment system, where users can customize their own widget. Ultimately, users will not need to use my dashboard.

For years, I didn't charge for using Cusdis, partly because I didn't have the energy and partly because I thought there were very few people willing to pay for a commenting system. But now, I want to try it out. There's no harm in trying.

Finally, as of July 13, 2023, here are some usage statistics for Cusdis:

- Total registered users: 5340
- Total comments: 20468
- Number of comments approved: 11381
- Total sites integrated: 6368
