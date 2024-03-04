# Contributing to the CSDMS Workbench

Thank you for contributing to the [CSDMS Workbench](https://csdms.colorado.edu/wiki/Workbench), an integrated system of software tools for building, coupling, and running models.
The CSDMS Workbench consists of the following core elements: 

* [Basic Model Interface](https://bmi.readthedocs.io) (BMI)
* [Standard Names](https://standard-names.readthedocs.io)
* [Babelizer](https://babelizer.readthedocs.io)
* [Python Modeling Toolkit](https://pymt.readthedocs.io) (pymt)
* [Landlab](https://landlab.readthedocs.io)
* [Data Components](https://csdms.colorado.edu/wiki/DataComponents)

as well as several other supporting software products.

What follows is a set of guidelines for contributing to the CSDMS Workbench. Use your best judgment, and feel free to ask questions at the [CSDMS Help Desk](https://csdms.github.io/help-desk/).

### Contents

1. [Code of Conduct](#code-of-conduct)
1. [Bug Reports](#bug-reports)
1. [Feature Requests](#feature-requests)
1. [Pull Requests](#pull-requests)
1. [Credits](#credits)

## Code of Conduct

This project and everyone participating in it is governed by the CSDMS [Code of Conduct](./CODE-OF-CONDUCT.md). By participating, you are expected to uphold this code.

## Bug Reports

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/).
A great way to contribute is to send a detailed issue when you encounter a problem.

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), check that you are using the latest version of the particular CSDMS Workbench tool; if not, see if updating fixes your issue.

To submit a good bug report, explain the problem and include additional details to help the maintainers reproduce the problem.

* Use a clear and descriptive title for the issue to identify the problem.
* Describe the steps which reproduce the problem, including as many details as possible.
* Provide specific examples to demonstrate the steps. Include links to files. If you're providing code samples in the issue, use [Markdown code blocks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github#multiple-lines).
* Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior. Explain which behavior you expected to see instead and why.

Include details about your configuration and environment:

* The name and version of your operating system.
* Any details about your local setup that might be helpful in troubleshooting.

Finally, please observe the following:

* Copy/paste text for error messages instead of using screen captures. 
* Use the GitHub issue web interface for discussing issues instead of replying by email.

## Feature Requests

Feature requests are also tracked as [GitHub issues](https://guides.github.com/features/issues/).

Before [creating an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), check for existing feature requests first. If you find your feature (or one similar to it), comment on that issue. Do not open a duplicate feature request.

In your request:

* Use a clear and descriptive title for the issue to identify the feature request.
* Explain in detail how it would work.
* Be precise about the proposed outcome of the feature and how it relates to existing features. Include implementation details if possible.
* Keep the scope as narrow as possible to make it easier to implement.

## Pull Requests

[Pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) are the mechanism for making changes to a repository. 

Before making a pull request, it's best to describe the changes you wish to make with a  maintainer by [creating an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue), or by commenting on an existing issue. Because there are only a few people maintaining CSDMS projects, unsolicited pull requests may languish.

When you're ready to propose changes, [fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and create a [topic branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) to hold your changes. Then [create the pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

Some notes on the process:

* Ensure the pull request description clearly describes the problem and solution. Include any relevant issue numbers.
* Smaller is better. Submit one pull request per bug fix or feature. A pull request should contain isolated changes pertaining to a single bug fix or feature implementation. Do not refactor or reformat code that is unrelated to your change. It is better to submit many small pull requests rather than a single large one. Enormous pull requests will take enormous amounts of time to review, or may be rejected altogether.
* Coordinate bigger changes. For large and non-trivial changes, be sure to open an issue to discuss a strategy with the maintainers. Otherwise, you risk doing a lot of work for nothing!
* Prioritize understanding over cleverness. Write code clearly and concisely. Remember that source code usually gets written once and read often. Ensure the code is clear to the reader. The purpose and logic should be obvious to a reasonably skilled developer.
* Follow existing coding style and conventions. Keep your code consistent with the style, formatting, and conventions in the rest of the code base. When possible, these will be enforced with a linter and a formatter. Consistency makes it easier to review and modify in the future.
* Include unit tests. Follow existing patterns for implementing tests. Make sure new and existing tests pass.
* Promptly address any CI failures. If your pull request fails to build or pass tests, please push another commit to fix it.
* Add documentation. Document your changes with code doc comments or in existing guides.

## Credits

Please feel free to remix this document for your needs. Some of the material included here is based on or inspired by the work of others, including:

* [@numpy](https://github.com/numpy)
* [@atom](https://github.com/atom)
* [@jessesquires](https://github.com/jessesquires)
* [@mozillascience](https://github.com/mozillascience)

We thank them for their efforts to facilitate collaboration in their projects.
