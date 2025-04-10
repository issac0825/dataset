# Test Instances 

This document contains the problem files used to test the algorithms used to solve the problem. The instances used were generated based on those proposed by Damian et al. 2018 for the Meal Delivery Routing Problem.

The “dataset” folder contains 34 instances, where the filename “01o100” denotes example number 1, which contains 100 orders. After “o” indicates the number of orders in the instance.

Meaning of hyperparameters in the problem file: 

“order” table: 
  Order number: order serial number 
  Restaurant: order corresponding to the restaurant 
  x: customer coordinates x 
  y: customer coordinates x 
  time window_ei: time window start node 
  time window_li: time window end node 
  service time: service time 
  demand: order demand 
  ready_time: time when the restaurant is ready to place the order 

“restaurant” table: 
  Restaurant serial number: restaurant number 
  Restaurant coordinates x: restaurant coordinate x coordinates x: restaurant coordinates x 
  Restaurant coordinates y: restaurant coordinates y 

“courier” table: 
  courier: rider number 
  on_time: point at which the rider goes to work 
  off_time: point at which the rider goes to work 

“distribution center” table: 
  x: distribution center coordinates x 
  y: distribution center coordinates y
