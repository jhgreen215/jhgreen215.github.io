---
layout: page
title: Otto-Bot Twitter Bot 
permalink: /ottobot/
---

# Otto-bot Bot

HackISU is Iowa State University's biannual hackathon. At the Spring 2017 edition, I created a twitter bot out of Otto Bot, the beloved mascot of ISU's student-run radio station, 88.5 KURE.

<figure>
	<img src="{{ site.baseurl }}/assets/otto.jpg" alt="Look, it's Otto Bot!"/>
	<figcaption>The pride and joy of 88.5 KURE, Otto Bot</figcaption>
</figure>

Otto is an automation program that plays tunes on air when there are no DJs in the studio. He has had a twitter account for some time now, but I wanted to bring him to the 21st century. The bot that I created allows him to respond to tweets directed at him that ask some form of the question "What's playing on KURE right now?". I was able to utilize the station's last.fm api to access info for what was currently on air, then format a response to be sent from Otto. 

Prior to this hackathon, I had no experience with node javascript, but throughout the weekend I was able to teach myself enough to create a functioning twitter bot. The bot works by parsing tweets directed at Otto and using regular expressions to look for something along the lines of "What band is this?" or "Who's playing on air?". It then queries the last.fm api and extracts the song name and artist from the resulting JSON file.

You can read more about the project on the [Devpost submission page](https://devpost.com/software/otto-bot-bot) or check out the [GitHub repo](https://github.com/jhgreen215/OttoBotBot). You can also listen to KURE online at [http://www.kure.stuorg.iastate.edu/](http://www.kure.stuorg.iastate.edu/)
