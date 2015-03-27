vimtips
=======

Memo, just in case Google and my memory go down while Github stays afflow.

Usually command descriptions refer to emacs commands.

## Normal mode

**join-line** (deletes line separator character, works at the opposite of emacs, one would say in a _natural_ way)
<br>**J**

**fill-paragraph**
<br>**gq** + movement

**string-rectangle ...**
<br>**C-v** entres visual block mode, **S-i|a...** starts insertion, **Esc** exits visual block mode writing to full column

## Insert mode

**dabbrev-expand** (M-/, autocomplete from buffers)
<br>**C-n**

## Vimdiff

**Ignore whitespace (diff -Bb)**

`vimdiff -c 'set diffopt+=iwhite'`
