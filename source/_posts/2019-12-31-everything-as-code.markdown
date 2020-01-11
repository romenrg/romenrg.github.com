---
layout: post
title: "Everything 'as-code'"
date: 2019-12-31 20:14
updated: 2020-01-11 11:45
comments: true
categories: [Software Development, DevOps, Management]
description: "In the software industry, 'infrastructure as code' and 'configuration as code' have become popular DevOps concepts. But the 'as code' idea can be applied to everything else in a software company, from documentation to training. We achieved 'training as code' in CloudBees University by doing everything 'as code' for our trianing platform and courses"
keywords: as-code, everything as code, infrastructure as code, configuration as code, training as code, CI/CD, devops, jenkins, cloudbees, dwjw, devops world, jenkins world, talk
twitterimg: "/images/dwjw2019_lisbon_talk.jpg"
---
If you are in the software industry, and specially if you are in the DevOps space, you are probaby familiar with the concepts of "Infrastructure as code" and "Configuration as code", which are very popular lately. But, what if that same idea could be applied to everything else in a software company? Aren't documentation and training great candidates for becoming "as-code" as well?

<img src="/images/dwjw2019_lisbon_talk.jpg" alt="Picture taken during the presentation at DWJW 2019. I'm showing the tech stack of the new CloudBees' training platform" />

During 2019 I've been intensively working in this idea at [CloudBees University](https://standard.cbu.cloudbees.com/), along with my colleagues. Nowadays, for our training platform and courses everything is done "as code".

Sounds interesting? Keep reading to learn more about it and/or watch the ["Training As Code" talk](https://www.romenrg.com/blog/2019/12/31/everything-as-code/#training-as-code-talk) my colleague Mark Waite and I delivered at DevOps World | Jenkins World in December 2019.

<!-- More -->

## Infrastructure and configuration as code

Moving infrastructure definition and application configuration to code has been a huge step forward for us as an industry. It has allowed us to automate many "opearions" tasks, saving significant time, reducing human errors and allowing us to have a clear "state" of our software products, their infrastructure and configuration. And it has also contributed to bridge the gap between "development" and "operations", improving collaboration between these teams.

When it comes to tools and technologies, Terraform, Chef, Puppet, Salt, Ansible, Docker and Kubernetes, among others, have played a crucial role in this movement; enabling engineers to describe infrastrucutre and configuration as code.

## How about documentation?

It's been a while since many technologies and tools have shifted their documentation to code. Many of the most popular open source tools are hosted in GitHub, and typically most of them contain at least a README file in the repo itself, often written in Markdown (but can also be written in alternative languages, such as [AsciiDoc](http://asciidoc.org/)).

Also, blogging tools, like [Jekyll](https://jekyllrb.com/), have geared to this concept as well; using Markdown files to represent the different posts, that are later rendered into HTML.

And this trend is also accelerating. Nowadays I see many relevant projects and tools shifting their documentation sites to code. Among the benefits, not only does it allow us to treat everything that belongs (or relates to) a software product equially, but it also improves collaboration between teams. Engineers are much more likely to contribute to documentation if it is written as code, and specially if it is in the very same repo in which the code is. This shift is actually helping to break silos again, as it did between development and operations.

## Combining these concepts in CloudBees University

In CloudBees University we offer several courses, most of them focused on [Jenkins](https://jenkins.io/) (targeting audiences with different level of knowledge in Jenkins administration or Jenkins Pipelines). Those courses are highly technical and have significant "hands on" pieces. The content is displayed as a website, while for the hands on part, we provide students with lab environments in which they have the different tools they need for the course, with the specific configuration needed for the different exercises they have to complete.

### Everything "as code"

Needless to say everything is done as code, from our content to the lab environments and their configuration.

Want to know more? Mark and I explained all the details in our talk at DevOps World | Jenkins World 2019, which we recorded and is available here:

<h3 id="training-as-code-talk"> Training As Code: Applying CI & CD to Training Development</h3>

<iframe width="560" height="315" src="https://www.youtube.com/embed/1hda-bVYaVc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

As we said during the talk, we are still learning and improving, but it's been a great experience. This approach has allowed us to achieve things that wouldn't have been possible if we were relying on manual tasks. Now we have a single source of truth for everything in CloudBees University, we have peer-reviews for any change we make, clear versioning and history and, of course, fully automated [CI/CD](https://www.romenrg.com/blog/2017/12/31/continuous-integration-delivery-deployment/) processes, for integrations and deployments.

Now, how about you? Are you doing "everything as code" already?

<div class="revisions">
  <h2>Significant revisions</h2>
  <p><em>2020, Jan 11</em>: Major rewrites to the article. First "public" version.</p>
  <p><em>2019, Dec 31</em>: Original draft.</p>
</div>

