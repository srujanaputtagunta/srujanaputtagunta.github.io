---
layout: post
title: Installing IDE and Hello World!
comments: true
image:
  feature: sample-image-5.jpg
  credit: WeGraphics
---

###Installing IDE 

After lot of research on Python IDEs, I decided to use Eclipse: [Download link](http://www.eclipse.org/downloads/packages/). The latest release at the time of writing this was the [Luna package](http://www.eclipse.org/downloads/packages/release/Luna/R). I downloaded the [Mac OS X 64-bit version](http://www.eclipse.org/downloads/packages/eclipse-standard-44/lunar)

The Eclipse that I downloaded is pretty generic and is not aware of Python. So I had to install [Python plugin for Eclipse](http://pydev.org/manual_101_install.html). This was pretty easy. Under available update sites: I chose the link under main (not nightly)

{% highlight css %}
Open Eclipse
> Help
> Install new software
> work with: http://pydev.org/updates
> choose select all
> next
{% endhighlight %}

![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/2/IDE_setup.png)

>>That will install: <br/>
1. PyDev <br/>
2. PyDev Mylyn Integration (optional)	

Restart Eclipse. I then configured Eclipse to use latest Python:

{% highlight css %}
Open Eclipse 
> Preferences 
> PyDev
> Interpreters 
> Python Interpreter 
> Quick Auto-Config
> Apply 
> click ok
{% endhighlight %}

###Hello Python!

To create a new Project:

{% highlight css %}
File 
> New
> PyDev Project 
> Project Name: HelloPython 
> Finish
{% endhighlight %}

To create a new module:

{% highlight css %}
New 
> PyDev module (see below images) 
> Finish
{% endhighlight %}

![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/2/create_new_py_module.png)

<br/>Select Module: Main from the below options:<br/>
<br/>![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/2/module_options.png)

<br/>The above creates a file called version.py with the following contents:

{% highlight ruby %}
'''
Created on Feb 20, 2015

@author: srujanaputtagunta
'''

if __name__ == '__main__':
    pass
{% endhighlight %}


Let's write our first program. I just added a new line to the existing code:

{% highlight ruby %}
'''
Created on Feb 20, 2015

@author: srujanaputtagunta
'''
print "Hello Python!"

if __name__ == '__main__':
    pass
{% endhighlight %}

Running Hello Python:

{% highlight css %}
Right click on the editor 
> Run As 
> Python Run
{% endhighlight %}

That prints `Hello Python!` in our console. <br/>
Before we quit Eclipse, let's just make sure that our Eclipse is using the latest Python that we installed.

{% highlight ruby %}
'''
Created on Feb 20, 2015

@author: srujanaputtagunta
'''
import sys
print sys.version_info

if __name__ == '__main__':
    pass
{% endhighlight %}
    

This prints: `sys.version_info(major=2, minor=7, micro=6, releaselevel='final', serial=0)`

<br/>The above output shows version 2.7.6 but we installed the latest version - 2.7.9. So let's make sure that our Eclipse uses the latest Python Interpreter.

<br/>![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/2/Interpreter_preference.png)

{% highlight css %}
Right click on our project: HelloPython 
> Properties 
> PyDev Interpreter/Grammar 
> change Interpreter to python1 
> Apply 
> Ok
{% endhighlight %}

Rerun our version.py. You should now see: 
`sys.version_info(major=2, minor=7, micro=9, releaselevel='final', serial=0)`


<br/>YAYYY!!!







