---
layout: post
title: "On Software Engineers' Productivity: Beyond Misleading Metrics"
date: 2024-12-31 20:35
updated: 2025-01-01 01:00
comments: true
categories: [Entrepreneurship, Management]
---
The question of how to measure software developers' productivity has long been a subject of debate in the tech industry. New versions of old misguided approaches, such as counting the "number of lines of code" written, resurface, over and over again, despite not reflecting value creation over and over again. 

<img src="/images/measuring-software-engineers-productivity.jpeg" alt="An image of the home office of a remote worker, where his mac laptop screen displays a Zoom meeting" />

In fact, setting incentives based on such metrics can lead to counterproductive behaviors, as explored in "Reinventing Organizations" by Frederic Laloux. The book highlights how traditional incentive systems often undermine intrinsic motivation and foster a culture of gaming the system rather than pursuing genuine excellence.

<!-- More -->

## The Pitfalls of Misleading Metrics

### Number of Lines of Code

The "number of lines of code" metric (LOC) is perhaps the most infamous example of a misleading measure. While intuitively appealing due to its simplicity, it fails to account for the true purpose of software development: solving problems efficiently and effectively. In fact, fewer lines of well-crafted, maintainable code are often more valuable than sprawling, complex implementations.

Consider the case of IBM in the 1980s, where developers were incentivized to write more code. The unintended consequence was a proliferation of verbose, redundant code that increased maintenance costs and slowed progress (from the documentary “Triumph of the Nerds”). Similarly, in 1982 in Apple, some managers in the Lisa software team were asking engineers to weekly submit the number of codes they had written, to measure productivity. This finally stopped when the, arguably, most important Lisa implementer, [Bill Atkinson](https://en.wikipedia.org/wiki/Bill_Atkinson), famously reported “[-2000 lines](https://www.folklore.org/Negative_2000_Lines_Of_Code.html)” the very same week he had made changes to an algorithm to make it 6x faster; thus highlighting the absurd nature of the LOC metric and its absolute disconnect with the actual impact of the work of engineers.

### Number of Commits

Another misleading metric that has somewhat replaced LOC in the GitHub era is the "number of commits." While frequent commits can indicate progress, they do not inherently reflect the quality or significance of the work. A developer making small, incremental improvements adds value, but using this metric as a primary measure can incentivize meaningless, fragmented, or even broken commits later fixed in subsequent ones just to bump the metric. Similarly to the LOC metric, this approach may discourage thoughtful, cohesive, simpler and more readable changes that are better for the project in the long term.

### Bug Count as a Standalone Metric

Another problematic metric is the number of bugs fixed. While fixing bugs is crucial, a focus solely on this metric can incentivize developers to neglect proactive measures like writing tests or addressing root causes of recurring issues. This approach risks significant business impact when unstable software reaches production. Worse, it can create perverse incentives. Developers may be tempted to introduce issues they later resolve, gaining recognition at the cost of overall product stability. The metaphor "rewarding firefighters creates a culture of arsonists" aptly describes how praising bug fixers can lead to these harmful behaviors.

## Designing Meaningful and Nuanced Metrics

Apart from all the above, one of the most problematic aspects of the simple metrics described before is that they distort the real work of Software Engineers, who contribute to the success of a project in many ways beyond just writing code.

When designing metrics to assess the productivity of Software Engineers, we need to take into account several different aspects that reflect the diverse nature of their work, many of which are difficult to quantify:

### 1. Long-Term Impact of Solutions

Measure the durability and adaptability of solutions. A developer who designs a system that scales effortlessly with growing user demand or integrates seamlessly with future technologies has delivered significant value. Metrics like the stability of code over time, adaptability to new requirements, and low frequency of critical bugs highlight long-term impact. These metrics are not trivial to calculate, although some authors dig into them, for example in "Accelerate: The Science of Lean Software and DevOps" by Nicole Forsgren, Jez Humble, and Gene Kim.


### 2. Total Cost of Ownership (TCO)

Account for the ongoing costs associated with a piece of software, including maintenance, infrastructure usage, and the complexity it adds to the codebase. Developers who minimize TCO by writing efficient, modular, and well-documented code provide substantial value. This is partly reflected in Martin Fowler’s “[Is High Quality Software Worth the Cost?](https://martinfowler.com/articles/is-quality-worth-cost.html)".

### 3. Collaboration and Mentorship

Effective software development is a team effort. The more senior engineers are, the more we must recognize their contributions to:

 * Mentoring junior developers.
 * Conducting code reviews.
 * Improving team processes.

These activities foster knowledge transfer and elevate the entire team’s productivity. For more on the importance of mentorship.

### 4. Explore Customer-Centric Metrics

Focus on the outcomes for end-users. Metrics like customer satisfaction (e.g. via Net Promoter Scores or feedback surveys), time-to-market for critical features, and user retention rates often indirectly reflect the real-world impact of developers’ work.

### 5. Quality Assurance Contributions

Value efforts in ensuring robust, maintainable software, such as:

 * Writing automated tests.
 * Implementing CI/CD pipelines.
 * Advocating for best practices.
 * Crafting readable and easily maintainable code.

### 6. Innovation and Creativity

Encourage developers to experiment and innovate by valuing the outputs of the implementation of new ideas or technologies. Innovation can manifest in improved algorithms, novel user experiences, or tools that enhance team productivity.
### 7. Quality of Pull Request Reviews

Pull Request (PR) reviews are a cornerstone of collaborative software development. However, the focus should be on the quality of these reviews rather than their quantity. High-quality reviews:

 * Identify potential bugs and inefficiencies.
 * Suggest improvements for maintainability and readability.
 * Provide constructive feedback that helps team members grow.

Defining quality in PR reviews is inherently complex, as it involves subjective elements like depth of analysis, clarity of communication, and alignment with project goals. A balanced approach considers both tangible outcomes (e.g., fewer post-merge defects) and team feedback on the helpfulness of reviews. For practical advice, see [Google’s Guidelines on Code Reviews](https://google.github.io/eng-practices/review/reviewer/).

## Trying to Define a Balanced System

The key takeaway from the previous sections is to acknowledge [the importance of qualitative metrics](https://martinfowler.com/articles/measuring-developer-productivity-humans.html) when assessing the performance of Software Engineers.

A holistic evaluation system should:

 * Combine quantitative and qualitative metrics.
 * Involve peer and stakeholder feedback to capture less tangible contributions.
 * Avoid incentivizing counterproductive behaviors.

For example, a balanced scorecard might include:

 * Objective measures like feature cycle time and defect rates.
 * Subjective assessments of mentorship, team collaboration, and alignment with business goals.

However, defining a formula to assess the performance of Software Engineers in a meaningful and holistic way is extremely hard.

## Do We Really Need Metrics?

Since we have acknowledged the difficulty to measure developers productivity, an alternative approach is to not focus on it.

As highlighted in _Reinventing Organizations_, we might be better off in environments of trust and autonomy where developers are empowered to self-manage and align their work with the organization’s broader purpose.

This method removes the need for counterproductive incentives, enabling individuals and teams to focus on delivering meaningful results.

This approach requires more careful hiring practices, to ensure a team of motivated, capable individuals who can thrive in such environments.

Low performers can still be identified through peer feedback, repeated poor outcomes, or by patterns of behavior that conflict with team culture, norms and goals. Thus, accountability within the self-managing system can still be achieved.

## Conclusion

There is a reasonable doubt about whether we can really measure developers’ productivity objectively; and also about whether we really need to do so, since measuring software developer productivity requires nuance and an appreciation of the multifaceted nature of their contributions.

Moving beyond superficial metrics like the number of lines of code (or the number of commits) and embracing more meaningful (though often subjective) indicators, organizations can foster a culture that values quality, collaboration, and long-term success. These more complex and nuanced approaches usually lead to better outcomes for users and businesses alike.

Alternative approaches to traditional incentives and measuring techniques involve creating environments of trust and autonomy where developers are empowered to self-manage and align their work with the organization’s broader purpose, removing the need for counterproductive incentives, and focusing on culture instead.

There is no silver bullet, but reimagining organizations to function as a “*Living System*” rather than a “*Machine*” offers a more natural fit for the complexity of today’s knowledge-driven, creative, and rapidly evolving digital landscape."

<div class="revisions">
  <h2>Significant revisions</h2>
  <p><em>2025, Jan 01</em>: Significant general revision; major improvements.</p>
</div>
