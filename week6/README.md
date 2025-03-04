# Week 6 • Version Control 3 / Refactoring

## References

- [Class
  Slides](https://drive.google.com/drive/u/1/folders/1HC5g1BO8moptbtgz-JwVVv9DldnW3Q_U)
- Week 4 Exercises Redux
  - [Exercise 4](https://editor.p5js.org/enickles/sketches/37od7_tjF)
  - [Exercise 3](https://editor.p5js.org/enickles/sketches/jwt-VWMOK)
- Refactoring
  - [Example 1](https://editor.p5js.org/enickles/sketches/bykhIJSBj) /
    [Refactored](https://editor.p5js.org/enickles/sketches/MAj5MQ_yk) 
  - [Example 2](https://editor.p5js.org/enickles/sketches/EQscgAK2b) /
    [Refactored](https://editor.p5js.org/enickles/sketches/E0HRz9YjC) 
  - [Example 3](https://editor.p5js.org/enickles/sketches/OXhVBDVMk) /
    [Refactored](https://editor.p5js.org/enickles/sketches/_gTwYE_0i) 
  - [Example 4](https://editor.p5js.org/enickles/sketches/eG70VJ7aV)
    - [Refactored part 1](https://editor.p5js.org/enickles/sketches/r711FGdgE) - Create a class and instantiate two objects.
    - [Refactored part 2](https://editor.p5js.org/enickles/sketches/z2_QBCX1D) - Use a loop in setup() to automate object creation.
      In draw(), access the objects to display them, move them, and make them
      bounce.
    - [Refactored part 3](https://editor.p5js.org/enickles/sketches/p9M_8aom_) - Implement a generic bounce function that works for
      all objects. This uses `return` keyword. "*[What are return
      values](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Return_values)?
      Return values are just what they sound like — the values that a function
      returns when it completes its task.*"
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
- **Tip:** Refactor your code with Git branches! See the steps and **demo videos** in this week's
  class slides. Consider installing the [Oh My Zsh shell
  framework](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/tips-and-tricks.md#oh-my-zsh) (if not already implemented) to automatically display
  when you are in a Git repository along with the current branch.

### Part 1: Refactor + Git Branches

- Set Up Your Local Project
  - Create a local directory for a p5.js project and initialize it as a [Git
  repository](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/git.md#create-a-git-repository).
  - Choose a previous sketch (from this course or another) to refactor so that
    the output remains the same, but the code is restructured for clarity and
    efficiency.
  - If your sketch is in the p5 web editor, copy and paste the code into your
    local p5 project.
- Refactor Your Sketch
  - Challenge yourself to refactor a sketch you really enjoyed but found
    messy—whether due to time constraints, evolving understanding of programming
    concepts, or a hunch that it could be optimized (e.g., addressing "code
    smells").
  - As you refactor, commit notable changes or milestones. Consider:
    - Reducing redundancy • Convert repeating elements into loops, functions, or
      classes.
    - Cleaning up unused code • Remove anything unnecessary.
    - Improving readability • Rename variables/functions for clarity so others
      can follow along without needing comments.
    - Adding comments • Reinforce your understanding of programming concepts and
      how your sketch works.
    - Organizing files • If your project is large, separate code into different
      files (see Coding Train video above).
- Experiment with Git Branches
  - Create at least one new Git branch to refactor part of your project
  - Practice switching between your branch and the "main" branch.
  - Merge your branch into "main" when you're ready.
  
### Part 2: Document

- Document your work that includes a link to your original AND refactored code.
- Describe and reflect on the changes you made and why you made them.
- How did it go with Git this week? Try experimenting with Git branches—did
  you create a branch to test changes before merging them? If so, how did it
  help (or not)? If not, what might be a use case for branching in your future
  work?
- Troubleshooting: Where did you get stuck—whether with Git, coding, or both?
  What steps did you take to troubleshoot?
- AI Use: If you used GitHub Copilot (or another AI tool) for debugging,
  refactoring, or generating code, reflect on how it influenced your process.
  Where was it helpful, and where did it fall short?
- Next steps: What coding or Git-related techniques would you like to explore
  and practice more?
- [Submit here](https://forms.gle/CJZMpMpTeDxpvWv18)

### Part 3: Prep for next week

- Next week, we'll practice pushing our code projects to GitHub. Be sure you
  have a [GitHub account](https://github.com/) (you likely set one up in Weeks 2
  and 3), and consider signing up for the GitHub Student Developer Pack for free
  benefits.
- After that, we’ll transition to the second part of the course, where you'll
  develop an independent project—or a series of smaller projects—of your choice.
  This will be an opportunity to deepen your practice with the programming
  concepts and strategies we've covered so far.
- We’ll discuss independent projects in more detail next week, but start
  brainstorming now! Come ready to share some early ideas informally when we
  meet.
