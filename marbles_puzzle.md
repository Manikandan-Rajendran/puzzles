#Marble puzzle

There are 9 marbles of equal weight and one that weighs a little more. Given a balance, how many weighings are required to deduce which is the heavier marble?

Solution Approach:

make 3 groups of marble with 3 marbles each in it. 

First weight, two group of marbles using balance.
if weight is balanced, then we can take 3 group of marbles and weight them. 
  still balanced?, then the weight marble is the last marble in group 3. otherwise, balance show which marble is over weighted.
if weight not balanced, then overweight marble is in one of the group,
  take that group and weight only two marble,  still balanced?, then the weight marble is the last marble in group 3 otherwise, balance show which marble is over weighted.
