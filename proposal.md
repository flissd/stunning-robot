# X-Team 33 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Help people, mainly children, with concentration and memory using a memory game.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

"Find the Objects!"

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Output a matrix showing the locations of a certain amount of objects. The player then must recall where those objects were located. If they get it right, they're given a harder puzzle, if they're wrong they are given an easier puzzle.
After given a certain number of puzzles, the program will give the user a score.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The user will input their recolection of the placement of the objects in the form of ordered pairs.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Starts with a welcome, press an key to begin
Program gives user a puzzle and prompts their input

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Node Class:
Nodes for a doubley linked list in increasing order of difficulty. Difficulty is calculated based on size of array and number of
hidden objects. Generates a random puzzle with the specifications for the particular node.

Linked List Class:
Organize list of nodes, print out array of a certain node.
Keep track of the progress of the player, determine a stopping point when they are getting significantly better or worse.

Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

