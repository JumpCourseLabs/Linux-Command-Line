# Linux and Command Line Course

## Michael Phelps

## Assignment 2 - Edit bash prompt

edited prompt in .bashrc to:

```
PS1=" [\d,\A]:\w \$(git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/(\1)/')@\h \\$:\[$(tput sgr0)\]"
```

Result:
![img](newprompt.png)
