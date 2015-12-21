---
layout: post
title:  "Class is in session"
date:   2015-11-30
---

<span class="image featured"><img src="/images/class.jpeg" alt=""></span>
So the holidays are starting and I am finding that keeping up with DBC is starting to get difficult. It didn't think that it would require so much of my time but every week seems to get harder and harder. This week was out third week of learning Ruby and it was during Thanksgiving and all the ridiculous Black Friday sales. I think the best part of this week was learning about Ruby classes.

During the beginning I learned that everything in Ruby is an object. Everything we have been learning originally stems from an object. We learned to add methods and create properties to already existing objects. Now we can create those objects and add our own methods and properties by creating a new object class. We can start a new class using this syntax:

{% highlight ruby linenos %}
class Person

end
{% endhighlight %}

We will use this example to create our new Person class. When creating a class we can give it an auto setup or some sort of code that automatically gives that class some properties. In Ruby we call this a constructor method. When creating a class the contructor method is named initialize and we can go ahead and put some properties to our Person class using this method.

{% highlight ruby linenos %}
class Person
  def initialize(name, age)
    @name = name
    @age = age
  end
end
{% endhighlight %}

Now we have some properties, name and age, to our Person class. You may have noticed that theres an '@' symbol there. That creates an instance variable, which we can use throughout the instance of this class. Pretty cool huh. Now we can create instance methods and use the instance variables we just made. Like this!

{% highlight ruby linenos %}
def greet
  puts "#{@name} says, 'Hello there!'"
end
{% endhighlight %}

Now that we have created our class, given it some properties and made a method to use those properties, lets see how we can use these. We can now create a new instance of our class below and call the method we created.

{% highlight ruby linenos %}
# this will create an instance of our Person class
Person.new("James", 25)

# this will call the greet method on the new instance of Person
new_person.greet

# this will be the output
=> James says, 'Hello there!'
{% endhighlight %}

As you can see creating classes is very useful in Ruby. It allows us create instances so that we don't have to keep repeating code. A class is like the blueprint for any object we create so having that blueprint allows us to create or modify that object multiple times. I hope I explained classes simple enough to understand. I wanted to go over the basics so we can have a good foundation on creating a class. I can always expand on this so let me know!