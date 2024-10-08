---

layout: splash
permalink: /projects/
title: "Projects"
header:
  overlay_image: /assets/face2.jpg
  
gallery2:
  - url: /assets/S1.png
    image_path: /assets/S1s.png
    alt: "Sketch 1"
    title: "Sketch 1"
  - url: /assets/S2.png
    image_path: /assets/S2s.png
    alt: "Sketch 2"
    title: "Sketch 2"
  - url: /assets/S3.png
    image_path: /assets/S3s.png
    alt: "Sketch 3"
    title: "Sketch 3"
  - url: /assets/S4.png
    image_path: /assets/S4s.png
    alt: "Sketch 4"
    title: "Sketch 4"
gallery3:
  - url: /assets/P1.png
    image_path: /assets/P1.png
    alt: "Persona 1"
    title: "Persona 1"
  - url: /assets/p2.png
    image_path: /assets/p2.png
    alt: "Persona 2"
    title: "Persona 2"
  - url: /assets/p3.png
    image_path: /assets/p3.png
    alt: "Persona 3"
    title: "Persona 3"

gallery4:
  - url: /assets/storyboard.jpg
    image_path: /assets/storyboard.jpg
    alt: "Storyboard"
    title: "Storyboard"
  - url: /assets/sb2.jpg
    image_path: /assets/sb2.jpg
    alt: "Storyboard 2"
    title: "Storyboard 2"
gallery5:
  - url: /assets/figma.png
    image_path: /assets/figma.png
    alt: "Prototype"
    title: "Prototype"


excerpt: >
  Experiences from my coding and informatics courses from UCI. <br />

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
* The third and final black ball will actively move towards blue or red balls. If no consumable objects are available, they will move in a straight line until it remove itself due to "hunger". 

## To Do List in Java
{% include video id="gZfhYXpCrbo" provider="youtube" %}


This project required me to make a To-Do List in Java that allowed for deadlines and sorted each item by it's priority and name lexicographically. You can mark individual items as done or outright delete them. 

## Webflow redesign of the UCI Informatic website
{% include video id="C9crYim8-8U" provider="youtube" %}


This project had me redesign parts of the UCI Informatics page from scratch to be easier to navigate and read. I rearranged the site to have information about Informatics at the top of the page compared to it being at the bottom. I also seperated the text hidden by images that required the user to hover over to see. While it does take up more room, it allows people to at least know there is text as some people may not notice that the images lead to new pages. The other page I redesigned was the B.S. Informatics page. The page has been reordered so that information such as requirements or qualifications are at the top before getting to the more specific details about the major. I also added a table of content that scrolls with the user so navigating the page would be even easier. On both pages, I redid the dropdown menu to look more in-line with the other UCI websites, to look nicer fancier in general, and reordered the categories so that undergraduate is before graduate. Undergraduate normally comes first in listing so the switch can help with reducing the odds of someone going to the wrong dropdown category. 

As I only had to design parts of the website, not all of the functions the site normally has works. The only option in the dropdown menu that works is the B.S. Informatics button as I needed a pathway to that page specifically. It was one of the two pages I decided to redesign, but I am confident in my ability to go back add more pages if I have more time. Links that do work will go to their respective page on the normal UCI Informatics site.

## ZotWasteLess


### Problem Statement

Yearly, one-third of all food produced globally is wasted? That means that an estimated 30-40% of the food supply in the US goes to waste each year which amounts to approximately 133 billion pounds (or 63 million tons) of food wasted. Food waste is a major environmental and economic problem. Team A++ and ZotWasteless is here to resolve this issue with user-friendly software for households and grocery stores, aiming to reduce waste and save money for the years to come. 

### Sketches

{% include gallery id="gallery2" layout = "half"%}

The sketches shown display our desire to make our app as simple and user-friendly as possible. Proper food storage tips are front and center as well as our calender to help with setting reminders for food expiration dates being only a single button press away. 

The inventory we planned to use is grid-based with images. Instead of a clutter of text, it would be easy to see and organize your own food supply. This will help with your own mental stack as you operate the app.

When it comes to analytics, we figured that showing graphs would be the most effective way to show how much food is being saved in a way that is easy to understand. These graphs would show trends, how much you are saving, and could help the user find out where they can improve when preventing food waste.

### Persona

{% include gallery id="gallery3"%}

After the sketches, we went on to design personas to get a better understanding of what users would want from our apps. These personas helped us understand how a user would operate the app and ways it could help a specific subset of people. We can also see who can and cannot operate our app's UI and if we need any improvements to the UX.

### Storyboard

{% include gallery id="gallery4"%}

These two storyboards show our focus on making the food saving process as user friendly as possible. The storyboards show two different stories about who we cater this app to. The grocery store manager is able to easily manage his store's inventory and decide what should go on clearance to make sure that they can maximize profit. The other story is about an everyday person trying to properly store their groceries. With the help of ZotWasteLess, they were able to manage their own food with relative ease. The focus on both stories is that the process is seamless and not confusing.

### Prototype

{% include gallery id="gallery5"%}

This is our design made within [Figma](https://www.figma.com/file/Yuf9dI82xSo7cI5DVcfxGB/ZotWasteLess?type=design&node-id=0-1&t=Pf6VDGDmVLwOf4hD-0). Using the iPhone X through iPhone 13 designs as our models, a prototype with a log-in/sign-up page and all of the afformentioned features was created. All of the features from storage tips, analytics, inventory tracking, and expiration calender are all showcased clearly. The prototype is easy to understand with buttons at the bottom for navigation. 
