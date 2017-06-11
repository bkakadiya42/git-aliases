To use this aliases:
- Put the `.bash_git_aliases` file in your home directory
- Load it from `~/.bashrc` using following snippet:
  ```
  if [ -f $HOME/.bash_git_aliases ]; then
    source $HOME/.bash_git_aliases
  fi
  ```

As usual with this kind of stuff, there's no guarantee that they do what you want, and use it only after understanding what it actually does.

Everything is licensed under the MIT license. Bug reports and pull requests are welcome.
