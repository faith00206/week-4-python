class Person:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age
        self.gender = gender
    
    def introduce(self):
        print("Hello, my name is {}, I am {} years old, and I am {}.".format(self.name, self.age, self.gender))

# Create an instance of the Person class
person1 = Person("Jane", 12, "female")

# Call the introduce method to display the person's information
person1.introduce()
