# Git Assignment - msugar

a. What is an issue?

	Use GitHub Issues to track ideas, feedback, tasks, or bugs for work on GitHub.

	GitHub Issues are items you can create in a repository to plan, discuss and track work.

	Issues are simple to create and flexible to suit a variety of scenarios. You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

	Source: [About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)


b. What is a pull request?

	A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase. Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.

	Source: [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)


c. How do I open up a pull request?

	You can create pull requests on GitHub.com by using a Web browser.

	If you want to create a new branch for your pull request and do not have write permissions to the repository, you can fork the repository first.

	You can specify which branch you'd like to merge your changes into when you create your pull request. Pull requests can only be opened between two branches that are different. When thinking about branches, remember that the base branch is *where* changes should be applied, the head branch contains *what* you would like to be applied.

	Steps:
	1. On GitHub.com, navigate to the main page of the repository.
	1. In the "Branch" menu, choose the branch that contains your commits.
	1. Above the list of files, in the yellow banner, click Compare & pull request to create a pull request for the associated branch.
	1. Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.
	1. Type a title and description for your pull request.
	1. To create a pull request that is ready for review, click Create Pull Request. To create a draft pull request, use the drop-down and select Create Draft Pull Request, then click Draft Pull Request. If you are the member of an organization, you may need to request access to draft pull requests from an organization owner. 

	Source:[Creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request?tool=webui) 


d. Give me a step by step guide on how to add someone to your repository.

	Steps:
	1. Navigate to your project.
	1. In the top-right, click to open the menu.
	1. In the menu, click Settings to access the project settings.
	1. Click Manage access.
	1. Under Invite collaborators, search for the user that you want to invite.
	1. Select the role for the collaborator. ...
	1. Click Invite.

	Source: [Managing access to your projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/managing-access-to-your-projects)

e. What is the difference between git and GitHub?

	Git is an open-source version control system that intelligently tracks changes in files. Git is particularly useful when you and a group of people are all making changes to the same files at the same time.

	GitHub is a cloud-based platform where you can store, share, and work together with others to write code. Collaborative working, one of GitHub’s fundamental features, is made possible by the open-source software, Git, upon which GitHub is built.

	Source: [About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git)


f. What does git diff do?

	It show changes between the working tree and the index or a tree, changes between the index and a tree, changes between two trees, changes resulting from a merge, changes between two blob objects, or changes between two files on disk.

	Source: [git-diff](https://git-scm.com/docs/git-diff)


g. What is the main branch?

	The "master" branch in Git is not a special branch. It is exactly like any other branch. The only reason nearly every repository has one is that the `git init` command creates it by default and most people don’t bother to change it.

	In GitHub, that default name of that primary branch is "main" instead. Note the exact name doesn't matter much, it's more a matter of convention.

	Most teams might give a special meaning to the main branch, though. Morever, usual practice is to consider main as the "approved" state, or "ready to deploy into production" configuration of the software system. But again, other teams with more complex needs might adopt different approaches, for example having one branch per major release version.

	Source: [Git Branching - Branches in a Nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

	If the repository designates 'main' as the branch containing the approved or production-ready version of the software, directly modifying this branch could introduce risks. It's advisable to utilize Git and GitHub features to safeguard against unintended alterations reaching the live environment.

