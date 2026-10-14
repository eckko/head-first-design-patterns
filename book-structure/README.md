> Version 3; kinds: architecture + has-code (chapters 1-13, Appendix A also technique-catalogue), expository (whole book). Built on versions 1 and 2 with every id kept; adds all 799 book pictures (encrypted) with alt text and 176 picture questions.

# Head First Design Patterns: chapter map for review (quiz-advanced, version 2)

**Summary:** A visual, story-driven course on object-oriented design patterns (Strategy, Observer, Decorator, Factory, Singleton, Command, Adapter, Facade, Template Method, Iterator, Composite, State, Proxy, MVC) and the design principles behind them.

Unit ids (`c01` to `c13`, `appa`, `whole`) are the same as in version 1, so saved progress carries over. This run rebuilds the cards and question ladders with the `architecture` kind (forces, pattern, consequences, Java code blocks) on `feat/2026-10-14/version-2`, based on version 1.

## Included units

| Unit | Title | Kind + modifiers | Confidence | Pages (est.) | Weight | Ideas | Questions | HTRAB tags |
|---|---|---|---|---|---|---|---|---|
| Chapter 1 | Intro to Design Patterns | architecture + has-code | high | 18.0 | 1.1 | 27 | 161 | 5 |
| Chapter 2 | The Observer Pattern | architecture + has-code | high | 19.2 | 1.0 | 26 | 156 | 4 |
| Chapter 3 | The Decorator Pattern | architecture + has-code | high | 13.6 | 1.0 | 18 | 110 | 4 |
| Chapter 4 | The Factory Pattern | architecture + has-code | high | 25.6 | 1.0 | 35 | 208 | 5 |
| Chapter 5 | The Singleton Pattern | architecture + has-code | high | 12.6 | 1.1 | 19 | 112 | 4 |
| Chapter 6 | The Command Pattern | architecture + has-code | high | 23.9 | 0.9 | 29 | 174 | 3 |
| Chapter 7 | The Adapter and Facade Patterns | architecture + has-code | high | 16.9 | 1.0 | 23 | 137 | 3 |
| Chapter 8 | The Template Method Pattern | architecture + has-code | high | 14.0 | 1.0 | 19 | 113 | 3 |
| Chapter 9 | The Iterator and Composite Patterns | architecture + has-code | high | 28.0 | 1.0 | 38 | 227 | 4 |
| Chapter 10 | The State Pattern | architecture + has-code | high | 15.9 | 1.0 | 22 | 129 | 3 |
| Chapter 11 | The Proxy Pattern | architecture + has-code | high | 28.9 | 0.9 | 35 | 211 | 4 |
| Chapter 12 | Compound Patterns | architecture + has-code | high | 31.9 | 0.8 | 34 | 207 | 3 |
| Chapter 13 | Better Living with Patterns | architecture + has-code | medium | 24.2 | 1.2 | 39 | 235 | 4 |
| Appendix A | Leftover Patterns | architecture + has-code, technique-catalogue | medium | 9.4 | 1.0 | 13 | 76 | 3 |
| Whole book | Reading the book as a whole | expository + none | high | 8.0 | 1.0 | 11 | 65 | 3 |

**Totals:** 290.1 estimated pages x 8.0 per page = 2321 questions. Writer model: Sonnet 5.5. Cost is high for a book this size.

## Excluded
Cover, title page, dedication, praise, authors, how-to-use intro, acknowledgements, Appendix B (a closing note from the publisher), Appendix C (a promotional page), index, colophon, copyright.

## Grouping
No grouping: each of the 13 chapters is one unit, Appendix A is one unit, plus the final whole-book unit.

## Will not cover
Book figures and screenshots (source use is `paraphrase`); questions that wanted a figure are listed as "wants media" in the review report. Only cover, logo and decorative images are allowed (`extraMedia` on, encrypted).

## How to review
Answer yes or no in the chat. Changes are pushed to this same branch (`book-structure`).

## Details per unit
### Chapter 1: Intro to Design Patterns (`c01`)
Why changing requirements break inheritance-heavy designs, and how encapsulating what varies and favouring composition (Strategy) fix it.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* It started with a simple SimUDuck app; But now we need the ducks to FLY; But something went horribly wrong...; Joe thinks about inheritance...; How about an interface?; What would you do if you were Joe?; The one constant in software development; Zeroing in on the problem...; Separating what changes from what stays the same; Designing the Duck Behaviors; Implementing the Duck Behaviors; Integrating the Duck Behavior; More integration...; Testing the Duck code; Setting behavior dynamically; The Big Picture on encapsulated behaviors; HAS-A can be better than IS-A; Speaking of Design Patterns...; Overheard at the local diner...; Overheard in the next cubicle...; The power of a shared pattern vocabulary; How do I use Design Patterns?; Tools for your Design Toolbox

