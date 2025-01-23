# Encode

*A process modified from the
[PRIMM](https://www.raspberrypi.org/blog/primm-talk-in-programming-lessons-research-seminar/)
approach ([official website](https://primmportal.com/))

Steps to start reverse engineering sketches:

1. **Run** • Before you look at the source code, run the sketch in full screen
   mode to fully experience its behavior and visual elements. Take note of any
   immediate impressions or key features that stand out.
2. **Pseudocode** • Based on what you see and experience on the screen, describe
   the various elements and how they operate computationally in your own words.
   Your goal is to build a mental model of the algorithm and translate that into
   step-by-step pseudocode. Steps to guide your observations:
    - What features do you see? List all visible elements such as shapes,
      colors, movement, etc.
    - How do these features behave? Consider their quantity, relationships, and
      movement patterns.
    - How can you interact with it? Try actions like clicking, dragging, or
      resizing the window. What changes occur?
    - How are colors or effects determined? Look for patterns, randomness, or
      triggers.
    - Summarize your observations into a list of plain-language steps that
      describe how you think the sketch works behind the scenes.
3. **Investigate** • Compare your pseudocode to the actual source code. Explore
   the code to identify specific lines or blocks that align with your
   predictions. Ask yourself: Does this confirm or challenge what I expected?
   Experiment with the code to deepen your understanding:
    - Modify function parameters and variable values significantly to observe
      the effects.
    - Comment out sections of the code to see how the sketch behaves without
      them.
    - If something is unclear, consult the provided resources or use AI tools to
      help clarify unfamiliar concepts or syntax.
4. **Annotate** • Duplicate the sketch into your own p5 account and add comments
   to explain what each part of the code does. i.e. Can you tell the story of
   the program?
    - If you need to, annotate each line, but be sure to focus on functions,
      parameters, and techniques that are new or unclear to you.
    - For example: describe how a function's parameters work, e.g. instead of //
      draws a circle, include the how: // the x parameter is the circle's
      distance from the origin of the canvas.
    - If you're stuck, write down specific questions for later review.
5. **Modify** • Experiment with the code to make it your own! Use this step to
   explore, play, and reinforce your understanding of how the sketch works.
   Change the code in a way that makes it distinct from the original, reflecting
   your own ideas. Perhaps start with small modifications, such as adjusting a
   single variable or parameter to gain momentum before attempting larger
   changes. If something feels tricky or unfamiliar, start there—it’s
   an opportunity to deepen your understanding. Ways to experiment:
    - Change visual elements like color, scale, or speed to see what happens.
    - Reorganize or rewrite parts of the code to simplify or extend its
      functionality.
    - Add interaction—try enabling user input through the keyboard, mouse, or
      other inputs.
