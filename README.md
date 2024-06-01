# Overview
My name is Afahri Kerr, and I am an aspiring software engineer. I first started learning to code when I joined the computer science program in February 2022. I had absolutely no experience, but I have always had an interest in technology so I knew I would do whatever it takes to succeed. The program has taught me many skills and programming languages necessary to achieve my goal, not limited to Python, Java, C++, HTML, and SQL. Above that, it has given me a greater appreciation and understanding of the technologies that are in use today and a burning desire to be a part of the ones to come. This site displays my current abilities through some projects I have completed in my coursework.

It takes a great deal of planning and focus to make a project successful. You must meet the client's needs while minimizing security risks and producing readable bug-free code. These first 2 projects were used for my capstone course at SNHU (Southern New Hampshire University). I had to choose artifacts to enhance across 3 categories which were software design and engineering, algorithms and data structures, and databases. I decided to use 2 artifacts and performed a code review which you can view [here](https://www.youtube.com/watch?v=AbIkUvgf_ck).

## Software Design and engineering / Databases: Artifact 1 - Weight Tracker App Enhancement
![Initial application screen](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/Weight%20Tracker%20App.png?raw=true)
I chose to enhance my weight tracker mobile application across these categories. The artifact originated from course CS-330: Mobile Architect & Programming. This project displays a wide range of abilities and was built in Android Studio using the Java and XML programming languages. The goal of this project was to design and build a mobile application that will allow the user to store their daily weights in a database along with a weight goal. The user should then be able to see each of their entries and be given an option to receive SMS notifications upon achievement of their goal. Follow the links below to download or view the files for this project.

- [Enhanced Version](https://github.com/AfahriOK/Mobile-Architecture-and-Programming/tree/main/Enhanced)
- [Original Version](https://github.com/AfahriOK/Mobile-Architecture-and-Programming/tree/main)

<ins>List of Enhancements</ins>
1. Designed and implemented an account creation screen to support multiple users.
2. Improved input validation to the username and password fields while utilizing the Encryptor class and ensured all database cursors were closed after use to improve security.
3. Merged the User and Goal tables in the database and changed the logic of the functions to improve efficiency.
4. Implemented a button to clear the complete list on the weight screen to improve usability.
5. Improved variable names and code spacing, added JavaDoc comments to functions, fixed font visibility and other warnings, and removed unnecessary comments and variables to improve readability.
   
This artifact demonstrates an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals. I used many different techniques in this project to achieve the overall goal. I had to design the database, the screen layouts, and the logic to combine everything and keep it secure while allowing a beginner user to utilize it easily. I decided to make a seperate account creation screen because I saw how easy it would be for a user to enter the incorrect information.  

The enhancements to my database demonstrated an ability to develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources. I decided to encrypt the passwords in case of a breach so that the users' passwords wouldn't be easy to steal. Each password is generated with a random salt so that all the passwords cannot be cracked using a rainbow table. I also added input validation to the sign-up process to prevent SQL injection attacks on the database.

I demonstrated an ability to design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts. I added code comments at the start of each file to document what each file should do. I also added JavaDoc comments to the functions so another programmer can easily modify the code.

## Algorithms and Data Structures: Artifact 2 - Testing Enhancement
![Coverage test](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/Testing.png?raw=true)
I chose to enhance my final project from course CS-320: Software Test Automation & QA. This project displays my ability to design and test my programs using efficient techniques such as boundary analysis. I built this project in Eclipse using the Java programming language and Junit5 for testing. The goal of this project was to design and test 3 classes and their associated service class for an appointment program given a set of requirements. Follow the links below to download or view the files for this project.

- [Enhanced Version](https://github.com/AfahriOK/Software-Test-Automation-And-QA/tree/main/Enhanced)
- [Original Version](https://github.com/AfahriOK/Software-Test-Automation-And-QA)

<ins>List of Enhancements</ins>
1. Changed internal data structure to a HashMap to improve code efficiency.
2. Added a @BeforeEach initialization method in my testing files to simplify and remove redundant code.
3. Improved variable names, code spacing, removed redundant code/comments, and added JavaDoc comments to functions to improve readability.
4. Added a header comment box to show the overall purpose and requirements of each file.
   
The skills for this artifact demonstrate an ability to design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices. My initial program was built using an array which caused the performance to be O(n) where n is the number of objects in the array. I changed the array to a HashMap using the unique ID of the objects as a key which improved the performance to O(1).

I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals. Testing is an important part of creating error free code. I used boundary analysis to identify the edge cases of the requirements and designed my tests around them to ensure functionality. I then used Junit5 to test my code coverage which came out to 100% for my object and service class files.

I also show an ability to design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts. I added a comment header box to my files to display the program requirements, purpose, test coverage, and most recent date that I updated the file. I also added JavaDoc comments to the functions and cleaned up a lot of redundant code using the @BeforeEach tag so that a new programmer can easily understand it and make changes as needed.

## Grazioso Salvare Animal Tracker
![Shelter Lookup](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/Grazioso.png?raw=true)
This artifact originated from my Client/Server Development course. It was built using Jupyter Notebook and was written using Python, Pandas, Plotly, and Dash. It allows a user to visualize location and other data of animals based on a MongoDB database. You can download the files for this project using the link below.
- [Grazioso Salvare Animal Tracker](https://github.com/AfahriOK/Client-Server-Development)

## OpenGL 3D Scene
![Original Scene](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/OriginalImage.jpg?raw=true) ![3DScene](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/3DScene.png?raw=true)
This artifact originated from my Computer Graphics and Visualization course. It was built using Visual Studio and was written using the C++ programming language and the OpenGL library. The scene was built from the ground up using many simple shapes. The program allows you to view the scene from any angle using the built-in camera functionality. You can view the files or download this project using the link below.

- [3D Scene](https://github.com/AfahriOK/Computer-Graphics-And-Visualization/tree/main)

## Travlr Web Application
![Travlr Home Screen](https://github.com/AfahriOK/AfahriOK.github.io/blob/main/assets/img/travlr.png?raw=true)
This artifact originated from my Full Stack Development course. This web application was built using the MEAN (MongoDB, Express, Angular, and Node.js) stack so it mostly utilized Javascript, but also included Typescript, HTML5, and CSS in Visual Studio Code. It features a user facing side to allow users to see different trip listings and descriptions. It also has an admin SPA built using Angular to allow admins to add trip listings to the site which is protected with user authentication to ensure a user is authorized to make changes. You can view the files or download this project using the link below.

- [Travlr Web Application](https://github.com/AfahriOK/Full-Stack-Development)
