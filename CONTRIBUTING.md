# Contributing to Labs

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

## Before you start

* `bug`:- Issues related to bugs in code which is creating some error or decreasing accuracy.
* `experiment`:- Issues related to creation/improvement of new/existing experiments. 
* `question`:- Any doubt you come across in the repository or while submitting PRs. 

## How to start

* Create issue using the issue templates provided by selecting from option after clicking new issue. This will allow us to know on what experiment you want to work and we can provide guidence/suggestion about it.
* After selecting issue template you will se some pre-written info in the description of issue fill that info. For every template the info needed may vary. If you have something more to add feel free to add in the issue.
* You can start working on the issue after you are done creating one. Please follow the contribution guidelines while writing the code.
* Comment on the issue that you plan to work on so we can assign it to you and there isn't unnecessary duplication of work.
* If you're fixing some smaller issue - please check the list of pending Pull Requests to avoid unnecessary duplication.

## How can you help

You can help in multiple ways: 
* Reproducing bugs, finding its root cause and providing fixes to that, this will be appreciated a lot (see the issues with label: `bug`)
* Sending Pull Requests for new experiment (see the issues with label: `new experiment`)
* Doing Code Reviews on the Pull Requests from the developers of this community and verifying if PRs are working correctly or not

## Pull Requests

All contributions are done through Pull Requests here on GitHub.

### Guidelines for PRs

* Submit all code changes via pull requests (PRs) rather than through a direct commit. PRs will be reviewed and potentially merged by the repo maintainers after a peer review that includes at least one maintainer.
* Make sure to add README for your code. A <a href="https://github.com/siesgstarena/labs/blob/master/README-template.md">README-template</a> has been provided for that purpose.
* **DO NOT** submit "work in progress" PRs.  A PR should only be submitted when it is considered ready for review and subsequent merging by the contributor.

## Linting

We use [nblint](https://pypi.org/project/nblint/) for ensuring Labs is nice and easy to use and work on long-term.

## Linting

We use [nblint](https://pypi.org/project/nblint/) for Notebooks and [pylint](https://pypi.org/project/pylint/) for Python source files for ensuring Labs is nice and easy to use and work on long-term.

## Coding Style Changes

### DON'T

* Send PRs for style changes. For example, do not send PRs that are focused on changing usage of ```Int32``` to ```int```.

### DO

* Send PRs for upgrading code to use newer language features as it's ok to use newer language features as part of new code that's written.

## Code Reviews

* All submissions, including submissions by project members, require review from maintainers of this repository.
* Don't worry, you will remain the owner and maintain essence of the code, we will provide suggestions on how to avoid redundancy and doing structuring of code which adher to certain guidelines of this repository.
* We use GitHub pull requests (PRs) for this purpose. Consult [GitHub Help](https://help.github.com) for learning about PR.
