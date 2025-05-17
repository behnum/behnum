### Behnam Baharmand

[![Linkedin Badge](https://img.shields.io/badge/linkedin-baharmand-blue)](https://www.linkedin.com/in/baharmand)
[![Gmail Badge](https://img.shields.io/badge/gmail-bbaharmand%40gmail.com-red)](mailto:bbaharmand@gmail.com)

#### About Me

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-
import datetime


class Behnam:
    def __init__(self):
        self.first_name = "Behnam"
        self.last_name = "Baharmand"
        self.pronouns = "he/him"
        self.email = "bbaharmand@gmail.com"
        self.interests = [
            {
                "category": "Fitness",
                "hobby": "Skipping Rope",
                "duration": "5 years",
                "achievements": [
                    "Survived the 30-day skipping challenge.",
                    "Mastery of advanced skipping tricks, such as double-unders and crossovers.",
                ],
            },
            {
                "category": "Creative Pursuits",
                "hobby": "Photography",
                "style": "Landscape and Nature",
                "equipment": ["Nikon D7100", "Prime and zoom lenses"],
                "projects": [
                    "Cityscape Wonders photo series.",
                    "Collaborated with local magazine for cover photo.",
                ],
                "portfolio_link": "[https://www.behnum.com/]",
            },
            {
                "category": "Creative Pursuits",
                "hobby": "Graphic Design",
                "tools": ["Adobe Creative Suite (Photoshop, Illustrator, InDesign)"],
                "specializations": [
                    "UI/UX design and branding.",
                    "Web and social media graphics.",
                    "Print collateral for events and promotions.",
                ],
                "portfolio_link": "[https://www.behinweb.com/archive]",
            },
        ]

    def hello_world(self):
        print("I'm Behnam! :)")
        print(
            "In my spare time, I tend to spend 5 days automating something I could do in 5 minutes."
        )

    def collaborate(self, interested: bool):
        if interested:
            print("I find joy in collaboration!")
            print(
                "If you have projects that you are passionate about, let me know! I'd love help if I can."
            )

    def contact_me(self):
        print(f"Feel free to send me a message at {self.email}")


if __name__ == "__main__":
    me = Behnam()
    me.hello_world()
```

#### Toolbox

I have some level of knowledge between _"adequately instructing seasoned developers"_ and _"acknowledging the inadequacy with a tinge of guilt"_ for each of the following.

| Programming  | Technologies and Concepts                   | Tools and Practices                          |
| ------------ | ------------------------------------------- | -------------------------------------------- |
| JavaScript   | Node.js                                     | Testing (Unit, Components, Integration)      |
| TypeScript   | ExpressJS                                   | Docker                                       |
| HTML         | REST API                                    | CI/CD                                        |
| CSS          | RDBMS/NoSQL (MySQL, PostgreSQL, MongoDB)    | Source Control                               |
| PHP          | Firebase                                    | Build system and bundlers                    |
| Python       | AWS                                         | WebSockets                                   |
