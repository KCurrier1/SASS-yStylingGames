![SASS-y Styling Games logo](https://user-images.githubusercontent.com/59896865/234712503-60a4e224-ea7f-499f-93f2-b2e9c2df3704.png)


# SASS-y Styling Games

SASS-y styling games is an application meant to be utilized as a fun learning tool to help new developers learn a very helpful frontend extension of CSS called SASS. SASS stands for Syntactically Awesome Style Sheets and is a great tool to build more organized style sheets and allow for java-like syntax when it comes to certain aspects of stylization. There are many learning tools and learning games to learn the base of CSS, but there are not nearly as many that focus of development with SASS and all its benefits – especially not ones that are meant to be entertaining and fun while you learn!

This application is setup in the form of a game where users will be shown an image purely made up of html and SASS, and they will be prompted to recreate the sass portion of the code needed to create the image through a series of levels with new SASS functionality and techniques explained as they progress. This game will be beginner friendly – the user will see a block of code with blanks and corresponding answer code snippets that can be dragged into their places and checked to see the user matched the code blocks correctly. This functionality is currently very simplistic as the answers are currently in order of correct placement! :)





## Features

- Drag & Drop Answer Functionality
- Reset All functionality
- Level Completion and Stage Completion Conditionals
- Accessible for all color blind variants

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | ![#731062](https://via.placeholder.com/10/731062?text=+) #731062 |
| Secondary Color | ![#A66BBF](https://via.placeholder.com/10/A66BBF?text=+) #A66BBF |
| Tertiary Color | ![#2B4075](https://via.placeholder.com/10/2B4075?text=+) #2B4075 


## Tech Stack

**Frontend (AKA application-wide):** Vue 3, SASS, JS

These were chosen mainly because I work directly with them in the industry, but also because I wanted to further my knowledge and capabilities in the tech stack I now know and love! This combo makes the code more reusable, faster to build, and infinetly more scalable!

**Cloud:** Vercel

This cloud platform was chosen for its simplicity, ease of code access via their github on-commit deployment, and because with my current code load it's free!

## Logical and Physical Diagrams

**Logical:**
![Logical Diagram](https://user-images.githubusercontent.com/59896865/234712251-98346faa-ad89-4514-855b-7a59dd625e12.png)

**Physical:**
![image](https://user-images.githubusercontent.com/59896865/234712382-b530b033-4d33-45c9-b600-5bb982496ee5.png)


## Lessons Learned

Throughout this project I learned not only more about the fundamentals of SASS, I also did a deep dive into Vue. This framework and its broad compatability along with the helpful compartmentalization of code has quickly made Vue my favorite framework I have every worked with. Coupled with the ease and reasuability of Sass, this combo is wonderful for spinning up a quick application that looks good and runs even better! 


## Risks and Challenges

I tried taking a few risks with this project, but unfortunately most of them did not pay off. I initially wanted to use micro frontends for this application to understand more about them as a concept brought to life. However, due to limitations with Vue components, lack of resources available to help me learn, and my own limited understanding of Microfrontends, I was unable to implement them. Similarly, due to time constraints and faulty time management skills, I was unable to implement live code rendering in my application to show the user their coding impact in real time. 

A successful risk I took was combining my middle layer and frontend into an all Vue frontend setup and it worked perfectly! Since I also downsized on the tech stack and layering, I was able to roll my app directly into Vercel, instead of utilizing a combonation with Vercel, AWS Amplify, and S3 bucket like I had intially planned. This made hosting my application take just over 1 minute instead of what it would have taken learning how to properly manage the two systems together.
## Outstanding Issues

Currently my application is not as thorough as I'd like it to be when it comes to the amount of tutorial levels it could have. Not all SASS fundamentals were covered, and all of the levels have the same level of difficulty and identical concepts. 

Known Issues/Limitations 
- No live answer checks to notify user when they placed an individual answer incorrectly
- Answers not randomized (all are in order of required placement)
- Only 4 levels per stage and only 3 stages, some fundamental concepts not covered
- Answers not draggable once placed in an answer box, must reset or place an unused answer over it to move it
- Answer replacement styling bug, the styling condition stays in the hover/drag over