### Chapter 2: The Observer Pattern (`c02`)
How a subject notifies dependent objects of changes without being tightly coupled to them.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* The Weather Monitoring application overview; Unpacking the WeatherData class; What do we know so far?; Taking a first, misguided SWAG at the Weather Station; What’s wrong with our implementation?; Meet the Observer Pattern; Publishers + Subscribers = Observer Pattern; A day in the life of the Observer Pattern; Five-minute drama: a subject for observation; Two weeks later...; The Observer Pattern defined; The Observer Pattern defined: the class diagram; The power of Loose Coupling; Cubicle conversation; Designing the Weather Station; Implementing the Weather Station; Implementing the Subject interface in WeatherData; Now, let’s build those display elements; Power up the Weather Station; Using Java’s built-in Observer Pattern; How Java’s built-in Observer Pattern works; Reworking the Weather Station with the built-in support; Running the new code; The dark side of java.util.Observable; Other places you’ll find the Observer Pattern in the JDK; And the code...; The updated code, using lambda expressions; Tools for your Design Toolbox

### Chapter 3: The Decorator Pattern (`c03`)
How wrapping objects adds behaviour at runtime while keeping classes closed to modification and open to extension.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Welcome to Starbuzz Coffee; The Open-Closed Principle; Meet the Decorator Pattern; Constructing a drink order with Decorators; Okay, here’s what we know so far...; The Decorator Pattern defined; Decorating our Beverages; Cubicle Conversation; New barista training; Writing the Starbuzz code; Coding beverages; Coding condiments; Serving some coffees; Real World Decorators: Java I/O; Decorating the java.io classes; Writing your own Java I/O Decorator; Test out your new Java I/O Decorator; Give it a spin; Tools for your Design Toolbox

### Chapter 4: The Factory Pattern (`c04`)
How Simple Factory, Factory Method and Abstract Factory isolate object creation and invert dependencies on concrete classes.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Identifying the aspects that vary; But the pressure is on to add more pizza types; Encapsulating object creation; Building a simple pizza factory; Reworking the PizzaStore class; The Simple Factory defined; Franchising the pizza store; We’ve seen one approach...; But you’d like a little more quality control...; A framework for the pizza store; Allowing the subclasses to decide; Let’s make a PizzaStore; Declaring a factory method; Let’s see how it works: ordering pizzas with the pizza factory method; So how do they order?; Let’s check out how these pizzas are really made to order...; We’re just missing one thing: PIZZA!; You’ve waited long enough. Time for some pizzas!; It’s finally time to meet the Factory Method Pattern; The Creator classes; The Product classes; Another perspective: parallel class hierarchies; Factory Method Pattern defined; A very dependent PizzaStore; Looking at object dependencies; The Dependency Inversion Principle; Applying the Principle; Inverting your thinking...; A few guidelines to help you follow the Principle...; Meanwhile, back at the PizzaStore...; Ensuring consistency in your ingredients; Families of ingredients...; Building the ingredient factories; Building the New York ingredient factory; Reworking the pizzas...; Reworking the pizzas, continued...; Revisiting our pizza stores; What have we done?; More pizza for Ethan and Joel...; From here things change, because we are using an ingredient factory; Abstract Factory Pattern defined; Factory Method and Abstract Factory compared; Tools for your Design Toolbox

### Chapter 5: The Singleton Pattern (`c05`)
How to guarantee one instance with a global access point, and what multithreading does to the classic version.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* The Little Singleton; A small Socratic exercise in the style of The Little Lisper; Dissecting the classic Singleton Pattern implementation; The Chocolate Factory; Singleton Pattern defined; Houston, Hershey, PA we have a problem...; Dealing with multithreading; Can we improve multithreading?; Meanwhile, back at the Chocolate Factory...; Congratulations!; Tools for your Design Toolbox

