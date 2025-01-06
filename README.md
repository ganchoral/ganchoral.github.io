# Gananoque Choral Society website

## Cheatsheet

### Cloning the repository from github

Open a terminal in the parent directory that you would like to clone the respository to.

Run:

```
git clone https://github.com/ganchoral/ganchoral.github.io.git
```

Then use cd to change to the new directory you just created:

```
cd ganchoral.github.io
```

### Pulling changes from github

To fetch any new changes that exist on github but not in your local repository, run:

```
git pull
```

### Committing and pushing changes

Start by making your changes to the files in the local repository.

(Optional) At this point you can get an overview of what files have changed by running `git status`, and you can see a
more detailed line-by-line description of the changes by running `git diff`.

When you're happy with your changes, stage them for commit:

```
git add --all
```

Commit them:

```
git commit -m "A short description of the changes"
```

And finally push the changes to github:

```
git push
```
