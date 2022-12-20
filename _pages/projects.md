---

layout: splash
permalink: /projects/
title: "Projects"
header:
  overlay_image: /assets/face2.jpg
  
  

excerpt: >
  Experiences from my coding courses from UCI. <br />

---
## Animation in Python
{% include video id="7e16-8DLrlI" provider="youtube" %}

This project had me create a simulation within python that had objects all with different behaviors. This is project that heavily incorporated inheritance as some objects are similar due to them potentially being dependencies or parent object. There are objects I can choose from at the start, and if I were to click anywhere on the screen, the object will spawn and move in a random direction granted they can move. The window can also be adjusted to whatever size and the objects will still be contained and bounce off them.

* The blue ball goes in a straight line and will bounce off walls.
* The red ball will also bounce off walls but slowly turns as it moves forward.
* The cyan ball will run away from either red balls or blue balls, but will not be destroyed by the black balls..

Each black ball is a form of a hunter. They will destroy either blue or red balls on contact but will eventually become smaller and destroy itself if they can't find food in time depending on which object it is.

* The first black ball will stay stationary until forcibly removed by the user.
* The second black ball will also stay stationary but will remove itself if it hasn't consumed a prey in a certain amount of iterations.
* The Third and final black ball will actively move towards blue or red balls. If no consumable objects are available, they will move in a straight line until it remove itself due to "hunger". 