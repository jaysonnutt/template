---
layout: project
type: project
image: images/map.jpg
title: Walking List
permalink: projects/walking-list
# All dates must be YYYY-MM-DD format!
date: 2016-09-15
labels:
  - Ajax
  - PHP
  - MySQL
  - HTML
summary: An interactive list used by political candidates when campaigning door to door.
---

<img class="ui medium right floated rounded image" src="../images/walking-list-1.jpg">This project was developed for my ICS 415 class. We were each assigned a street in Hawaii and provided with actual voter data from that street. The purpose of this web application is to assist political candidates as they walk door-to-door campaigning. It provides them with information about the voter before encountering them. The application supports search and other features to refine the list. The candidate has the capability to rate the encounter on a scale from -2 to 2 and add a comment to the house to give them a better idea of how receptive the person was for future use. The candidate can refine the list and click a button to download the results as a CSV file which can then be used in other applications such as Microsoft Excel. The tables are dynamically populated drawing from a MySQL database. The lists are divided by house number into even and odd lists so that the candidate can walk up one side of the street and back down.

I remember this project vividly because it took me a long time to get it to function properly. The application was a bit more complicated than I was used to, fusing together HTML for the structure, PHP to interface with the database and create dynamic HTML tables, and SQL for storing and retrieving the data. I've had experience with all of these languages individually, but getting them to play together nicely was a real challenge. Through working on this project I learned how to design more complex projects that require many pieces working together.

You can [view the application here](http://jaysonnutt.com/walking_list/).



