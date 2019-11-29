# Technopedia

## Difference between a data warehouse and a data lake

The main difference between a data warehouse vs. data lake vs. relational database system is that a relational database is used to store and organize structured data from a single source, such as a transactional system, while data warehouses are built to hold structured data from multiple sources.

### Data lake

The biggest advantage of data lakes is flexibility. By allowing the data to remain in its native format, a far greater—and timelier—stream of data is available for analysis. Some of the benefits of a data lake include: Ability to derive value from unlimited types of data.

### Hadoop data lake

A Hadoop data lake is a data management platform comprising one or more Hadoop clusters. It is used principally to process and store nonrelational data, such as log files, internet clickstream records, sensor data, JSON objects, images and social media posts.

## JavaScript primitives 

In JavaScript there are 5 primitive types: undefined , null , boolean , string and number . Everything else is an object. The primitive types boolean, string and number can be wrapped by their object counterparts. These objects are instances of the Boolean , String and Number constructors respectively.

### Big data and Data Lake

 Perhaps the greatest difference between data lakes and data warehouses is the varying structure of raw vs. processed data.

 Raw data is data that has not yet been processed for a purpose. Much associated with Data Lake. Because of this, data lakes typically require much larger storage capacity than data warehouses.

## Continuous Integration 

CI is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.

The goal of Continuous Integration is to provide rapid feedback so that if a defect is introduced into the code base, it can be identified and corrected as soon as possible. Continuous integration software tools can be used to automate the testing and build a document trail.

A CI/CD tool such as Jenkins or Travis CI is used to automate the steps and provide reporting.

How do you achieve continuous integration?

1. Maintain a code repository.

2. Automate the build.

3. Make the build self-testing.

4. Everyone commits to the baseline every day.

5. Every commit (to baseline) should be built.

6. Keep the build fast.

7. Test in a clone of the production environment.


## Benefits of REACT

1. Used for Single Page Applications

2. Better Performance - Businesses that use ReactJS are assured of better performance compared to those that use other frameworks - Avoids 2 way binding - Virtual DOM (DIFFING ALGORITHM). 

Because ReactJS helps to prevent updating of DOM, it means that the apps will be faster and deliver better UX. ReactJS was designed to help improve the total rendered pages from the website server.

  Virtual DOM - Any new view changes are first performed on the virtual DOM, which lives in memory and not on your screen. An efficient algorithm (DIFFING ALGORITHM) then determines the changes made to the virtual DOM to identify the changes that need to be made to the real DOM. It then determines the most effective way to make these changes and then applies only those changes to the real DOM. This guarantees a minimum update time to the real DOM, providing higher performance and a cleaner user experience all around.

3. It's used for handling view layer for web and mobile apps. 

4. React also allows us to create reusable UI components.

5. Another React js benefits is its ability to deal with a common search engine failure to read JavaScript-heavy apps. As a solution, React can run on the server, rendering and returning the virtual DOM to the browser as a regular webpage.

6. Speed. Fast and is optimised during compilation.

7. Handle errors at run time during compilation.

8. It’s the V in the MVC – the view part

9. Great Developer Tools

 React Developer Tools, available for Chrome and Firefox, is a browser extension for React. It allows you to inspect the React component hierarchies in the virtual DOM. 

10. JSX produces React “elements” and has a number of side benefits, including helping prevent injection attacks.

REACT Testing - https://github.com/testing-library/react-testing-library/blob/master/README.md

## What is JSX

 Basically, JSX is a JavaScript render function that helps you insert your HTML right into your JavaScript code.


 What ia BABEL?

 Babel is a JavaScript compiler. Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.


## What are the 5 Scrum ceremonies?

Scrum suggests three roles: The team, ScrumMaster, and product owner; 

four ceremonies: the sprint planning meeting, Daily Scrum, sprint review meeting, and sprint retrospective meeting; 

 three artifacts: the product increment, product backlog, and sprint backlog.


## Principles of Lean Software Development

1. Eliminate Waste.

2. Build Quality In

3. Create Knowledge

4. Defer Commitment

5. Deliver Fast

6. Respect People

7. Optimize the Whole 



## CODE REVIEW


1. SOLID: Does the code follow SOLID principles?

```
i. Single responsibility principle
A class should only have a single responsibility, that is, only changes 
to onepart of the software's specification should be able to affect the 
specification of the class.


ii. Open–closed principle
"Software entities ... should be open for extension, but closed for modification."

iii. Liskov substitution principle
"Objects in a program should be replaceable with instances of their subtypes 
without altering the correctness of that program." 

iv. Interface segregation principle
"Many client-specific interfaces are better than one general-purpose interface.

v. Dependency inversion principle
One should "depend upon abstractions, concretions."

```

2. Check for null pointers where exceptions are needed.

3. Buffer Overflows

4. Integer overflows

5. Uninitialised objects

6. DRY: Are re-usble properties, routines being cached?

7. Formatting: Where are the spaces and line breaks? Are they using tabs or spaces? How are the curly braces laid out?

8. Style: Are the variables/parameters declared as final? Are method variables defined close to the code where they’re used or at the start of the method?

9. Naming: Do the field/constant/variable/param/class names conform to standards? Are the names overly short?

10. Test coverage: Is there a test for this code?

11. Race conditions: Any global polution? Leakages? Managing callbacks and side effects.

12. Design patterns: What design patterns are used in the new code? Any anti-patterns (in loops etc)

13. Lines of code: Are functions too long?

14. Using modern syntaxes (ES6): Arrow functions, default parameters, block scoping, template strings, spread operators, generator functions, destructuring etc

15. Optimisation in multi-threaded code

Also - https://github.com/kukuu/javascript/blob/master/citylit/tutorials/JavaScript-BestPractices.pdf
## Attributes of a good leader


1. Honesty and Integrity

2. Creativity and Innovation.

3. Accountability. 

4. Provide Source of Inspiration - Inspire Others.

5. Show Commitment and Passion

6. Good Communicator.

7. Have decision-Making Capabilities.

8. Lead by example

9. Delegation and Empowerment. 

10. Clearly defines goals

11. Helps to refine the knowledge base


## ECS and ECR

Amazon Elastic Container Registry (ECR) is a fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images. Amazon ECR is integrated with Amazon Elastic Container Service (ECS), simplifying your development to production workflow.


## Tracking the metrics / KPI (of the team)

Keeping track of certain metrics is an important step in making sure your company’s software engineering team is performing as efficiently and productively as possible. Here are some of the most essential metrics for developers to track:

1. Lead time

Lead time is a general measurement of the amount of time that passes from product concept to final delivery. 

2. Impact

Impact measures how much changes to the code affect the overall project. It is also a measurement of how those changes impact the engineers who make them. 

3. Churn

Churn is the percentage of time developers spend editing, adding to, or deleting their own code. A high code churn indicates rework and may mean something is wrong in the development process.

4. Productivity

This measures the amount of each engineer’s efficient code, or code that provides business value. An engineer creating a whole new solution or implementing sweeping code changes will likely deal with lots of trial and error with a low efficiency rate. An engineer who is making a lot of small changes with a low churn rate, however, is likely to have a higher efficiency rate.

4. Cycle time

Cycle time, part of lead time, is how long it takes to make a desired change to the software and put it into production. When a team is using DevOps and employing continuous integration, continuous delivery (CI/CD) practices, they can often measure cycle time in minutes rather than months.

5. Open and close rates

The open and close rate is the number of issues or problems developers report and fix or close over a period of time.

6. Down time analysis

Downtime analysis is a measure of the mean time between failures (MTBF) and mean time to recover/repair (MTTR). This evaluates how well software performs in a production environment.



## HIGH Performing engineering team

The Leader:

1. Drives goal execution and are a catalyst for team performance

2. Sets the bar for performance

3. Sets the tone

4. Communicate goals


The team:

1. People have solid and deep trust in each other and in the team's purpose - they feel free to express feelings and ideas

2. Everybody is working toward the same goals.

2. A quick turn around 

3. Minimum or no down time

3. A good ROI

4. Meeting deadlines, and hiting targets from planning

5. Achieving definition of done,(DoD) over SPRINT period. From requirement gathering to production.

6. Managing low fault levels. Less or minimum  return rates/complaints/bugs from users

7. Accountable for end to end delivery of the products and services. Holding each one responsible.


## SPRINT BURN DOWN CHARTS - KPI Measurement.

The Sprint Burndown Chart makes the work of the Team visible. It is a graphic representation that shows the rate at which work is completed and how much work remains to be done over the SPRINT period. The chart slopes downward over Sprint duration and across Story Points completed.

The outstanding work (or backlog) is often on the vertical axis, with time along the horizontal. That is, it is a run chart of outstanding work. It is useful for predicting/forecasting when all of the work will be completed

## SPRINT BURN UP CHARTS

Burn up chart shows how much work has been completed, and the total amount of work.

## ES5/ES6 

Features: 

Template strings

Destructuring 

Arrow functions

Setting Defaults

Block scopped - let/const 

Promises 

Spread operators

Generator functions 

Classes 

module imports

## REACT Life Cycle states

Lifecycle methods (with the exception of constructor) are hard to reason about. They add complexity to your app. Don’t use them unless you must.

1. Mounting

constructor:

