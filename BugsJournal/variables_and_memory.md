Date: July 21, 2026
Topic: Variables, Names, and Objects

Definition: In Python, variables are NOT "boxes" that store values. They are Names (like sticky notes) bound to Objects living in memory.

Key Concept (Pass-by-Object-Reference):
When you write a = b, Python does not create a new box for a. It takes the name a and points it to the exact same memory address (object) that b is pointing to.

Important Tool:
Use id(variable_name) to see the actual memory address of an object. If two variables have the same id(), they are pointing to the same object.

Immutability:
Numbers (integers, floats) and Strings are immutable. You cannot change the object itself. Reassigning a variable (e.g., score = 200) creates a brand new object in memory and moves the "sticky note" to it.

Docs Reference: Python Data Model - Objects, values and types