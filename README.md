# CS-230_Operating_Platforms

### _"Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?"_

The developers at The Gaming Room have already released the Android app "Draw It or Lose It," which poses a new challenge for memory and storage management. The game includes a library of 200 images, each with a size of 8 megabytes, resulting in a total of 1.6 gigabytes of image data. Given the high-definition nature of the game, proper memory and storage management are crucial. Loading all 200 images simultaneously can strain the game's performance, particularly on less powerful hardware. To optimize the game's speed and efficiency, a more effective approach is to load images dynamically. This entails loading images in batches or quick succession based on user progress, the current round, or other immediate requirements. By loading images on-demand, the game can run smoothly while conserving memory resources. Originally focused on developing mobile app games, The Gaming Room received positive feedback for their Android puzzle competition game. In response to customer demand, they aim to create a web-based version of their existing Android app, ensuring that the game can be enjoyed on a wide range of platforms and devices.

Design Constraints:
*	Android, iOS, and web platforms each have different tools and capabilities/requirements.
*	The program should work between each platform for seamless cross-play.
*	The capacity to inform the team captain that a team name is already taken and give them the option of selecting another.
*	A game will have the ability to have one or more teams involved. Regardless of the platform.
*	Each team will have multiple players assigned to it.
*	Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
*	Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.

In relation to their game, Draw It or Lose It, at one point I was asked to:

- Explain the operating system architectures for different operating systems.
- Analyze the differential file system components that represent a collection of data.
- Explain the functions of memory and storage management.
- Identify memory management techniques.
- Describe distributed systems and the networks that interconnect them.



### _"What did you do particularly well in developing this documentation?"_

In my detailed recommendation section, I covered essential aspects for the client's consideration, providing valuable insights. These areas included the selection of a suitable host operating system (OS), effective memory and storage management solutions on host servers, the importance of an appropriate API framework, the significance of implementing robust security measures, and the numerous benefits associated with leveraging serverless architecture to successfully launch the product. I presented a compelling argument highlighting why a cloud platform would be the optimal choice to fulfill the client's objectives.

### _"What about the process of working through a design document did you find helpful when developing the code?"_
Analyzing the domain model as a UML class diagram aided in understanding the structure and relationships of entities representing app components. This aided in the development of compact classes with basic methods that directly utilized other things to construct a clean prototype.

### _"If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?"_
Having better documentation and in-line comments within the code of my work. Some of the comment's didn't explain what I had done in an effective manner.

### _"How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?"_
It is critical to focus the user's core demands while designing web-based apps, which generally center around speed and intuitiveness in terms of usability. While quality features such as the app's design and feel are crucial, speed and usability take precedence. Even if a user is not totally delighted with the appearance of an app, they will quickly quit it if the functionality is confusing or it runs poorly. The demands of the user should be prioritized because they are the ultimate source of money for the client, making their happiness critical to the product's success.

### _"How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?"_

It is good to begin with a broad understanding and subsequently refine it to obtain precision while building software. Starting with high-level goals and iterating through many stages to arrive at the ultimate answer. For example, a client's business objectives might be broken down into functional requirements, which explain the core features required to fulfill those goals. These functional requirements can then be subdivided into technical requirements, which outline the technological method needed to achieve the functional needs. Finally, the technical requirements may be converted into design papers, architecture, and code, yielding a solution that meets the criteria while also delivering the end product.
