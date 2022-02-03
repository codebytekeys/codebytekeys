#!/usr/bin/python
# @author: Afran Shamik | @codebytekeys

class AboutMe:
    def __init__(self):
        self.name = "Afran Shamik"
        self.role = "Student - Bsc in Physics"
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

know_more = AboutMe()
know_more.about_me()
