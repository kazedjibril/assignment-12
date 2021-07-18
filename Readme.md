PART I
1.	What is object oriented programming?
A programming language structure wherein the data and their associated processing ("methods") are defined as self-contained entities called "objects." 
~ https://www.pcmag.com/encyclopedia/term/object-oriented-programming
2.	Why would you use it? 
We use OOP when we want to achieve the following features:
a.	Encapsulation (which forces modularity)
Encapsulation refers to the creation of self-contained modules that bind processing functions to the data. These user-defined data types are called "classes," and one instance of a class is an "object." 
Encapsulation ensures good code modularity, which keeps routines separate and less prone to conflict with each other.
b.	Inheritance (which passes knowledge down)
Classes are created in hierarchies, and inheritance allows the structure and methods in one class to be passed down the hierarchy. That means less programming is required when adding functions to complex systems. If a step is added at the bottom of a hierarchy, only the processing and data associated with that unique step needs to be added. Everything else is inherited. The ability to reuse existing objects is considered a major advantage of object technology.
c.	 Polymorphism (which takes any shape)
Object-oriented programming allows procedures about objects to be created whose exact type is not known until runtime. For example, a screen cursor may change its shape from an arrow to a line depending on the program mode. The routine to move the cursor on screen in response to mouse movement would be written for "cursor," and polymorphism allows that cursor to take on whatever shape is required at runtime. It also allows new shapes to be easily integrated.
3.	In which case, in JavaScript, would an OOP pattern be a better choice?
There are so many reasons to use OOP pattern in any programming language however in our case JavaScript. As we know there are four main reasons which are the following:
a.	Modularity which comes in handy when troubleshooting
When working with object-oriented programming languages, you know exactly where to look. “Oh, the car object broke down? The problem must be in the Car class!” You don’t have to muck through anything else. 
We will need OOP pattern in any case an application or system can be divided into module. 
b.	Reuse of code through inheritance
 Suppose that in addition to your Car object, one colleague needs a RaceCar object, and another needs a Limousine object. Everyone builds their objects separately but discover commonalities between them. In fact, each object is really just a different kind of Car. This is where the inheritance technique saves time: Create one generic class (Car), and then define the subclasses (RaceCar and Limousine) that are to inherit the generic class’s traits.
Of course, Limousine and RaceCar still have their unique attributes and functions. If the RaceCar object needs a method to “fireAfterBurners” and the Limousine object requires a Chauffeur, each class could implement separate functions just for itself. However, because both classes inherit key aspects from the Car class, for example the “drive” or “fillUpGas” methods, your inheriting classes can simply reuse existing code instead of writing these functions all over again.
What if you want to make a change to all Car objects, regardless of type? This is another advantage of the OO approach. Simply make a change to your Car class, and all car objects will simply inherit the new code.
We will need this concept when we don’t want to re-type all codes from scratch.
c.	Flexibility through polymorphism
Riffing on this example, you now need just a few drivers, or functions, like “driveCar,” driveRaceCar” and “DriveLimousine.” RaceCarDrivers share some traits with LimousineDrivers, but other things, like RaceHelmets and BeverageSponsorships, are unique.
This is where object-oriented programming’s sweet polymorphism comes into play. Because a single function can shape-shift to adapt to whichever class it’s in, you could create one function in the parent Car class called “drive” — not “driveCar” or “driveRaceCar,” but just “drive.” This one function would work with the RaceCarDriver, LimousineDriver, etc. In fact, you could even have “raceCar.drive(myRaceCarDriver)” or “limo.drive(myChauffeur).”

d.	 Effective problem solving
Object-oriented programming is often the most natural and pragmatic approach, once you get the hang of it. OOP languages allows you to break down your software into bite-sized problems that you then can solve — one object at a time.
This isn’t to say that OOP is the One True Way. However, the advantages of object-oriented programming are many. When you need to solve complex programming challenges and want to add code tools to your skill set, OOP is your friend — and has much greater longevity and utility than Pac-Man or parachute pants.

PART II
1.	 write a few paragraphs describing a project that would benefit greatly from an OOP structure.
Most of modern systems are written in OOP concept, I would like to go for a banking system. We have different types of entities in this system. For example:
-	Customer (normal customer, VIP customer, etc…)
-	Worker (staff member, cashier, clears, etc…)
Those two types of entities are person type too as the resemblance. This is one of the systems needs OOP structure in other to reuse the codes.
2.	Describe the application flow from the user's point of view (user stories). 
Each person trying to access this system has his/her own way according to the clearance he/she has.
Let’s say a cashier trying to accessing the system, he/she will enter his/her account which will give him/her some view and prevent her/him to access other’s accounts.
Example a guy named Sam, he is a cashier in AB Bank. He comes in the morning; he logs in his account to be able to work. He receives a display with some different choices which differs to the display staff will receive. 
3.	What is the application's purpose?
This application is a bank application which will ease data sharing, accessing, edit, updating, etc…
4.	How would people use it? 
Depends on which person accessing the system, customer accessing the system will have several options which differ from the staff or cashier options. Signup option, Login option, Update option, deposit option, withdraw option and so on.
5.	What information would they enter?
Information to be entered most of it is user personal information, details about balance or account details.
6.	What would be received? 
Data from the database including amount from the account, details about the customer and so on.

PART III
Next, using pseudocode (or any other notation-technique or diagramming tool you wish), map out what the main objects of the system would look like, how they would be constructed, and how they would relate to each other. 
