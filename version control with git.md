### git log
Displaying informations about existing commits
```shell
   $ git log
```
### git show
Displays information about given commits
```shell
   $ git show
```
![]{/assets/pics/git-log.png}

```shell
git log --oneline
```
The git log command has a flag that can be used to alter how it displays the repositorys information.
That flag is --oneline:

```shell
git log --stat
```
The git log command has a flag that can be used to display the files that have been changed in the commit,
as well as the number of lines that have been added or deleted.
The flag is --stat ("stat" is short for "statistics"):

```shell
git log -p
```
The git log command has a flag that can be used to display the actual changes made to a file.
The flag is --patch which can be shortened to just -p:
