# CS255: Systems Analysis and Design

### Course Reflection:

*Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?*

The client for this project is DriverPass, a company founded to help people pass their driving tests by addressing inadequate training. They wanted me to design a secure online system that provides their student drivers with education through online classes, practice tests, and on-the-road training, all accessible via the internet to prepare them for their Department of Motor Vehicles (DMV) tests. The system is envisioned to include online accounts where customers can buy training packages, schedule and view driving lessons, take practice tests, track progress, see instructor notes, and find contact information, while employees have role-based access, actions are tracked by username, administrators get remote access and activity report downloads, and the system connects to the DMV for updated rules and policies.

*What did you do particularly well?*

I did particularly well in creating the UML Class diagram for DriverPass, making it thorough yet not cluttered and easy to follow. I used inheritance from a main User class to connect all the other users, such as Customer, Owner, and others,  into a neat structure that simplifies the design. Additionally, I defined the methods and attributes correctly for each class, ensuring every part of the system has clear roles and details to support the client's needs effectively.

*If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?*

If I could pick one part of my work to revise, I would choose the UML use case diagram. Although I feel I did a good job capturing all the use cases to reflect DriverPass’s needs, I am not happy with how I formatted it. The diagram has no crossing lines, but it still feels a bit cluttered and hard to read. To improve it, I would rearrange the actors and actions more spaciously, group related tasks, and use a larger layout to give everything room to breathe, making it easier to understand at a glance.

*How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?*

I started by reviewing the interview with the DriverPass client to understand their desired design, where the owner clearly outlined the different functions he envisioned for the system. I noted each function for various users —himself, the IT Officer, customers, and others —and translated those ideas into a UML use case diagram to map everything out. From there, I broke down those use cases into sequence and activity diagrams, as well as a UML Class diagram for the whole system, ensuring every part reflected what they needed. It is so important to consider the user’s needs when designing because that is the foundation of the system—without it, the system would not work for the client the way they want it to.

*How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?*

When I approach designing software, I begin by listening closely to the client’s needs, as I did with DriverPass, and organizing those ideas into a business requirements document and a software design document to set a clear foundation. In this class, I used techniques such as creating UML diagrams—use case, sequence, activity, and class diagrams—to map out how the system should work, organizing details from customer profiles to admin tasks. I also developed a Gantt chart to plan the project timeline and key milestones. In the future, I would continue using these diagrams and documents to analyze and design systems. Still, I would adopt an iterative approach, with regular check-ins and a feedback loop with the client, to refine the design and ensure it evolves to meet their growing demands effectively.
