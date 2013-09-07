#Notes on Learning Git

## Useful yet Un-frequently-used Commends 
After using Git for a while, I found I need to take extra effort to remember some useful yet un-frequently-used commends. I list here for reference:

```
git diff HEAD
git diff --staged
git add -i
git log branchA ^master
git checkout
git checkout -- filename.
git reset --hard origin/master
git reset filename.txt
```

## [Force git to overwrite local files on pull](http://stackoverflow.com/questions/1125968/force-git-to-overwrite-local-files-on-pull)
```
git fetch --all
git reset --hard origin/master
```

##Great entry level tutorials
While I was learning and using git, I found the following tutorials are great and worth reading several times.

1. [Git - The Simple Guide](http://rogerdudler.github.io/git-guide/)
2. [Try Git from Code School & Github](http://try.github.io/)
3. [Git Immersion](http://gitimmersion.com/)

## Tutorial on Git Internals

1. [Think Like (a) Git](http://think-like-a-git.net/)
2. [A Visual Git Reference](http://marklodato.github.io/visual-git-guide/index-en.html)
3. [Git Internals PDF](https://peepcode.com/products/git-internals-pdf)
4. [Understanding Git Conceptually](http://www.sbf5.com/~cduan/technical/git/)
