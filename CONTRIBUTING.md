# Contributing to ASNeG

The following is a set of guidelines for contributing to ASNeG's projects,
which are hosted in the [ASNeG Organization](https://github.com/ASNeG) on GitHub. 
These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.


#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Feature Request](#feature-request)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)
  
[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [Changelog Styleguide](#changelog-styleguide)
    
 
## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, 
you are expected to uphold this code. Please report unacceptable behavior to [info@asneg.de](mailto:info@asneg.de).

## How Can I Contribute?

### Reporting Bugs

When you are creating a bug report, fill out [the required template](.github/ISSUE_TEMPLATE/bug_report.md), 
the information it asks for helps us resolve issues faster.

### Feature Request

Before creating enhancement suggestions, please fill in [the template](.github/ISSUE_TEMPLATE/feature_request.md), 
including the steps that you imagine you would take if the feature you're requesting existed.

### Your First Code Contribution

If you'd like to help us but don't know how to start, look through `good first issue` issues.

### Pull Requests

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](.github/PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing 
<details><summary>What if the status checks are failing?</summary>
If a status check is failing, and you believe that the failure is unrelated to your change, 
please leave a comment on the pull request explaining why you believe the failure is unrelated. 
A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, 
then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, 
the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request 
can be ultimately accepted.

## Styleguides

### Git Commit Messages

* Start with lower case ("fix something" not "Fix something")
* Use the present tense ("add feature" not "added feature")
* Use the imperative mood ("move cursor to..." not "moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title

### Changelog Styleguide

All bug-fixes, new features and significant changes in the documentation must be recorded in CHANGELOG.rst file.
There are 3 categories of the records:

* Features
* Bugs
* Documentation

Every record should:

* Use ReST format
* Start with lower case ("fix something" not "Fix something")
* Use the present tense ("add feature" not "added feature")
* Use the imperative mood ("move cursor to..." not "moves cursor to...")
* Have number of related issue or PR
* Ended with `, by @author1, @author2`

Example:

`* fix error "Unexpected SequenceNumber" #57, by @author1`
