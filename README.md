```python
"""Hello! This is basically me."""


class CtrlManiac:
    """CtrlManiac because i overuse the ctrl key."""

    def __init__(self):
        """My specifications."""
        self.name = "Davide"
        self.surname = "Di Criscito"
        self.nickname = "Dave"
        self.pronouns = (
            "He",
            "Him",
        )

        self.languages_spoken = ["it_IT", "en_US", "en_GB"]

        self.description = (
            "I'm currently an Artisan, soon-to-be a full-stack developer!"
        )

        self.hobbies = [
            "coding",
            "photography",
            "watching movies & TV series",
            "listening to music",
            "going out with my friends and have fun",
        ]

        self.coding_languages = [
            "Python",  # I simply love it
            "JavaScript",
        ]

        self.favourite_tools = [
            "poetry",  # makes it simpler to manage a python project
            "black",  # chooses a coding style for me and makes my code pretty, also black it's my favourite colour
            "isort",  # sorts python imports so that everything is really clear
            "flake8",  # tells me whether I've made a mistake
            "pydocstyle",  # helps me write better documentation
            "yarn",  # I love it for the workspace feature
            "lerna",  # I use it to manage my monorepos
            "prettier",  # chooses a coding style for me and makes my code pretty
        ]

        self.IDEs = [
            "VScode",  # because it's awesome!
            "IntelliJ Idea",  # it makes coding Java easier
        ]

    def greet(self, lang) -> None:
        """Say hi.

        :param lang: the language you want me to greet you with.
        """
        if lang == "it_IT":
            print(
                "Ciao! Grazie per aver visitato il mio profilo! Spero che i miei progetti ti piacciano!"
            )
        else:
            print("Hi! Thanks for visiting my profile! I hope you like my projects!")

    def learn_new_coding_languange(self, language) -> None:
        """Print a string that tells what new coding language I'm learning.

        :param language: the coding language to learn.
        """
        print(f"I'm currently studying a new coding language: {language}")


me = CtrlManiac()

me.greet("en_US")

# Currently learning
me.learn_new_coding_languange("Java")
me.learn_new_coding_languange("Typescript")
me.learn_new_coding_languange("Golang")
```

## Follow Me on:

- [Twitter](https://twitter.com/ctrlmaniac)
- [Instagram](https://instagram.com/meldinco)
- [Linkedin](https://www.linkedin.com/in/dcdavide/)
- [Pinterest](https://pin.it/4erq4kP)

## :pray: Help me test The House!

Help me test my text-based game written in python!
You can find the repository [here](https://github.com/ctrlmaniac/the-house) or you can install it via pip `pip install thehouse` and then run `thehouse` to make the game start!