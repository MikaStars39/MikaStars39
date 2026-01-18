<p align="center"> 
  <img src="https://img.shields.io/badge/Google%20Scholar-4385FE.svg?&color=d6d6d6&style=flat-square&logo=google-scholar" width="120px" alt="" />
  <img src="https://img.shields.io/github/stars/mikastars39?style=flat-square&logo=github&label=Stars&color=gray" width="90px" alt="" /> 
  <img src="https://komarev.com/ghpvc/?username=mikastars39&style=flat-square" width="120px" alt="profile views" /> 
</p>

```
class PersonalProfile:
    """
    A class to represent a human entity in the tech ecosystem.
    """
    
    def __init__(self):
        self.name = "Qingyu Yin"
        self.role = "LLM Researcher"
        self.location = "Earth"
        self.languages = ["Python", "C++", "English", "Mandarin", "Japanese"]
        self.hobbies = ["Open Source Contributing"]

    def speak(self):
        introduction = (
            f"Hello! I'm Qingyu Yin. "
            f"I specialize in exploring "
            f"the boundaries of Machine Learning."
        )
        print(introduction)

    def __repr__(self):
        return f"Developer(name='{self.name}', status='Always Learning')"

# Instantiate the persona
me = PersonalProfile()

if __name__ == "__main__":
    # Execute introduction
    me.speak()
    
    print("\n--- Technical Stack ---")
    for category, tools in me.get_core_competencies().items():
        print(f"{category}: {', '.join(tools)}")
        
    print(f"\nCurrently playing with: {me.hobbies[0]}")
```
