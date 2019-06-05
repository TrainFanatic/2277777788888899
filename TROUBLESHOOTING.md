#Troubleshooting
This is the troubleshooting document

##Error 1: Permission denied

**When executing linesplitter, I get something like this:**

Bash:

```
bash: ./linesplitter: Permission denied
```

Zsh:

```
zsh: permission denied: ./linesplitter
```

Csh:

```
./linesplitter: Permission denied.
```

Tcsh:

```
./linesplitter: Permission denied.
```

Ksh:

```
ksh: ./linesplitter: cannot execute [Permission denied]
```

Sh:

```
sh: ./linesplitter: Permission denied
```

*etc, etc*

### Fix:

```
chmod +x linesplitter
```

