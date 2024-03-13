### Hi there 👋

<!--
**shivkatira/shivkatira** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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


class Person:

    def __init__(self):
        self.name = 'Shiv Katira'
        self.gender = 'male'
        self.nationality = 'Indian'
        self.address = Place(address_locality='Kolkata',
                             address_region='West Bengal',
                             address_country='India')
        self.home_location = Place(address_locality='Morbi',
                                   address_region='Gujarat',
                                   address_country='India')
        self.email = 'shivkatira@gmail.com'
        self.job_title = 'Research Manager'
        self.works_for = Organization(name='Kantar',
                same_as='https://www.linkedin.com/company/kantar/')
        self.alumni_of = \
            [CollegeOrUniversity(name='University of Mumbai',
             same_as='https://en.wikipedia.org/wiki/University_of_Mumbai'
             ),
             CollegeOrUniversity(name='Institute of Cost Accountants of India'
             ,
             same_as='https://en.wikipedia.org/wiki/Institute_of_Cost_Accountants_of_India'
             ),
             CollegeOrUniversity(name='The Maharaja Sayajirao University of Baroda'
             ,
             same_as='https://en.wikipedia.org/wiki/Maharaja_Sayajirao_University_of_Baroda'
             )]
        self.knows_language = ['en_IN', 'hi_IN', 'gu_IN']
        self.same_as = 'https://www.linkedin.com/in/smkatira/'

```
