# Project_Description
Description of the Porsche Flight Advisor Project

The project was launched during Stuttgart Hackathon 2019

---------------------------------------------------------------------

## Aim of the Project:
The Use Case is, that you wat to go on a flight from Stuttgart Airport and you drive there with your Porsche car.
To realize this, we combine the Stuttgart Airport-API with the Porsche Dashboard.
For the last meters inside the airport we provide a cross plattform mobile app.


## Structure of the Project:

- Server written in Python that handles the data management and API-Requests
- Pegasus-backend which implements the Display inside the Porsche Dashboard, making use of the Porsche-API
- Cross-Platform Mobile App, that shows all relevant flight information on your mobile device. While Data is automatically synced between server and mobile device


![alt text](https://github.com/Pegasus-Stuttgart2019/0_Project_Description/blob/master/Documentation/project_overview.png)

## Features of the Porsche Dashboard
- fastest way to airport and the best parking slot that's nearest to his boarding terminal
- because you're driving, you can't interact via the touch menus. 
So it's possible to talk with the Car-App to get alle the information per speach and additionally shown in his Infotainment-Dash.
(Due to the lack of an real car, we used an Amazon-Echo as speeh-bot)

## Features of the Mobile App

All necessary information right at your fingertips.
Including:

- Time left till takeof 
- interesting shopping tips
- Fastest Security Check waiting Queue
- Terminal To Go
