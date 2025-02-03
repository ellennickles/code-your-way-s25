# Decode

*A process modified from the
[PRIMM](https://www.raspberrypi.org/blog/primm-talk-in-programming-lessons-research-seminar/)
approach ([official website](https://primmportal.com/))

Steps to start reverse engineering sketches:

1. **Predict** • Before you run the sketch, look at the code and decide what it
   will do. This step encourages you to think critically and engage deeply with the code by forming hypotheses about its behavior before testing them.
    - Read through the code as if "you" were executing it like the computer,
      line by line.
    - What's the logic or flow structure?
    - What features will appear? How will these features behave? Consider their
      quantity, relationships, and movement patterns.
    - Can you interact with the sketch?
    - If it helps, draw what you think the output will be.
2. **Run** • Run the sketch and test your prediction(s). Is the output what you
   expected?
3. **Investigate** • Go back to the code and map the individual lines or blocks
   of code to the output features that you observed when you ran the sketch. For
   example, if you see a series of circles drawn in the sketch, identify which
   part of the code controls their size, position, or color. Mapping in this way
   reinforces understanding by linking abstract code to tangible outputs,
   helping you see how specific instructions translate into visual results. To
   test and reinforce your understanding:
    - Log the values of variables and operations to the Console instead of
      calculating them in your head, i.e. `console.log(some variable or
      operation)`.
    - Log statements (tracing statements) to test the order in which statements
      are executing.
    - Change function parameters and variable values in substantial ways, i.e.
      make some numbers really big or really small.
    - Comment out parts of the code to see what happens or to help you focus
      on smaller sections at a time.
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
