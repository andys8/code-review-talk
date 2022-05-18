%title: Code Review
%author: e-bot7
%date: 2022-05-19

```
     _____          _          _____            _
    / ____|        | |        |  __ \          (_)
   | |     ___   __| | ___    | |__) |_____   ___  _____      __
   | |    / _ \ / _` |/ _ \   |  _  // _ \ \ / / |/ _ \ \ /\ / /
   | |___| (_) | (_| |  __/   | | \ \  __/\ V /| |  __/\ V  V /
    \_____\___/ \__,_|\___|   |_|  \_\___| \_/ |_|\___| \_/\_/

```

---

-> # Code Review

## Agenda

- Pull request with code review and CI
- Author's perspective
- Reviewer's perspective
- Discussion

---

# What's a Pull Request?

> Pull requests let you _tell others about changes_
> you've pushed to a branch in a repository on GitHub.
> Once a pull request is opened, you can **discuss** and
> **review** the potential changes with collaborators
> and **add follow-up commits** before your changes
> are merged into the base branch.

[Github](https://docs.github.com/pull-requests/collaborating-with-pull-requests)

---

# Why Code Reviews?

## Goal

- Goal: Improve the quality of the code that's added
- Systematic approach to reviewing new code for mistakes
- Checks if all _requirements_ have been implemented correctly

---

# Why Code Reviews?

## Share Knowledge

> Code review is **more than just a quality check**

Multiple developers looking at the PR:

- They are exposed to new code
- Reviewers _have to understand_ the context and scope
- Can be a great tool to reduce technical debt

---

# Why Code Reviews?

## Get Feedback

Can be a valuable learning moment for developers
=> Get _feedback_ about your code and coding style

---

# Pull Request and Code Review

- In general: Pull request setup and CI
- Author: How to **create** a pull request?
- Reviewer: How to **review** a pull request?

---

# Pull Request: Setup

Opinionated, whatever works _best for the team_

- Decide how developers are assigned
- Decide how comments should be handled
- Define number of approvals and the condition

---

# Pull Request: CI (Continuous Integration)

> Automate everything that's possible

- Tests
- Code Coverage
- Deployment
- Formatting
- Static code analysis
- Special rules e.g. line length or forbidden imports

---

# Author: How to Create a Pull Request?

How to open a pull request that can easily be reviewed?

---

# Create a Pull Request

## Share Insights

> What would you tell somebody?

- "No description provided"?!
- "WIP" or "Make linter happy"?!

---

# Create a Pull Request

## Share Insights

> What would you tell somebody?

Don't explain what is clear already,
but explain what is **interesting to others**.

- What were the decisions and why?
- Are you uncertain about some decisions?

---

# Create a Pull Request

## Description

Screenshots or video
Smaller change is easier to review
Speak about controversial questions before code review
Commits (and commit messages) can be powerful

---

# Create a Pull Request

## Share Knowledge

Also leverage other formats:

- Call to discuss a topic in detail
- Small presentation

---

# Create a Pull Request

## Self-Review

Review your own pull request
... and this time it's **fine if you're nitpicky**

Avoid unfinished pull requests and multiple review loops

---

# Reviewer: How to Review a Pull Request?

How to give valuable feedback?

---

# Code Review

## Friendly Atmosphere

Serves the team, is _not about letting pass_
Language is important, since it might look negative
Code reviews aren't a tool to criticize colleagues

Comments should be **about code**

---

# Code Review

## Goal: Specific and Actionable Feedback

Clear and **over-communicate**
Tell what to do or "you decide"
Better ask questions rather than making statements
With enough information to understand the question

---

# Code Review

## Try the Code

Checkout and **run** the code
Try to **understand**
Try to **break it** (QA)!

---

# Code Review

## Add Comments

- If you don't understand: Do not trust, _ask questions_
- Discussions, but keep them small ⚠️
- PR in PR or code suggestions? ⚠️
- Differentiate if code suggestion would be _opinionated_ ⚠️
- Check your review again

---

# Code Review

## Questions About the Change

- How important is the code that is changed?
- Do I understand the change?
- Are feature requirements covered?
- Could the change break something or other teams?
- What are the edge cases?
- Could this introduce security issue?
- Were tests added?

---

# Code Review

## Questions About the Code

- Is there a simpler way to achieve the same goal?
- Is documentation missing / needs to be updated?
- Is the change consistent (naming, modules, libraries)? ⚠️
- Is the code self-explanatory?
- Could reorganizing improve readability?

---

# Code Review Discussion

What is working well for you?

**End**

---

# Sources

- [Clément Mihailescu](https://www.youtube.com/watch?v=1Ge__2Yx_XQ)
- [Alex Omeyer](https://dev.to/alexomeyer/code-review-a-comprehensive-checklist-5gnm)
