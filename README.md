# GITHUB LESSON

In this lesson we will learn:

## :telescope: Planning

Use Github projects or trello (recommended).

## :herb: GIT cheasheet

### Branches

- pulling new code (`git pull origin main` - every time new code has been merged and every start of the day)
- solving conflicts (after pulling you might have to solve conflicts. look for all red files to see which one is broken)
- creating new branches (`git checkout -b <branch name>`)
- moving between branches (`git checkout <branch name>`)

### Commiting

- before we can commit, we need to stage the files
- to do that, we write `git add .` (git add all) or `git add <path to file>` if we want to stage specific ones
- then we check that we stage the correct ones (`git status`)
- if we made a mistake we can unstage (`git reset .` - "git reset all" or `git reset <path to file>` for specific ones)
- once all files are correct we shoudl commit `git commit -m"<message>"`

The commit message should follow conventions to make it easier to trace:

```
git commit -m"COMMAND[SCOPE - optional]: MESSAGE"
```

Main commands are

- Fix (any fix that affect what the user sees)
- Feat (new feature or part of it)
- Refactor (any fix or update that does not affect the user)

```
git commit -m"fix[home page]: link to about page works"
git commit -m"feat[about page]: added new content about me"
git commit -m"refactor[calendar]: calendar is split into smaller files"
```

### Pushing

pushing code

- `git push -u origin <branch name>` for the first time to create a new branch remotely
- `git push` every time after that)

## :memo: Pull request

### Creating a pull request

After pushing a new branch, you will have a notification for creating a new pull request.

- create a pull request
- title should follow the same commit convention
- a description (optional: add a change log and list all changes to make it easier to read)
- add a reviewer
- asign yourself
- let the reviewer know via Slack that their review is needed!

### Reviewing a pull requests

- go to "Files changed"
- review all changes and comment on the if needed
- when finished with the review, go to "review changes" green button
- either choose approve or request changes
- if changes are needed, inform the assignee
- if changes are not needed, merge it! :tada:

:warning: Update all team members that a new change has been merged so everybody can pull the new changes.

## :fork_and_knife: Fork

Once this project is finished, fork it so it will appear on your own Github profile.

## :package: External packages

> Don't re-invent the wheel

_wise teacher_

Other developer all ready wrote so much good code and it's free!

We should not write everything on our own by try to use external libraries to do complex things.

This will allow us to concentrate on the most important thing - combine those amazing tools together and create real value for other people.

You search by using the word "npm":

```
Search: rich text editor react npm
```

We should write "React" so we will find libraries that were already implemeneted in React for us. This is not mandatory and does not alway exist but it can be so useful!

---

### Enjoy coding :tada:
