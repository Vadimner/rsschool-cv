## Vadim Zhminkovskiy

### Contacts
* [tg](https://t.me/Vadimner)
* [Discord](https://discordapp.com/users/Vadimner#4216)
* [Mail](mailto:astronomail@gmail.com)

### Information
Just a guy who loves IT. I Work in this field since 2012. At first as a UI/UX designer, laiter on as an Engineering Manager.

Already have some experience with Python and its frameworks.

At the moment main goal to become a "Full Stack" developer.

Going to learn JavaScript and its frameworks to make a step to my target.

### Skills

#### Technical
* Python
  * Flask
  * FastApi
  * Django
* SQL
* UX Design
* UI Design
* JIRA (and JQL)

#### Other Skills
* People Management
* Project management methodologies (Agile, Scrum, Kanban, Waterfall)

### Code examples

#### [Extract the domain name from a URL](https://www.codewars.com/kata/514a024011ea4fb54200004b)

Python solution:

    import re

    def domain_name(url):
        
        www_result = re.compile('((?<=www.).+)\.').findall(url)
        if www_result:
            return www_result[0]
        
        http_result = re.compile('((?<=://).*?)\.').findall(url)
        if http_result:
            return http_result[0]
        
        nude_result = re.compile('(^.*?)\.').findall(url)
        if nude_result:
            return nude_result[0]

### Experience

* 2017-2022 — Engineering Manager.
* 2015-2017 — UX/UI Designer (main).
* 2013-2015 — UI Designer (main). Junior mobile developer (Native Android and iOS).
* 2012-2013 — UI Designer. Motion Designer
* 2010-2012 — UI Designer.
* 2008-2010 — Graphic Designer.

### Education

#### Main
Interior Designer

#### Additional
[Python for Everybody Specialization](https://www.coursera.org/specializations/python#courses)
[Интерактивный тренажер по SQL](https://stepik.org/cert/1370828)
[Jira: ведение задач на электронных досках](https://stepik.org/cert/947343)

### Languages knowlege
* English (B1)
* Russian (native)