## Introduction
    
My name's Robert Dominguez and I am currently attending the Deep Dive Coding Java + Android Bootcamp.
I have a bachelor's degree in compuer science from Southwesetern Adventist University and believe that 
the Deep Dive Coding Bootcamp will greatly improve my programming skills. My plan after graduation is to
work on personal projects while looking for employment as a Java programmer.
	
## Current projects

* [Hello World: Java console application](https://github.com/Dominguez1st/deep-dive-hello-world-ij)
      
* [Hello World: Android app](https://github.com/Dominguez1st/android-hello-world)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/robert-dominguez-0a5553178/)