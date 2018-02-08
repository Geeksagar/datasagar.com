---
ID: 440
post_title: Pickle and cPickle in Python
author: datasagar
post_excerpt: ""
layout: post
permalink: >
  https://datasagar.com/2018/02/07/pickle-and-cpickle-in-python/
published: true
post_date: 2018-02-07 20:32:05
---
Serializing and De-serializing a Python object structure can be done with pickle . Pickle module serialize the object before writing it to specific file. converting the python objects such as list, dict etc into stream of characters is called as pickling. Information contained by thus converted character stream can be used to reconstruct those object in another python script.

Before getting started, do consider the fact that <a class="reference internal" title="pickle: Convert Python objects to streams of bytes and back." href="https://docs.python.org/2/library/pickle.html#module-pickle"><code class="xref py py-mod docutils literal"><span class="pre">pickle</span></code></a> module is not secure against erroneous or maliciously constructed data. Never unpickle data received from an untrusted or unauthenticated source.

Lets get started with pickling up python list.

<strong>First of all you need to import pickle module as</strong>
<pre>import pickle

<strong>Now, import the pickled object and assign it to a variable</strong>

a = ['test value','test value 2','test value 3']
a
['test value','test value 2','test value 3']

file_Name = "testfile"
# open the file for writing
fileObject = open(file_Name,'wb') 

# this writes the object a to the
# file named 'testfile'
pickle.dump(a,fileObject)   

# here we close the fileObject
fileObject.close()
# we open the file for reading
fileObject = open(file_Name,'r')  
# load the object from the file into var b
b = pickle.load(fileObject)  
b
['test value','test value 2','test value 3']
a==b
True


There is also a predecessor to python named cpickle and according to official documentation it is 1000 times faster because of use of C-language.

</pre>
For more on documentation of Pickle and CPickle <a href="https://docs.python.org/2/library/pickle.html">click here</a>

Thanks.