---
layout: post
title:  "Putting the engineering back into DevOps"
date:   2024-10-04 11:02:20 +1100
categories: devops
---

![Engineer at work](/assets/images/2024-10-04/AdobeStock_784304975-2500px-2060x860.jpg.webp)

In today’s modern workplace, especially within the Australian technology industry, DevOps is often linked with build and release pipelines and numerous integrations, many of which leverage the widely used YAML syntax to define their implementation.

The work itself has become a skill of piecing together snippets of markup to achieve the desired outcome. Is there a risk of moving towards a path where those who have been leading collaboration and excellence in enabling business agility are reduced to the role of “YAML Engineer?” In this article, I will briefly explore the origins of DevOps and the potential it holds for us today.

![Yet Another Markup Language](/assets/images/2024-10-04/AdobeStock_867743114-2500px-2048x1366.jpg.webp)

## Back to our roots

Let’s take a step back and consider the challenges that the DevOps movement aimed to address. Its name reflects the historical struggles between two teams or disciplines with conflicting priorities: the “Devs,” motivated to deliver new business features rapidly, and the “Ops,” focused on stability and ensuring that systems are available, reliable, and servicing customers. This misalignment in purpose resulted in the creation of silos, with the “Devs” passing their completed releases to the “Ops” without due consideration for performance or reliability. This left the “Ops” team to manage potentially failing or unstable systems and roll back releases often without sharing sufficient context or data to diagnose the root cause with the “Devs.” These ongoing struggles within IT departments would ultimately hinder productivity and escalate tensions.

To address this conflict, the DevOps movement focuses on a shift in culture, emphasising the importance of collaboration between development (Devs) and operations (Ops) to achieve meaningful business outcomes. This collaboration fosters the sharing of best practices, resulting in significant innovations such as automated and repeatable deployments and the development of tools like Infrastructure-as-Code.

As for the topic mentioned in this article, YAML is not all bad. As its name suggests, “Yet-Another-Markup-Language,” has successfully achieved a level of readability and data serialisability that many of its predecessors could not, leading to the widespread adoption that we see today. This has resulted in its incorporation into many of the tools in the DevOps toolbox.

### Gluing together the tooling a business needs is one thing; doing it over and over again is another entirely.

Throughout the years, I have observed how quickly various tools for practices such as continuous integration, containerisation, and cloud deployments spread throughout an organisation. These tools and platforms are based on the best practices promoted by DevOps, making their adoption highly desirable. However, after initial adoption and success, each team’s unique implementation and preferences can cause divergence and fragmentation in how solutions are developed and managed across the business. This can lead to issues in maintainability and add unintended complexity to an already inherently complex ecosystem.

Offering initial templates and starters to aid teams in delivering value early on is a good start, but it is equally important to consider how to provide ongoing support and maintenance for the future. Failing to consider this may result in revisiting the challenges presented by siloed teams. As we stitch together our workflows, pipelines, and integrations to help us deliver within our business, we at times create unnecessary repeat work, anomalous configurations, and broader challenges for the business when it needs to introduce expansive, cross-cutting changes, requiring teams to invest more time to remain compliant.

## What’s the solution?

Taking a moment to consider what a business truly needs and how it is expressed with its internal language allows for a tailored design around common functions and reusable patterns. The ultimate goal is to provide self-service-focused tools that enable teams efficiently. These efforts shed light on the often-untapped potential that DevOps and its practices can bring.

Like the Agile movement, DevOps has been built on the success of numerous initiatives aimed at solving complex problems in building and running software. These practices and patterns form the solid foundation for building high-quality software quickly, thus increasing business agility. Below are a few examples that are battle-tested and noteworthy. This list is by no means exhaustive.

- Test-Driven Development
- SOLID
- Continuous Integration
- Continuous Delivery and Deployment
- Microservices Architecture
- Infrastructure-as-Code or Everything-as-Code
- Shift Left

The combination of proven practices and patterns, along with teamwork and collaboration, is key to establishing a strong DevOps culture in an organisation. This culture gives the organisation the ability to accelerate growth, seize opportunities, foster innovation, and stay ahead of the competition. Movements like Shift Left prioritise testing and security, adding further value to the proposition mentioned. Bringing security into the development process early on reduces the chances of last-minute changes and the risk of missing deadlines.

Today, a wide range of security tools and services are available to address various concerns about the secure development and operation of software systems.

Tools are great; however, in my opinion, there is a hidden cost here as well. The more things piled into the development process, the greater the burden on software developers, eventually bogging them down so much that we are essentially back where we started, losing the gains in productivity we’ve enjoyed.

By applying a DevSecOps lens to the challenges faced, we can now focus on integrating these tools into a standardised approach to how software is developed and released within a business. This involves designing and combining select frameworks and tooling to address these concerns with the aim of reducing the burden on developers and delivery teams. Essentially, we define the paved road or the path of least resistance, providing a consistent and understood experience for meeting security and compliance obligations.

## Key takeaway…

In developing processes, frameworks, and tooling to address non-functional requirements such as security concerns or to design solutions for building and deployment, it’s important to embrace innovation and avoid rigidly enforcing policies and development practices across a business. Room should be allowed for those with unique cases to step outside the standard practices when necessary, encouraging collaboration and the contribution of new ideas and patterns into existing standards.

The goal of this article is to explore the potential of DevOps, its origins, and where we stand today. It highlights how leveraging the collective knowledge and expertise within an organisation can bring back an “engineering” focus on delivering value with a productive DevOps culture in any business, without unnecessarily limiting ourselves to the role of “YAML Engineer.”
