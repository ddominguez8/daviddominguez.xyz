---
layout: post
title: WWW - Countersurveillance Fellowship Reflection
date: 2026-06-04
tags: [random]
permalink: /blog/whowatcheswho
---

### Finding the fellowship
---

I think I was just doomscrolling at home one night when my girlfriend had pointed out this fellowship by the AjA Project, one with a caption "Who Watches Who! Countersurveillance Fellowship to learn how surveillance policies + technologies impact our communities". I felt like I had been semi-aware already of what goes on from an online perspective, but not so much on how it affects communities locally in San Diego. I currently reside in a community where a majority are Black and Brown, a lot of Mexican, Haitian, Ethiopian, and Vietnamese people all stay. Where a lot of the shops are independently owned, by a family you'll end up knowing by name and knowing some of their life story after enough visits.

More than anything, I wanted to know how these people who I've lived alongside and gotten to know, are affected by surveillance technologies in the area. I have read a few books on the topic, including [_Abolishing Surveillance: Digital Media Activism and State Repression_](https://openlibrary.org/works/OL28737949W/Abolishing_Surveillance?edition=key%3A/books/OL39440044M) as well as [_Walls Have Eyes: Surviving Migration in the Age of Artificial Intelligence_](https://openlibrary.org/works/OL37588369W/Walls_Have_Eyes?edition=key%3A/books/OL50658207M), so I am aware from a broader movement/global perspective as to how communities are affected, but nothing locally, which intrigued me.

I submitted an application the same night, going through and explaining how I know a lot of the intricacies of how tech works as a whole, and confidently have the ability to break it down for others to understand, digest, and learn, and how I aim to not only receive the information, but also learn on what type of information would be most relevant to share to others in our area.

### During the fellowship
--- 

Luckily, I was selected for the fellowship! I was now one of the fellows part of a 10 week program to learn more and eventually create a community art piece designed to educate and challenge surveillance in our local San Diego area. 

Throughout the fellowship we did a lot of activities as a group, always in person at a local coffee shop, that also has a back area that is an empty fridge space, holding some artwork for the public to come and view. 

Anyways, some of the key activities we did that had a major impact on me were: 

__Journaling__, this one I always forget how impactful it is to just write your raw feelings down. At the first session, we were given blank, white small journals, meant to document some of our learnings and how we were feeling at various points in time. I tended to just get random ideas and doodle while we were in session. Not out of disrespect, mind you, mostly because that's what the journals were meant for, I wanted to make sure I could visually represent how I was feeling, in addition to the words on the pages. 

__Defining Surveillance and Countersurveillance__, where the facilitator let each of the fellows explore what the meaning of surveillance and countersurveillance meant to each of us. We came up with multiple definitions, revolving around different ways to define them, some focused a lot on the border (San Diego is a largely border town so there is a lot of surveillance that is in place by organizations such as ICE and DHS). 

__Exploring Artists__, where the facilitator would show art from a variety of artists within the San Diego area and broader, some who speak directly on surveillance through their art. The whole objective was to get us to start thinking on how we were going to approach our final art pieces. These final art pieces were to be shown to the general public via an exhibition.

__Speaking Up__, where we each would share specific experiences about being surveilled within our community. I used to walk to the coffee shop where we would have the sessions, and one time I just got curious as to how many cameras were on the path from my home to the coffee shop. I don't remember the exact number anymore, I think it was in the realm of like 20-30 ish cameras within a 1 mile radius. One specific 3 car parking lot (very small) had like 5 cameras, all different brands, presumably owned by different shops, observing the _same_ parking lot. None of them really gained any additional angle or advantage. 

We also were encouraged to attend [Privacy Advisory Board](https://onboard.sandiego.gov/board/4526) meetings, where we would voice our opinions on specific technologies that were actively being reviewed. The Privacy Advisory Board is designed to "provide advice and technical assistance to the City of San Diego on best practices to protect resident and visitor privacy rights...", so they represent the citizens and need to be able to support us when new surveillance technologies are attempting to be implemented in our communities.

### My Art 
---

As I spoke a bit about in the prior section, we all developed our own art pieces. My art is a collection of four pieces of code revolving primarily around the theme of how a lot of these surveillance companies have very pretty UIs, fancy websites, and very functional. But in reality, I want to challenge people to think about _how secure is the data these companies are holding_? From a technical standpoint, each piece contains some level of vulnerable code to reinforce this message. I did not use any AI to build the raw code, as I wanted the mess to be part of the piece. 

I'll leave them here for reference and allow you to review them in more detail.

![david-code-1](/assets/images/www/david-code-1.svg)

![david-code-2](/assets/images/www/david-code-2.svg)

![david-code-3](/assets/images/www/david-code-3.svg)

![david-code-4](/assets/images/www/david-code-4.svg)

I'm especially fond of the last piece, as this was a crazy last minute 2am idea I came up with. I'll lightly go through the technical details for this one specifically, but for context I'll just highlight the vulnerability for the others: 
1. encoded base64, not inherently bad but the lack of transparency is the highlight. In the full script it actually downloads an [eicar file](https://en.wikipedia.org/wiki/EICAR_test_file) 
2. unsanitized input, vulnerable to command injection 
3. similarly, unsanitized input, vulnerable to sql injection
4. For this one I was able to learn some basic Terraform so I could do a few things. It stands up a storage account and a container, and leaves the access open publicly intentionally, where I planted a text file. On the final version of this (and the one that is at the gallery today) there is a QR code as well for folks to directly read the files from their phones.

And proof :D 

![az-ddx](/assets/images/www/storageaccddx.png)

### Close Out
---

I'm extremely grateful to all the other fellows, the facilitator, and the AjA project for giving me an opportunity to be part of something so special. This program holds a very dear place in my heart and I will continue to maintain an active presence in the community and support (hopefully more once I'm walking!)