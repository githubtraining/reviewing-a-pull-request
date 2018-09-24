# Commenting on Pull Requests

As a member of an awesome team, you will get and give pull request reviews before merging changes into production. This is important because it ensures quality code and maintains momentum of changes to your products.

As you can see, I've opened this pull request and requested a review from you. Pull requests, unlike issues where project contributors _discuss_ a bug or new feature, are places to _share_ the changes being made to the repository.

**Comments** are used early in the review process when an explicit approval or request for changes is not yet warranted. They enable you to inquire about the proposed change, make suggestions, and help your team create awesome features.

Not only can you ask questions or make suggestions to the proposed change, you can suggest changes directly to the code using the [```suggestion ``` feature](https://team.githubapp.com/posts/31384). _Note: At the time of the team post, this feature will only be staff shipped, so only expect to see it on repositories in the `github` org._

### Responsibilities of a reviewer

As a pull request reviewer, your role is to help the pull request author by making sure:

- Code destined for production is of the highest quality
- Any intentional shortcuts (technical debt) added to the code are properly commented on and confirmed
- The greater team is aware of potential risks associated with changes

These broad responsibilities can include more specific goals, like:

- Calling out any potential issues you spot with regards to code quality, security, or inaccuracies in business logic
- Suggesting other reviewers to the author, when warranted
- Commenting on, approving, or requesting changes on the PR
- Providing suggestions for alternate or better implementation details

### What repositories require a peer review and approval in order to deploy?

Depending on how your admin has setup the code repositories within your organization adhering to best practises, most of the repositories that you work in will require an approved peer review prior to deployment. Not only do these repositories require peer reviews, but they use automated tests to ensure the code being shipped :ship: is as amazing as you are. :sparkles:

Additionally, some repositories use the [CODEOWNERS](https://help.github.com/articles/about-codeowners/) feature in concert with the pull request approval process. If approval is required from a code owner, the code owner has the final authority to approve the pull request. Although providing your approval on a pull request with `CODEOWNERS` enabled won't enable the pull request to be merged, it does demonstrate additional _confidence_ in the change.

### :keyboard: Activity: Add a comment to my pull request

1. On the pull request, click **Files changed**.
1. Hover over the line of code where you'd like to add a comment, and click the blue comment icon.
1. In the comment window, type your comment. You can ask a question, or leave a more general comment.
1. When you're done, click **Add single comment**.

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
