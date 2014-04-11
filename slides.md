# git tips

!SLIDE

![logo](https://raw.githubusercontent.com/alexfish/git-tips/master/images/logo.png)

# git tips

!SLIDE

## Branched from the wrong branch?

``` 
git rebase —onto foo bar 
```

![onto](https://raw.githubusercontent.com/alexfish/git-tips/master/images/onto.gif)

!SLIDE

## Forgot to add something to a commit?

``` 
git commit —amend -c foobar
```

![ammend](https://raw.githubusercontent.com/alexfish/git-tips/master/images/ammend.gif)

!SLIDE

## Want to switch back to the previous branch?

``` 
git checkout -
```

![checkout](https://raw.githubusercontent.com/alexfish/git-tips/master/images/checkout.gif)

!SLIDE

## Want to stage some changes?

``` 
git add -p
```

![add](https://raw.githubusercontent.com/alexfish/git-tips/master/images/add.gif)

!SLIDE

## Want to set upstream?

``` 
git push -u origin foobar
```

![push](https://raw.githubusercontent.com/alexfish/git-tips/master/images/push.gif)

!SLIDE

## Want to push nothing?

``` 
git commit —allow-empty -m "foobar"
```

![empty](https://raw.githubusercontent.com/alexfish/git-tips/master/images/empty.gif)

!SLIDE

## Want to find out which branch has a commit?

``` 
git branch --contains foobar
```

![contains](https://raw.githubusercontent.com/alexfish/git-tips/master/images/contains.gif)

!SLIDE

## Want to speed things up?

``` 
git gc
```

![gc](https://raw.githubusercontent.com/alexfish/git-tips/master/images/gc.gif)

!SLIDE

## Want to undo bad things?

``` 
git reflog
```

![reflog](https://raw.githubusercontent.com/alexfish/git-tips/master/images/reflog.gif)

!SLIDE

## Want to find out when things broke?

``` 
git bisect start foo bar
```

![bisect](https://raw.githubusercontent.com/alexfish/git-tips/master/images/bisect.gif)

!SLIDE

## Want to squash/delete commits?

``` 
git rebase -i foobar
```

![rebase](https://raw.githubusercontent.com/alexfish/git-tips/master/images/rebase.gif)

!SLIDE

## Want to always pull with rebase?

``` 
git config --global branch.autosetuprebase always
```

!SLIDE

## Want git to be case sensative?

``` 
git config --global core.ignorecase false 
```

!SLIDE

## Love typos?

``` 
git config --global help.autocorrect 1
```

!SLIDE

## Like color?

``` 
git config —global color.ui 1
```

!SLIDE

## Same conflicts?

``` 
git config --global rerere.enabled true
```



