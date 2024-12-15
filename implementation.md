# COS126 Final Project: Implementation

Please complete the following questions and upload this `implementation.md`
file to the TigerFile assignment for the "Final Project Implementation".

**Do not alter the formatting**
(e.g. write your answer after the asterisks ** FIELD NAME ** or on the next
line after the header ### HEADER NAME). We have filled in a dummy response
for the first question in the first two sections as an example.

## Basic Information

You may copy and paste your answers from questions 1-8 in the status update.

1. **Name 1:** Samy Lamothe (replace with your name)


2. **NetID 1:** Sl2938


3. **Name 2 (include if pair project):** Nia Mosby


4. **NetID 2 (include if pair project):** NMosby


5. **Project preceptor name:** Yunyun Wang


6. **Project title:** Pacman


7. **CodePost link for proposal:**  https://codepost.io/code/566915


8. **CodePost link for revised proposal:** https://codepost.io/code/575838


9. **CodePost link for status update:**


10. **Link to project video:**
https://youtu.be/uliF0LGjMlM

11. **Number of hours to complete implementation:**
158

## Required Questions

### A. Describe your implemented project in a few sentences below.

Our final project was able to display the game of pacman, but it failed to either
show movement with the character on the screen or it would show the movement
without them on the screen.


### B. Describe your three features.
*Be specific in your description of each feature.
In particular, specify **where** they are implemented
(e.g. .java file name, starting and ending line numbers, method names, etc.).*

 1. The screen will display pacman. On line 18 is one of the instance variables,"
  private final short levelData[]" used  to help display the map that is being used. The changes to the numbers
 gives the boarders, the blue blocks and the white coins that is eaten. The method
 "DrawMaze" was on Line 295 to line 336 is where the maze is using this instance variable to draw the maze out to
 look the way it dos while playing.

 2. Our second function was to get pacman to move to eat the coin. We used a few
 instance variables for pacman's ability to move. One of which is "Pacman Speed"
. Pacman needs to move at a certain pace to make the game not to fast nor to slow.
The next instance variables used is "private int pacman_x, pacman_y, pacmand_x, pacmand_y;"
This helped with the change of direction for pacman when ever you moved him. Along
side these instance variables were these methods "private void movePacman()" this
was one of the methods which aided in moving pacman around te screen. This code was from line
150 to 186. The next method was "drawpacman" to be able to see him move we have to
draw him on screen of course. This was from line 187 to 198. Lastly, the last
method that was used to help with movement was "  class TAdapter extends KeyAdapter ", this allowed
Pacman to be controlled through the arrow keys on the computer. This was on line 405 to 436.
 3. Ghost will float randomly through the maze. The ghost is to operate similar to pacman, but without
 the key input from the user. The ghost used some instance variables like, private int[] ghost_x, ghost_y, ghost_dx, ghost_dy, ghostSpeed;
 This allowed the ghost to be able to move anywhere on the gamemap. There were some methods that allowed
 the ghost to be functional and move as well. One of the methods were "private void moveGhosts(Graphics2D g2d)"
 this method allowed the Ghost to move freely and randomly. This method is on line 200 to 270. The next method is "DrawGhost" just like
 Pacman you have to be able to draw the ghost to see the movement taken place.This method is on line
 291 to 293.


### C. Describe in detail how to compile and run your program.
*Include a few example run commands and the expected results of running your program.
For non-textual outputs (e.g. graphical or auditory), feel free to describe in
words what the output should be or reference output files (e.g. images, audio files)
of the expected output.*
To compile this program we just used the lift and recompile and this then allowed us to run. The
expected result of this is for a start up screen to pop up of pacman and have the the user press
spacebar to commence the game. Then you control pacman avoiding the ghost and rating the coins to win
the game.




### D. Describe how your program accepts user input
*Mention the line number(s) at which your program accepts user input.*
The user input that is accepted is the arrow keys are pressed to move pacman in those directions.
Line number 405 to 436. Like I mentioned before that is one of the methods which allows pacman to move.





### E. Describe how your program produces output based on user input
*Mention the line number(s) at which your program produces output.*
Line number 405 to 436. That produce movement from pacman which is the output from user input.



### F. Describe the data structure your program uses
*Also describe how it supports your program's functionality.
Include the variable name and the line number(s) at which it is declared
and initialized).*





### G. List the two custom methods written by your project group
*Include method signatures and line numbers.
If your project group wrote more than two custom functions, choose the
two functions that were most extensively tested.*

1. one of the custom method that was used was drawPacman 187 to 198

2. The other method was private void drawMaze line 295 to 336.

### H. List the line numbers where you test each of your two custom methods twice.
*For each of the four tests (two for each method), explain what was being
tested and the expected result. For non-textual results (e.g. graphical or
auditory), you may describe in your own words what the expected result
should be or reference output files (e.g. images, audio files).*
1.line 96 is where drawpacman is used and it is supposed to start the game and be able to move pacman.

2. line 387 is where the maze is being drawn for the game.

