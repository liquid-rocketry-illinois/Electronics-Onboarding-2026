# Intro Materials

## Language Stuff

We'll need to offload some of our basic c/c++ content to videos/written materials to make it feasable to get through the
sheer volume of content we have. Here is a list of the things I think we need to include for language content:

- Variables
- Math operators
- Control structures (if/while/for)
- Functions
- Pointers
    - Stack vs heap
    - Arrays
        - C Strings
- structs
- Macros/preprocessor directives
- cstd: things like printf, basic string manipulation (strlen, strcat, memcpy)
- bitwise operations
- binary and hex

Moving on to C++ stuff:

- Namespaces
- References
- Pass-by- copy/reference
- Classes and OOP
    - encapsulation
    - inheritance
    - operator overloading
    - Constructors/destructors
    - rule of 0/3/5

## Tooling

I think making a video on going through the installation steps for clion/arm/cubemx/openocd/git is reasonable, so I will
work on that too. This video won't be detailed on usage, just focused on installation and making sure the environment is
setup correctly. We'll save usage for the sessions.

I do think a separate git usage video is ok though, since I don't want to spend a lot of time on it during a session.

## Intro project

I think this would be a good idea. It would give people a chance to use some of the knowledge they are supposed to have
learned which will help them learn it better. The real challenge is coming up with something that wont be too hard.

I have come up with one idea, let me know what you guys think or if you have any ideas of your own:

- Small notepad app (with UI) based on ImGui
    - ImGui is the library I use for RCI, so I am very familiar with it.
- We provide the code that sets up the window and environment since its kind of a convoluted mess to do so (but still
  comment this code to death to explain what everything is doing)
- We have a walkthrough of putting together the most basic of features (the text editinng itself)
    - This will be fairly guided to get people introduced
    - Doing just this will be fairly simple, (i.e. like 10-15 lines)
- Then, we give ideas of what you could do to expand the app to do more things (like saving/loading a file, undo/redo,
  line numbers, other fancy things), as well as some resources for getting started in doing those things
    - We can provide some hints for these, but not full solutions
- Each one of us (leads) comes up with our own implementation that we can then show off at the sessions to talk about
  design decisions and such
- Doing graphics does scare me a little because it can be a mess sometimes, but imgui abstracts away most of it so I
  think its feasible