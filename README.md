Application Development Paradigm Discussion

# Overview

We are asked to develop apps to solve business problems.

I propose that we develop apps because we want to see our ideas built, and 
because we enjoy helping people and serving our community well. Reducing 
friction during app building allows us to focus on our ideas.

My first React project: <https://github.com/mhodgesatuh/ConferenceRegApp>.
I've been in the habit of building conference registration apps as a way to 
learn new frameworks. My first one was built with the Symfony 1 PHP framework.
The learning curve was steep and very high friction.

# Application Development: Velocity vs Friction

Friction slows the transition from ideal to implementation.

Friction comes in many forms:
* Fear of breaking working code
* Understanding the code
* Manual refactoring
* Searching documentation
* Debug cycles
* Onboarding to new codebases
* Climbing learning curves
* Finding and fixing vulnerabilities
* Manually entering every single line of code
* Generating unit tests
* The feedback loop of writing code, running it, and seeing the results

# Tooling up to reduce friction

| Tool     | Description         | Velocity                                                  |
|----------|---------------------|-----------------------------------------------------------|
| Git      | Source code control | Version control: commits and branches                     |
| GitHub   | Collaboration       | Project control: source of truth                          |
| IntelliJ | Powerful IDE        | Code control: refactoring, formatting, etc                |
| CoPilot  | IDE/AI integration  | Debugging, refactoring, code generation, exploration, etc |

## Git - safety, educes the cost of being wrong

* Branch isolation (feature branches)
* Atomic commits
* Safe rollback
* Local history rewriting before publishing
* Time-travel debugging

Consider a git UI such as GitKraken to climb the learning curve more quickly. 
It works very well for visual learners. Git Desktop is another consideration.

## GitHub - structured coordination, versioning, institutional memory

* Central code repository for collaboration
* Pull Requests for source code control
* Review requirements
* Review code quality
* Traceability

UH has an Enterprise Github license and integrates with our Entra tenant.

## IntelliJ - powerful IDE, reduces the cost of understanding and changing code

* Refactoring tools
* Code formatting
* Code navigation
* Code search
* Built-in terminal

Frankly, you could use any IDE. IntelliJ is powerful and ICS recommends it. The 
students on the IAM team have free access to the paid version and it is the 
editor that they know. Some members of IAM and ES teams prefer it. VS Code is a
worthy contender.

The community version is also free and has many of the same features and doesn't 
require as many plugins/extensions as VS Code, for example.

## CoPilot - AI paired programming, reduces discovery time, compresses the learning curve

* Infers framework patterns
* Generates code that follows industry best practices and language-specific conventions
* Drafts unit tests
* Suggests edge cases
* Helps with trouble shooting

There are two main ways to use CoPilot: Ask and Agent:
* Ask: Great for brainstorming, having a running conversation to explore ideas,
  generating code for a specific task.
* Agent: It is empowered, can explore your codebase, update your code, create 
  new files and documentation, and more. 
