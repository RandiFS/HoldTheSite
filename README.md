# HoldTheSite



**Build:**[https://griffitheduau-my.sharepoint.com/:u:/g/personal/randi\_silviken\_griffithuni\_edu\_au/IQCFWyFvhpuyQIQniKt6uwhlAQqenSO5aVsztRX8HN7rot4?e=BQyYvK](https://griffitheduau-my.sharepoint.com/:u:/g/personal/randi_silviken_griffithuni_edu_au/IQCFWyFvhpuyQIQniKt6uwhlAQqenSO5aVsztRX8HN7rot4?e=BQyYvK)



**Video:** [https://griffitheduau-my.sharepoint.com/:v:/r/personal/randi\_silviken\_griffithuni\_edu\_au/Documents/A3\_s5448036\_3148GFS/HoldTheSiteVideo.mp4?d=w7a810d3fd7af426eb7c12f07324ba118\&csf=1\&web=1\&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0\&e=wNKSA5](https://griffitheduau-my.sharepoint.com/:v:/r/personal/randi_silviken_griffithuni_edu_au/Documents/A3_s5448036_3148GFS/HoldTheSiteVideo.mp4?d=w7a810d3fd7af426eb7c12f07324ba118&csf=1&web=1&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=wNKSA5)





**How the Ai works:**

Each enemy uses and AI controller that has an Ai Perception (sight), They have a blackboard that stores what it know and a behavioral tree that decides whet to do. 



**Behavioral Tree checks three branches:**



**1 - Combat**

&#x09;If the enemy can see the player, and the player is close enough the enemy will shoot.

&#x09;If the player is far away the enemy will chase the player

**2 - Defuse**

&#x09;If the bomb is armed the enemy will runt to it, wait three seconds, then press defuse button

**3 - Patrol** 

&#x09;The enemy walks to random points in the level due to a nav mesh



**Other features** 

* When the player hides the enemy will stop shooting, but keeps aiming at the corner for 4 seconds 
* Only one enemy defuses the bomb at a time, if the enemy defuser dies the next enemy will take over the job
* If an enemy sees the player while defusing the enemy will stop and shoot 
* Enemy only react to the player not to each other



**Game Feel**

* Muzzle flash so you can see the shots 
* Red screen flash and camera shake to see you have been hit
* Beep sound that gets faster as the time runs out
* Defusing wanting on the HUD
* Health hits over the enemies that go from red to white when they have been hit
* E prompt on bomb to signal press E
* Explosion and camera shake to before win screen





