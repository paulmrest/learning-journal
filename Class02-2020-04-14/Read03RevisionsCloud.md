# An Introduction to Git

As most software projects involve many developers working on different parts of the code base at different times, it is important to be able to manage these distributed changes whether within a single department in an organization, or across the globe.

**Git** is a solution to this management. Developed in 2005 for [open source](https://opensource.com/resources/what-open-source) software, [Git](https://en.wikipedia.org/wiki/Git) offers a number of capabilities for managing software projects:

* Version control - as software is modified, whether for fixing bugs, adding features, or tweaking performance, there can be many versions of that software. Changes within any one version need to be confined to that version. Furthermore, any changes to that version need to be coordinated with other changes made to the same version.
* Code management - allowing developers to try new things without worrying about breaking the production version is essential for creativity and exploring. Code management with Git allows developers to make changes to a development **branch** which only a subset of the developers will have access to. Only once a **Project Manager** (PM) or **Product Owner** (PO) confirms all the code in a development branch to be good will it be merged with a higher branch.
* Distributed access - Git allows for, potentially, anyone to access a given software project and make changes to it. It is only once a PM/PO determines that the new code is a worthy contribution that it is added to the project.
* Backup - if a developer makes a huge mistake, or simply gets lost in their own changes, they can "reset" at any time by **pulling** the last committed changes from the Git's **repository**.

A simple life-cycle sketch for using a Git is:

1. Clone Git repository to local machine.
1. Make changes to files on local machine.
1. Add-Commit-Push the changes back to the repository

Git requires some setup to get working on a given system, and requires some working knowledge of your computer's command line interface, but with those two prerequisites in place, Git can be a powerful way to share and develop software.

[More information on Git](https://www.udemy.com/blog/git-tutorial-a-comprehensive-guide/)