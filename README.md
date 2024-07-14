# SeniorDesignProject
For my senior design project, my group (consisting of 6 junior computer science students) worked with the company VPT.FIT, and the product he asked us to make was a virtual personal trainer chatbot which could be added to his website. His goals for having a chatbot instead of his current setup is that it could provide support for users during their workout (if they had questions about a specific exercise) or if the workout needed to be adjusted according to user need/feedback (such as injury, area of focus, intensity). Another Stevens group created a VPT.FIT app, so please note that is unrelated to our project.

My team signed an NDA at the completion of the project which prohibits us from sharing our work and defines the ownership of the software to VPT.FIT, so I do not feel comfortable sharing it on a public repository. Instead, I will describe it here.

For the final product, we used HTML and CSS for the front-end, and we used Javascript and the OpenAI API for the back-end.

For the Fall semester, we primarily wrote and edited the back-end chatbot of the project. Starting initially with an entirely command-line interface, we met weekly with the client and discussed features of the chatbot. The specifications we decided on were as follows:
1. Conversational
   a. Would turn unrelated conversation back to workouts
   b. Would provide motivation to the user
3. Would create a workout based on the same user specifications (equipment, time)
   a. This would consist of a warmup, main workout, and cooldown.
5. Would connect back to VPT.FIT's YouTube videos

We initally had some issues with getting OpenAI to print what we desired. We did not have enough character space to include all of the exercises in VPT.FIT's database. There were also issues with getting the AI to take into account how many exercises could be done within a certain number of exercises, reps, and sets. In addition, it often included videos that were unrelated to the VPT.FIT youtube channel, or it would include exercises that we did not include. Thus, we spent the Fall semester working out these issues within the character limit of the OpenAI prompt.

The Spring semester consisted of creating a front-end and making sure it worked well with the backend we had created. For the majority of the year, we had used Python for the back-end and had started the front-end in PySimpleGUI Web.  One issue my team had faced is while we were in the process of creating the front-end, PySimpleGUI suddenly required a paid license, which would be enforced after 30 days of free use. We were then unable to run any of the front-end code. Due to the lack of time we had to learn a new front-end language, we shifted the project to be done in JavaScript, HTML, and CSS which we had just learned in WebDev, and we felt confident that we would be able to complete the project in time in those languages.

We then worked with our client to make sure the front-end specifications in his company's colors, and that the code would be easy to include on his website (in which using HTML and CSS over PySimpleGUI was much better for the client as well).

For the senior design fair, we had a working demo in which we were able to show how the chatbot worked. It was met with mostly positive reviews, although some people recommended that the client includes workouts that require different equipment (weight-lifting, elliptical, and treadmill) and that nutrition could be tracked in the website/app. We also discussed extensively throughout the year if certain information about workouts should be tracked in the client database to make the chatbot smarter and more personable. This information was shared with the client, and he expressed interest in continuing working with Stevens students.
