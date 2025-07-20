# ☎️Smart Phonebook with Tags (v2.0)
A Python CLI project that simulates a smart contact book. Each contact contains a name, phone number, and a set of tags like `family`, `work`, or `emergency`. Built using Python dictionaries and sets — no external libraries!


## 🧠Features
- 📇 Add new contact with tags
- 🔍 Search contact by name
- 🗑️ Delete contact
- 📃 Show all contacts
- 🏷️ Show all unique tags
- 🔎 Search contacts by tag


## 🛠️Concepts Used
- `dict` with nested values
- `set()` for storing and searching tags
- `.split()`, `.strip()`, `.lower()` for input cleaning
- Loops, conditionals, CLI design
- Optional: `match-case` or function modularization


##🔍 Sample Output
📞 Smart Phonebook v2.0

1.Add Contact
2.Search by Name
3.Delete Contact
4.Show All Contacts
5.Show All Unique Tags
6.Search Contacts by Tag
7.Exit

Choose Option: 1
Name: Om
Number: 9876543210
Tags: family, emergency
✅ Contact Added!

Choose Option: 6
Enter tag to search: family
Om → 9876543210

Choose Option: 5
All Unique Tags: {'family', 'emergency'}

Choose Option: 7
👋 Goodbye!


## 🚀Ideas for Future
Contact update option
Export to CSV or JSON
GUI with Tkinter
Contact groups / favorites


## 😄Dev Joke
Why don’t Python programmers fight with phonebooks?
Because they always handle things with dictionaries and sets 🧠📖
