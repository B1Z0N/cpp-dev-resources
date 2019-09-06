# Contribution Guidelines

``YOU SHOULD ADD TOOLS/C++ RESOURCES SUCH THAT YOU HAVE PERSONAL EXPERIENCE WITH``

## Contents

* [Getting started](#getting-started)
* [Opening an issue](#issues)
* [Opening a pull request](#opening-a-pull-request)
* [Code of conduct](#code-of-conduct)

## Getting started

* Start by exploring the repository. Take a look at how resources lists are written and each individual tool is.
  
* Before beginning your contribution, [create an issue][issue-guide]. In your issue's 
  description, please describe the addition or change you wish to make. This helps us guide 
  your contribution, and it lets others know what you're working on.

* [Fork][fork-guide] the repo, clone your fork, and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/cpp-dev-res.git
   # Navigate to the newly cloned directory
   cd cpp-dev-res
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/B1Z0N/cpp-dev-res.git
   ```

* If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

* Create a new branch (from the `master` branch) to contain your code for a
   specific algorithm or data structure:

   ```bash
   git checkout -b <branch-name>
   ```

## Opening an issue

You should do this mostly in two main cases:

1. If you disagree with some subjective thoughts written in this repo, feel free to open an issue.
We always opened to suggestions. 
1. If you want to open a pull request, be sure to open an issue first. This way you let others know
what you are working on. You should ignore this, only in rare cases, if it is a pull request of obvious
fixes.

Here is an [issue guide](issue-guide)

## Opening a pull request

Follow these steps when you're ready to submit your code:

1. Locally merge (or rebase) the upstream development branch into your branch:

   ```bash
   git pull [--rebase] upstream master
   ```

1. Push your branch up to your fork:

   ```bash
   git push origin <branch-name>
   ```

1. [Open a pull request][pr-guide] with a clear title and description against the
   `master` branch. Your pull request should reference the same issue you created 
   above.

1. Once your pull request has been opened, we'll review it and go from there. :smile:

## Code of Conduct

This project has a [Code of Conduct](CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

[fork-guide]: https://help.github.com/fork-a-repo/
[rebase-guide]: https://help.github.com/articles/interactive-rebase
[pr-guide]: https://help.github.com/articles/about-pull-requests/
[issue-guide]: https://help.github.com/en/articles/about-issues