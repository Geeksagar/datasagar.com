---
ID: 85
post_title: How to install python in Windows 10?
author: datasagar
post_excerpt: >
  The young team of Franziska Hildebrand,
  Franziska Preuss, Vanessa Hinz and
  Dahlmeier clocked 1 hour, 11 minutes,
  54.6 seconds to beat France
layout: post
permalink: >
  https://datasagar.com/2017/12/24/python-installation-windows10/
published: true
post_date: 2017-12-24 06:56:42
---
This document shows downloading and installing Python 3.6.2 on Windows 7 in Summer 2017. <b>You should download and install the latest version of Python.</b> The current latest (as of Fall 2018) is Python 3.6.4.
<h2>Python: Version 3.6.4</h2>
The Python download requires about 30 Mb of disk space; keep it on your machine, in case you need to re-install Python. When installed, Python requires about an additional 90 Mb of disk space.
<h3>Downloading</h3>
<ol>
 	<li>Click <a href="https://www.python.org/downloads/" target="_blank" rel="noopener">Python Download</a>.The following page will appear in your browser.<img class="alignnone wp-image-333" src="https://datasagar.com/wp-content/uploads/2015/03/python1-300x213.jpg" alt="" width="400" height="284" /></li>
 	<li>Click the <b>Download Python 3.6.4</b> button.The file named <b>python-3.6.4.exe</b> should start downloading into your standard download folder. This file is about 30 Mb so it might take a while to download fully if you are on a slow internet connection (it took me about 10 seconds over a cable modem).The file should appear as<img src="https://www.ics.uci.edu/~pattis/common/handouts/pythoneclipsejava/images/python/exefile.jpg" /></li>
 	<li>Move this file to a more permanent location, so that you can install Python (and reinstall it easily later, if necessary).</li>
 	<li>Feel free to explore this webpage further; if you want to just continue the installation, you can terminate the tab browsing this webpage.</li>
 	<li>Start the <b>Installing</b> instructions directly below.</li>
</ol>
&nbsp;

<strong>INSTALLATION PROCESS</strong>
<ol>
 	<li>Double-click the icon labeling the file <b>python-3.6.2.exe</b>.An <b>Open File - Security Warning</b> pop-up window will appear.</li>
 	<li>Click <b>Run</b>.A <b>Python 3.6.2 (32-bit) Setup</b> pop-up window will appear.</li>
 	<li>Ensure that the <b>Install launcher for all users (recommended)</b> and the <b>Add Python 3.6 to PATH</b> checkboxes at the bottom are checked.If the Python Installer finds an earlier version of Python installed on your computer, the <b>Install Now</b> message will instead appear as <b>Upgrade Now</b> (and the checkboxes will not appear).</li>
 	<li>Highlight the <b>Install Now</b> (or <b>Upgrade Now</b>) message, and then click it.A <b>User Account Conrol</b> pop-up window will appear, posing the question <b>Do you want the allow the following program to make changes to this computer?</b><img class="wp-image-340 aligncenter" src="https://datasagar.com/wp-content/uploads/2017/12/setup1-300x185.jpg" alt="" width="532" height="328" /></li>
 	<li>Click the <b>Yes</b> button.A new <b>Python 3.6.2 (32-bit) Setup</b> pop-up window will appear with a <b>Setup Progress</b> message and a progress bar.</li>
 	<li>During installation, it will show the various components it is installing and move the progress bar towards completion. Soon, a new <b>Python 3.6.2 (32-bit) Setup</b> pop-up window will appear with a <b>Setup was successfuly</b> message.
<ol>
 	<li>Click the <b>Close</b> button.<img class="alignnone size-medium wp-image-339" src="https://datasagar.com/wp-content/uploads/2017/12/setup2-300x188.jpg" alt="" width="300" height="188" /></li>
</ol>
</li>
 	<li>Python should now be installed.</li>
</ol>
<strong>VERIFYING INSTALLATION</strong>

To try to verify installation,
<ol>
 	<li>Navigate to the directory <b>C:\Users\Pattis\AppData\Local\Programs\Python\Python36-32</b> (or to whatever directory Python was installed: see the pop-up window for Installing step 3).</li>
 	<li>Double-click the icon/file <b>python.exe</b>.The following pop-up window will appear.</li>
 	<li>A pop-up window with the title <b>C:\Users\Pattis\AppData\Local\Programs\Python\Python36-32</b> appears, and inside the window; on the first line is the text <b>Python 3.6.2 ...</b> (notice that it should also say 32 bit). Inside the window, at the bottom left, is the prompt <b>&gt;&gt;&gt;</b>: type <b>exit()</b> to this prompt and press <b>enter</b> to terminate Python.You should keep the file <b>python-3.6.2.exe</b> somewhere on your computer in case you need to reinstall Python (not likely necessary).<img class="alignnone size-medium wp-image-338" src="https://datasagar.com/wp-content/uploads/2017/12/python3-300x169.jpg" alt="" width="300" height="169" />You may now follow the instructions to download and install Java (if you have not already done so), and then the instruction to download and install the Eclipse IDE (for Python, Java, or both ). Note: you you need to download/install Java even if you are using Eclipse only for Python)</li>
</ol>