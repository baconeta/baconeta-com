---
title: "My boldest game jam challenge so far."
description: "A discussion of my experience leading a team through ludum dare 51 held in October 2022 online, making a game in just 72 hours, and more."
date: "2022-11-18"
banner:
  src: "../../images/18112022/img0.png"
  alt: "Discussing a recent game jam experience"
categories:
  - "Production"
  - "Ludum Dare"
  - "Game Jam"
keywords:
  - "producer"
  - "development"
  - "process"
  - "ldjam"
---

## Background
One autumn weekend just a few weeks ago, I produced a game. And not just any game, but maybe the most ambitious game jam game so far. Long story short, it went quite well. 
But it also was not without its share of successes, and failures, along the way.

I have been a part of the previous 5 ludum dare game jams. Every time we get involved, our team grows bolder, and sometimes bigger. Well, this time was not our biggest, but it certainly was our boldest.
Even just at the tail end of ludum dare 50 back in April, I already knew exactly where I wanted to improve and optimise the experience. 

For the previous two jams before this one, I had organised, and facilitated everything. From getting the people together, to streamlining the decision-making process (another long story), and
continuously making sure we were culling just the right number of features each successive hour to ensure we finished in time. I knew years ago that I wanted to produce video games, and what better experience
could I get (short of working in the field), than producing one right here, in just a weekend.

Producing even a game jam proved to be a monumental task. I mean, it's super fun, but always huge. This is partially due to the timezone differences between the entire team, plus the different levels of motivation and experience. Creating a game in 72 hours is not easy.

## Preparation
*"It's Corn"*

In the few weeks leading up to the event, things become to take shape. I have a lot to organise and keep track of to make sure that I, and everyone who volunteers their weekends to such a good cause,
has the best possible experience. 

The To-Do list looked something like:
- **Check in with anyone who was previously involved, and see if they want to be involved again.** This is more difficult than you might think, so it often involves reaching out to everyone individually fairly well in advance.
- **Scope out potential candidates for newbies to get involved.** This is super important to me - I want more people to experience the joys of creating something so quickly and in such a casual but exciting way, and I also want to give people the opportunity to do what I did - coming from a place of virtually no experience and making something they can be forever proud of.
- **Plan the tech stack we will use.** This time, a good friend and I decided we wanted to go deeper on the scoring side of the games, due to having a local only high scores system in ld50. So this involved researching, and putting together a fully functional but simplistic web server that could handle simple database management and high score saving/loading for global high scores. Shout out to James for his amazingly hard work getting things up and running.
- **Prepare the planning tools.** Well, this wasn't so hard but involved preparing a collaborative whiteboard and a trello board for task management, making sure everyone had access to it, getting the team verified together on ldjam.com, setting up the discord server and channels for the weekend and so on.
- **Check in once again with each member about schedules** and rough manpower evaluations a week before the event.
- **Make sure all my meals and food was planned** and my fridge was full of energy drinks and milk for coffee.

![trello board prep](../../images/18112022/img6.png "A small snippet of the final trello board column...everyone's favourite - bugs!")

For this event, we also had an amazing artist who had always wanted to get involved with making a game but never had the opportunity. An avid gamer, but first time game artist, she was brilliant, but also we did some preparation work there to make sure all the right pieces were in place for that (including asset folders, content management and so on).

We also developed an unholy obsession with the "[it's corn](https://www.youtube.com/watch?v=_caMQpiwiaU)" kid and the song that came from that. I don't know why, we just did. More on how that entered the game later.

![miro pre plan process](../../images/18112022/img7.png "We pre-planned a few of the potential themes in advance")

Oh, and a particular focus this jam was on mobile playability. So that influenced a lot of UI/UX and design choices (lots of new learnings here too).

## Jam time - Day one
The weekend came around super quickly, and the week of voting ended with the announcement of the theme at 1am in my timezone.

**"Every 10 seconds"**

_Sigh_. It was about everyone's least favourite of the possible themes. But we immediately got cracking into our Miro whiteboard and brainstormed for 30 minutes.

![miro speed theme ideas](../../images/18112022/img8.png "Speed round theme ideas")

Eventually we put our pens down and started chatting - eventually diving deep into the idea of a forest that changes between day and night, and this occurs every 10 seconds.
We already had considered the possibility of a rogue lite / hack 'n slash style game so merging that idea with the target genre was not so difficult…

Then we got to work.

#### Me, myself and 3am production mode

A huge part of my role on day one was about making sure we were making significant progress, and that everyone had tasks to do at all times.
Of course, this is not a job, people could come and go as they pleased - but everyone knows the first 12 hours are the most vital and also about the most significant. Maybe not the most fun though.

I felt during this whole procedure while preparing scenes, assets, tasks and making sure everyone was firing on all cylinders, that I had failed.
There was never a dull moment for me, but I would have loved to have been able to get our newbie quickly on the board with a task. I struggled here though, and I really let them down.

I also would love to have been able to go one by one through everyone cyclically (there was seven of us in total) and make sure everyone knew what they wanted to do. I spent a lot of my time ensuring that our
ideas and early developments were all lining up, and not enough time on ensuring that everyone was equally able to contribute. 

It might be less that I failed, and more that I learnt a lot from this first few hours. 
I'll come back to reflecting deeper on this in another blog post.

I went to sleep at around 5.30am and let the team do what they do best.

## The rest of the development

I won't go into a lot of detail for the rest of the jam process, but I will share some highlights, snapshots and progress, in a sort of montage-y fashion.

<img src="https://i.imgur.com/cizwOES.gif" style="width:100%"  alt="The very first progress gif we took."/>
<figure class="gatsby-resp-image-figure" style=""><figcaption class="gatsby-resp-image-figcaption"><p>The very first progress gif we took</p></figcaption></figure>

![first mid game interface image](../../images/18112022/img1.png "First mid game interface image")
<img src="https://i.imgur.com/PU1rrHA.gif" style="width:100%"  alt="... and it's first implementation."/>
<figure class="gatsby-resp-image-figure" style=""><figcaption class="gatsby-resp-image-figcaption"><p>... and it's first implementation.</p></figcaption></figure>