3. In the pacman class is uses both to start up the game to start playing the game of pacman

4.


## Citing Resources

### A. List below *EVERY* resource your project group looked at
*Bullet lists and links suffice.*
https://introcs.cs.princeton.edu/java/stdlib/StdDraw.java.html
https://introcs.cs.princeton.edu/java/22library/StdRandom.java.html
https://introcs.cs.princeton.edu/java/10elements/
https://www.geeksforgeeks.org/java-util-timer-class-java/
https://code-knowledge.com/java-create-game-keyadapter/
https://introcs.cs.princeton.edu/java/stdlib/StdOut.java.html
https://algs4.cs.princeton.edu/41graph/Maze.java.html
https://www.educba.com/2d-graphics-in-java/


### B. Did you cite every resource that influenced your code in the code itself?
*Every resource that informed your code should be cited in a comment at/near the
line(s) of code that it informed.*

**Yes or No?** Yes

### C. Did you receive help from classmates, past COS 126 students, or anyone else?
*If so, please list their names. ("A Sunday lab TA" or "Office hours on
Thursday" is ok if you don't know their name.)*

**Yes or No?** yes Lab Ta and office hours



### D. Did you encounter any serious problems? If so, please describe.

**Yes or No?** yes, the image of the ghost and pacman either appears and do not move or it
moves and do not appears.




### E. List any other comments here. ###




## Submission Checklist
*Please mark that you’ve done all of the following steps
(fill in square bracket with x, i.e. [x]):*

* [ ] Created a project.zip file, unzipped its contents, and checked that our
    compile and run commands work on the unzipped contents. Ensure that the .zip
    file is under 50MB in size.
* [ ] Created and uploaded a Loom or YouTube video that...
  * [ ] is maximum 2 minutes in length
  * [ ] demonstrates live your program's input(s) and output(s)
  * [ ] demonstrates live your 3 features
  * [ ] does **not** reveal any code
  * [ ] includes your project name and the name of each student
  * [ ] has its thumbnail and/or starting frame set to an image of your program
        or a title slide
  * [ ] is publicly viewable (check in an incognito browser)
  * [ ] is linked to in this `implementation.md` file (Q10 under Basic Information)
* [ ] Uploaded all .java files to TigerFile. Each .java file should be uploaded
      separately as an additional file.
* [ ] Uploaded project.zip file to TigerFile.

*After you’ve submitted the above on TigerFile, **remember to do the following**:*
* [ ] Complete and upload this `implementation.md` file to TigerFile.
* [ ] Complete and submit this Google Form
    (https://forms.cs50.io/27ca51e0-4d81-4d97-8621-ba1e5d26cd78).


## Partial Credit: Bug Report(s)
*For partial credit for buggy features, you may include a bug report for at
most 4 bugs that your project group was not able to fix before the submission
deadline. For each bug report, copy and paste the following questions and
answer them in full. Your bug report should be detailed enough for the grader
to reproduce the bug.*

***Note:** if your code appears bug-free, you should **not** submit any bug reports.*

### BUG REPORT #1:
**1. Describe in a sentence or two the bug below.**




**2. Describe in detail how to reproduce the bug (e.g. run commands, user input,
etc.).**




**3. Describe the resulting effect of bug and provide evidence
(e.g. copy-and-paste the buggy output, reference screenshot files and/or buggy
output files, include a Loom video of reproducing and showing the effects of
the bug, etc.).**




**4. Describe where in your program code you believe the bug occurs (e.g. line
numbers).**




**5. Please describe what steps you tried to fix the bug.**





## Extra Credit

### A. Going above and beyond the scope of COS126

#### Did your program go above and beyond the scope of COS126?

**Yes or No?**yes

*If yes, please answer the following question.*

#### Describe in detail how your program went above and beyond the scope of COS126.
The project used features that was not described in the lectures for cos126. THAT would graphics2d
even going to office hours the Lab ta were not able to help on it so it took a good amount of
research to be able to complete the task. We had also had lives added to the game as well.


### B. Runtime Analysis

#### Did you analyze the efficiency of a substantial component of your project?

**Yes or No?** no

*If yes, please answer the following questions.*

**1. Specify the scope of the component you are analyzing
(e.g. function name, starting and ending lines of specific .java file).**




**2. What is the estimated runtime (e.g. big-O complexity) of this component?
Provide justification for this runtime (i.e. explain in your own words why
you expect this component to have this runtime performance).**




**3. Provide experimental evidence in the form of timed analysis supporting this
runtime estimate. (Hint: you may find it helpful to use command-line
arguments/flags to run just the specified component being analyzed).**




### C. Packaging project as an executable .jar file

#### Did you package your project as an executable .jar file?

**Yes or No?** no

*If yes, please answer the following question.*

#### Describe in detail how to execute your .jar application (e.g. what execution command to use on the terminal).
*Include a few example execution commands and the expected results of running
your program. For non-textual outputs (e.g. graphical or auditory), feel free
to describe in words what the output should be or reference output files
(e.g. images, audio files) of the expected output.*



