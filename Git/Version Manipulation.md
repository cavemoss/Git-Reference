```html
HEAD / master
<!-- HEAD detached -->
git Branching <!-- idea of branching out lines of commits
```
> `../project>` <br> Version Manipulation

`git checkout <commit_hash>` *view a previous version (branching warning)*

<br>

`git reset --hard HEAD^` *Delete previous commit* <br>
&#8195;&emsp;`git reset --hard HEAD~<number>` *Delete multiple previous commits*

<br>

`git branch <branch_name>` *Create branch originating from the current branch* <br>
&#8195;&emsp;`git branch <branch_name> <commit_hash>` *Brunch out of a certain commit* <br>
&#8195;&emsp;`git branch -m <old_name> <new_name>` *Rename branch* <br>
&#8195;&emsp;`git branch -d <branch_name>` *Delete branch*

<br>

`git checkout <commit_hash> <file>` *Restore a previous version of a file* <br>
&#8195;&emsp;`git checkout <commit_hash> .` *Completely restore a previous version* 

<br>

`git merge <branch_name>` *merge another brunch into the current brunch*
