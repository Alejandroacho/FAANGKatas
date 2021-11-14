# Music List Kata

### Description

A FAANG company that owns a music service wants to give their customers the best experience when they have a bus ride. To achieve that they must know the ride duration to bring the best songs comibnation to the customer based on a list.

* From a list of songs they want to bring **exactly two songs** that its duration fits perfectly with the **bus travel duration minus 30 seconds**.
* If you have two or more pairs of songs, you must return the one which contains the longest song.

You must write a function that receives 2 parameters (the bus travel duration expressed in total seconds, and a list of songs duration expressed in total seconds too) and returns a list with the original lists position of the picked songs.

### Example

Parameter 1 : 150

Parameter 2 : [ 30, 65, 35, 55, 40, 70, 50, 80 ]

Expected return : [ 4, 7 ]

Explanation : The function must look for a pair of songs that their durations combined are exactly 120. You may found 3 pairs:

* 65, 55
* 70, 50
* 40, 80

So the pair with the longest song duration is the one with the song with 80s of duration, so this is the pair you must return.
