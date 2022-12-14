# GamingRoomDesignDoc

# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room wanted to devlop a an image based guessing game called Draw It or Lose It that was already available on android, but wanted to make an application available on desktops and iOS.
The requirments included: 
  - A game will have the ability to have one or more teams involved.
  - Each team will have multiple players assigned to it.
  - Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
  - Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.
  
# What did you do particularly well in developing this documentation?
Did well evaluating the strengths and weaknesses of MacOS, Linux, and Windows for application development which included a great amount detail in regard to the different tools available to each.

# What about the process of working through a design document did you find helpful when developing the code?
It was helpful having a descriptive UML diagram to follow to help guide me through the process of implementing the iterator and singleton design patterns for the project.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I was a bit to general in the scope of the operating system recommendations and could have been more specific about how the advantages of my recommendation pertained to developing a web based game application as opposed to genral application development.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
Since the user would be creating an account to log into the game, it was important to implement the client server design pattern into the design document. Security is vital in server based applications, and it is important to take the proper defense in depth to prevent intruders from stealing user credentials (i.e., strong passwords and proper authentication methods).

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I would implement the singleton design pattern as much as possible to ensure that only unique instances of an obejct can exist in an application at any given time. The iterator pattern is an amazing way to implement an interface that abstarcts iteration of lists out of the code for easier readability. As stated above, the client server design pattern needs to be implemented in any appliation that calls for data from a non local source for optimal security. Design patterns are the cornerstone for efficient, secure, and readable projects that follow a systematic approach to application development.
