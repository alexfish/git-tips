git-tips
========

![logo](https://raw.githubusercontent.com/alexfish/git-tips/master/images/logo.png)

Some quick git tips: [Slides Here](http://alexfish.github.io/git-tips)


## Branched from the wrong branch?

``` 
git rebase —onto foo bar 
```

![onto](https://raw.githubusercontent.com/alexfish/git-tips/master/images/onto.gif)

## Forgot to add something to a commit?

``` 
git commit —amend -c foobar
```

![ammend](https://raw.githubusercontent.com/alexfish/git-tips/master/images/ammend.gif)

## Want to switch back to the previous branch?

``` 
git checkout -
```

![checkout](https://raw.githubusercontent.com/alexfish/git-tips/master/images/checkout.gif)

## Want to stage some changes?

``` 
git add -p
```

![add](https://raw.githubusercontent.com/alexfish/git-tips/master/images/add.gif)

## Want to set upstream?

``` 
git push -u origin foobar
```

![push](https://raw.githubusercontent.com/alexfish/git-tips/master/images/push.gif)

## Want to push nothing?

``` 
git commit —allow-empty -m "foobar"
```

![empty](https://raw.githubusercontent.com/alexfish/git-tips/master/images/empty.gif)

## Want to find out which branch has a commit?

``` 
git branch --contains foobar
```

![contains](https://raw.githubusercontent.com/alexfish/git-tips/master/images/contains.gif)

## Want to speed things up?

``` 
git gc
```

![gc](https://raw.githubusercontent.com/alexfish/git-tips/master/images/gc.gif)

## Want to undo bad things?

``` 
git reflog
```

![reflog](https://raw.githubusercontent.com/alexfish/git-tips/master/images/reflog.gif)

## Want to find out when things broke?

``` 
git bisect start foo bar
```

![bisect](https://raw.githubusercontent.com/alexfish/git-tips/master/images/bisect.gif)

## Want to squash/delete commits?

``` 
git rebase -i foobar
```

![rebase](https://raw.githubusercontent.com/alexfish/git-tips/master/images/rebase.gif)

## Want to always pull with rebase?

``` 
git config --global branch.autosetuprebase always
```

## Want git to be case sensitive?

``` 
git config --global core.ignorecase false 
```

## Love typos?

``` 
git config --global help.autocorrect 1
```

## Like color?

``` 
git config --global color.ui 1
```

## Same conflicts?

``` 
git config --global rerere.enabled true
```



