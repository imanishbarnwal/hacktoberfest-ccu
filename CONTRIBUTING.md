#### If you don't have git on your machine, follow & [install it](installation.md).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/<YOUR-USERNAME>/H4B-git-github-workshop.git
```

where `<YOUR-USERNAME>` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd H4B-git-github-workshop
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-manish
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `README.md` file in a text editor, add your name, github link & feedback in the [README.md](README.md). Now, save the file.

For example:

```
- [Manish Kumar Barnwal](https://github.com/imanishbarnwal), I really enjoyed interacting with you all.
```

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add README.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Added <your-name>"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button. And submit the pull request.

And soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

**Congrats!!** You just completed the standard `fork -> clone -> edit -> pull request` workflow that you'll encounter often as a contributor!