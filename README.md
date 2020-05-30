<center><h1><span style="color: lightblue ; ">Elevator Project </span> </h1></center> <br>


<ul>
<li><span style="color: grey ; "> Mohammed Elsayed.</span></li>
<li><span style="color: grey ; "> Abdullah Drwesh.</span></li>
<li><span style="color: grey ; "> Esraa Sayed.</span></li>
<li><span style="color: grey ; "> Zeinab Walid.</span></li>
</ul>
<br>

<h2><span style="color: pink ; "> Introduction: </span></h2>
<p>
<span style="color: grey ; ">
&nbsp;&nbsp; We implement an Elevator system  that mimic the real system of elevators.
We use stepper motor that makes the elevator to move depending on given steps which are the 5 levels from ground till the fourth floor.
We use 7-Segment to display the location of the elevator in each floor.
We use two push buttons outside each floor except the ground and the last floor have one push button only to request the elevator to go up or down.
Also we use push buttons inside the elevator for the ground and the four floors.
We tried to express all scenario that could happen in real elevator system.
For example,the user can be in lower level and enter the elevator and press the fourth floor then another user enter from first floor and press the third floor, we save these requests and order them as to open in third floor first then the fourth one, not move to the fourth floor first then the third one which is not make sense and so on for other scenario that could happen in real elevator system.
Also, there is a push button to open the elevator if needed by user from inside.
The time of opening in each floor is five seconds except any one press the open button inside the elevator or someone stand infront of the door, we used IR sensor to sense the presence of anyone infront of the door in each time the door opens so if IR sensor detect someone infront of the door, the door still opens.
Moreover , We take overload issues into consideration for saftey so we determine the maximum number of passengers can be in the elevator is four and if the number of passengers exceed four the door still opens and an alarm starts.
We used Flex sensor to sense if the maximum weight is reached in the elevator or not in each time the door of elevator opens. If the maximum weight is reached the door of the elevator still open till someone exit from the elevator.

</span>
</p> 
<br>


<h2> <span style="color: pink ; "> Schematic Circuit : </span></h2>

<h3><span style="color: grey ; ">Default view of Elevator System.</span></h3>

![default](default.png)
<br>

<h3><span style="color: grey ; ">Two push buttons to adjust duration needed by user.</span></h3>


 <center> <img src = "user_in_pushbuuton.png">  </center>
<br>

<h3><span style="color: grey ; ">User's adjustment for the speed of counting down:</span></h3>
<h5><span style="color: grey ; ">1- High Speed.</span></h5>

<center> <img src = "high_speed.png">  </center>
<br>

<h5><span style="color: grey ; ">2- Normal Speed.</span></h5>

 <center> <img src = "normal_spead.png">  </center>
<br>

<h5><span style="color: grey ; ">3- Low Speed.</span></h5>
  
  <center> <img src = "low_speed.png">  </center>
<br>


<h3><span style="color: grey ; ">The duration displayed on 7 segments up on user's adjustment.</span></h3>

  ![default](user_input.png)

<br>


<h3><span style="color: grey ; ">Start button that confirm all user's adjustments.</span></h3>


<center> <img src = "start_button.png">  </center>

<br>

<h3><span style="color: grey ; ">Count Down displayed on 7 segments.</span></h3>

![default](count_down.png)

<br>  

<h3><span style="color: grey ; ">Toogling of the two leds after the 7 segments reach to zero.</span></h3>


<center> <img src = "toogle.png">  </center>
<br>

<h3><span style="color: grey ; ">New cycle for the other led.</span></h3>


<center> <img src = "new_cycle.png">  </center>

<br>


