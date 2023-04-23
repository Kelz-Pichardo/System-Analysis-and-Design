# System-Analysis-and-Design

Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
What did you do particularly well?
If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?


DriverPass was the name of the client company, and their objective was to create a comprehensive system that would assist people in passing their driving exams on the first attempt. They wanted to develop a system with different levels of users, each having access to various content types. Additionally, users could schedule in-person behind-the-wheel lessons and training with certified instructors. This system was intended to manage everything and offer admins the capability to disable any packages that they no longer wanted to provide.

In this project, I broke down the requirements into use cases. I transformed the interview notes into use cases, identified the extend and include relationships, and specified who would have access to which functions. I believe that the output was quite satisfactory.

If I had to do it again, I would change the sequence diagram by conducting more research on how to create a better one. I had two "alternative" sections nested inside a parent "alternative" section, which would represent nested loops in code. However, I am not confident if it's appropriate to use nested loops in a sequence diagram. I would try to simplify the process by transforming it into single choices in order and using a more step-by-step approach.

My approach to software development entails reading the interview transcript comprehensively and noting down everything that I could interpret as a deliverable. I then focused on how those requirements could be implemented via software, setting aside the ones that were external requirements. When dealing with abstract requirements like "security," I researched the best approach. I broke down these requirements into basic tasks and created use cases. Afterward, I added complexity by introducing include and extend relationships. When designing, it's critical to consider the user's needs to ensure that you build what was requested. For instance, if the software has downloadable content available to specific users, failing to incorporate a login or a tiered user system would make the content available to anyone, defeating the purpose of offering "premium" content. Taking the user's needs into account when designing can save a lot of rework and keep clients satisfied.

As a software developer, I'm still new to the entire process. My approach involves reading all the requirements while noting down the essentials in a checklist. I then identify the system's objects and their interactions, sometimes using a UML Class Diagram, before moving on to a process diagram. Once I have both diagrams, I proceed to code the software. The diagrams assist me in identifying things that I might overlook if I jumped straight into coding. However, when pressed for time, I tend to jump straight into coding. In the future, I'll likely make extensive use of the activity diagram to outline how functions should work since they are a valuable tool to ensure that your function behaves as expected.
