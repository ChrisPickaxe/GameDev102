# Game Development 102
An experimental C# Unity development curriculum geared to learners experienced with [Scratch](https://scratch.mit.edu). This has not be vetted by any pedagogical standard or research study, and is completely made up on the fly. Maybe it will be useful, I provide no guarantees that this course is any good at all

# Getting Started 
## Git and Github
Following this course will require the regular use of git to save and share progress. If you are unfamiliar with git and / or GitHub I recommend using [GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop). Work should be saved in your own fork of the project - and since it's your own fork you should feel free to make any changes that you please, including to this readme!

For organizational purposes, each lesson should use its own branch, using the name provided in the lesson text

## Using Unity
This project uses Unity version `2021.3.16f1`

To get started: clone the project to a local folder, then open that folder as a project using Unity Hub. Let Unity do it's thing, and then you should be ready to begin!

# Lessons
## 01 - Introduction
Use the `01-intro` branch

The goal is to create a "PlayerController" C# class that, when placed on a game object in Unity, will move the game object in the four cardinal directions - up, right, down, left - in a top-down style

### Challenges:
- [ ] Use function(s) to logically organize your code, instead of putting everything in `Update`
- [ ] Use public variables to let the developer adjust the player's movement speed
  - [ ] Bonus: Use the Tooltip attribute to document and organize the variable(s)
- [ ] Use the [new](https://gamedevbeginner.com/input-in-unity-made-easy-complete-guide-to-the-new-system/) or [classic](https://docs.unity3d.com/Manual/class-InputManager.html) control system to allow for multiple control schemes and analog control
- [ ] Implement a camera control system to prevent the player from escaping the camera view

# Vocabulary
## Class
A collection of code, organized into functions and variables, that act similarly to the "Code" tab of a sprite or stage in Scratch. By creating classes of the correct types, using the correct syntax, we can directly interact with the Unity engine, and run code within the [Unity life cycle](https://docs.unity3d.com/Manual/ExecutionOrder.html). Classes, as well as functions within classes, do not have to be made to interact with the Unity engine and can be made to be run independently by code operating within the lifecycle

## Function
A collection of code within a class that is equivalent to a custom block created in the "My Blocks" section, sometimes called "methods". A function is uniquely defined by its "signature", which has two parts: 
1. The function's name, roughly equivalent to a label. By convention, should be CamelCase with a capitalized first character
2. Any inputs that the function accepts when it is called - known as "parameters" or "arguments"

A function can also optionally return a value when it is called

## Git
A protocol that handles the saving of changes in code in a standardized way that allows for multiple developers to more easily work on the same codebase. Not to be confused with "GitHub"

## GitHub
An online service that integrates with `git` and acts as a central online repository for code. Not to be confused with "Git"

## Variable
A named value that can be changed, either by the code or directly by the developer. Same as a "variable" in Scratch
