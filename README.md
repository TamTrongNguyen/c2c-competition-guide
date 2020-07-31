# Per-Day Milestones

## Monday 8/3
Your goal for monday should be to set up your environment
 - Join the slack workspace for the competition (TODO), (optionally) find a partner to make a team (1 or 2 per team), and tell us your team name and team members
 - Start a couple test games on the contest webapp (TODO link) to get an idea for how the website works and what the end goal is
 - Set up python and IDLE (if you don't already have python installed)
 - Get the python code running on your computer
 - Submit basic_program.py to the contest website
These are all described in detail below.

## Tuesday 8/4
Your goal for tuesday should be to improve your program to play in different positions based on the state of the game, and to pass a full submission 

## Wednesday 8/5
Your goal for wednesday should be to continue improving your program to try to beat the higher difficulty levels of Code2College provided programs, and test your program against other students' programs. 

## Thursday 8/6
It's tournament time! Let us know which program you want to use in the competition, and make some popcorn!


# Detailed Setup Guide

## Day 1
If you haven't already, download python for your development platform:
https://www.python.org/downloads/release/python-2718/
 - for windows, select Windows x86-64 MSI installer

Create a folder for the contest on your local file system.
For example on windows, C:\Documents\C2C_Contest

Download the code in this git repository. You can either do it by cloning the repository, or you can just download the files, and unzip them and move them to this directory.

Start IDLE (python's Integrated Development and Learning environment)
 - on windows, you can do this by searching for "IDLE" in the windows search bar

Open the 'basic_program.py' file in IDLE by navigating to the folder where you saved the files. This is the file you will be modifying to create your program.
You can see that the program always plays in column zero (the left-most column) without even examining whether that column is full or whether there are any better moves!

Before you improve basic_program.py, let's make sure the rest of your setup is working.
In IDLE, open the 'test_my_program.py' file, and click 'Run' + 'Run Module'.
You should see a bunch of output in the Python Shell in IDLE.

test_my_program runs a couple example moves through basic_program.
For each "test case", it sets up an example connect 4 board, and asks your program which column it would like to play in.

If you want to create a new program, all you have to do is copy basic_program.py to a new file, and to test it, change basic_program.py on the line "program_name = test.py" to  whatever the name of your new file is.

You are also welcome to create your own test cases by calling do_test with your own 2D list.

To finish today's milestone, upload basic_program.py to the competition website.

When you submit your program, the competition website will run its own tests against it, like test_my_program.py does, including having your submitted program play an entire game against itself to completion. If your program passes all of these tests without invalid moves or making any errors, your program will be successfully submitted.

Click "Submit" on the navigation bar to go to the submit web page.

For now, just type in your chosen team name and upload basic_program.py.

## Day 2
Once you've modified your program to be a little more interesting, and change the column it plays in depending on the state of the board, you can submit it to the competition website

Once your program is successfully submitted, you can watch your program play against any other program!

If you navigate to the "Start" page, you can start a game between any two submitted programs. The Code2College team has provided a number of programs for you to test your program against that have the team name [c2c], but you can also run your program against itself, or against other students' programs, to see how you stack up!

## Day 3
Work on improving your program to beat the higher difficulty [c2c] programs.
Brainstorm ideas for strategies, and don't hestitate to reach out in slack if you get stuck!
 - [c2c] Random - This program always plays in a random column, so it's relatively easy to beat
 - [c2c] Easy - This program only plays one way, and doesn't consider how you play
 - [c2c] Medium - This program plays all ways, but still doesn't consider how you play
 - [c2c] Hard - This program plays all ways, and takes into account how you play as well
 - [c2c] Expert - Good luck :)
