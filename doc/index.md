# ias_marty_emacs_tutorials

## Buffers

To view a list of open buffers:

```
C-x C-b
```

To switch to a buffer:
```
C-x b
```

To kill the current buffer:
```
C-x k
```

## Splitting Windows

To split the current pane into top and bottom:

```
C-x 2
```

To split the current pane into left and right:

```
C-x 3
```

To change between windows:

```
C-x o
```

To eliminate the current window:
```
C-x 0
```

To eliminate all other windows except the current one:
```
C-x 1
```

## browsing the web

To open the web browser that comes with Emacs:

```
M-x eww
```

The manual for EWW can be found here:

* https://www.gnu.org/software/emacs/manual/html_node/eww/


## Using Emacspeak

A tutorial for emacspeak can be found here:

* https://github.com/tvraman/emacspeak/blob/master/info/tutorial.org

# Shells in Emacs


To run a shell:

```
M-x shell
```

## Terminals vs Shells

A "terminal" is treated differently than a shell.

To run a terminal:
```
M-x term
```

* When trying to run emacs commands when you have
the terminal window focussed, you use **C-c (whatever)** to
execute the emacs command.


## Emacspeak

Read the buffer interactively:

```
C-e B
```

Read the current character:
```
C-e c
```

Speak current line number:
```
C-e C-l
```

Repeat what was last said:
```
C-e a
```

## Reading Pages at a Time

Read a page:
```
emacspeak-speak-page (&optional arg)
C-e [
```

Go to next page:
```
C-v
```

