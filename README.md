# aspect-fsharp

This repository contains the "Aspect" game project for the YouTube show
[the_dev_aspect](http://youtube.com/c/thedevaspect) written in F#.

## Episode Branches

The code for each part of the F# series is stored in branches of this repo.
For each part I include branches for the initial and final states of the
code.  Here is the current list of branches for each part of the show:

- **Episode 004** - [Functional Concurrency with the Actor Model, F# Part 4](https://www.youtube.com/watch?v=AMjcjXIMzmA)
  - [part-4-initial](https://github.com/thedevaspect/aspect-fsharp/tree/part-4-initial)
  - [part-4-final](https://github.com/thedevaspect/aspect-fsharp/tree/part-4-final)

- **Episode 005** - [Parsing Text with Combinators, F# Part 5](https://youtu.be/ARJB8eDyxrg)
  - [part-5-initial](https://github.com/thedevaspect/aspect-fsharp/tree/part-5-initial)

## Cloning the Code

You have two options for cloning the code for an episode:

### 1. Clone the repo and branch directly

```
git clone -b part-N-initial https://github.com/thedevaspect/aspect-fsharp.git
```

### 2. Clone the repo and then switch to a branch

```
git clone ps://github.com/thedevaspect/aspect-fsharp.git
cd aspect-fsharp
git checkout part-N-initial
```

If you've already cloned the repository when watching a prior episode, you should
just be able to use these commands to get the code for the new episode:

```
git pull origin
git checkout part-N-initial
```

> **Don't forget to replace the `N` in `part-N-initial` with the part number
>  of the episode!**

I recommend approach #2 because it will allow you to reuse the repository for
downloading the code of future episodes.

## Recommended Code Editor

In the show I use the [Visual Studio Code](http://code.visualstudio.com) editor with
the [Ionide-fsharp](https://marketplace.visualstudio.com/items?itemName=Ionide.Ionide-fsharp)
extension to do interactive development.

### Helpful Keyboard Shortcuts

- Run current line of code: <kbd>Alt + /</kbd>
- Run current selection of code: <kbd>Alt + Enter</kbd>
- Show VS Code's command palette: <kbd>Ctrl/Cmd + Shift + P</kbd> or <kbd>F1</kbd>

VS Code's command palette contains a ton of commands that are helpful while editing
F# code.  Try typing `FSI` or `F#` in the command palette to see relevant commands.

## Questions or Feedback?

Please feel free to leave a comment on YouTube or tweet [@daviwil](https://twitter.com/daviwil) if you have
any trouble downloading or using this code!

## License

This code is licensed under the [MIT License](https://github.com/thedevaspect/aspect-fsharp/blob/master/LICENSE)
so feel free to use it in your own projects!