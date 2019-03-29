# Diane Sanchez - Capstone Proposal

## Problem Statement

Too many people refuse to get medical and mental health because they cant afford it. This app proposes an initiative 
to help change that stigma starting with office ergonomics. There are a lot of simple stretches that can vastly improve the quality of life while promoting wellness. With mindFULL users will be able to select area of pain on a graph and then 2 different stretch reccomendations will be displayed that can be saved to their profile as a reference guide for the future.
## Technologies Used

### Application

- O Auth for log in

### Frontend
- Vue.js

### Backend
- Express.js
- knex.js

### Database
- PostgreSQL


## Wireframe
<img width="874" alt="Screen Shot 2019-03-29 at 2 28 14 PM" src="https://user-images.githubusercontent.com/42956051/55260890-2ccbb900-522f-11e9-9973-0aa8a8ab6873.png">

## Palette
<img width="1401" alt="Screen Shot 2019-03-29 at 1 46 46 PM" src="https://user-images.githubusercontent.com/42956051/55258696-36522280-5229-11e9-810d-1d8936e2fe5a.png">

## ERD
<img width="566" alt="Screen Shot 2019-03-29 at 1 23 55 PM" src="https://user-images.githubusercontent.com/42956051/55257689-46b4ce00-5226-11e9-9d7d-f06ad7b32ab3.png">

## Serve Route Plan
```
POST
  ('/users')
   (/:email) Post route to create user profile
   
PATCH
  ('/users')
    (/:email) Patch route for form to input email/name/age/height/weight
    
PATCH
  ('/user')
    ('/:user_id) Patch route to update user profile
    
GET
  ('/stretches')
    ('/:stretches_id) Get all route to return array of all stretch objects
    
POST
  ('/stretches')
    ('/:user_id) Post route to save stretches
   
```
## Planning Tool & User Stories

### [User Stories on Trello](https://trello.com/b/YAphSBeQ/mindfull)



