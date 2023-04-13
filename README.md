# dsa3101-2220-12-ds

## Project Description 
Data Science has been around for close to 10 years, yet there is no agreement on what the field consists of. This leads to confusion among prospective students when they are trying to decide between degree programs. It also leads to arguments and disagreements within and between universities when it comes to assessing the performance of a "data science" department.
The goal of this project is to analyse the similarities and differences between data science departments of local universities in Singapore using unsupervised learning techniques. This is so as to provide some guidance to prospective students looking to further their education in one of our local universities here in Singapore.

## Table of Content 
This Repo contains the following folders: 
* Backend/
* Data/
    * university_courses/
    * salary_info.xlsx 
* Frontend/

The 3 folders contain the code, data and relevant resources for backend, raw data collected and frontend respectively. The Backend/ folder is managed by the backend team, while the Frontend/ folder is managed by the frontend team. As for the Data/ folder, it consists of resources relevant to both sub-teams and is thus jointly managed by everyone in the group.

## How to use 
To access our final product. Do the following: 
1. cd to Frontend/API_testing folder
2. Run docker build --no-cache -t py_mock_api . to create image 
3. Run docker run --name api -d -p 9001:5000 py_mock_api to create container 
4. cd .. to go back to Frontend folder where the final webpage is stored and connection of backend and frontend has been built. 
5. Run docker compose build
6. Run docker compose up -d 
7. Go to http://localhost:8050 and start broswing through our website! 
