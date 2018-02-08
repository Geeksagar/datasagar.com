---
ID: 108
post_title: 'Introduction to NumPy: useful cheat sheets'
author: datasagar
post_excerpt: ""
layout: post
permalink: >
  https://datasagar.com/2018/01/21/numpy-cheat-sheets/
published: true
post_date: 2018-01-21 08:42:19
---
<img class="size-medium wp-image-367 alignleft" src="https://datasagar.com/wp-content/uploads/2015/03/numpy_project_page-300x169.jpg" alt="" width="300" height="169" />The NumPy library is the core library for scientific computing in Python. It provides a high-performance multidimensional array object, and tools for working with these arrays. This post is an effort to collect useful numpy commands in one place to make your computing task easier. Before moving forward, make sure that you've installed Python and NumPy library in your system.

<!--Read More-->

&nbsp;

To install Python in Windows follow previous article <a href="https://datasagar.com/2017/12/24/python-installation-windows10/">here</a>

To install NumPy library follow <a href="https://www.youtube.com/watch?v=-llHYUMH9Dg">this</a> YouTube video
<h3>First of all, after installing Numpy library, use the following import convention:</h3>
<blockquote><strong>&gt;&gt;&gt; import numpy as np</strong></blockquote>
<h3><span style="text-decoration: underline;">To create NumPy arrays</span></h3>
<blockquote><strong>&gt;&gt;&gt; a = np.array([1,2,3])</strong>
<strong>&gt;&gt;&gt; b = np.array([(1.5,2,3), (4,5,6)], dtype = float)</strong>
<strong>&gt;&gt;&gt; c = np.array([[(1.5,2,3), (4,5,6)], [(3,2,1), (4,5,6)]], dtype = float)</strong></blockquote>
here,  a is 1D - array, b is 2D array and c is 3D array

&nbsp;
<h3><span style="text-decoration: underline;"><strong>Use of initial place holders:</strong></span></h3>
<blockquote><strong>&gt;&gt;&gt; np.zeros((3,4))</strong> Create an array of zeros
<strong>&gt;&gt;&gt; np.ones((2,3,4),dtype=np.int16)</strong> Create an array of ones
<strong>&gt;&gt;&gt; d = np.arange(10,25,5)</strong> Create an array of evenly spaced values (step value)
<strong>&gt;&gt;&gt; np.linspace(0,2,9)</strong> Create an array of evenly spaced values (number of samples)
<strong>&gt;&gt;&gt; e = np.full((2,2),7)</strong> Create a constant array
<strong>&gt;&gt;&gt; f = np.eye(2)</strong> Create a 2X2 identity matrix
<strong>&gt;&gt;&gt; np.random.random((2,2))</strong> Create an array with random values
<strong>&gt;&gt;&gt; np.empty((3,2))</strong> Create an empty array</blockquote>
&nbsp;
<h3><span style="text-decoration: underline;"><strong>Basic I/O </strong></span></h3>
<h5><strong>Saving &amp; Loading On Disk</strong></h5>
<blockquote><strong>&gt;&gt;&gt; np.save('my_array', a)</strong>
<strong>&gt;&gt;&gt; np.savez('array.npz', a, b)</strong>
<strong>&gt;&gt;&gt; np.load('my_array.npy')</strong></blockquote>
<h5><strong>Saving and Loading Text Files</strong></h5>
<blockquote><strong>&gt;&gt;&gt; np.loadtxt("myfile.txt")</strong>
<strong>&gt;&gt;&gt; np.genfromtxt("my_file.csv", delimiter=',')</strong>
<strong>&gt;&gt;&gt; np.savetxt("myarray.txt", a, delimiter=" ")</strong></blockquote>
<h3><span style="text-decoration: underline;">To Inspect Your array</span></h3>
<blockquote><strong>&gt;&gt;&gt; a.shape Array dimensions</strong>
<strong>&gt;&gt;&gt; len(a) Length of array</strong>
<strong>&gt;&gt;&gt; b.ndim Number of array dimensions</strong>
<strong>&gt;&gt;&gt; e.size Number of array elements</strong>
<strong>&gt;&gt;&gt; b.dtype Data type of array elements</strong>
<strong>&gt;&gt;&gt; b.dtype.name Name of data type</strong>
<strong>&gt;&gt;&gt; b.astype(int) Convert an array to a different type</strong></blockquote>
&nbsp;

&nbsp;