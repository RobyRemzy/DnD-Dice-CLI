# Dnd Dice CLI

> script writen in bash

## Install

Copy both scripts inside your `$HOME/.local/bin:\` or somewhere else into your `$PATH`

If you use zsh, or any typical shell with normal shell syntax, you can usually just throw `source ~/.roll` into your zshrc or other shell config and the script will work just as well for them.

make i executable with

```shell
chomd -x roll
chmod -x dragon
```

## Prerequisite

- Work best with a terminale [NerdFonts](https://www.nerdfonts.com/#home) friendly

## Usage

Open you terminal and enter your single or complex roll with the `roll`
commande, and accept your faith. The dragon rider will be sumon in case of a _natural 20_

```bash
 $  ➜ roll d20

Rolling  d20 icosahedron
     﫩 dice roll = 14
sum total = 14
```

```bash
 $  ➜ roll 2d4 d20

Rolling 2 d4 tetrahedron
     﫪 dice roll = 4
     﫪 dice roll = 1
sum total = 5


Rolling  d20 icosahedron
     﫩 dice roll = 15
sum total = 15
```
