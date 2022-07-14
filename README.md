
# Hi there 👋


```python
#!/usr/bin/env python
# -*- coding: utf-8 -*-


class FullStackDeveloper:

    def __init__(self):
        self.name = 'Toño'
        self.role = 'Full Stack Developer'


    def say_hi(self):
        return u"I'm %s, a %s." % (self.name, self.role)

    def get_current_workplace(self):
        return 'https://z1.digital'

    def get_frontend_skills(self):
        return [
            'react',
            'flutter',
            'react-native',
            'tailwind',
            'sass',
            'vanilla js'
        ]


    def get_backend_skills(self):
        return [
            'python',
            'node',
            'php',
            'firebase',
            'redis',
            'mysql',
            'postgresql',
        ]


me = FullStackDeveloper()
print(me.say_hi())


```
