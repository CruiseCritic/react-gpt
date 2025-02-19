# Contributing to this project

Please take a moment to review this document in order to make the contribution
process easy and effective for everyone involved.

_**Please Note:** These guidelines are adapted from [@necolas](https://github.com/necolas)'s
[issue-guidelines](https://github.com/necolas/issue-guidelines) and serve as
an excellent starting point for contributing to any open source project._

<a name="pull-requests"></a>
## Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

The project uses `semantic-release` to make releases, which requires the commit messages to have a certain convention
for the release action to be triggered. To find out more check [Commit message format](https://github.com/semantic-release/semantic-release#commit-message-format).


**Please ask first** before embarking on any significant pull request (e.g.
implementing features, refactoring code, porting to a different language),
otherwise you risk spending a lot of time working on something that the
project's developers might not want to merge into the project.

<a name="development"></a>
## Development Process
Here are some guidelines to making changes and preparing your PR:

1. Make your proposed changes to the repository, along with updating/adding test cases.
2. (Optional) If you prefer to also test your changes in a real application, you can do the following:
  1. Run `npm link` in `react-gpt` repository.
  2. `cd` to your favorite React application, run `npm link react-gpt` to point to your local repository.
  3. Run your application to verify your changes.
3. Run `npm test` to verify all test cases pass.
4. Run `npm run lint` to verify there are no linting errors.
