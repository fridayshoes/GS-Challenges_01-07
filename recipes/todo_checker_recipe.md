# Todo Checker Method Design Recipe

## 1. Describe the Problem

As a user
So that I can keep track of my tasks
I want to check if a text includes the string #TODO.

## 2. Design the Method Signature

_Include the name of the method, its parameters, return value, and side effects._

```ruby

result = todo_checker(text)

text will be a string (e.g. #TODO Clean the kitchen)
result will be true or false


```

## 3. Create Examples as Tests

_Make a list of examples of what the method will take and return._

```ruby

todo_checker("") => throws an error
todo_checker("Watch the television") => false
todo_checker("#TODO wash the car") => true
todo_checker("There's so many things #TODO today") => true
todo_checker("The postman todotoday will be here") => false

```

_Encode each example as a test. You can add to the above list as you go._

## 4. Implement the Behaviour

_After each test you write, follow the test-driving process of red, green, refactor to implement the behaviour._


<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

