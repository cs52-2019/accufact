# accufact

# The Challenge
In the age of false information, individuals need a way to fact check news sources effortlessly as they browse the web. All of this must be done optimally across platforms to ensure that users are always presented with high quality information. Our challenge with this extension is being able to detect facts within a text, and then be able to retrieve credible sources with it. 

# Our solution
After engaging in needfinding with the Stanford professors, students, and researchers, we realized that a browser extension would enable users to be presented with analytics around the validity of viewed facts while maintaining their autonomy in deciding which news sources to visit. To do this, users will be presented with the following information:
Number of sources with similar facts
Ratings of sources with similar facts
Source skew

# Our Live Demo
Here

# Who We Are
Member | Bio
---|---
Kyle Feliciano | Kyle is a sophomore majoring in bioengineering. He is interested in tissue engineering and prosthetics design. He has researched in labs at Northwestern and Stanford, working on projects that include laser-tissue dynamics, hydrogels, and visual-to-motor learning pathways. In his freetime, Kyle likes watching Youtube, giving piano lessons to children, and composing music.
---|---
Jackson Parell | Jackson is a freshman  majoring in IR and Computer  science. He is interested in national security in the digital age. He works part time for a Venture capital fund that specializes in deep technology and machine learning, and is a research assistant at the Center for International Security and Development. In his freetime, he enjoys hiking, surfing, running – really just any activity outside.
---|---
Darian Martos | Darian is a senior majoring in Symbolic Systems. He is broadly interested in artificial intelligence and natural language processing, especially in the fields of language understanding and artificial consciousness. In the past, he has worked on other projects in deep learning and loves to keep up with the field. In his free time, he likes to read, swim, play virtual card games, or work on other side projects like his up-and-coming app foode.


# Our Development Timeline
Week | Milestone | Details |Status
---|---|---|---
2 | Plan ML framework, begin interface design | Begin interface design by learning how to create components in React. ML framework will involve research in receiving fact queries using methods such as NER. By end of the week, should have considerable grasp of how to seek facts in a text query and understand what data to train on. | In Process!
3
Implement fact querying, prototype database design,create downloads and settings pages
Create a mock database, sketch out the design features of the database and consider potential ethical issues that may arise. Design downloads page and the settings page. From the ML framework with fact querying, implement the fact querying algorithm with PyTorch, and figure out how to merge the algorithm with the front end of the extension. 


4
Continue ML development and training, User Testing I, start chrome extension, design home page
Design home page. Begin building chrome extension by building graphical extension. By end of the week, a fully designed frontend should be finished for user testing purposes. Over the course of the weekend, we will begin testing the application with set text files and mock data, since IR methods will not be fully implemented yet.


5
Design info retrieval process, design source page
Begin designing source page. Learn how to highlight text and iterate on how to make it clear. Make sure click on fact creates up pop-up. Begin researching different information retrieval methods, including PageRank, that can handle optimal runtime given a large database.


6
Implement information retrieval methods, “finalized” website produced with nice UI, design login page, begin implementing extension data retrieval methods
Finish source page. Implement login page. Begin implementing information retrieval methods using Python. Finalize training process for fact query retrieval. 


7
User Testing II, finalize chrome extension, integrate extension with backend
Finalize chrome extension. Build in communication between chrome extension and website page. Optimize information retrieval methods and ensure they are connected to backend of the server. Afterward, do basic user testing to check how the app works with new IR methods.


8
User Testing III, continue backend integration
Backend integration with chrome extension and website. Over the end of this week, perform final user testing rounds and then optimize extension based off user evaluations.


9
Finalize implementation, optimize design and backend
Backend integration with chrome extension and website. Finalize any details of implementation from user evaluation, and continue to optimize the backend to ensure proper flow of information and maximal F1 performance.


10
Presentation
Figure out how to diffuse the extension widely, and conduct presentation and general findings of working on the extension and potential goals or shortcomings of the project.


 
# Acknowledgements
We are grateful for the help and support from our instructors with CS+Social Good, including Jose Giron, Vik Pattabi, and many others.