The first thing that gets called is your component constructor, if your component is a class component. This does not apply to functional components i.e REACT Hooks (https://reactjs.org/docs/hooks-overview.html).

Most Common Use Case For Constructor: Setting up state, creating refs and method binding.

2. getDerivedStateFromProps 

When mounting, getDerivedStateFromProps is the last method called before rendering.
If you need to update your state based on a prop changing, you can do it here by returning a new state object.

Here’s some examples:

i. resetting a video or audio element when the source changes
ii. refreshing a UI element with updates from the server
iii. closing an accordion element when the contents change


Note: Even with the above cases, there’s usually a better way to do it. But getDerivedStateFromProps will have your back when worst comes to worst.


3. render

Rendering does all the work. It returns the JSX of your actual component. When working with React, you’ll spend most of your time here.

Most Common Use Case For Render: Returning component JSX.

4. componentDidMount

After we’ve rendered our component for the first time, this method is called.

If you need to load data, here’s where you do it. Don’t try to load data in the constructor.

Most Common Use Case for componentDidMount: Starting AJAX calls to load in data for your component.


5. shouldComponentUpdate

Typical React dogma says that when a component receives new props, or new state, it should update.

But our component is a little bit anxious and is going to ask permission first.

Here’s what we get — a shouldComponentUpdate method, called with nextProps as the first argument, and nextState is the second.

shouldComponentUpdate should always return a boolean. If you’re worried about wasted renders, (i.e Age authentication) shouldComponentUpdate is an awesome place to improve performance.


6. getSnapshotBeforeUpdate


Note it’s called between render and the updated component actually being propagated to the DOM. It exists as a last-chance-look at your component with its previous props and state.

You should either return null or a value from getSnapshotBeforeUpdate.

Most Common Use Case: Taking a look at some attribute of the current DOM, and passing that value on to componentDidUpdate.

7. componentDidUpdate

Now, our changes have been committed to the DOM.

In componentDidUpdate, we have access to three things: the previous props, the previous state, and whatever value we returned from getSnapshotBeforeUpdate.

Most Common Use Case for componentDidUpdate: Reacting  to committed changes to the DOM.

8. componentWillUnmount

Your component is going to go away. Maybe forever. It’s very sad.

Before it goes, it asks if you have any last-minute requests.

Here you can cancel any outgoing network requests, or remove all event listeners associated with the component.


9. getDerivedStateFromError

i.e Something broke. Not in your component itself, but one of its descendants.

10. ComponentDidCatch

It is triggered when an error occurs in a child component.

The difference is rather than updating state in response to an error, we can now perform any side effects, like logging the error.


 Note that componentDidCatch only works for errors in the render/lifecycle methods. If your app throws an error in a click handler, it will not be caught.

Most Common Use Case for componentDidCatch: Catching and logging errors.


## OutSystems platform

OutSystems is a low-code platform for the development of enterprise web and mobile applications, which run in the cloud, on-premises or in hybrid environments. The current version is 11, for both the paid and unpaid versions - developers are permitted personal cloud environments to use the platform without charge.

## JavaScript Design Patterns     

Developermust  strive to write maintainable, readable, and reusable code. Code structuring becomes more important as applications become larger. Design patterns prove crucial to solving this challenge - providing an organization structure for common issues in a particular circumstance.


i. Constructor Pattern

ii. Module Design Pattern

iii. Prototype Design Pattern

iv. Observer Design Pattern

v. Singleton


Also - https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know 

## System environmental Architectures

1. Multi tier - https://github.com/kukuu/AGILITY/blob/master/white-paper/restfulArchitecturalDesign-2.png

2. JWT - https://github.com/kukuu/AGILITY/blob/master/white-paper/restfulArchitecturalDesign-2.png

3. Micro service  - https://github.com/kukuu/Microservice-NodeJS/blob/master/microservice-snapshots/3.png

4. CI/CD - https://github.com/kukuu/AGILITY/blob/master/white-paper/CI-CDL-CDPL-pipeline.jpg

5. CI/CD with Jenkins - https://github.com/kukuu/CI-CD-pipeline-with-Jenkins

6. Orchestrating with Kubernetes - https://github.com/kukuu/AGILITY/blob/master/white-paper/kubernetes/1.png

### Software Module Design Pattern

JavaScript modules are the most prevalently used design patterns for keeping particular pieces of code independent of other components, and consistent. This provides loose coupling to support well-structured code.


For those that are familiar with object-oriented languages, modules are JavaScript "classes". One of the many advantages of classes is encapsulation - protecting states and behaviors from being accessed from other classes. The module pattern allows for public and private (plus the lesser-know protected and privileged) access levels.

Modules should be Immediately-Invoked-Function-Expressions (IIFE) to allow for private scopes - that is, a closure that protect variables and methods.

#### Revealing Module Pattern

A variation of the module pattern is called the Revealing Module Pattern. The purpose is to maintain encapsulation and reveal certain variables and methods returned in an object literal. The direct implementation looks like this.


### Prototype Design Pattern

 The Prototype design pattern relies on the JavaScript prototypical inheritance. The prototype model is used mainly for creating objects in performance-intensive situations.


 The objects created are clones (shallow clones) of the original object that are passed around. One use case of the prototype pattern is performing an extensive database operation to create an object used for other parts of the application. If another process needs to use this object, instead of having to perform this substantial database operation, it would be advantageous to clone the previously created object.


 To clone an object, a constructor must exist to instantiate the first object. Next, by using the keyword prototype variables and methods bind to the object's structure. Let's look at a basic example.

#### Revealing Prototype Pattern

Similar to Module pattern, the Prototype pattern also has a revealing variation. The Revealing Prototype Pattern provides encapsulation with public and private members since it returns an object literal.

### Observer Design Pattern

There are many times when one part of the application changes, other parts needs to be updated. In AngularJS, if the $scope object updates, an event can be triggered to notify another component. The observer pattern incorporates just that - if an object is modified it broadcasts to dependent objects that a change has occurred.

Another prime example is the model-view-controller (MVC) architecture; The view updates when the model changes. One benefit is decoupling the view from the model to reduce dependencies.


### Publish/Subscribe

The Publish/Subscribe pattern, however, uses a topic/event channel that sits between the objects wishing to receive notifications (subscribers) and the object firing the event (the publisher). This event system allows code to define application-specific events that can pass custom arguments containing values needed by the subscriber. The idea here is to avoid dependencies between the subscriber and publisher.


Subscribers in the publish/subscribe pattern are notified through some messaging medium, but observers are notified by implementing a handler similar to the subject.

In AngularJS, a subscriber 'subscribes' to an event using $on('event', callback), and a publisher 'publishes' an event using $emit('event', args) or $broadcast('event', args).


### Singleton

A Singleton only allows for a single instantiation, but many instances of the same object. The Singleton restricts clients from creating multiple objects, after the first object created, it will return instances of itself.

Finding use cases for Singletons is difficult for most who have not yet used it prior. One example is using an office printer. If there are ten people in an office, and they all use one printer, ten computers share one printer (instance). By sharing one printer, they share the same resources.


In AngularJS, Singletons are prevalent, the most notable being services, factories, and providers. Since they maintain state and provides resource accessing, creating two instances defeats the point of a shared service/factory/provider.

Race conditions occur in multi-threaded applications when more than one thread tries to access the same resource. Singletons are susceptible to race conditions, such that if no instance were initialized first, two threads could then create two objects instead of returning and instance. This defeats the purpose of a singleton. Therefore, developers must be privy to synchronization when implementing singletons in multithreaded applications.

## Unit Tests 

Unit tests don't work in current mainstream languages anyway because the status quo pervasively includes use of globally accessible mutable state, platform dependence, and violation of encapsulation.

1. It's the usual cost/benefit analysis that may restrain Developers from writing Unit Tests.

2. Cost: You need to spend time developing and maintaining the tests, and put resources into actually running them.

3. Benefits are well known (mostly cheaper maintenance/refactoring with less bugs).


If it's a throw away quick hack you know will never be re-used, unit tests might not make sense. 

### In practice:


Use TDD if you are implementing an isolated library-like module. If you’re not implementing an isolated library-like module, it’s best to implement first and then conduct the tests. The important thing is to make sure you don’t implement too much without writing any tests. Ideally you should implement incrementally, and at the end of each step, do the unit tests.

Write unit tests daily. Do not code for days, or worse weeks, and leave unit tests to the end. By that time, you will have lost most of the context. Writing unit tests is inherently dull; it’s a daunting task to write them for a week’s worth of code.


## SonarQube 

SonarQube (formerly Sonar) is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities on 20+ programming languages.

Code smell: They refer to any symptom in the source code of a program that possibly indicates a deeper problem

## DroneDeploy 

Is the leading cloud software platform worldwide for drone mapping and 3D modeling. The DroneDeploy mobile app allows you to fly your drone to make interactive maps and models. ... It works with many DJI drones such as Phantom 3, Phantom 4, Inspire 1 and 2, Mavic Pro, Matrice 100, 200 and 600 models.3 Mar 2019

## Statement of Work (SoW)

Statement of work is a detailed overview of the project in all its dimensions. It’s also a way to share what the project entails with those who are working on the project, whether they are collaborating or are contracted to work on the project. This includes vendors and contractors who are bidding to work on the project.

It’s also helpful to the project leader, as it provides a structure on which the project plan can be built on. The statement of work will also help to avoid conflicts in the project. With detail and clarity, the SoW helps keep everyone that’s involved in the project on the same page and works to leave confusion to a minimum.

## Traits of good Line Management & Essential Management  skills

Qualities of good line management:

1. Communicate well, be clear on vision to meet the needs of  both their employees  and bosses.

2. Emotional stability 

3. Enthusiasm 

4. Self assurance

5. The understanding by a manager that members of a team strive to reach  their own personal  goals, as well as their teams.

6. Finding time for team members to discuss their strength and work on their weaknesses. 

7. Empathy allows one to identify gaps.

8. When you  work in a team it gives you sense of belonging.


Essential Management  skills:

1. A good manager ensures everyone knows what their role is, and explains the expectations for that role.
Good management motivate people and are able to negotiate for resources and other support to achieve their goals.

2. Sets clear goals and expectations keep employees engaged, with something to work towards.

3. Provides the team with necessary tool to work and develop 

4. Stay away from the team to develop and empower them

5. Refines and reviews the success of the team

6. Planning

7. Communication 

8. Decision making 

9. Delegation

10. Problem solving

11. Motivation - https://github.com/kukuu/AGILITY/blob/master/motivation.md

12. Demonstraitng appropriate style of Management - https://github.com/kukuu/AGILITY/blob/master/ManagementStyles-InfluencingSkills.md

 And honesty and openness are skills that build trust


## Making Effective Decisions

1. Create a constructive environment.

2. Investigate the situation in detail.

3. Generate good alternatives.

4. Explore your options.

5. Select the best solution.

6. Evaluate your plan.

7. Communicate your decision, and take action.


## Influenceing with communication

Effective leaders don’t just command; they inspire, persuade, and encourage. Leaders tap the knowledge and skills of a group, point individuals toward a common goal, and draw out a commitment to achieve results.

To influence one needs to be clear about own goals, values, assertive and have a dynamic model to meet the challenges of the technology changing market. This requires an aggregation of a network of skills, a dynamic model and flexible governance.

The goal is to influence others, not manipulate them. Effective, ethical leaders use different approaches in different situations. Leaders need to understand why they are doing something, and be clear about their own values and goals when applying their influence skills. Influencing then comes from a place of authenticity and has the greatest impact.

1. Reasoning: Using logic to explain the importance of your ideas or projects. 

2. Consulting and collaborating: Asking for help or involving others can create an attachment to your idea. If your proposal benefits others, make sure they know about it.

3.  assertiveness

4. interpersonal

5. interactive

6. Support Initiatives

7. Attract Partnerships.

8. Avoid Coercion and Manipulation.

9. Acknowledge Opposing Points of View.

10. Focus on Effectiveness.

11. Show a Willingness to Learn


## Five Essential Project Management Skills

1. Communication. One of the most important skills for project managers is great communication. ...

2. Time Management. The ability to manage time and prioritize tasks is an essential characteristic of efficient 

3. Project managers. ...

4. Organizational Awareness. ...

5. Problem Solving. ...

6. Leadership.

## Skills Needed To Be A Successful Tech Leader

1. The ability to establish trust.

2. A strong vision for the future. 

3. Cohesion with company culture. 

4. Excellent problem-solving skills. 

5. A strong work ethic. 

6. An agreeable personality. 

7. Top-notch management skills.


## Management Styles

Different types of leadership styles exist in work environments. The culture and goals of an organization determine which leadership style fits the firm best, while personality differences often dictate which is most often used. Some companies offer several leadership styles within the organization, dependent upon the necessary tasks to complete and departmental needs.

### The Laissez-Faire Leader

A laissez-faire leader lacks direct supervision of employees and fails to provide regular feedback to those under his supervision. 

### The Autocrat

The autocratic leadership style allows managers to make decisions alone without the input of others. This leadership style benefits employees who require close supervision. Creative employees who thrive in group functions detest this leadership style.

### The Participative Leader

Often called the democratic leadership style, participative leadership values the input of team members and peers, but the responsibility of making the final decision rests with the participative leader.

Participative leadership boosts employee morale because employees make contributions to the decision-making process. It causes them to feel as if their opinions matter. 

### The Transactional Leader

Managers using the transactional leadership style receive certain tasks to perform and provide rewards or punishments to team members based on performance results. Managers and team members set predetermined goals together, and employees agree to follow the direction and leadership of the manager to accomplish those goals. The manager possesses power to review results and train or correct employees when team members fail to meet goals. Employees receive rewards, such as bonuses, when they accomplish goals.

### The Transformational Leader

The transformational leadership style depends on high levels of communication from management to meet goals. Leaders motivate employees and enhance productivity and efficiency through communication and high visibility and empowerment. This style of leadership requires the involvement of management to meet goals. Leaders focus on the big picture within an organization and delegate smaller tasks to the team to accomplish goals.

## Continuous Delivery (RRASc)

Reliable :: Repeatable :: Automation :: Source control
CD is the ability to get changes of all types including new features, configuration changes, bug fixes and experiments into production, or into the hands of users, safely and quickly in a sustainable way.

A logical extension of Continuous Integration, It is based on the use of smart automation. This is all about creating a repeatable and reliable process for delivering software. You have to automate pretty much everything in order to be able to achieve continuous delivery. Manual steps will get in the way or become a bottleneck. This goes for everything from requirements authoring to deploying to production.

The ultimate goal of continuous delivery is to minimise the iteration time of the code-test-deliver-measure experimentation cycle. Increasing deliverable throughput in this way is the key to not only more feature work being delivered but higher quality code as well. This might seem counter-intuitive at first but code is fixed and polished through that same cycle and less time spent on deployment is more time spent on designing quality code. - https://github.com/kukuu/AGILITY 


## How to motivate your team

Teams are the way that most companies get important work done. When you combine the energy, knowledge, and skills of a motivated group of people, then you and your team can accomplish anything you set your minds to.

Hi-lighted below are some mistakes leaders make that drive away their top talent. Rule of thumb, "Reflect on your behavior, fix these mistakes, and get ready to boost your team performance and motivation."
1. Pay your people what they are worth

When you set your employees' salaries, be sure that their pay is consistent with what other companies in your industry and geographic area are paying. Remember: 26 percent of engaged employees say that they would leave their current job for just a 5 percent increase in pay. Don't lose great people because you're underpaying them.

2. Provide them with a pleasant place to work

Everyone wants to work in an office environment that is clean and stimulating, and that makes them feel good instead of bad. You don't have to spend a lot of money to make an office a more pleasant place to be.

3. Offer opportunities for self-development

The members of your team will be more valuable to your organization, and to themselves, when they have opportunities to learn new skills. Provide your team with the training they need to advance in their careers and to become knowledgeable about the latest technologies and industry news.

4. Foster collaboration within the team

Encourage the members of your team to fully participate by inviting their input and suggestions on how to do things better. Ask questions, listen to their answers, and, whenever possible, implement their solutions. Ensure retrospectives are continuously engaged.

5. Encourage happiness

Happy employees are enthusiastic and positive members of the team, and their attitude is infectious. Keep an eye on whether or not your people are happy with their work, their employer, and you. If they're not, you can count on this unhappiness to spread.

4. Don't punish failure

We all make mistakes. It's part of being human. The key is to learn valuable lessons from those mistakes so we don't make them again. When members of your team make honest mistakes, don't punish them--instead, encourage them to try again. Note the principle of fail fast in Agile.

5. Set clear goals

Sizeable amount of Employees have reported that they wasted time at work because they weren't aware of what work was a priority, and what wasn't. As a leader, it's your job to work with the members of your team to set clear goals. And once you do that, make sure everyone knows exactly what those goals are, what their relative priority is, and what the team's role is in reaching them.

6. Don't micromanage

No one likes a boss who is constantly looking over her shoulder and second-guessing her every decision. Sizeable percent of employees have reported that they would rather take on unpleasant activities than sit next to a micromanaging boss. Provide your people with clear goals, and then let them figure out the best way to achieve them.

7. Avoid useless meetings

Meetings can be an incredible waste of time--the average professional wastes 3.8 hours in unproductive meetings each and every week. Create an agenda for your meetings and distribute it in advance. Invite only the people who really need to attend, start the meeting on time, and then end it as quickly as you possibly can.


## Steps to Helping Your Team Advance

1. Discuss Goals. The first step is to sit down with each team member and discuss her desired career goals. 

2. Identify Your Team's Development Gaps.

3. Establish Specific Training Objectives. 

4. Celebrate and Make it Fun.

## Essential Steps to Develop Your Team

1. Ensure that each person truly understands their role.

2. Provide training and development tools. 

3. Step away and let them do their job. 

4. Meet with team members regularly to discuss goals. ...

5. Game plan for their growth.


## Straightforward strategies to help improve teamwork in your startup today:

1. Lead by example.

2. Build up trust and respect.

3. Encourage socializing.

4. Cultivate open communication.

5. Clearly outline roles and responsibilities.

6. Organize team processes.

7. Set defined goals.

8. Recognize good work.


## Factors of Successful Teams: The Keys to Ensure High Team Performance

1. Domain Knowledge


2. Cohesiveness -  The first factor to consider is how cohesive members are with one another.

Once a team is highly cohesive, a member’s commitment and willingness to strive for excellence thrives. Team cohesion affects the extent to which members like one another, get along with each other, and trust and respect one another’s abilities and opinions. 

Although these characteristics are difficult to observe, managers can look for signs that team members are well-acquainted past superficial meet-and-greet topics. Managers can also determine whether team members equally participate in group discussions and activities rather than forming cliques or subgroups of cohesive units.

3. Communication -  Efficient communication mechanisms are crucial to develop effective teams.

4. Groupthink -  This is when a group in a team tend to suppress the thinking and development of others.

Other signs of groupthink include individual conformity, apathy toward team goals and outcomes, peer-pressure exerted by leaders within the team, and discussions that tend to be one-sided.

5. Homogeneity -  Having the right ballanced composed members in the team. 

It is the extent to which members are similar or different to one another. The difficulty for most project managers is finding the right balance between overly homogenous and overly heterogeneous teams. When evaluating team homogeneity, a manager can consider similarities and differences in personal characteristics, education, skills, abilities, generational backgrounds, cultural background, and income levels.

6. Role Identity -  Role identity is the extent to which members are capable of assuming different roles throughout the team structure, thus diversifying efforts and developing subject matter experts. Delegating by having experts in different disciplines . Empowerment. 

7. Stability -  Teams that have higher turnover rates experience higher levels of group cohesion, better communication methods, and more effective role identity.

8. Team Size - By evaluating a team’s size, managers are able to maximize productivity to ensure high levels of team performance. The greater number of members within a team the more resources available to achieve a goal. However, as team size increases, so does the number of conflicts resulting in decreased levels of cohesion and inefficient productivity. To evaluate whether a team is too large or small, managers must consider how effectively and harmoniously members work together and whether the required tasks are being efficiently accomplished by all members of the team.

## Team building objectives

1. Learn to work as a team

2. Re-assess your team's goals and direction

4. Communicate better as a team

5. Give your team a boost of energy

6. Create trust amongst team members

7. Recognise individual strengths, styles and skills

8. Keep lines of communication flexible

9. Ensure tolerance

10. Encourage sharing of ideas

11. Allow for differences


## Achieving CD

Automation::Reliable::Elastic::Traceable
Repeatable, Automation, Source Control

1. The process for releasing/deploying software MUST be repeatable and reliable. 

2. Automate everything!

3. If somethings difficult or painful, do it more often.

4. Keep everything in source control

5. Done means “released”.

6. Build quality in! 

7. Everybody has responsibility for the release process

8. Improve continuously

## Micro-services

A micro-service is a self contained process that provides a unique business capability.

Microservices architecture is an approach to application development in which a large application is built as a suite of modular services. Each module supports a specific business goal and uses a simple, well-defined interface to communicate with other sets of services.

When you choose to build your application as a set of microservices, you need to decide how your application’s clients will interact with the microservices. With a monolithic application there is just one set of (typically replicated, load‑balanced) endpoints. In a microservices architecture, however, each microservice exposes a set of what are typically fine‑grained endpoints.

Services must handle requests from the application’s clients. Furthermore, services must sometimes collaborate to handle those requests. They must use an inter-process communication protocol. Use asynchronous messaging for inter-service communication. Services communicating by exchanging messages over messaging channels. Examples of asynchronous messaging technologies are Apache Kafka and RabbitMQ.

Micro services communicate via REST or Messaging services. Communication is always stateless.
Every micro service is federated (Has its own data model and data). Each Request/Response is stateless (Independent). More instances of the microservic cn be added.

Stateless communication allows the micro service to scale. Add more instances.

Microservices application hardly breaks, as you can set up defaults as part of the architecture.

## Benefits of Micro-services:

1. Loose coupling since it decouples client from services

2. Improved availability since the message broker buffers messages until the consumer is able to process them

3. Supports a variety of communication patterns including request/reply, notifications, request/async response, publish/subscribe, publish/async response etc

## Micro-services drawbacks:

i. Additional complexity of message broker, which must be highly available

ii. Request/reply-style communication is more complex

iii. Client needs to discover location of message broker

iv. Need to mitigate performance

v. Log monitoring

## Seeting up a  microservice team

1.	Set up feature teams  that can possibly set up a new service in under four hours. What this means
	is Developing services should not   require knowledge of the infrastructure and changing 
	infrastructure should not require detailed knowledge of the services running on it. 
	If we need to change the hostname or port a service runs on it should require no changes
	to the service itself.

2.	All project configuration—from build process to health monitoring—must be contained within the 
	project repository. Anything else introduces hidden dependencies for deployment that threaten
	to break the pipeline and require specialist knowledge to debug.

3.	The above configuration should be declarative and not require adding dependencies to the project.

4.   Use Containerisation

## Implementing a Gateway

It makes sense,  to build the API Gateway on a platform that supports asynchronous, nonblocking I/O. There are a variety of different technologies that can be used to implement a scalable API Gateway.

On the JVM you can use one of the NIO‑based frameworks such Netty, Vertx, Spring Reactor, or JBoss Undertow. 

One popular non‑JVM option is Node.js, which is a platform built on Chrome’s JavaScript engine. 

Another option is to use NGINX Plus. NGINX Plus offers a mature, scalable, high‑performance web server and reverse proxy that is easily deployed, configured, and programmed. NGINX Plus can manage authentication, access control, load balancing requests, caching responses, and provides application‑aware health checks and monitoring.


Writing API composition code using the traditional asynchronous callback approach quickly leads you to callback hell. The code will be tangled, difficult to understand, and error‑prone. A much better approach is to write API Gateway code in a declarative style using a reactive approach. Examples of reactive abstractions include Future in Scala, CompletableFuture in Java 8, and Promise in JavaScript. There is also Reactive Extensions (also called Rx or ReactiveX), which was originally developed by Microsoft for the .NET platform. Netflix created RxJava for the JVM specifically to use in their API Gateway. There is also RxJS for JavaScript, which runs in both the browser and Node.js. Using a reactive approach will enable you to write simple yet efficient API Gateway code.


## Handling Partial Failures in API Gateways


Another issue you have to address when implementing an API Gateway is the problem of partial failure. This issue arises in all distributed systems whenever one service calls another service that is either responding slowly or is unavailable.

The API Gateway should never block indefinitely waiting for a downstream service. However, how it handles the failure depends on the specific scenario and which service is failing. For example, if the recommendation service of the application is unresponsive in the product details scenario, the API Gateway should return the rest of the product details to the client since they are still useful to the user. The recommendations could either be empty or replaced by, for example, a hardwired top ten list.

If, however, the product information service is unresponsive then API Gateway should return an error to the client.

The API Gateway could also return cached data if that was available. The data can be cached by the API Gateway itself or be stored in an external cache such as Redis or Memcached. By returning either default data or cached data, the API Gateway ensures that system failures do not impact the user experience.

A very good robust and scalable API Gateway must time out calls that exceed the specified threshold. It implements a circuit breaker pattern, which stops the client from waiting needlessly for an unresponsive service, can be added to the model's implementation. If the error rate for a service exceeds a specified threshold, it could trip a circuit breaker and all requests will fail immediately for a specified period of time. The module should define a fallback action when a request fails, such as reading from a cache or returning a default value.

For most microservices‑based applications, it makes sense to implement an API Gateway, which acts as a single entry point into a system. The API Gateway is responsible for request routing, composition, and protocol translation. It provides each of the application’s clients with a custom API. The API Gateway can also mask failures in the backend services by returning cached or default data.

## Containerisation

Source code of any program cannot fully describe the function of that program without the context it will be compiled and run in. Most unexpected behaviour during deployment comes from build environments being different than expected. To make deployment repeatable, we need to make a program’s context repeatable. That’s where Docker and Kubernetes comes in.

Docker essentially allows you to specify a “source code” for a program’s context that can then be “compiled” to an image and run as a container. This means that once we have tested an image we can have high confidence that it will perform equally well in every environment it is deployed to.

Additionally, Docker allows you to specify deploy configurations made up of multiple containers all linked in a private network and DNS that allows services that depend strongly on each other to be deployed and scaled together.

To be fully context-agnostic, deployment should be able to happen to any host on the network on whatever port the host happens to have free. This presents a challenge: how do services link up when their network locations are fluid? You need a reverse proxy (like nginx) and a way to keep its configuration up to date in a changing service landscape. You will need a Consul to store and manage service states.

## Deployment steps for Docker Container:

1.	Build Docker image.

2.	Test that image in isolation.

3.	Push that image to the in-house image registry.

4.	Pull all images you need to deploy linked.

5.	Deploy them to a test environment.

6.	Run automated tests against the container system.

7.	Upload service configuration to Consul API (if changed).

8.	Deploy the containers to all hosts, tagged with the offline colour.

9.	Wait until they are all responding and passing automated checks.

10.	Flip environment alias to point at the offline colour.

11.	The new build is now online.

## Docker File:  Configuration infrastructure code

```
FROM node: latest

COPY . /src

WORKDIR  /src

RUN npm install --production

EXPOSE 3000

CMD  npm start

```


## Micro-service Docker Compose file - For a NodeJS Micro-service

```
version: '3'

services: 
    web: 
      build: './web'
      ports:
        - "3000: 3000"

    serach: 
      build: './serach'
      ports:
        - "3001: 3000"
      depends_on: 
        - db
      environment: 
        - MONGO_DB_URI = mongo://db/microservices

    books: 
      build: './books'
      ports: 
        - "3002: 3000"
      depends_on: 
        - db
      environment: 
        - MONGO_DB_URI=mongodb://db/microservices

    videos:
      build: './videos'
      ports: 
        - "3003: 3000"
      depends_on: 
        - db
      environment: 
        - MONGO_DB_URI = mongo://db/microservices

    db: 
      image: mongo:latest
      ports: 
        - "27018:27018"

    nginx: 
      image: nginx:latest
      ports: 
        - "8080"
      volumes: 
        - ./web/public:/svr/www/static
        -  ./default/.conf:/etc/nginx/conf.d/default.conf
      depends_on:
          - web
          - serach
          - books
          - videos

```

## Web Services

A web service is a collection of open protocols and standards used for exchanging data between applications or systems over the internet and uses a standardized XML messaging system. XML is used to encode all communications to a web service. For example, a client invokes a web service by sending an XML message, then waits for a corresponding XML response.

As all communication is in XML, web services are not tied to any one operating system or programming language - Java can talk with Perl; Windows applications can talk with Unix applications.

Web services are self-contained, modular, distributed, dynamic applications. These applications can be local, distributed, or web-based. Web services are built on top of open standards such as TCP/IP, HTTP, Java, HTML, and XML.

## Differences between SOA and Micro-services

The core difference between SOA and microservices lies in the size and scope. Microservices must be independently deployable, whereas SOA services are often implemented in deployment monoliths. Classic SOA is more platform driven, so microservices offer more choices in all dimensions.

Features of SOA:

1. Boundaries are explicit

2. Services are autonomous

3. Services share schema and contract, not class

4. Service compatibility is based on policy


## Cloud Computing - Architecting for High Availability

1. Design for Failure - Horizontal scaling : Elastic IPs, EBS, EC2, Cloud Watch

2. Multiplle Availability Zones - Offset natural disaster (Low prone disaster zones)

3. Scaling

4. Loose Coupling

5. Self Healing (Policy - Responsive to Peaks[Calculated and abrupt])


## Functional and NFR (Non functional requirements)

1. Functional

Functional requirement (FR) focus on the behavioral aspects.

2. NFR

NFRs are the requirements defined to cover the operational aspects of a product or an app.

Efficiency 

Portability 

security 

Reliability 

Usability

Caching

## Cloud Architectures

1. SaaS (Software as a Service) applications are designed for end-users, delivered over the web.

SaaS is a software distribution model in which applications are hosted by a vendor or service provider and made available to customers over a network, typically the Internet.

With Saas model you are provided with access to application softwares often referred to as on-demand softwares. You don't have to worry about the installation, setup and running of the application. Service provider will do that for you. You just have to pay and use it through some client.

Example: Google Apps, Microsoft Office 365.


2. PaaS

PaaS (Platform as a Service) is the set of tools and services designed to make coding and deploying those applications quick and efficient over the Internet.

The model is a category of cloud computing services that provides a platform allowing customers to develop, run, and manage web applications without the complexity of building and maintaining the infrastructure typically associated with developing and launching an app - via the browser.

Examples: AWS Elastic Beanstalk, Windows Azure, Heroku, Force.com, Google App Engine, and Apache Stratos. IaaS (Infrastructure as a Service), is the hardware and software that powers it all – servers, storage, networks, operating system.


3. IaaS

IaaS provides you the computing infrastructure, physical or (quite often) virtual machines and other resources like virtual-machine disk image library, block and file-based storage, firewalls, load balancers, IP addresses, virtual local area networks etc.

Examples: Amazon EC2, Windows Azure, Rackspace, Google Compute Engine. Additional points to note:

AWS(Amazon web services) is a complete suite which involves a whole bunch of useful web services. Most popular are EC2 and S3 and they belong to IaaS s

Windows Azure is both a PaaS and IaaS.


## DevOps

DevOps is a software development approach which involves continuous development, continuous testing, continuous integration, continuous deployment, and continuous monitoring of the software throughout its development lifecycle.

Meanwhile, in every step, if there is an error, you can shoot an email back to the development team so that they can fix it. Then they will push it into the version control system and it goes back into the pipeline.

Using Jenkins 

From Git, Jenkins pulls the code and then Jenkins moves it into the commit phase, where the code is committed from every branch. The build phase is where we compile the code. If it is Java code, we use tools like maven in Jenkins and then compile that code, which can be deployed to run a series of tests. These test cases are overseen by Jenkins again.

Then, it moves on to the staging server to deploy it using Docker. After a series of unit tests or sanity tests, it moves on to production.

Docker is just like a virtual environment in which we can create a server. It takes a few seconds to create an entire server and deploy the artifacts we want to test. But here the question arises:

Why do we use Docker?

As we said earlier, you can run the entire cluster in a few seconds. We have a storage registry for images where you build your image and store it forever. You can use it anytime in any environment which can replicate itself.

## Continuous Integration and Continuous Delivery

1. Maintain a code repository.

2. Automate your build.

3. Make your build self-testing.

4. Daily commits to the baseline by everyone on the team.

5. Every commit (to the baseline) should be built.

6. Keep your builds fast.

7. Clone the production environment and test there.

## Quicksort 

This is one of the most efficient methods for sorting an array in computer science.

Quicksort works by picking an element from the array and denoting it as the “pivot.” All other elements in the array are split into two categories — they are either less than or greater than this pivot element.

Each of the two resulting arrays (array of values less-than-the-pivot and array of values greater-than-the-pivot) is then put through that very same algorithm. A pivot is chosen and all other values are separated into two arrays of less-than and greater-than values.

Eventually, a sub-array will contain a single value or no value at all, as there will be no more values with which to compare it. The rest of the values were all denoted to be “pivots” at some previous point and did not trickle down to this lowest sub-array. At that point, the values will be sorted, as all values have now been declared as less than or greater than all other values in the array.

## Using es6 Spread operator

```
export default function sum(...figures) {
  return figures.reduce((total, current) => {
    return total + current;
  });
}

```

## JAM Stack

JAMSTACK  is a set of best practices and not a technology.
Focuses on Build Time Rendering (changes responsibility of the backend). Other than Server Side. No need for backend to (publish) server side  rendering. The backend will contune to focus on the API Layer

Technologies: Gatsby, GraphQL (gives a consistent API Layer). Keeps the Backend decoupled from the backend. No worries abot passing JSON up and down. You can configure the plugins for GrphQL to do this.

Great for Blogs, eCommerce, Static Contents


Downsides of JAM Stack
i. Not good for Big DATA and Analytics
ii. Not good for Real Time Systems
iii. Non Developer interactions


## REFS in REACT

refs are used to get reference to a DOM(Document Object Model) node or an instance of a component in a React Application i.e. refs would return the node we are referencing .

## Monolith to Microservice - Strategy


Note any changes should not change the user experience. Just the underlying architecture. Changing architecture can allow the product serve multiple channels, IMPROVE USER EXPERIENCE AND ENHANCE EFFICIENCY.


1. Define Business context

2. Security

3. Technology

4. Architecture

5. Configuration Management

6. Monitoring

7. Aggregating logs

8. Deployment

9. Documentation

.................

Implementation

In the conversion we use a dispatcher proxy to the monolithic (legacy system) to capture requests and direct it to the micro-service
ii. Use Apache config file to do re-write rule for the new urls (end points) - Apache's re-write engine switched on. Each URL with a string in it will be re-written.


## Data-driven 

Data-driven approach is when a team makes strategic decisions based on data analysis and interpretation, rather than by intuition or by personal experience. The process of democratising data means making data accessible to as many people as possible within a company.

-  Data-driven learning: A learning approach driven by research-like access to data. 

- Data-driven science, an interdisciplinary field of scientific methods to extract knowledge from data.


## Parcel

An out of the box support for JS, CSS, HTML, file assets, and more (perfect for React)

## Leadership & Management

The main difference between the two is that leaders have people that follow them, while managers have people who simply work for them. ... For any company to be successful, it needs management that can plan, organise and coordinate its staff, while also inspiring and motivating them to perform to the best of their ability.

https://www.forbes.com/sites/williamarruda/2016/11/15/9-differences-between-being-a-leader-and-a-manager/#67a42d494609


## Improving your JavaScript performance

i. Learn the techniques of asynchronous programming.

ii. Pass local variables. 

iii. Use gzip compression. 

iii, Keep code small and light.

iv. Avoid unwanted loops.

v. Keep DOM access to a minimum. 

vi. Cache objects to increase performance. 


https://www.monitis.com/blog/8-tips-for-improving-your-javascript-performance/

## GraphQL

Specifically, GraphQL allows you to evolve your API naturally without versioning, it provides workable documentation, it avoids the problems of over- and under-fetching, and it offers a convenient way to aggregate data from multiple sources with a single request.

Fetching data with GraphQL queries: 

When an application needs to retrieve data from a GraphQL API, it has to send a query to the server in which it specifies the data requirements. Most GraphQL servers accept only HTTP POST requests where the query is put into the body of the request. Note however that GraphQL itself is actually transport layer agnostic, meaning that the client-server communication could also happen using other networking protocols than HTTP.

Here’s an example query that a client might send in an Instagram-like application:

```
query {
  feed {
    id
    imageUrl
    description
  }
}

```

The keyword query in the beginning expresses the operation type. Besides query, there are two more operation types called mutation and subscription. Note that the default operation type of a request is in fact query, so you might as well remove it from the above request. feed is the root field of the query and everything that follows is called the selection set of the query.
When a server receives the above query, it will resolve it, i.e. collect the required data, and package up the response in the same format of the query. Here’s what a potential response could look like:

```

{
  "data": {
    "feed": [
      {
        "id": "1",
        "description": "Nice Sunset",
        "imageUrl": "http://example.org/sunset.png"
      },
      {
        "id": "2",
        "description": "Cute Cats",
        "imageUrl": "http://example.org/cats.png"
      }
    ]
  }
}


```
The root of the returned JSON object is a field called data as defined in the official GraphQL specification. The rest of the JSON object then contains exactly the information that the client asked for in the query. If the client for example hadn’t included the imageUrl in the query’s selection set, the server wouldn’t have included it in its response either.

In case the GraphQL request fails for some reason, e.g. because the query was malformed, the server will not return the data field but instead return an array called errors with information about the failure. Notice that it can happen that the server returns both, data and errors . This can occur when the server can only partially resolve a query, e.g. because the user requesting the data only had the access rights for specific parts of the query's payload.


Creating, updating and deleting data with GraphQL mutations:

Most of the time when working with an API, you’ll also want to make changes to the data that’s currently stored in the backend. In GraphQL, this is done using so-called mutations. A mutation follows the exact same syntactical structure as a query. In fact, it actually also is a query in that it combines a write operation with a directly following read operation. Essentially, the idea of a mutation corresponds to the PUT, POST and DELETE calls that you would run against a REST API but additionally allows you to fetch data in a single request.

Let’s consider an example mutation to create a new post in our sample Instagram app:

```
mutation {
  createPost(description: "Funny Birds", imageUrl: "http://example.org/birds.png") {
    id
  }
}


Instead of the query operation type, this time we’re using mutation. Then follows the root field, which in this case is called createPost. Notice that all fields can also take arguments, here we provide the post’s description and imageUrl so the server knows what it should write into the database. In the payload of the mutation we simply specify the id of the new post that will be generated on the server-side.

```
After the server created the new post in the database, it will return the following sample response to the client:

```
{
  "data": {
    "createPost": {
        "id": "1"
      }
  }
}
```

The Schema Definition Language (SDL)

GraphQL has a type system that’s used to define the capabilities of an API. These capabilities are written down in the GraphQL schema using the syntax of the GraphQL Schema Definition Language (SDL). Here’s what the Post type from our previous examples looks like:


```


type Post {
  id: ID!
  description: String!
  imageUrl: String!
}

```


https://medium.com/@childsmaidment/getting-started-with-redux-and-graphql-8384b3b25c56

https://docs.expo.io/versions/latest/guides/using-graphql/?redirected 


## Apollo GraphQL

Apollo Client is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL. ... Apollo Client can be used in any JavaScript frontend where you want to use data from a GraphQL server.

The client is designed to help you quickly build a UI that fetches data with GraphQL, and can be used with any JavaScript front-end.

## RUST

Rust is a multi-paradigm system programming language focused on safety, especially safe concurrency. ... Rust was originally designed by Graydon Hoare at Mozilla Research, with contributions from Dave Herman, Brendan Eich, and others.

While Rust is a general purpose language, you could write your next web app in Rust, but you wouldn't be best experiencing what it has to offer. Rust is a low-level language, best suited for systems, embedded, and other performance critical code.

## Jenkins

Used for:

i. Static code analysis
ii. Automated testing
iii. Deploying artefacts
Can be run as a Docker Container.

PHP Plugins:

i. PHP Unit
ii. PHP CodeSniffer
iii. PHPMD
iv. PHPCPD
PHP_Depend

Use composer require -dev to find all packages here https://packagist.org/_

## Implode()

The implode() function returns a string from the elements of an array. Note: The implode() function accept its parameters in either order. However, for consistency with explode(), you should use the documented order of arguments. However, it is recommended to always use two parameters for backwards compatibility.


## Types of injection Attacks

https://dzone.com/articles/what-are-injection-attacks

i. XSS (Cross Site Scripting) - Inject arbitrary JS into a legitimate website/application, which is executed in the users browser.

 

ii. CRLF (Carriage Return Line Feed) - Injection of unexpected CRLF.

Injects an unexpected CRLF (Carriage Return and Line Feed) character sequence used to split an HTTP response header and write arbitrary contents to the response body, including Cross-site Scripting (XSS).



iii. Email injection (Mail Command SMTP) - Injects SMTP/IMAP statements into an email server

Potential Impact 

iv Host Header Injection - Abuses the implicit trust of the HTTP host Header to poison passsword re-set functionality.



v LDAP injection - Injects LDAP (Lightweight  Directory Access Protocol) statements to execute arbitrary LDAP commands including granting permissions and modifying contents of an LDAP tree.


vi. SQLi (SQL injection) - Injects SQL commands that can read or modify data from a database. Advanced variations of this attack can be used to write arbitrary files to the server and even execute OS commands which may lead to full system compromise.



vii. XPath injection - Inject data into an application to execute crafted XPath queries which can be used to access unauthorized data and bypass authentication.

 

viii. Code injection - Injects application code which can execute operating system commands as the user running the web application.



vix. CSRF (XSRF)

Cross-Site Request Forgery (CSRF) is an attack that forces an end user to execute unwanted actions on a web application in which they're currently authenticated. CSRF attacks specifically target state-changing requests, not theft of data, since the attacker has no way to see the response to the forged request.

A csrf token is generated for the forms and Must be tied to the user's sessions. It is used to send requests to the server, in which the token validates them. This is one way of protecting against csrf, another would be checking the referrer header.


## What is the difference between XSS and CSRF?

Fundamental difference is that CSRF (Cross-site Request forgery) happens in authenticated sessions when the server trusts the user/browser, while XSS (Cross-Site scripting) doesn't need an authenticated session and can be exploited when the vulnerable website doesn't do the basics of validating or escaping input.

## XSS Attack 

The concept of XSS is to manipulate client-side scripts of a web application to execute in the manner desired by the malicious user. Such a manipulation can embed a script in a page that can be executed every time the page is loaded, or whenever an associated event is performed.

XSS is a web-based attack performed on vulnerable web applications.
In XSS attacks, the victim is the user and not the application.
In XSS attacks, malicious content is delivered to users using JavaScript.

XSS vulnerabilities gives the attackers the capability to inject client-side scripts into the application, for example to re-direct users to malicious websites

It can be used to hi-jack user accounts, spread worms, and Trojans, access browser history and clipboard contents, control the browser remotely, and scan and exploit online appliances and applications.

Example

Cyber criminals exploited a persistent XSS vulnerability in the eBay website to embed malicious JavaScript in legitimate listings, redirecting them to spoofed eBay login paes for phishing user credentials.


Featurs of XSS
.............

i. XSS is a web-based attack performed on vulnerable web applications.

ii.In XSS attacks, the victim is the user and not the application.

iii. In XSS attacks, malicious content is delivered to users using JavaScript.

https://www.veracode.com/security/xss



Examples
For example, the attacker could send the victim a misleading email with a link containing malicious JavaScript. If the victim clicks on the link, the HTTP request is initiated from the victim's browser and sent to the vulnerable web application.


## How to Prevent an SQL Injection

The only sure way to prevent SQL Injection attacks is 

i. Input validation and parametrized queries including prepared statements. The application code should never use the input directly. 

ii. The developer must sanitize all input, not only web form inputs such as login forms. 

iii. They must remove potential malicious code elements such as single quotes. 

iv. It is also a good idea to turn off the visibility of database errors on your production sites. Database errors can be used with SQL Injection to gain information about your database.

https://www.acunetix.com/websitesecurity/sql-injection2/


## Selenium

Selenium is a portable framework for testing web applications. Selenium provides a playback (formerly also recording) tool for authoring functional tests without the need to learn a test scripting language (Selenium IDE).

Using Selenium type of testing can be done are:

Functional Testing.

Regression Testing.

Sanity Testing.

Smoke Testing.

Responsive Testing.

Cross Browser Testing.

UI testing (black box)

Integration Testing.

https://www.youtube.com/watch?v=_JNeiGbAgL4


## jMeter


Apache JMeter is open source software, a 100% pure Java desktop application, designed to load test functional behavior and measure performance of web sites. It was originally designed for load testing web applications but has since expanded to other test functions.


## JUnit

Junit is widely used testing framework along with Java Programming Language. You can use this automation framework for both unit testing and UI testing.it helps us define the flow of execution of our code with different Annotations.7 D


## Black Box Testing

Black Box Testing is a software testing method in which the internal structure/ design/ implementation of the item being tested is NOT known to the tester. White Box Testing is a software testing method in which the internal structure/ design/ implementation of the item being tested is known to the tester.


This method of test can be applied virtually to every level of software testing: unit, integration, system and acceptance.

## White Box Testing

Statement Coverage – ensure every single line of code is tested.
Branch Coverage – ensure every branch (e.g. true or false) is tested.
Path Coverage – ensure all possible paths are tested.

## Challenges to integrating heterogenous services

The increase need for services to handle a plethora of business needs within the enterprise landscape has yielded to an increase in the development of heterogeneous services across the digital world. In today’s digital economy, services are the key components for communication and collaboration amongst enterprises internally and externally. 

Since Internet has stimulated the use of services, different services have been developed for different purposes prompting those services to be heterogeneous due to incompatibles approaches relied upon at both conceptual and exploitation phases. The proliferation of developed heterogeneous services in the digital world therefore comes along with a range of challenges more precisely in the integration layer. 

Traditionally, integration is achieved by using gateways, which require considerable configuration effort. Many approaches and frameworks have been developed by different researchers to overcome these challenges, but up to date the challenges of integration heterogeneous services with minimal user-involvement still exist. 


##  SMACSS

Smacss (Scalable and Modular Architecture for CSS) is a style guide that follows five simple categories. SMACSS is a way to examine your design process and to fit those rigid frameworks into a flexible thought process.

## Headless CMS

(Crafter/Contentfull/Prismic/Storyblok)

How does a headless CMS work?

A headless CMS is a back-end only content management system (CMS) built from the ground up as a content repository that makes content accessible via a RESTful API for display on any device. 

A headless CMS remains with an interface to add content and a RESTful API (JSON, XML) to deliver content wherever you need it.

Other than by using a regular/monolithic CMS, one website can’t be built only with a headless CMS. A headless CMS separated the head from its stack and therefore lacks this point by design. Therefore, the developer must craft the website by his- or herself and use the Content Delivery API of the headless CMS to load the content.

Creating the whole website on their own seems like a big task on the list, but by decoupling the CMS from the front-end a developer can choose any technology he is already familiar with and does not need to learn the technology for that specific CMS. Another big bonus is the fact that one developer can also focus on their own work without handling the bugs of an already existing stack of technology - therefore it is easier to optimize pages for googles pagespeed and even relaunch parts of the website.

DRUPAL with JSON API to Headless CMS - https://www.youtube.com/watch?v=tDj41kSjKvA

### APIs

There are following REST-APIs available at the endpoint api.storyblok.com/v1/cdn.

Stories, For receiving the content entries

Tags, For receiving tags (ex. building a tagcloud)

Links, For receiving the mappings of the story links

Datasource_entries, For receiving datasources (key value pairs)
The endpoint is made for highspeed delivery and therefore the content is cached in a CDN. If you want to receive the uncached version of your content you need to provide a version parameter in the URL. This parameter is cache_version and usually has a timestamp (The SDKs automatically ups the version timestamp).

Resource - 

i. https://www.storyblok.com/tp/headless-cms-explained

ii. https://www.youtube.com/watch?v=FOZtRzY5x8E

iii. REST Frameworks for node

a. HapiJS
b. Loopback

### SDKs

Development can be made easier with the use of an SDK. The following SDKs are currently available, with more to be released soon:


Javascript

Node.js

Ruby


```
\<body>
<script src="https://app.storyblok.com/f/storyblok-latest.js?t=hZ9t5mLywGe41ragtcSLgwtt">
</script>
<script>
  // Get the content of the current page
  storyblok.get({slug: 'home', version: 'draft'}, function(data) {
    console.log(data.story)
  })

  // Get multiple content entries from a folder called "news"
  storyblok.getAll({starts_with: 'story', version: 'draft'}, function(data) {
    console.log(data.stories)
  })
</script>
</body>


```


### Optimising SQL queries

Optimize queries based on the query optimization guidelines
Follow the SQL best practices to ensure query optimization:

1. Index all the predicates in JOIN, WHERE, ORDER BY and GROUP BY clauses.
WebSphere Commerce typically depends heavily on indexes to improve SQL performance and scalability. Without proper indexes, SQL queries can cause table scans, which causes either performance or locking problems. It is recommended that all predicate columns be indexed. The exception being where column data has very low cardinality.

2. Avoid using functions in predicates.
The index is not used by the database if there is a function on the column. For example:
SELECT * FROM TABLE1 WHERE UPPER(COL1)='ABC'Copy
As a result of the function UPPER(), the index on COL1 is not used by database optimizers. OracleIf the function cannot be avoided in the SQL, you need to create a function-based index in Oracle or generated columns in DB2 to improve performance.


3. Avoid using wildcard (%) at the beginning of a predicate.
The predicate LIKE '%abc' causes full table scan. For example:
SELECT * FROM TABLE1 WHERE COL1 LIKE '%ABC'Copy
This is a known performance limitation in all databases.

4. Avoid unnecessary columns in SELECT clause.
Specify the columns in the SELECT clause instead of using SELECT *. The unnecessary columns places extra loads on the database, which slows down not just the single SQL, but the whole system.
Use inner join, instead of outer join if possible.
The outer join should only be used if it is necessary. Using outer join limits the database optimization options which typically results in slower SQL execution.
DISTINCT and UNION should be used only if it is necessary.
DISTINCT and UNION operators cause sorting, which slows down the SQL execution. Use UNION ALL instead of UNION, if possible, as it is much more efficient.
OracleOracle 10g and 11g requires that the CLOB/BLOB columns must be put at the end of the statements.
Otherwise, it causes failure when the input value size is larger than 1000 characters.


5. The ORDER BY clause is mandatory in SQL if the sorted result set is expected.
The ORDER BY keyword is used to sort the result-set by specified columns. Without the ORDER BY clause, the result set is returned directly without any sorting. The order is not guaranteed. Be aware of the performance impact of adding the ORDER BY clause, as the database needs to sort the result set, resulting in one of the most expensive operations in SQL execution.

### Leads

i. Gatsby & Contentful - https://www.youtube.com/watch?v=fY3mBJSDA44 (6 episodes)  | https://www.youtube.com/watch?v=L9Uv_bLSaP4


## Flexbox against CSS Grid

CSS Grid Layout is a two-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a one-dimensional system (either in a column or a row). A core difference between CSS Grid and Flexbox is that — CSS Grid's approach is layout-first while Flexbox' approach is content-first.

When working on either element (row or column), you are most associated with the content. Flexbox, here, gives you more flexibility.

Grid is much newer than Flexbox and has a bit less browser support. That's why it makes perfect sense if people are wondering if CSS grid is here to replace Flexbox. ... Flexbox can do things Grid can't do. They can work together: a grid item can be a flexbox container.


## Common OAuth 2.0 grant types

i. Authorization Code.

ii. Implicit.

The Implicit grant type is a simplified flow that can be used by public clients, where the access token is returned immediately without an extra authorization code exchange step. It is generally not recommended to use the implicit flow. 

The Implicit Grant is an OAuth 2.0 flow that client-side apps use in order to access an API

Based on the needs of your application, some grant types are more appropriate than others. Auth0 provides many different authentication and authorization flows and allows you to indicate which grant types are appropriate based on the grant_types property of your Auth0-registered Application.

For example, let's say you are securing a mobile app. In this case, you'd use the Authorization Code using Proof Key for Code Exchange (PKCE) Grant.

Alternatively, if you were securing a client-side app (such as a single-page app), you'd use the Implicit Grant.

iii. Password.

iv. Client Credentials.

v. Device Code.

vi. Refresh Token.

Refresh Tokens are credentials used to obtain access tokens. Refresh tokens are issued to the client by the authorization server and are used to obtain a new access token when the current access token becomes invalid or expires, or to obtain additional access tokens with identical or narrower scope.

Of course, nothing lasts forever, and even the refresh token will eventually expire. These tokens commonly last for 14-60 days, and afterwards, you have no choice but to ask the user to re-authorize your application. A refresh token could last forever - it's up to the OAuth server.

https://auth0.com/docs/api-auth/tutorials/implicit-grant

## TDD & BDD 

TDD is a developer-focused methodology that aims to encourage well-written units of code that meet requirements.

BDD extends the process of TDD. However, the tests describe behavior.


## APIGEE API Hybrid Management

https://cloud.google.com/apigee/


## Terraform

It is a command line tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions. Configuration files describe to Terraform the components needed to run a single application or your entire datacenter.

 Terraform is an “infrastructure as code” tool similar to AWS. Terraform's code is written in HashiCorp's proprietary language called HashiCorp Configuration Language (HCL). HCL is a structured configuration language that is intended to be both machine friendly and human readable.

  It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

  https://linoxide.com/devops/install-terraform-provision-aws-ec2-instance/


## VPCs and Subnets

A virtual private cloud (VPC) is a virtual network dedicated to your AWS account. It is logically isolated from other virtual networks in the AWS Cloud. You can launch your AWS resources, such as Amazon EC2 instances, into your VPC.

Benefit of VPC is that it helps in aspects of cloud computing like privacy, security and preventing loss of proprietary data. Lets take a look at some of the basics of a VPC. Subnets: A subnet can be thought of as dividing a large network into smaller networks.


### CIDR

Classless inter-domain routing (CIDR) is a set of Internet protocol (IP) standards that is used to create unique identifiers for networks and individual devices. The IP addresses allow particular information packets to be sent to specific computers.

https://specialties.bayt.com/en/specialties/q/270484/what-is-cidr-and-why-it-is-important-in-today-s-scenario/



## KIBANA vs GRAFANA

The main difference is that Grafana focuses on presenting time-series charts based on specific metrics such as CPU and I/O utilization. Kibana, on the other hand, runs on top of Elasticsearch and can create a comprehensive log analytics dashboard. For example, Grafana does not allow for data search and exploring.


## HTTP Headers

HTTP is a pull protocol, the client pulls information from the server (instead of server pushes information down to the client). 

HTTP is a stateless protocol. Data is passed on and stored rather on the client (Caching/sessions).

The REST headers and parameters contain a wealth of information that can help you track down issues when you encounter them. HTTP Headers are an important part of the API request and response as they represent the meta-data associated with the API request and response.

They are name or value pairs that are displayed in the request and response messages of message headers for Hypertext Transfer Protocol (HTTP). Usually, the header name and the value are separated by a single colon. HTTP headers are an integral part of HTTP requests and responses.

The response header contains the date, size and type of file that the server is sending back to the client and also data about the server itself.


## Difference between ACCEPT HEADER and CONTENT TYPE

Accept and Content-type are both headers sent from a client(browser say) to a service. Accept header is a way for a client to specify the media type of the response content it is expecting and Content-type is a way to specify the media type of request being sent from the client to the server.


## Progressive Web Apps - PWA

PWA - provides improved user experience, better visitor engagement, and increased conversion rates. What's more, they bridge the gap between responsive web pages and mobile apps. PWA technology expands the common understanding of web pages

Benefits:

1. Progressive Web Apps match the mobile-first approach. This means that application developed with PWA will function on mobile devices without any issues.

2. PWA combines the UX of a native app with the benefits of the mobile web. Application with PWA run smoothly both as a web page and native app.

3. Application built with PWA save up to 75% of the costs of a native app (both development and maintenance). 

With PWA you simply don’t have to make a separate native app, it’s enough to adjust your storefront.

4. PWA works offline, allowing the user to keep on browsing even without an internet connection. With any other web store, a user would have to drop this.

5. Supports notification

6. PWAs uses headless architecture. It’s all about separating the frontend from your backend eCommerce platform. With this approach, PWA can be added to eCommerce platform by API in just 3 months. This includes a Proof of Concept.

7. Loading time of PWA is at least 2-3x faster compared to responsive or m.dot web application. Google mobile-first indexing helps it to express the high speed of PWA and it’s smooth performance on mobile devices.

8. With faster loading time, PWA reduces server load. Your store won’t crash or slow down during periods of intense traffic.

9. Browsing with PWA is seamless. This causes a huge increase in conversion rates. 

Requirement for PWA - Service worker and Manifest.json

For accelerated work you can use Google Workbox

Disadvantages:

1. Compatibility with iOS

Since iOS 11.3, it’s been possible to run PWAs on Apple devices, but you can forget about compatibility with older devices. What’s more, Apple doesn’t allow PWAs to access many important features, including Touch ID, Face ID, ARKit, Bluetooth, serial, Beacons, altimeter sensor, and even battery information.

2. Issues with legacy devices

PWAs have been around for just a few years, so it shouldn’t come as a surprise that older mobile devices with outdated web browsers don’t support them too well. While this problem will inevitably solve itself in the future, it may be a source of customer complaints for some companies.

3. PWAs can’t do everything

As capable as PWAs are compared to traditional web apps, they can’t do everything mobile apps can do. Because they are written in JavaScript, they are not as battery efficient as apps written in native languages, such as Kotlin or Swift.

Their performance is also not as good as the performance of native apps, which has a lot to do with the fact that JavaScript is a single-threaded programming language. At the moment, access to certain important device features is still missing, including Bluetooth, proximity sensors, ambient light, advanced camera controls, and others.

## Golang 

Golang is a statically typed, compiled programming language designed at Google.

It is fast - The language is based on functions, so it is simple and fast to learn. It's compiled so it provides faster feedback, shorter time to market, and saves time and money. It's simple, so it is more maintainable, and development is faster and cheaper.

Go is faster most of the time since it does not have to consider anything at runtime.

Go is compiled to machine code and is executed directly, which makes it much faster than Java. It is so because Java uses VM to run its code which makes it slower as compared to Golang. ... Golang is also good in memory management,which is crucial in programming languages. Golang does not have references but has pointers.

Go is syntactically similar to C, but with memory safety, garbage collection, structural typing, and CSP-style concurrency.

In Static typed programming languages  variables need not be defined before they're used. This implies that static typing has to do with the explicit declaration.

## CSP Style Concurrency

In computer science, communicating sequential processes (CSP) is a formal language for describing patterns of interaction in concurrent systems. It is a member of the family of mathematical theories of concurrency known as process algebras, or process calculi, based on message passing via channels.

## Prometheus

Prometheus is an open source monitoring and alerting toolkit for containers and microservices. Based on the organizations that have adopted it, Prometheus has become the mainstream, open source monitoring tool of choice for those that lean heavily on containers and microservices.

The Prometheus server works on the principle of scraping, i.e., invoking the metrics endpoints of the various nodes that it is configured to monitor. 

It collects these metrics at regular intervals and stores them locally. The nodes expose these over the endpoints that the Prometheus server scrapes.

## Web Accessibility

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with physical disabilities, situational disabilities, and socio-economic restrictions on bandwidth and speed.

The four main guiding principles of accessibility in WCAG 2.0 are: POUR

Perceivable.

Operable.

Understandable.

Robust.



How do you achieve Web accessibility?

Choose a content management system that supports accessibility. ...

Use headings correctly to organize the structure of your content. ...

Include proper alt text for images. ...

Give your links unique and descriptive names. ...

Use color with care. ...

Design your forms for accessibility. ...

Use tables for tabular data, not for layout.

## Jenkins and Maven

Jenkins  is a continuous integration tool. In Jenkins, maven is used for building the automation code. It is used to automate the build deployment process. It is used in Selenium tests to run the tests faster and every time software changes a deployment happens to different targeted environments.


Jenkins and maven together can be used to automate this whole pipeline. 

Jenkins can be used to setup rules and parameters around maven system. Maven is a tool that is used to compile your code. And not only compile it can validate your code, install a package and can even analyse the test-cases in your code.

## Pretty JSON parser

http://json.parser.online.fr

## Bundlephobia 

Find the cost of adding a npm package to your bundle

https://bundlephobia.com

## Kotlin

A statically typed language. A JVM  typed languag. Needs the JVM to execute its bytecode. Fully interoperable with JAVA, and other Server side languages.

Has support to avoid the null pointer exception

Supports Immutability (Values don't change after initialization)

OO Language

Supports functional programming

Can compile into JS and run in Browser

https://www.youtube.com/watch?v=iC8LRjd67Ds 

https://www.youtube.com/watch?v=k9K71QkrHGE

## IIFE

An IIFE, or Immediately Invoked Function Expression, is a common JavaScript design pattern used by most popular libraries (jQuery, Backbone.js, Modernizr, etc) to place all library code inside of a local scope. ... An IIFE protects a module's scope from the environment in which it is placed.

It is a JavaScript function that runs as soon as it is defined. Also known as a Self-Executing Anonymous Function and contains two major parts.

 IIFEs are very useful because they don't pollute the global object, and they are a simple way to isolate variables declarations.

## Closure

A closure gives you access to an outer function's scope from an inner function. In JavaScript, closures are created every time a function is created, at function creation time. To use a closure, define a function inside another function and expose it.

## Use strict directive


It is not a statement, but a literal expression, ignored by earlier versions of JavaScript. The purpose of "use strict" is to indicate that the code should be executed in "strict mode". With strict mode, you can not, for example, use undeclared variables.

## Typescript

Modules in typescript are loaded on demand. This enhances efficiency. Module loaders are hence required i.e SystemJS,RequireJS, Webpck, CommonJS.

Some Typecsript features

- Classes
- Properties
- Methods
- Implementing Inheritance and Interfaces
- Import and Export
- Loading modules using module loader (System loading - On Demand Loading)

Data Types

- number 
- string 
- boolean 
- enum 
- void 
- null 
- undefined 
- any 
- never 
- Array 
- tuple 

Features

- entity: datatype (for all functions properties and arguments).

- Classes, properties, and methods

- Inheritance and interfaces

- Imports and exports

- Loding modules using Module loader (System.js)


```

class Customer {

	public CustomerName: string;

	validate(input:number) boolean {
		
		alert("hey");

		return true;
	}
}

//inheritance

class someOtherCustomer extends Customer {

	validate(){
		alert("This is a new Customer");
	}
}



```


### JS transpiled (compiled)

```
var Customer = (function(){
	function Customer(){
		this.CustomerName =  '';
	}
	return Customer
}());

```

())

Features:


1. Run time error checks - during compilation

2. Safe - Datatype pre-determined

3. Handle exceptions

4. Interface definition

5. Inheritance

6. Polymorphism

7. Uses Closure - JS design pattern

8. IIFES - JS design pattern

9. Performance friendly - Uses On-demand/Modular loading (3rd party Middlewares SystemJS/Webpack/RequireJS/CommonJS/AMD/lODASH)

10. On demand loading

Use 'npm i systemjs' - loads asynchronously


in the HTML

```
<script src= "Customer.js"></script>
<body>
	<script>	
		let cust = new Customer();
		cust.CustomerName = "Luca";

		alert(cust.CustomerName);

		cust.validate();

		cust = new someOtherCustomer;
		cust.validate()

	</script>
</body>

```


8. Create Private properties (variables), and use se(setters) and get(getters) to access them publicly.

i. Write business logic in the setters.
```
class Customer {

	private _customerName: string;

	public set CustomerName( value: string ){
		this._customerName = value;
	}

	public get CustomerName(): string {
		return this._customerName;
	}

	validate(input:number) boolean {
		
		alert("hey");

		return true;
	}
}



ii. html

<script src= "Customer.js"></script>
<body>
	<script>
		let cust = new Customer();
		cust.CustomerName = "Luca";
		alert(cust.CustomerName);
	</script>
</body>
```

9. Handling Exceptions

```
class Customer {

	private _customerName: string;

	public set CustomerName( value: string ){

		//Handling exception
		if(value.length == 0){
			throw "Customer Name is required";
		}
		//end exception. If there is exception, following statement will not run

		this._customerName = value;
	}

	public get CustomerName(): string {
		return this._customerName;
	}

	validate(input:number) boolean {
		
		alert("hey");

		return true;
	}
}
```


html

```
<script src= "Customer.js"></script>
<body>
	<script>
		try{
		
			let cust = new Customer();
			cust.CustomerName = "";
			alert(cust.CustomerName);
		}

		catch(ex){
			alert(ex)
		}
	</script>
</body>
```

10. Inerfaces



Note JS does not handle:

i. Interfaces (Separate modules that can be referenced.)
ii. Protected. 
ii. All protected variables are handles as public. Can be used in sub-classes

```
Interface IDal {
	
	add(){

	}
}


class Customer implements IDal {
	
	protected name:string == '';
	private _customerName: string;

	public set CustomerName( value: string ){

		//Handling exception
		if(value.length == 0){
			throw "Customer Name is required";
		}
		//end exception

		this._customerName = value;
	}

	Add(){

	}

	public get CustomerName(): string {
		return this._customerName;
	}

	validate(input:number) boolean {
		
		alert("hey");

		return true;
	}
}
```

html

```
<script src= "Customer.js"></script>
<body>
	<script>
		try{
		
			let cust = new Customer();
			cust.name = "me!";
			alert(cust.name);
		}

		catch(ex){
			alert(ex)
		}
	</script>
</body>
```


11. Using external modules

//Address.ts

```
export class Address{

	public Street1: string = '';
}

class DB {

}
.......................


//Customer.ts

import { Address } from './Adress';

export class Customer {
	
	protected name:string == '';
	private _customerName: string;
	public adressObject : Adress = new Address //type address and instantiate it.

	public set CustomerName( value: string ){

		//Handling exception
		if(value.length == 0){
			throw "Customer Name is required";
		}
		//end exception

		this._customerName = value;
	}

	
	public get CustomerName(): string {
		return this._customerName;
	}

	validate(input:number) boolean {
		
		alert("hey");

		return true;
	}
}

```

html

```
<script src= "/dist/systems.js"></script>
<body>
	<script>
		system.config({
			"defaultJSExtensions": true
		});

		system.import("Customer.js").
		then(function(exports){
			var cust = new exports.Customer();
		});
	</script>
</body>
```


## map

let tasks = [
	{
 
    'name'     : 'Write for Envato Tuts+',
 
    'duration' : 120
 
  },
 
  {
 
    'name'     : 'Work out',
 
    'duration' : 60
 
  },
 
  {
 
    'name'     : 'Procrastinate on Duolingo',
 
    'duration' : 240
 
  }
 
];


let result = tasks.map(task, index, array) => {
	return task.name
}


## reduce

let list = [2, 3, 4, 5];

let total_value = list.reduce((current, previous) => previous + current )

## Setting up a React + TypeScript + SASS + Webpack and Babel project in 6 Steps

https://medium.com/swlh/setting-up-a-react-typescript-sass-webpack-and-babel-7-project-in-6-steps-b4d172d1d0d6



## JavaScript Design Patterns

1. Constructor Pattern

2. Module Pattern

3. Revealing Module Pattern

4. Singleton Pattern

5. Observer Pattern

6. Mediator Pattern

7. Prototype Pattern

8. Command Pattern

9. Facade Pattern

10. Factory Pattern

11. Mixin Pattern

12. Decorator Pattern

13. Flyweight Pattern

14. JavaScript MV* Patterns

15. MVC Pattern

16. MVP Pattern

17. MVVM Pattern

Modern Modular JavaScript Design Patterns
1. AMD

2. CommonJS

3. ES Harmony
## OKR

The acronym OKR stands for Objectives and Key Results, a popular goal management framework that helps companies implement strategy. The benefits of the framework include improved focus, increased transparency, and better alignment. It also helps companies to move from an output to an outcome-based approach to work.

https://ally.io/?utm_campaign=1344228909&utm_source=google&utm_medium=cpc&utm_content=262344502731&utm_term=%2Bokr%20methodology&adgroupid=59637947171&gclid=Cj0KCQjw_absBRD1ARIsAO4_D3uD9KBxv7pjM1weNaX7cTekgUxifuWajjvz-7x_WqKwBtHh5M0SLGkaAl-yEALw_wcB

## Deep and Shallow clones

In programming, we store values in variables.

A deep copy means that all of the values of the new variable are copied and disconnected from the original variable. A shallow copy means that certain (sub-)values are still connected to the original 

https://we-are.bookmyshow.com/understanding-deep-and-shallow-copy-in-javascript-13438bad941c

## React Native 

React Native components are pure, side-effect-free functions that return what the views look like at any point in time. For this reason it is easier to write state-dependent views, as you don't have to care about updating the view when the state changes since the framework does this for you.

The UI is rendered using actual native views, so the final user experience is not as bad as other solutions that simply render a web component inside a WebView.


NATIVE CODING

There are certain features that cannot be implemented solely in JavaScript, native code is needed for:

push notifications

deep linking

native UI components that need to be exposed to React.

Overall approximately 80% of the code is shared between iOS and Android and written in JavaScript.

HOT RELOADING can be enabled. 

Conclusions:

React Native seems to be suitable for apps with simple UI, simple animations, and not long life or performance-critical apps. 

We found that a good use case for React Native can be found in applications that need short time support, for example an app for a one-shot event like a concert or a conference. These kind of apps could also benefit from the fast release cycle available if dynamically loading part of the application logic from a remote server.

## Curry and compositional programming

Currying is the process of taking a function with multiple arguments and turning it into a sequence of functions each with only a single argument.

https://medium.com/front-end-weekly/javascript-es6-curry-functions-with-practical-examples-6ba2ced003b1

```
const sum = x => y => z => x + y + z;

// JavaScript substring: str.substr(start[, length])

//definin
const curriedSubstring = start => length => str
  => str.substr(start, length);

//get
const getSubstring = (start, length, str)
  => curriedSubstring (start) (length) (str);

  //get first characters
const getFirstCharacters = (length, str) =>
curriedSubstring (0) (length) (str);

//get first character
const getFirstCharacter = str => curriedSubstring (0) (1) (str);



```


## PEGA CRM

PEGA is a Business Process Management tool (BPM). It is developed on Java and uses OOP and java concepts. The main use of PEGA technology is to reduce cost and is used in improving business purpose . Pega allows organizations to deploy changes eight times faster than Java based applications.

## Native array methods 

Native array methods that iterate through all its items are: indexOf, lastIndexOf, includes, fill, and join. 

Additionally, we can provide a callback function to the following methods: findIndex, find, filter, forEach, map, some, every, and reduce.

## Features PHP 7:

Scalar type declarations.

Return type declarations.

Null coalescing operator.

Spaceship operator.

Constant arrays using define()

Anonymous classes.

Unicode codepoint escape syntax.

Closure: call()

## CSS3


Box Shadows.

CSS3 Selectors. 

Font Additions. 

Rounded Corners. 

Border Images. 

Opacity Levels. 

Transform.

CSS3 Text Shadow.

Media  queries

## REACT snippets




index.js


```
import React, { Component } from 'react';
import ReactDOM from 'react-dom';
import MyBox from './component/component';
import './index.css'

class MyApp extends React.Component{

	render(){

		return(
			<MyBox />
		)
	}
}

ReactDOM.render( <MyApp />,document.getElementById("result"))

```


Cmponent shell ()component.js

```
import React { Component } from 'react';

class MyBox extends React.Component{
	
	render(){
		return(

		)
	}
}

export default MyBox;

```

API call with axios - actions/index.js

```
import axios from 'axios';

export function loadColour(){
	return(dispatch) => {
		return axios.get('endPointURL').then((response) => {
			dispatch(changeColor(response.data))
		})
	}
}


export function changeColor(color){
	retun {
		type:"CHANGE_COLOR",
		payload: color
	}
}


```

## Mentoring and Coaching

Mentoring is a long-term process based on mutual trust and respect. Coaching, on the other hand, is for a short period of time. Mentoring is more focused on creating an informal association between the mentor and mentee, whereas coaching follows a more structured and formal approach.

## RxJS

RxJS (Reactive Extensions for JavaScript) is a library for reactive programming using observables that makes it easier to compose asynchronous or callback-based code. See (RxJS Docs)

## CloudBees Core

 Is a continuous delivery solution that provides manageability, security, best practices and supports multiple platforms, teams, and geographical locations. ... CloudBees Core on modern cloud platforms provides flexible, governed continuous delivery with the high availability and scalability of Kubernetes.


## TOGAF

The Open Group Architecture Framework (TOGAF) is an enterprise architecture methodology that offers a high-level framework for enterprise software development. 


TOGAF helps organize the development process through a systematic approach aimed at reducing errors, maintaining timelines, staying on budget and aligning IT with business units to produce quality results.

Like other IT management frameworks, TOGAF helps businesses align IT goals with overall business goals, while helping to organize cross-departmental IT efforts. TOGAF helps businesses define and organize requirements before a project starts, keeping the process moving quickly with few errors.


The Open Group states that TOGAF is intended to:

1. Ensure everyone speaks the same language

2. Avoid lock-in to proprietary solutions by standardizing on open methods for enterprise architecture

3. Save time and money, and utilize resources more effectively

4. Achieve demonstrable ROI.

Different elements of TOGAF are:

BADT:

There are four architectural domains in TOGAF 9.1 that offer specializations for businesses.

i. Business architecture: includes information on business strategy, governance, organization and how to adapt any existing processes within the organization.

ii. Applications architecture: a blueprint for structuring and deploying application systems and in accordance with business goals, other organizational frameworks and all core business processes.


iii. Data architecture: defining the organization’s data storage, management and maintenance, including logical and physical data models.

iv. Technical architecture: also called technology architecture; it describes all necessary hardware, software and IT infrastructure involved in developing and deploying business applications.


## OWASP (Open Web Application Security Project )


OWASP (Open Web Application Security Project) is an organization that provides unbiased and practical, cost-effective information about computer and Internet applications.


The OWASP Top 10 list consists of the 10 most seen application vulnerabilities:

1. Injection.

2. Broken Authentication.

3. Broken Access control.

4. Sensitive data exposure.

5. XML External Entities (XXE)

6. Security misconfigurations.

7. Cross Site Scripting (XSS)

8. Insecure Deserialization.


## HTTP2 

1. Concurrent downloads streamlined within a single TCP connection

2. Enable browsers to fetch crucial assets of a web page first

3. Optimize and improve HTTP header compression

4. And integrating a feature known as 'Server Push' that allows the server to deliver crucial data before the browser asks for it.


## 10 ways to avoid cross-browser compatibility issues

1. Validate your code.

2. Fail gracefully. 

3. Know your audience. 

3. Consider using a framework. 

4. Keep your design simple. 

5. Reuse and reduce components.

6. Test with the difficult browsers first. 

7. Use automation - Create test scripts .



## JS Design Ptterns

1. Constructor Pattern

2. Module Pattern

3. Revealing Module Pattern

4. Singleton Pattern

5. Observer Pattern

6. Mediator Pattern

7. Prototype Pattern

8. Command Pattern

9. Facade Pattern

10. Factory Pattern

11. Mixin Pattern

12. Decorator Pattern

13. Flyweight Pattern

https://addyosmani.com/resources/essentialjsdesignpatterns/book/

https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know

## JavaScript MV* Patterns

MVC Pattern

MVP Pattern

MVVM Pattern

## Modern Modular JavaScript Design Patterns

1. AMD

2. CommonJS

3. SystemJS

4. ES Harmony

## Best practices in software engineering

1. Develop iteratively.

2. Manage requirements and edge cases.

3. Use component architecture.

4. Model software visually.

5. Verify quality.

6. Control change.

7. Use SOLID Principles


## Basic Programming Principles Every Programmer Must Follow

1. KISS. The “keep it simple, stupid” principle applies to pretty much all of life, but it's especially necessary in medium-to-large programming projects. ...

2. DRY. ...

3. Develop iteratively

4. Composition > Inheritance. ...

5. Single Responsibility. ...

6. Separation of Concerns. ...

7. Avoid Premature Optimization.

## What is diff between functional and object oriented programming?

Both concepts have different methods for storing the data and how to manipulate the data. 

In object oriented programming, you store the data in attributes of objects and have functions that work for that object and do the manipulation. 

In functional programming, we view everything as data transformation.


OOP says that bringing together data and its associated behavior in a single location (called an “object”) makes it easier to understand how a program works. 

FP says that data and behavior are distinctively different things and should be kept separate for clarity.

Functional programming is stateless. ... The lack of state allows a functional language to be reasoned just by looking at a function's input and output.

FP treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## Agile methodologies

Scrum

Lean Software Development

Kanban

Extreme Programming (XP) - Extreme Programming is about putting individuals and interactions over processes and tools, working software over documentation, customer collaboration over contract negotiation, and responding to change over following a plan. Extreme Programming should be applied to systems that have no constant functionality features. If the system should often change its functions it requires the use of Extreme Programming method.

Crystal

Dynamic Systems Development Method (DSDM)

Feature Driven Development (FDD)


## Map & ForEach Defined


forEach() — executes a provided function once for each array element.

map() — creates a new array with the results of calling a provided function on every element in the calling array.


The forEach() method doesn’t actually return anything (undefined). It simply calls a provided function on each element in your array. This callback is allowed to mutate the calling array.

Meanwhile, the map() method will also call a provided function on every element in the array. The difference is that map() utilizes return values and actually returns a new Array of the same size.


## PHP REST API with Database & Read

https://www.youtube.com/watch?v=OEWXbpUMODk

## Working with Laravel

https://www.youtube.com/watch?v=emyIlJPxZr4

## PHP Validate email

```
<?php
declare(strict_types=1);
namespace UnitTestFiles\Test;
use PHPUnit\Framework\TestCase;
final class EmailTest extends TestCase
{
   public function testCanBeCreatedFromValidEmailAddress(): void
   {
       $this->assertInstanceOf(
           Email::class,
           Email::fromString('user@example.com')
       );
   }
   public function testCannotBeCreatedFromInvalidEmailAddress(): void
   {
       $this->expectException(InvalidArgumentException::class);
       Email::fromString('invalid');
   }
   public function testCanBeUsedAsString(): void
   {
       $this->assertEquals(
           'user@example.com',
           Email::fromString('user@example.com')
       );
   }
}

```

## Following are the features available with VueJS:


Virtual DOM. VueJS makes the use of virtual DOM, which is also used by other frameworks such as React, Ember, etc. ...

Data Binding. 

Components. 

Event Handling. 

Animation/Transition. 

Computed Properties. 

Templates. 

Directives.


https://www.tutorialspoint.com/vuejs/vuejs_overview.htm

## Cordova platform

Cordova is an open-source mobile development framework. It allows you to use standard web technologies such as HTML5, CSS3, and JavaScript for cross-platform development, avoiding each mobile platforms' native development language.

https://www.youtube.com/watch?v=CDY1fRZycGk

## PreCSS

PreCSS is a tool that allows you to use Sass-like markup in your CSS files. It lets you enjoy a familiar syntax with variables, mixins, conditionals and other goodies. ... PreCSS alone will give us most of what we'd need to replace Sass, but there are plenty of additional PostCSS plugins to choose from.

## PostCSS-cssnext 

PostCSS-cssnext is a PostCSS plugin that helps you to use the latest CSS syntax today. It transforms CSS specs into more compatible CSS so you don't need to wait for browser support.

## JS Promises snippet

i. Shell
```
const flipACoin = new Promise((resolve, reject) => {    

});
```


A Promise is a JavaScript class, and its constructor takes in a single argument: a function called the executor function. The executor function itself has two arguments called resolve and reject. The code inside the executor function runs and you call resolve() when you’re done and reject() if something goes wrong.

ii. Extending the execution function

```
const flipACoin = new Promise((resolve, reject) => {    
  const flipResult = flip(); //let's say flip() takes a few seconds
  
  if(flipResult) {
    resolve();
  } else {
    reject();
  }
});

```

iii. Interacting With Surrounding Code

Now that we’ve got a Promise running, let’s see how it interacts with the context around it. One of the most important facets of using a Promise is that even though you’ve created a Promise, the code around it keeps running!

```
console.log("I'm about to flip a coin!");

const flipACoin = new Promise((resolve, reject) => {
  console.log("I'm flipping the coin!");
  
  const flipResult = flip(); //let's say flip() takes a few seconds
  
  if(flipResult) {
    console.log("Here is the coin flip result!", flipResult);
    resolve();
  } else {
    reject();
  }
});

console.log("I have flipped the coin.")

```


and this is the output:
a. “I’m about to flip a coin!”

b. “I’m flipping the coin!”

c. “I have flipped the coin.”

d. “Here is the coin flip result! Heads”



iv. Waiting For A Promise To Finish

You can call several functions on a Promise in order to run code in response to the Promise completing. The first one we’ll discuss is .then()

```
console.log("I'm about to flip a coin!");

const flipACoin = new Promise((resolve, reject) => {
  console.log("I'm flipping the coin!");
  
  const flipResult = flip(); //let's say flip() takes a few seconds
  
  if(flipResult) {
    console.log("Here is the coin flip result!", flipResult);
    resolve();
  } else {
    reject();
  }
}).then(() => {
  console.log("I have flipped the coin.")
});

```



.then() is a function of a Promise that takes in a function that will be run after the code inside the executor function of the Promise calls resolve(). In this new snippet, the following will be the order of logs:

a. “I’m about to flip a coin!”

b. “I’m flipping the coin!”

c. “Here is the coin flip result! Heads”

d. “I have flipped the coin.”

The content of the .then() function is only called after the resolve() call, which only happens after “Here is the coin flip result! Heads” has been printed to the log. We’ve now successfully waited for the Promise to complete before doing something!

Here are all of the other Promise functions that you can use:

```
const flipACoin = new Promise((resolve, reject) => {
  resolve();
}).then(() => {
  //use `.then()` to do something after `resolve()` has been called
}).catch(() => {
  //use `.catch()` to do something after `reject()` has been called
}).finally(() => {
  //use `.finally()` to do something either way
});

```


v. Returning Values Out Of Promises

Waiting for a Promise is useful, but it’s even more useful to be able to tell surrounding code what the resolved value of the Promise is. To accomplish this, you need two things:

a. resolve() should take in an argument

b. The function in .then() should take in a parameter

```
const flipACoin = new Promise((resolve, reject) => {
  const flipResult = flip(); //let's say flip() takes a few seconds
  
  if(flipResult) {
    resolve(flipResult);
  } else {
    reject();
  }
}).then((flipResult) => {
  console.log(`The result was ${flipResult}`);
});

```


vi. Using A Promise Later

You can  break away from promises and continue to use .then() later, so long as you have them stored in variables.

```
const flipACoin = new Promise((resolve, reject) => {
  const flipResult = flip(); //let's say flip() takes a few seconds
  
  if(flipResult) {
    resolve(flipResult);
  } else {
    reject();
  }
});

//...
//do other things
//...

console.log("Wait did I flip the coin?");

flipACoin.then((flipResult) => {
  console.log("Oh I did!");
});

console.log("Double checking...");

flipACoin.then((flipResult) => {
  console.log("Okay I definitely did!");
});

```

vii. Chaining

The most aesthetic property of promises is that they can be chained:

```
const flipACoin = new Promise((resolve, reject) => {
  resolve();
}).then(() => {
  doSomething();
}).then(() => {
  doSomethingElse();
}).then(() => {
  doAnotherThing();
});

```

Note:

This is highly maintainable and readable because as you continue to add more things to depend on, you can simply keep adding chained .then() calls.

But there’s something tricky here that you need to know! Look at the snippet above. You might think that doSomethingElse() will wait for doSomething() to complete. But it doesn’t! Here’s why.

Every .then() call in a chain waits on the last Promise in the chain, not the .then() before it. 

That means if doSomething() takes a while, doSomethingElse() may finish executing before doSomething() is finished executing.

See: https://codepen.io/jksaunders/pen/pozmWGv




## "please enter a commit message to explain why this merge is necessary"

It's not a Git error message, it's the editor as git uses your default editor.

To solve this:

press "i"
write your merge message
press "esc"
write ":wq"
then press enter




## REACT HOOKS 

https://reactjs.org/docs/hooks-overview.html

Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class.

Hooks are backwards-compatible. 

```
import React, { useState } from 'react';

function Example() {
  // Declare a new state variable, which we'll call "count"
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>
        Click me
      </button>
    </div>
  );
}

```


Here, useState is a Hook (we’ll talk about what this means in a moment). We call it inside a function component to add some local state to it. React will preserve this state between re-renders. useState returns a pair: the current state value and a function that lets you update it. You can call this function from an event handler or somewhere else. It’s similar to this.setState in a class, except it doesn’t merge the old and new state together. (We’ll show an example comparing useState to this.state in Using the State Hook.)

The only argument to useState is the initial state. In the example above, it is 0 because our counter starts from zero. Note that unlike this.state, the state here doesn’t have to be an object — although it can be if you want. The initial state argument is only used during the first render.

You can use the State Hook more than once in a single component:


```
function ExampleWithManyStates() {
  // Declare multiple state variables!
  const [age, setAge] = useState(42);
  const [fruit, setFruit] = useState('banana');
  const [todos, setTodos] = useState([{ text: 'Learn Hooks' }]);
  // ...
}

```




## Homormophic Encryption

Homomorphic encryption is a form of encryption that allows computation on ciphertexts, generating an encrypted result which, when decrypted, matches the result of the operations as if they had been performed on the plaintext. Homomorphic encryption can be used for privacy-preserving outsourced storage and computation.

Homomorphic encryption operations are malleable by definition. You would use the RSA private key for decryption.

The biggest challenge in cloud computing is the security and privacy problems caused by its multi-tenancy nature and the outsourcing of infrastructure, sensitive data and critical applications.

Fully Homomorphic Encryption. A fully homomorphic encryption system enables computations to be performed on encrypted data without needing to first decrypt the data. Such cryptosystems have natural applications in secure, privacy-preserving computation as well as many other areas.

https://www.semanticscholar.org/paper/Optimizing-Fully-Homomorphic-Encryption-Algorithm-Kaur-Sengupta/364f5e31eb4056b4e12063761952625cf16c46de 

Key security threats associated with cloud computing:
 https://www.semanticscholar.org/paper/Security-Threats%2FAttacks-Present-in-Cloud-Munir-Palaniappan/44dc8494b2bbd8aa56320de8a209d3aa6c36628b

 There are two types of encryption in widespread use today: symmetric and asymmetric encryption. The name derives from whether or not the same key is used for encryption and decryption.

 SE (Searchable Encryption) is a positive way to protect users sensitive data, while preserving search ability on the server side. ... The two main branches of SE are SSE (Searchable Symmetric Encryption) and PEKS (Public key Encryption with Keyword Search).

 Homomorphic encryption allows user to operate encrypted data directly without decryption.

 Searchable symmetric encryption (SSE) allows a party to outsource the storage of his data to another party in a private manner, while maintaining the ability to selectively search over it.

 
 Homomorphic Linear authention

 called homomorphic linear authenticator (HLA) [1].It is a. signature scheme widely used in cloud computing and. storage server systems, which allows client that has stored. data at an untrusted server to verify that the server. possesses the original data without retrieving it


## JavaScript REST  API 

A REST API is a way of easily accessing web services without having excess processing. Whenever a RESTful API is called, the server will transfer to the client a representation of the state of the requested resource.

So we can define a RESTful API:

1. One that is stateless. Data is not stored on the server but in sessions on the client.

2. separates concerns between client-server.

3.  Allows caching of data client-side

4. Utilizes standardized base URLs and methods to perform the actions required to manipulate, add or delete data.

Summary:Basic features of REST

Stateless: Meaning the client data is not stored on the server, the session is stored client-side (typically in session storage).

Client<->Server: There is a separation of concerns between the front-end (client) and the back-end (server). They operate independently of each other and both are replaceable.

Cache: Data from the server can be cached on the client, which can improve performance speed.

URL Composition: We use a standardized approach to the composition of base URLs. For example, a GET request to /cities, should yield all the cities in the database, whereas a GET request to /cities/seattle would render the city with an ID of seattle. Similarly, REST utilizes standard methods like GET, PUT, DELETE and POST to perform actions. Which we’ll take a look at in the next section!

https://itnext.io/javascript-fundamentals-an-introduction-to-rest-apis-7cbe8a809d3b 

https://www.youtube.com/watch?v=LooL6_chvN4  (1)  https://www.youtube.com/watch?v=FOZtRzY5x8E (2) - REST and RESTful Web Services explained

## AXIOS vs FETCH

https://medium.com/frontend-digest/axios-vs-fetch-which-to-use-in-2019-6678c083c5c


## MAP vs EACH

https://codeburst.io/javascript-map-vs-foreach-f38111822c0f

## JavaScript es6 CURRY functions

https://medium.com/front-end-weekly/javascript-es6-curry-functions-with-practical-examples-6ba2ced003b1

## Getting started REDUX, REACT, GraphQL and Express

https://medium.com/@childsmaidment/getting-started-with-redux-and-graphql-8384b3b25c56

## Cypress

 It is a JavaScript-based end-to-end testing framework that doesn't use Selenium at all. It is built on top of Mocha, which is again a feature-rich JavaScript test framework running on and in the browser, making asynchronous testing simple and fun.

 Alternatively, while Cypress is used for UI testing, it uses its own unique DOM manipulation and runs directly in the browser with no network communication. ... One of the biggest gaps between Selenium and Cypress is that while Selenium runs against different browsers, as mentioned before, Cypress only supports Chrome.


## git Work Flow 

Feature Branches with Merge commits

https://github.com/kukuu/algorithms/blob/master/git-workflow/feature-branch-with-merge-commits.png

Option A - When  local repo exists before creaTing GITHUB repo

Create and checkout branch - git checkout -b feature-1
git status
git branch -a
git add .
git commit -m ''
git checkout feature-a
gitcheckout feature-b

merging (fast forward and recursive strategy):
git checkout master
git merge feature-a   
git merge feature-b  



1. Push to git - git push 'remote repo url' master

2. Create an alias to 'remote repo url' - git remote add 'repourl' origin

3. Push to alias - git push origin master



Option B - When you dont have a local repository. Alias is created by default.
Check alias with command 'git remote -v' 
Result  gives 'fetch' and 'push'

1. git clone 'remote repo url created'

2. git status

3. git add .

4. git commit -m "message"

5. git push origin masters



Delete branch:

to delete branch: git branch -D feature-3 (when branch is not merged)

to delete branch: git branch -d feature-3 (when branch is  merged)


Conflicts:

No need to add message on command commit, because is a merge commit.
1. Fix error

2. git status

3. git add .

4. git commit

5. in new editor do 'shift : wq enter key' to exit

6. git log --oneline (git log)


Collaboration:

1. git checkout master

2. git pull origin master

3. git checkout -b feature-d

4. git status

5. git add .

6. git commit -m "message"

7. git push origin feature-d

8. pick  => 'compare and pull request' f

9. Add extra useful messages

10. => click ' createpull request' button

11. Add assignee/reviewers to code  review and request to merge

12. check commits made and files changed

13. Add a comment. Say 'good work'

14. You can add messages to lines of code by clicking next to them (+)

15. Finally, you can merge

16. Confirm

17. Delete branch

.......................

Adding missed or new features

18. git chckout master

19. git pull origin master  (to get other collaborators)

20. git checkout -b image-update

22. Make changes

23. git status

25. git add .

26. git commit -m "added images"

27. git push origin image-update

28. Check remote repo

29. Confirm and click branch  changes have been mades 


30. Go to 8 : Compare and pull request

In case it is not complete. Add a message : DONT MERGE:  say for example to add a misssing image and send back.
Work to be done in same branch

31. git add .

32. git commit -m "added last image"

33. git push origin image-update

34. Check remote repo and a timeline will be added to preious commit prior to adding the missing image

35. You should see message : THIS PAGE IS OUT OF DATE. REFRESH

36. (REVIEWER) Go back to conversations and MERGE.

37. Go to master branch and check updates.


## Bearer Token

Bearer Tokens are the predominant type of access token used with OAuth 2.0. A Bearer Token is an opaque string, not intended to have any meaning to clients using it. Some servers will issue tokens that are a short string of hexadecimal characters, while others may use structured tokens such as JSON Web Tokens.

## Related Articles

1. Agility - https://github.com/kukuu/AGILITY/blob/master/README.md 

2. Digital Transformation - https://github.com/kukuu/digitalTransformationStrategies/blob/master/README.md 

3. Scaffolding for projects - https://github.com/kukuu/AGILITY/blob/master/README-scaffolding.md

## TypeScript

 Benefits
 1. Compile to JavaScript

 2. Uses IIFE
 		(());
 3. Closure

 4. Exception handling (TR/CATCH)

 5. Module Loading

 6. On demand loading using loaders: CommonJS, SystemJS, Webpack, RequireJS

 7. Compile time checking


## The Twelve-Factor App methodology 

This is a methodology for building software as a service applications. These best practices are designed to enable applications to be built with portability and resilience when deployed to the web.


## TestComplete

TestComplete is a functional automated testing platform developed by SmartBear Software. TestComplete gives testers the ability to create automated tests for Microsoft Windows, Web, Android, and iOS applications.

## Testenium

Testenium generates programming language code for Selenium WebDriver in C#, Java and Python languages. ... When a test is executed Testenium records screenshots, videos and error reports and provides user with the reports without writing any code at all.

## Blue Green Deployment

At its core, a blue-green deployment is a release practice that maintains two production environments called blue and green, switching between whether the blue or green environment is live - using Load Ballancers. The primary benefit of this approach is to mitigate risk and control the timing of releases.

## Canary deployment - Segmentation

A canary deployment / canary test allows you to gradually release new features to a subset of your users while still serving your current branch to the rest of your users.  It basically allows you to test things in parallel without having to make major merges/deployments.  This allows you to A/B test features to assess performance before releasing them to a majority of your users.

## Coaching & Mentoring

Mentoring is a long-term process based on mutual trust and respect. Coaching, on the other hand, is for a short period of time. Mentoring is more focused on creating an informal association between the mentor and mentee, whereas coaching follows a more structured and formal approach.

## Factory pattern

A Factory Pattern or Factory Method Pattern says that just define an interface or abstract class for creating an object but let the subclasses decide which class to instantiate.  The Factory Method Pattern is also known as Virtual Constructor.

## Webhook

A webhook in web development is a method of augmenting or altering the behavior of a web page, or web application, with custom callbacks. These callbacks may be maintained, modified, and managed by third-party users and developers who may not necessarily be affiliated with the originating website or application.


Webhook endpoint:

The receiving endpoint can choose to whitelist certain IP addresses from known sources. The webhook can include information about what type of event it is, and a secret or signature to verify the webhook. GitHub and Stripe sign their requests using an HMAC signature included as an HTTP header.


## Difference between APIs and Webhooks

To put it simply, an API does stuff when you ask it to, while a Webhook does stuff on it's own when certain criteria is met or scenarios takes place. 

Webhooks on the other hand are automated calls from example.com to a server.

## Benefits SPA

Advantages:

1. Fast and responsive. Since single-page applications don't update the entire page but only required content, they significantly improve a website's speed. 

2. Good for making Responsive Websites, Support mobile, Tablet & Desktop. No extra queries to the server to download pages. Performance improvement.

3. Single Page Application can improve performance in many ways, Single time file load each of HTML, CSS, JS


Disadvantages:

Client must enable JavaScript, Single Page Application build with JavaScript, So JavaScript should be enabled in client browser. JavaScript enabled in all modern browsers by default.

Security: Compare to traditional page Single Page Application is less secure due to Cross-site scripting (XSS).

Memory Leak: Memory leak in JavaScript can even cause powerful system to slow down.
