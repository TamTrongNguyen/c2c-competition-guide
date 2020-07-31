If you haven't already, download python for your development platform:
https://www.python.org/downloads/release/python-2718/
 - for windows, select Windows x86-64 MSI installer
 
 ![windows python dl](https://user-images.githubusercontent.com/43589228/89078466-17e2c680-d34a-11ea-8527-f4669fcfa896.png)

Create a folder for the contest on your local file system.
For example on windows, C:\Documents\C2C_Contest

![Contest folder](https://user-images.githubusercontent.com/43589228/89078467-17e2c680-d34a-11ea-81ff-8760b70588cc.PNG)

Download the code in this git repository in either of the following ways: 
 1. You can either do it by cloning the repository by downloading GitHub Desktop at https://desktop.github.com/. After it finishes, click on the installer and let it install.
 
 ![Github dl](https://user-images.githubusercontent.com/43589228/89078456-16b19980-d34a-11ea-8e8c-712200e0ea09.PNG)
 
 Then go to the GitHub Repository for the game and click on code, then GitHub Desktop and accept the prompt.
 ![Github desktop](https://user-images.githubusercontent.com/43589228/89078455-16190300-d34a-11ea-84e6-812f8b47a889.png)

 Then make sure that it is creating the repo inside of the folder you designated for the game (I.E C2C_Contest).
 ![Github repo](https://user-images.githubusercontent.com/43589228/89078457-16b19980-d34a-11ea-8a77-1760fc72e458.PNG)

 2. You can just download the files.
 ![Dl Zip](https://user-images.githubusercontent.com/43589228/89078469-17e2c680-d34a-11ea-83a9-8f40917e1803.png)
 
 Then move them to the folder you designated for the game (I.E C2C_Contest), then unzip it.
 ![unzip file](https://user-images.githubusercontent.com/43589228/89078464-17e2c680-d34a-11ea-873f-ec15c0e08ac7.PNG)

Open the 'basic_program.py' file in IDLE by navigating to the folder where you saved the files. This is the file you will be modifying to create your program.

![edit idle](https://user-images.githubusercontent.com/43589228/89078470-187b5d00-d34a-11ea-8a3b-88adf3ef589d.png)

You can see that the program always plays in column zero (the left-most column) without even examining whether that column is full or whether there are any better moves!

![open basic_program](https://user-images.githubusercontent.com/43589228/89078459-174a3000-d34a-11ea-89ca-d1c5a7ad4021.PNG)

Before you improve basic_program.py, let's make sure the rest of your setup is working.
In IDLE, open the 'test_my_program.py' file, and click 'Run' + 'Run Module'.
You should see a bunch of output in the Python Shell in IDLE.

![running test_my_program](https://user-images.githubusercontent.com/43589228/89078460-174a3000-d34a-11ea-87c9-7178d2926b32.PNG)

test_my_program runs a couple example moves through basic_program.
For each "test case", it sets up an example connect 4 board, and asks your program which column it would like to play in.

If you want to create a new program, all you have to do is copy basic_program.py to a new file, and to test it, change basic_program.py on the line "program_name = test.py" to  whatever the name of your new file is.

You are also welcome to create your own test cases by calling do_test with your own 2D list.

Once you've modified your program to be a little more interesting, you can submit it to the competition website.

(TODO URL)

Click "Submit" on the navigation bar to go to the web page to submit your program.

When you submit your program, the competition website will run its own tests against it, like test_my_program.py does, including having your submitted program play an entire game against itself to completion. If your program passes all of these tests without invalid moves or making any errors, your program will be successfully submitted.

![submit](https://user-images.githubusercontent.com/43589228/89078463-174a3000-d34a-11ea-9e94-deec7e1e8cc4.png)

Once your program is successfully submitted, you can watch your program play against any other program!
If you navigate to the "Start" page, you can start a game between any two submitted programs. The Code2College team has provided a number of programs for you to test your program against that have the team name [c2c], but you can also run your program against itself, or against other students' programs, to see how you stack up!

![start](https://user-images.githubusercontent.com/43589228/89078462-174a3000-d34a-11ea-8945-922afb700397.png)





