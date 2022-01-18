# zemoso-training


**1)There are 5 Branches- main(default contains readme), Master , Torvalds , New Branch, req.**

**2)The master branch consists of the txt file uploaded through local repository.**

**3)the Torvalds branch consists of txt file where  torvalds String is replaced  with my name.**


**4)the new Branch consists of the txt file where all "to " are replaced with my name.**

**5) req branch was constructed to pull request and merge**
```
#helps in creating the repo folder

mkdir repo

#choosing the repo folder name
cd repo

#to initialize
git init
```

**To Commit**
```
#first we need to add
git add hello_world.txt
git commit -m "First Commit"
git remote add origin https://(URl of repository you want to use )
git pull origin master
git push origin master

```
```git commit``` to save the changes to the local repository.

```git remote``` to add our remote repository location as origin(branch) which is used to refer our remote repository.

```git pull```  to keep our master branch up to date.

```git push```  to push the committted contents from our local repository to remote repository.

**To Replace "to" with myname**

```
sed -i 's/to/MyName/g' hello_world.txt
this command replace all "to" words with myname

```
```
git diff
whether the words are replaced 

```

```
git add hello_world.txt
git commit -m "new Commit" 
git push origin master

```

**Revert Back**
``` 
git revert HEAD
```

**To create new Branch**
```
git checkout -b new_branch
git checkout -b Torvalds
```

**To Merge**
```
git checkout
git merge new_branch
```

**To Clone the repo**
```
 mkdir clone_repo
 cd clone_repo
 git init
 git clone url(Repo link)

```


