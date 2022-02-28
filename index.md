## Tony Rapoza

My name is Anthony Rapoza and I am graduating with a bachelor’s degree in Computer Science from Southern New Hampshire University. As a child I always dabbled in programming and game development, but it wasn’t until 2018 that I decided to dedicate myself to programming and enrolled in Southern New Hampshire’s Computer Science Program. It was through this program that I was able to gain confidence and in-depth knowledge of how to use programming to solve issues I ran into, automate tasks to save time, and create programs, applications, and video games from scratch. I am always filled with joy looking back at how far I have come since beginning my formal studies.

Below you will find an artifact that I created back when I first began my programming journey. It was a simple, full-stack task management application for android that I built in an introductory mobile development class. As you will see from the code review, while I had a solid understanding of programming concepts, there was so much more I had to learn to make this application achieve its potential. I chose to showcase this artifact as the enhancements I have recently made to it show how much I have learned and grown throughout this program as a full-stack developer. As you browse through the enhancements made to this project, I hope to show you specifically what I am capable of as a programmer now.

In the first enhancement you will see that I have successfully ported my original project from Android Studio and Java to Unity Engine using C#. This shows not only my ability to understand and learn new languages and frameworks, but also my ability to transfer and implement logic between them successfully. As you read through my narrative, I hope you can gain an understanding of the considerations and thinking behind why I felt this port would be a beneficial enhancement to the program.

In the second enhancement you will see my ability to streamline, expand, organize, and secure existing programs to better suit the environment and use cases they are tailored for. When further developing this artifact, I decided to completely overhaul the existing structure of the code while still retaining some of the original logical processes. The original application was based solely around tying together Androids UI elements to the SQLite backend. You will see that I cleared up vulnerabilities and streamlined the entire applications back-end operations by building all of the scripts around a custom-built script-based database system I developed specifically for this application. Furthermore, I was able to make the code run far more efficiently by building a more robust system of functions that handle related processes without being hampered by many of the technical drawbacks presented by the original Android Studio framework.

Finally, in my third enhancement to this artifact, I will be converting the project over to the previously mentioned database system that I built. This shows not only my ability to completely build a back-end system from scratch, but also my ability to structure it in a way that is re-usable, efficient, and customizable to the program I have built. I also hope my narrative will convey to you my thought process behind why I decided to migrate to a custom system from the original SQLite system.

Throughout this portfolio, I have made an effort to showcase my desire and ability to maximize efficiency and work smarter, not harder. I value re-usability, readability, and customizability above all else when programming as most of the time other people will be collaborating with me and these attributes make collaboration and teamwork run smoothly.

Thank you for taking the time to read about me and my approach to programming.


### Task Management Artifact

This artifact was originally created very early on in my program at Southern New Hampshire University. It is a task management application that allows a user to create an account, log in, and manage daily tasks. It was designed for a user to keep track of daily tasks that they could create and mark as complete.

**Code Review**

Watch the Code Review Here: https://www.youtube.com/watch?v=M5ny2Zl_mmw
  

**Artifact Enhancement: Software Design and Engineering**

This particular enhancement was porting the project from Android Studio to Unity. This required the codebase to be rebuilt using C# instead of the original Java. This change added much needed flexibility in UI and UX design as well as code efficiency for the application to function at its smoothest. This enhancement was accomplished with relative ease thanks to my existing knowledge and experience with C#. However, the app will still require two following enhancements for it to be fully functional.

Reflecting on the process, I feel as though I learned a lot of what to expect and what challenges I will face implementing the remaining two enhancements. One issue I encountered was figuring out how to make the account registration function in MacOS compared to Android. In Android, the account registration could be handled internally through SQLite, but on MacOS there are far more options for account storage than in Android meaning there are various security and programming concerns and benefits that needed to be weighed. Additionally, Unity has a much more robust system for managing UI and tying it into your scripts. As a result, I had to adjust to handle UI object interaction completely different than in Android Studio.


**Artifact Enhancement: Algorithms and Data Structures**

This enhancement was probably the most broad and expansive of them all. Porting over the project in the first enhancement provided some initial hurdles but was smooth sailing after that. My primary focus with this enhancement was increasing the efficiency of the code and restructuring it in a way that was more re-usable and customizable. I decided to pursue this by making the entire code structure of the program built around integration with a custom-built script-based database back-end I was developing. This allowed me to integrate database management directly into my scripts and functions without having to worry about managing two separate systems at the same time.

One massive benefit of the increased efficiency by integrating the database and program functionality into one was that I was able to eliminate some of the security concerns that existed prior. Thanks to Unity’s built in JSON Utility and PlayerPrefs libraries, I was able to partition every piece of data within my database so that injections ran into them would not be able to gain any information outside of what they had just injected. Using data structures in this way required constant thought throughout development, but ultimately resulted in a more efficient and secure program.


**Artifact Enhancement: Database**

By far my most cherished of the enhancement, I spent time throughout this project looking for a way to implement in a database in Unity that wouldn’t cause issues when ported to different devices. I learned that I could keep my original SQLite database structure, but that some mac devices could run into issues with it in Unity. As a result, I decide to replace it with a more elegant system of creating a script-based database that integrates seamlessly in Unity via C#. This system allowed you to code your scripts as you normally would without considering a database framework in the background and instead taking all of your updated lists and arrays, saving them to files, and loading the information back in whenever you choose. All of this is done using Unity’s built-in libraries and is handled completely in C#.

Upon implementing this change, I realized that I was able to create databases for user accounts, tasks, and player profiles. I could partition these however I wanted and handle all of their functionality at runtime from within Unity without having to rely on any third-party tie-ins.


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
