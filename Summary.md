# GroupLink (tentative name)

## Usability and Convenience
  
  Sending multiple links to people is often a time-consuming and difficult process. While there are types of software and extensions that can open a list of specified links, there is no way of compiling those links for later use.

## Our Goal

  We seek to build a browser extension that will have the ability to take in a number of links from the internet and create a unique link. This link, upon clicking, will have the ability to open all links within simultaneously, allowing the user to view each webpage individually. GroupLinks that are created can have new links added, almost the same way one would add a bookmark.
  
 ### Proposed Structure
 - A user interface that gives the option to create a new GroupLink
 - Upon establishing a new GroupLink, users would use a "+" button to add a new link
 - When saving, the user has an option to choose whether the links open as new tabs in a current window or new tabs in a new window
 - The user will also have the option to set an expiration time if the links are only meant to be used for a certain amount of time
 
 ### Expected Resources
  - Javascript
  - jQuery (for simplifying certain web tasks)
  - Ajax ( for potentially interacting with web servers for saving links)
 ### Potential Challenges
  - Creating the link to redirect to the group of links
  - Having one link seamlessly open multiple links
  - Having users without the extension able to open the shortened group link
 
 ### Segmentation of Work
  - Backend Specialists (handling the JavaScript and web server handling)
    - Isaiah Freeman
  - Frontend Specialists (focusing on GUI appearance, UX design, and usability)

## Who are Our Users?

  There are many applications of our project not only in the workplace, but also in personal lives and in education.
  
  ### Example: Education
  - A professor at a college teaching a Composition writing class has to send three literature reviews from an top-level university. The students are assigned to read and answer subsequent questions.
  - The typical way to do this (on Blackboard, for example), would be to post each individual link as a new object on the Blackboard menu.
  - With our extension, the professor could add a single link, perhaps entitle it something like "Chapter 2 Readings", and upon clicking it, would open all three literature reviews as new tabs,
  - The teacher can set an expiration for the link to expire just before a scheduled quiz
  
  ### Example: Research
  - A student working on a persuasive paper needs to find articles that propose one side of the argument and articles that propose another side of the argument
  - With our extension, a student can find relevant articles, then use our extension to save them into two GroupLinks: One support the affirmative and the other supporting the negative of the persuasive arguments
  
  - The student can then keep those GroupLinks on their accounts or even *save them as bookmarks* to open later on.
  
    
