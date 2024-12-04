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

Landing page
![](images/landingpage.png)

About Us page
![](images/aboutus.png)

Admin page
![](images/admin.png)

Sign up page
![](images/screenshot4.webp)

Select a Workout page
![](images/selectaworkout.png)

List Partners page
![](images/listpartners.png)

Workouts page
![](images/workouts.png)




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

In M3 we will make a much more user friendly application, with coherent color schemes, design aspects, and overall aesthetic choices. With this will involve a lot of bug testing and trying to find as many edge cases as possible to test the app to the best of our abilities.


[Here is the link to our M3 project page](https://github.com/orgs/spot-me-bro/projects/7)



### Adherence to the GitHub hosting guidelines

Our team created SpotMeBro, a web platform designed to help students find gym partners, while adhering to GitHub hosting guidelines to ensure professionalism and maintainability. All source code for the project is hosted in a GitHub repository, enabling new developers to build the system locally without needing additional files from us. We established a dedicated GitHub organization named SpotMeBro, which includes a repository for the application code and a separate repository for the project’s homepage, hosted via GitHub Pages. The homepage includes an overview, user guide, developer guide, and development history making the project accessible and well-documented for users and developers alike. This structured approach ensures a collaborative and professional development environment, with clear documentation to support future contributors.


### Deployment

SpotMeBro is deployed on vercel [here](https://spot-me-bro-nextjs.vercel.app/).

### Team Contract

Team Contract can be found [here](https://docs.google.com/document/d/1R3GT8Ti9fhLgFd88CLp2sHaLnCis-MX7W9F1UdYqiRk/edit?tab=t.0#heading=h.9odkc9kfj5rj).

### Team
SpotMeBro is designed and implemented by, Ashton Aparra (ashtonaparra), Adeil Mohammadzadah (Adeilmo226), and Coen Bracilano (CoenBracilano).
