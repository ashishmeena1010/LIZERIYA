class Lizeriya:
    def __init__(self, owner_name):
        self.owner_name = owner_name

    def greet(self):
        return f"Hello! I am Lizeriya, created by {self.owner_name}."

# Create an instance of Lizeriya
lizeriya = Lizeriya("Ashish")

# Call the greet method
print(lizeriya.greet())
