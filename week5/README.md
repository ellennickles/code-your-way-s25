# Week 5 • Version Control 2 / Parametric Geometries

## References

- [Class
  Slides](https://drive.google.com/drive/u/1/folders/1HC5g1BO8moptbtgz-JwVVv9DldnW3Q_U)
- Version control with Git
  - [Command Line Intro](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/commandline.md)
  - [Git Intro](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/git.md)
  - [Integrated Terminal in Visual Studio
    Code](https://code.visualstudio.com/docs/terminal/basics)
  - Coding Train videos (from 2018): [Visual Studio
    Code](https://thecodingtrain.com/tracks/2018-workflow/workflow/2-visual-studio-code)
    | [Shell](https://thecodingtrain.com/tracks/2018-workflow/workflow/3-shell)
| [Git](https://thecodingtrain.com/tracks/2018-workflow/workflow/4-git)
  
## Assignment

Don't worry if you haven't worked with algebra and trigonometry in a long time!
Just tinker and have fun with the equations in the code examples and perhaps use
GitHub Copilot to help you. This week is more about getting used to implementing
version control with Git using the command line interface.

### Part 1: Explore and Experiment

Modify each sketch to make it your own: play with the numbers (make some huge,
some tiny), change the shapes, make multiples of an animation, integrate some
random functions (`random()` and `noise()`), "layer up sine and cosine
functions" as suggested in Miller's video (linked below), make a grid, make it
interactive, and/or combine it with a previous sketch. 

- [Example 1](https://editor.p5js.org/enickles/sketches/XFLDhFgk6)
- [Example 2](https://editor.p5js.org/enickles/sketches/291nqvFwo)
- [Example 3](https://editor.p5js.org/enickles/sketches/DIQO7W7ep)
- [Example 4](https://editor.p5js.org/enickles/sketches/I3fbOML-3)
- [Example 5](https://editor.p5js.org/enickles/sketches/ARUWgs58A)

#### Resources

- Highly recommend! [Recreating Vintage Computer Art with
  Processing](https://www.youtube.com/watch?v=LaarVR1AOvs), inspired by John
  Whitney’s work (linked below), is an excellent introduction to creative coding
  with parametric equations with sine and cosine functions. (What's the
  [`return`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return)
  keyword?)
- [Khan Academy's lesson on Parametric
  equations](https://www.khanacademy.org/math/algebra-home/alg-trig-functions/alg-parametric/v/parametric-equations-1)
- [Graphs of Sine, Cosine and
  Tangent](https://www.mathsisfun.com/algebra/trig-sin-cos-tan-graphs.html)
- [Amplitude, Period, Phase Shift and
  Frequency](https://www.mathsisfun.com/algebra/amplitude-period-frequency-phase-shift.html)
- Description and use of the `sin()` function in [Creative Computing: Changes
  over time](https://creative-coding.decontextualize.com/changes-over-time) by
  Allison Parrish
- Coding Train videos
  - [3.4 Polar
    Coordinates](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/3-angles/4-polar-coordinates)
    (don't worry about vectors)
  - [3.5 Harmonic
    Motion](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/3-angles/5-harmonic-motion)
    demonstrating how to use the `sin()` function to simulate simple harmonic motion
  - [3.6 Graphing Sine
    Wave](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/3-angles/6-graphing-sine-wave)
    on how to graph and animate a sine wave varying the period and
    phase
  - [Coding Challenge #116 — Lissajous Curve
    Table](https://thecodingtrain.com/challenges/116-lissajous-curve-table) (and
    [challenge continued](https://www.youtube.com/watch?v=glDU8Nsyidg))

### Part 2: Re/Code

1. Develop a local p5 project on your computer in VS Code, and program your own
  full screen screensaver. (Hmmm... coming full circle to Week 1's preloaders?)
  Further extend one of your modified examples above or combine some.
2. Using the command line, navigate into the p5 project directory and
    initialize it as a Git repository. (I generally recommend creating one folder per p5 project to initialize as a repo.)
3. Use our [Git Intro](https://github.com/ellennickles/code-your-way-s25/blob/main/version-control-guides/git.md)
    and/or our [Week 5 Class
    Slides](https://drive.google.com/drive/u/1/folders/1HC5g1BO8moptbtgz-JwVVv9DldnW3Q_U)
    from this week as references and try committing your changes as you develop your sketch.
    - NOTE: Saving changes in VS Code does not automatically save them to your
      Git repository. To save changes in Git, you need to (1) stage (add) your
      modified files and then (2) commit them to the repository.
4. Review possible inspiration
   - Featured artists in the Class Slides
   - Classic Windows screensavers that do not use parametric equations but are
    adjacent to this week's creative
    theme: [Mystify](https://www.youtube.com/watch?v=FPfMkEgi2qI),
    [Bézier](https://www.youtube.com/watch?v=3SEBEh_t5K8), and also
    [Screensaver_XP](https://openprocessing.org/sketch/215642) by kuba
   - John Whitney’s [Catalog](https://www.youtube.com/watch?v=TbV7loKp69s) (1961)
    and [Matrix III](https://www.youtube.com/watch?v=ZrKgyY5aDvA) (1972), as
    well as [An Afternoon with John
    Whitney](https://www.youtube.com/watch?v=cP5Mj6ZvZJc)
   - [Franke’s
    Oscilloscope](https://www.drbillkolomyjec.com/artworks/generative-art-vending-machine/franke-s-oscilloscope)
    Be sure to click _Generate_ for new examples! See description for how to
    start with a pair of parametric equations.
   - [Coding Train Coding Challenge #12 — The Lorenz
    Attractor](https://thecodingtrain.com/challenges/12-lorenz-attractor) in
    Processing
   - [Peter de Jong Attractors](http://paulbourke.net/fractals/peterdejong/)
    (1989) written by Paul Bourke (images updated 2014)
   - [Visualize:
    SUPERFORMULA](http://formandcode.com/code-examples/visualize-superformula)
    in _Form+Code in Design, Art, and Architecture_
   - The [PATHS](https://exchange.art/semuspace/nfts) series by @semuspace, "an
    art project inspired by the image produced by a
    [Harmonograph](https://en.wikipedia.org/wiki/Harmonograph), a mechanical
    device that employs a pendulum to generate images"

### Part 3: Document

- Document your work. Copy and paste any code from VS Code into the p5 web
  editor, so you can link to your sketches in your documentation. I know, I know
  this is getting super redundant, but it's still the easiest way to share.
- Reflect on the discoveries and challenges you encountered with the code
  exercises **and also with your new workflow using the command line interface
  with Git for version control**. And also: what graphic or animation effects are most pleasing to you? Where did you get stuck, and what steps did you take to troubleshoot? If you debugged or extended your code with GitHub Copilot, reflect on your discoveries and challenges, noting where AI was helpful or limiting. Are there any code-related techniques that would you like to explore and practice more?
  What would you like to explore and practice more?
- [Submit here](https://forms.gle/CJZMpMpTeDxpvWv18)

### Part 4: Prepare for next week's class

- You should have this from Weeks 2 and 3 but if you don’t already have one,
  create a [GitHub account](https://github.com/).
- Sign up for the [GitHub Student Developer
  Pack](https://education.github.com/pack) to get free benefits.
