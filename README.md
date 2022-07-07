# **Jr-Programmer-Project**

This was one of my last project during Unity Junior Programmer Pathway. It was divided on two different tasks.

## Table of Contents
 * [First task](https://github.com/Minal06/Jr-Programmer-Project/blob/main/README.md#first-task)
 * [Second task](https://github.com/Minal06/Jr-Programmer-Project/blob/main/README.md#second-task)
 * [Links](https://github.com/Minal06/Jr-Programmer-Project/blob/main/README.md#links)

### First task:

I received files with a prepared scene and I setup my first version control tool - Github.

Then I have to implement some functions with object-oriented programming:
- Necessary scene flow and interface buttons
- Data persistance between scenes (color choose of in-game elements in start menu and apply it in  simulation)
- Data persistance between sessions (with json)

Please check scripts:
 **MainManager** - It was wrote with a singleton usage for this task. 
 **ProductivityUnit** - It was class that inherit from Unit class and override some methods.

I also add an encapsulation for crucial properties - as intended in this task.

### Second Task:

There was also prepared Optimization folder. Scene there spawn a lot of different game objects, that slow down game drastically.

My task was to optimalize scene with use of Unity Profiler.
With *Profiler.BeginSample();* and *EndSample();* I manage to find and solve the issue in the **OptimUnit** script.

### Links
