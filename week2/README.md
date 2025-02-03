## References

- [Class
  Slides](https://drive.google.com/drive/folders/1HC5g1BO8moptbtgz-JwVVv9DldnW3Q_U?usp=sharing)
- [In-class code tracing example](https://editor.p5js.org/enickles/sketches/rqjScpXGp) from Ellen
- [A Brief Introduction to Debugging Parts
  1-4](https://vimeo.com/channels/debugging) (p5 is not mentioned, but these
  strategies are universal for all programming languages) ~15min
- p5 Tutorial: [A Field Guide to
  Debugging](https://p5js.org/learn/debugging.html)
- [Rubber Duck Debugging: Debugging software with a rubber
  ducky](https://rubberduckdebugging.com/)
- [Happy Coding Debugging p5.js
  Tutorial](https://happycoding.io/tutorials/p5js/debugging)
- “Topic 20: Debugging,” [The Pragmatic Programmer, 2nd
  Edition](https://bobcat.library.nyu.edu/primo-explore/fulldisplay?docid=nyu_aleph006843771&context=L&vid=NYU&lang=en_US&search_scope=all&adaptor=Local%20Search%20Engine&tab=all&query=any,contains,pragmatic%20programmer&sortby=rank&mode=basic),
  by David Thomas and Andrew Hunt (NYU Library online access)
- “Chapter 23: Debugging,” [Code Complete, 2nd
  Edition](https://bobcat.library.nyu.edu/primo-explore/fulldisplay?docid=nyu_aleph005835845&context=L&vid=NYU&lang=en_US&search_scope=all&adaptor=Local%20Search%20Engine&isFrbr=true&tab=all&query=any,contains,code%20complete&sortby=date&facet=frbrgroupid,include,1147872474&offset=0),
  by Steve McConnell (NYU Library online access)
- [Frieder Nake: The Beginnings of Digital Art](https://vimeo.com/645548103)
  ~7min
- Install [Visual Studio Code](https://code.visualstudio.com/)

## Assignment

### Part 1: Decode

Use the [Decode process](https://github.com/ellennickles/code-your-way-s25/blob/main/decode.md) to practice reading and analyzing code before running it to predict the outcome.

- [Decode
  1](https://github.com/ellennickles/code-your-way-s25/blob/main/week2/decode1.js)
- [Decode
  2](https://github.com/ellennickles/code-your-way-s25/blob/main/week2/decode2.js)
- [Decode
  3](https://github.com/ellennickles/code-your-way-s25/blob/main/week2/decode3.js)
- [Decode
  4](https://github.com/ellennickles/code-your-way-s25/blob/main/week2/decode4.js)

Watch [Coding Train videos
I.2-I.4](https://thecodingtrain.com/tracks/the-nature-of-code-2/noc/perlin/intro-to-perlin-noise)
on the difference between `random()` and `noise()` ([related
code](https://editor.p5js.org/codingtrain/collections/qTyT_RX11)), or ask AI for
explanations and examples of these p5.js functions, and then:

- [Decode
  5](https://github.com/ellennickles/code-your-way-s25/blob/main/week2/decode5.js)

#### Resources

- **TL;DW**
  - Did you know that the [`random()`](https://p5js.org/reference/p5/random)
    function in p5.js does not produce pure random numbers? Instead, it
    generates what’s known as “pseudo-random” numbers. Every number within a
    given range has an equal probability of being generated, also known as
    uniform distribution of numbers
    ([example](https://editor.p5js.org/enickles/sketches/dC50tsWAF)).
  - Each time a p5.js sketch with the `random()` function starts, it produces a
    different outcome. In other words, a different pseudo-random number is
    generated. However, if you want to produce the same results (because maybe
    you prefer the visual output), then you can “seed” the number generator with
    a fixed value. To see this in action, edit the
    [`randomSeed()`](https://p5js.org/reference/p5/randomSeed) example on the
    p5.js Reference.
  - The [`noise()`](https://p5js.org/reference/p5/noise) function is also a
    random number generator, but it produces a more “smooth and organic”
    sequence of pseudo-random numbers
    ([example](https://editor.p5js.org/enickles/sketches/HvjK-H9sw)) compared to
    the `random()` function. There is also a corresponding
    [`noiseSeed()`](https://p5js.org/reference/p5/noiseSeed) function.
  - More illustrative? [Three different lines: straight, `random()`,
    `noise()`](https://editor.p5js.org/enickles/sketches/8zBZe9DuZ)
  - If you prefer to read, Daniel Shiffman explains this along with some
    alternative options to non-uniform and custom distributions of numbers in [The Nature of
    Code](https://natureofcode.com/random/).
- [Perlin Noise with p5.js](http://genekogan.com/code/p5js-perlin-noise/) by
  Gene Kogan
- [RANDOM.ORG: Introduction to Randomness and Random
  Numbers](https://www.random.org/randomness/) on “why it's hard (and
  interesting) to get a computer to generate proper random numbers.”
- [Coding Train videos on conditional
  statements](https://thecodingtrain.com/tracks/code-programming-with-p5-js/code/3-conditionals/1-conditionals)
- [Coding Train videos on while and for
  loops](https://thecodingtrain.com/tracks/code-programming-with-p5-js/code/4-loops/1-while-for)

### Part 2: Re/Code

- This assignment introduces unpredictability into our programs by
  coding procedural drawing rule sets with random functions. Invent your own
  rules and create a system that as Tyler Hobbs mentions in his talk, [Code goes
  in, Art comes out](https://www.tylerxhobbs.com/words/code-goes-in-art-comes-out), “balance[s]
  randomness and structure so the outcome is unpredictable and surprising but
  [has] a type of order that we still understand.” Challenge yourself to create
  something that is distinctive from the examples.
- Can you combine aspects from the above exercises for an unexpected design? Can
  you apply unpredictability using `random()` or `noise()` (or both!) to color
  (stroke, fill), size, stroke weight, rotation, using different types of
  [shapes or curves](https://p5js.org/reference/#Shape), vertices of
  [custom shapes](https://p5js.org/reference/p5/vertex), position, speed,
  etc.? Can you animate your sketch or make responsive/interactive? What
  functions and techniques can you continue to practice from the previous week’s exercises?
- If it helps, make a plan before you start (pseudocode).
- Work in Visual Studio Code to start getting used to this environment.
- Possible inspiration
  - Featured artists in the Class Slides
  - [Working with Color in Generative
    Art](https://tylerxhobbs.com/essays/2016/working-with-color-in-generative-art)
    by Tyler Hobbs

### Part 3: Document

- Document your work. Link to your sketches from Parts 1 and 2. Copy and paste
  any code from Visual Studio Code into the p5 web editor, so you can link to your
  sketches. I know this is redundant, but for now this is the easiest way to
  share.
- Same as last week: reflect on the discoveries and challenges you encountered
  during the exercises. What graphic or animation effects are most pleasing to
  you? Where did you get stuck, and what steps did you take to troubleshoot?
  What code-related techniques would you like to explore and practice more?
- [Submit here](https://forms.gle/CJZMpMpTeDxpvWv18)

### Part 4: Prepare for next week (plan ahead—this might take a few days!)

Next week, we'll experiment with GitHub Copilot Pro, an AI-powered coding assistant, in Visual Studio Code.

While a free version of Copilot ([Copilot Free](https://docs.github.com/en/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/about-github-copilot-free)) is available, it has limitations. However, as a student, you can access the Pro version for free.

1. If you don’t already have one, create a [GitHub account](https://github.com).
2. Sign up for a free [GitHub Education
  account](https://github.com/education/students).
3. Once verified as a student, [request free GitHub Copilot Pro
  access](https://docs.github.com/en/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/managing-your-github-copilot-pro-subscription/getting-free-access-to-copilot-pro-as-a-student-teacher-or-maintainer). (Approval might take several days.)
