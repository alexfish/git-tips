# git tips

!SLIDE

# git tips

!SLIDE

## Branched from the wrong branch?

``` 
git rebase —onto foo bar 
```

!SLIDE

## Forgot to add something to a commit?

``` 
git commit —amend -c foobar
```

!SLIDE

## Want to switch back to the previous branch?

``` 
git checkout -
```

!SLIDE

## Want to stage some changes?

``` 
git add -p
```

!SLIDE

## Want to set upstream?

``` 
git push -u origin foobar
```

!SLIDE

## Want to push nothing?

``` 
git commit —allow-empty -m "foobar"
```

!SLIDE

## Want to find out which branch has a commit?

``` 
git branch --contains foobar
```

!SLIDE

## Want to speed things up?

``` 
git gc
```

!SLIDE

## Want to undo bad things?

``` 
git reflog
```

!SLIDE

## Want to find out when things broke?

``` 
git bisect start foo bar
```

!SLIDE

## Want to squash/delete commits?

``` 
git rebase -i foobar
```

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



