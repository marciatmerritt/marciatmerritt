<div id="header" align="center">
    <h1 align="left">Hi, 👋🏾 I'm Marcia </h1>
    <img src="https://github.com/user-attachments/assets/9b5865c0-d24e-4399-8ac2-0ba4567091dd" alt="Welcome Banner" style="max-width: 100%; height: auto;" />
    <div id="badges">
      <a href="mailto:marciatmerritt@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-marciatmerritt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail: Marcia" />
      </a>
      <a href="https://www.linkedin.com/in/marcia-merritt-58662761/">
        <img src="https://img.shields.io/badge/-marciatmerritt-blue?style=for-the-badge&logo=Linkedin&logoColor=white" alt="LinkedIn badge"/>
      </a>
    </div>
    <img src="https://komarev.com/ghpvc/?username=marciatmerritt&style=flat-square&color=blue" alt=""/>
<!--     [![GitHub Marcia](https://img.shields.io/github/followers/marciatmerritt?label=follow&style=social)](https://github.com/marciatmerritt) -->
</div>


```python
from datetime import datetime

class Marcia:
    def __init__(self):
        self.name = "Marcia Merritt"
        self.title = "software engineer"
        self.start_year = 2012
        self.soft_skills = [
            "problem-solving 🧩",
            "adaptability 🌱⚡",
            "empathy 🤝🏾",
        ]
        self.code = [
            "Java ☕",
            "JavaScript 🌐",
            "Jest 👑",
            "Typescript 📜",
            "HTML 🏗️",
            "CSS 🎨",
            "SQL 🗄️",
            "Python 🐍",
            "XML 📄",
            "XSLT ✂️"
        ]
        self.tools = [
            "React ⚛️",
            "Node.js 🌲",
            "Git 🔀",
            "Docker 🐳",
            "VS Code 🖥️",
        ]
        self.databases = ["SQL Server 📊", "PostgreSQL 🐘"]
        self.architecture = ["MVC", "RESTful APIs"]
        self.methodologies = ["Agile", "Scrum"]
        self.communities = {
            "volunteer": [
                "🐾 local animal shelter",
                "👩🏽‍🏫 instructor and mentor at Code2College",
            ],
            "referee": [
                "⚽ soccer",
                "🏀 basketball",
                "🏐 volleyball",
                "🎾 tennis",
            ],
        }
        self.hobbies = [
            "🐕🐀🐈 animals",
            "🎾🏐⚽🏀 playing sports",
            "🏋🏽‍♀️🏃🏽‍♀️ working out",
            "🧘🏽‍♀️ practicing Bikram Yoga",
        ]
        self.challenges = [
            "completed a Full-Stack Software Engineering and Web Development certificate at Midlands Tech",
            "diving deeper into Node.js through RS school's NodeJS2024Q3 online course",
            "starting a Javascript Front-End online course with RS school 2024Q4",
        ]

    def years_of_experience(self):
        current_year = datetime.now().year
        return current_year - self.start_year

    def _build_intro(self):
        return (
            f"Hi, I’m {self.name}, a passionate {self.title} with over {self.years_of_experience()} years of experience "
            f"in the tech industry. I have a solid foundation in programming languages such as {', '.join(self.code[:-1])}, and {self.code[-1]}. "
            f"I'm proficient in {', '.join(self.tools[:-1])}, and {self.tools[-1]}, along with databases like {', '.join(self.databases[:-1])}, and {self.databases[-1]}. "
        )

    def _build_challenges_section(self):
        return (
            f"\n\nRecently, I {self.challenges[0]}, which deepened my expertise in modern web technologies and fueled my passion for building user-friendly web applications. "
            f"Currently, I am expanding my back-end skills by {self.challenges[1]}, and I'm excited to be {self.challenges[2]} in late October.\n\n"
        )

    def _build_soft_skills_section(self):
        return (
            f"I thrive in collaborative environments and believe my soft skills--{', '.join(self.soft_skills[:-1])}, and {self.soft_skills[-1]}--"
            f"enhance my effectiveness in diverse teams. My community involvement includes volunteering at my "
            f"{self.communities['volunteer'][0]}, serving as a volunteer {self.communities['volunteer'][1]}, and officiating various sports, all of which "
            f"help me to continuously refine my customer service abilities while honing my mentoring and leadership skills.\n\n"
        )

    def _build_hobbies_section(self):
        return (
            f"Outside of work, I enjoy spending time with my {', '.join(self.hobbies[:-1])}, and {self.hobbies[-1]}. "
            f"These activities not only help me maintain a healthy work-life balance but also foster creativity, which I bring into my professional endeavors.\n\n"
        )

    def generate_elevator_pitch(self):
        elevator_pitch = (
            self._build_intro()
            + self._build_challenges_section()
            + self._build_soft_skills_section()
            + self._build_hobbies_section()
            + "I’m truly excited about the opportunity to leverage my skills and experiences to contribute to innovative projects that make a positive impact. "
            "I’d love to discuss how my experience and skills can contribute to your team’s success.\n\n"
            "How do you see someone with my background fitting into your current initiatives?"
        )
        return elevator_pitch


marcia = Marcia()
print(marcia.generate_elevator_pitch())

```

## Output

```console
Hi, I’m Marcia Merritt, a passionate software engineer with over 12 years of experience in the tech industry. I have a solid foundation in programming languages such as Java ☕, JavaScript 🌐, Jest 👑, Typescript 📜, HTML 🏗️, CSS 🎨, SQL 🗄️, Python 🐍, XML 📄, and XSLT ✂️. I'm proficient in React ⚛️, Node.js 🌲, Git 🔀, Docker 🐳, and VS Code 🖥️, along with databases like SQL Server 📊, and PostgreSQL 🐘. 

Recently, I completed a Full-Stack Software Engineering and Web Development certificate at Midlands Tech, which deepened my expertise in modern web technologies and fueled my passion for building user-friendly web applications. Currently, I am expanding my back-end skills by diving deeper into Node.js through RS school's NodeJS2024Q3 online course, and I'm excited to be starting a Javascript Front-End online course with RS school 2024Q4 in late October.

I thrive in collaborative environments and believe my soft skills--problem-solving 🧩, adaptability 🌱⚡, and empathy 🤝🏾--enhance my effectiveness in diverse teams. My community involvement includes volunteering at my 🐾 local animal shelter, serving as a volunteer 👩🏽‍🏫 instructor and mentor at Code2College, and officiating various sports, all of which help me to continuously refine my customer service abilities while honing my mentoring and leadership skills.

Outside of work, I enjoy spending time with my 🐕🐀🐈 animals, 🎾🏐⚽🏀 playing sports, 🏋🏽‍♀️🏃🏽‍♀️ working out, and 🧘🏽‍♀️ practicing Bikram Yoga. These activities not only help me maintain a healthy work-life balance but also foster creativity, which I bring into my professional endeavors.

I’m truly excited about the opportunity to leverage my skills and experiences to contribute to innovative projects that make a positive impact. I’d love to discuss how my experience and skills can contribute to your team’s success. 

How do you see someone with my background fitting into your current initiatives?
```

## 🛠️ Technologies & Tools:

<table>
  <tr>
    <td>CI/CD</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/jenkins/jenkins-original.svg" width="40" height="40" title="Jenkins" alt="Jenkins" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/github/github-original.svg" width="40" height="40" title="GitHub" alt="GitHub" />
    </td>
  </tr>
  <tr>
    <td>SysOps</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/master/icons/azure/azure-original.svg" title="Azure" alt="Azure" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/powershell/powershell-original.svg" width="40" height="40" title="PowerShell" alt="PowerShell" />
      <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-official.svg" width="40" height="40" title="Bash" alt="Bash" />
    </td>
  </tr>
  <tr>
    <td>Backend</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/java/java-original.svg" width="40" height="40" title="Java" alt="Java" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/spring/spring-original.svg" width="40" height="40" title="Spring" alt="Spring" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/python/python-original.svg" width="40" height="40" title="Python" alt="Python" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" width="40" height="40" title="PHP" alt="PHP" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/graphql/graphql-plain.svg" width="40" height="40" title="GraphQL" alt="GraphQL" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/xml/xml-original.svg" width="40" height="40" title="XML" alt="XML" />
      <img src="https://www.vectorlogo.zone/logos/json/json-ar21.svg" title="JSON" alt="JSON" width="40" height="40" />
    </td>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/javascript/javascript-original.svg" width="40" height="40" title="JavaScript" alt="JavaScript" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/typescript/typescript-original.svg" width="40" height="40" title="TypeScript" alt="TypeScript" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/react/react-original.svg" width="40" height="40" title="React" alt="React" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/vitejs/vitejs-original.svg" title="Vite" alt="Vite" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/redux/redux-original.svg" width="40" height="40" title="Redux" alt="Redux" />
      <img src="https://www.vectorlogo.zone/logos/npmjs/npmjs-icon.svg" width="40" height="40" title="NPM" alt="NPM" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/jest/jest-plain.svg" width="40" height="40" title="Jest" alt="Jest" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/webpack/webpack-original.svg" width="40" height="40" title="Webpack" alt="Webpack" />
      <img src="https://www.vectorlogo.zone/logos/sass-lang/sass-lang-icon.svg" title="SASS" alt="SASS" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/axios/axios-plain-wordmark.svg" title="Axios" alt="Axios" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40" />
    </td>
  </tr>
  <tr>
    <td>Microservices</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/docker/docker-original.svg" width="40" height="40" title="Docker" alt="Docker" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/spring/spring-original.svg" width="40" height="40" title="Spring Boot" alt="Spring Boot" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="Express.js" alt="Express.js" width="40" height="40" />
    </td>
  </tr>
  <tr>
    <td>Databases/Datastores</td>
    <td>
      <!-- <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/mongodb/mongodb-original.svg" width="40" height="40" title="MongoDB" alt="MongoDB"/> -->
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/mysql/mysql-original.svg" width="40" height="40" title="MySQL" alt="MySQL" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/oracle/oracle-original.svg" width="40" height="40" title="Oracle" alt="Oracle" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/postgresql/postgresql-original.svg" width="40" height="40" title="PostgreSQL" alt="PostgreSQL" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/sqldeveloper/sqldeveloper-original.svg" title="SQL" alt="SQL" width="40" height="40" />
    </td>
  </tr>
  <tr>
    <td>IDEs</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/vscode/vscode-original.svg" width="40" height="40" title="VSCode" alt="VSCode" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/pycharm/pycharm-original.svg" width="40" height="40" title="PyCharm" alt="PyCharm" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/intellij/intellij-original.svg" width="40" height="40" title="IntelliJ" alt="IntelliJ" />
    </td>
  </tr>
  <tr>
    <td>Others/Misc</td>
    <td>
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/gitlab/gitlab-original.svg" width="40" height="40" title="GitLab" alt="GitLab" />
      <img src="https://github.com/devicons/devicon/blob/v2.13.0/icons/git/git-original.svg" width="40" height="40" title="Git" alt="Git" />
      <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40" height="40" title="Postman" alt="Postman" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/swagger/swagger-original.svg" width="40" height="40" title="Swagger" alt="Swagger" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original-wordmark.svg" width="40" height="40" title="Jira" alt="Jira" />
      <img src="https://github.com/devicons/devicon/blob/master/icons/trello/trello-original.svg" width="40" height="40" title="Trello" alt="Trello" />
    </td>
  </tr>
</table>


<br/>

## 🔥 My Stats :

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=marciatmerritt&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

<!-- [![Marcia's GitHub stats](https://github-readme-stats.vercel.app/api?username=marciatmerritt)](https://github.com/anuraghazra/github-readme-stats) -->

<!-- ![marciatmerritt github-trophies](https://stats.dooboo.io/api/github-trophies?login=marciatmerritt) -->

![marciatmerritt github-stats](https://stats.dooboo.io/api/github-stats-advanced?login=marciatmerritt)
