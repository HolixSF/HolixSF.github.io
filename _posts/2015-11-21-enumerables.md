---
layout: post
title:  "Enumerabararraabless"
date:   2015-11-21
---

<span class="image featured"><img src="/images/methodchain.jpg" alt=""></span>
The weeks are getting harder and harder! This time we are in our second week of coding with Ruby and what a week it was. This week got a bit more advanced and a bit more confusing but im slowly understanding things. Lets talk Enumerables. Yeah its kinda hard to say at first that why my title was like that haha.

Ruby's enumerable module has built in methods for all kinds of things which operate in a collection. Its like trying to use the "each" method when trying to iterate over something but there is a enumerable that does this for what you want to do. So what does enumerable actually mean? The Enumerable module gives objects of collection classes additional collection-specific behaviors. The class requiring the Enumerable module must have an #each method because the additional collection-specific behaviors given by Enumerable are defined in terms of #each. Lets give you an example of one of the enumerable methods, map!

What is map? The map method takes an enumerable object and a block, and runs the block for each element, outputting each returned value from the block. Map can be used non-destructively and destructively by implementing a "!" symbol after it. Basically lets say you have an array of strings and you want to iterate over those strings one by one and add to them or change them.

{% highlight ruby linenos %}
# Here we have an array with 3 string elements
my_array = [ "a", "b" , "c" ]

# We use .map on our array to iterate through the array and add a "!" to each string in the array
my_array.map{ |i| puts i + ! }
 
# This is what we get in return
=> [ "a!" , "b!" ,"c!" ]
{% endhighlight %}

So as you can see, instead of using .each we just used .map. There are other methods similar to this in which you can iterate and modify the given object. So why not use .each like we always do? The difference is .each executes the given block for each element of the array, then returns the array itself. While .map also executes the given block for each element of the array, but returns a new array whose values are the return values of each iteration of the block. Collect is also an enumerable and does the same thing as what map does. Like everything else in Ruby there are more ways than 1 to do things.
