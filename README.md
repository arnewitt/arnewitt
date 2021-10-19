# Hello there!


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from earth.life import Human


class Arnewitt(Human):
    
    def __init__(self):
        self.name = "Arne"
        self.job = "Data Engineer"
        self.passions = ["Data Engineering", 
                         "Data Science", "Software Engineering"]
        
    def introduce(self):
        """
        Introduce briefly.
        
        :param: None
        :return: None
        """
        print("Hi, nice to meet you! My name is Arne, I am looking forward to connect and collaborate!")
 
 
if __name__ == "__main__":
    arne = Arnewitt()
    arne.introduce()
 ```
 
