# The SPOC archetype framework for evaluating software developers (and other IT professionals)

## Introduction

Evaluating software engineers for a job opening is a daunting task. It's difficult to think of a field more [varied](https://en.wikipedia.org/wiki/List_of_programming_languages), [diverse](https://en.wikipedia.org/wiki/List_of_operating_systems), [esoteric](https://en.wikipedia.org/wiki/Esoteric_programming_language), [technical](https://www.gnu.org/software/libc/manual/), [quirky](https://www.reddit.com/r/javascript/comments/2scikz/eli5_why_is_this_true_01_02_030000000000000004/) and [misunderstood](https://hackernoon.com/50-common-misconceptions-in-the-world-of-software-development-7144566c54f9) as software engineering. 

Even the name for the field itself is hotly disputed. A quick search on [Wikipedia](https://en.wikipedia.org/wiki/Software_engineer#Suitability_of_the_term) comes up with this quote from computing legend Edsger Djikstra:

> The existence of the mere term [software engineering] has been the base of a number of extremely shallow—and false—analogies, which just confuse the issue... Computers are such exceptional gadgets that there is good reason to assume that most analogies with other disciplines are too shallow to be of any positive value, are even so shallow that they are only confusing.
> Edsger W. Dijkstra, 1978

This state of affairs is unsuprising when the reader considers that the discipline itself [cannot be older than 200 years by the most generous definition](https://www.britannica.com/story/ada-lovelace-the-first-computer-programmer). The term "software engineering" itself was [coined in the 1960's](https://en.wikipedia.org/wiki/History_of_software_engineering#1945_to_1965:_The_origins) and is less than 60 years old as of the time of this writing (Dec 2019).

To pile insult upon injury, there is not a single generally-accepted framework for evaluating software engineering candidates that the author knows of. Not a lot of companies know how to properly evaluate developers and other technical personnel. There are several superstitions and misconceptions, which make matters worse. We won't go into the details, but here are a few such myths:

* Having more developers means faster delivery.
* Developers are a commodity resource.
* Education matters a lot.
* Experience matters a lot.
* All developers are expensive.
* Expensive developers are good developers.
* Consultants are always a bad idea.
* PHP/Perl/Python/JavaScript/Java/etc. developers are bad developers.
* ...and the list goes on. 

In the midst of such uncertainty, it is clear to the author that a practical and memorable framework for evaluating software developers is immediately necessary. In order to help clear up the confusion, we're presenting here, in plain english, **the SPOC framework**, which we at [Mintbean](https://mintbean.io) use on a daily basis to evaluate software engineering candidates. 

------

## Index

- [The SPOC archetype framework for evaluating software developers (and other IT professionals)](#the-spoc-archetype-framework-for-evaluating-software-developers--and-other-it-professionals-)
  * [Introduction](#introduction)
  * [Index](#index)
- [How to use this framework](#how-to-use-this-framework)
  * [1. Understand the framework](#1-understand-the-framework)
  * [2. Understand the job opening](#2-understand-the-job-opening)
  * [3. Evaluate the job opening](#3-evaluate-the-job-opening)
  * [4. Evaluate the candidate](#4-evaluate-the-candidate)
- [The traits](#the-traits)
  * [S - Schooling](#s---schooling)
  * [P - Practice](#p---practice)
  * [O - Organizational](#o---organizational)
  * [C - Community](#c---community)
- [The Archetypes](#the-archetypes)
  * [The Adventurer](#the-adventurer)
    + [Traits](#traits)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them)
  * [The Spectator](#the-spectator)
    + [Traits](#traits-1)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-1)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-1)
  * [The Nontechnical](#the-nontechnical)
    + [Traits](#traits-2)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-2)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-2)
  * [The Facilitator](#the-facilitator)
    + [Traits](#traits-3)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-3)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-3)
  * [The Tinkerer](#the-tinkerer)
    + [Traits](#traits-4)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-4)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-4)
  * [The Hacker](#the-hacker)
    + [Traits](#traits-5)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-5)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-5)
  * [The Savvy](#the-savvy)
    + [Traits](#traits-6)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-6)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-6)
  * [The Self-Taught](#the-self-taught)
    + [Traits](#traits-7)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-7)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-7)
  * [The Academic](#the-academic)
    + [Traits](#traits-8)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-8)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-8)
  * [The Researcher](#the-researcher)
    + [Traits](#traits-9)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-9)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-9)
  * [The Organizer](#the-organizer)
    + [Traits](#traits-10)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-10)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-10)
  * [The Native](#the-native)
    + [Traits](#traits-11)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-11)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-11)
  * [The Fledgling](#the-fledgling)
    + [Traits](#traits-12)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-12)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-12)
  * [The Seeker](#the-seeker)
    + [Traits](#traits-13)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-13)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-13)
  * [The Careerist](#the-careerist)
    + [Traits](#traits-14)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-14)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-14)
  * [The Star](#the-star)
    + [Traits](#traits-15)
    + [Jobs that fit this archetype](#jobs-that-fit-this-archetype-15)
    + [Common jobs given to this archetype that actually don't fit them](#common-jobs-given-to-this-archetype-that-actually-don-t-fit-them-15)
  * [About](#about)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


------

# How to use this framework

The SPOC framework is meant to be used to build a recruiting process. However, it is also easy, intuitive, and memorable. Once you're familiar with it, you can even use it as a kind of mental shortcut to quickly judge whether you should hire someone for a software development role.

Over time, patterns will emerge, and you will develop an intuitive sense for evaluating software engineering candidates based on their resume, the interview process, their personality type, their behavioral patterns, and so on.

Ideally, you're evaluating candidates for a very specific software engineering position inside a company that you understand very well. If this is the case, then each evaluation criteria has specific modifications that must be made to adjust for this very relevant information.

The framework can be used at any step of the recruiting process. Whether you're writing a job description, filtering resumes, interviewing candidates or conducting technical tests, you will find that the SPOC framework informs your decisions and is a useful tool in your toolbelt.

## 1. Understand the framework

The first thing you should do is make yourself familiar with the SPOC framework. It is relatively easy to understand and is not technical in nature. It can even be fun to learn.

Understand the 4 traits. Familiarize yourself with the resulting 16 archetypes. As a fun test, evaluate yourself on the framework and "guess" where you might fit.

TBD

## 2. Understand the company and the job description

TBD

## 3. Identify the ideal candidate archetype

TBD

## 4. Evaluate the candidates

TBD

## 5. Hire a candidate

TBD

## 6. Follow through

TBD

# The traits

## S - Schooling

This trait measures formal education in computer science & software engineering. 

Any formal instruction counts toward this trait, including high school software development classes, diploma courses, professional certification, development bootcamps, coursework completed, and completed university degrees.

TBD

### How to evaluate this trait

TBD

## P - Practice programming

Practice is the time and effort spent building projects using code, whether in the workplace, at school, or as a hobbyist.

TBD

### How to evaluate this trait

TBD

## O - Organizational experience

This is a measure of experience the candidate has in a technical workplace environment. 

This is not necessarily workplace experience as a developer. This could be a non-technical person, such as a manual QA specialist or a business analyst, working closely with an engineering team.

TBD

### How to evaluate this trait

TBD

## C - Community

This indicates familiarity with and participation in the developer community.

TBD

### How to evaluate this trait

TBD

------

# The Archetypes

## The Adventurer

:boat:

Adventurers are brand new entrants in the tech world. Often, they're explorers, and are curious about the tech world and the opportunities that lay therein. They have no exposure to the software industry at all. Many of them are looking for their first opportunities in technology, and some might be applying for a job that is similar to ones they've had in the past.

Adventurers are wildcards. You never know what you're going to get with them -- which is simultaneously their biggest strength and their biggest weakness. They can bring unique strengths and synergies. Expect the unexpected with these brave souls.

### Traits

* Schooling - :x:
* Practice - :x:
* Organizational - :x:
* Community - :x:

### Jobs that fit this archetype

* Manual QA
* Roles that match their existing skillset
* Generalist roles

### Common jobs given to this archetype that actually don't fit them

* Anything having to do with code
* Anything having to do with understanding developers
* Anything having to do with understanding the industry

------

## The Spectator

:newspaper:

Spectators are deeply interested in the world of tech, but have never worked in it. This person could be an Adventurer who has been curious about the technical world for a while, but has never worked in it.

Spectators have spent significant amounts of time reading about and interacting with the world of software development. They can work in fields that interact with the engineering community in some way or another.

### Traits

* Schooling - :x:
* Practice - :x:
* Organizational - :x:
* Community - :heavy_check_mark:

### Jobs that fit this archetype

* Manual QA
* Roles that match their existing skillset
* Generalist roles
* Technical recruiter
* Technical writer
* Marketing specialist (targeting developers)

### Common jobs given to this archetype that actually don't fit them

* Anything having to do with code
* Anything having to do with understanding developers

------

## The Nontechnical

:briefcase:

The Nontechnical has worked in a technical company, or closely with a technical department, but not in a technical capacity. These people are familiar with the rhythm and flow of a technical department. They are often liaisons between engineering departments and business departments, and bring a lot of specialized experience with them.

### Traits

* Schooling - :x:
* Practice - :x:
* Organizational - :heavy_check_mark:
* Community - :x:

### Jobs that fit this archetype

* Manual QA
* Roles that match their existing skillset
* Business analyst (non-technical)
* Project manager
* Product manager

### Common jobs given to this archetype that actually don't fit them

* Dev manager
* Team lead
* Scrummaster

------

## The Facilitator

:smiley:

Facilitators are people who are very familiar with the developer community, but are not developers themselves, nor do they have technical schooling. They understand software development and the engineering mindset and typically work well with developers.

Facilitators fit well into organizations and departments that work closely with the engineering community. The best role for facilitators is one centered around understanding, supporting and nurturing the other archetypes. Facilitators deeply understand both business folk and developers, and can act as translators between these two departments. 

### Traits

* Schooling - :x:
* Practice - :x:
* Organizational - :heavy_check_mark:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Business analyst
* Technical recruiter
* Technical community manager
* Marketing specialist (targeting developers)
* Sales & business development

### Common jobs given to this archetype that actually don't fit them

* Dev manager
* Team lead
* Scrum master

------

## The Tinkerer

:wrench:

Tinkerers are pure technicians. They've focused on making machines do their bidding. They take pride in their technical skill and may be hobbyist programmers in their off-hours. 

Tinkerers often can work wonders with Excel macros, and often write small scripts that make their coworkers' jobs a bit easier. However, they haven't (yet) invested the time in learning best practices or getting to know the culture and community surrounding the language they know best.

### Traits

* Schooling - :x:
* Practice - :heavy_check_mark:
* Organizational - :x:
* Community - :x:


### Jobs that fit this archetype

* Tech support
* Junior business analyst
* Manual QA
* QA Automation Engineer
* Roles that match their existing skillset

### Common jobs given to this archetype that actually don't fit them

* Junior software developer
* Product manager
* Technical business analyst
* Scrummaster

------

## The Hacker

:neckbeard:

Hackers are Tinkerers who have invested more time in understanding the culture surrounding the language of their choice. These are self-taught developers who truly enjoy software development, and may be self-studying their way into a software development role.

Hackers are beyond seeing code as just a tool. They're enthusiasts, and understand the aesthetic beauty of software development. They could be idealists at heart, and might subscribe to open-source philosophy. Given mentorship and experience in a mature software development team, these people have the potential to become some of the best software developers you've ever seen.

### Traits

* Schooling - :x:
* Practice - :heavy_check_mark:
* Organizational - :x:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Junior software developer
* QA Automation Engineer

### Common jobs given to this archetype that actually don't fit them

* Manual QA
* Intermediate software developer
* Senior software developer
* Business analyst
* Technical busines analyst

------

## The Savvy

:bulb:

Savvies bring experience in writing scripts and programs to the departments they work in. Very often, savvies work in quantitative professions such as accounting or finance, and have picked up coding as yet another tool in their number-crunching toolbelt.

Savvies have the business knowledge to build software that solves real problems, but have gaps in theoretical and practical knowledge that ultimately put them squarely in the realm of business and NOT technology.

### Traits

* Schooling - :x:
* Practice - :heavy_check_mark:
* Organizational - :heavy_check_mark:
* Community - :x:

### Jobs that fit this archetype

* Business analyst
* Technical business analyst
* Roles that match their existing skillset

### Common jobs given to this archetype that actually don't fit them

* Junior software developer
* QA Automation Engineer
* Manual QA

------

## The Self-Taught

:squirrel:

These gritty individuals have dedicated their professional lives to code. They've successfully broken into the software development profession, and rightfully see themselves as full-fledged software developers. They may have previous experience as non-technical professionals, which they've left behind, but that experience is valuable and still informs their work on a near-daily basis.

The Self-Taught archetype is one of the best fits for a software development role. What they don't know theoretically, they make up for with passion for their work, dedication to their craft, and a knowledge of their tools and their community.

### Traits

* Schooling - :x:
* Practice - :heavy_check_mark:
* Organizational - :heavy_check_mark:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Junior Software Developer
* Intermediate Software Developer
* Senior Software Developer
* Team Lead
* Dev Manager
* QA Automation Engineer
* QA Automation Lead
* Software Architect

### Common jobs given to this archetype that actually don't fit them

* Manual QA
* Business Analyst
* Technical Business Analyst
* Technical recruiter

------

## The Academic

:book:

Academics are those who have studied computer science without any significant coding experience or experience working in the industry. These individuals may have significant prior work experience outside software development. Many recent graduates fit this archetype, as do individuals who got their degree or diploma in software engineering or computer science but then moved into a non-technical profession.

Academics understand computer science and software engineering to a certain degree, but may not fully understand the psychology of a software developer or the inner workings of a well-run software engineering department. They are good fits for roles that fit their prior work experience or junior-level non-technical roles.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :x:
* Organizational - :x:
* Community - :x:


### Jobs that fit this archetype

* Junior-level non-technical roles.
* Manual QA
* Generalist roles
* Jobs that match their existing skillset.

### Common jobs given to this archetype that actually don't fit them

* Junior software developer
* QA Automation Engineer
* Intermediate Business Analyst
* Scrummaster
* Dev manager

------

## The Researcher

:telescope:

Similar to the Academic, the Researcher has spent significant amounts of time studying the software development industry. In addition to book knowledge, the Researcher understands the state of the industry from an outsider's perspective. They are frequently able to come up with deep insights about the industry.

Researchers are often computer science or engineering students who are passionate about technology, but not necessarily about coding. Such students can make excellent additions to non-technical departments, and often show curiosity and passion about the industry and its players.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :x:
* Organizational - :x:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Junior-level non-technical roles.
* Manual QA
* Generalist roles
* Jobs that match their existing skillset.
* Technical recruiter
* Technical writer
* Marketing specialist (targeting developers)

### Common jobs given to this archetype that actually don't fit them

* Junior software developer
* QA Automation Engineer
* Intermediate Business Analyst
* Scrummaster
* Dev manager

------

## The Organizer

:bookmark_tabs:

Organizers are people who help software departments and companies run efficiently and smoothly. Without any special inclination towards coding, these tend to be industry specialists who have studied software development and made it their home.

Very often, the academic background of an Organizer is irrelevant. They have understood the mechanics of information technology to a certain degree, but do not show any inclination towards learning to code or to learning more about development culture.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :x:
* Organizational - :heavy_check_mark:
* Community - :x:

### Jobs that fit this archetype

* Junior-level non-technical roles.
* Manual QA
* Generalist roles
* Jobs that match their existing skillset.
* Business analyst (non-technical)
* Project manager
* Product manager

### Common jobs given to this archetype that actually don't fit them

* Junior software developer
* QA Automation Engineer
* Intermediate Business Analyst
* Dev manager
* Team lead
* Scrummaster

------

## The Native

:globe_with_meridians:

Natives are at home in the world of software development. They have studied a technical field, possess relevant industry experience, and have researched the industry to a point where they understand trends in technology and understand long-term trends that may affect the business.

Natives are non-technical, but are well-suited to leadership positions in software development firms. Since they have the conceptual background to do so, they might be able to lead a software development team in a limited capacity. Many of them do so on a regular basis, to varying degrees of success.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :x:
* Organizational - :heavy_check_mark:
* Community - :heavy_check_mark:

### Jobs that fit this archetype

* Product manager
* Project manager
* Dev manager
* Scrummaster
* Business analyst
* Marketing manager
* Non-technical Leadership
* Jobs that fit their existing skillset

### Common jobs given to this archetype that actually don't fit them

* Manual QA
* Team lead
* Software Developer
* Software Architect

------

## The Fledgling

:seedling:

Fledglings have studied software development and have built several projects of varying sizes, maybe as part of their coursework. Many software development bootcamp graduates fall into this category. They may be building their portfolio of projects and working towards their first software development jobs.

Many fledglings eventually land their first software development job, although most take on non-technical or semi-technical roles. Some move out of the software development industry altogether, following their passion or their curiosity to greener pastures.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :heavy_check_mark:
* Organizational - :x:
* Community - :x:


### Jobs that fit this archetype

* Junior software developer
* QA Automation Engineer
* Manual QA
* Jr. Technical Business Analyst
* Jr. Technical Project Manager

### Common jobs given to this archetype that actually don't fit them

* Scrummaster
* Lead QA Automation Engineer
* Business Analyst
* Generalist roles

------

## The Seeker

:eyeglasses:

Seekers are serious software development students who have dedicated large amounts of their personal and professional time to learning as much as possible about software development. They are actively looking for their first software development jobs.Many seekers may accept non-technical roles, but nothing would make them happier than landing a software development role.

Seekers sometimes come from other industries, especially via bootcamps and short diploma programs. They might have something to prove, and as such can make very dedicated and enthusiastic employees.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :heavy_check_mark:
* Organizational - :x:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Junior software developer
* QA Automation Engineer
* Technical business analysis

### Common jobs given to this archetype that actually don't fit them

* Non-technical roles
* Generalist roles
* Project manager
* Dev manager
* Product manager

------

## The Careerist

:office:

The vast majority of software developers are Careerists. They understand the various tools of their specific industry or language, and might even know many popular libraries in their ecosystem, but they have not put in the effort to learn the culture and community surrounding those tools (although they might look up tutorials and examples on a near-daily basis).

Careerists make excellent intermediate developers, QA Engineering professionals and long-term hires. They are professional software developers, but tend not to be overly passionate about the craft of development.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :heavy_check_mark:
* Organizational - :heavy_check_mark:
* Community - :x:


### Jobs that fit this archetype

* Intermediate software developer
* Lead software developer
* Dev manager
* QA Automation Engineer
* Lead QA Automation Engineer
* Technical product manager
* Technical business analyst

### Common jobs given to this archetype that actually don't fit them

* Software Architect
* Senior software developer
* Manual QA


------

## The Star

:star:

Stars are enthusiastic software developers who eat, drink, sleep and dream software development. These are career developers who have studied software development professionally, have experience as developers in the software development industry, and often actively partake in the dev community they are a part of.

Some of the best software developers are Stars. They make excellent technical leaders and are frequently an inspiration to younger developers who have the privilege of working with them. They fit well into technical organizations and are capable of building projects from scratch with strong technical foundations. However, they might not fit well into organizations that are primarily non-technical or that do not have a strong software development culture.

### Traits

* Schooling - :heavy_check_mark:
* Practice - :heavy_check_mark:
* Organizational - :heavy_check_mark:
* Community - :heavy_check_mark:


### Jobs that fit this archetype

* Junior Software Developer
* Intermediate Software Developer
* Senior Software Developer
* Team Lead
* Dev Manager
* QA Automation Engineer
* QA Automation Lead
* Software Architect

### Common jobs given to this archetype that actually don't fit them

* Any non-developer roles

------

## About

The SPOC framework was created by [Monarch Wadia](https://linkedin.com/in/monarchwadia), who is CEO at [Mintbean](https://mintbean.io), where his team uses it to evaluate software engineering candidates for Mintbean and its clients. The framework draws on his professional experience as a software architect and business leader. He also finds it immeasurably amusing, and somewhat uncomfortable, to write about himself in the third person.