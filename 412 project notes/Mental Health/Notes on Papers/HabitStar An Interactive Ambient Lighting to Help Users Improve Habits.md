
## Summary

- Research introduces "HabitStar," an interactive ambient lighting system designed to help users improve their habits.
- HabitStar is star-shaped and connects with a mobile application.
- The lighting and the app are synchronized through a network server.
- Users can interact with both the lighting and the app to manage their habits.
- HabitStar helps users recognize their goals by prompting them to self-record their progress.
- It promotes a gradual approach to habit change by offering norm data as practical goal indicators.
- The ambient visualization provided by the lighting helps keep users motivated in their habit improvement journey.

## Research 

- Studies have been conducted on [[casual information visualization]], in this case it is used to improve information quality for users using an ambient display.
- The focus of HabitStar is to apply the theory behind [[casual information visualization]] to improve the users habits.
- According to this paper, [[aware]]ness of [[behavior]] is necessary to change or forge new habits.

## Hypotheses

- Self-recording data in terms of [[achievement]]s will help users recognize the progress toward their goals. Additionally, this will increase users [[aware]] of their habits.
- Displaying data through ambient light focuses the user on the current state of their habits. Comparing user data helps set feasible goals, and deters impractical goal setting that demotivates users.
## System Design of HabitStar

- The design has three main components:
	1. Star 
	2. network server
	3. application

![[Pasted image 20231025152229.png]]
#### star

- The device can be clicked to document progress towards goals.
- The LED lighting unit displays the progress toward a users goals using brightness.
- One user will have one star for each habit.

![[Pasted image 20231025165554.png]]
#### network server

- Allows communication between the mobile device and multiple stars.

#### application

- Allows the users to change settings such as star color, goals, and add or remove habits.
- Users can use the app to document progress.
- Has access to the users data, shows historical habit data.

![[Pasted image 20231025165711.png]]

 

