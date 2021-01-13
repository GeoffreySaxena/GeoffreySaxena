### Hi there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class BuddingAnalyst:
    def __init__(self):
        self.name = "Pratik Geoffrey Saxena"
        self.location = "27.2046° N, 77.4977° E"
        self.website = "https://geoffreysaxena.github.io/"
        self.role = "Budding Analyst and Creative Coder"
        self.knowledge_base = [
            "Data Analysis",
            "Machine Learning",
            "Deep Learning",
            "Business Analytics",
        ]
        self.knowledge_base.insert(0, "Data Visualization")

    def say_hi(self):
        print(
            """Greetings humans, thanks for dropping by!

I am {name}, I live in {location}. I am a {role}, off-late I am focusing on {focus} for my personal growth.

I have wide interests, but most of them are {knowledge_base}.

I post about stuff that interests me on: {website}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                website=self.website,
            )
        )


me = BuddingAnalyst()
me.say_hi()

```

<!--
**GeoffreySaxena/GeoffreySaxena** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
