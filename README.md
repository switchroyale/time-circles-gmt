# TimeCircles GMT
A small change to Wim Barelds' TimeCircles plugin to use GMT time for more accurate countdowns no matter where a user is in the world.
 See the original repository [here](https://github.com/wimbarelds/TimeCircles).

The key is to update the "data-date" attribute with a GMT friendly date and time:

`data-date="Mon Mar 16 2020 00:00:00 GMT-7"`
