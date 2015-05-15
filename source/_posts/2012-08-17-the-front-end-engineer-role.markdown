---
layout: post
title: "The Front-end engineer role"
date: 2012-08-17 20:27
comments: true
categories: [Front-End]
description: The Front-End Engineer role has become vital to develop modern web apps. Apart from client-side javascript code, work may include API design, HTML and CSS.
---

<p>The Front-end engineer is a relatively recent role in software development, but its importance is growing everyday as the importance of Javascript does. I've been working as a front-end engineer in the <a href="http://www.stat4you.com">Stat4you</a> project since January and in this article I will try to describe this role, emphasize its importance and highlight the differences that the introduction of Javascript has brought to the development of the front-end of web applications.</p>

<p>I would like to introduce this article with a quote from the human-computer interaction expert Jeff Raskin that summarizes quite clearly the importance of software interfaces from the perspective of users. It reads: <em>“As far as the customer is concerned, the interface is the product”</em>.</p>

<p>Although the quote above seems quite obvious, often developers and managers tend to forget or underestimate the importance of user interfaces, blinded by the complexity of the back-ends of the applications. This blindness has led many projects to failure, but fortunately this is starting to change.</p>

<p>In order to continue highlighting the importance of user interfaces, there is another quote from Linus Torvalds on this topic which I also fully agree with: <em>“In many cases, the user interface to a program is the most important part for a commercial company: whether the programs works correctly or not seems to be secondary”</em>.</p>

<img src="/images/angry.jpg" />

<!-- More -->

<p>Quite often, traditional developers teams give priority to the development of new and complex features (which mostly will never be used by the majority of end-users) instead of spending the time in the creation a friendly and easy to use interface. This frequently results in a hard-to-use application with a lot of functionalities that will never be used due to the poor user experience caused by its unfriendly interface. Thereby, many projects meet with failure due to usability issues rather than lack of functionalities, as Linus Torvalds said.</p>

<p>But… <em>What is exactly the interface?</em> And, <em>who develops it?</em> For many years there hasn’t been a figure in the development process dedicated exclusively to interfaces. Usually there was only the general concept of developer or programmer, who sometimes coded the business logic or the services, while in other occasions had to control user events or choose the color of the buttons and the way the information had to be displayed.</p>

<p>It is true that it has been years since there is also a role related somehow with interfaces. It is called the designer, but usually this role is related to someone with an artistic background, most of the time it is someone who works fine creating images with Photoshop, but with little or none technical knowledge about HTML, CSS and Javascript. This kind of professional cannot be considered a Front end engineer. It is just a graphic designer.</p>

<p>Working on this article I found an <a href="http://htmlcssjavascript.com/web/the-front-end-engineering-spectrum-the-three-generic-types-of-front-end-engineers/">interesting categorization</a> done by Rob Larsen in which he describes three profiles of front-end engineers: “the creative” (who would be probably a designer with HTML and CSS skills), “the coder” (who would be a javascript programmer, also strong at CSS and HTML but probably weak at design) and there a last one, named “the core” (this would be somewhere in the middle of the other two).</p>

<p>The profiles defined above are rather wide, but I find them quite accurate. In my case, due to my programmer background and these last months focused on javascript I fit probably better into “the coder” although I see something of me in “the core” profile. Probably I was in this profile years ago, before studying at university, when I was interested in the web in general and I started learning both design and programming by myself. Then, at university I started to learn more about programming and I became more “coder”.</p>

<p>Reading <a href="http://htmlcssjavascript.com/web/the-front-end-engineering-spectrum-the-roles/">another post</a> of Rob Larsen in which he describes the different front-end roles, I found his <strong>description of a “Front end developer”</strong>. He defines it as someone who is “responsible for HTML, CSS and JavaScript templates and prototypes at the beginning of development and remains heavily involved with the integration and QA phases of a site build. This person is solely focused on the presentation layer. While one might occasionally help out with tasks on either the design side or the server side, 95% of the work done in this role is in the narrow band defined above.”. He also says that this role is for a “core” or a “coder” who is happy to focus in javascript as his main programming language. I think that in the project I'm working on right now I fit in this description of front-end engineer fairly well.</p>

<p>About the old concept of designer, Rob Larsen says: <em>“The general trend of the front end engineering spectrum is expanding away from this type of role”</em> mainly due to the importance of javascript.</p>


<img title="The front-end layers" src="/images/applicationLayers3.png" />

<p>In the image above, we can see the distribution of tasks between front-end and back-end in a web application. In the case of the front-end I have separated it in two columns: on the right side we have the traditional web application (where the presentation code is in the server) and in the left side we have the modern concept (with javascript controllers in the client side).</p>

<p>Nowadays with the growing importance of Javascript and the single-page applications, the controllers of the web applications are being moved to the client using javascript MVC frameworks such as Backbone.js, with the goal of providing a more fluid user experience akin to a desktop application. In our case, we have thinned the server side significantly with this approach. The server side provides a REST API from which the client consumes the services. The client sends AJAX requests to the API and the server sends JSON responses with the information required. </p>

<p>Thus, in our case the information processing and the built of the web interface are done in the client side by the front-end engineer, using Javascript for the behavior and HTML and CSS for the markup and styles. For us this has been possible and maintainable thanks to the help of many frameworks, libraries and tools such as Backbonejs, Underscorejs, jQuery, D3js, Highcharts, Jasmine, Handlebars, Less and the Google Chrome Inspector for debugging. Surely, I would write about some of them in more detail in future.</p>

<br />

<p>So, in conclusion, front-end engineering is not designing, even though the design is a part of the front-end of an application. A front-end engineer must be someone focused on the presentation layer, mainly responsible for HTML, CSS and JavaScript templates and prototypes even though might occasionally help out with tasks on either the design side or the server side. With the growing importance of Javascript and the help of frameworks and libraries the controllers are being moved to the client side and being written in Javascript, leading the front-end engineers to focus on this programming language.</p>

