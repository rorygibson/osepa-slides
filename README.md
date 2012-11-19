Intersection: Combining Open Source and agile delivery
======================================================

_Slides for my presentation at the Public Sector Open Source Conference, November 21st, Sheffield Uni_


Contents
--------

1. Introduction
1. Freedom
1. The Open Source community
1. Collaboration
1. Regular releases
1. Feedback
1. Overlap with the Agile community
1. Combining Open Source and agile in the public sector
1. In practice
1. Challenges
1. The future


Introduction
------------

[Slide: Front page]

Good afternoon.

My name is Rory Gibson. 

I'm a technical architect, a consultant, an Open Source developer, an agile coach, and very occasionally a conference 
speaker.

[Slide: Technophobia]

I work for Technophobia, a Sheffield-based software house. We focus on user experience, web development and the 
delivery of challenging projects. We do everything from brochure-ware websites to systems integration work for the NHS, 
social networking to agile consultancy.

We often work in the Public Sector, either directly delivering new and updated systems, or helping our clients develop their 
digital vision and strategy.

Personally, that means that I spend a lot of time talking to new and existing clients about using Open Source. The rest is 
making bespoke changes to Open Source software, and delivering projects, using that software, and usually in an agile way.

I get a lot of opportunities to talk to decision makers in public sector organisations, often in the Local Authority space.

As a result I've got an appreciation of the challenges that can present themselves when introducing Open Source, and a lot 
of experience of working through those problems and making it work.


Freedom
-------
Now, this is a conference about Open Source in the Public Sector, and I'm sure there will be a number of presentations over 
the next 2 days that will directly address issues of policy, procurement and so forth.

I'm going to talk about something that's perhaps a little more general and abstract.

I've been around the Open Source community since before the term "Open Source" was coined, back when software 
developers, geeks, nerds and enthusiasts of all sorts were beginning to get excited about this thing called "Free Software".

[Slide: Free Software]

"Free Software", capitalised exactly so, is a term with a very specific meaning. 

Introduced by one Richard Stallman, [Slide: Transition GNU] "Free Software" means software that is "free as in speech, not 
free as in beer", and the emergence of this term, and the burgeoning movement behind it, presented a very significant 
change to the way that people (me included) started to think about software.

Since "Free Software" appeared on the scene many derivative movements, terms and visions have come and gone, and 
"Open Source" is, broadly speaking, one of these.

[Slide: transition Open Source]

Even though it's often forgotten today, this direct link to the geeky, idealistic Free Software movement - and the benefits 
that it delivers - is at the heart of what I want to talk about today.


The Open Source community
-------------------------

The Free Software community is stereotypically depicted as being made up of ... well, nerds, coding in their bedrooms.

[Slide: nerds in bedrooms]

These days, Open Source encompasses a much wider definition.

There are a great number of heavyweght Open Source products and tools that can help you to deliver value to your 
customers and citizens. And there's a great deal of money to be made by businesses that follow a "commercial Open 
Source" model - making the source code of the software available under one OS license or another, and profiting by the 
provision of support or additional features.

