---
ID: 463
post_title: Creating dictionary in Python
author: datasagar
post_excerpt: ""
layout: post
permalink: >
  https://datasagar.com/2018/02/10/creating-dictionary-in-python/
published: true
post_date: 2018-02-10 15:47:02
---
<p class="exercise--title">A Dictionary is an unordered set of key:value pairs, with the requirement that the keys are unique (within a Dictionary). A few pointers about dictionary:</p>

<div>
<div>
<ul>
 	<li>An empty dictionary can be created by a pair of braces: {}.</li>
 	<li>Dictionary elements can be accessed by dictionary keys</li>
 	<li>DICT.keys() will return all the keys of given dictionary "DICT"</li>
</ul>
<code class="python">DICT = {
  'Name':'Kunal',
  'Company':'Analytics Vidhya'
  }

#Dictionary elements can be accessed by keys

print (DICT['Name'])

#The above print statement will print Kunal
</code>

In dictionary "DICT", Name and Company are dictionary keys whereas "Kunal" and "Analytics Vidhya" are their respective values.

Other Tasks:

<strong># Create a dictionary dict1</strong>
dict1 = { 'Age': 16, 'Name': 'Max', 'Sports': 'Cricket'}

<strong># Update the value of Age to 18</strong>
dict1['Age'] = 18

<strong># Print the value of Age</strong>
print(dict1['Age'])

<strong># Store the keys of dictionary dict1 to dict_keys</strong>
dict_keys = dict1.keys()

</div>
Try it yourself in DataCamp <a href="https://campus.datacamp.com/courses/introduction-to-python-machine-learning-with-analytics-vidhya-hackathons/python-libraries-and-data-structures?ex=3">here</a>

</div>