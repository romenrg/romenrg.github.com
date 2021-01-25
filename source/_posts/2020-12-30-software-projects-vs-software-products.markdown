---
layout: post
title: "Software Projects vs Software Products"
date: 2020-12-30 13:26
updated: 2020-01-10 19:00
comments: true
categories: [Software Development, Management, Entrepreneurship]
description: "Do you work on software projects? Or are they software products? According to definitions, projects are time-constrained efforts, supposed to have a defined beginning and end. This clearly-defined temporary nature does not apply to products, which don’t have a predefined beginning and end in time, being subject to market demand. The same applies to fixed scope. Products evolve constantly. As an industry we should talk more about software products, instead of projects"
keywords: software projects, software products, agile software development, lean startup, open source products, outsourcing, building products
twitterimg: "/images/products_vs_projects.jpg"
---
As a developer, you work on software projects, right? ...Or are they _software products_?

Like many others in the software industry, you might think those two concepts are synonyms; but they aren’t. In fact, whether the software being developed is considered a project or a product may have critical and non-trivial ramifications, in many aspects.

<img src="/images/products_vs_projects.jpg" alt="Team meeting in which multiple colleagues discuss in a table, where several computres are opened. One man moves hands displaying confusion" />

The _not-so-subtle_ differences between software projects and software products actually have a huge impact on our behavior, both from a business as well as from an engineering perspective.

<!-- More -->

