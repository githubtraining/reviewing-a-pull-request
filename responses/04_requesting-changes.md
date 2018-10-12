# Using `request changes` on a pull request

Thanks again for all your help on that last pull request. With our powers combined, _anything_ is possible! This last change might introduce some new changes that aren't going to look great.

Sometimes, the author might identify that something isn't working. They might need a helping hand :wave: to solve the problem. In other instances, it might only work in their environment. When reviewing a pull request, look at and test the code to pinpoint any bugs or unexpected behavior.

If you could check out this code for me and tell me what is wrong, that would be fantastic.

### Writing a review

#### Review the `diff`

Reviewing the `diff`, the comparison of the proposed code, in the context of the whole project. Could it introduce performance problems, or security vulnerabilities? Try to predict unintended consequences that this change could cause.

#### Try it out

For most things, actually trying out the proposed change is a good idea. This makes it a lot easier to tell if the actual change matches the intention.

<details><summary>
Here are some ways you could try the implementation:</summary>

- Clone the repository, and checkout to the branch compared in the pull request. Run the application in your local development environment.
- Deploy the pull request to a review-lab or staging environment (as appropriate).
</details>

When summarizing your review, let the author know if you completed any of these tests.

#### Empathy and Constructive Feedback

The goal of providing feedback on a pull request is to ensure that the best possible change is being added. Sometimes, a change isn't addressing the problem in the best possible way. It's the reviewer's responsibility to provide meaningful and constructive feedback.

<details><summary>Requesting Changes 101</summary>
    
- Before you submit your review, your line comments are pending and only visible to you. You can edit pending comments anytime before you submit your review. To cancel a pending review and its pending comments, scroll down to the end of the page in the Conversation tab. Then click _**Cancel review**._
</details>

### :keyboard: Activity: Requesting changes

1. On the pull request, click **Files changed**
1. Hover over the line of code where you'd like to add a comment, and click the blue comment icon
1. In the comment window, type your comment
1. Click **Start a review**
    - If you have already started a review, you can click **Add review comment**
1. Above the changed code, click **Review changes**
1. Type a comment summarizing your feedback on the proposed changes
    - _Note: The problem here is that too many Tetris pieces are the same color. In your review, you might want to suggest that I choose colors which would be easier to see when playing the game._
1. Select **Request changes** to submit feedback introducing changes necessary before merging
1. Click **Submit review**

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._
