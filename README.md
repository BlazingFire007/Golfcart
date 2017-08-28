# Golfcart
Golfcart is a JavaScript library for code golfing.


The current version (0.1) was made public at **12 PM CT on August 28th**. 

This library should not be used with any challenges before then.


Function creator
------
Golfcart comes with a built in function, f. This function is used to create other functions. It takes one parameter, an Array. The 0 index of the Array needs to be a String. 

It should look somethng like: `ab b-a`. 

This returns a new function that looks like: `(a,b)=>b-a;`.

You can also use brackets if you want: `ab {return b-a}`.

Will return a function that looks like `(a,b)=>{return b-a};`.

Midpoint function: ``m=f`abxy [(a+x)/2,(b+y)/2]``

Usage: ``m(-1,2,3,-6)//returns [1,-2]``
