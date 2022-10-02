## 📝 Contribution Guidelines

- Fork this repo (button on top) _(Mandatory)_
- Clone this on your local machine _(Mandatory)_

```
git clone https://github.com/Sanchitbajaj02/Hacktoberfest-2022-firstPush
```

- Navigate to project directory.

```
cd Hacktoberfest-2022-firstPush
```

- Create a new Branch

```
git checkout -b my-new-branch
```

- Add your contribution

```
git add .
```

- Commit your changes.

```markdown
git commit -m "Relevant message"
```

- Then push

```
git push origin my-new-branch
```

- Create a new pull request from your forked repository

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.

```terminal
git remote add upstream https://github.com/Sanchitbajaj02/Hacktoberfest-2022-firstPush
```

You can verify that the new remote has been added by typing

```terminal
git remote -v
```

To pull any new changes from your parent repo simply run

```terminal
git merge upstream/master
```
