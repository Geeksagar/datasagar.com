---
ID: 460
post_title: Working with String in Python
author: datasagar
post_excerpt: ""
layout: post
permalink: >
  https://datasagar.com/2018/02/10/working-with-string-in-python/
published: true
post_date: 2018-02-10 15:27:16
---
<h1 class="exercise--title">Create a String</h1>
<div>

Strings can simply be defined by use of single ( ‘ ), double ( ” ) or triple ( ”’ ) inverted commas. Strings enclosed in triple quotes ( ”’ ) can span over multiple lines. A few things to keep in mind about strings:
<ul>
 	<li>Strings are immutable in Python, so you can not change the content of a string.</li>
 	<li>Function len() can be used to get length of a string</li>
 	<li>You can access the elements using indexes as you do for lists</li>
 	<li>You can use '+' operator to concatenate two strings</li>
</ul>
<h2><code class="python">String ="String elements can also be accessed using index numbers, just like lists"

print (String[0:7])

#Above print command displays "String " on screen.</code>

TASKS TO DO</h2>
<strong># Create a string str1</strong>
str1 = "Introduction with strings"

<strong># Now store the length of string str1 in variable str_len</strong>
str_len = len(str1)

str_new = "Machine Learning is awesome!"
<strong># Print last eight characters of string str_new (the length of str_new is 28 characters).</strong>
print(str_new[20:28])

str2 = "I am doing a course Introduction to Hackathon using "
str3 = "Python"

<strong># Write a line of code to store concatenated string of str2 and str3 into variable str4</strong>
str4 = str2 + str3

</div>
Try it yourself in DataCamp <a href="https://campus.datacamp.com/courses/introduction-to-python-machine-learning-with-analytics-vidhya-hackathons/python-libraries-and-data-structures?ex=2">here</a>