# Contributing

## Code of Conduct

All members of the project community must abide by the [Contributor Covenant, version 2.0](CODE_OF_CONDUCT.md).
Only by respecting each other we can develop a productive, collaborative community.
Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting [moodle-dl@ist-ein-knaller.de](mailto:moodle-dl@ist-ein-knaller.de) and/or a project maintainer.

We appreciate your courtesy of avoiding political questions here. Issues which are not related to the project itself will be closed by our community managers.

## Engaging in Our Project

We use GitHub to manage reviews of pull requests.

* If you are a new contributor, see: [Steps to Contribute](#steps-to-contribute)

* Before implementing your change, create an issue that describes the problem you would like to solve or the code that should be enhanced. Please note that you are willing to work on that issue.

* The team will review the issue and decide whether it should be implemented as a Pull Request. In that case, they will assign the issue to you. If the team decides against picking up the issue, it will be closed with a proper explanation.

* Our code style is based on [Black's Pep8 subset(https://black.readthedocs.io/en/stable/the_black_code_style.html).

## Steps to Contribute

Should you wish to work on an issue, please claim it first by commenting on the GitHub issue that you want to work on. This is to prevent duplicated efforts from other contributors on the same issue.

Only start working on the Pull Request after the team assigned the issue to you to avoid unnecessary efforts.

If you have questions about one of the issues, please comment on them, and one of the maintainers will clarify.

We kindly ask you to follow the [Pull Request Checklist](#Pull-Request-Checklist) to ensure reviews can happen accordingly.

## Contributing Code

You are welcome to contribute code in order to fix a bug or to implement a new feature that is logged as an issue.

Only start working on the Pull Request after the team assigned the issue to you to avoid unnecessary efforts.

The following rule governs code contributions:

* Contributions must be licensed under the [GPL-3.0 License](LICENSE)

## Contributing Documentation

You are welcome to contribute documentation to the project.

The following rule governs documentation contributions:

* Contributions must be licensed under the same license as code, the [GPL-3.0 License](LICENSE)

## Pull Request Checklist

* Branch from the master branch and ensure it is up to date with the current master branch before submitting your pull request. If it doesn't merge cleanly with master, you may be asked to resolve the conflicts.

* Commits should be as small as possible while ensuring that each commit is correct independently (i.e., each commit should compile and pass tests).

* Pull requests must not contain compiled sources (already set by the default .gitignore) or binary files

* Test your changes as thoroughly as possible before you commit them. Preferably, automate your test by unit/integration tests. If tested manually, provide information about the test scope in the PR description (e.g. “Test passed: Upgrade version from 0.42 to 0.42.23.”).

* Create _Work In Progress [WIP]_ pull requests only if you need clarification or an explicit review before you can continue your work item.

* If your patch is not getting reviewed or you need a specific person to review it, you can @-reply a reviewer asking for a review in the pull request or a comment, or you can ask for a review by contacting us via [email](mailto:moodle-dl@ist-ein-knaller.de).

* Post review:
  * If a review requires you to change your commit(s), please test the changes again.
  * Amend the affected commit(s) and force push onto your branch.
  * Set respective comments in your GitHub review to resolved.
  * Create a general PR comment to notify the reviewers that your amendments are ready for another round of review.

## Issues and Planning

* We use GitHub issues to track bugs and enhancement requests.

* Please provide as much context as possible when you open an issue. The information you provide must be comprehensive enough to reproduce that issue for the assignee. Therefore, contributors should use but aren't restricted to the issue template provided by the project maintainers.

* When creating an issue, try using one of our issue templates which already contain some guidelines on which content is expected to process the issue most efficiently. If no template applies, you can of course also create an issue from scratch.

* Please apply one or more applicable [labels](https://github.com/C0D3D3V/Moodle-Downloader-2/labels) to your issue so that all community members are able to cluster the issues better.