### Chapter 6: The Command Pattern (`c06`)
How wrapping a request as an object decouples the invoker from the receiver and enables undo, macros, queues and logs.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Free hardware! Let’s check out the Remote Control...; Taking a look at the vendor classes; Cubicle Conversation; Let’s study the interaction in a little more detail...; The Objectville Diner roles and responsibilities; From the Diner to the Command Pattern; Our first command object; Using the command object; Creating a simple test to use the Remote Control; The Command Pattern defined; The Command Pattern defined: the class diagram; Assigning Commands to slots; Implementing the Remote Control; Implementing the Commands; Putting the Remote Control through its paces; Now, let’s check out the execution of our remote control test...; Time to write that documentation...; What are we doing?; Time to QA that Undo button!; Using state to implement Undo; Adding Undo to the CeilingFan commands; Get ready to test the ceiling fan; Testing the ceiling fan...; Every remote needs a Party Mode!; Using a macro command; The Command Pattern means lots of command classes; Do we really need all these command classes?; Simplifying the Remote Control with lambda expressions; Simplifying even more with method references; What if we need to do more than one thing in our lambda expression?; Test the remote control with lambda expressions; Check out the results of all those lambda expression commands...; More uses of the Command Pattern: queuing requests; More uses of the Command Pattern: logging requests; Tools for your Design Toolbox

### Chapter 7: The Adapter and Facade Patterns (`c07`)
How Adapter converts one interface to another and Facade simplifies a subsystem, guided by the Principle of Least Knowledge.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Adapters all around us; Object-oriented adapters; Test drive the adapter; The Adapter Pattern explained; Here’s how the Client uses the Adapter; Adapter Pattern defined; Object and class adapters; Real-world adapters; Old-world Enumerators; New-world Iterators; And today...; Adapting an Enumeration to an Iterator; Designing the Adapter; Dealing with the remove() method; Writing the EnumerationIterator adapter; And now for something different...; Home Sweet Home Theater; Watching a movie (the hard way); Lights, Camera, Facade!; Constructing your home theater facade; Implementing the simplified interface; Time to watch a movie (the easy way); Facade Pattern defined; The Principle of Least Knowledge; How NOT to Win Friends and Influence Objects; Keeping your method calls in bounds...; The Facade and the Principle of Least Knowledge; Tools for your Design Toolbox

### Chapter 8: The Template Method Pattern (`c08`)
How a superclass fixes an algorithm skeleton and lets subclasses supply steps, with hooks and the Hollywood Principle.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* It’s time for some more caffeine; Whipping up some coffee and tea classes (in Java); And now the Tea...; Sir, may I abstract your Coffee, Tea?; Taking the design further...; Abstracting prepareRecipe(); What have we done?; Meet the Template Method; Let’s make some tea...; What did the Template Method get us?; Template Method Pattern defined; Hooked on Template Method...; Using the hook; Let’s run the Test Drive; The Hollywood Principle; The Hollywood Principle and Template Method; Template Methods in the Wild; Sorting with Template Method; We’ve got some ducks to sort...; What is compareTo()?; Comparing Ducks and Ducks; Let’s sort some Ducks; The making of the sorting duck machine; Swingin’ with Frames; Applets; Tools for your Design Toolbox

### Chapter 9: The Iterator and Composite Patterns (`c09`)
How Iterator hides how a collection is traversed and Composite treats single objects and trees of objects uniformly.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Breaking News: Objectville Diner and Objectville Pancake House Merge; Check out the Menu Items; Lou and Mel’s Menu implementations; What’s the problem with having two different menu representations?; The Java-Enabled Waitress Specification; What now?; Can we encapsulate the iteration?; Meet the Iterator Pattern; Adding an Iterator to DinerMenu; Reworking the Diner Menu with Iterator; Fixing up the Waitress code; Testing our code; Here’s the test run...; What have we done so far?; What we have so far...; Making some improvements...; Cleaning things up with java.util.Iterator; We are almost there...; What does this get us?; Iterator Pattern defined; Single Responsibility; Taking a look at the Café Menu; Reworking the Café Menu code; Adding the Café Menu to the Waitress; Breakfast, lunch AND dinner; Here’s the test run; check out the new dinner menu from the Café!; What did we do?; We decoupled the Waitress....; ... and we made the Waitress more extensible; But there’s more!; Iterators and Collections; Is the Waitress ready for prime time?; Just when we thought it was safe...; What do we need?; The Composite Pattern defined; Designing Menus with Composite; Implementing the Menu Component; Implementing the Menu Item; Implementing the Composite Menu; Fixing the print() method; Getting ready for a test drive...; Now for the test drive...; Flashback to Iterator; The Composite Iterator; The Null Iterator; Give me the vegetarian menu; The magic of Iterator & Composite together...; Tools for your Design Toolbox

### Chapter 10: The State Pattern (`c10`)
How an object changes behaviour by delegating to state objects, and how this differs from Strategy.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Jawva Breakers; Cubicle Conversation; State machines 101; Writing the code; In-house testing; You knew it was coming... a change request!; The messy STATE of things...; The new design; Defining the State interfaces and classes; Implementing our State classes; Reworking the Gumball Machine; Now, let’s look at the complete GumballMachine class...; Implementing more states; Let’s take a look at what we’ve done so far...; The State Pattern defined; We still need to finish the Gumball 1 in 10 game; Finishing the game; Demo for the CEO of Mighty Gumball, Inc.; Sanity check...; We almost forgot!; Tools for your Design Toolbox

