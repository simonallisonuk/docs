# IC Principles

I’ve been an Individual Contributor (IC) for most of my 25-year career in software development. 
An IC is an employee who does not have direct reports and does not perform people management tasks. 
This document describes some high-level principles that I've followed in my career as an IC. If you have any 
questions, please email me (hello@threddy.dev) or find me on Twitter (https://twitter.com/ThreddyRex). Initially written Mar 2022. Updated May 2022, Jun 2022.

----
# Caveats

Before I dive into the principles, I’d like to first share some caveats. The main one being "this is my personal experience, 
and your mileage may vary". Some examples of what I mean:

* **Role** – I’ve been a software developer for most of my career. For other roles there may be other principles that are more important.
* **Industry** – I’ve spent my career in tech and finance. Perhaps other industries are different.
* **Region** – I live and work in the U.S.
* **Privilege** – I come from a place of privilege (middle-aged, white, man, raised middle-class, etc.). Principles might be different 
for folks in under-represented groups.


----
# Principle – Persistence is key

If you remember one thing from this document, let it be this one.

Success doesn’t always happen on the first try. Sometimes you pick the wrong solution, or you don’t execute well enough, 
or something happens that is out of your control. All of these things might happen (and have happened to me). 
This is ok, it is a part of life. 

*	**_When failure occurs, the important thing is how you respond to it._**

Try to figure out why the failure occurred, learn from it, adjust your approach, and then…try again. 
If anything, you’ll have more knowledge about the problem space and your chance of success will be higher.


----
# Principle - Fall into the pit of success

I think of this principle as the following:

* _**Position yourself in such a way that success is nearly inevitable.**_

What do I mean by "position yourself"? This could mean changing either the tasks that you are working on, 
the role you are in, the team you are a member of, or your employer. Very often I encountered highlights in my career just 
after re-positioning myself. Like switching a role or switching a team. Don't be afraid to re-position if you 
feel that it will increase your chances of success. You are probably correct.

This doesn't mean that success is guaranteed. It also doesn't mean that there won't be hard work. But I feel that
positioning yourself correctly is a key part of success.

----
# Principle – Be a subject matter expert

I've always strived to be the go-to person on a particular subject. The subjects are usually technical in nature and what I would 
consider "complex". I would pick a subject, learn as much as I can about it, and try to practice it with the goal of becoming an expert.

In fact, I can trace my career based on the subjects I was learning at the time. My earliest subject was C++ - that was one of the first 
languages that I used professionally. I read every book I could find on the subject, watched videos about it, etc.

At Microsoft I’ve traveled through several subjects – first performance engineering, then network engineering, and most recently data 
engineering and visualization. As I collect these subjects it makes me feel like I can be more valuable to the company. I love it 
when someone emails or IMs me asking about a subject that I know a lot about.

How will you know what subjects to focus on? For me, I pick things that are fun, technical, complex, and something I feel I can provide unique value in.

An alternate way to phrase this principle:

* Pick a subject you care deeply about,
* that would provide value to the business, 
* learn all about it,
* position yourself to work on it (potentially changing jobs),
* and become known as the person who cares deeply about the subject.

On a related note, there is a similar saying that I like to live by:

* _**The secret to success is showing up and giving a shit.**_

Pick a subject, and then become known as the person that gives a shit about it.


----
# Principle – Have a mix of "Preparation" and "Highlight" years

When I look back at the years of my career, each of those years can be classified as either a "preparation" year or a "highlight" year:

*	**Preparation year** – you are laying groundwork for a highlight year, either by learning new skills, starting on a new team 
or in a new company, or putting together some building blocks (tools/code/libraries/analyses/etc.) that will come in handy 
later. Preparation years sometimes feel difficult. You might feel like you aren’t providing enough value to the business. 
Don't worry, this hard work will pay off soon. You are preparing for your highlight.
*	**Highlight year** - an opportunity has appeared where you can utilize prior preparation to create a highlight! Highlights can 
be delivering a high-value project, getting a promotion, or something else that is just plain awesome. All of that hard work 
in the preparation years has now paid off!

When I look back at my Microsoft career, of the 14+ years I've been here, I've had four major project-related highlights. And in between 
those I've had years where I was learning or otherwise positioning myself for an upcoming highlight.

It's natural to have a mix of both. Not every year will be a highlight. But make sure you occasionally experience the highlights.

Looking back at my career highlights, what are the common themes for all of them?

* **Opportunity** - a large opportunity appears (huge challenge/problem/business need)
* **Positioning** - I'm positioned near it (right team/role)
* **Preparation** - I'm prepared for it (skills/tools)
* **Subject Matter Expertise** - I'm a SME on the topic or the project allows me to become one (perf, network, data analysis/viz)
* **Clarity** - I have clarity about the "right path" and feel strongly about that path
* **Autonomy** - I have autonomy to explore that path and lead folks down it
* **Work Product** - my "work product" is being directly used (toolset, analysis, etc)
* **Pressure** - there's high pressure, and almost feels hectic at times



----
# Principle – Test your assumptions

This principle manifests itself in several ways, but the general idea is:

* **_If you are making an assumption, be sure to verify the assumption with tests or observations._**
	
The earliest example of this I can remember from my career is unit testing. Prior to unit testing, I was always nervous
about refactoring code, and I made assumptions about the correctness of the code based on code review and manually testing. 
Once I started writing unit tests, refactoring became way easier, and I found a ton of problems with my initial assumptions. 
To this day, unit testing is one of the subjects that fundamentally changed how I approach software development.

A more recent example of this is data engineering. Let's say I’m evaluating a new data source for visualization, and I find a column
in a data table named "US State". My initial assumption would be "Oh, this will have data for all 50 U.S. States". It’s important to test 
that assumption. Many times I find that my assumption is wrong – either some data is missing, or some data is duplicated, or I misunderstood 
the purpose of the column, or something else. Often when I am starting a new data project, the first thing I'll do is create visualizations 
that test my assumptions about the data. Besides initially verifying my assumptions, these visualizations help when issues arise with a data
source. I can send a screenshot of the chart and say, "this data doesn't look right, can we investigate?"

This principle applies to non-technical situations, too. One example of this is when you are working on a team across multiple cultures. 
Don’t assume that you fully understand the nuances of folks that live and work in cultures that you are unfamiliar with. Communication 
styles and behaviors may be slightly different. Ask questions and replace assumption with curiosity to ensure that communication is effective.

One a similar note – don't be afraid to ask questions. If you are in a meeting or on an email thread, and you are making an assumption but 
you're not quite sure about it – ask a question. There's a good chance that other folks are wondering the same thing you are. 
Also if you are a more senior person in the group, it’s good to ask questions to set the right example for the entire team.


- - - -
# Principle – Document the important things

This is something I've started doing more recently in my career. At first it feels like too much time and energy to stop what I am 
doing and write a document, but later I find that it provides so much value. It's something you need to try once to really understand fully.

Some situations where I've found this to be useful:
* **Documenting an existing system.** There are some software systems that I get asked questions about a lot, and it's really great 
to be able to say "first read this document I wrote, and then if you have more questions, please ask." It helps save me time 
and provides information to the folks that need it.
* **Gaining consensus on a plan.** Sometimes there is a path forward on a project, and it would help to get consensus from the team on 
the plan. Writing a document and letting folks comment on it is a great way to gain consensus.
* **Learning about a topic.** I often will write something as I'm trying to learn it. I like the saying – 
"you don't really know a topic until you can teach it."
* **Documenting experience.** For example, documenting principles of being an Individual Contributor. 😊 

I urge everyone to create a few documents on topics they care about. You might be surprised at how useful these documents become.


- - - -
# Principle – Think of a career as a "collection of experiences"

A common career question is "where do you want to be in 5 years?"

I'll be honest - I struggle answering this question. I really have no idea "where I want to be".  However, I find it easy to identify 
what types of activities and experiences keep me most engaged at work. Tasks where I often find myself "in the zone".

Given this, I reframe the original question as the following:

* _**What experiences do I want to have over the next 5 years?**_

This helps me decide what next steps I might want to take in my career. If there are experiences I haven't yet had, I’ll gravitate towards 
roles that might help me have them.

This principle is related to "fall into the pit of success" in that both rely on positioning to succeed. Position yourself in such a way 
where you can have those desired experiences!


- - - -
# Principle – Move to adjacent roles

You may love your current role, but at some point you will reach a moment where it's time for a change. Maybe a move 
to a different team, or a different role, or a different company or career. 

When making these moves, I like to pick an adjacent role. What does this mean? I try to pick something where my current experience 
will be useful and help me in the new role, but the new role has new tasks and activities that I can learn and grow with. The
adjacency provides familiarity that helps me learn and grow into the new role.

An example of this: I was on a team doing data analysis and performance engineering. For my next role, I chose a team where I 
could continue doing these types of tasks, however it was for a new product, in a new org, with different strategies for how we approached 
the tasks. I was able to lean on my past experience, while learning new things and growing.


- - - -
# Principle – Try things that scare you

I am a risk-averse person. I like to stay in my comfort zone. It is safe there.

This is Ok at times, but if I stay there always, I'll never learn or experience new things. Occasionally I like to try things that scare me. 

An example of this is when I was invited to give a talk at Microsoft Ignite 2019. I was invited in early 2019, and I spent the entire year 
worrying about it until the conference in the Fall. Would I fail? Would people not like it? What if I tripped off the stage and broke something? 
Despite all these worries, I got up on stage anyways and gave what I think was an acceptable talk. And I'm glad I did – it is an experience I will 
never forget and I consider it to be one of my career highlights.


- - - -
# Principle – Trust your instincts

A few times during my career I've found myself in a position where there was a status quo, and I felt strongly that it should be changed 
(and I had the skill and power to change it). During these times, I chose to trust my instincts and attempt to make a change and follow the 
path I thought was correct. So far, these have been good decisions.

This reminds me a bit of the first principle – caring deeply about a subject. If I care about a subject, and I know the most about it, 
and I'm being held accountable for it, I feel I have the right (and obligation!) to make changes in that area that will put it on the best path.

I will often ask permission in these cases. But not always. Sometimes you need to put your head down, crank out a solution, then come up for
air and show it to folks (and apologize later if needed). It's like that saying – it's easier to ask for forgiveness than to ask for permission. 😊

Use this sparingly and wisely. Weigh the risks/rewards, and if it makes sense to try it, go for it. There is higher risk here, but the reward is wonderful.

- - - -
# Principle – Network with peers

The idea here is that, over time, you should build up a network of peers in your company and industry. This network can help in various ways 
– you can learn from each other, help each other through difficulties, collaborate on projects, share successes and failures, etc.

You might not think you need this – and I certainly didn't at the beginning of my career – but it's something you won't fully understand until 
you try it. I spent most of my career heads-down working on projects, without spending any time interacting or connecting with others. Luckily within the
past few years I joined Twitter and that has forever changed for the better. 😊

How do you do this? Social media is one way. Every social media platform is different, and my general advice is to pick the one that best fits 
your personality and then be consistent with your engagement. Offline pursuits are also helpful here – both internal resource groups, as well 
as external hobbies. Basically anything where you are spending time with others on a subject that you care about and enjoy. And the subject 
doesn't really need to be work-related, it can be anything.

- - - -
# Principle – Choose an organization carefully

I try not to underestimate the importance of organization and management chain. Not all chains are created equal. And this is not a comment 
on good or bad – it's just that my own personality is better suited to certain teams. Everyone is unique, and a team that is a great fit for 
one person, might not be a great fit for another person. I've had situations where I was on the fence about a job offer, but the reputation of 
the management chain was the tipping point in my accepting the offer (and it worked out well).

How can you know about an organization before joining it? This is one situation where leaning on your network helps. Do you know anyone on the 
team? Can you ask their opinion? You might learn things that sway you in either direction.


- - - -
# Principle – Know your tools

Software development requires a lot of tools - IDEs, programming languages, version control, graphical tools, etc. 
All of these tools assist you in solving your scenarios and problems. 

Here's the trick though - if you don't know how your tools work, you'll spend too much time fighting
with the tools themselves, instead of solving your customer problems. That's why I like to spend a small % of my time 
dedicated to learning. 

When do I decide to spend time learning? In some cases, the team or organization
has mandated use of a tool (build system, programming language, etc.), and I have no choice but to learn it. In other cases, 
I'll be using a toolset on my own, and I'll notice that it has a downside that may be fixed by migrating to something else. 
In either case I'll pause what I'm working on and shift my focus to learning.

Here are a few examples:

* **Power BI** - prior to learning Power BI, I had been building reports at work using things like JS and D3, and hosting them on my own server. 
The analyses were going well, but I was spending too much time on things like server maintenance, authentication, and report look-and-feel. 
I just wanted to focus on the analyses instead. I had heard that Power BI was getting popular within the company and I decided to give it a try. 
I'm glad I did - since then I've been using it successfully for our team's analyses.
* **Affinity Designer** - I like to make comics. For a while I used a raster-based tool for drawing the Threddy comics. The problem, though, was
that if I wanted to scale the characters larger or smaller, the raster drawings wouldn't scale well and I would need to redraw them. I had heard 
that a vector-based approach might fix this. During a long flight to China I decided to practice using Affinity Designer, which is a popular 
vector drawing tool. By the end of the flight I had learned enough about the software to be able to use it for the comics. And ever since 
then I've been using _only_ Affinity Designer for Threddy comics.

If you find yourself thinking "if I learn tool XYZ it will be good for my project or career", you're probably right.
Spend that time on learning and you won't regret it.



- - - -
# Principle – Use the right tool for the job

Also on the subject of tools - when you are faced with a task, pick the tool that is best suited to the job, 
rather than a tool you are currently comfortable with.

Early in my career I was enamored with C++. I wanted to focus my entire career on it. I learned the ins and outs of the language, watched 
videos on it, and practiced the language as much as possible. But I quickly realized that this language was not well suited for many 
problems. It honestly was a difficult lesson for me, but once I learned to focus on picking toolsets based on task, it made problem solving easier.



- - - -
# Principle – Do great work, and be visible

I heard a definition of success that I really like:

* _**Success is a combination of two things: doing great work, and being visible.**_

Doing great work seems like the obvious part. If you are good at what you do, and you provide value to the business, I would consider 
that "succeeding". Whatever you choose to do with your career, be awesome at it.

Being visible is maybe the less-obvious part. If you are doing great work, but nobody knows about it, will you be rewarded for 
that success? Are you really working on the most impactful things? It’s important that folks know about your successes.


- - - -
# Principle – You're not alone, find people in your shoes

I sometimes fall into the trap of thinking "nobody else on earth is experiencing this thing that's happening to me." The reality is that there are usually *many* folks experiencing the same things. The trick is finding some of these folks and comparing notes.

A recent example: my role at work shifted from software engineering tasks (coding, data analysis, etc.) to what I would consider "non-software engineering tasks" (recruiting, driving meetings, building consensus on process, etc). I was very engaged in these tasks, however I no longer felt like a Software Engineer, and I struggled to find a vocabulary to describe this new role I was in. Then one day I had a chat with someone and mentioned the situation, and discovered they were in the *exact same situation*. It was AMAZING to have someone to compare notes with and confide in. This discovery will probably result in us meeting periodically to compare notes and help each other.




- - - -
# Principle – Know when to log out

Working hard is great, but it's equally important to know when to log out. Work/life balance is critical for maintaining a successful, 
happy, and healthy life. Don’t be afraid to take breaks. Enjoy life. The work will be here when you return.



