# Manual

> A step through guide for csapp labs

## Malloc

#### Conflicts

Getting

`fatal error: sys/cdefs.h: No such file or directory compilation terminated`

with building the lab's drivers?

Run:

```
$ sudo apt-get install g++-multilib
```

#### Git it up

Installing **g**it

```
$ sudo apt-get update
$ sudo apt-get install git
```
Configuring **g**it

```
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@domain.com"
```

Setup Malloc

```
$ git clone https://github.com/heapsters/mon-malloc.git Malloc
$ cd Malloc
```

Committing Changes

```
# Make some changes and save
$ git add .
$ git commit -m "Descriptive commit message"
$ git push
# Follow prompt and done!
```

Pulling Changes

```
$ git pull
```

*you're ready to roll with malloc*

## Attack

#### Conflicts

Getting

```
FAILED: Initialization error: Running on an illegal host [*]
```

when running executables `./ctarget` and `./rtarget`?

Include the `-q` flag which prevents program from contacting non-existent grading server in addition to the above error.

For example:

```
$ ./ctarget -q  # i
```

*and there ya have it*
