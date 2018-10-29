# X-Team NN Project Proposal

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
For College and Professional football scouts, there is a massive amount of statistics on a large amount of players. Accessing the particular statistics one desires and analyzing particular players can be time consuming and frusturating. Scouts and teams need a way to efficiantly comb through football statistics in a format that can be analyzed and evaluated well.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Customizable Football Player Stat Comparison

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Our program will produce a filterable list of all of the players specified by the scout, as well as all of the particular accompanying statistics desired by the scout

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

We will need a comprehensive list of all college and high school football prospects, as well as all of their stats

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The user interface would first prompt the user for what players they wanted, then it would prompt the user for what statistics they wanted, and finally would prompt for a specific "order-by" statistic

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
we need to be able to get a player by each different parameter possible
need to create a player type
need a list of players to return


Name each interface or class and briefly describe its function or purpose.
- Player ADT
- Stat ADT
- getPlayer
  - getPlayerByName
  - getPlayerByPosition
  - etc
- updatePlayer
  - calls stat specified
  - updates specified stat
- PlayerList<Player>
- StatList<Stat>




## Edit and Submit this file and any figures referenced by this document.

