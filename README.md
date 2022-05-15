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

- Pull Request / CI
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

# Pull Requests and CI (Continuous integration)

CI: Move discussion to tooling. E.g. line length.
Or forbidden words, modules
Opinionated, whatever works best for the team
Team: Decide how comments should be handled.
Decide CI and device number of approvals and when.

---

# Pull Request and Code Review

- How to _create_ a pull request?
- How to _review_ a pull request?

=> Open discussion afterwards

---

# Create a Pull Request

Add information: what would you tell somebody?
Screenshot, Video (examples from CE?)
Smaller is easier to review
Try to speak about controversial stuff before code review

Use commit messages
Author: Review your own pull request

Don't explain what is clear already, but explain what is interesting to others.
What were the decisions and why? Are you unsure about certain decisions?

Share knowledge: But only if it makes sense,
otherwise different format -> Followups

---

# Code Review 1

Serves the team, is not about letting pass
Clear, over communicate. What to do? Or "you decide".
Language is important, be nice to each other.
Comments should be about the code (Not: I don't like this).
Language is very important, since it might look negative.
Do not trust, ask questions instead
PR in PR? Or suggestions?
Check your comments again
Discussions: But keep small

---

# Code Review 2

QA! Devs should always do QA. Break it.

Tests: Were tests added? Do the tests make sense coverage?

Relation: How important is the code?
Is it a small improvement or a large feature that could break everything?

Hard: Consistency, naming, modules/folders
Beware of bikeshedding
Is the change an opinion and could the author just have a different opinion

---

# Code Review 3: Questions

- How important is the code that is changed?
- Do I understand the change?
- Is there a simpler way to achieve the same goal?
- Could the change break something or other teams?
- What are the edge cases?
- Could this introduce security issue?
- Are tests added?

---

# Code Review: Discussion

What is working well?
