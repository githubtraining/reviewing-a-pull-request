Questions:
- We open a pull request in step 2. What branch are we using? What changes are we introducing?
- We open another pull request in step 4. Same question.
- @beardofedu do we need the lower stuff? 

@beardofedu, not sure what these other notes were from, but they're taken from `notes`, outline.md, and `finish.md`.

1. First PR comment
   Hey there, I see you're new around here. As a member of the engineering team, you will be required to get and give pull request reviews before changes can be merged to production. This is important because ... as you can see, I've just opened this pull request and requested a review from you. I haven't done much yet, but would you mind taking a quick look and adding comments.

   Comments are used early in the review process when an explicit approval or request for changes is not yet warranted.

   You can suggest changes using the ```suggestion ```.

   - User adds a line comment: PR has a change to `file` with `reviews reviews reviews` "accidentally" entered (i.e. Intro to pull request reviews reviews reviews)

1. Second PR comment
   - Bot has added a commit and now it is 30%
   - Content: Guidelines for a 30% review
   - User adds a 30% review
1. Learning Lab
1. Introduction
   - Overview of the course
   - Terminology: Must / Should
     - Must assign themselves
     - Should apply a label
1. Why we do code review
   - Pull from https://github.com/github/experience-engineering-business/blob/master/guides/code-review.md
1. Review Request overview
   - Formal
   - Informal
   - Uninvited
1. Review Request Example
   - PR w/ student assigned as a reviewer
   - This example will be good to go, so just an approval is needed
1. Code review at GitHub
   - Pull from https://github.com/github/docs/blob/master/docs/crafts/engineering/code-review-at-github.md#how-to-review-a-pr
1. Starting a review
   - Understand the PR (Discern the context section)
   - 30% v 90%
     - 30% section
     - 90% section
     - Overserve the stage of progress section
1. Writing a Review
   - Reviewing the diff
   - Testing it
   - Automated reviews
     - Introduction to sentinel
   - Line level comments
   - Summarizing your review
1. Approving a Pull Request

Auditor: What repos require a peer review and approval in order to deploy?
Auditor: For repos that do not require this, yet allow for deployment of code/configs to production, is there a documented business justification for this configuration that reflects on how risks are addressed with compensating controls elsewhere in the process?
Auditor: When in the process is peer review required?
Auditor: What are the rules around who is considered an appropriate peer reviewer for the changes being made (i.e., product vs internal tools vs prod eng)
Auditor: How can you tell a PR has been appriopriately peer reviewed and signed off
Auditor: Is there an exception process defined for code that requires peer review but must be deployed without it for whatever reason?


----

1. Introduction
   - Overview of the course
   - Terminology: Must / Should
     - Must assign themselves
     - Should apply a label
1. Why we do code review
   - Pull from https://github.com/github/experience-engineering-business/blob/master/guides/code-review.md
1. Review Request overview
   - Formal
   - Informal
   - Uninvited
1. Review Request Example
   - PR w/ student assigned as a reviewer
   - This example will be good to go, so just an approval is needed
1. Code review at GitHub
   - Pull from https://github.com/github/docs/blob/master/docs/crafts/engineering/code-review-at-github.md#how-to-review-a-pr
1. Starting a review
   - Understand the PR (Discern the context section)
   - 30% v 90%
     - 30% section
     - 90% section
     - Overserve the stage of progress section
1. Writing a Review
   - Reviewing the diff
   - Testing it
   - Automated reviews
     - Introduction to sentinel
   - Line level comments
   - Summarizing your review
1. Approving a Pull Request

Storyline of Course:

New hire within GitHub Engineering, first task is to modify a Tetris game to show off their personality




Source of Truth: Order of activites
Readme - approve a PR
3090 - understand what to review at different stages of development
suggest - how to provide feedback using the suggested changes function


yourturn

----

Wow {{ user.username }}, we covered a lot in this course! You are definitely a master at reviewing and authoring pull requests at GitHub now. While, we covered a lot, there are a couple more things that I wanted to let you know about before saying goodbye :cry:.

_Use this as an area to include anything not covered in the course_

xTerminology

Before starting a review

xReview requests


Informal review requests

Uninvited reviews


Role of the reviewer


Reviewer vs. author responsibilities
  - xReviewer responsibilities
  - author responsibilities

Either a reviewer or an author may:

Deploy the pull request to review-lab to try it out.
Discern the context

Author self-reviews


Observe the stage of progress

- 30% vs. 90% review
  - 30% review
  - 90% review


Opting-out and partial reviews


Involving other reviewers

When to suggest other reviewers

Selecting reviewers


Writing a review
- Review the diff
- Consider trying it out
- Leaving review comments
- Leaving suggested changes
- Committing directly to another person's branch
- Address automated reviews
- Sentinel reviews
- Summarizing your review

xApproving a Pull Request
- Conditions for approval

Requesting changes

Dismissing a review

Stalemates

CODEOWNERS
