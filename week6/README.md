# Week 6 • Version Control 3 / Refactoring

## References

- [Class
  Slides](https://drive.google.com/drive/u/1/folders/1HC5g1BO8moptbtgz-JwVVv9DldnW3Q_U)
- Week 4 Exercises Redux
  - [Exercise 4](https://editor.p5js.org/enickles/sketches/37od7_tjF)
  - [Exercise 3](https://editor.p5js.org/enickles/sketches/jwt-VWMOK)
- Refactoring
  - [Example 1](https://editor.p5js.org/enickles/sketches/bykhIJSBj) /
    [Refactored]() Link TBA
  - [Example 2](https://editor.p5js.org/enickles/sketches/EQscgAK2b) /
    [Refactored]() Link TBA
  - [Example 3](https://editor.p5js.org/enickles/sketches/OXhVBDVMk) /
    [Refactored]() Link TBA
  - [Example 4](https://editor.p5js.org/enickles/sketches/eG70VJ7aV)
    - [Refactored part 1]() Link TBA
    - [Refactored part 2]() Link TBA
    - [Refactored part 3]() Link TBA
      (refactored with generic random number generator and bounce functions
      using the `return` keyword. "*[What are return
      values](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Return_values)?
      Return values are just what they sound like — the values that a function
      returns when it completes its task.*")
  - [Refactoring: Improving the Design of Existing Code, 2nd
    Edition](https://bobcat.library.nyu.edu/primo-explore/fulldisplay?docid=nyu_aleph005592882&context=L&vid=NYU&lang=en_US&search_scope=all&adaptor=Local%20Search%20Engine&isFrbr=true&tab=all&query=any,contains,martin%20fowler&sortby=date&facet=frbrgroupid,include,1149505003&mode=basic&offset=0)
    by Martin Fowler, especially “Chapter 2: Principles in Refactoring” and
    “Chapter 3: Bad Smells in Code.”  (NYU Library online access)
  - [Refactoring Guru: Refactoring](https://refactoring.guru/refactoring) (What
    is refactoring? Clean Code, Refactoring Process, Code Smells, and
    Refactoring Techniques)
  - “Chapter 24: Refactoring,” [Code Complete, 2nd
    Edition](https://bobcat.library.nyu.edu/primo-explore/fulldisplay?docid=nyu_aleph005835845&context=L&vid=NYU&lang=en_US&search_scope=all&adaptor=Local%20Search%20Engine&isFrbr=true&tab=all&query=any,contains,code%20complete&sortby=date&facet=frbrgroupid,include,1147872474&offset=0),
    by Steve McConnell (NYU Library online access) 
  - “Topic 41: Refactoring,” [The Pragmatic Programmer, 2nd
    Edition](https://bobcat.library.nyu.edu/primo-explore/fulldisplay?docid=nyu_aleph006843771&context=L&vid=NYU&lang=en_US&search_scope=all&adaptor=Local%20Search%20Engine&tab=all&query=any,contains,pragmatic%20programmer&sortby=rank&mode=basic),
    by David Thomas and Andrew Hunt (NYU Library online access)
- Related
  - [Naming things in
    JavaScript](https://gomakethings.com/naming-things-in-javascript/)
  - [Organize your code into multiple JavaScript
    files](https://thecodingtrain.com/tracks/code-programming-with-p5-js/code/6-objects/4-editor-js-files)
    (Coding Train)
  - [How to Optimize Your
  Sketches](https://p5js.org/tutorials/how-to-optimize-your-sketches/) (p5
  Reference tutorial)

## Assignment

- The ideas this week are to practice refactoring code that you have already
  written and to continue practicing version control with Git.
- **Tip:** Refactor your code with Git branches! See the steps in this week's (or last week's) class slides. Consider installing the [Oh My Zsh shell
  framework](https://github.com/ellennickles/code-your-way-s24/blob/main/version-control-guides/tips-and-tricks.md#oh-my-zsh) (if not already implemented) to automatically display
  when you are in a Git repository along with the current branch.

### Part 1: Refactor + Git Branches

- Create a local directory with a p5 project, initialize it at as a [Git
  repository](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/git.md#create-a-git-repository),
  and refactor a previous sketch so that the output is the same but
  the the code has been restructured.
- You can refactor a sketch from this course or another one. If your sketch is
  in the p5 web editor, copy and paste the code into your local p5 project on
  your computer.
- Challenge yourself to refactor a prior sketch that you really enjoyed but
  feels messy because you ran out or time, have a different understanding
  of how to implement programming concepts, and/or you have inklings that the
  code could be written in more efficient ways, i.e. "bad smells"
- As you refactor, commit notable changes or milestones:
  - Look for repeating elements to convert into a loop, a function, or a class
    to make objects.
  - Is there any unused code to remove?
  - Can you make your code more readable? e.g. Any variables or functions to
    rename so that someone else reading your code can follow along without
    needing comments?
  - Adding comments are okay too! Especially to reinforce YOUR understanding
    of programming concepts and how your sketch works.
  - If there’s a lot of code, can you organize separate into different
    files? (See Coding Train video above)
  
### Part 2: Document

- Write a blog post that includes a link to your refactored code.
- Describe and reflect on the changes you made and why you made them. How did it
  go with Git this week? For all of it (including the coding part), where did
  you get stuck, and what steps did you take troubleshoot? Anything that you
  would like to explore and practice more?
- [Submit here](https://forms.gle/CJZMpMpTeDxpvWv18)
