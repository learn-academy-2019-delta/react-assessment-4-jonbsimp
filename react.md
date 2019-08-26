# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- True: React is a modern, efficient answer to complex UI applications
- False: React will only render on the server using Node.js
- False: React is a full stack framework for modern web applications
- True: React is a flexible library that plays the role of V in an MVC framework
- False: You should always update a component's state directly using this.state
- True: React is made up of encapsulated components that manage their own state
- False: React components render HTML

1b. Add an interesting true fact about React to the list.

  -Reacts virtual DOM is faster than real DOM.
  -React takes DOM to the next level by keeping in memory a virtual representation of a UI and synchronizing it with the real DOM. 
   Not only does virtual DOM enable the declarative API of React, but it allows ReactJS to know when exactly to re-render or ignore 
   certain specific pieces of DOM, reducing the performance cost of updating the real DOM.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer:
  
  -"Smart"(logic) components are more complicated and hard to test.
  -"Dumb"(display) components are presentational components that present something to the DOM


  Researched answer:

  -Dumb Components: This component only responsible to present something to DOM. There will be no logic at all inside this component therefore it is called dumb component.
        Because dumb component only focus on the presentation (UI Component), it is ideally will the most reusable component.
  -Smart Components: Also called container components. Smart component on the other hands keep track of state and concern with how things work.
        Container component still receives data or function via props and can pass it to another smart component or dumb component as props.
        Container component pattern is class-based components and have constructor() functions. We usually initialize state inside the constructor, although you can remove the constructor and still have a state.


3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer:
  
  -Yarn add is used to download the package for react

  Researched answer:

  -Yarn add installs a package and any packages that it depends on.

4. How would you explain state to a friend who doesn't know code?

  Your answer:
  
  -I would use the example that we used in class. I would say that state is what we can change upriver
   to change the behaviors downriver.

  Researched answer:

  -In the React sense, “state” is an object that represents the parts of the app that can change. 
   Each component can maintain its own state, which lives in an object called this.state

5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer:
  
  -props get passed to the component and state is managed within the component

  Researched answer:

  -Props: Props are how components talk to each other. 
  -State: State is used so that a component can keep track of information in between any renders that it does.