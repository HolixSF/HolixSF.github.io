---
layout: post
title:  "Array here, Hash there?"
date:   2015-11-14
---

<span class="image featured"><img src="/images/ruby.png" alt=""></span>
We are at the end of week 4 and my head is burnt out on math and conditional statements! We did a huge refresh on the Ruby language this week and boy what a refresh it was. It started on a pretty easy review of basic Ruby like variables and methods, stuff that we sort of learned before starting phase 0. Then thats when it got harder for me. It went on to control flow with conditional statements and then we had to start thinking about math processes. Math that I haven't done since high school! This stuff really picked at my brain and got me super frustrated. After all that it went on to Arrays and Hashes. What a review huh.

What is an Array and what is a Hash? Lets start with an Array. An Array is a list of objects that are indexed by an integer. It could be a list of strings, numbers or even have an array inside an array. The list is numbered starting from 0. So if we were to have an array with 5 objects in it, we would number them from 0 to 4. Think of a grocery list with 5 items in it. If I wanted to see what the third item on the list was I would look for the number 2 since 0 would be the first and 1 would be the second on the list. Here is an example of an Array.

{% highlight ruby linenos %}
my_array = [ object1, object2, object3 ]
{% endhighlight %}

We have named the array "my_array" and whatever is inside the array is denoted with brackets. We have 3 objects inside of our array and the 3 objects are numbered or indexed starting with 0. So object1 would be 0 on the list and object2 would be 1 on the list and then object3 would be 2 on the list. The values in an Array can be accessed by its index number.

Lets look into Hashes now. A Hash in like an Array as it is also a list of objects, but the difference is a Hash is indexed by another object resulting in a key and value pair. In an Array the key would be its number or index number, on the list and its value is the objects. Meanwhile in a Hash, the key is another object representing a value of another object. Lets go back to our grocery list shall we. If we made out grocery list into a hash and had 5 items on the list, we can also put the price of each item next to it. So our key would be the item, say ice cream, and then we would then give it a value of $3. In a Hash we would have pairs of keys and values and we can access those values by calling on its key. Here is an example of a Hash.

{% highlight ruby linenos %}
my_hash = { object1 => value1,
			   object2 => value2,
			   object3 => value3 }
{% endhighlight %}

Here we named our Hash "my_hash" and whatever is inside the hash is denoted with curly brackets. We have 3 key:value pairs in our hash. Object1 is tied to value1 and object2 is tied to its value2, so on and so forth. A Hash is similar to an Array except its values are not accessed by an index number. If we wanted to get value3 we would then have to call on object3. The values in a Hash are accessed by another object.

Choosing which to use is entirely up to you and what type of list or code you are writing. I think that for something simple that you just need to make a numbered list for I would go with an Array. If you wanted to create something more complicated that has multiple things with multiple values I would go with a Hash.