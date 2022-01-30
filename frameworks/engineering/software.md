---
path: "/engineering/software"
title: "🦛 Software Engineering Framework"
sidebarTitle: "🦛 Software"
sidebarGroup: "engineering"
yaml: true
levels: 5
homepage: true
topics:
  - name: "craft"
    title: "💻 Craft"
    content:
      - level: 1
        criteria:
          - "I puzzle through problems. I seek guidance from other engineers, rather than answers."
          - "I document my code's performance, and verify it, using tools like the Chrome Performance tab and PyInstrument."
        exampleCriteria:
          - criteria: "I regularly ship code that is free of glaring errors."
            examples:
              - "I can be trusted to implement simple components."
              - "I know what code smells are, and generally avoid them."
              - "I am familiar with the Google style guides. I therefore write pretty HTML/CSS/JS/Python."
              - "I effectively leverage unit tests via PyTest or a component-level testing library."
              - "I provide sample output, or review apps. These artifacts do, in fact, work."
      - level: 2
        criteria:
          - "I create design documents that acknowledge multiple possible solutions, and their trade-offs. I design interacting components, and solicit feedback on my interfaces."
          - "I regularly identify and resolve performance, functional, and security defects in our codebase, even in code I didn't write."
        exampleCriteria:
          - criteria: "I write clean code."
            examples:
              - "I can be trusted to implement complex components with ambiguous requirements"
              - "I know most of the idioms of my primary programming language(s)"
              - "I consider metrics, using tools like Lighthouse and New Relic"
              - "I am familiar with the APIs and best practices of at least some of our dependencies: Django, PostGIS, Geopandas, Mapbox, Plotly, flex-box, Heroku.."
              - "I effectively leverage end-to-end tests via Cypress."
              - "I know what design patterns are, and try to leverage them."
              - "My code is self-documenting, but I document it anyway."
              - "My PR descriptions serve as reliable context for future pangolins."
              - "I know when to optimize for speed over quality, and can justify the decision"
      - level: 3
        criteria:
          - "I keep up-to-date on the ecosystem of tools and libraries supporting my primary programming language."
          - "I am generous with my time, and consider no urgent work 'beneath me.' I effectively and quickly debug cross-module issues, and may intuit where bugs might lie due to my deep knowledge of the libraries, platforms, and systems that my software relies on."
        exampleCriteria:
          - criteria: "I write exemplary code."
            examples:
              - "I can be trusted to implement core components, and multi-component systems"
              - "I can be trusted to deploy our applications"
              - "Simplicity, maintanence, flexibility, and SOLIDity are all critical to my designs"
              - "I create and evaluate proof-of-concepts"
              - "I effectively leverage general design patterns"
              - "I effectively leverage JavaScript or Python patterns for componentization, mixins, etc."
              - "I contribute to our CI tools, so that future code can be as good as mine"
              - "I create new abstractions and explain them to other developers"
              - "I am regarded as a go-to expert in at least one of our dependencies: Django, PostGIS, Geopandas, Mapbox, Plotly, flex-box, Heroku.."
      - level: 4
        criteria:
          - "I track the performance of our whole system, and recommend improvements across the stack."
          - "I design systems. I’m able to create coherent designs with multiple components interacting across API or system boundaries. Bugs do not creep in at the boundaries between components due to mismatches in expectations of what is technically feasible."
        exampleCriteria:
          - criteria: "I write foundational code."
            examples:
              - "Given enough time, I can be trusted to implement component libraries"
              - "I could be relied on to own the deployment of our applications"
              - "I have sufficient full-stack skills to whip up a proof-of-concept application"
              - "I can intuit where bugs might lie due to my deep knowledge of the libraries, platforms, and systems that my software relies on, though I likely delegate the actual fix."
              - "I identify and fix security and performance bottlenecks, when critical"
              - "I implement services or libraries that require a deep level of domain knowledge"
              - "I’m capable of driving overall testing strategy of a significant system with high reliability or quality requirements"
              - "I identify architecturally significant functional and non-functional requirements, identify conflicts among them, and define possible trade-offs scenarios"
              - "A new engineer can expect to learn something from a 30 minute conversation with me"
      - level: 5
        criteria:
          - "I keep up-to-date on architectural patterns, and reflect on how Kevala fits in."
          - "I am responsible for reducing leaks in the abstractions of our architecture."
        exampleCriteria:
          - criteria: "I write foundational systems."
            examples:
              - "I have implemented core libraries used across our platform"
              - "I contribute to open source software that we depend on"
              - "I’m capable of designing systems with significant ambiguity and/or lots of systems that depend on it"
              - "I contribute to inter-departmental systems, and can reduce the complexity of these to foundational concepts"
              - "I use a risk-based approach to manage technical debt systemically"
              - "You could write a good blog post on a system I've delivered."
  - name: "coordination"
    title: "☀️ Coordination"
    content:
      - level: 1
        criteria:
          - "I am absorbing information about the clean energy sector."
          - "Where things are confusing for me, I document them (or fix the documentation), for the benefit of future pangolins"
          - "I track my work in Jira, in alignment with broader epics"
      - level: 2
        criteria:
          - "I can effectively articulate how my work helps to decarbonize the energy sector."
          - "I help newer hires throughout their onboarding process."
          - "I break down epics into stories, and effectively pace my progress through these."
      - level: 3
        criteria:
          - "I identify opportunities to better align our products to Kevala's mission of decarbonization."
          - "I am able to manage my own projects, when required. I draft epics as living documentation, incorporating feedback as requirements change."
        exampleCriteria:
          - criteria: "I am involved with hiring in some form."
            examples:
              - "I volunteer to run tech screens or sit on interview panels"
              - "I provide feedback on team job descriptions"
              - "I leverage my professional network in recruiting"
      - level: 4
        criteria:
          - "I hold Kevala accountable for the impact that we have on the climate."
          - "I help identify talent gaps required for team success."
          - "I bootstrap new initiatives. I am able to manage my own boards, when required. I prioritize work across an annual time horizon."
      - level: 5
        criteria:
          - "I take responsibility for how Kevala (attempts to) decarbonize."
          - "I take a long view on organizational planning. I identify and resolve risks to institutional knowledge."
          - "I ensure the long term success of our platform by identifying horizontal engineering objectives, and prioritizing these across a multi-year time horizon."
  - name: "impact"
    title: "👩‍💼 Impact"
    content:
      - level: 1
        criteria:
          - "I take time to try to understand our user personas."
          - "I take pride in the features I release, and own any bugs in their deployment"
          - "I avoid contributing to technical and functional debt, as inhibitors to the scaling of the Assessor platform"
      - level: 2
        criteria:
          - "I know who our users are, and connect their goals to the work I do."
          - "I own several features in the Assessor platform. My peers seek out and respect my review on related PRs."
          - "I know our platform's strengths and weaknesses, as far as technical debt and scalability"
      - level: 3
        criteria:
          - "I have literally met our users or clients, or at least potential ones."
          - "I own technical decisions with high risk and low reversibility, and delegate technical decisions with low risk and high reversibility"
          - "I identify bottlenecks in our application, and am able to ameliorate the problems, if given the time"
      - level: 4
        criteria:
          - "I know our users' pain points, and can articulate the steps that we would take to resolve them, but I manage competing priorities effectively."
          - "I am the authority for the technical implementation of a customer-facing application. I own its deployment in Heroku."
          - "I identify bottlenecks in our applications, and know when to resolve them and when to delegate their resolution"
      - level: 5
        criteria:
          - "Our users trust me."
          - "I am familiar with all our applications, and can effectively lead discussions about most aspects therein"
          - "I understand the limitations of our platform, and draft roadmaps to their resolution (regardless of whether these are actualized)"
  - name: "influence"
    title: "✨ Influence"
    content:
      - level: 1
        criteria:
          - "I write clearly. I ask questions and collaborate with my peers."
          - "I follow the processes put in place by others"
          - "I listen to different perspectives and I cut biases from my words and actions."
        exampleCriteria:
          - criteria: "I read PRs from my peers, and indicate that I have done so."
            examples:
              - "Positive comments are great. Even just saying 'TIL ___' is a useful comment."
              - "'This doesn't quite match our style guide.'"
      - level: 2
        criteria:
          - "I resolve ambiguities in assignments and processes. I proactively present information to the right people."
          - "I build relationships with other applications teams (pangolins) and product teams to clarify technical requirements."
        exampleCriteria:
          - criteria: "I contribute to a positive sense of community on my team, in some form"
            examples:
              - "Help new hires throughout the on-boarding process"
              - "Actively participate in team meetings or pair programming work"
              - "Participate in company-wide seminars like the diversity salon or tech talks"
          - criteria: "I read PRs from my peers, and provide detailed feedback."
            examples:
              - "Positive comments are still very much encouraged."
              - "'I noticed a bug in this edge case.'"
      - level: 3
        criteria:
          - "I build relationships with the data science and data engineering teams to ameliorate technical debt, blindspots, or mismatched requirements."
        exampleCriteria:
          - criteria: "I provide resources to help the people around me to be more effective"
            examples:
              - "Tech talks on innovative technologies (GCP resources, etc.)"
              - "Written tutorials on tools (debuggers, dev and testing tools, Git)"
              - "PR contributions to other teams"
              - "Help product managers and designers understand non-functional requirements"
              - "Help devs on other teams understand requirements due to technical requirements of my team's stack"
          - criteria: "I contribute to a positive sense of community on my team, in some form"
            examples:
              - "Help new hires throughout the on-boarding process"
              - "Organize or facilitate team meetings or pair programming work"
              - "Participate in company-wide seminars like the diversity salon or tech talks"
          - criteria: "I read PRs from my peers, and provide holistic feedback."
            examples:
              - "Positive comments are still very much encouraged."
              - "'Did you consider ____?' 'What if we ____?'"
              - "PR review should not necessarily limited to your immediate team"
      - level: 4
        criteria:
          - "I build relationships throughout Kevala to drive company goals, and to help other departments achieve their goals."
          - "I drive changes (when sensible) to engineering practices with well-reasoned arguments and a 'strong opinion, weakly held' mentality"
          - "I create an inclusive environment for others and ensure diverse perspectives are included. I leverage the strengths & skills of the members of my team."
          - "I primarily provide feedback to component and system design. I encourage and support other engineers to achieve outstanding results."
      - level: 5
        criteria:
          - "I drive changes (when sensible) to engineering practices with well-reasoned arguments and a 'strong opinion, weakly held' mentality"
          - "I lead by example. I am aware of my public presence and actions and my influence on the people around me and Kevala's culture. I personify Kevala's values."
          - "I review high level designs and effectively steward Kevala's application architecture."
        exampleCriteria:
          - criteria: "I represent Kevala's applications to other organizations, internally and externally"
            examples:
              - "Demos to clients"
              - "Tech talks at conferences"
              - "Blog posts on our website"
              - "Serves as a technical authority in the wider engineering community"
