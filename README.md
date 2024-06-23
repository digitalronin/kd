# kd

Copy of a shell script I found somewhere (can't remember where) to manage directory shortcuts.

## Installation

Copy the `kd` script to somewhere on your path.

## Usage

To create a shortcut to the current directory:

```
kd foo .
```

To change directory to a shortcut:

```
kd foo
```

Uses sub-string matching, so `kd fo` would work if no other shortcut matches.
