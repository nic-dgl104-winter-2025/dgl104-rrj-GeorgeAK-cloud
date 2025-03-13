

# rrj-George  Akaeze
## Week 8

## What I Learned This Week

### Functional Requirements and User Stories
This week, I explored the concepts of functional requirements and user stories in software development. Key takeaways include:

- **User Stories**: These are written in natural language to describe user interactions with a system. They are great for team communication but often lack technical details.
- **Technical Design Documents (TDD)**: Used to address technical concerns and provide a high-level design context. They help align the team on architecture and technologies early in the development process.
- **Functional Requirements**: These describe software features on an input-output basis, similar to programming functions. They provide clear specifications for app features and are often derived from user stories.

Understanding these concepts helps in balancing user experience with technical implementation, ensuring robust and user-friendly applications.

## Research on Haskell

### Overview
Haskell is a purely functional programming language known for its strong static typing and lazy evaluation. It emphasizes immutability and mathematical precision, making it a favorite among those who appreciate clean and reliable code.

### Applications
1. **Academic Research**: Used for teaching functional programming concepts.
2. **Financial Systems**: Employed by companies like Standard Chartered for reliable financial software.
3. **Web Development**: Frameworks like Yesod and Servant leverage Haskell's strengths for building web services.
4. **Data Analysis**: Suitable for handling large datasets and complex computations.
5. **Compiler Development**: Ideal for developing compilers and interpreters due to its support for abstract syntax trees.

### Users
- Academic Researchers
- Financial Software Developers
- Web Developers
- Data Analysts
- Compiler Engineers

### Useful Resources
1. **Learn You a Haskell for Great Good!**: A fun and approachable online book for beginners.
2. **Haskell.org**: The official site with comprehensive documentation and tutorials.
3. **Hackage**: A central package archive for discovering and sharing Haskell libraries.
4. **Stack Overflow**: A platform for solving specific problems and learning best practices in the Haskell community.

## User Stories

**User Story 1: Purchasing a Bus Ticket**

As a commuter, I want to buy a bus ticket online to secure my seat without visiting the station.

**Acceptance Criteria:**
1. Select departure/arrival locations, date, and time.
2. View available bus services.
3. Choose a bus and pay online (credit card, PayPal, etc.).
4. Receive a confirmation email with ticket details.
5. Download or print the ticket from the email or app.

**User Story 2: Checking Bus Schedule**

As a passenger, I want to check bus schedules to plan my trip.

**Acceptance Criteria:**
1. Enter departure/arrival locations without logging in.
2. View schedules for today and tomorrow, including times and prices.
3. Filter results by time, price, or provider.

**User Story 3: Managing Bookings**

As a user, I want to view, cancel, or modify my bookings easily.

**Acceptance Criteria:**
1. Log in to view current and past bookings.
2. Cancel or modify bookings (change date/time/seat).
3. See available options for modifications.
4. Receive confirmation and refund details for cancellations.
5. Get a new confirmation email for modifications.
6. Be informed of any extra charges or refunds.


#### CHOOSE A LANGUAGE FOR COMMUNITY CODE:

