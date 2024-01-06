## About this project

Gym Project is the 2.0 version of MyGymTrainer, a gym application developed for my final course project in the Information Systems program. The project was developed with **Laravel** for the API, **Mysql** for database, **React.js** for frontend and **Backpack** to build the administration panels.

## Overview

This project is a comprehensive web platform designed to streamline gym administration and enhance client experiences. We offer an intuitive administration system to simplify member management.

### Key Features

- **Efficient Administration:** Member control, financial management, and simplified scheduling.
- **Detailed Tracking:** Individual profiles for each client with workout history and progress.
- **Motivating Gamification:** Scoring system, challenges, and ranking to encourage consistency and effort.

## How do I install it?
       clone repository
       git clone https://github.com/ViniciusDuranteBagio/GymProject.git


## How do I run it ?
To run this project, you will need to have Docker installed on your machine. If you don't have it, [click here](https://docs.docker.com/engine/install/). After installing Docker and cloning the project, open the terminal in the project folder and run the following command:`docker compose up -d`.

After running the above command, it is necessary to enter the container created with this command: `docker exec -it gym_project_web bash`.

After enter the container you will need to run this command to update the composer: `compose update`

And After that you will need to run this command to start the server and run the application: ` php artisan serve`.

After that you will be good to go, use the project as you want.



