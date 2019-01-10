**Theseus Terminal Emulator**

This project was created and exists as a part of the Theseus Operating System under the Rice Efficient Computing Group.

The terminal emulator allows users to run commands and interact with the virtual filesystem with unix-like commands such as cd, ls, pwd, ps, etc.

The terminal is based on an event-driven architecture with an object-oriented design wherein input events (like keystrokes) or output events (such as printing or logging) triggers handlers that will run in repsonse to these events. 


The functionality/capabilities of the terminal includes:
- logging keystrokes and storing them in a buffer
- the ability to spawn multiple terminals simultaneously due to the OO design
- running unix-like commands
- terminal-emulator behaviors such as scrolling, moving the cursor, and paging up and down
- storing command histories


**Note**This project is meant as a code sample. The project will not run or compile as a standalone due to dependencies on other portions of the operating system, which are not a part of this repository. 

