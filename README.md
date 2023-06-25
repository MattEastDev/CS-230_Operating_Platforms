# CS-230_Operating_Platforms

### _"Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?"_
There is already an Android app called "Draw It or Lose It" from the developers, The Gaming Room. Based on the present game, they want to adapt their web-based game to support various platforms. The program is made up of numerous games that each include multiple teams with multiple players. Each game and team name must be unique for the game to operate correctly. Draw It or Lose It has a vast stock of drawings to call upon for the facilitation of its gameplay. The Gaming Room's staff has no idea how to set up an environment to facilitate gameplay on non-android platforms.

Design Constraints:
*	Android, iOS, and web platforms each have different tools and capabilities/requirements.
*	The program should work between each platform for seamless cross-play.
*	The capacity to inform the team captain that a team name is already taken and give them the option of selecting another.
*	A game will have the ability to have one or more teams involved. Regardless of the platform.
*	Each team will have multiple players assigned to it.
*	Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
*	Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.

In relation to their game, Draw It or Lose It, you have been asked to:

- Explain the operating system architectures for different operating systems.
- Analyze the differential file system components that represent a collection of data.
- Explain the functions of memory and storage management.
- Identify memory management techniques.
- Describe distributed systems and the networks that interconnect them.

In the case of Draw It or Lose It, the memory is used to store 200 images. Each image is 8 megabytes in size, so that means we have 1600 megabytes, or 1.6 gigabytes, worth of images that need proper memory and storage management. Draw It or Lose It is a game that requires rendering and displaying high-definition image files. For the game to function, a large number of images must be loaded into memory. The game may run slowly if all 200 image files are loaded at once, especially on less powerful hardware. A better approach is to load images dynamically, only loading the images that are needed at the moment. This can be done by loading images in batches or quick succession, based on the user's progress, depending on the round, or if there are some other immediate requirements. 

### _"What did you do particularly well in developing this documentation?"_


### _"What about the process of working through a design document did you find helpful when developing the code?"_


### _"If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?"_


### _"How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?"_


### _"How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?"_

