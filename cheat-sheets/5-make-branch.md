# Attach the Commit to a Branch

Git isn't truly happy until our commit is attached to a branch:

```
git update-ref refs/heads/master <commit-SHA>
```

Let's inspect it:

```
cat .git/refs/heads/master
```
