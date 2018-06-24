---
layout: post
title: "The Programmer Bill Of Rights, Revisited"
date: 2016-11-15 18:34
updated: 2018-05-06 15:15
comments: true
categories: [Software Development, Management, Entrepreneurship]
description: "There are at least 10 basic rights, fundamental to the quality of work life for a software developer"
keywords: programming, rights, best practices, monitors, autonomy
twitterimg: "/images/two_monitors_unsplash.jpg"
---
10 years ago, [Jeff Atwood](https://en.wikipedia.org/wiki/Jeff_Atwood) wrote an article he titled [The Programmer Bill of Rights](https://blog.codinghorror.com/the-programmers-bill-of-rights/). In that article he described 6 fundamentals that companies should provide for programmers to be successful and work to their full potential, thus maximizing their productivity.

<img src="/images/two_monitors_unsplash.jpg" alt="Picture of a programmers desk with two monitors, one of them showing code" />

Sadly, ten years later, many companies still deny these basics to their developers, even though the business case for these six points is absolutely proved.

In this article, not only would I like to update the original 6 principles, providing further evidence of their importance; but also I would like to extend the list. Based on my experience during the last 10 years, I will propose 4 new fundamentals that I consider absolutelly necessary for the daily work of any programmer, developer or software engineer. Let's get started:

<!-- More -->

## 10 Fundamental Programmer Rights (6 + 4)

It is worth mentioning that, despite the headline, *this article does not refer to general Labor Rights, since those are usually well-known and its compliance is required by law. This article focuses only on aspects that are specific to software development*, aspects that are usually not regulated, but have a huge impact on programmers' daily work.

### The 6 Original Rights proposed by Jeff


1. **Every programmer shall have two decent monitors**. <br/>
Apart from the scientific studies Jeff linked in his article in 2006, [many others have emerged more recently](http://techreport.com/news/14343/more-bigger-monitors-boost-productivity-says-study), proving the productivity benefits of having two monitors while programming. [Some studies even suggest having three monitors](http://www.computerweekly.com/news/2240088457/Multiple-monitors-boost-productivity-by-355).
However, I have met some engineers that prefer to choose one big (27”) monitor rather than two smaller ones; and that should definitely be OK if that is her preferred set-up. *The key here is that companies should be wise enough to provide developers with the tools they need to take their productivity to the maximum.*
Also, developers working on User Interfaces and graphic designers care a lot about other characteristics such as colors or bright; so again, it is not just about the screen size, it is about taking your employee into account when providing the tools he needs to perform his job in the best possible way.
How is it possible that some companies do not pay attention to this at all? As many people pointed out in [this slashdot discussion about the topic](http://developers.slashdot.org/story/11/05/16/1957210/do-developers-really-need-a-second-monitor), the cost of a decent monitor may be around $150 - $200 nowadays. That is a ridiculous amount compared to [the salary of a developer](http://money.usnews.com/careers/best-jobs/software-developer/salary)… So it cannot be about the money; since we know that the productivity increase would pay off in just a few days. Sadly, refusals from management to provide the right tools to employees are a clear sign of toxic management or toxic company culture and [if you find yourself in that situation, you should consider looking for a new job *ASAP*](#toxic-management-denying-rights).

2. **Every programmer shall have a fast PC**. <br/>
Although this claim still makes total sense, I think this one is one of the easiest-to-get for management and non-tech people, since everybody has suffered a slow pc and can relate to it more easily. However, I have seen cases in which developers have to connect to a remote machine using a remote desktop. This may cause some performance issues, as well as other problems such as non-functioning shortcuts or hardware compatibility problems. Unless there is a very clear reason to use a Remote Desktop, it should be avoided. As Jeff stated 10 years ago, every developer should have a fast computer that allows her to do all she needs to get her job done.

3. **Every programmer shall have their choice of mouse and keyboard**. <br/>
To be honest, I’m not especially picky with mouse and keyboard, but some developers are… So if you are a manager and one of your developers complains about his keyboard and mouse… Do not waste any time thinking, we are probably talking about less than $50 here. It’s not worth discussing. If his choices are very specific or expensive, at least allow him to bring his own keyboard and mouse from home. Diversity in a company is enriching, so don’t try to treat all your employees as if they were clones.

4. **Every programmer shall have a comfortable chair**. <br/>
I hope this is obvious to everybody in 2016. [Having an ergonomic chair and sitting correctly is a health issue](http://ergo.human.cornell.edu/AHTutorials/chairch.html). In fact, many countries have already created [health-and-safety regulations for office chairs](http://www.hse.gov.uk/pubns/priced/hsg57.pdf). Moreover, money is not a big deal either now, since [there are good chairs for $200](http://www.ikea.com/us/en/catalog/products/00103102/). Also, it is worth mentioning that in recent years the [benefits of standing desks](http://ergonomics.about.com/od/office/a/Benefits-of-a-Standing-Desk.htm) have become popular, so it could be something to consider. Once again, when it comes to the tools to be used on a daily basis at work, like chairs, the best approach would be to involve employees in the decision. We all may have different preferences, based on our height, weight, back problems, etc…

5. **Every programmer shall have a fast internet connection**. <br/>
For this claim, the same as in the “fast PC” sections has happened. Apart from the widespread access to broadband internet at low prices; services like Youtube, Netflix, online games and Skype/Hangouts video-calls have made us a great favour. Thanks to them many non-technical managers have realised about the importance of a fast internet connection, making it a default in most companies.

6. **Every programmer shall have quiet working conditions**. <br/>
This is a tricky one. Nowadays most offices are open-plan. Moreover, collaboration is encouraged in agile teams. All this makes it difficult to keep quiet working conditions for us to concentrate. Many [relevant people in the industry are raising concerns about this](https://twitter.com/jasonfried/status/794212152206729216). However, [there are some things we can do](https://hbr.org/2015/03/stop-noise-from-ruining-your-open-office), such as having (and using) meeting rooms, having white noise generators to mask voices, wearing headphones to concentrate (which I usually do) and/or use an indicator to show coworkers if you can or cannot be interrupted. Even though many jobs require concentration, getting to “flow state” is vital to accomplish most programming tasks, as Jeff mentions.

### My 4 Proposed Additions

7. **Every programmer shall be free to choose her preferred IDE**. <br/>
In the past it was common to have the build and/or deploy process of the application being developed attached to the IDE (usually by means of a plugin). Fortunately, nowadays the use of build tools has become mainstream, making our build processes IDE-independent. For example, in the Java community, build tools like maven or gradle make it possible for developers in a team to use different IDEs such as Eclipse, Intellij IDEA or any other editors, without any problems of collaboration. They just need to use a version control system (such as Subversion or Git) to share changes and a build tool to generate artifacts. In such environment, forcing developers to use an standardized IDE seems to be only a poor resource of old-school managers used to the “command-and-control” approach to impose their rule. That imposition can only cause a low morale among team members, decrease motivation and cause brain drain in the team, since many talented developers will leave to a more open-minded company.

8. **Every programmer shall have admin rights on his computer**. <br/>
Last year I was introduced to a company that had recently been created with the idea to enter in the software development market. However, I was utterly surprised when I got to know that this company didn’t allow developers to have admin rights in their computers. This is pure nonsense. [As this fantastic answer in Stack Overflow states](https://stackoverflow.com/a/701361), developers in their daily work need to install software for different development purposes (editors, servers, databases, API clients...), they need to change different system configurations for different purposes and, most importantly, they need to be comfortable at work in order to give the best of themselves. Restricting admin rights to developers will only lead to a high turnover rate, inability to retain competent people, poor morale and poor quality delivery. Probably, [as this other comment states](http://stackoverflow.com/questions/701214/should-developers-have-administrator-permissions-on-their-pc#comment526142_701214), "if you walk into a job as a developer and find you have no admin rights in your machine, the best choice is to not come back the next day".

9. **Every programmer shall have access to the big picture**. <br/>
Sometimes programmers are not presented with the big picture of the system they are contributing to build, but instead they are given small tasks to do, with narrow descriptions. In those cases, they often do not have direct access to the product owner nor the end users of the software they are working on. This usually causes trouble, since many wrong decisions can be made and many misconceptions can be created. To design software that can evolve properly in the desired direction, developers should understand the big picture, the whole system that is being built, not only the small task that has been assigned to them at one point. Moreover, developers should be free to ask as many functional questions as they need, so they can make the right design decisions and write software that can evolve as expected, avoiding later problems.

10. **Every programmer shall have autonomy in his daily work**. <br/>
As any other creative process, programming requires autonomy. That is why agile frameworks, like [Scrum](https://en.wikipedia.org/wiki/Scrum_\(software_development\)), propose planning work for periods of a week, 15 days or a month; so developers can organize themselves in between. Daily meetings can help detect and resolve problems, as well as keep the development team in sync; but freedom for each contributor to organize his workday without suffering micromanagement should be preserved. The need for autonomy also applies to the programming process, where creativity is key to problem-solving. Some developers prefer to solve a task by creating some tests first, others build a monolithic function and then refactor it, others start by understanding the existing codebase and doing some diagrams... Any of these approaches should be respected, as long as basic agreements of the team (e.g. *"definition of done"*) and quality standards (e.g. *minimum test coverage*) are met.

*What do you think about these additions? Please, join the conversation!* <br/> *Are these rights being respected at your company?*

> ### <a name="toxic-management-denying-rights">A real case of toxic management denying many of these rights</a>

> Unfortunately, there are companies that keep denying many of these basics today.

>I recently saw a case in which a manager refused to replace a defective monitor with obvious flickering problems to an employee (even though flickering may cause dizziness, fatigue and headaches). This very manager was also forcing programmers to work with only one squared 19” monitor (for no reason). He firmly refused to buy second monitors and even forbade some developers to bring a second monitor from their homes… Does it make any sense? However, this guy had two wide monitors in his desk, of course. I guess he just wanted to show that there was a big difference between him and his “subordinates”, who had to be controlled and treated like clones.

>As with any other of these rights, a reluctance to provide programmers with two monitors not only shows that your manager or the company board do not care about your opinions or comfort; they don’t even care about productivity. It is definitely a red flag. Taking into account the ridiculously small cost of monitors nowadays, even worrying about it shows a clear case of being “penny wise, pound foolish”.

>But that’s not all of it. Usually, when an old-school command-and-control minded manager is violating one of these basics, is probably violating many others, since they are all tightly-linked and it is all about mindset and company culture.

>In this particular case, this very manager was also forcing developers to use a three-year-outdated version of Netbeans as IDE, with no front-end support (significantly diminishing their productivity). And, by the way, he had also decided to forbid admin rights to programmers in their own machines (making their daily work absurdly complicated)... So you see, three basics at once. Not to mention that micro-management was also one of the company core values. The micro-manager used to interrupt programmers every hour to closely control their tasks, taking away all the autonomy and long-term vision from the developer.

>If you find yourself in a case like this one, my advice cannot be clearer: there are many companies that will be glad to provide the tools you need to achieve the best results in your daily work, so don’t wait anymore, move on. No one should work for a tyrant like that.

As an ending to this article, I would like to borrow the last paragraph from Jeff’s article: “The few basic rights we're asking for are easy. They aren't extravagant demands. They're fundamental to the quality of work life for a software developer. If the company you work for isn't getting it right, making it right is neither expensive nor difficult. **Demand your rights as a programmer!** And remember: you can either change your company, or you can *change your company*”.

<div class="revisions">
  <h2>Significant revisions</h2>
  <p><em>2018, Apr 27</em>: Clarified the last two 'rights', improving grammar and style. Minor corrections in the example section were also included.</p>
  <p><em>2016, Nov 15</em>: Original version published.</p>
</div>