[Slide: vendors I've worked with]
[TODO more vendors as below]

Many of these vendors - and I can single out a few that I've worked with, like Magnolia, Liferay, MySQL, JasperSoft and 
Canonical - appear almost indistinguishable from purely commercial vendors.

[Slide: web of collaboration]

But at the heart of it all, most Open Source projects are still rooted in code originally written by enthusiasts, working in 
loosely federated groups, often spread across continents, and collaborating together in ways that would have confounded 
the traditional software houses of the past.



Collaboration
-------------

[Slide: collaboration def]

"Collaborating" is the important word here. 

The dictionary definition of "collaboration" is "to work jointly with others or together especially in an intellectual endeavour".

If you look at many enterprises, both public and private sector, there's often an emphasis on supporting collaboration with 
tooling.

[Slide: collaboration via sharepoint]

We see a proliferation of software like Sharepoint, ostensibly designed to help people share documents and work together, 
but often so complex and difficult to configure that it ends up getting in the way, rather than supporting the emergence of 
new and better processes in the workplace.

[Slide: transition OS collaboration software]

Contrast this with the typical Open Source project; supported by mailing lists, Internet Relay Chat sessions, ad-hoc wiki 
pages, forums, and open-access distributed revision control systems like Git, usually allowing anonymous read access for 
any interested party.

The use of these more free-form tools actively promotes people talking to each other, working more closely together, and 
pulling together in the same direction - creating working software. These tools are so widely available, and so easy to 
acquire, that introducing them to a project requires little to no effort; their barrier to entry is extremely low, and as a result 
many Open Source projects can and do evolve their tooling very effectively.

One well-known example of this is in the development of the Linux kernel, the software at the heart of the GNU/Linux 
operating system that's so widely used now. 

This software was maintained for many years using a commercial version control system, until a disagreement with the 
vendor of that system started limiting the project's flexibility. The maintainers wrote a brand new, open source version 
control system that suited their needs, and within two months had transitioned millions of lines of code to the new system, 
and removed the problematic dependency on the commercial vendor.

Incidentally, the version control software they wrote is called Git, and it's now hugely popular in its own right.


Regular releases
----------------

Simply, Open Source software development is, by nature, conducted in the open. 

In general, the development of the product is transparent, and anyone who wants to can gain access to the latest state of the 
software, simply by cloning it from Github, downloading it, or checking it out from a public Subversion repository.

It's a natural result of this openness that, in order to maintain the reputation of the projects, the teams working on them tend 
to release their software regularly. 

This frequency of formal release, and the transparency of the systems in use, leads to a very short feedback loop; the team 
releases a new version (or closes a bug in a public tracker), and real users very quickly obtain the latest version, try it out, and 
are free to raise new defects, suggest enhancements - or develop them themselves and release them into the wild for the 
benefit of all.

[Slide: feedback loop]
[TODO re-order]
Cyclical processes are often said to follow the "PDCA" system, first laid out by W. Edwards Deming.

In essence, you 
 * Plan a piece of work
 * Do the work
 * Check whether the results are what you expected
 * Act on the results
 * ... and repeat

It's the speed of this feedback loop, and the ease with which interested parties can engage with the community, that drives 
the adoption of many Open Source projects, and contributes to the growth of their communities.

And it's the speed of the feedback loop that delivers real, tangible benefits to the users over time.
They can and will receive new functionality very quickly as it's created - no waiting for 12 month release schedules.

[Slide: agile methodologies]

And here we start to see parallels with another major new force in the software world in the last 20 years; agile software 
development methodologies.


Overlap with the Agile community
--------------------------------

It's no accident that proponents of agile methods are also often proponents of Open Source or Free Software.

There are several common agile methodologies, including Scrum, DSDM, XP, Kanban and others. 
In general, they share the common characteristics of being:

 * low in ceremony
 * high in reliance on teamwork
 * focussed on delivering value early

The mechanisms differ; some methodologies that broadly fall under the agile moniker aren't iterative, some have differing 
roles within the team, and they vary in the artefacts and meetings that make up the processes, but at the end of the day the 
focus is always on producing working software as early as possible - shortening the feedback loop.

If I can be so bold as to paraphrase the Agile Manifesto - the original written definition of what makes a methodology agile - 
then:

[Slide: Agile Manifesto]
[TODO transitions?]

We value:
 * Individuals and interactions over processes and tools
 * Working software over comprehensive documentation
 * Customer collaboration over contract negotiation
 * Responding to change over following a plan

Who here can look at those four elements and not see the parallels with the Open Source community?

In the main, Agile methods are all about delivering the software that customers need, when they need it, rather than what 
they said they needed a year ago. 

The techniques that we use to deliver in an agile way are all, really, about collaboration and communication in one way or 
another.
 * Talking to your customer more
 * Demonstrating real, running features
 * Getting feedback from the customer
 * Low-level code and design reviews (through techniques like pair programming)
 * Automating error-prone delivery processes (like integrating and building software)

It's only natural that a community that embraces communication and working together should also embrace software that's 
built on the same principles.

The vast majority of software that supports the agile ecosystem - story tracking tools, continuous integration tools, 
distributed version control systems - is Open Source. The communities overlap significantly.

[Slide: virtuous circle]
[TODO bigger]

I believe that this overlap, and the emphasis on feedback, collaboration and iteration, creates a virtuous circle, where the 
processes in use enhance the tools that are delivered, and the tools are used by the kinds of people that understand the 
processes.


Combining Open Source and agile in the public sector
----------------------------------------------------

I would guess that most of us here understand the benefits of Open Source to the public sector - in terms of (potentially) 
lower cost, reduced risk of vendor lock-in, the ability to take advantage of community enhancements and support, and so 
on.

Similarly, the benefits of agile processes 
 * early delivery of value to stakeholders
 * the ability to alter the requirements on the fly without massive cost impact, 
 * increased quality, 
 * improved stakeholder engagement 

and all the rest - are well documented and widely discussed.

Where I see an opportunity for increased understanding, is in what happens when you mix the two. 
I believe you should empower your organisations to choose not only the software that fits their needs, but the processes that 
can deliver them smoothly.

The key to doing this is to start without preconceptions, to use observation and data to determine what fits best in your 
situation. 

For some organisations that might be enterprise Oracle licenses, a Service Oriented Architecture across your entire estate, a 
two year gestation period for projects and a team of architects.

For other organisations a small, cross-functional team, using Open Source software components, a minimum of carefully 
crafted bespoke code, and delivering a subset of features inside a month, might be a better fit.

I've seen many risk averse organisations. To my eyes, risk should be analysed, quantified and mitigated, but sadly it's very 
common for the adoption of Open Source, or, for that matter, Agile, to be labelled as "risky" without real analysis or 
understanding - which is why I'm sure many of you will agree it can be an uphill battle to introduce Open Source, despite 
the benefits we can demonstrate.

By using open source components in a project, you reduce some of the barriers that make vendor lock-in such an issue. If 
you introduce elements of agile processes into the same projects, you can give yourself the flexibility to change 
components mid stream, and further reduce that risky dependency on particular vendors.


In practice
-----------

We at Technophobia have had great success in the Public Sector with introducing solutions based on these two pillars; 
Open Source and agile methodologies.

Our usage of agile - whether vanilla Scrum, or our hybrid process, designed to play nicely inside the Prince2 framework - 
has enabled us to work closely with clients including the The Pensions Regulator, the Driving Standards Agency, the 
Technology Strategy Board, the Criminal Records Bureau and Sheffield City Council.

In each of these projects we've used Open Source software; our development toolchain, our integration platforms, our 
hosting solutions, the content management system we use and the tools we use to collaborate with the clients are all Open 
Source.

In development, we use a great many tools and libraries, and of those, well over 90% are Open Source, and most of those are 
Free, at least as in beer.

[Slide: Recent application stack]

For example, you can see here my most recent project.

This project, which was delivered in less than a month from start to finish, was developed for a client in the property industry.
My team developed a case management system, integrated to several legacy systems in the client's data-centre. 

Every single piece of software, from the virtualisation software on the hosting platform, through the OS, database, 
application framework and development tools, was Open Source.

Even during the User Experience phase, we used the Twitter Bootstrap framework to deliver a flexible UI prototype, in 
preference to using Photoshop or other proprietary software to deliver graphical concepts.

In addition, a significant portion of the bespoke code that we wrote, which handles customised data import into the system, 
has now been released as LGPL-licensed Open Source code.

We used a very lightweight Scrum-based framework for this client, with several collaborative wireframing sessions, and a 
backlog of requirements shared using free online tools.

By working closely with the customer we determined the initial requirements, and we evolved them over the three week 
life of the project; the final product was significantly different to the initial brief, but perfectly fits the client's current 
business processes.

[Slide: TSB arch diagram]

As a larger scale example, for the Technology Strategy Board, we employed a hybrid lean & agile process to deliver a 
platform based on social networking technology. This project has now been running for four years and over 20 releases to 
production.

It's based on the Liferay Portal Server, in combination with SugarCRM, MySQL, the ServiceMix ESB and the JasperSoft BI 
Suite.
The enterprise search solution on this platform is based on Apache Solr; we used it to replace an existing Autonomy IDOL 
implementation, and saved the client several hundred thousand pounds while delivering new, more powerful features.

We work very closely with the client. We have the client's product managers on site for several days a week on average, and 
we even have a set of desks permanently reserved for them to sit at. 

The process has evolved constantly since the project began. Though we started off with basic Scrum, which provided a 
simple framework and a set of rules for the inception of the project, we've worked with the client to find a way of working 
that suits their business practices and gives us the flexibility to deliver to rapidly changing requirements. 

It's no longer Scrum, but a totally bespoke process that we've developed over four years of close collaboration, and it suits 
the client perfectly.


[Slide: SCC arch diagram]

For Sheffield City Council, we delivered a content managed web platform based around Magnolia CMS, hosted on Ubuntu; 
in this case we didn't host the final solution, but worked with Capita IT Services, one of the UK's largest traditional systems 
integrators, to help them skill up in Magnolia, Ubuntu, Tomcat, Rabbit MQ and the other Open Source technologies we 
employed.

This project was delivered using the Scrum agile framework, working closely and iteratively with the Council - a traditionally 
very risk-averse, Big IT-centric and slow-moving institution. We used Open Source software and agile techniques together 
to rapidly deliver a working system, whilst also educating the Council about the benefits of agile - so much so that they're 
now running their own agile projects without external involvement.

During the Sheffield City Council project, and later projects, we've started working with the Government Digital Service, 
who are breaking new ground in the rapid delivery of low-cost, user-centric services in the central government space.
Through working with them, we've realised that the ways of working we've promoted within our client base are very much 
in line with those of GDS - regular releases, agile techniques, and a reliance on Open Source software wherever it makes 
sense - which is most places!


Challenges
----------

[Slide: challenges]

In some cases, we've experienced push-back from clients on our use of Open Source technologies. 

This has often centred around supportability; our answer has been that if we're hosting the platform, we'll support the 
technology and back off the risk ourselves as appropriate, and if we're not hosting it, we'll work with you to train and equip 
your teams to manage the solution in Business As Usual.

Sometimes we've been asked if Open Source software is somehow "less secure" - that's an easy one to deal with, as there 
are numerous peer reviewed studies giving empirical evidence to the contrary.

And sometimes we've been told that the organisation simply has a principle of using Commercial Off The Shelf Software ... 
we can remedy that by recommending any of the excellent commercial Open Source vendors we work with, from Liferay 
to MySQL and Magnolia CMS.

In the same way, I've faced challenges with introducing agile methods into traditional public sector organisations.

Typically, these can be expressed as:

 * What am I going to get?
 * When am I going to get it?
 * How much is it going to cost?

There are some obvious, quick answers to these questions - the main one being that you're going to get what you ask for, 
when you ask for it, for an amount equal to the size of the team multiplied by the time to develop the feature.

That's the quick answer - but these quick answers don't really help anyone who needs to ask the questions.

The best answer by far is a decent conversation, a friendly working relationship and a degree of trust - which is difficult to 
achieve in an industry that's predicated on not trusting your suppliers, on assuming that they're out to bleed you dry.


The future
----------

[Slide: The future]

Projects like the ones we've conducted with local authorities and the ongoing work of the Government Digital Service are 
pointing the way; to where decisions are taken on the basis of empirical evidence, and where lightweight procurement 
processes, combined with robust knowledge of the realities of IT implementation - rather than the rosy picture painted by 
traditional vendors - are used to engage suppliers who can really deliver.

I believe that the collaborative, transparent nature of agile delivery, combined with the benefits of Open Source software, 
opens up a brighter future for public sector IT projects, where iterative enhancements can be layered on top of each other 
to improve user experiences and realise efficiencies.

By introducing realistic analysis of the benefits and risks of these approaches, we can work to educate the Public Sector that 
it's possible to have solutions that are cheap to build, cheap to run, and that deliver to the end users on an ongoing basis, 
without tying ourselves to vendor lifecycles that could limit our flexibility.

In a world of changing regulations and politics, using Open Source software, delivered in an agile way, will mean we can 
serve our customers - even if we don't know now, what we'll need later.

 	



