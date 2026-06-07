# GODOT PROJECT VERSION MANAGER

A simple *command line Godot Project Manager* (for linux) to manage what version a godot project should be opened with it, supporting custom godot builds

**NOTE: This Project does NOT manage your Godot Versions, it's only to manage the versions of PROJECTS**

## Introduction

Godot Project Version Manager (or gpvm) is a godot project version manager(duh) that lets you choose what project should be opened with which version. It doesn't manage the versions, but rather
lets you assign identifiers to existing Godot executables and then just specify the identifier for the project to choose what it should be opened with. This means that any sort of Godot Executeable works
(as long as it has the --project-manager and --editor flags, so basically all of them unless you remove those for some reason)

## Why Does This Exist??

- Most of the projects I find provide way more features than I need, for example, a whole GUI for displaying projeects, which I agree can be helpful but I don't need it
- A lot of them don't let you add custom godot executeables, which I have a lot of, since most of the projects also manage the installation of versions themselves
- I wanted an excuse to learn Bash (this is the only reason why I'm using bash for this instead of something else) and just make something like this (This is definetely not the only actual reason for this project and I definetely didn't make the others up)

If you want something like this but better, I like [fgvm](https://github.com/patricktcoakley/fgvm)

## Getting Started



