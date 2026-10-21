

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:

    def __init__(self):
        self.name = "Jade (Jung) Ahn"
        self.major = "Data Science"
        self.current_status = "Master"
        self.interest = [ "Open Source Contribution",
                            "AI Safety","Agent Safety",
                            "AI Social Intelligence",
                            "AI Society Safety"]
        self.language_spoken = ["en_US", "ko_kr", "ja_JP"]

    def welcome(self):
        print("Welcome!!")

me = SoftwareEngineer()
me.welcome()
```