### Chapter 11: The Proxy Pattern (`c11`)
How remote, virtual and protection proxies control access to another object.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Coding the Monitor; Testing the Monitor; The role of the ‘remote proxy’; Adding a remote proxy to the Gumball Machine monitoring code; Remote methods 101; Java RMI, the Big Picture; How does the client get the stub object?; Back to our GumballMachine remote proxy; Getting the GumballMachine ready to be a remote service; Registering with the RMI registry...; Now for the GumballMonitor client...; Writing the Monitor test drive; Another demo for the CEO of Mighty Gumball...; The Proxy Pattern defined; Get ready for Virtual Proxy; Remote Proxy; Virtual Proxy; Displaying CD covers; Designing the CD cover Virtual Proxy; How ImageProxy is going to work; Writing the Image Proxy; Testing the CD Cover Viewer; Things to try...; What did we do?; Using the Java API’s Proxy to create a protection proxy; The PersonBean implementation; Five-minute drama: protecting subjects; Big Picture: creating a Dynamic Proxy for the PersonBean; Step one: creating Invocation Handlers; Creating Invocation Handlers continued...; Step two: creating the Proxy class and instantiating the Proxy object; Testing the matchmaking service; Running the code...; The Proxy Zoo; Tools for your Design Toolbox; The code for the CD Cover Viewer

### Chapter 12: Compound Patterns (`c12`)
How patterns combine, with MVC as the model case built from Observer, Strategy and Composite.

*Kind:* `architecture` (high): Teaches OO design patterns by forces, structure and consequences, with Java before/after code.

*Sections:* Working together; Duck reunion; What did we do?; A duck’s eye view: the class diagram; The King of Compound Patterns; Meet the Model-View-Controller; A closer look...; Looking at MVC through patterns-colored glasses; Observer; Strategy; Composite; Using MVC to control the beat...; Meet the Java DJ View; The controller is in the middle...; Let’s not forget about the model underneath it all...; Putting the pieces together; Building the pieces; Now let’s have a look at the concrete BeatModel class; The View; Implementing the View; Implementing the View, continued...; Now for the Controller; And here’s the implementation of the controller; Putting it all together...; And now for a test run...; Things to do; Exploring Strategy; Adapting the Model; Now we’re ready for a HeartController; And that’s it! Now it’s time for some test code...; MVC and the Web; Model 2: DJ’ing from a cell phone; The plan; Step one: the model; Step two: the controller servlet; Now we need a view...; Putting Model 2 to the test...; Design Patterns and Model 2; Model 2 is an adaptation of MVC to the Web; Tools for your Design Toolbox

### Chapter 13: Better Living with Patterns (`c13`)
What a pattern really is, how to choose and keep one, and when not to use it.

*Kind:* `architecture` (medium): Discusses what a pattern is, choosing and keeping patterns, anti-patterns; more principle than structure.

*Sections:* Design Pattern defined; Looking more closely at the Design Pattern definition; So you wanna be a Design Patterns writer; Organizing Design Patterns; Pattern Categories; Thinking in Patterns; Keep it simple (KISS); You know you need a pattern when...; Refactoring time is Patterns time!; If you don’t need it now, don’t do it now.; Your Mind on Patterns; Don’t forget the power of the shared vocabulary; Cruisin’ Objectville with the Gang of Four; Your journey has just begun...; The Patterns Zoo; Annihilating evil with Anti-Patterns; Tools for your Design Toolbox

### Appendix A: Leftover Patterns (`appa`)
Nine further patterns (Bridge, Builder, Chain of Responsibility, Flyweight, Interpreter, Mediator, Memento, Prototype, Visitor) in brief.

*Kind:* `architecture` (medium): Catalogue of nine further patterns, each with intent and structure, no worked chapter.

*Sections:* Bridge; Why use the Bridge Pattern?; Builder; Why use the Builder Pattern?; Chain of Responsibility; How to use the Chain of Responsibility Pattern; Flyweight; Why use the Flyweight Pattern?; Interpreter; How to implement an interpreter; Mediator; Mediator in action...; Memento; The Memento at work; Prototype; Prototype to the rescue; Visitor; The Visitor drops by

### Whole book: Reading the book as a whole (`whole`)
Putting the patterns and principles together: choosing among them, telling similar ones apart, and knowing when none is needed.

*Kind:* `expository` (high): Final unit that ties the book together is always expository.

*Sections:* 
