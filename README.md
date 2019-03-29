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
![image](https://user-images.githubusercontent.com/42956051/55254765-634d0800-521e-11e9-8d15-36397642a979.png)

## Palette
<img width="1428" alt="Screen Shot 2019-03-29 at 12 36 13 PM" src="https://user-images.githubusercontent.com/42956051/55255110-61d00f80-521f-11e9-9846-3b58b808ab76.png">

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
    
POST
  ('/stretcher')
    ('/:user_id) Post route to save stretches
   
```
## Planning Tool & User Stories

### [User Stories on Trello](https://trello.com/b/YAphSBeQ/mindfull)



