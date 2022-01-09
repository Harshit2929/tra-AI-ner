# HealthifyAtHome

HealthifyAtHome is a one stop application for ur fitness.No need of a trainer user our webb app and  our ai trainer will give u realtime feedback onyour exercise movements.We also have made a game In this stressed times having fun is also important ,play our game to alleviate ur stress and have fun while exercising.
## T187[Software Chasers]
## Team Members
```sh
Pushpendra Vishwakarma
Harshit Chauhan
Harsh Suthar
 ```

## Problem statement
One of the problems that we identified in these covid times was that due to reduced physical activity has caused many psychological and physical health issues. Physical activities (PA) and exercise are very essential for one's well being as they not only maintain physical and psychological health but also help our body to respond to the negative consequences of several diseases such as diabetes, hypertension, cardiovascular diseases, and respiratory diseases.
World Health Organization (WHO) has advised adults to accumulate at least 150 min of moderate-intensity aerobic physical activity during the week, and additional muscle strengthening activities on two or more days a week (WHO, 2018).Population-based survey studies for example showed that those who exercise at least two to three times a week, report significantly less stress, cynical distrust, and anger than less active individuals.Thereby we thought that solving this problem was necessary  and we hope our project gives a positive impact to society.

## Solution

In order to solve this problem we have built a web application where we will give user real time feedback on of user's exercises both for yoga poses and workout exercises.A game has also been built in whhich the users using his hand movements has to destroy the obstacle coming his way.This game will help motivate users to exercise and have fun too😜. 
Streaks have also been added so that user remains motivated and doesn't leave a day without exercising.We have also integrated music player in our web app so that users can exercise and play their favourite songs 🎶.

## Features

- User can see his/her daily progress through our streak in profile.
- A fun game has been built in which using hand movements one has to break obstacles in order to survive in the game.
- Our ai trainer is compatible with both for yoga  and workout exercises.It will give the percentage score and even realtime feedback to user on what he can improve on.
- User can check his daily tasks that he/she has to do in /plans route.
- We have added challenges  in which in a time limit user has to perform given number of reps.


## Tech stack/Framework used
- Next.js
- Tensorflow.js
- Firebase
- Three.js

## Challenges we ran into

- The biggest challange we encounter is to make the 3D game. The first challage is the model in game is 3D and the pose we are getting is 2D. Using some high school mathematics we were able to map 2D co-ordinated to 3D. The next challenge was to make the 3D model to copy the exact pose which we managed to do after few hit and trial.
- While matching the pose directly needs many tranformations like shifting,scaling,etc. So we chose to  match the user's joimts angle instead of matching pose points directly.


## Demo Video

[![Demo Video](https://img.youtube.com/vi/v=WeegoO-dvXs/0.jpg)](https://www.youtube.com/watch?v=WeegoO-dvXs)




## Further upgrades we want to fulfil

- We aim to add pwa to our web application so that same code can be used both for our web and mobile application,add offline access and push notifications for daily reminders of our exercises.
- We aim to add leg movements so that we can include exercises related to movements of  lower body in our game.



## Installation

### 1. Clone Repo
- git clone https://github.com/Harshit2929/tra-AI-ner/

### 2. Install yarn
- npm install --global yarn

### 3. Install dependencies
- yarn install

### 4. Run locally
- npm run dev






