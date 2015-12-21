---
layout: post
title:  "Javascript!"
date:   2015-12-05
---

<span class="image featured"><img src="/images/js.jpg" alt=""></span>
Alright! We are in week 7 people! Ruby is over and we have now started our journey into JavaScript! I wish we could have started with JS because it seems to teach more fundamentals and show how the coding process works. I think this is due to the fact that JS requires you to create functions in order to do some of the things that Ruby has already built in. I'm looking at you enumerables and built in methods! Anyways lets talk about some of the differences between JS and Ruby.

Lets look at some syntax differences between Ruby and JS. Setting variables in Ruby is as simple as stating a name and setting a value.

{% highlight ruby linenos %}
variable_name = variable_value
{% endhighlight %}

In JS setting a variable is the same with the exception of adding 'var' before the name like so.

{% highlight js linenos %}
var variable_name = variable_value
{% endhighlight %}

Lets look at how Hashes look between Ruby and JS. Here is a Ruby Hash.

{% highlight ruby linenos %}
hash_name = { hash_key: hash_value , second_hash_key: second_hash_value}
{% endhighlight %}

Easy enough right? A Hash in JS is reffered to as an 'Object', the 'key' in Ruby is just a variable.

{% highlight js linenos %}
var hash_name = { hash_key: hash_value , second_hash_key: second_hash_value}
{% endhighlight %}

To get the value of a key in a hash in Ruby you just call the hash like so:

{% highlight ruby linenos %}
hash_name[:hash_key] -> hash_value
{% endhighlight %}

In JS you would call the 'Object' to get the value of the key like so:

{% highlight js linenos %}
hash_name.hash_key -> hash_value
{% endhighlight %}

Now lets look at some looping! What are the differences between Ruby loops and JS loops? Not that much really except that JS is more tedious to write. Lets look at 'for' loops below starting with Ruby.

{% highlight ruby linenos %}
for varibale_name != variable_value do
  #actions
   end
end
{% endhighlight %}

Simple enough, we set a condition for our variable and run our 'for' loop. Lets look at how this is done is JS.

{% highlight js linenos %}
for (var i=0; i !== var_value; i++)  {/*actions*/}
{% endhighlight %}

It is less readable and includes more syntax like more curly brackets and semicolons. You set the loop within the 'for' and your code block inside the curly brackets.

These are just some simple things that are different with Ruby and JS. The basic fundamentals of each language are the same. They both manipulate objects, have the same types of conditional statements, they have the same comparison operators, and they use the same types of data structures like arrays and hashes. Ruby is a lot more readable than JS and also easier to understand since Ruby has some built in methods to help with what your looking to do. I think JS is more fundamental and helps you understand programming alot better.






