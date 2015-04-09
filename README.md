# getsbo manual

## NAME
     getsbo - dumb Slackbuilds.org helper

## SYNOPSYS
     getsbo <package-name>

## DESCRIPTION
     getsbo is a helper script for download a Slackbuild script package from <http://www.slackbuilds.org>

     Downloaded package will be extracted to current working directory. After that you can **cd** into the directory
     and run <package-name>.SlackBuild

## EXAMPLE
     $ getsbo git

> Search result for 'git'
>
> 1. GitPython 0.3.6 (Libraries)
> 2. PyGithub 1.25.2 (Python)
> 3. cgit 0.11.2 (Development)
> 4. geogit 0.10.0 (Gis)
> 5. geogit-py 0.10 (Gis)
> 6. git-cola 2.1.0 (Development)
> 7. gitdb 0.6.4 (Libraries)
> 8. gitolite 3.6.2 (System)
> 9. hg-git 0.8.0 (Python)
> 10. libgit2 0.22.2 (Libraries)
>
> Enter a number or 0 to view next page [0]:

     <press 1, then enter>

> SlackBuild: http://slackbuilds.org/slackbuilds/14.1/libraries/GitPython.tar.gz
> Source: https://pypi.python.org/packages/source/G/GitPython/GitPython-0.3.6.tar.gz
>
>    [0] Download SlackBuild + Source
>    [1] Download SlackBuild only
>    [2] Download Source only
>    [3] Quit
>
> Wat do u want ? [0]: 

     - enter 0 if you want to download SlackBuild script and source tarball
     - enter 1 for SlackBuild script only
     - enter 2 for sourc tarball only
     - enter 3 for quit

## AUTHOR
     getsbo was created by Arif Hendrawan <http://www.arifhn.net>
