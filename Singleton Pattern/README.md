# Singleton Pattern
## Description
- A pattern used to share a single instance across many files. Typically can be used as a single source of truth.

## Pros and Cons
### Pros
- Can share data between multiple files.
- A single source of truth.
### Cons
- Race conditions can happen when multiple files manipulate the same value, for example, one object wants to run the toggleLight method which turns it on, but another object at the same time runs the toggleLight method and turns it off. In a db (database) example, we can have an object write to a record but then a different object overwrites that record.

Video: https://youtu.be/sJ-c3BA-Ypo