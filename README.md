#!/usr/bin/python
# @author: Afran Shamik | @codebytekeys

class AboutMe:
    def __init__(self):
        self.name = "Afran Shamik"
        self.role = "Student - B.Tech in Computer Science and Engineering"
        self.location = "Chennai, Tamil Nadu (India)"
        self.knowledge_base = [
            "Machine Learning",
            "Deep Learning",
        ]
        self.knowledge_base.insert(0, "Deep Learning")

    def about_me(self):
        print(
            """Hello there, thanks for dropping by!

This is {name}, I live in {location}. I am a {role} and recently I am focusing on {focus} for my personal growth.

I have wide interests, but most of them are {knowledge_base}.

I write down tips and lecture notes on my personal tech blog, which can be found here: {blog}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,
            )
        )

know_more = AboutMe()
know_more.about_me()
