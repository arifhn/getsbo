### Getsbo Manual
- - -

#### NAME
getsbo - the dumb [Slackbuilds.org][] helper
[Slackbuilds.org]: <http://www.slackbuilds.org>

#### SYNOPSYS
`getsbo <package-name>`

#### DESCRIPTION
getsbo is a helper script for download a Slackbuild script package from Slackbuilds.org

#### EXAMPLE
`$ getsbo git`

Below is the result

     Search result for 'git'
     
     1. GitPython 0.3.6 (Libraries)
     2. PyGithub 1.25.2 (Python)
     3. cgit 0.11.2 (Development)
     4. geogit 0.10.0 (Gis)
     5. geogit-py 0.10 (Gis)
     6. git-cola 2.1.0 (Development)
     7. gitdb 0.6.4 (Libraries)
     8. gitolite 3.6.2 (System)
     9. hg-git 0.8.0 (Python)
     10. libgit2 0.22.2 (Libraries)
     
     Enter a number or 0 to view next page [0]:

press 1, then enter

     SlackBuild: http://slackbuilds.org/slackbuilds/14.1/libraries/GitPython.tar.gz
     Source: https://pypi.python.org/packages/source/G/GitPython/GitPython-0.3.6.tar.gz
     
      [0] Download SlackBuild + Source
      [1] Download SlackBuild only
      [2] Download Source only
      [3] Quit
     
     Wat do u want ? [0]: 

Downloaded script package will be extracted to current working directory. And the source tarball will be moved inside the new directory. After that you can **cd** into the directory and run <package-name>.SlackBuild

#### AUTHOR
getsbo was created by [Arif Hendrawan][]
[Arif Hendrawan]: <http://www.arifhn.net>
