# WinObtain

*Inspired by [guinget](https://github.com/DrewNaylor/guinget) by Drew Naylor.*

## What?
This is a C++-based frontend for winget, the main goal of which is to bring some much needed quality-of-life improvements to winget, while being portable and fast.

Right now it's just a CLI frontend, with the ambition to add a GUI once I have the basic functionality working.

## Why?
I really like winget - I believe a package manager is just what any modern OS needs - but feel that it just gets in my way all too much. I hate having to reauthenticate for every single update, I hate it trying to update programs of which I need multiple versions, including not the most recent ones (mainly applies to SDKs).

## How?

For now it's just:
- C++ 21
- json-cpp

We utilise json for "blocked" and "pinned" packages for a simple, easy to back up and manually editable setup.