# SpotMeBro
![](images/newlogo.png)

[View Github Organization](https://github.com/spot-me-bro)


## Table of contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Mockup](#mockup)
* [Adherence to the GitHub hosting guidelines](#adherence-to-the-gitHub-hosting-guidelines)
* [Deployment](#deployment)
* [Community Feedback](#community-feedback)
* [Team Contract](#team-contract)
* [Team](#team)

## Overview

SpotMeBro is a platform designed to help students find gym partners based on their fitness level, experience, and goals. Whether you’re a beginner looking for guidance or an advanced gym-goer looking for a partner to push you to your limits, SpotMeBro aims to make your workout experience more engaging and productive.
SpotMeBro is a platform designed to help students find gym partners based on their fitness level, experience, and goals. Whether you’re a beginner looking for guidance or an advanced gym-goer looking for a partner to push you to your limits, SpotMeBro aims to make your workout experience more engaging and productive.

### Key Features

1. Gym Partner Matching: Match users with others based on their fitness level, experience, and workout preferences.
2. Profile Customization: Users create and manage their profiles, including fitness goals and availability.
3. Workout Plans: Users can browse workout plans based on their fitness goals.


### Technology Used

* [Node.js](https://www.nodejs.com/) for Javascript-based client and server code implementation.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [React Bootstrap](https://react-bootstrap.github.io/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.
* [Postgresql](https://www.postgresql.org/) for SQL database management

## User Guide
Up-to-date screenshots showing the state of the project.

Landing page. Users can click on the LEARN MORE button to learn more about the website.
![](images/LANDINGPAGE1.png)

Learn More page. Users can see the unique features our website offers.
![](images/LEARNMORE1.png)

Admin page. This page is only accessible when logged in as an admin user. Admins can view/edit all user profiles and workouts. 
![](images/ADMIN1.png)

Sign Up page. Users can make an account. Users must sign up with a registered @hawaii.edu email. 
![](images/SIGNUP1.png)

Login page. Users who have a registered account can log in. 
![](images/Login1.png)

Select a Workout page. Users use the drop down menu to choose which type of workout they are interesting in. They will be matched with other users who also chose the same workout type. 
![](images/SELECTWORKOUT1.png)

Match or Find page. Users can be matched with potential gym partners by clicking the "Match Gym Partners" button or can browse potential workouts by clicking the "Find Workouts" button. 
![](images/MATCHORFIND1.png)

Potential Partners page. Users are presented with other "potential gym partners" who also chose the same workout type. 
![](images/PARTNERS1.png)

Workouts page. Users can choose a type of workout to see a list of workouts based on difficulty level. Ideally, these workouts would be updated every week by Admin. 
![](images/WORKOUTS1.png)




## Developer Guide



### Prerequisites 🛠️
Before you begin, make sure you have the following installed on your system:

Node.js (v16 or higher) and npm
PostgreSQL (or any compatible SQL database)
A GitHub account


### How to Collaborate 🤝
If you want to contribute, you must either clone or fork the repository:

Navigate to the SpotMeBro GitHub repository.
Click on Fork (if you want your own copy) or request to be added as a collaborator by the admin.
Clone the Repo:

> git clone https://github.com/spot-me-bro/SpotMeBro-nextjs.git

> cd SpotMeBro-nextjs

After cloning the repository, install the required dependencies using npm:

> npm install

You’ll need a PostgreSQL database to store the system’s data.

Create a new database in your PostgreSQL instance (e.g., spotmebro_db).
Copy the database connection string (you’ll need it for the next step).


Create a .env file in the project root directory and add your database connection string:

For example:

DATABASE_URL=postgresql://postgres:password@localhost:5432/spotmebro_db


Run the following commands to set up the database schema and seed the initial data:

Run migrations to create the database tables:

> npx prisma migrate dev

Seed the database with default data:

> npx prisma db seed  

Once the database is set up and seeded, start the local development server:

> npm run dev



### Viewing the Deployed Website 🌐
If you just want to view the website, visit our live deployment on Vercel:

[👉 SpotMeBro Live Site](https://spot-me-bro-nextjs.vercel.app/).

No setup is needed. You can explore the system directly in your browser!


### Mockup
Here is a sketch of our ideas for some basic page layouts and page flow:
![](images/mockupfinal.png)

### Development History

#### Milestone #1:

[Here is the link to our M1 project page](https://github.com/orgs/spot-me-bro/projects/5)

For this Milestone, we set simple database models and pages/components.

![](images/M1progress.png)

#### Milestone #2:

[Here is the link to our M2 project page](https://github.com/orgs/spot-me-bro/projects/6)

The goal of this Milestone is to have a fully working application that references our database for information.

![](images/updatedm2.png)

#### Milestone #3:

In M3, our final milestone, we created user a more friendly application, with coherent color schemes, design aspects, and overall aesthetic choices. This involved a lot of bug testing and trying to find as many edge cases as possible to test the app to the best of our abilities.


[Here is the link to our M3 project page](https://github.com/orgs/spot-me-bro/projects/7)

![](images/M3DONE.png)

### Adherence to the GitHub hosting guidelines

Our team created SpotMeBro, a web platform designed to help students find gym partners, while adhering to GitHub hosting guidelines to ensure professionalism and maintainability. All source code for the project is hosted in a GitHub repository, enabling new developers to build the system locally without needing additional files from us. We established a dedicated GitHub organization named SpotMeBro, which includes a repository for the application code and a separate repository for the project’s homepage, hosted via GitHub Pages. The homepage includes an overview, user guide, developer guide, and development history making the project accessible and well-documented for users and developers alike. This structured approach ensures a collaborative and professional development environment, with clear documentation to support future contributors.

### Deployment

SpotMeBro is deployed on vercel [here](https://spot-me-bro-nextjs.vercel.app/).


### Community Feedback
To make sure SpotMeBro is as user-friendly and effective as possible, we had 5 community members try out the app and share their feedback. Overall, the responses were pretty positive, with most users saying they liked the clean design and simple navigation. Many found the “Find a Partner” feature to be the most useful, as it allowed them to quickly connect with gym partners who had similar workout goals. Some users suggested adding more customization options profile details and also having hyperlinks in the workouts page so users could learn more about the workouts that were listed. We also received feedback that the sign-up process could be more flexible, as the requirement for a @hawaii.edu email could be seen as a limitation. Based on this feedback, we plan to improve performance, add more customization options, and explore ways to make the sign-up process more inclusive but also safe. Overall, the feedback confirmed that SpotMeBro has potential, and the suggested improvements will make it even better.

### Team Contract

Team Contract can be found [here](https://docs.google.com/document/d/1R3GT8Ti9fhLgFd88CLp2sHaLnCis-MX7W9F1UdYqiRk/edit?tab=t.0#heading=h.9odkc9kfj5rj).

### Team
SpotMeBro is designed and implemented by, Ashton Aparra (ashtonaparra), Adeil Mohammadzadah (Adeilmo226), and Coen Bracilano (CoenBracilano).
