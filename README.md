# LaserLapCounter
A laser lap counter for mini-z rc cars.

# Project overview
An laser barrier, connected to an arduino, will detect the passage of a car. The arduino will count the time elapsed between two laps and will send the data to the computer. The pc will save the data in a database and will display the result on a web page.

The webpage will have the following features :
* Create a new player
* Add a circuit
* Main page displays the different circuit and the first three records along with player names
* Start a race :
  * Select circuit
  * Select player
  * Select car and its configuration
  * Click start
  * A vocal messaeg will tell if any new record was made
  * A vocal message will announce the lap number
 
Angular will be used for this project with Tailwind for the CSS, and mysql for the database. 

