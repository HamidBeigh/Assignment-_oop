# Homework Assignment #12: Object Oriented Programming

What is object oriented programming, and why would you use it?

Object-oriented programming: As the name suggests, Object-Oriented Programming or OOPs refers to languages that uses objects in programming. Object-oriented programming aims to implement real-world entities like inheritance, hiding, polymorphism etc in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that function.

One of the principal advantages of object-oriented pattern over procedural pattern is that they enable developers to create modules that do not need to be changed when a new type of object is added. A developer can simply create a new object that inherits many of its features from existing objects. This makes object-oriented programs easier to modify.

## Project: Favorite Contact List

###Description
I propose a system where the user can see a contact list, the user can see the details of each contact, and be able to add contacts to their favorite list.

###Pseudocode
class User {
  first name,
  last name,
  email,
  password,
  favorite list of contacts
  ---
  addFavorite()
  removeFavorite()
  getFavorites()
}

class contact {
  name,
  adress,
  description,
  image
  ---
  addContact()
  removeContact()
  getContact()
}
