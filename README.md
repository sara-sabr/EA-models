## In a nutshell

Here are the recommended ways (tool-agnostic!) to contribute to this repo:

* use [branches](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) when making changes. These are required to initiative pull requsts
* always create a pull request to propose changes to the remote repository (GitHub), even if the assignee is yourself;
* do not alter the model directory manually, it's operated by the coArchi plugin and any manual alteration would most likely break it.
  
## In a nutbasket

The toolbox we use:

* [GitHub Desktop](https://desktop.github.com). See [here](https://youtu.be/S7f8qJscmRE) for a quick video
  * _Note_: If you're only doing modeling using Archi, you do not need GitHub desktop
* [Archi](https://www.archimatetool.com/download/) &nbsp; the [coArchi plugin](https://www.archimatetool.com/plugins/#coArchi). See [here](https://youtu.be/Ht1Bf7VXfkk) for an intro video.
  * _Note_: For Windows users, the most convenient Archi installation would be the portable ZIP (make sure you download the correct architecture, e.g. x64). The screenshot below shows proven to work versions of Archi (4.6.0) and coArchi (0.5.4.202002281020).
  
  ![Archi and coArchi versions](/Documents/Services/Projects/ESDC-EA-SAS/archi_version.png)
  
* Atom: TBD

## How to contribute (procedures and guidelines)

### Archi modeling

Using Archi with its [coArchi plugin](https://www.archimatetool.com/plugins/#coArchi) handles the git distributed repository in the background for you.
The [Archi coArchi plugin GitHub repository](https://github.com/archimatetool/archi-modelrepository-plugin/wiki/Understand-the-Basics) provides further details.

You will **still need** to understand the [concepts of a distributed version control system](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction) to know how to collaborate, in particular how [branching works](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell).

**TL;DR** Multiple contributors to an Archi model do not work on the same model at once. They work on local copies they have on their PC and, when one is ready, pushes (publishes) their local copy to the remote server (the GitHub repository). When pushing to the remote server to communicate their intent to the rest of the team, they do so by initiating a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). You initiative a Pull Request by [creating a branche](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) and requesting that branch to be merged with another (most likely the master branch)

[See here procedures and guidelines for contributing to Archi models](procedures_archi.md)

### General repository contributions

to come...
