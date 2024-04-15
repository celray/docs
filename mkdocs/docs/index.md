{% extends "base.html" %}

{% block outdated %}
  You're not viewing the latest version.
  <a href="{{ '../' ~ base_url }}"> 


    <strong>Click here to go to latest.</strong>
  </a>
{% endblock %}

# SWAT+ Toolbox v1.0.1

SWAT+ is relatively new, and there are not so many tools to carry out model analysis and calibration. SWAT+ Toolbox is a free tool that allows the user to perform sensitivity analyses, calibration and more. The software has been written in C# and is available for the Windows operating system. We are still exploring how to bring this to Linux and Mac through .Net Core and the Avalonia project. 

There are built-in updates through which more features, functionalities and bug fixes will are delivered. Check for updates as soon as you install. 
To check for updates, go to the 'about' section and click 'Check for Updates'.

![ASWAT+ Toolbox](images/start-page.png "Start Page")
