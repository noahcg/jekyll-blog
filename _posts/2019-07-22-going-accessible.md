---
layout: post
title: "Going Accessible – Building an Inclusive First Design Team"
date: 2019-07-22 10:05:17 -0500
categories: inclusive
---

A few months ago I came across a blog post by [Ethan Marcotte][ethan marcotte] who is a web designer, writer, and speaker; if you don’t know who he is, I highly recommend you look him up. In his post he reminisces about an interview he listened to given by [The A11y Rules Podcast][a11y rules podcast]. The person being interviewed was [Liz Jackson][liz jackson] the founder of [The Disabled List][disabled list]. In Ethan’s post, he repeats a quote from Liz’s interview in which she mentions that her greatest frustration with accessibility is that people view it as a box to be checked. She elaborates a bit further ending with a wish that we could start viewing accessibility as an opportunity to engage. For some reason, that really struck me and I’m glad that I found Ethan’s post and that he quoted from Liz. That day I changed the way I think about accessibility.

That day I also came to a realization, I’m a terrible developer. Or at least I used to be. Not because I don’t know how to code or because I’m a bad teammate. I was a terrible developer because I was just trying to check a box, just trying to maintain compliance because I had to. Ever since having that revelation I am on a new mission. My goal is to help shape my current team into an inclusive first design and development team and to accessibly revamp what it means for the US Holocaust Memorial Museum to build digital products. This article will document the things I have done, and plan to do, in order to achieve this goal.

## Accomplished Thus Far

### Knowing is Half the Battle

To me, the most important thing I needed to do was admit that I don’t know enough about accessibility yet. I need to get educated on a huge array of topics. I’m tackling this in a couple of different ways including being a member and regular contributor to an A11y Slack board, following as many #accessibility advocates as possible on Twitter, enrolling in the full curriculum given by Deque University and eventually obtaining a Web Accessibility Specialist certification. I’m also going to be attending more conferences focused around accessibility and assistive technology.

The way I look at it, the more information I can gather the stronger the case my team can make for pushing this new approach. What I wasn’t prepared for was how much information there is out there. Even just trying to figure out where to start can be a daunting task. Every time I see a new question posted on Slack it only reaffirms the fact that I don’t know enough. On the bright side, at the same time, it’s pushing me to constantly keep learning and documenting.

By now, I have completely reorganized my Chrome bookmarks to help me keep track of everything I’m reading.

### Getting Approval from Management

Another hurdle that I can check off my list is getting buy-in from management. For me, that part wasn’t difficult and I consider myself fortunate. It was my director who came to my team shortly after I joined. She said that one of us needs to be the point person for making sure our products adhere to Section 508 and the WCAG. Being a new employee and wanting to show that I can be a team player, I offered to be that point person.

This is the first time I have ever worked for a federal institution. My entire career has been working in the private sector. None of my previous companies pushed accessibility so I naively never learned it. When I volunteered to be the point person I was nervous about if I was the right person for the job. Did I know enough to make sure our products were in compliance at a bare minimum? Even though I had my doubts I’m glad I stuck with it because this is important work. Focusing on accessibility for the last few years has changed how I approach development.

### Employee Engagement

I have also started an accessibility Slack channel at work that's open to all employees. I feel that we should have an open dialogue and it should be available to everyone. I’m not a big fan of private Slack channels. Mostly what I’ve been posting are news articles I find interesting, tweets from industry professionals and webinars I’ve been watching. With each webinar I register for, I send out a message to everyone offering them to join me. For those who can’t attend I try to upload all of the downloadable material or screen recordings to Google Drive.

Aside from using Slack and watching webinars, another way I engage other employees is by inundating them with anything I find interesting. Sometimes I’ll read something that stands out to me and I’ll just get up from my desk and walk into someone else's cubicle. I frequently walk around the office knocking on people's cubicle walls so I can mention an article I read or something cool I just saw. What can I say, I’m a fan of the “pop-in” (Seinfeld reference for anyone who gets it). My coworkers probably think it’s annoying.

## Challenges to Overcome

### Getting the Team on Board

One thing I never want to do is come across as a know-it-all and alienate my teammates. I want to make sure that when I approach them with this lofty goal of reshaping our approach I do it from an educated place. My teammates are all experts in their fields and their opinions about our work are just as valid as anything I’m going to present to them. I want to make sure that I convey the importance, not only of inclusive first design, but also of incorporating iterative accessibility development into our product lifecycle.

Some things I have to consider when approaching my team is how I want to present this information. Why should they listen to me? Who am I to ask them to change their approach? How do I get them to care about this as much as I do? Where do we even start?

