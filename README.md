<div id="header" align="center">
    <h1 align="left">Hi, 👋🏾 I'm Marcia </h1>
    <img src="https://github.com/user-attachments/assets/21379ba4-1b37-49f8-94e8-cbd11bb38160" alt="Welcome Banner" style="max-width: 100%; height: auto;" />
    <div id="badges">
      <a href="https://www.linkedin.com/in/marcia-merritt-58662761/">
        <img src="https://img.shields.io/badge/-marciatmerritt-blue?style=for-the-badge&logo=Linkedin&logoColor=white" alt="LinkedIn badge"/>
      </a>
      <a href="(https://discordapp.com/users/marciam2911">
        <img src="https://img.shields.io/badge/marciam2911-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white">
      </a>
      <a href="mailto:marciatmerritt@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-marciatmerritt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail: Marcia" />
      </a>
    </div>
    <img src="https://komarev.com/ghpvc/?username=marciatmerritt&style=flat-square&color=blue" alt=""/>
</div>

<!-- [![LinkedIn: Marcia](https://img.shields.io/badge/-marciatmerritt-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/marcia-merritt-58662761/)
[![Gmail: Marcia](https://img.shields.io/badge/Gmail-marciatmerritt@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:marciatmerritt@gmail.com)
[![Discord: Marcia](https://img.shields.io/badge/marciam2911-%237289DA.svg?style=flat-square&logo=discord&logoColor=white)](https://discordapp.com/users/marciam2911)
[![Slack: Marcia](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)](https://join.slack.com/t/marciam2911/shared_invite) -->

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
            "Typescript 📜",
            "HTML 🏗️",
            "CSS 🎨",
            "SQL 🗄️",
            "Python 🐍",
            "XML",
            "XSLT",
        ]
        self.tools = [
            "React ⚛️",
            "Node.js 🌲",
            "Git 🗂️",
            "Docker 🐳",
            "VS Code 💻",
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
            "I’d love to discuss how my experience and skills can contribute to your team’s success. "
            "How do you see someone with my background fitting into your current initiatives?"
        )
        return elevator_pitch


marcia = Marcia()
print(marcia.generate_elevator_pitch())

```

## Output

```
Hi, I’m Marcia Merritt, a passionate software engineer with over 12 years of experience in the tech industry. I have a solid foundation in programming languages such as Java ☕, JavaScript 🌐, Typescript 📜, HTML 🏗️, CSS 🎨, SQL 🗄️, Python 🐍, XML, and XSLT. I’m proficient in React ⚛️, Node.js 🌲, Git 🗂️, Docker 🐳, and VS Code 💻, along with databases like SQL Server 📊, and PostgreSQL 🐘.

Recently, I completed a Full-Stack Software Engineering and Web Development certificate at Midlands Tech, which deepened my expertise in modern web technologies and fueled my passion for building user-friendly web applications. Currently, I am expanding my back-end skills by diving deeper into Node.js through RS school’s NodeJS2024Q3 online course, and I’m excited to be starting a Javascript Front-End online course with RS school 2024Q4 in late October.

I thrive in collaborative environments and believe my soft skills–problem-solving 🧩, adaptability 🌱⚡, and empathy 🤝🏾–enhance my effectiveness in diverse teams. My community involvement includes volunteering at my 🐾 local animal shelter, serving as a volunteer 👩🏽‍🏫 instructor and mentor at Code2College, and officiating various sports, all of which help me to continuously refine my customer service abilities while honing my mentoring and leadership skills.

Outside of work, I enjoy spending time with my 🐕🐀🐈 animals, playing sports 🎾🏐⚽🏀, working out 🏋🏽‍♀️🏃🏽‍♀️, and practicing Bikram Yoga 🧘🏽‍♀️. These activities not only help me maintain a healthy work-life balance but also foster creativity, which I bring into my professional endeavors.

I’m truly excited about the opportunity to leverage my skills and experiences to contribute to innovative projects that make a positive impact. I’d love to discuss how my experience and skills can contribute to your team’s success. How do you see someone with my background fitting into your current initiatives?
```


<!--
**marciatmerritt/marciatmerritt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
