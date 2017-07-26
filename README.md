# new_project_example
This is a new project example

### Create a new project on Git Server
Below is an example for creating a new project on git server
1. make a new folder
```
mkdir new_project_example
```
2. change to new folder
```
cd new_project_example
111
3. initialize new repository
```
git init --bare
```

### Start a new project on Developer(your PC)
Below are stpes to start a new git repository.
. Create a directory for your new_project
```
mkdir new_project_example
cd new_project_example
```
. Initialize new_project_example. Type
```
git init
```
. Add your file/documents...
for example:
```
touch Readme.md
```
. Add the files
```
git add .
```
. Commit your files
```
git commit -am "Initial Commit, Adding a Readme.md"
```
. Checking new_project status
```
git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```

### Connect it ot GitServer/GitHub
ex: Push your new_project_example to GitHub
. Goto to [GitHub](https://github.com)
. Config your git config
```
git config --global user.name "your name"
git config --global user.email "your email"
```
. Create a new Repository   
. Set your remote repo
```
git remote add origin https://github.com/dexterlu/new_project_example
```
. Push your code
```
git push origin master
```