For many years I’ve been trying to find the time to write about this key difference, to which many people in tech fail to give importance to. About a year ago, I had the opportunity to give a [lecture](https://www2.slideshare.net/romenrg/agile-software-development-beyond-projects-ull) on this very topic. And now, I have finally decided to write about this important topic in more detail.

I'll start with definitions, digging into the key differences that derive from them. Afterwards, I'll explore the critical behavioral ramifications. However, if you just want a quick summary, feel free to jump directly to the [comparison table](#detailed-comparison).

## Let’s start with some definitions

If we want to get a clear definition of "project" and “[project management](https://www.pmi.org/about/learn-about-pmi/what-is-project-management)", the Project Management Institute (PMI) can probably be of some help. From their site we can extract two clear sentences that are relevant in this context:

 * A **project** is temporary in that it has a defined beginning and end in time, and therefore defined scope and resources.
 * **Project management**, then, is the application of knowledge, skills, tools, and techniques to project activities to meet the project requirements.

Now, if we try to look for definitions of “[product](https://en.wikipedia.org/wiki/Product_(business\))” and “[product management](https://en.wikipedia.org/wiki/Product_management)”, we can probably summarize them as:

 * A **product** is an object or system made available for consumer use; it is anything that can be offered to a market to satisfy the desire or need of a customer.
 * **Product management**, then, drives the business case for product development and has an active role throughout its development, test and launch; being also involved in product change and lifecycle decisions and planning.

Can you tell the key differences already?

## Digging into the differences

### Two key differences, from definitions

From the definitions above, we can clearly see the first big difference: the temporary nature of a project. **Projects are time-constrained efforts**, supposed to have a defined beginning and end date. This clearly-defined temporary nature does not apply to products, which don’t have such predefined beginning and end in time, being subject to market demand instead.

Moreover, those clearly defined time boundaries for projects also bring the second clear distinction: fixed scope and resources (i.e. the project requirements). This doesn’t apply to products either. **Products are evolving creatures by nature**. While project management cares about meeting those predefined project requirements; product management cares about the business case for the product, constantly learning from users and having an active role in the product lifecycle, defining new features and/or re-prioritizing work, adapting to market needs.

### <a id="detailed-comparison"></a>Detailed comparison

When I was preparing my lecture, I found a very nice article by Sriram Narayan in Martin Fowler’s blog. In his article, Sriram added a very comprehensive [table comparing project-mode and product-mode](https://martinfowler.com/articles/products-over-projects.html#WhatIsProduct-mode).

For this article, I have created my own simplified table; focusing only on some key aspects I would like to compare for the two cases.

Aspect                                  | Project                                   | Product                                                    |
--------------------------------------- | ----------------------------------------- | ---------------------------------------------------------- |
_Duration_                              | Fixed. Limited (e.g. _X_ months).           | Unknown. Depending on market (from _X_ weeks to _Y_ decades).
_Scope_                                 | Supposedly known and fixed.               | Unknown. Constant learning and adaptation is assumed.
_Costs_                                 | Supposedly known and fixed.               | “Pay as we go”, i.e. weekly / monthly / yearly (e.g. salaries).
_Technical quality_                     | Not rewarded; thus, not prioritized. Projects are seen as one-off efforts, so maintainability is not valued. | Critical. Product development is a continuum. Technical excellence is key to keep up the product’s iterative and incremental evolution.
_Key mindset aspects_                   | Fixed mindset. “We know what we have to build”. So, “just do it”. Don’t question things. | Learning mindset. “We are constantly learning and adapting”. Data-driven. Question decisions constantly.
_Key engineering skills_                | Framework-specific knowledge. <br/><br/> Everything is fixed, from features to technologies. "We just need to write the code as quickly as possible". | [Evergreen development skills](https://github.com/romenrg/evergreen-skills-developers). <br/><br/> Everything may change, from features to technology. "We need to learn and adapt constantly". "We apply technical best practices". "Teamwork, mentoring and collaboration are key".


## Software development is mainly about building products

[Software development involves many unknowns](https://www.romenrg.com/blog/2015/09/28/why-asking-developers-for-time-estimates-in-software-projects-is-a-terrible-idea-and-how-to-bypass-it-with-scrum/#the-role-of-evil-contracts). Those unknowns make it extremely hard for us to have the certainties "projects" require upfront. At the beginning is when we know the least about the software what we are building.

### In the digital economy, software evolves constantly

Think of the software you use in your daily life. Isn't it always evolving? You receive constant updates, not only for bugfixing; but also to add new features, [improve the UX](https://www.romenrg.com/blog/2013/01/02/improving-the-ui-to-achieve-a-better-ux-my-experience-in-stat4you/), or even to remove pieces that are no longer relevant.

Does this fit into the definition of "project" we saw before? Do these applications have “a defined beginning and end in time”? And how about scope and resources, do they seem to have been fixed upfront?

Change and evolution are natural in products, but not in projects. Projects don't welcome change. And software evolves constantly.

### Software products and outsourcing are not a good fit

Traditionally, it has been common for non-software organizations to outsource software development initiatives. For instance, Government agencies typically outsource their “software development projects”, even though in most cases they should have been thinking in terms of software products instead.

Think of an e-gov application in which citizens can perform their bureaucratic obligations from home. Isn’t that a software product? It will have to evolve, as new laws are passed. And it is not supposed to have a predefined teardown day. Instead, we would probably expect it to be there for the long run. Over time, citizens (users) will discover bugs, which will have to be addressed; and we will likely complain about it and/or suggest improvements. There might also be scalability issues and/or outages that will have to be tackled.

Treating these software products as outsourced projects means that the owners will hire an external company to build it. Usually the cheapest. The project will have a fixed scope, and the parties will agree on a timeline and on a price. The external company will complete the project, according to those parameters and hand it over to the customer. Then, usually, the external company forgets about it. If changes are desired in the future, new projects will be defined and outsourced. Often to different companies.

In most cases, the company that is hired to build the software is not involved in the discovery process with potential users. They are not involved in the prioritization of features. They are just hired to do X, as quickly and cheaply as possible. And since they are not rewarded for software quality nor for asking questions, they will probably build it without maintenance in their minds. And they won’t question decisions nor worry about gathering data.

Now, think how different it would be if it was treated as a software product, with an in-house team building it and participating in all the process, from conception to evolution. The team would understand needs, motivations and strategic goals; they would be engaged. They would ask questions. Hypotheses could be defined together and data collection and learning would be in everybody’s mind since the beginning. Working in small increments would be easier. Writing maintainable code becomes crucial. Changes are welcome. And quality matters.

Being aware of the importance of software products in the digital economy means that, if your software is (or is becoming) the core of your business, then you keep software development in-house. Nowadays, every company is a software company. Think of Airbnb, Lyft or Netflix. These businesses could have opted to externalize software development, but they realized the software products they were building are the core of their business. They realized they were software companies.

### How about open source "projects"?

It is common in the software industry to hear people refer to “open source projects”. In most cases, though, I would argue we should be talking about “open source products” instead.

I have been an open source software (OSS) user for many years, and I have also contributed to open source myself. One example of OSS to which I have contributed is [Jenkins](http://jenkins.io/). Jenkins is the leading open source automation server. It has been around for more than 15 years, with millions of installations worldwide. And it has evolved significantly, including the rename from Hudson, the recent UI changes, and the thousands of ever-evolving plugins, created by a thriving open source community. Based on this data and the previous definitions, should we consider Jenkins an “open source project” or, rather, an “open source product”?

I understand that, when somebody (like Kohsuke with Jenkins) starts to build an open source software, they might have a limited and well defined idea. And they may work on a “project” to make it happen. A project to build the first set of fixed features for their idea. But then, if it is successful, that initial project leads to a product that keeps evolving in unanticipated ways. Scope is no longer fixed, as the community starts to bring new ideas and prioritize their development; and there is no defined “end date”.

Successful open source "projects" are here to stay, for a long time. But their success will keep them evolving within their communities, as _software products_.

## My personal take

As you may have guessed after reading this article, I’m a big fan of building software as products. I have built many in my career; and [I’ve learned a lot](https://www.romenrg.com/blog/2015/03/17/10-plus-1-valuable-lessons-i-learned-from-my-failed-startup/) from those experiences.

But building software as products is not just what I enjoy the most. It is truly the way I believe we should be building software, to get the most out of it.

Software projects are dead. Long live _software products_.

<div class="revisions">
  <h2>Significant revisions</h2>
  <p><em>2021, Jan 10</em>: Improved introduction, incl. reference to comparison table, as a TL;DR resource.</p>
  <p><em>2020, Dec 30</em>: First version published.</p>
 </div>