There are a lot of questions I need to get answers to but as long as we start somewhere, it’s better than not starting at all.

### What About Non-Team Members?

Another thing I need to do is find out about coworkers who aren’t on my team. I need to find out who the key players are. Who can I get to be my allies? Is there anyone who could prevent me from making this a reality? Are there others who have an interest in accessibility and I just haven’t met them yet? At the museum, we have developers on multiple teams so I need to find out what they know too. Do they adhere to standards and guidelines? If so, is there someone who oversees that they do?

### Where is the Documentation?

Chances are, if your company doesn’t have current, updated documentation regarding their product accessibility policy then it will fall onto your shoulders to create them. Throughout my time here I have been creating and maintaining our documentation on the following: what section 508 is and why we are legally responsible for making our products accessible, WCAG 2.1 and ATAG 2.1 guidelines and what that means for the code we write, as well as resource links supporting the information in the documents.

Admittedly I’m a verbose writer, which may or may not be a good thing. I often struggle with the question of writing fewer, but longer documents, or separating the information out into many documents. I try my best to make sure that everything I write will answer as many questions as possible. I know that a lot of people like documents to be brief and to the point but that has just never been my style. I like to be thorough and all-encompassing.

## Auditing Current Products

I’ve been sharing all of my new found information with my manager and getting his take on it. He recognizes the importance of everything I’m trying to accomplish and I’m happy to say that he fully supports it. He has helped me get a project on our roadmap for conducting audits on all of our digital products. The full audit plan hasn’t been created yet as I’m still trying to document everything that our company needs to be in compliance with. And to take things one step further I have also started defining the difference between being in compliance and being accessible. The two are not synonymous. We need to be clear that we are doing a WCAG and ATAG compliance audit and not necessarily an accessibility audit. In order to conduct a true accessibility audit, we would need to reach out to users with disabilities, or work with a company like LevelAccess, to help us get the information we couldn’t otherwise obtain.

More than a year ago we started including Google’s Lighthouse auditing tool into our development process. If you haven’t checked it out yet I suggest you do, it’s a great product. There are other impressive accessibility audit tools that you can add as extensions to your browser as well. Deque has a product called Axe that will catch bugs and defects as well as check for compliance with WCAG and 508 standards. At the time of this writing, I also have the Arc Toolkit Chrome extension installed. It was developed by The Paciello Group and enables you to easily drill down into code-level issues and gain in-depth insight into the accessibility of the screen.

Down the line, I may look deeper into some applications that aren’t free. Deque and LevelAccess both have robust monitoring platforms that look interesting. Honestly, there are so many great tools out there it’s becoming hard to choose the best one for our needs.

## Getting Up to Speed

If you’re going to help build an inclusive first team then it’s going to take effort to get everyone up to speed and on the same page. Where I work, employees are encouraged to conduct what we call "brown bag training sessions". Most of us have the 12:00 p.m. block open on our calendars so we just book a conference room and send out an invite. Sometimes the training is just for the team, other times we may open it to the entire department or even to all museum staff. Regardless of who attends, since we’re taking up our coworker's lunchtime, everyone can bring their lunch and eat during the presentation. We have also started recording our sessions so anyone who can’t attend can still get the necessary information.

Upcoming training sessions I have on the roadmap include: writing proper semantic markup, designing with assistive devices in mind, designing for keyboard navigation, accessible javascript, and a demo of screen readers and how users with visual impairments hear the web. There will be plenty more but I’m starting with these few while I’m still in the planning phase of things.

## Tracking Our Progress

Building our team around this methodology is going to be an ongoing process. I’m not expecting any of us to get it right on the first try. We will certainly make stumbles along the way. It will be important for us to focus on why we’re doing this. Not just because we have to maintain compliance, but because of where we work. We don’t work for a B2B and we don’t increase a company’s profits. We are educators and the information we provide needs to be available to everyone. There should be no limitations to receiving an education and if that means I have to work a little harder then I will proudly do so.

I plan to document and track the progress we make with our transition to an inclusive first design team. I’m going to write more articles, message more people, and connect with more people on Twitter. Who knows, maybe it will inspire other companies, teams or individual team members to change things up where they work. A key thing to remember is that inclusive first doesn’t mean that only those with disabilities can use your product. It means that everyone can.

[ethan marcotte]: https://ethanmarcotte.com/
[a11y rules podcast]: https://a11yrules.com/
[liz jackson]: http://www.thegirlwiththepurplecane.com/
[disabled list]: https://www.disabledlist.org/
