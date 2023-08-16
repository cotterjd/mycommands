# mycommands
commands to speed things up

## Getting Started
`$ git clone git@github.com:cotterjd/mycommands.git`<br>
`$ export PATH=~/current/directory/mycommands:$PATH`<br>

### commit
behaves like `git commit` but runs tests first and only commits if they pass


### changebranch
behaves like `git checkout` but changes branch on multiple projects. Useful in cases when your project has multiple repos involved and you want the branch names to be the same when you work on features that cross repos. Code is ad hoc, so will need to be modified.

### rootfind
will search entire system for a file and filter out all "Permission denied" messages. Since it searches the whole file system, this command takes a while

### uselocal
Comments out prod connection string and uncomments local connection string in env file

### useprod
opposite of uselocal
