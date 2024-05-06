# MonoGame.Community.Toolkit

> [!WARNING]
> This is still under construction, please come back later.

Hi, and welcome to the MonoGame Community Toolkit.  This is a collection of several modules that can be used in any MonoGame project that implements common functionality that everyone implements at some point.  The goal for 

The **MonoGame.Community.Toolkit** is an unopinionated  collection of repositories that can be used in any MonoGame project.  Each repository is self contained and implements common functionality within it's domain that everyone implements at some point in their MonoGame project.

As stated before, this project is unopinionated.  This means that there is no core module that all other modules rely on.  You do not have to switch your `Game` class to inherit from some core which fundamentally changes how your MonoGame project is created.  There are no global/static members like a global Delta Time value that other modules would depend on.  

Each individual module is plug-n-play into any new or existing MonoGame project.

## Modules
| Name | Description |
| ---- | ----------- |
| [MonoGame.Community.Toolkit.EntityComponent](https://github.com/MonoGame-Community-Toolkit/MonoGame.Community.Toolkit.EntityComponent) | Provides a basic Entity-Component framework.  **This is not ECS**.  |
| [MonoGame.Community.Toolkit.Graphics](https://github.com/MonoGame-Community-Toolkit/MonoGame.Community.Toolkit.Graphics) | Provides graphics related utilities. |
| [MonoGame.Community.Toolkit.Input](https://github.com/MonoGame-Community-Toolkit/MonoGame.Community.Toolkit.Input) | Provides an input management layer that implements common input scenarios such as checking for keypress only on current frame, not subsequent frames.  There is also a virtual input manager that can be used to make it easier to create customized input profiles. |
| [MonoGame.Community.Toolkit.PathFinding](https://github.com/MonoGame-Community-Toolkit/MonoGame.Community.Toolkit.PathFinding) | Provides a basic path finder that can use BreadthFirst, BestFirst or A* pathfinding. |
| [Monogame.Community.Toolkit.Scenes](https://github.com/MonoGame-Community-Toolkit/MonoGame.Community.Toolkit.Scenes) | Provides a basic Scene implementation, a Scene Manager, and transition effects between scenes. |