# Chat Application - Part 1

## Student Information
- Name: Nela
- Student Number: ST10521312
- Module: PROG5121

---

## Project Information
This is a project that has Java registration and login system for a chat app. The Login class validates that usernames have an underscore and are five characters or less, passwords meet complexity rules, and phone numbers use the +27 format. Main handles all user input and output, while LoginTest uses JUnit to automatically check that every rule works with both valid and invalid data.

---
## Features
### Login.java 
- Contains all the business logic to validate usernames, passwords, and South African phone numbers.

### Main.java
- Acts as the user interface, using a Scanner to collect input from user and calling the Login methods to register and log in the user, then displaying the appropriate success or error messages.

### LoginTest.java 
- Uses JUnit to automatically test each validation rule with valid and invalid data to prove the Login class works correctly. 
