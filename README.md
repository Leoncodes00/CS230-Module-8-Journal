# CS230-Module-8-Journal
The Gaming Room Client and Software Requirements

The client was The Gaming Room, and they wanted to expand their Android-only game Draw It or Lose It into a cross-platform web application. Their goal was to make the game available on any device—computers, tablets, and phones—without requiring users to download or install anything. The application needed to support multiple simultaneous games, manage teams and players, and render images quickly for smooth real-time gameplay. The server side would handle data like scores, timing, and players, while the client side would focus on displaying drawings and interacting with users.

What I Did Well in the Documentation

One thing I think I did particularly well was clearly explaining the technical requirements and justifying why a Linux-based web server was the best choice. I compared Linux, Windows, and macOS platforms and showed how Linux offered better performance, lower costs, and easier scalability for a web game. I also explained how technologies like WebSockets, PostgreSQL, and REST APIs would work together to keep the game responsive and reliable for all users.

Helpful Parts of the Design Document Process

Working through the design document helped me think through the entire structure of the program before writing any code. It forced me to consider how different parts—like the database, client interface, and network communication—would interact. This made coding much smoother because I already had a clear plan for how the data should flow between the client and server. It also helped me think about long-term scalability, which is something I might have overlooked without that planning step.

What I Would Revise

If I could revise one part of my work, I’d spend more time improving the Domain Model section. I created a UML diagram showing relationships between Game, Player, and Team classes, but I think it could be expanded to include more detail—like the flow of data between the client and server, or how authentication ties into gameplay. Adding that would make the design easier to understand for anyone looking at it later.

Understanding and Implementing User Needs

I interpreted the user’s needs by focusing on accessibility and ease of use. The Gaming Room didn’t want users to have to install apps or deal with compatibility issues, so I designed the system to run directly in a web browser. That decision met the need for simplicity while still supporting multiplayer gameplay. Considering user needs is essential because even the best technical solution won’t matter if it’s frustrating or inconvenient for the people using it.

Approach to Software Design and Future Strategies

My approach to designing this software started with identifying what the client wanted most—speed, accessibility, and scalability—and then matching those goals with the right technologies. I used object-oriented design principles to keep the structure organized and modular. In the future, for similar projects, I’d continue using early-stage diagrams, requirement breakdowns, and platform evaluations before writing code. These strategies help ensure that the design aligns with both user expectations and technical constraints.
