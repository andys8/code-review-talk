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

# What's a pull request?

> Pull requests let you _tell others about changes_
> you've pushed to a branch in a repository on GitHub.
> Once a pull request is opened, you can **discuss** and
> **review** the potential changes with collaborators
> and **add follow-up commits** before your changes
> are merged into the base branch.

[Github](https://docs.github.com/pull-requests/collaborating-with-pull-requests)

---

# Why code reviews?

## Goal

- Goal: Improve the quality of the code that's added
- Systematic approach to reviewing new code for mistakes
- Checks if all _requirements_ have been implemented correctly

---

# Why code reviews?

## Share knowledge

> Code review is **more than just a quality check**

Multiple developers looking at the PR:

- They are exposed to new code
- Reviewers _have to understand_ the context and scope
- Can be a great tool to reduce technical debt

---

# Why code reviews?

## Get feedback

Can be a valuable learning moment for developers
=> Get _feedback_ about your code and coding style

---

# Pull Request and Code Review

- In general: Pull request setup and CI
- Author: How to _create_ a pull request?
- Reviewer: How to _review_ a pull request?

---

# Pull Request: Setup

Opinionated, whatever works _best for the team_

- Team: Decide how comments should be handled.
- Define number of approvals and when
- Decide how developers are assigned

---

# Pull Request: CI (Continuous Integration)

> Automate everything that's possible

- Tests
- Code Coverage
- Deployment
- Formatting
- Static code analysis
- Special rules the team has decided on
  e.g. line length, forbidden imports or words

---

# Author: How to create a pull request?

How to open a pull request that can easily be reviewed?

---

# Create a pull request

## Provide information

> What would you tell somebody?

- "No description provided"?!
- "WIP" or "Make linter happy"?!

---

# Create a pull request

## Share insights

> What would you tell somebody?

Don't explain what is clear already,
but explain what is **interesting to others**.

- What were the decisions and why?
- Are you uncertain about some decisions?

---

# Create a pull request

## Provide information

Screenshots or video
Smaller change is easier to review
Speak about controversial questions before code review
Commits (and commit messages) can be powerful

---

# Create a pull request

## Share knowledge

Also leverage other formats:

- Call to discuss a topic in detail
- Small presentation

---

# Create a pull request

## Self-Review

Review your own pull request
... and this time it's **fine if you're nitpicky**

Avoid unfinished pull requests and multiple review loops

---

# Reviewer: How to review a pull request?

How to give valuable feedback?

---

# Code Review

## Friendly atmosphere

Serves the team, is not about letting pass
Language is important, since it might look negative
Code reviews aren't a tool to criticize colleagues
Comments should be about the code

---

# Code Review

## Goal: Specific and actionable feedback

**Clear and over-communicate**
What to do? Or "you decide".
Ask questions rather than making statements.
Enough information so the author can understand the question

---

# Code Review

## Try the code

Checkout and **run** the code
Try to **understand**
Try to **break it** (QA)!

---

# Code Review

## Add comments

- If you don't understand: Do not trust, ask questions
- Discussions, but keep them small ⚠️
- PR in PR or code suggestions? ⚠️
- Differentiate if code suggestion would be opinionated ⚠️
- Check your review again

---

# Code Review

## Questions about change

- How important is the code that is changed?
- Do I understand the change?
- Are feature requirements covered?
- Could the change break something or other teams?
- What are the edge cases?
- Could this introduce security issue?
- Were tests added?

---

# Code Review

## Questions about code

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
