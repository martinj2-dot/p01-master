# Project Requirements
**_Do not modify this file; it is for your reference only._** You should make your edits to README.md while working on your project. 

❗️indicate action items; you should remove these emoji as you complete/update the items which they accompany. (This means that your final README should have no ❗️in it!)

---

## ⚡️Project Overview

For your final project, you will be revisiting an earlier piece of code and refactoring it. (In other words, rewriting it to make it better.) In doing so, you must:
1. Implement at least one class which is appropriate to the context.
2. Add event handling (mouse or keyboard interaction). Note that it is enough to use event handlers, as outlined in the textbook; you do **not** need to use Tkinter.
3. You do **not** need to include a test suite.

You have two options as to which body of code you revisit, with slightly different (but comparable) requirements:
1. T01/T04: Choose Your Own Adventure
    - ~~Implement a class representing the player who moves throughout the labyrinth. The state of the player should be somehow affected by events in the labyrinth (and these effects should be apparent to the user).~~
    - ~~Add keyboard interaction which allows the user to navigate using arrow keys. You will probably have to edit your story/"rooms" to accommodate this.~~
    - If you plan to pursue this project path, you need to run your implementation plan by Emily first! (You need to incorproate at least one appropriate class as well as event handling, but exactly how is up to you.)
    - Your implementation must also:
        1. Include a __str__() method in your class, that returns a nicely formatted version of a class instance. Your program must also *use* this method to print an instance of your class to the console.
        2. Quit (or at least close the window) when the letter "q" is pressed on the keyboard.
    - Note: Your labyrinth should contain only "rooms" that you have created (i.e. not your classmates') and at least 5 of them.
2. T10: Oh, The Places You'll Go!
    - Implement a class representing place(s) on the map. 
    - Add mouse interaction that allows the user to click to add a new place, using the console to provide additional necessary information.
    - Your implementation must also:
        1. Include a __str__() method in your class, that returns a nicely formatted version of a class instance. Your program must also *use* this method to print an instance of your class to the console.
        2. Quit when the letter "q" is pressed on the keyboard.
    - Note: Your map should begin by loading 5 places of personal significance to you (from a specified text file).

---

## 📌Milestone 1: Setup, Planning, Design
*Due Wednesday, 4/17, by the start of class.*

- Create your project repository (this one!) 
- Update the README header with your information (name, etc.)
- Indicate which teamwork you plan to use for your project: either *Choose Your Own Adventure* or *Oh, The Places You'll Go!*
- Copy files from your original T01/T04/T10 teamwork repository into this repository
    - Make sure that git is tracking these files (in PyCharm, the filenames should *not* be red; you should also see them on GitHub after pushing)
    - _**Do not modify these files! They are for reference only!**_
- Create a CRC card for the class you will be implementing
    - You must include an image of this CRC card in your README file
    - See my example for how to do this
    - Verify via GitHub that your README is formatted appropriately to show your image
- **Commit and push** your work!

## 📌Milestone 2: Code
*Due Wednesday, 4/24, by the start of class.*

- Add new file(s) to your repository for your final project code
- Copy and paste any code that you plan to reuse from your reference files into the new file(s)
- Complete a rough draft of your code! Hints:
    - Refactor your code to use a class(es) first
    - *Then*, after that code is fully functional, add event handling
- **Commit and push** your work!

## 📌Milestone 3: Final Code, Presentation, Demo
*Due at the start of your section's Final Exam period.*

- Final version of your code, cleaned up and commented
- Final, fully completed version of your README 
    - Your README should be proofread, nicely formatted, and cleaned up (all sample text/instructions below headings replaced with your own writing)
    - Your README will be graded as it appears on GitHub, so make sure to double check how your formatting looks in a browser!
- In-class lightning presentation (5 minutes, 3 slides)
    - Your slides must be uploaded to your repository as images or a PDF file (not PowerPoint!)
    - You should briefly summarize your response to all of the Milestone 3 README prompts/subheadings
    - You should not have any slides that consist entirely of code, nor should you focus on talking about the details of your code
- In-class live demo to your classmates
- **Commit and push** your work!
