# Pastiche Animation

## Description

In this lab, you will choose two works of art and use them to inspire an animated [*pastiche*](https://www.merriam-webster.com/dictionary/pastiche). The conceptual and artistic goal for this lab  is to create an animated 3D canvas that shows thoughtful engagement with these two pieces of art.

You can get credit for **variables**, **math-logic**, **while-loops**, **for-loops**, **if-else**, **functions** and **dictionaries**. (We will learn about dictionaries on 3/26.) You can deploy these concepts however you like as long as it is **documented with comments** and **has a visible effect in your canvas**. Your project should also include animation and you should be able to write about how your two selected images influenced the outcome in your reflection. 

This project covers [course outcomes](https://github.com/allegheny-college-cmpsc-100-fall-2023/course-materials#learning-outcomes) including application of Python programming principles, and designing and implementing original projects. 

> [!TIP]
> Read all the words in all the instructions!

## Step One: Planning

1. **Go on Artstor and choose two images for inspiration**! First, you are going to choose two artworks that resonate with you on Artstor. You can access Artstor [at this link](https://go.openathens.net/redirector/allegheny.edu?url=https%3A%2F%2Flibrary.artstor.org%2F%23%2Fhome). Spend some time searching for ideas, topics, artists, historical periods, or art styles that mean something to you! Take the time to choose **two images** that will each serve as a vital source of inpsiration. See if you can find two images that relate to each other in a way that's challenging but fun! **Place the links to your two images under Step One in the file called `planning.md`**
2. **Brainstorm your animation.** Next, take out a pen and paper. You'll set a timer for seven minutes. Keep the pen moving the whole time, and write or draw anything that comes to mind when you think about these two images and what you are able to do with animations in VPython. Consider adding [textures](https://trinket.io/library/trinkets/892338055c) to your project. **Take a photo of what you've drawn and paste in Step Two of `planning.md`.**
3. **Make a plan**. Under Step 3, write a polished paragraph with at least 100 words about what you plan to make. Or write at least 50 words and include a drawing. 

## Step Two: Get Coding

Create a VPython Trinket, title it appropriately, and save it. Paste the link to your Trinket in `trinket.md` right away, so that professor can see your progress as needed while you are working on your lab. 

**To get credit for a coding concept, include a comment above the relevant code with the concept name in all-caps.** So for **for-loops**, put a comment `# FOR-LOOPS` just above the code your using. If you use a concept more than once, flag the instance that you found the most challenging. 

**You also must document code thoroughly with comments to get credit.**

In this lab, you can get credit for **variables**, **math-logic**, **while-loops**, **for-loops**, **if-else**, **functions** and **dictionaries**. You can also get credit for **independent research**. You can use these concepts however you like, but I've included some suggestions below.  

You can choose to use some but not all of the concepts listed. You'll just need to get credit for them in your final project if not this lab. 

### Variables

Assign variables throughout your code, as a natural part of the below. 

### Lists and For-Loops

Some options: 

- Declare a list of shapes (or compound shapes) and a list of animation properties, like velocity. The two lists should be the same length. Inside    `while True`, iterate through the list of shapes in the firs tlist move each shape by the amount in the second list. See [random scatter demo](https://trinket.io/library/trinkets/1eb4cf8d51) for an exmaple of this. 
- Use a for-loop to randomly scatter a bunch of shapes. (See the demo in the last bullet for an example of this as well)
- Use a for-loop to draw the same mini-sculpture at a progressively larger scale

### While Loops

Some options: 

- Use `while True:` (with a `rate()` function as the first line insdie it) in order to animate your image. 
- Use a `while` loop to draw the same shape or compound shape more than once. 

### Functions

Some options: 

- Write a function that allows you to draw the same compound shape, or 3D sculpture, over and over again, as in this [stick-figure-demo](https://drive.google.com/file/d/1Qtyu2AhH2P3sObAaIAO7bvNUaafUL9rW/view). Return the compound shape so that you can manipulate it later. 
- Write your own rotation function. You can use the one in the stick-figure demo above as a starting place, but make it your own in some way. 
- Write a function that interpolates between colors to create a gradient.

### Math-Logic + If-else

Some options (note that some suggestions include credit for both math-logic and if-else; others are just math-logic):

- Use a `random()` function to scatter objects randomly.
- Use a arithmetic operation (`+`, `-`, `*`, `/`) to move objects around the canvas or to scale them. 
- Use an `if` statement with a comparison operation to make an object move back and forth, as in the [rolling ball exercise](https://trinket.io/library/trinkets/6bdecc2b97).
- Use an `if` statement with a comparison operation to make it so that when an object crosses a boundary on one side of the canvas, it starts again on the other side. You can see an example of this and of `random()` in this [floating ghost demo](https://drive.google.com/file/d/1P_f4G5188m3aoqTCNbJ1EYe0duFG2Udv/view)
- Use an `if` statement to color shapes on one side of the origin one color (e.g `if shape.pos.x < 0: ... else:`), and on the other side another color. You could make this even more sophisticated by doing it along multiple axes. 
- Use a modulus `%` to color or scale alternating objects in a list. You can also use a modulus with an `if-else` to color objects where `index%2==1` one color and all othe objects another color. 

### Independent Research

**You need to get two checkmarks for independent resarch throughout the duration of the semester in order to receive credit**. 

To get an Independent Rsearch checkmark, you should use VPython and/or Python code we haven't covered in class (see Coding References on the syllabus). You should mark the section of code that you've independently researched with the comment label # INDEPENDENT RESEARCH, and you should explain what each line of the newly-learned code is doing in the comments. 

You should also include a link the the source code you're referencing, and an acknowledgment if you've borrowed any codeblocks more than two lines long (even if you've modified them -- mark your modifications in the comments). 

## Step Three: Reflection

In order to get a "reflection" checkmark for this lab, write at least two hundred words inside `reflection.md` in which you reflect on your technical and artistic goals and accomplishments with this lab. You will also consider the strengths and weaknesses of Python itself. To receive credit, your response should address each of the following bullet points.

- In what ways did this project meet the goals set out in `planning.md`? If your project idea changed, that's okay! Just explain those changes here. 
- What would you do to further achieve these goals if you had more time?
- How do your references, in combination with the capabilities of VPython, influence the feeling and the meaning of your piece? It's okay if your references are no longer obvious in the final product, but write about how they altered the process for you. 
- How did working on this project change your skills as a coder?
- When it comes to Python and VPython, do you feel the language and library are well-designed? Is there anything that could change to make the language more effective? 


