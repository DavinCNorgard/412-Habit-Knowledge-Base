
## System Design of HabitStar

HabitStar is an interactive ambient lighting system designed to help users improve their habits and [[behavior]]. 

- The design has three main components:
	1. Star 
	2. network server
	3. [[smartphone app]]

![[Pasted image 20231025152229.png]]
#### star

- The device can be clicked to document progress towards goals.
- The LED lighting unit displays the progress toward a users goals using brightness.
- One user will have one star for each habit.

![[Pasted image 20231025165554.png]]
#### network server

- Allows communication between the mobile device and multiple stars.

#### [[smartphone app]]lication

- Allows the users to change settings such as star color, [[Goal Setting]], and add or remove habits.
- Users can use the app to document progress.
- Has access to the users data, shows historical habit data.

![[Pasted image 20231025165711.png]]

SRC: https://dl.acm.org/doi/10.1145/2702613.2732782