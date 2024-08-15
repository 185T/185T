class Terano:
    def __init__(self):
        self.name = "Terano"
        self.age = 18
        self.nationality = "Japanese"
        self.role = "High School Student by day, Discord Bot Creator by night"
        self.skills = ["Discord Bots", "Pixel Art", "Automation"]
        self.languages = ["Python", "JavaScript"]  # No particular fondness for Python, just getting things done.
        self.mission = "Make bots that even your grandma could use (well, almost)."
        self.current_focus = ["Learning English", "Building awesome stuff"]

    def looking_for(self):
        return "An English teacher—got any tips?"

    def __repr__(self):
        return (
            f"👋 Hey there! I'm {self.name}!\n"
            f"🎮 {self.age}-year-old {self.nationality} student and {self.role}.\n"
            f"🔧 Hobbyist who loves {', '.join(self.skills)}.\n"
            f"🚀 Always cooking up something new in {', '.join(self.languages)} and pixels.\n"
            f"📈 {self.mission}\n"
            f"📚 {self.looking_for()}\n"
            f"😎 Drop by my repos, and let's build something awesome together!"
        )

terano = Terano()
print(terano)