---
### About this page
This engineering progression framework is a tool to help engineers and managers:
- talk about what we're* looking for from engineers in a consistent way
- make development and career plans
- set a fair level of compensation.

The framework is a compass, not a GPS.

It's meant to be a helpful thought exercise. It's not meant to be a rating system for humans.

### How does it work?
The framework covers all the things we're looking for from engineers at Kevala. These things are very roughly divided into four categories, across two axes. These aren't weighted equally; code mastery, for example, should probably be the primary focus of SWEIs. But they are all part of your job requirements.
- Craft - The quality of your technical contributions in our codebase
  - Code Mastery
  - Software Design and Architectural Design
  - Approach to bugs and issues
- Coordination - The alignment of your contributions to our mission
  - Decarbonization
  - Growing the team
  - Tracking work
- Impact - How your work makes life better for our users
  - Relationship to our users
  - Product ownership
  - Scaling the platform
- Influence - How your work makes life better for your coworkers
  - Processes
  - Culture
  - Relationships
  - Feedback

Every individual will have strengths and weaknesses on these axes. Your manager will work with you to make sure You are happily engaged and utilized. It should be clear, however, where your areas of growth are. If it isn't, ask in your next 1:1 :)

### What are the levels?

Integers translate directly to titles:

- 1 - SWEI
- 2 - SWEII
- 3 - Senior Software Engineer
- 4 - Staff Software Engineer
- 5 - Principal Software Engineer

These bands are quite wide. It is not reasonable to expect to rocket up them in 18 months. There is, however, ample opportunity within a band to grow your craft, coordination, impact, and influence.

### Give us your feedback!
This is a rough draft. Let us know if it should have more depth, examples, or if you disagree with what we value.

* "we" currently refers to "Teddy Ward" in this document, since the draft is _so_ rough, that I'm the only one who has seen it :p
