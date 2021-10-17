# Hello there!


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from earth.life import Human


class Arnewitt(Human):
    
    def __init__(self):
        self.name = "Arne"
        self.job = "Data Engineer"
        self.passion = ["Data Engineering", "Data Science", "Software Engineering"]
        
    def introduce(self) -> str:
        """
        Introduce myself briefly.
        
        :param: None
        :return: Str Introduction
        """
        print("Hi, nice to meet you! My name is Arne, I am looking forward to connect and collaborate!")
 
 
 arne = Arnewitt()
 arne.introduce()
 ```
 
