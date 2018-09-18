## Reviewing Pull Requests

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

This [classic GitHub video](https://githubber.tv/github/the-p-dot-e-e-dot-p-method) should also help you decide if you're the right reviewer.

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
