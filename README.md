[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/rahulkarda/100Devs-Members)
[<img align="right" width="150" src="https://img.shields.io/badge/%3CJoin Us on Discord%3E-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white">](https://discord.com/invite/zNxhjnmDPy)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Contributors](https://img.shields.io/github/contributors/rahulkarda/100Devs-Members?color=green&label=Contributors&style=flat)](https://github.com/rahulkarda/100Devs-Members/graphs/contributors)



# 100Devs-Members
🚀✨ Help 100Devs Members to get started with open source contributions.

This project aims to simplify and guide 100Devs members the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below. 

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<!-- <img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" /> -->

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<!-- <img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" /> -->

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<!-- <img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" /> -->

For example:

```
git clone https://github.com/this-is-you/100Devs-Members.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd 100Devs-Members
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-your-name
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Add your name to the section that matches your Initial in the list and save your changes.

<!-- <img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" /> -->

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<!-- <img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" /> -->

Now submit the pull request.

<!-- <img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" /> -->

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Anatomy of an open source project:

Every open source community is different.

Spending years on one open source project means you’ve gotten to know _one_ open source project. Move to a different project, and you might find the vocabulary, norms, and communication styles are completely different.

That said, many open source projects follow a similar organizational structure. Understanding the different community roles and overall process will help you get quickly oriented to any new project.

A typical open source project has the following types of people:

**Author**: The person/s or organization that created the project.

**Owner**: The person/s who has administrative ownership over the organization or repository (not always the same as the original author).

**Maintainers**: Contributors who are responsible for driving the vision and managing the organizational aspects of the project (may also be authors or owners of the project).

**Contributors**: Everyone who has contributed something back to the project.

**Community Members**: People who use the project. They might be active in conversations or express their opinion on the project’s direction.

Bigger projects may also have subcommittees or working groups focused on different tasks, such as tooling, triage, community moderation, and event organizing. Look on a project’s website for a “team” page, or in the repository for governance documentation, to find this information.

A project also has documentation. These files are usually listed in the top level of a repository.

**LICENSE**: By definition, every open source project must have an open source license. If the project does not have a license, it is not open source.

**README**: The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.

**CONTRIBUTING**: Whereas READMEs help people use the project, contributing docs help people contribute to the project. It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.

**CODE_OF_CONDUCT**: The code of conduct sets ground rules for participants’ behavior and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.

**Other documentation**: There might be additional documentation, such as tutorials, walkthroughs, or governance policies, especially on bigger projects.

Finally, open source projects use the following tools to organize discussion. Reading through the archives will give you a good picture of how the community thinks and works.

**Issue tracker**: Where people discuss issues related to the project.

**Pull requests**: Where people discuss and review changes that are in progress.

**Discussion forums or mailing lists**: Some projects may use these channels for conversational topics (for example, “How do I…“ or “What do you think about…“ instead of bug reports or feature requests). Others use the issue tracker for all conversations.

## How can I fix a merge conflict?

A GitHub conflict is when people make changes to the same area or line in a file. This must be fixed before it is merged in order to prevent collision in the main branch.

- **To read more about this, go to [GitHub Docs - About Merge Conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)**

- **To find out about how to fix a Git Conflict, go to [GitHub Docs - Resolve Merge Conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)**


## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

## [Additional material](additional-material/git_workflow_scenarios/additional-material.md)

## References 
1. [First Contributions](https://firstcontributions.github.io/)
2. [Zero To Mastery](https://github.com/zero-to-mastery/start-here-guidelines)
3. [Eddie Hub](https://github.com/EddieHubCommunity/hacktoberfest-practice)
