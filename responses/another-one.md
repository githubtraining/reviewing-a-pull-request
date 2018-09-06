This document is an attempt at creating the course in a different manner. The story and activities will be created in this document and parsed out to other files once it has received a general approval. Moving between files to track the flow of the course is annoying (to me) and having one stream of content just makes more sense for my brain. 

Layout of this file:

```
# New comment on issue or pr

Content inside said comment

## response (success or failure)

```

# Intro to course

- pull request

Hey there, I see you're new around here. As a member of the engineering team, you will be required to get and give pull request reviews before changes can be merged to production. This is important because it ensures the best :ok_hand: code makes it to production and maintains the momentum of changes to our products.
   
As you can see, I've just opened this pull request and requested a review from you. I haven't done much yet, but would you mind taking a quick look and adding comments.

Comments are used early in the review process when an explicit approval or request for changes is not yet warranted. They enable you to inquire about the proposed change, make suggestions to the author, and generally help your team make awesome things.

Not only can you ask questions or make suggestions to the proposed change via your sweet vocabulary, you can suggest changes directly to the code using the [```suggestion ``` feature](https://team.githubapp.com/posts/31384). 

<details><summary>Responsibilies of a reviewer</summary>

As a pull request reviewer, your role is to help the pull request author:

- Make sure that code destined for production is of the highest quality.
- Make sure that we have commented on and confirmed any intentional shortcuts (techdebt) being taken in the code.
- Make yourself aware of potential risks associated with their changes.

As a reviewer, your responsibilities include:

- Calling out any potential issues you spot with regards to code quality, security, or inaccuracies in business logic,
- Suggesting other reviewers to the author if you feel they are warranted,
Commenting on, approving, or requesting changes on the PR, and
- Providing suggestions for alternate or better implementation details.

</details>

### :keyboard: Activity: Add a comment to my pull request
   
- User adds a line comment: PR has a change to `file` with `reviews reviews reviews` "accidentally" entered (i.e. Intro to pull request reviews reviews reviews)

## Commented on pull request (success) 

Nice work @{{ user.username }}, by providing feedback on my pull request it enables me to make changes or reevaluate how I am making my desired change. Pull request reviews don't stop at commenting though, you can also `approve` or `request changes` on my pull request that will enable me (or prevent in the case of request changes) to merge my pull request!

Typically when you get asked to review something at GitHub, you should acknowledge the request within 1 business day. Acknowledging a review request can be a quick direct message to the author in Slack, leave a comment on the PR, leave a review, _or_ in some cases you may need to reject the review request altogether. 

I've made some changes to this branch and would love :heart: it if you could `approve` this pull request. For now, just approving the pull request will suffice, in a moment we will look at requesting changes :+1:.

<details>
<summary>Why would I reject a review request</summary>

After discerning the context for the PR and observing its stage of progress, you should consider whether you feel comfortable moving forward with a review.

Consider these qualifiers:

- Do you have relevant expertise with the programming languages in use?
- Do you have enough context to provide accurate feedback or ask helpful questions regarding the business logic at hand?
- Does this PR look pretty similar to the other PRs that your team has been asked to review lately?

You might consider offering a partial review to the author for the areas that you do understand, and noting in your review that you didn't feel comfortable reviewing 100% of the content.

And of course, if you can't obtain sufficient context or you don't have the expertise such that you feel comfortable providing the review, you must opt out of the review.

You can leave a comment politely declining the review request, and/or surface the situation to your manager for guidance.

</details>

### :keyboard: Activity: Approve a pull request

_steps to approve a pr_

## Approved pull request (success)

Thanks for approving my pull request! Now that my pull request is approved, I can merge it into our project. While I'm merging this in (I might have already :grinning:), why don't you head over to this new pull request I made. With you helping me out, I seem to be able to tackle anything! :muscle::muscle-right:

[Link to next pr](link to next pr)

# Using requires changes on a pull request

Thanks again for all your help on that last PR. Since you are helping me out, I figured I would add some more changes to our project, with our powers combined _anything_ is possible! This last change I made doesn't seem to be working though. :grimacing: 

Sometimes when you are reviewing a pull request, the author might identify that some of the functionality isn't working and needs a helping hand :wave: to solve the problem, in other instances it might "work on their machine" and they won't be aware that it doesn't work. When reviewing a pull request, not only is it important to look :eyes: at the code, but actually testing the code in a `dev` environment can help pinpoint any bugs that you don't catch by just looking at the code. 

If you could check out this code for me and tell me what is wrong, that would be fantastic! 

### :keyboard: Activity: Using requires changes

_instructions for using requires changes_ the broken code will be something easy to spot , alternatively, we can have them enable github pages and be able to use the preview pages option to identify the issue

## Requires changes (success)

Thanks for catching that bug :bug:. In my excitement to ship more stuff I must have made a typo. I'm making a change to this branch to fix my mistake, once I've done that you can click **Approve changes**. 

### :keyboard: Accept my changes

_instructions for accepting change on convo tab_

# Requesting a reviewer

- issue

Wow, I've been working _really_ hard on this project but I haven't let you show off your sweet programming skills yet. I'd like you to make a change to our project to really make it your own :+1:. After you create your change and open a PR, I would like to review it. The best way to get someone to review your pull request is to request them to review it. 

As your reviewer, I'm going to check to make sure your change doesn't break anything :construction:, but it is your job as the author of the pull request to tell me what you are trying to accomplish. By letting me know what you are trying to do in the initial comment of the pull request, I can get to testing and reviewing immediately without needing to ask you clarifying questions. Being able to jump into a review without needing to ask you questions lets us work asyncronously, so I can continue being a nightowl :owl: and you can enjoy being the early bird :bird:.

### :keyboard: Activity: Request a reviewer

_steps to request a reviewer / what changes to make for LL to work_