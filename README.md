# gradu8: Automated Academic Advising
Welcome to gradu8! This app was the product of Hack UMass 2018. Some friends ([Rishabh Srivastava](https://www.linkedin.com/in/rishsrivastava), [Sharvil Kekre](https://www.linkedin.com/in/sharvilkekre/), and [Nathan Duarte](https://www.linkedin.com/in/nathanduarte/)) and I made this automated course planner, which aimed to help students work through [UMass Amherst's Computer Science course cirriculum](https://www.cics.umass.edu/ugrad-education/bs-degree-requirements). To use the planner, a student creates a quick profile (listing courses they've already taken, whether they want a lighter / heavier credit load, etc.), and then is immediately taken to their suggested "course plan" for the remainder of their college career! 

Since it's a hackathon project, it's not the neatest project in the world - there were a number of corners that were cut in the interest of time. Naturally, too, we've all grown as programmers a great deal since writing this project, so there are a *number* of things we'd probably do different if we were to re-make this application. Still, though: we had a blast making the project, so I figured I'd highlight it here. During the hackathon, we won the Berthiaume Center for Entrepreneurship's Hustle Award for the best pitch of a new project! 


## How to Install
Download this GitHub repo, navigate to the directory you saved it to, and type: 

`pip install -r requirements.txt`

This will install the required libraries.


## How to Use
Navigate to the directory you've got gradu8 in, and run: 

`python gradu8.py`

This'll launch the Flask application, which you can then reach from any browser by navigating to 'http://127.0.0.1:5000/'

Once you have gradu8 open, you can just scroll down to the pre-requisite form near the bottom of the screen. (Most of the form was for demo purposes, and doesn't actually affect the performance of the course planner.) Here, you can fill out courses you've already taken, and then click "Submit" to see your custom schedule! 

![A screenshot of gradu8's course-selection checklist](https://i.imgur.com/FJsJknA.png)
