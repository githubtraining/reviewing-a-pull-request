This document is an attempt at creating the course in a different manner. The story and activities will be created in this document and parsed out to other files once it has received a general approval. Moving between files to track the flow of the course is annoying (to me) and having one stream of content just makes more sense for my brain.

Layout of this file:

```
# New comment on issue or pr

Content inside said comment

## response (success or failure)

```

# Intro to course

- pull request

Hey there, I see you're new around here. As a member of the engineering team, you will get and give pull request reviews before merging changes into production. This is important because it ensures the best quality code makes it to production and maintains the momentum of changes to our products.

As you can see, I've opened this pull request and requested a review from you. I haven't done much yet, but would you mind taking a quick look and adding a line comment to the file?

Comments are used early in the review process when an explicit approval or request for changes is not yet warranted. They enable you to inquire about the proposed change, make suggestions to the author, and generally help your team make awesome things.

Not only can you ask questions or make suggestions to the proposed change via your sweet vocabulary, you can suggest changes directly to the code using the [```suggestion ``` feature](https://team.githubapp.com/posts/31384).

<details><summary>Responsibilities of a reviewer</summary>

As a pull request reviewer, your role is to help the pull request author by making sure:

- Code destined for production is of the highest quality
- Any intentional shortcuts (technical debt) added to the code are properly commented on and confirmed
- The greater team is aware of potential risks associated with changes

As a reviewer, your responsibilities include:

- Calling out any potential issues you spot with regards to code quality, security, or inaccuracies in business logic
- Suggesting other reviewers to the author, when warranted
- Commenting on, approving, or requesting changes on the PR
- Providing suggestions for alternate or better implementation details

</details>

### :keyboard: Activity: Add a comment to my pull request

- User adds a line comment, NOT a review: PR has a change to `file` with `reviews reviews reviews` "accidentally" entered (i.e. Intro to pull request reviews reviews reviews)

## Commented on pull request (success)

Nice work @{{ user.username }}. By providing feedback on my pull request, you've enabled me to make changes or reevaluate how I am making my desired change. But, pull request reviews don't stop at commenting. You can also `approve` or `request changes` on my pull request to enable me to merge my pull request (Or, if you request changes, prevent me from merging until the pull request has had some work)!

Typically when you get asked to review something at GitHub, you should acknowledge the request within 1 business day. Acknowledging a review request can be sending a quick direct message to the author in Slack, leaving a comment on the pull request, leaving a review, _or_ in some cases, rejecting the review request altogether.

I've made some changes to this branch and would love :heart: it if you could `approve` this pull request. For now, just approving the pull request will suffice. In a moment we will look at requesting changes :+1:.

<details><summary>Before you review, some things to consider</summary>

#### Discern the context

Reviewing the title and body of the PR should help you understand the intended change and the reasoning behind the change. This clarification _should_ help you identify limitations, boundaries, and other context that could prevent the pull request from being merged in its current state.

#### Observing the progress

As a reviewer, there are certain attributes to look for when identifying how to best provide feedback to the author of a pull request. For early stage pull requests, or "30%" pull requests, reviews should focus on the general direction of the changes. Identifying if the pull request's goal is feasible or if the architecture can handle the change is more important than nitpicking the style, polish, or wording of the change. However, a "90%" PR is almost finalized, so checking for consistent style, that it is free of error messages, and exceptional cases are handled or at least tracked is vital at this stage.

Regardless of the stage of the pull request, it is important to prioritize your feedback on the most essential changes, suggest changes for minor issues, and open a separate pull request against the author's branch when suggesting major changes.

</details>

<details>
<summary>Why would I reject a review request?</summary>

After discerning the context for the PR and observing its stage of progress, you should consider whether you feel comfortable moving forward with a review.

Consider these qualifiers:

- Do you have relevant expertise with the programming languages in use?
- Do you have enough context to provide accurate feedback or ask helpful questions regarding the business logic at hand?
- Does this pull request look similar to the other pull requests that your team has been asked to review lately?

You might consider offering a partial review to the author for the areas that you do understand, and noting in your review that you didn't feel comfortable reviewing 100% of the content.

And of course, if you can't obtain sufficient context or you don't have the expertise such that you feel comfortable providing the review, you should opt out of the review.

You can leave a comment politely declining the review request, or surface the situation to your manager for guidance.

</details>

### :keyboard: Activity: Approve a pull request

1. In the pull request, click the **Files changed** tab.
1. Review the changes in the pull request by optionally commenting on specific lines.
1. Above the changed code, click **Review changes**.
1. Type a comment summarizing your feedback on the proposed changes.
1. Select **Approve** to approve merging the changes proposed in the pull request.
1. Click **Submit review**.

## Approved pull request (success)

Thanks for approving my pull request! Now that my pull request is approved, I can merge it into our project. While I'm merging this in (I might have already :grinning:), why don't you head over to this new pull request I made? With you helping me out, I seem to be able to tackle anything! :muscle:

<details><summary>What repositories require a peer review and approval in order to deploy?</summary>

At GitHub, most of the repositories that you work in will require an approved peer review prior to deployment. Not only do these repositories require peer reviews, but they use automated tests to ensure the code being shipped :ship: is as amazing as you are. :sparkles:

Additionally, some repositories use the [CODEOWNERS](https://help.github.com/articles/about-codeowners/) feature in concert with the pull request approval process. If approval is required from a code owner, the code owner has the final authority to approve the pull request. Although providing your approval on a pull request with `CODEOWNERS` enabled won't enable the pull request to be merged, it does demonstrate additional _confidence_ in the change.

</details>


[Link to next pr](link to next pr)

# Using `requires changes` on a pull request

Thanks again for all your help on that last pull request. Since you are helping me out, I figured I would add some more changes to our project. With our powers combined, _anything_ is possible! This last change I made doesn't seem to be working, though. :grimacing:

Sometimes when you are reviewing a pull request, the author might identify that some of the functionality isn't working and needs a helping hand :wave: to solve the problem. In other instances, it might "work on their machine" and they won't be aware that it doesn't work in other environments. When reviewing a pull request, not only is it important to look :eyes: at the code, but actually testing the code in a `dev` environment can help pinpoint any bugs that you don't catch by just looking at the code.

If you could check out this code for me and tell me what is wrong, that would be fantastic.

<details><summary>Writing a review</summary>

#### Review the diff

When reviewing the diff, read it critically and think about it in connection with other parts of the system. Try to anticipate unintended consequences (exceptions, performance problems, security vulnerabilities, etc.) this change could cause.

If the diff adds more code than you can comprehend in a single reading, suggest that the author break the pull request up into smaller chunks that can be reviewed more easily, or try to find a way to accomplish the same goal with less code.

#### Try it out

For most things, actually trying out the proposed change is a good idea. This makes it a lot easier to tell if the actual change matches the intention.

Here are some ways you could try the implementation:

- Clone the repository, checkout to the branch, and run the application in your local development environment
- Deploy the pull request to a review-lab or staging environment (as appropriate)

When summarizing your review, consider letting the author know whether or not you tried out the implementation.


#### Empathy =/= Avoiding Constructive Feedback

The goal of providing feedback on a pull request is to ensure that the best possible change is being applied to the application. If a change isn't fixing the problem or adding a new feature the best possible way, it is your role as a reviewer to provide that feedback to the author in a meaningful and constructive manner. Pull requests are a great learning experience for both the author and the reviewer, and by avoiding constructive feedback, you are limiting the potential of your team.

</details>


### :keyboard: Activity: Using requires changes

_instructions for using requires changes_ the broken code will be something easy to spot, alternatively, we can have them enable GitHub pages and be able to use the preview pages option to identify the issue

1. On the pull request, click **Files changed**.
1. Hover over the line of code where you'd like to add a comment, and click the blue comment icon.
1. In the comment window, type your comment. When you're done, click **Start a review**. If you have already started a review, you can click **Add review comment**.
  - _Note: Before you submit your review, your line comments are pending and only visible to you. You can edit pending comments anytime before you submit your review. To cancel a pending review, including all of its pending comments, scroll down to the end of the timeline on the Conversation tab, then click **Cancel review**._
1. Above the changed code, click **Review changes**.
1. Type a comment summarizing your feedback on the proposed changes.
1. Select **Request changes** to submit feedback that must be addressed before the pull request can be merged.
1. Click **Submit review**.

## Requires changes (success)

Thanks for catching that bug :bug:. In my excitement to ship more stuff, I must have made a typo. I'm making a change to this branch to fix my mistake. Once I've done that, please click **Approve changes**.

### :keyboard: Accept my changes

_instructions for accepting change on convo tab_

# Requesting a reviewer

- issue

Wow, I've been working _really_ hard on this project, but I haven't let you show off your sweet programming skills yet. I'd like you to make a change to our project to really make it your own :+1:. After you create your change and open a pull request, I would like to review it. The best way to get someone to review your pull request is to request for them to review it.

As your reviewer, I'm going to check to make sure your change doesn't break anything :construction:, but it is your job as the author of the pull request to tell me what you are trying to accomplish. By letting me know what you are trying to do in the initial comment of the pull request, I can get to testing and reviewing immediately without needing to ask you clarifying questions. Being able to jump into a review allows us to work asynchronously, so I can continue being a night-owl :owl: and you can enjoy being the early bird :bird:.

### :keyboard: Activity: Request a reviewer

_steps to request a reviewer / what changes to make for LL to work_

1. In the pull request, click **Request** in the right sidebar under **Reviewers**.
1. Type the username of the person or the name of the team you're asking to review your changes, then click their team name or username to request a review.

# Graceful Exit

- issue

Nice work helping me with all of these pull requests! As you embark on your journey of making GitHub better everyday, you might want to keep this article in your [back-pocket](https://githubber.com/article/crafts/engineering/how-to-review-a-pull-request#approving-a-pull-request) :jeans:. It covers a lot of the stuff we covered in this course and provides some more tips and requirements for reviewing pull requests within GitHub. If you have any questions along the way, make sure to ask you team (or the team you are helping) to answer any questions :question: as they come up.
