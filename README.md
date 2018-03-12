# Informational Command

My personal information command

## Setup

Place the script where most convenient. But the folder path must be added to your $PATH environment variable. It may also be best to place in your personal root directory so you can edit it easily.

```
$ cd
$ git clone <repo>
$ PATH=$PATH:~/.halp
$ chmod u+x ~/.halp
```

Now you're ready to edit and/or use

## Usage

```
$ halp
> test, git, docker, redis, ssh

$ halp git
> # helpful tip 1
> git status
> # helpful tip 2
> git fetch
```

## Things to do

- Cleanup bash script using a simple loop
- Add more extensive or helpful cmds
- Find a way to chmod script on github so user doesn't need to
- Maybe create simple setup script?