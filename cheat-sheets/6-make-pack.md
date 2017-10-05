# Create a Pack File

First, let's take a look at how many objects are in our repository:

```
git count-objects -H
```

Now let's pack it up:

```
git gc
```

Let's look again at the objects in our repository:

```
git count-objects -H
OR
git count-objects -v -H
```
