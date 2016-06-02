# bootstrap101
My first repository in git :)

## My Git tips

### Cloning a repository

```
git clone REPO_URL
```

Where `REPO_URL` can be something like:
 1. `git@github.com:kellenr/bootstrap101.git` or
 1. `https://github.com/kellenr/bootstrap101.git`

### After any change
After any change, we need to follow the next steps:

 1. Pull from github to see if there is any changes.

  ```
  git pull origin master
  ```

  When there is no changes to pull and merge, the answer will be:

  ```
   . . .
   Already up-to-date.
  ```

 1. Look into the status of the repository.

  ```
  git status
  ```

 1. See the differences or changes in the files

  ```
  git diff PATH_TO_FILE
  ```

 1. Add the changes to commit

  ```
  git add PATH_TO_FILE
  git add PATH_TO_FILE2
  ```

 1. Commit the changes with a comment.

  ```
  git commit -m "describing the change"
  ```

 1. List the commits

  ```
  git log
  ```

 1. Push to github

  ```
  git push origin master
  ```
