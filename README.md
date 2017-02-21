# git-cpr
*help out a pr*

`git cpr` checks out a pr locally so you can help it out or work on it.
It works for github prs like the
[instructions](https://help.github.com/articles/checking-out-pull-requests-locally/) say

## INSTALL
1. make a ~/bin directory if it doesn't already exist
  `mkdir ~/bin`
1. add ~/bin to your PATH in your .bashrc / .zshrc / ... if it's not
   already there
   `export PATH=~/bin:$PATH`
1. copy git-cpr to your ~/bin directory
  `cp git-cpr ~/bin`

## USAGE
`git cpr https://github.com/$user/$repo/pull/$id`

Afterwards you will have a local branch that is the same name as the
remote branch
