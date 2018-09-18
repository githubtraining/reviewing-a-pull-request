# Using `request changes` on a pull request

Thanks again for all your help on that last pull request. Since you are helping me out, I figured I would add some more changes to our project. With our powers combined, _anything_ is possible! This last change I made doesn't seem to be working, though. :grimacing:

Sometimes when you are reviewing a pull request, the author might identify that some of the functionality isn't working and needs a helping hand :wave: to solve the problem. In other instances, it might only work in their environment. When reviewing a pull request, it's important to both look at, and test the code to pinpoint any bugs or unexpected behavior.

If you could check out this code for me and tell me what is wrong, that would be fantastic.

### Writing a review

#### Review the diff

When reviewing the diff, read it critically and think about it in connection with other parts of the system. Try to anticipate unintended consequences (exceptions, performance problems, security vulnerabilities, etc.) this change could cause.

If the diff adds more code than you can comprehend in a single reading, suggest that the author break the pull request up into smaller chunks that can be reviewed more easily, or try to find a way to accomplish the same goal with less code.

#### Try it out

For most things, actually trying out the proposed change is a good idea. This makes it a lot easier to tell if the actual change matches the intention.

Here are some ways you could try the implementation:

- Clone the repository, checkout to the branch, and run the application in your local development environment
- Deploy the pull request to a review-lab or staging environment (as appropriate)

When summarizing your review, consider letting the author know whether or not you tried out the implementation.


#### Empathy and Constructive Feedback

The goal of providing feedback on a pull request is to ensure that the best possible change is being applied to the application. If a change isn't fixing the problem or adding a new feature the best possible way, it is your role as a reviewer to provide that feedback to the author in a meaningful and constructive manner. Pull requests are a great learning experience for both the author and the reviewer, and by avoiding constructive feedback, you are limiting the potential of your team.


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

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
