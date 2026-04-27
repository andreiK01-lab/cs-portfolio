# cs-portfolio
## CS 230 Portfolio Artifact: Draw It or Lose It Software Design Document

### Briefly summarize The Gaming Room client and their software requirements.
The Gaming Room was the client for this project. They wanted a software design for expanding their game, Draw It or Lose It, from Android to a web-based application that could run across multiple platforms. The software needed to support multiple teams and players, unique names for games and teams, and one main game service instance in memory.

### What did you do particularly well in developing this documentation?
I think I did well in organizing the design document clearly and explaining technical ideas in a way that would make sense to both the client and the development team. I also did a good job comparing operating platforms and showing why certain design choices, such as using Linux for the server environment, would be the most practical.

### What about the process of working through a design document did you find helpful when developing the code?
The design document helped me break the project into smaller parts before coding. It made it easier to understand the requirements, class relationships, and design patterns that would be needed in the application. This gave me a clearer plan before I started writing code.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I revised one part, I would improve the recommendations section by making the comparisons between platforms even more detailed. I would also add a little more discussion about long-term scaling and performance in a distributed environment.

### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I looked at the client’s main goals, such as supporting multiple platforms, keeping names unique, and managing multiple players and teams. Then I connected those needs to design choices like the singleton and iterator patterns. Considering user needs is important because the software has to solve the client’s actual problem, not just work technically.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the software design by starting with the requirements, then identifying constraints, comparing platform options, and using UML and design patterns to organize the program's structure. In the future, I would use the same process of gathering requirements first, modeling the system, and evaluating platform tradeoffs before writing code.
