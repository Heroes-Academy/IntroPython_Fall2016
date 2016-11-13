[Week 7] Advanced collections and functions
===========================================

I have written up a cookbook for you all to use in solving problems!
You can find it by :doc:`clicking here <tutorials/cookbook>`

Refresher
---------

At the start of class, you will be working on the refresher:
:doc:`refresher link <refreshers/week7_refresher>`

Exercises
---------

Today, there are only a couple exercises involving dictionaries and using functions as values.
You can find them by `clicking here <exercises/week7>`.

Projects
--------

When you finish exercises, and over the week, you should be working on your projects.
I have written a couple tutorials to assist you in accomplishing them:

1. :doc:`Minecraft Architect <tutorials/f16_minecraft_architect>`
2. :doc:`Interactive Stories <tutorials/f16_interactive_stories>`
3. :doc:`Animation <tutorials/f16_animation>`



Content wise, we will cover dictionaries first.

Then, I will talk about functions as values.

to illustrate, use map and filter


Finally, i will briefly introduce the various projects and them start to go over that.


to reiterate:

1. Refresher + introduce cookbook
2. dictionaries
3. functional ideas
4. maybe simple classes as storage containers
5. projects









Day 7: More Functions and Intro to Minecraft
=============================================

Take Home Work
--------------



Review
------



Python Classes
**************
Finally, we learned the basics of defining and using our own custom-made object classes. The basic idea behind **defining** a class is that you're writing a recipe for a particular type of object. you can think of it like this: if you have a room full of chairs, each of those chairs is a chair object, but "chair" would be the name of the class.

After you've defined a class (written your recipe), you can use it to make copies of your custom-made object in code. The Lecture Slides have example code in case you forget!

See the "Extra Resources" section for examples. In short, the proper syntax is this:
::
	class <Class_Name>:
		property_a = value_a
		property_b = value_b
		property_c = value_c

		def some_class_function(self)
			<code>
			<code>
			<code>

Remember, classes have two very important features in Python: **properties**, which are details about the object that describe it, and **functions**, which are things that the object can **do**.

For example, a ``Dog`` object in Python might have the properties ``name``, ``age``, ``height``, etc., and functions like ``run(self)``, ``bark(self)``, and ``fetch(self)``. Remember that when you're defining functions inside an object, you need to make the first argument (the first thing in the parentheses) the keyword ``self``, which tells Python, "this function belongs to this object type."

Similarly, inside of a class's function, if you want to reference one of that class's properties, you also need to use the ``self`` keyword. So, in the ``bark(self)`` function for a dog, if you wanted to print its name, it would look like this:
::
	def bark(self)
		print("Hello! My name is " + self.name)

Don't forget the ``self`` keyword!


Lecture Slides
--------------

.. raw:: html

    <iframe src="https://docs.google.com/presentation/d/1NN_ABGEUyzSj3ntAICFilRvRDkJhXz7qn75RWlCI5uE/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
