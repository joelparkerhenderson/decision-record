<!--
* browser: decision-record
* tracker: fc94c9c34370b9b2f36270aac1deca20
* version: 2.1.0
* updated: 2025-05-18T13:48:41Z
* contact: Joel Parker Henderson (http://joelparkerhenderson.com)
* options: commentable
-->

# Decision record (DR)

A decision record (DR) is a way to initiate, debate, and archive an important choice, along with its context and consequences.

Contents:

* [What is a decision record?](#what-is-a-decision-record)
* [Decision record template](#decision-record-template)
* [How to start using decision records](#how-to-start-using-decision-records)
* [Why are decision records better than just notes?](#why-are-decision-records-better-than-just-notes)
* [How to start using decision records with tools](#how-to-start-using-decision-records-with-tools)
* [Suggestions for writing good decision records](#suggestions-for-writing-good-decision-records)
* [Teamwork advice for decision records](#teamwork-advice-for-decision-records)
* [Teamwork questions for decision records](#teamwork-questions-for-decision-records)
  * [Who can create a decision record?](#who-can-create-a-decision-record)
  * [What justifies raising a decision record?](#what-justifies-raising-a-decision-record)
  * [What justifies not rasing a decision record?](#what-justifies-not-rasing-a-decision-record)
  * [What is the lifecycle of a decision record?](#what-is-the-lifecycle-of-a-decision-record)
  * [What are criteria for lifecycle steps of a decision record?](#what-are-criteria-for-lifecycle-steps-of-a-decision-record)
  * [What roles and responsibilities interact with a decision record?](#what-roles-and-responsibilities-interact-with-a-decision-record)
  * [How does governance interact with a decision record?](#how-does-governance-interact-with-a-decision-record)
  * [What principles interact with a decision record?](#what-principles-interact-with-a-decision-record)
* [For more information](#for-more-information)


## What is a decision record?

A **decision record** (DR) is a way to initiate, debate, and archive an important choice, along with its context and consequences.

A **decision log** (DL) is the collection of all DRs created and maintained for a particular project (or organization).

A **decision** in this context is an organization's choice that addresses a significant requirement.

A **significant requirement** (SR) is a project's need that has a measurable effect on a project's system.

All these terms are within the topic of **knowledge management** (KM).

The goal of this document is to provide a fast overview of decision records.

## Decision record template

See our file [template.md](/template/template.md) which uses these major sections:

* **Title**: short present tense imperative up to 50 characters.

* **Status**: request for comments | proposed | accepted | rejected | deprecated | superseded

* **Issue**: describe the issue you want to address, and leave no questions about why.
  
* **Assumptions**: describe any assumptions, premises, cross-project requirements, etc.
  
* **Constraints**: capture any constraints to the environment this decision might pose. 

* **Positions**: list the potential candidate options as facts and data, not opinions.

* **Opinions**: by the team and stakeholders, and also third-party advisors and reviewers.

* **Selection**: explain why you selected a position, with purpose and accountability.

* **Implications**: state your decision’s implications, such as any need for changes.

* **Related**: such as for references, cross-project work, and follow on needs.

## How to start using decision records

To start using decision records, talk with your teammates about these areas.

Decision identification:

* How urgent and how important is the decision?

* Does it have to be made now, or can it wait until more is known?

* Both personal and collective experience, as well as recognized design methods and practices, can assist with decision identification.

* Ideally maintain a decision todo list, that complements the product todo list.

Decision making:

* A number of decision making techniques exists, both general ones and software-specific ones, for instance, dialogue mapping.

* Group decision making is an active research topic.

Decision enactment and enforcement:

* Decisions have to be communicated to, and accepted by, the stakeholders of the system that fund, develop, and operate it.

* Architecturally evident coding styles and code reviews that focus on architectural concerns and decisions are two related practices.

* Decisions can be reconsidered when making significant changes to a system, such as evolving a system, or upgrading a system, or adjusting a system for changing requirements.

Decision sharing (optional):

* Many decisions recur across projects.

* Hence, experiences with past decisions, both good and bad, can be valuable reusable assets when employing an explicit knowledge management strategy.

* Group decision making is an active research topic.

Decision documentation:

* Many templates and tools exist for decision planning and decision capturing.

* See agile communities, e.g. M. Nygard's architectural decision records.

* See traditional software engineering and architecture design processes, e.g. table layouts suggested by IBM UMF and by Tyree and Akerman from CapitalOne.

Decision guidance:

* The steps above are adopted from the Wikipedia entry on [Architectural Decision](https://en.wikipedia.org/wiki/Architectural_decision)

* A number of decision making techniques exists, both general ones and software and software architecture specific ones, for instance, dialogue mapping.

## Why are decision records better than just notes?

A decision record adds some structure to freeform notes.

A decision record template adds a list of items to cover, which functions as a checklist.

The important result is that teams can use decision records and templates to improve teamwork: the decision records and templates both work as checklists, that help the team ensure they cover all the bases, and they communicate efficiently and effectively.

The advantages of decision records tend to grow with team size, project expansion, integration opportunities, stakeholder involvement, long term maintenance, and evolution over time.

For example, we use decision records with large teams, and across multiple departments, and with multiple partner organizations, and on multiple-year projects, and million-dollar budgets. With this kind of size and scope, we prefer using some kinds of structured communication over just freeform notes.

In practice, we also like using decision records because they encourage more participation among remote teammates, more asynchronous communication, more efficient evalation of options, and more summarization going forward. All of these aspects also help onboard new teammates because the decisions are clear, complete, succinct, and recorded.

## How to start using decision records with tools

You can start using decision records with tools any way you want.

For example:

* If you like Google Drive and Google Docs, then create a `decisions` folder, and a doc per decision record.

* If you like source code version control, then create a `decisions` directory, and a text file per decision record.

* If you like project planning tools, such as Atlassian Jira, then use the tool's planning tracker.

* If you like wikis, such as MediaWiki, then create a decision record wiki, with a wiki page per decision record.

## Suggestions for writing good decision records

Characteristics of a good decision record:

* Point in Time - Identify when the decision was made

* Rationality - Explain the reason for making the particular decision.

* Immutable record - The decisions made in a previously published decision record should not be altered.

* Specificity - Each decision record should be about a single decision.

Characteristics of a good context in a decision record:

* Explain your organization's situation and business priorities

* Include rationale and considerations based on social and skills makeups of your teams.

Characteristics of good consequences in a decision record::

* Right approach - "We need to start doing X instead of Y"

* Wrong approach - Do not explain the decision in terms of "Pros" and "Cons" of having made the particular AD

A new decision record may take the place of a previous decision record:

* When a decision is made that replaces or invalidates a previous decision record, then create a new decision, and reference the old decision.
  
## Teamwork advice for decision records

If you're considering using decision records with your team, then here's some advice that we've learned by working with many teams.

You have an opportunity to lead your teammates, by talking together about the "why", rather than mandating the "what". For example, decision records are a way for teams to think smarter and communicate better; decision records are not valuable if they're just an after-the-fact forced paperwork requirement.

Some teams much prefer the name "decisions" over the abbreviation "decision records". When some teams use the directory name "decisions", then it's as if a light bulb turns on, and the team starts putting more information into the directory, such as vendor decisions, planning decisions, scheduling decisions, etc. All of these kinds of information can use the same template. We hypothesize that people learn faster with words ("decisions") over abbreviations ("decision records"), and people are more motivated to write work-in-progress docs when the word "record" is removed, and also some developers and some managers dislike the word "architecture".

In theory, immutability is ideal. In practice, mutability has worked better for our teams. We insert the new info the existing decision record, with a date stamp, and a note that the info arrived after the decision. This kind of approach leads to a "living document" that we all can update. Typical updates are when we get information thanks to new teammates, or new offerings, or real-world results of our usages, or after-the-fact third-party changes such as vendor capabilities, pricing plans, license agreements, etc.

</div>

## Teamwork questions for decision records

### Who can create a decision record?

Consider areas such as specific people, or specific roles, or specific teams, or specific departments; also consider if there are people, or roles, or teams, or department that can commission a decision record, meaning they request one that someone else will author. 

Example answer: Any person in our organization who has read the architecture decision record README page can propose a decision record, meaning the person can start writing it, and share it with the team.

### What justifies raising a decision record?

Consider areas such as your organization's team ways of working, your software system structure, cross-team coordination, long-term maintainability, external interfaces, who you want to benefit, and the like. 

Example answer: We want to create a decision record when we want future developers to understand the “why” of what we're doing.

### What justifies not rasing a decision record?

Consider areas such as decisions that are not about architecture, or are tiny such as minimal-risk or self-contained or single-developer, or are already fully covered elsewhere such as by standards or policies or documentation, or are temporary such as workarounds or proofs of concepts or orexperiments. 

Example answer: We want to skip a decision record when a decision is limited in scope and time and risk and cost, or is already covered elsewhere.

### What is the lifecycle of a decision record?

Consider areas such as the creation process, research process, decisioning process, implementation process, and sunsetting process. Consider how to track the decision record lifecycle over time, such as how to move the decision record from one state to the next state, and also how to communicate this to stakeholders. 

Example answer: We want a decision record to have five lifecycle stages: Initiating → Researching → Evaluating → Implementing → Maintaining → Sunsetting.

### What are criteria for lifecycle steps of a decision record?

Consider areas such as acceptance criteria for a decision record, meaning how do you know it's good enough to progress from one lifecycle step to the next? Is the problem clearly articulated? Have the alternatives been considered? Are trade-offs well-enough understood and documented?
Is all relevant context in place? Are all revelant stakeholders involved? Has all feedback been incorporated? 

Example answer: We want a decision record to be voted on by stakeholders when the active team has 1) completed their research, 2) completed their evaluation, 3) published the decision record proposal to the stakeholders with a request for comments and a timebox of one week, 4) all stakeholder comments have been incorporated and addressed.

### What roles and responsibilities interact with a decision record?

Consider roles such as proposer, researcher, evaluator, reviewer, approver, maintainer, and the like. Consider responsbilities such as communication with stakeholders, ensuring expectations are met, sharing on the website or intranet, and reviewing the work periodically and especially when relevant changes happen.

Example answer: We want each decision record to always have a primary contact person, secondary contact person, and accountable team; these are responsble for communications, publications, maintenance, periodic review at least once per year, and eventual sunsetting as needed.

### How does governance interact with a decision record?

Consider areas such as your organization's ways of working, any special compliance needs such as for legal aspects or human resource aspects, how you want to handle consensus versus conflict versus escalation. Are there areas or people or teams that can have more influence than others regarding a decision record, such as being able to approve it, or vote on it, or veto it?

Example answer: The governance of a decision record is in this priority order: the CEO, the CTO, the CLO, the team that implements a decision record, the experts on the team that are most-knowledgeable about the ADD. No one else has governance unless described in the decision record. 

### What principles interact with a decision record?

Consider areas such as your organization's ways of working that include  moving quickly versus moving slowly, for decision consensus versus decision conflict, and for risk preferences versus safety preferences, public discussion versus private discussion, and the like.

Example answer: We use the leadership priciples of bias for action, disagree-and-commit, 70% estimates are good enough for easily-reversable easily-isolatable decisions, and public ways of working with the exception of confidential information as described in our organization's confidentiality agreement.

## For more information

Introduction:

* [Architectural decision record](https://github.com/joelparkerhenderson/architecture_decision_record)

* [Architectural decision (wikipedia.org)](https://wikipedia.org/wiki/Architectural_decision)

* [Architecturally significant requirements (wikipedia.org)](https://wikipedia.org/wiki/Architecturally_significant_requirements)

Templates:

* [Documenting architecture decisions - Michael Nygard (thinkrelevance.com)](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

* [Markdown Architectural Decision Records (decision record.github.io)](https://decision record.github.io/mdecision record/) - provided by the [decision record GitHub organization](https://decision record.github.io/)

* [Template for documenting architecture alternatives and decisions (stackoverflow.com)](http://stackoverflow.com/questions/7104735/template-for-documenting-architecture-alternatives-and-decisions)

In-depth:

* [ADMentor XML project (github.com)](https://github.com/IFS-HSR/ADMentor)

* [Architectural Decision Guidance across Projects: Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge (ifs.hsr.ch)](https://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf)

* [The Decision View's Role in Software Architecture Practice (computer.org)](https://www.computer.org/csdl/mags/so/2009/02/mso2009020036-abs.html)

* [Documenting Software Architectures: Views and Beyond (resources.sei.cmu.edu)](http://resources.sei.cmu.edu/library/asset-view.cfm?assetID=30386)

* [Architecture Decisions: Demystifying Architecture (utdallas.edu)](https://www.utdallas.edu/~chung/SA/zz-Impreso-architecture_decisions-tyree-05.pdf)

* [ThoughtWorks Technology Radar: Lightweight Architecture Decision Records (thoughtworks.com)](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)

Tools:

* [Command-line tools for working with Architecture Decision Records](https://github.com/npryce/decision record-tools)

* [Command line tools with python by Victor Sluiter](https://bitbucket.org/tinkerer_/decision record-tools-python/src/master/)

Examples:

* [Repository of Architecture Decision Records made for the Arachne Framework](https://github.com/arachne-framework/architecture)

See also:

* REMAP (Representation and Maintenance of Process Knowledge)

* DRL (Decision Representation Language)

* IBIS (Issue-Based Information System)

* QOC (Questions, Options, and Criteria)

* IBM’s e-Business Reference Architecture Framework
