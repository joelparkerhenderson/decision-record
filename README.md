<!--
  * browser: decision-record
  * tracker: fc94c9c34370b9b2f36270aac1deca20
  * version: 1.2.0
  * updated: 2018-12-25T02:39:34Z
  * contact: Joel Parker Henderson (http://joelparkerhenderson.com)
  * options: commentable
-->

# Decision record (DR)

A decision record (DR) is a way to initiate, debate, and archive an important choice, along with its context and consequences.

Contents:

* [What is an architecture decision record?](#what-is-an-architecture-decision-record)
* [How to start using decision records](#how-to-start-using-adrs)
* [How to start using decision records with tools](#how-to-start-using-adrs-with-tools)
* [How to start using decision records with git](#how-to-start-using-adrs-with-git)
* [decision record file name conventions](#adr-file-name-conventions)
* [Suggestions for writing good decision records](#suggestions-for-writing-good-adrs)
* [decision record example templates](#adr-example-templates)
* [For more information](#for-more-information)


## What is a decision record?

A **decision record** (DR) is a way to initiate, debate, and archive an important choice, along with its context and consequences.

An **decision log** (DL) is the collection of all DRs created and maintained for a particular project (or organization).

A **decision** in this context is an organization's choice that addresses a significant requirement.

An **significant requirement** (SR) is a project's need that has a measurable effect on a project's system.

All these terms are within the topic of **knowledge management** (KM).

The goal of this document is to provide a fast overview of descion records, including how to create them, and where to look for more information.

Abbreviations:

  * **DL**: decision log

  * **DR**: decision record

  * **KM**: knowledge management

  * **SR**: significant requirement



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

  * Many templates and tools exisit for decisison planning and decision capturing.

  * See agile communities, e.g. M. Nygard's architectural decision records.

  * See traditional software engineering and architecture design processes, e.g. table layouts suggested by IBM UMF and by Tyree and Akerman from CapitalOne.

Decision guidance:

  * The steps above are adopted from the Wikipedia entry on [Architectural Decision](https://en.wikipedia.org/wiki/Architectural_decision)

  * A number of decision making techniques exists, both general ones and software and software architecture specific ones, for instance, dialogue mapping.


## How to start using decision records with tools

You can start using decision records with tools any way you want.

For example:

  * If you like using Google Drive and online editing, then you can create a Google Doc, or Google Sheet.

  * If you like use source code version control, such as git, then you can create a file for each decision record.

  * If you like using project planning tools, such as Atlassian Jira, then you can use the tool's planning tracker.

  * If you like using wikis, such as MediaWiki, then you can create an decision record wiki.


## How to start using decision records with git

If you like using git version control, then here is how we like to start using decision records with git for a typical software project with source code.

Create a directory for decisions:

```sh
$ mkdir decisions
```

For each decision, create a text file, such as `helloworld.txt`, and edit as you like:

```sh
$ vi helloworld.txt
```

Write anything you want in the decision record. See the templates in this repository for ideas.

Commit the decision record to your git repo.


## Decision record file name conventions

If you choose to create your decision records using typical text files, then you may want to come up with your own decision record file name convention.

We prefer to use this file name convention:

  * The name has a present tense imperative verb phrase. This helps readability and matches our commit message format.

  * The name uses lowercase and underscores (same as this repo). This is a balance of readability and system usability.

  * The extension is markdown. This can be useful for easy formatting.

Examples:

  * choose-databases.md

  * format-timestamps.md

  * manage-passwords.md

  * handle-exceptions.md


## Suggestions for writing good decision records

Characteristics of a good decision record:

  * Point in Time - Identify when the decision was made

  * Rationality - Explain the reason for making the particular decision.

  * Immutable record - The decisions made in a previously published decision record should not be altered.

  * Specificity - Each decision record should be about a single decision.

Characteristics of a good context in an decision record:

  * Explain your organization's situation and business priorities

  * Include rationale and considerations based on social and skills makeups of your teams.

Characteristics of good consequences in an decision record::

  * Right approach - "We need to start doing X instead of Y"

  * Wrong approach - Do not explain the decision in terms of "Pros" and "Cons" of having made the particular AD

A new decision record may take the place of a previous decision record:

  * When an decision is made that replaces or invalidates a previous decision record, then create a new decision, and reference the old decision.


## For more information

Introduction:

  * [Architectural decision record)](https://github.com/joelparkerhenderson/architecture_decision_record)

  * [Architectural decision (wikipedia.org)](https://wikipedia.org/wiki/Architectural_decision)

  * [Architecturally significant requirements (wikipedia.org)](https://wikipedia.org/wiki/Architecturally_significant_requirements)

Templates:

  * [Documenting architecture decisions - Michael Nygard (thinkrelevance.com)](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

  * [Markdown Architectural Decision Records (adr.github.io)](https://adr.github.io/madr/) - provided by the [adr GitHub organization](https://adr.github.io/)

  * [Template for documenting architecture alternatives and decisions (stackoverflow.com)](http://stackoverflow.com/questions/7104735/template-for-documenting-architecture-alternatives-and-decisions)

In-depth:

  * [ADMentor XML project (github.com)](https://github.com/IFS-HSR/ADMentor)

  * [Architectural Decision Guidance across Projects: Problem Space Modeling, Decision Backlog Management and Cloud Computing Knowledge (ifs.hsr.ch)](https://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf)

  * [The Decision View's Role in Software Architecture Practice (computer.org)](https://www.computer.org/csdl/mags/so/2009/02/mso2009020036-abs.html)

  * [Documenting Software Architectures: Views and Beyond (resources.sei.cmu.edu)](http://resources.sei.cmu.edu/library/asset-view.cfm?assetID=30386)

  * [Architecture Decisions: Demystifying Architecture (utdallas.edu)](https://www.utdallas.edu/~chung/SA/zz-Impreso-architecture_decisions-tyree-05.pdf)

  * [ThoughtWorks Technology Radar: Lightweight Architecture Decision Records (thoughtworks.com)](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)

Tools:

  * [Command-line tools for working with Architecture Decision Records](https://github.com/npryce/adr-tools)

  * [Command line tools with python by Victor Sluiter](https://bitbucket.org/tinkerer_/adr-tools-python/src/master/)

Examples:

  * [Repository of Architecture Decision Records made for the Arachne Framework](https://github.com/arachne-framework/architecture)

See also:

  * REMAP (Representation and Maintenance of Process Knowledge)

  * DRL (Decision Representation Language)

  * IBIS (Issue-Based Information System)

  * QOC (Questions, Options, and Criteria)

  * IBM’s e-Business Reference Architecture Framework
