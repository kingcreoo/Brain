#programming

## What is neovim?

Neovim is a text editor that nerds use because it has a very high skill ceiling. The skill floor may be high but if you are able to master it, apparently, you can become a much more efficient programmer.

---

## Why do I want to use neovim?

I am interest in neovim for the obvious possible optimization of my workflow. I would love to ditch vs code because it's heavy and gay.

However I must figure out how to properly set it up for roblox programming & porting into my win11 VM, along with the standard barriers to entry.

---

## How to install & basic usage?

We can install neovim's base installation simply from the community repos. Open it in the terminal using the command `nvim`. Exit neovim using `:q` .

We can also install a pre-configured version of neovim with tons of cool packages. Install nvchad from the AUR or by cloning their repo.

---

## Usage

**Help**

We can use `:help` for a basic help document provided by neovim. You can scroll through the index, pick a topic, and run `:help topic-name` .

---

**Modes**

There are three different modes in neovim.

Insert mode - for coding
Visual mode - for manipulating text & scrolling around (i think)
Command mode - for neovim commands

---

**Leader key - Spacebar**

We can also use spacebar(default LEADER key) to open up a hub of shortcuts. From the spacebar we can:

- open nvimtree
- open terminals & new windows
- use telescope

---

**Navigation**

Move around in visual mode using hjkl.

   K
H   L
   J

--- 

**Treesitter**

Treesitter can be used as your file browser on the side of the screen. Open it using `space -> e`.

---

**Telescope**

Telescope can be used to navigate and switch through files. Using `space -> f` will prompt you with a variety of parameters to search through.

Use
`space -> f -> a` to search through all files
`space -> f -> f` to search through files