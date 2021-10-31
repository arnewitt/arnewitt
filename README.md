# Hello there!


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from earth.life import Human


class Arnewitt(Human):
    
    def __init__(self):
        self.name = "Arne"
        
    def greet(self):
        """
        Introduce briefly.
        
        :param: None
        :return: None
        """
        print("Hi, nice to meet you!")
 
 
if __name__ == "__main__":
    arne = Arnewitt()
    arne.greet()
 ```
 
