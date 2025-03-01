# DrawItOrLoseIt
Project for SNHU

This assignment focused more on design than development, so the code isn't provided.

# Responses

. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client, The Gaming Room wanted a web application for their game Draw It or Lose it where teams of players compete to identify images as they were slowly revealed. The design follows the REST API's server-client pattern. It needsmobile and traditional operating system support, a database, and to handle sensitive user information like email.


. What did you do particularly well in developing this documentation?

I think I did a good job identifying the storage and memory constraints of the app. The speed of image transfer and render is crucial to the game, and I made a point to list some potential solutions: preloading images before the game starts, rendering at different resolutions on devices with less memory, managing the collection of images using a database or JSON file, etc. 


. What about the process of working through a design document did you find helpful when developing the code?

Thinking through the storage concerns made it easier to understand the code template and add to it. I learned more about the functions of the server-side when designing the app. It also helped to plan the object-oriented aspects beforehand.


. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I think the "Requirements" section could've been more detailed. I didn't explictly state how much storage was needed, and I would also add estimations on the memory needs. In a later week, we learned about cloud-based platforms; going back now I'd list that as an option.


. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

The user's needs match most of the needs of the client-side, so it was important to account for the information and functions that both would need. Clients need to access and add to the user and image databases and provide some of that info players. Software designs have to be very deliberate with those kinds communications--especially since they include sensitive information.


How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I designed the software keeping in mind the base requirements of the game. For each section, I focused on the most bare-bone necessities that meet the game's needs--identifying problems and giving a list of solutions with their strengths and weaknesses. I think I'd keep this approach when designing another app like it because it makes development easier. Rigid designs can create development constraints that are more troublesome than the initial design constraints. Multiple solutions with different positives and negatives is much closer to how programming actually works.
