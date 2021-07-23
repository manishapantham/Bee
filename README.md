# Bee
Name of the project

Bee Killing Application

Run the sourcecode(program.cs) to run the application.

Prerequisites

Miscrosoft visualstudio and .Net Framework 4.8

Program

There are three different types of bee: Worker,Drone,Queen with floating-point health property which is not writable externally,and upon creation the value is set to 100

Each bee is having a damage value set in between 0-100

Whhenever Damage method is called the health of the bee gets reduced.

When a Worker bee has health below 70% it is pronounced dead. when a Drone bee has health below 50% it is pronounced dead. when a Queen bee has health below 20% it is pronounced dead.

Explanation

It is a console application I have written a switch case in which there are two cases case 1:if we give input as 1 it will create a new bee list. case 2:if we give input as 2 the loop will gets executed till the bee is dead,if the bee is dead the damage will be stopped.

In the program we have taken the damage value as random so we will get the output in a random.

Output Here is the sample output:

Enter Input Value: 2 1: Worker alive = False health = 62 2: Drone alive = True health = 92 3: Queen alive = True health = 47 Enter Input Value: 2 1: Worker alive = False health = 62 2: Drone alive = True health = 85 3: Queen alive = False health = 3 Enter Input Value: 2 1: Worker alive = False health = 62 2: Drone alive = True health = 57 3: Queen alive = False health = 3 Enter Input Value: 1 1: Worker alive = True health = 100 2: Drone alive = True health = 100 3: Queen alive = True health = 100
