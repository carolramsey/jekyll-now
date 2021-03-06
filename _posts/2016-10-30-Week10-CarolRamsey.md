---
layout: post
title: Week 10 from Carol Ramsey
---

**What did you do this past week?**

I finished reading the series of articles about design strategies and I wondered, where does the guy work and has he ever seen real world production code? The article's design strategies and patterns are elegant and powerful. The idea that developers should spend part of everyday refactoring is hopeful. 

Later the same day, I'm using End Note, a bibliography research tool, and I can see the bad design from the other side of the UI. The client app handles multiple libraries, but in the web app the user must create multiple user accounts, one for each library. Then there is the manual configuration that requires values like http://ezproxy.lib.utexas.edu/login?url= and http://te7fv6dm8k.search.serialssolutions.com. The relationship between Groups and Group Sets is unique and mysterious and why should organizing folders and tags, with well established best practices and patterns, ever be unique or mysterious?

Then, I forget my password. (That is not uncommon, even though I use 1Password. Don't ask me to explain that.) So, I'm entering my new password and then I start to enter the answer to my security question, "J..." and the app offers to complete the field for me with my Mom's maiden name. It seems that End Note had saved my security question answers in a cookie. 

Now, I am not worried about someone breaking into my End Note account and stealing my list of references articles for my next research paper. But, the app uses the most common security questions that can't be changed. It is unsettling to see auto-complete for the same security questions used by my bank. 

Back to the readings. From what I can see through the UI, I am confident that the developers at Thomson Rueters are not using design patterns or refactoring inelegant code. I can imagine who they are. They are an IT shop. Their background is in mainframe publishing systems. The app was initially designed long ago and it's too late to fix it now. 

If End Note is bad software, that isn't going to cost the company millions or kill anyone, but what about when the software operates a spacecraft or medical devices? The <a href ="https://www.technologyreview.com/s/401594/why-software-is-so-bad/">impact of bad software</a> has been well documented. 

I believe that the top software companies, hiring the best developers, working on new code, when market timing and competition allows, are writing excellent software consistent with the articles we have read. For the other 90% of the software, I don't think these articles apply. They aren't even close. 

It will be interesting to watch how the software industry matures over time and if higher quality software wins out over other business drivers. I would be more hopeful if the industry hadn't been struggling with this for most of its existence and if the answer hasn't always been the same. 

**What's in your way?**

I'm writing this at 4:30am. Time. I need more time.  

**What will you do next week?** 

I am going to get a 10 on a quiz if its the last thing I do. 

**Tip of the Week**

When using End Note, references in the library can be added to one or more Groups. Each Group is part of a Group Set. "My Groups" is a Group Set that is created at installation and can't be deleted.  You can create up to 500 Group Sets and save an unlimited number of references, but you can create only 2 levels of organization, the Group Set and the Group. 

When I see something like this in a UI, I imagine the design mistake behind it. In this case, I imagine that instead of one folders DB table with each row/folder having an ID field for the parent folder (a standard implemention used by DOS in the late 80s, right?), there are two DB tables, one for Groups and another for Group Sets. I imagine that the 2-level organization is embeded and hard-coded from the database all the way through to the UI. It is clear that the program isn't using a UI framework, because this and a few other UI pieces couln't be implemented with standard widgits. This is a sign that the level of hard-coded specifics vs. abstrated layers is far off in the wrong direction. I imagine the Product Manager asking for a typical n-level folder structure and the Tech Lead saying that would cost too much and the Tech Lead would be right. 

Is this is helpful tip or a weird habit, to imagine the design flaws through the lens of the UI? Maybe it's some of both. 


 
