---
path: "/engineering/software"
title: "🦛 Software Engineering Framework"
sidebarTitle: "🦛 Software"
sidebarGroup: "engineering"
yaml: true
levels: 6
homepage: true
topics:
  - name: "craft"
    title:
    content:
      - level: 1
        criteria:
          - "My code is free of glaring errors. It is well-documented and appropriately utilizes manual vs. automated tests."
          - "I puzzle through problems. I seek guidance from other engineers, rather than answers."
          - "I document my code's performance, and verify it, using tools like the Chrome Performance tab and PyInstrument."
      - level: 2
        criteria:
          - "I leverage the idioms and design patterns of my primary programming language. I optimize for either speed or quality (or both?!), depending on the explicitly-stated needs of my team."
          - "I read PRs from my peers, and provide detailed feedback."
        exampleCriteria:
          - criteria: "I document problems and trade-offs. I design interacting components, and solicit feedback on my interfaces."
            examples:
              - "Positive comments are still very much encouraged."
              - "I noticed a bug in this edge case."
      - level: 3
        criteria:
          - "I keep up-to-date on the ecosystem of tools and libraries supporting my primary programming language."
          - "I design core components. Simplicity, maintanence, flexibility, and well... SOLIDity are all critical to my designs."
          - "I am generous with my time, and consider no work 'beneath me.' I effectively and quickly debug cross-module issues, and may intuit where bugs might lie due to my deep knowledge of the libraries, platforms, and systems that my software relies on."
        exampleCriteria:
          - criteria: "I read PRs from my peers, and provide holistic feedback."
            examples:
              - "Positive comments are still very much encouraged."
              - "Did you consider ____? What if we ____?"
              - "This is not necessarily limited to your immediate team"
      - level: 4
        criteria:
          - "I track the performance of our whole system, and recommend improvements across the stack."
          - "I keep tabs on PRs, but focus on providing feedback to component and system design."
          - "I design systems. I’m able to create coherent designs with multiple components interacting across API or system boundaries; bugs do not creep in at the boundaries between components due to mismatches in expectations of what is technically feasible."
      - level: 5
        criteria:
          - "I keep up-to-date on architectural patterns, and reflect on how Kevala fits in."
          - "I carefully review proposed changes to our system."
          - "I am responsible for reducing leaks in the abstractions of our architecture."
  - name: "coordination"
    title: "Coordination"
    content:
      - level: 1
        criteria:
          - "scaling the team"
          - "stories/epics/boards"
          - "decarbonization as a company objective"
          - "Delivers assigned tasks, working with a more senior team member, and able to take PR feedback to improve their work"
      - level: 2
        criteria:
          - "Delivers assigned tasks that meet expected criteria"
          - "Works for the team, focuses on tasks that contribute to team goals"
          - "Tries to unblock themselves first before seeking help"
          - "Manages their own time effectively, prioritises their workload well, on time for meetings, aware when blocking others and unblocks"
          - "Helps the team, does what needs doing"
          - "Breaks down small/medium problems into iterative steps"
      - level: 3
        criteria:
          - "Delivers large well-defined tasks and solves small scope not-well-defined problems"
          - "Contributes to writing proposals (Co-authors with more experienced Engineer)"
          - "Breaks down large problems into smaller iterative steps across multiple PRs"
      - level: 4
        criteria:
          - "Solves ambiguous problems"
          - "Leads writing small/medium scope proposals"
          - "Thrown at fires and resolves / contributes heavily to resolving them"
          - "Makes pragmatic choices about taking on tech debt"
          - "Considers multiple different solutions for solving a problem"
          - "Breaks down projects into smaller iterative steps that each deliver value"
      - level: 5
        criteria:
          - "Solves the 'hard problem' in a project e.g. Mastercard crypto and sees it through to resolution"
          - "Solves larger ambiguous problems"
          - "Leads incident resolutions"
          - "Makes judgements about when to diverge from the immediate goal to achieve something else"
          - "Leading large scale technical infrastructure projects (level 5 would originate or complete, probably)"
          - "Leads writing large scope proposals"
          - "Breaks down large long-lasting projects into sensible discrete chunks that compound to achieve a large goal"
          - "Helps prioritise and balance short-term and long-term investments, focusing on high impact, high value work"
      - level: 6
        criteria:
          - "Accountable for delivery of large, mission critical engineering projects"
          - "Originates or finishes large, horizontal engineering efforts"
  - name: "impact"
    title: "👩‍💼 Impact"
    content:
      - level: 1
        criteria:
          - "user"
          - "ownership"
          - "scaling the platform"
      - level: 2
        criteria:
          - "Contributes to maintaining the Monzo culture in their team, helping new joiners"
          - "Gets buy-in on technical decision-making and proposed designs"
          - "Proactively involves other relevant engineers"
          - "Sought out for code reviews"
          - "Instills Monzo engineering principles in other engineers"
          - "Helps the growth of engineers around them through coaching and mentoring"
          - "Helps their squad work together more effectively"
          - "Helps facilitate team/squad rituals"
        exampleCriteria:
          - criteria: "Makes improvements to modules/libraries/services and goes out of their way to help others learn from it"
            examples:
              - "I've used RxJava for the first time here, I'm going to do a talk about why I've done this, here's some great blog posts on it"
      - level: 3
        criteria:
          - "Instills Monzo engineering principles across a whole squad of engineers"
          - "Works with relevant Engineering Managers to help other engineers perform and grow"
          - "Fosters effective collaboration in multi-disciplinary squads (backend, mobile, data, design, web)"
          - "Delegates technical decisions with low risk and high reversibility"
          - "Owns technical decisions with high risk and low reversibility"
          - "Contributes to maintaining the Monzo culture in the wider company"
          - "Bootstraps new teams"
      - level: 4
        criteria:
          - "Helps groups of squads work together more effectively"
          - "Starts things that they cannot finish by themselves"
          - "Delegates to make better use of their time"
      - level: 5
        criteria:
          - "Helps groups of squads work together more effectively"
          - "Starts things that they cannot finish by themselves"
          - "Delegates to make better use of their time"
  - name: "influence"
    title: "✨ Influence"
    content:
      - level: 1
        criteria:
          - "culture"
          - "communication (networking)"
          - "I follow the processes put in place by those before me"
        exampleCriteria:
          - criteria: "Peer review - I read PRs from my peers, and indicate that I have done so."
            examples:
              - "Positive comments are great. Even just saying 'TIL ___' is a useful comment."
              - "This doesn't quite match our style guide."
      - level: 2
        criteria:
          - "Proactively raises issues they spot in retrospectives"
      - level: 3
        criteria:
          - "Provides valuable input to proposals from their team"
          - "Proactively improves modules, services, systems and codebases they encounter, 'this doesn't make sense, I'm going to do something about it'"
          - "Contributes to scaling engineering hiring (e.g. leads calls, does onsite interviews)"
          - "Builds simple tools or iterates existing tools for the benefit of all engineers"
          - "Helps Product Managers and Designers to understand and consider non-functional requirements in the product development process"
          - "Promotes accessibility good practice and helps other engineers to deepen their accessibility knowledge, including demonstrating how to use screen readers"
          - "Promotes security good practice and helps other engineers to deepen their security knowledge"
          - "Promotes performance good practice and helps other engineers to deepen their performance knowledge"
      - level: 4
        criteria:
          - "Positively influences engineers in the wider org"
          - "Maintains documentation on things they know the most, makes it easy for future engineers to interact with systems/code"
          - "Clears blockers for junior team members, provides context/guidance, or knows how to escalate"
          - "Asks why. Does not take truths for granted unless they understand exactly where they are coming from (especially with regards to regulation, compliance, etc)"
          - "Drives changes to engineering practices with well-reasoned arguments and a 'strong opinion, weakly held' mentality"
          - "Shapes the direction of systems designs with less experienced engineers"
          - "Breaks down delivery and knowledge silos in their squad"
          - "Keeps up to date with industry developments and feeds specific technical and non-functional recommendations back into the business"
          - "Proactively identifies opportunities to improve company culture around coding standards and non-functional requirements"
      - level: 5
        criteria:
          - "Represents Monzo at conferences/events"
          - "Given as reason for other engineers to join Monzo"
          - "Proactively shares knowledge internally"
          - "Acts as the 'sole proprietor', in the CEO mindset, their ego/agenda is not a factor in their thinking or decision making"
      - level: 6
        criteria:
          - "Attracts other very senior hires"
          - "Engineers around them get better and have a bigger impact, faster"
  - name: "mastery"
    title: "🛠️ Mastery"
    content:
      - level: 1
        criteria:
          - "Learns to write semantic HTML and CSS following guidance and training materials"
          - "Learns to write correct JavaScript following guidance and training materials"
          - "Uses Chrome, React, and Redux DevTools effectively to increase productivity during development and debugging"
          - "Implements simple components"
          - "Fixes simple bugs"
          - "Asks questions and actions feedback from mentor"
        exampleCriteria:
          - criteria: "Uses git to manage the development workflow effectively"
            examples:
              - "Checkout, Push, Pull, Branch, Diff, Merge, Stash, Rebase, etc."
      - level: 2
        criteria:
          - "Writes semantic HTML and CSS following accepted best practices"
          - "Uses appropriate algorithms and data structures to solve problems"
          - "Writes Flow types to statically type-check the code at compile-time"
          - "Writes automated unit and end-to-end tests following accepted best practices"
          - "Deploys web services into staging and production following our deployment guidelines"
          - "Assists on the design of new features and components"
          - "Solves well-defined tasks within our current developer abstractions"
          - "Integrates with backend APIs and handles successful and failed responses properly"
          - "Works with users to improve new and existing simple features iteratively"
          - "Uses a keyboard and screen-reader to manually test their application for accessibility issues"
          - "Runs automated auditing tools such as Lighthouse before submitting a PR for review"
          - "Demonstrates awareness of a range of security considerations, and mitigates against them"
          - "Has multiple examples of where performance was considered as part of a solution"
        exampleCriteria:
          - criteria: "Applies fundamental UX and accessibility principles to common problems such as form design"
            examples:
              - "Referencing (and improving) existing Design Systems where possible"
          - criteria: "Writes correct JavaScript code following accepted best practices"
            examples:
              - "Follows our JavaScript Coding Conventions & Best Practices; uses language-level primitives correctly"
          - criteria: "Implements simple components following accepted best practices"
            examples:
              - "Follows React Development Conventions & Best Practices; uses component state and lifecycle methods correctly"
          - criteria: "Uses shared libraries to reuse existing functionality"
            examples:
              - "lib.money"
              - "lib.api"
              - "lib.identity-verification, etc."
      - level: 3
        criteria:
          - "Uses appropriate design patterns to solve problems"
          - "Identifies obvious deficiencies in the development processes and supports activities to improve them"
          - "Assists more experienced engineers on the design of larger features"
          - "Modifies and improves code outside of the developer abstractions and reasons about the improvements effectively"
          - "Fixes bugs in asynchronous code"
          - "Debugs production issues"
          - "Explains developer abstractions and how to contribute to them to other engineers"
          - "Collaborates with designers and user researchers to create prototypes and to evaluate them"
          - "Differentiates between user needs and desires and prioritises accordingly"
        exampleCriteria:
          - criteria: "Implements non-trivial components"
            examples:
              - "Uses modern CSS features like flex-box, grid, media-queries, selectors, etc"
              - "Uses advanced component patterns higher-order components, render props, controlled components, compound components"
          - criteria: "Writes effective asynchronous code"
            examples:
              - "Demonstrates solid understanding of the JavaScript runtime; reasons effectively about the runtime behaviour of asynchronous code; uses async/await, generators and Redux-Saga’s to implement asynchronous code"
          - criteria: "Writes effective JavaScript by applying fundamental functional and reactive principles and techniques where appropriate and guides others in so doing"
            examples:
              - "Uses uses event streams, immutable data structures, pure functions, functional composition, memoization, etc."
          - criteria: "Considers metrics when developing, and uses appropriate services to check quality levels"
            examples:
              - "A range, from services such as Lighthouse, WebPageTest, WAVE etc" 
      - level: 4
        criteria:
          - "Writes code that serves as a definitive example for new engineers"
          - "Makes contributions to library code or other core parts of the applications"
          - "Makes contributions to our development tools and build processes"
          - "Writes complex asynchronous and concurrent code"
          - "Identifies optimisation opportunities in the development process and contributes to the implementation of proposed solutions"
          - "Builds maintainable and flexible components and applications"
          - "Leads the refactoring of complex parts of the system"
          - "Debugs and fixes complex issues at speed"
          - "Identifies and fixes security weaknesses"
          - "Identifies and fixes performance bottlenecks in applications"
          - "Explains all aspects of the web platform to new engineers"
          - "Implements services or libraries that require a deep level of domain knowledge"
          - "Puts users first and can manage competing priorities effectively"
      - level: 5
        criteria:
          - "Makes major contributions to library code or core parts of the application"
          - "Contributes to external technologies or libraries that we depend on"
          - "Anticipates platform and project needs, technical debt and common issues intuitively"
          - "Develops clear technical solutions from ambiguous requirements"
          - "Produces technical designs for large complex projects"
          - "Uncovers and fixes tricky bugs that have previously evaded detection"
          - "Demonstrates a deep level of knowledge in a specific area"
          - "Serves as a technical authority on a technology or an area of the codebase"
          - "Reviews technical designs and pull requests for large complex projects"
          - "Encourages and supports other engineers to achieve outstanding results"
          - "Creates major contributions to our documentation, and creates documents that provide guidelines and best practices to other engineers"
          - "Works with technical and non-technical stakeholders to identify high-level requirements and turns them into discrete technical concerns"
      - level: 6
        criteria:
          - "Makes major contributions to technologies and libraries that we depend on"
          - "Uses a risk-based approach and manages technical debt systematically to focus the team’s design and development efforts on the most important problems"
          - "Works with business and technology stakeholder to translate difficult business problems into technical designs, thereby ensuring that the organisation derives maximum value from services"
          - "Identifies architecturally significant functional and non-functional requirements, identifies conflicts among them, and defines possible trade-offs scenarios"
          - "Articulates high-level technical goals, concerns, trade-offs, and decisions to the rest of the company effectively"
          - "Facilitates technical decision making in complex and ambiguous situations"
          - "Promotes architectural thinking and good engineering practices at scale"
          - "Makes improvements that affect important non-functional requirements that have an effect on the entire web-platform"
          - "Serves as a technical authority in the wider engineering community"
          - "Identifies and explores opportunities for service and business improvement"