For my community coding project, My group  decided to focus on PHP for both the front end and back end. My experience with PHP is limited, but I'm eager to learn more about it. We chose PHP because it's a versatile language that powers many websites and applications, making it ideal for developing dynamic and interactive web pages. PHP is widely used for server-side scripting, and its integration with databases like MySQL makes it perfect for building robust web applications. Additionally, PHP has a large and supportive community, which is beneficial for beginners seeking guidance and resources. [Learn more about PHP](https://www.php.net/manual/en/intro-whatis.php)


## Week 9
### Summary of Design Patterns

**Overview:**
Design patterns are established solutions to common problems in software design, particularly within the object-oriented programming paradigm. They were popularized by a group of four authors known as the "Gang of Four" in their book "Design Patterns: Elements of Reusable Object-Oriented Software," published in the early 1990s. This summary outlines key principles, types of design patterns, and specific examples discussed in the transcript.

**Key Principles:**
1. **Program to an Interface, Not an Implementation:** This principle encourages developers to define interfaces that specify expected behaviors without dictating how those behaviors should be implemented. This promotes flexibility and reduces dependencies between classes.
   
2. **Favor Object Composition Over Class Inheritance:** Instead of relying solely on inheritance to create complex behaviors, this principle advocates for composing objects from smaller, simpler components. This approach can lead to more maintainable and less brittle code.

**Categories of Design Patterns:**
Design patterns are typically classified into three main categories based on their purpose:
1. **Creational Patterns:** These patterns deal with object creation mechanisms, aiming to create objects in a manner suitable to the situation. An example is the Singleton pattern, which ensures a class has only one instance and provides a global point of access to it.
   
2. **Structural Patterns:** These patterns focus on how classes and objects are composed to form larger structures. They help ensure that if one part of a system changes, the entire system doesn't need to change. 

3. **Behavioral Patterns:** These patterns are concerned with algorithms and the assignment of responsibilities between objects. They help define how objects interact and communicate with one another.

**Examples of Design Patterns:**
- **Singleton Pattern:** This creational pattern restricts a class to a single instance and provides a global access point to that instance. It is useful for managing shared resources, such as database connections.
  
- **Observer Pattern:** This behavioral pattern allows a subject to notify multiple observers about state changes, facilitating a one-to-many dependency. This is particularly useful in user interface design, where changes in one part of the system need to be reflected in others.

**Resources for Further Learning:**
- Wikipedia provides a comprehensive list of design patterns, including those not covered by the Gang of Four.
- Refactoring Guru offers approachable explanations and graphics related to design patterns.
- "Learning JavaScript Design Patterns" by Addy Osmani is a recommended resource for understanding design patterns in JavaScript.

**Conclusion:**
While design patterns provide valuable solutions to common programming challenges, they are not one-size-fits-all solutions. Developers should be aware of the context in which they apply these patterns and consider the potential for over-engineering or creating complex dependencies. Understanding both design patterns and their anti-patterns can lead to better software design practices.




### HOW TO CONTRIBUTE TO OPEN SOURCE

I recently learned that contributing to open source projects is accessible to everyone, not just those with advanced coding skills. There are numerous ways to get involved, such as helping with event organization, enhancing design elements, writing documentation, managing project issues, facilitating discussions, and reviewing code contributions. This realization was a relief for me, as I often doubted my coding abilities. I also discovered valuable resources like [First Contributions](https://firstcontributions.github.io/), [First Timers Only](https://www.firsttimersonly.com/), and [Up For Grabs](https://up-for-grabs.net/#/), which are excellent starting points for newcomers seeking welcoming projects. It’s crucial to choose a project that is genuinely open source, active, and supportive of beginners.

Before diving into this world, I hesitated to contribute because I felt inexperienced. However, I now recognize that open source is inclusive and offers opportunities for everyone, including those who excel in writing, design, or translation. The guide I explored helped me identify tasks that align with my skills and interests, which was incredibly motivating. It shifted my perspective from believing that only seasoned developers could contribute to understanding that open source is a space for all—writers, designers, translators, and even those just starting their coding journey. Moreover, open source extends beyond software; it encompasses everything from educational materials to creative projects, broadening the scope for contributions. This newfound understanding has opened my eyes to the vast possibilities within the open source community.

#### Finding a Project to Contribute To

One project that caught my attention was the Guess Game created by Prateek Kalra, which can be found [here](https://github.com/prateekkalra/guess-game). I focused on setting appropriate ranges for different difficulty levels and ensuring that players received clear messages if they entered numbers outside those ranges. By tackling these challenges, I helped enhance the game's functionality and overall player experience.

#### Reflection

Searching for the right project to contribute to was a bit challenging. I explored platforms like Good First Issue, Up for Grabs, and CodeTriage to find suitable opportunities. I had specific criteria in mind, and it took considerable time to identify a project that met my expectations. Additionally, sifting through various issues in the project to find one I could effectively address added to the complexity of the process.



# **Week 10**  
## **Learning MV* Architectural Patterns**  

This week, I focused on **MV* (Model-View-Anything) architectural patterns**, which are widely used in **UI development**. These patterns help structure applications by separating **data, user interface, and logic**, making them more **maintainable and scalable**.  


## **Key Concepts of MV* Patterns**  

**MV*** is a collection of design patterns that all include the **Model (M)** and **View (V)** components but vary in the third part. The most widely used patterns include:  

- **MVC (Model-View-Controller)** – A long-standing and widely adopted pattern.  
- **MVVM (Model-View-ViewModel)** – A more modern approach, commonly used in mobile and web applications.  
- **MVP (Model-View-Presenter)** – A variation of MVC, often used in Android app development.  
- **MVI (Model-View-Intent)** – A pattern found in some mobile architectures.  


## **MVC (Model-View-Controller) Explained in Detail**  

One of the video lectures broke down **MVC** into three core components:  

1. **Model** – Manages application data and business logic.  
2. **View** – Displays the data but does not modify it.  
3. **Controller** – Acts as an intermediary between the **Model** and **View**, processing user input and updating the Model accordingly.  

---

## **Evolution of MVC in Different Platforms**  

- **iOS Development**: Initially relied heavily on **MVC**, but with the introduction of **SwiftUI**, it has shifted toward **MVVM**.  
- **Android Development**: Originally used **MVC** and **MVP**, but now prefers **MVVM** and **Jetpack Compose**.  
- **Web Development**: **MVC** remains prevalent in frameworks such as **Django, Ruby on Rails, Angular, and Vue**.  

---

## **Separation of Concerns and Why It Matters**  

A core principle of **MV* patterns** is keeping **data, user interface, and logic separate**. This makes applications:  

- **Easier to test** – Since the **Model** operates independently, unit testing becomes more straightforward.  
- **More scalable** – Modular separation prevents one small change from affecting the entire application.  
- **More maintainable** – Helps keep applications **organized, readable, and less complex**.  

---

## **Applying MVC to Software Development**  

This week, I learned that **MVC remains a foundational UI architecture**. While newer trends like **MVVM** are growing in popularity, **MVC still plays a critical role in modern applications**.  

### **How I Applied My Learning:**  
 **Examined how MVC structures function in different programming environments.**  
 **Analyzed real-world implementations in web frameworks like Django and Ruby on Rails.**  
**Researched how MVVM builds upon MVC in mobile app development.**  

---

## **Reflection**  

This week, I gained hands-on experience with **MV* architectural patterns**, which deepened my understanding. Initially, some concepts seemed **complex**, but breaking them down into their **individual components** helped me grasp them better.  

- The **biggest challenge** was identifying the **subtle differences** between **MVC, MVVM, and MVP**.  
- However, after **watching lectures, reading additional materials, and analyzing real-world examples**, I now feel **more confident** in distinguishing these patterns.  
- I also realized that **following established architectural patterns is essential** for **code organization, readability, and long-term maintainability**.  
