# AdventureGame
Here is small Adventure Game, a sort of Colossal Cave. The below technics were used: HashMap, shallow copy, constructor of Main class, non-static fields in Main class, String.split() method, containsKey() method, putIfAbsent() method

Allow the player to navigate between the locations in compass directions + Q (QUIT). The player should be able to type commands such as "Go West", "run South", or just "East" and the program will move to the appropriate location if there is one.  An attempt to move in an invalid direction should print a message and remain in the same place. Single letter commands (N, W, S, E, Q) should still be available.
![alt text](https://disk.yandex.ru/i/YI-POAmeqlZ2XA)

The console should display its current location, then it should prompt the user with: "Available exits are ", and its available exits. For example:

You are standing at the end of a road before a small brick building

Available exits are Q, S, E, N, W, 

A move in a valid direction should print (keep in mind N, S, E and W variants - showing N below):

You are standing at the end of a road before a small brick building

Available exits are Q, S, E, N, W, 

You are in the forest

Available exits are Q, S, W, 

An attempt to move in an invalid direction should print a message and remain in the same place. The printed message should be: "You cannot go in that direction". For Example:

You are standing at the end of a road before a small brick building

Available exits are Q, S, E, N, W, 

You cannot go in that direction

You are standing at the end of a road before a small brick building

Available exits are Q, S, E, N, W, 

Output for quit (Q) command should be displayed as:

You are standing at the end of a road before a small brick building

Available exits are Q, S, E, N, W, 

You are sitting in front of a computer learning Java