---
### About this page
This engineering progression framework is a tool to help engineers and managers:
- talk about what we're* looking for from engineers in a consistent way
- make development and career plans
- set a fair level of compensation.

The framework is a compass, not a GPS.

It's meant to be a helpful thought exercise. It's not meant to be a rating system for humans.

### How does it work?
The framework covers all the things we're looking for from engineers at Kevala. These things are very roughly divided into four categories, across two axes.
- Craft - The quality of your technical contributions in our codebase
- Coordination - The alignment of your contributions to our mission
- Impact - How your work makes life better for our users
- Influence - How your work makes life better for your coworkers

Every individual will have strengths and weaknesses on these axes. Your manager will work with you to make sure You are happily engaged and utilized. It should be clear, however, where your areas of growth are. If it isn't, ask in your next 1:1 :)

### What are the levels?

Integer levels translate directly to titles:

- 1 - SWEI
- 2 - SWEII
- 3 - Senior Software Engineer
- 4 - Staff Software Engineer
- 5 - Principal Software Engineer

These bands are quite wide. It is not reasonable to expect to rocket up them in 18 months. There is, however, ample opportunity within a band to grow your craft, coordination, impact, and influence.

### Give us your feedback!
This is a rough draft. Let us know if it should have more depth, examples, or if you disagree with what we value.

* "we" currently refers to "Teddy Ward" in this document, since the draft is _so_ rough, that I'm the only one who has seen it :p
