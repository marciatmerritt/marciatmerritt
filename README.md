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
<div style="width: 100%; margin: 0 auto;">
      <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/junit/junit-plain-wordmark.svg" title="JUnit" alt="JUnit" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/jest/jest-plain.svg" title="Jest" alt="Jest" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/vitejs/vitejs-original.svg" title="Vite" alt="Vite" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-plain.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/sqldeveloper/sqldeveloper-original.svg" title="SQL" alt="SQL" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="VSCode" alt="VSCode" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/intellij/intellij-original.svg" title="IntelliJ" alt="IntelliJ" width="40" height="40"/>&nbsp;
      <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original-wordmark.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
</div>


## 🔥 My Stats :

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=marciatmerritt)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=marciatmerritt&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)