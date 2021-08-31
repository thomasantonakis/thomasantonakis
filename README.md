### Hi there 👋

<!--
**thomasantonakis/thomasantonakis** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


```python 
#!/usr/bin/python
# -*- coding: utf-8 -*-

class Me:
    """
    A class to represent a person.
    """
    def __init__(self):
        self.name = "Thomas Antonakis"
        self.role = "Senior Business Intelligence Analyst"
        self.employer = "Orfium"
        self.bsc_studies = ("Statistics", "Statistics Dept.", "Athens University Of Economics & Business")
        self.msc_studies = ("Computational Methods in Decision Making", "Statistics Dept.", "Athens University Of Economics & Business")
        self.language_spoken = ["el_GR", "en_US", "it_IT", "fr_FR", "es_ES"]
        self.country = "Greece"
        self.city = "Athens"
        

    def say_hi(self):
        print("Thanks for stopping by, hope you find some of my work interesting!")


thomas = Me()
thomas.say_hi()
```
