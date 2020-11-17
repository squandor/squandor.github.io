---
layout: page
#
# Content
#
subheadline: "Datatypes"
title: "The common datatypes in python"
teaser: "Python has a lot of different datatypes which you will encounter so lets start with the most common used."
categories:
  - Basics
tags:
  - Python
  - Datatypes
  - Basics
  - Examples
#
# Styling
#
header: no
mediaplayer: false
comments: true
---

Inside python you have different datatypes which you can use or will encounter. 
The basic/most often datatypes are:
- String
- Integer
- Float
- List
- Dictionary

But before we will see what different options each datatype has you first need to know some things:
- First, what are comments?. 
A Comment is just some kind of text which will not be run by python but will make youre life easier if you learn from the start to use it.
You can use comments to explain what a line or piece of code does inside the program.
Every Comment inside python starts with an # 
But beware, if you read further i will show you some examples where a peace of code looks like an comment but really isn't. 
- Second, what are variables?.
A variable is an piece of memory which you can reserve to save data on the fly. In my examples i always start my variables with an underscore _. 
Its not needed but this way i always know which codes are variables. 
To save some kind of info to an variable you first need to give the variable a name and follow that name with an = 

For example:
{% highlight python %}
_hello = 
{% endhighlight %}

So the name of the variable is _hello and with the = i said that everything that comes next will be put inside _hello, be aware that at this point the "datatype" of the variable 
is still nothing. That will change depending on the data you will use after the = 

So lets start first with the datatypes:
## String
Simple said an String is not an piece of underware but a piece of text inside python. If you want to create an string you simple use quotes around some text. 
So lets say i want to create an string with the words Hello World inside of it i can simple say:
{% highlight python %}
'Hello World'
{% endhighlight %}
or
{% highlight python %}
"Hello World"
{% endhighlight %}

Python will see both examples as an String. 
So if i want to save the string "Hello World" to the variable _hello you can simply use:
{% highlight python %}
_hello = 'Hello World'  # saving string to variable
print(_hello)           # Print variable to console
{% endhighlight %}

In this example i saved the string "Hello World" to the variable _hello and on the second line i wrote that i want to print the variable to the console to check if the text
is really saved to the variable. 
