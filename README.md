git-config
==========

My git config files with a bunch of aliases

## Import

You can import the config file in your .gitconfig file like this :

```bash
[include]
    path = git-config/.gitconfig
```

In this way you can keep your git folder.

# git-bash

To import prompt improvement:

```bash
# in your .bashrc file
if [ -f "$HOME/git-config/.bash_git" ]; then
 . "$HOME/git-config/.bash_git"
fi
```
