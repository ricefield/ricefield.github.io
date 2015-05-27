---
layout: default
title: "Projects"
featured_image: /images/cover.jpg
---

## Projects
---

### Code

* [Bibles for America](#bfa)
* [Attendance Project](#attendanceproject)
* [CalChat](#calchat)
* [hymnalAPI / rcvAPI](#apis)
* [Blind.ly Messenger](#blindly)

### Design

* [Verse Cards](#versecards)
* [Christians on Campus](#coc)
* [Saratoga Falcon](#falcon)
  
<br>

---

## Code

<span id="bfa"></span>
### Bibles for America

[Bibles for America](http://bfa.org) (BfA) is a Christian non-profit whose goal is to distribute the Word of God and Christian books to believers across the country. During my time at BfA, one of my main projects was a rewrite of the [BfA website](http://biblesforamerica.org). The original website was built on Wordpress, using a variety of plugins for e-commerce, multilingual, and blogging/SEO. Unfortunately, this was causing BfA a lot of problems: difficult bugs, slow site performance, and a large hosting bill. 

Inspired by the success the [Obama campaign had with static sites](http://kylerush.net/blog/meet-the-obama-campaigns-250-million-fundraising-platform/), as well as [Development Seed's usage of Jekyll for healthcare.gov](http://www.theatlantic.com/technology/archive/2013/06/healthcaregov-code-developed-by-the-people-and-for-the-people-released-back-to-the-people/277295/), I proposed we also try converting our problematic Wordpress site into a Jekyll-driven static site. Less than a year later, we launched a fully static version of [biblesforamerica.org](http://bfa.org), resulting in a 75% reduction in load time and bringing out monthly hosting costs down to less than a dollar.

**[2014 Year in Review](http://bfa.org/2014)**  
Another major project I enjoyed working on at BfA was our first-ever annual review minisite. It was my first time working a purely presentational website, and I learned a lot working with the designers and writers in producing a scrolling website to be used as promotional material. You can take a look here: [BfA 2014 Year in Review](http://bfa.org/2014)


<span id="attendanceproject"></span>
### Attendance Project

In Fall 2012 I enrolled in the [Full-time Training in Anaheim](http://ftta.org) (FTTA), a 2-year Bible truth and church service training program based in Anaheim, CA. As part of my program, I was assigned to various services, one of which was the [Attendance Project](https://github.com/attendanceproject/djattendance), an internally developed and maintained web application used by all the trainees and training administrators to mark attendance, process leave slips, enter exam scores and grades, assign weekly services, and handle other administrative functions.

The project was in it's 10th year of development when I joined the team, and had accumulated contributions from many programmers passing through the program year after year. While mature and feature-rich, the project's age was becoming problematic for the team, as lack of documentation and a messy, old codebase made bug-fixing difficult, leaving little time for new feature development. 

After some deliberation with current and former team members, as well as the administration, we made the decision to start with a blank slate, rewriting the app from the ground up using more modern technologies and workflow. As former team lead and a primary contributor, I've continued to be involved with planning the project roadmap, gathering requirements and specs, training new developers, coordinating a distributed team of contributors, and of course, coding. The project is open-source and available on [GitHub](https://github.com/attendanceproject/djattendance).

<span id="calchat"></span>
### CalChat

In my last semester at Cal, my friends [Jesse Chen](http://jessechen.net), Nelson Hoang, and I decided to enter a hackathon hosted by the [UC Berkeley Student Technology Council](http://stc.berkeley.edu/) (STC). We used the occassion as an opportunity to learn NodeJS, which we had never worked with before. Despite a hastily assembled demo, we managed to [place third in the judging](http://stc.berkeley.edu/competitions/code-4-cal/2011-2012).

Later that semester, we decided to enter the STC's Web App Competition and invited our friend Mark Wei to join our team. Over the course of a month, we rewrote our entire app (still in Node) and submitted it to the competition, [winning both the Grand Prize and the People's Choice Award to take home a combined $4000](http://stc.berkeley.edu/competitions/web-app-competition/2011-2012). 

You can see our app live at: [calchat.net](http://calchat.net) and our competition pitch deck on [SpeakerDeck](https://speakerdeck.com/ricefield/calchat).

<span id="apis"></span>
### hymnalAPI / RcVAPI

These were two fun projects I worked during the winter of 2013, mainly as a way to play around with Ruby and Sinatra. Both [hymnal.net](http://hymnal.net) and [recoveryversion.org](http://online.recoveryversion.org) are websites my friends from church and I use often to look up songs or Bibles verses. Unfortunately, hymnal.net lacks an official API, and I found recoveryversion.org's unwieldy. Since I know of a few others who had independently written scrapers to get the data into databases and/or mobile apps, I thought it would be a good exercise to write a common interface to retrieve the data. Sinatra ended up being a great microframework for writing simple web APIs, and for a first Ruby project, it was simple and helped me get comfortable with the language. You can view both projects on GitHub: [hymnalAPI](https://github.com/ricefield/hymnalAPI) / [RcVAPI](https://github.com/ricefield/RcVAPI).

<span id="blindly"></span>
### Blind.ly Messenger

Worked with my excellent teammates Jesse Chen, Woosuk Kim, Edmond Lo, and Mark Wei on this project for our Software Engineering (CS169) class. Our idea was to develop a text messaging client for blind users, that took morse code as input. Our unique take on the problem was to use the volume rocker buttons as the sole input method (both for navigation and text entry), to avoid the confusion and difficulty typically presented to blind users by touchscreens, which provide little to no tactile feedback.

You can check the source code for our Android client on [GitHub](https://github.com/pingpongboss/Blind.ly-Messenger), and our final project presentation on [SpeakerDeck](https://speakerdeck.com/ricefield/blindly-messenger).

---

## Design

<span id="versecards"></span>
### Verse Cards

These verse cards were a side project I worked on during my first term of the FTTA. I came up with the idea of having wallet-sized tracts a few years prior, thinking it would be nice to always have gospel materials on hand. Initial mockups didn't seem to work so well though, so I dropped the idea.

After being inspired to take another stab at it, I decided on a simpler format of having one verse and one footnote (from the [Recovery Version](http://recoveryversion.org)), making sure to leave some space for contact info to be written. This ended up working well, though it still required a lot of kerning to get some text to fit properly. A very fun and rewarding project. 

* Song of Songs 6:1-2 | [Front](tracts/SS61-2front.pdf) / [Back](tracts/SS61-2back.pdf)
* Romans 12:2 | [Front](tracts/Rom122front.pdf) / [Back](tracts/Rom122back.pdf)
* Romans 8:6 | [Front](tracts/Rom86front.pdf) / [Back](tracts/Rom86back.pdf)
* Phillipians 3:8 | [Front](tracts/Phil38front.pdf) / [Back](tracts/Phil38back.pdf)
* Phillipians 3:10 | [Front](tracts/Phil310front.pdf) / [Back](Phil310back.pdf)
* Ensemble: on [Instagram](https://instagram.com/p/UM2_tEmzNS/?taken-by=ricefield) 

<span id="coc"></span>
### Christians on Campus

In college, I became involved with a Christian fellowship called [Christians on Campus](http://christiansoncampus.info/). Since I had background in print design, I volunteered to help out with the design of [several](coc/flyers/2010welcomemtghandout.jpg) [flyers](coc/flyers/2011celebrationmtg.pdf) and a [new club t-shirt](coc/tshirt/final.jpg).

In February of 2013, I spent two weeks volunteering with our sister clubs, Christians on Campus at the University of Central Oklahoma (UCO) and Oklahoma State University (OSU). Part of my work there involved making some [new](coc/UCO/info.pdf) [flyers](coc/UCO/signup.pdf) for the welcome events at UCO.

<span id="falcon"></span>
### Saratoga Falcon

In my senior year at [Saratoga High](http://www.saratogahigh.org/), I served as the Design Editor for the school newspaper, [The Saratoga Falcon](http://saratogafalcon.org/). That year, the paper was [awarded a Gold Crown by the Columbia Scholastic Press Association](http://cspa.columbia.edu/recepient-lists/2009-awards-student-work-crown-awards-scholastic-recipients#High School Gold Newspapers), one of the highest distinctions for scholastic journalism at the national level. My work for the paper which included a complete redesign of the masthead, a redefinition of typographic style, and issue-to-issue layout design, is reflected in a few of our best issues linked below.

[September 21 [PDF]](falcon/sept21issue.pdf)  |  [December 7 [PDF]](/falcon/dec7issue.pdf)  |  [May 2 [PDF]](falcon/may2issue.pdf)  |  [Senior Magazine [PDF]](falcon/seniormag.pdf)  
