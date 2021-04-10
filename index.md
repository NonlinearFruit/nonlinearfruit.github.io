# Projects

{% for page in site.pages %}
  {% if page.path contains 'project' %}
    {% assign repo = site.github.public_repositories | where: "html_url", page.repo %}
- [{{ page.title }}]({{ page.url }}) » {{ page.description | default: repo.first.description }}
  {% endif %}
{% endfor %}

# About Me
I love learning, creating and merrymaking. Maybe the best way to summarize is through some examples.

## Learning
Here are some things I like learning about:

 - Programming techniques
 - Esoteric programming languages
 - Pure and applied math
 - Linguistics
 
There are a couple resources that I particularly enjoy using:

 - [Crash Course](https://www.youtube.com/user/crashcourse)
 - [Open Courseware](https://ocw.mit.edu/courses/find-by-topic/)
 - [Project Euler](https://projecteuler.net)
 - [Programming Puzzles and Code Golf](https://codegolf.stackexchange.com)
 
## Creating
Here are some things I have created:

 - Minecraft (3,2) turing machine
 - [Domino logic gates](https://codegolf.stackexchange.com/questions/82938/golf-all-the-16-logic-gates-with-2-inputs-and-1-output/91472#91472)
 - [Minimalist Password Manager](https://gist.github.com/NonlinearFruit/7b6f72f97f0d70086f3f229fbf23850f)
 - [Windows enhancing AHK script](https://github.com/NonlinearFruit/Ultimate)
 - Origami
 
## Merrymaking
A lot of my merrymaking activities revolve around interacting with others or picking up a skill that is fun, novel and teachable:

 - Slack lining
 - Juggling
 - Cude solving
 - Rock slinging
 - Board games

# Links
- [CV](https://stackoverflow.com/cv/nonlinearfruit)
- [Stackoverflow](https://stackoverflow.com/users/4769802/nonlinearfruit?tab=profile)
- [Github](https://github.com/NonlinearFruit)
