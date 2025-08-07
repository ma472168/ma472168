    def __init__(self):
        self.name = "cesar martinez"
        self.age = 21
        self.email = "ma472168@uaeh.edu.mx"
        self.university = "autonomous university of the state of hidalgo"
        self.degree = "bachelor of computer science"
        self.expected_graduation = "june 2026"
        self.electives = ["multi-agent systems", "network design", "network administration"]
        self.location = "mineral de la Reforma, pachuca, hidalgo"
        self.country = "mexico"
        self.languages = ["spanish native", "conversational english"]

    def experience(self):
        return {
            "community service": "web developer and service provider in the planning department of the UAEH",
            "personal projects": ["static web pages", "web applications with Django", "database management systems", "pdf to excel data conversion"],
            "participations": ["hackathons", "research projects", "cpc (competitive programming competitions)"],
            "family technical support": "providing technical support to family and friends with basic IT problems"
        }

    def education(self):
        return {
            "high school": "Technical Programming at the College of Scientific and Technological Studies of the State of Hidalgo (CECyTEH)",
            "university": "Bachelor of Computer Science at the Autonomous University of the State of Hidalgo",
            "certifications": ["CCNAv7: Introduction to Networks (completed)", "Linux Unhatched (in progress)", "CCNA: Enterprise Networks, Security, and Automation (in progress)"]
        }

    def coding_languages(self):
        return ["python", "java", "c++", "javascript", "html", "css", "sql"]

    def tools(self):
        return ["git", "github", "visual studio code", "mysql workbench", "virtualbox", "cisco packet tracer", "adobe photoshop", "office suite"]
    
    def websites(self):
        return ["github.com/ma472168", "linkedin.com/ma472168", "instagram.com/ma472168"]

    def hobbies(self):
        return ["reading", "programming", "playing video games", "watching series and movies", "listening to music"]

    def skills(self):
        return {
            "teamwork": "ability to work in a team and collaborate with others",
            "communication": "good verbal and written communication skills",
            "problem solving": "ability to solve problems effectively",
            "adaptability": "ability to adapt to new environments and learn quickly"
        }
