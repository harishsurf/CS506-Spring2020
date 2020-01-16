# A collaborative exercise to learn Python and Git

## Objective

Build a city! The city will be printed out to the terminal (use python's `print()` function for this) and will have the following components:

- School
- Library
- Museum
- Fire Station
- Police Station
- Restaurant
- Market
- Park
- Lake
- Roads
- Hospital
- Gym
- Power Plant
- Mall
- Trees

Each team will be responsible for coding one component of the city. Each component is a member of a quarter. The quarters of the city are the following:

- Education
- Leisure
- Outdoors
- Safety
- Infrastructure

Once a team has coded their component they will open a Pull Request against this repository. Once all teams in a quarter have submitted their code, they will receive requirements for designing each quarter. **Beware** this may change the implementation of each component and cross team collaboration will be needed in order to support each other's implementation changes! Teams will then submit their code in the form of a Pull Request to this repository. We will then merge the PRs and print our city!

## Running the code

    $ python3 city.py

## Helpful Resources

- [Getting Started with Python](https://www.python.org/about/gettingstarted/)
- [Getting Started with Git](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html)

## Contributing Basics

To contribute to a repository on GitHub, you'll want to first [Fork](https://help.github.com/en/articles/fork-a-repo) the repository. You can then [Clone](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html#clone-a-repository) that fork locally to start making changes. Make sure to [add a remote](https://help.github.com/en/articles/adding-a-remote) pointing to the repo you forked. Typically this remote is named `upstream`. To add changes to your fork you must first [create](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html#create-a-new-branch) and checkout a branch named after the component you are working on. Then [add](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line) and [commit](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line) your changes. You can then [Push](https://help.github.com/en/articles/pushing-commits-to-a-remote-repository) these changes to your fork on github and [create a Pull Request](https://help.github.com/en/articles/creating-a-pull-request) against the forked repository.

### Step by step checklist

- [ ] [Fork](https://help.github.com/en/articles/fork-a-repo) this repository
- [ ] [Clone](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html#clone-a-repository) **your fork** locally
- [ ] [Add a remote](https://help.github.com/en/articles/adding-a-remote) called `upstream` pointing to this repo (`https://github.com/gallettilance/CS506-Spring2020` or `git@github.com:gallettilance/CS506-Spring2020.git`)
- [ ] [Create](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html#create-a-new-branch) and checkout a branch named after the component you are working on
- [ ] Implement your component by editing the relevant file(s)
- [ ] [Add](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line) and [Commit](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line) your changes
- [ ] [Push](https://help.github.com/en/articles/pushing-commits-to-a-remote-repository) these changes to your fork on github
- [ ] [Create a Pull Request](https://help.github.com/en/articles/creating-a-pull-request) against this repository.

### Addressing Feedback

Once you have created a PR, we will review it and submit feedback. This feedback must be addressed in order for the PR to be merged. In order to address feedback:

- [ ] Locally edit the relevant files on the same branch that you used to create your PR
- [ ] [Add](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line) your changes
- [ ] [Amend your commit](https://help.github.com/en/github/committing-changes-to-your-project/changing-a-commit-message)
- [ ] [Force Push](https://help.github.com/en/github/committing-changes-to-your-project/changing-a-commit-message#amending-older-or-multiple-commit-messages) these changes to your fork on github
- [ ] These changes should now be reflected in the PR
