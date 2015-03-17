---
layout: post
title: Installing Python
comments: true
image:
  feature: sample-image-5.jpg
  credit: WeGraphics
---

I usually use [homebrew](http://brew.sh/) as the package manager in my Mac. Mac OS usually comes with Python pre-installed. So I checked my Python version by entering the following at the terminal:

{% highlight bash %} $ python {% endhighlight %}

{% highlight yaml %} Python 2.7.6 (default, Sep  9 2014, 15:04:36) 
[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.39)] on darwin
Type "help", "copyright", "credits" or "license" for more information. {% endhighlight %}

The logs showed that a new python version is available. So I wanted to make sure I am using the latest Python version. I entered:


{% highlight bash %} $ brew upgrade python {% endhighlight %}

The above command automatically updated my Python to 2.7.9. So when I entered the command 'python' now, it showed the latest version


{% highlight bash %} $ python {% endhighlight %}

{% highlight yaml %} Python 2.7.9 (default, Feb 20 2015, 18:11:15) 
[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.56)] on darwin
Type "help", "copyright", "credits" or "license" for more information. {% endhighlight %}