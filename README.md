```
Tell me how to remove them locally and remotly

Locally:
git rm README.md
git commit -m "Remove README.md file"
git status
git log


Remotely:
git rm README.md
git commit -m "Remove README.md file"
git push origin main
git fetch origin
git log origin/main

````

```
tell me how to list tags locally

git tag

```


```
tell me how to delete tag locally and remotely.

locally:
git tag -d v1.4
git push origin --delete v1.4

Remotely:
git push --delete origin v1.4
git push --delete origin v1.4

```


```
What is git rebase? Give me an example.
git rebase is a Git command used to integrate changes from one branch into another
example:
git checkout main
git pull origin main
git rebase feature_branch

```
![Alt Text](D:\ITI\Course Git\Day2\git_lab2\11.jpg)
