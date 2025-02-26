# CS360_Project2_3


    Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
			This app was built to answer the need to manage a stock of supplies. It needed to store inventory items and amounts in a database, provide mulit-user access, allow adjustments to stock, and send allerts via SMS when stock is low.
   
    What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
      The first screen was a login screen, with standard username and password inputs and login and signup buttons. That leads into the main screen featuring a recyclerview list that can be populated with inventory items, each featuring add, subtract, and remove buttons. Adding items is done via a fab that brings up a popup window featuring inputs for the item name and amount. One final screen features simply a button enabling SMS notifications. I believe the screens and layouts are intuitive, or if not outright intuitive, at least common enough in app design that users will have almost certainly encountered them before.
      
    How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
      For this project, I was tackling many new concepts, and so I took a divide and conquer approach featuring research and trial and error. Much research went into setting up the seperate features, but weaving the disparate parts together took more trial and error. As the project evolved, I found how My approach to bundling functions and methods together shifting. My view of what could constitute a complete class changed, and I believe that will serve me greatly in the future for any OOP programming project.
    
    How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
      Testing was done in a fairly standard fashion, running the application after the smallest functional unit was added. My understanding and appreciation of the logcat and debug features improved by leaps and bounds. The process is vital because it's simply not possible for a person to track every function and predict the outcomes of all the myriad interactions that occur in milliseconds, the best way to ensure every odd interaction and calculation never goes astray is to run the program.
      
    Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
      The lion's share of innovating came from trying to get the seperate features to work together, but also some fine tuning of standard features to handle more complex input. Finding materials that cover setting up a recyclerview is one thing, but incorporating the SMS notification function into the inventory, or encouraging the database to change in unison with the custom layout, were not topics with much material to sift through.
      
      In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
        I think setting up the database and weaving it into the various parts of the application was the most successful part of my development process. The documentation for SQLite seemed less than ideal, but I've worked with databases before and I had some prior understanding of how to interact with them.
