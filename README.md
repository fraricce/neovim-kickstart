# My Neovim kickstart

## The beginning

I've spent months trying Vim and its ecosystems. Initial motivation came from the desire of challenging myself to use a tool I was not comfortable with. Then, I understood there was more in the thing, and I felt like I was connecting the dots. I started to get more information in the Vim space, reading about the principles of the Unix philosphy, and I suddenly re-aligned my principles with the basic principle of computing: spending minimal resources while getting more results. Vim was something I desiderd to spend time with: a focused environment that allowed me to easily get into deep work and relaxed coding.

## Why I use Vim

NeoVim it's the tool that I don't want to loose, and I've decided to adopt it in my programmer workflow.
Here's why: using Vim it's been like to extract a magic gem from a secret cave, spending time and dedication to discover its secrets, and harness its full power to generate more gems. 
I've found exciting and challenging the process of beginning with Vim, learning its basic commands, customizing and finally building new things on top of it, to generate new knowledege and full proucts.
Moreover, the vibrant Vim ecospace (official documentation and sources, reddit, just search on the Web) is a constant generator of new things to learn and to master. So why don't jump right in?

## Which Vim?

I've tried quite a number of configurations, plugins and versions of Vim ecospace, and my final to-go choice is NeoVim that I customized to fit my needs.
Because NeoVim has the configuration starting from a prebuilt init.lua from (this cool repo) 
[https://github.com/nvim-lua/kickstart.nvim] from TJ DeVries, a core maintainer of NeoVim and creator of important NeoVim plugins like telescope. Along the way I've just added some shortcuts and commands that I needed

## A brief introduction to NeoVim configuration

Configuration is a core aspect of NeoVim. It's where you can program the software to do exactly what you need.
NeoVim can be configured in two native ways: via VimScript (you'll have a init.vim file) or in Lua (here you'll have a init.lua file).
My choice is Lua for two reasons: it's more natural to me using a language that I can reuse for other applications than a language that I won't use elsewhere.
Moreover, Lua is a decent language with a great community, and many great products have been built with it. It's even well suited for creating videogames!

## What you'll find in this repo

My init.lua file, that is based on the one from TJ DeVries with some modifications that I'll list in the features section

## Features

For the basic features please take a look at the repo I've mentioned early, that is the repo from my small modifications are based on:
(nvim-lua/kickstart.nvim)[https://github.com/nvim-lua/kickstart.nvim]

### Additional configuration by me

* By pressing space,p,p NeoVim will execute a python file and put the result in the Vim console
* By pressing space,- NeoVim will open telescope and show last modified files

More features will be added.
