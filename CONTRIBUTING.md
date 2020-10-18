# How to Contribute :
- Fork the repository to your own GitHub account.

- Clone the repository to your local machine

```
$ git clone "https://github.com/{username}/Gamers-Console.git"
$ cd Gamers-Console
```
where username is your GitHub account username.

- Create a branch where you can do your local work.
```
$ git branch {branchname}
$ git checkout branchname
```
- Do your work and stage your changes.
```
$ git add <filename>   //for adding particular files to the staging area
$ git add .           //for adding all the files to the staging area
```
- Commit you changes with a commit message containing your name, file(s) worked upon, changes added.
```
$ git commit -m "commit message"
```
- Push changes to your forked repository
```
$ git push -u origin branchname
```
- Create a pull request to the upstream repository.
