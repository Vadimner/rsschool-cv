## Vadim Zhminkovskiy

### Contacts
* [Telegram](https://t.me/Vadimner)
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

* __2017-2022__ — Engineering Manager.
* __2015-2017__ — UX/UI Designer (main).
* __2013-2015__ — UI Designer (main). Junior mobile developer (Native Android and iOS).
* __2012-2013__ — UI Designer. Motion Designer
* __2010-2012__ — UI Designer.
* __2008-2010__ — Graphic Designer.

### Education

#### Main
Interior Designer

#### Additional
* [Python for Everybody Specialization](https://www.coursera.org/specializations/python#courses)
* [Интерактивный тренажер по SQL](https://stepik.org/cert/1370828)
* [Jira: ведение задач на электронных досках](https://stepik.org/cert/947343)

### Languages knowlege
* English (B1)
* Russian (native)