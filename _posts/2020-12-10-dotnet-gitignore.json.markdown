---
layout: post
title:  "Creating gitignore with dotnet"
date:   2020-12-10 20:03:00 -4
categories: [ruby]
---
The new dotnet 5.0 came with other features appart of libraries and code. Now there is no more need to search github for a .gitignore file for Visual Studio. Searching for a gitignore template file when creating a new project but no more became part of my workflow after I learned what gitignore was all about.
With just a simple command it will create the gitignore file you need. Just go into the directory of the project and type this.

{% highlight shell %}
dotnet new gitignore
{% endhighlight %}

Hope this helps you