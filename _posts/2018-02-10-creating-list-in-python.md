---
ID: 456
post_title: Creating List in Python
author: datasagar
post_excerpt: ""
layout: post
permalink: >
  https://datasagar.com/2018/02/10/creating-list-in-python/
published: true
post_date: 2018-02-10 15:07:15
---
<p class="exercise--title">Lists are probably the most versatile data structures in Python. A list can be defined by writing a list of comma separated values in square brackets. Lists might contain items of different types. Python lists are mutable - individual elements of a list can be changed while the identity does not change.</p>

<div>
<pre><code class="python">Country =['NEPAL','INDIA','USA','GERMANY','UK','AUSTRALIA']

Temperature =[22, 44, 28, 20, 18, 25, 45, 67]</code></pre>
We just created two lists, one for Country names (strings) and another one for Temperature data (whole numbers).
<h4>Accessing individual elements of a list</h4>
<ul>
 	<li>Individual elements of a list can be accessed by writing an index number in square bracket. The first index of a list starts with 0 (zero) not 1. For example, Country[0] can be used to access the first element, 'INDIA'</li>
 	<li>A range of elements can be accessed by using start index and end index but it does not return the value of the end index. For example, Temperature[1:4] returns three elements, the second through fourth elements [28, 20, 18], but not the fifth element</li>
</ul>
<h2>Tasks</h2>
<strong># Create a list of squared numbers</strong>
squares_list = [0, 1, 4, 9, 16, 25]

<strong># Now write a line of code to create a list of the first five odd numbers and store it in a variable odd_numbers</strong>
odd_numbers= [1, 3, 5, 7, 9]

<strong># Print the first element of squares_list</strong>
print (squares_list[0])

<strong># Print the second to fourth elements of squares_list</strong>
print(squares_list[1:4])

</div>
Practice it in DataCamp <a href="https://campus.datacamp.com/courses/introduction-to-python-machine-learning-with-analytics-vidhya-hackathons/python-libraries-and-data-structures?ex=1">here</a>