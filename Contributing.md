
## ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a Fork of the [**PetMe**](https://github.com/akshitagupta15june/PetMe/) repository. Click on the <a href="https://github.com/akshitagupta15june/PetMe/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a>Fork symbol at the top right corner.

**2.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:

```bash
git clone https://github.com/<your-github-username>/PetMe
```

**3.** Navigate to the newly created LinkFree project directory:

```bash
cd PetMe
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/Susmita-Dey/PetMe.git
```

**5.** Create a new branch:

```bash
git checkout -b YourBranchName
```

**6.** Sync your fork or your local repository with the origin repository:

- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"

### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.

**8.** Stage your changes and commit:

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

```bash
git add public
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!


