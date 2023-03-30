# Compare forked repository w.r.t. original repository 

To check the difference between your forked repository and the original one, you can follow these steps:

### 1. Clone your forked repository to your local machine using the `git clone` command. 

```
git clone https://github.com/yourusername/yourforkedrepo.git
cd yourforkedrepo/
```

### 2. Add the original repository as a remote using the `git remote add` command.

```
git remote add upstream https://github.com/originaluser/originalrepo.git
```

### 3. Fetch the latest changes from the original repository using the `git fetch` command.

```
git fetch upstream
```

### 4. Check out your local branch that you want to compare to the original repository using the `git checkout` command.

```
git checkout yourRepoBranch
```

### 5. Compare your local branch with the specific branch of the original repository that you want to compare with, using the `git diff` command. 

```
git diff upstream/originalRepoBranch
```
