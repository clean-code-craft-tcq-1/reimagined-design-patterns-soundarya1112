# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

**Observer Pattern :**
About:
Observer pattern is used when there is one-to-many relationship between objects such as if one object is modified, its dependent objects are to be notified automatically. Observer pattern falls under behavioral pattern category. The Observer defines a one-to-many relationship so that when one object changes state, the others are notified and updated automatically. Some auctions demonstrate this pattern.

Problems that can be solved using the pattern:
You have moved to a new area and are searching for a good pre school for your child. You zero in on one but there are no vacanies left. Administrator tells you that some seats might get vacant in a month since some families might move out of area. You give them your phone number and ask them to keep you updated of any change. After a month, you get a call that there is a spot available for your child and you are in. Observer pattern helped you get admission for your child.

Advantages : 
•	Allows you to send data to many other objects in a very efficient mannor. 
•	No modification is need to be done to the subject to add new observers. 
•	You can add and remove observers at anytime.

Disadvantages:
•	The order of Observer notifications is undependable
•	If not used carefully the observer pattern can add unecessary complexity

**Prototype Pattern:**
About:
Prototype allows us to hide the complexity of making new instances from the client. The concept is to copy an existing object rather than creating a new instance from scratch, something that may include costly operations. The existing object acts as a prototype and contains the state of the object. The newly copied object may change same properties only if required.

Problems that can be solved using the pattern:
A possible real world application might be say, when you need to create a spreadsheet containing many cells. Rather than set the style for each newly created cell to override the default stylings, you'd use a Prototype pattern to create a template cell, and clone that cell when creating new cells.

Advantages:
•	It reduces the need of sub-classing. 
•	It hides complexities of creating objects. 
•	The clients can get new objects without knowing which type of object it will be. It lets you add or remove objects at runtime.
Disadvantages:

•	There is certainty in determining the number of iterations.
•	There may be incomplete or inadequate problem analysis.
•	There may increase the complexity of the system.

**State Pattern:**
About:
State design pattern is used when an Object changes its behavior based on its internal state. If we have to change behavior of an object based on its state, we can have a state variable in the Object and use if-else condition block to perform different actions based on the state.

Problems that can be solved using the pattern:
TV Remote control is one of the best examples of the State Design Pattern. Using the TV Remote Control we can switch On the TV and switch off the TV. That means the Remote control internally maintains two states (i.e. On and Off)

Advantages:
•	With State pattern, the benefits of implementing polymorphic behavior are evident, and it is also easier to add states to support additional behavior.
•	The State design pattern also improves Cohesion 
Disadvantages:
•	The State pattern requires a lot of code to be written. 
•	Depending on how many different state transition methods are defined, and how many possible states an object can be in, there can quickly be dozens or more different methods that must be written.

**Proxy Pattern:**
About:
In proxy pattern, a class represents functionality of another class. This type of design pattern comes under structural pattern. In proxy pattern, we create object having original object to interface its functionality to outer world. 

Problems that can be solved using the pattern:
A real world example can be a cheque or credit card is a proxy for what is in our bank account. It can be used in place of cash, and provides a means of accessing that cash when required. And that's exactly what the Proxy pattern does – Controls and manage access to the object they are protecting

Advantages:
•	Proxy pattern is security. This pattern avoids duplication of objects which might be huge size and memory intensive. This in turn increases the performance of the application.
Disadavantages:
•	The downside here is 'magic' could be happening that an extender is unaware of (a 'black-box' problem). ... 
•	A proxy can mask the life-cycle and state of a volatile resource from its client.




