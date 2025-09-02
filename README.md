# python-assignment-7(@blockfuse labs)


## README.md`** file that covers **all four tasks** in one place, written in a simple, neutral, human-like style.



### This repository contains beginner-friendly Python tasks designed to practice:  
- Functions  
- Dictionaries and Lists  
- `*args` and `**kwargs`  
- Basic problem-solving  

Each task is small but practical, and can later be extended into bigger projects.  


##  Task 1: Library Management System  

### Requirements  
- Store books as dictionaries with the fields:  

  { "id": int, "title": str, "author": str, "available": bool }


* Use a list to represent the library.
* Functions needed:

  * `add_book(book)`: Add a new book with flexible details (using `**kwargs`).
  * `search_books(*args)`: Search for books by title or author.
  * `borrow_book(book_id)`: Borrow a book if it is available.

  Future idea: extend this with classes (`Book`, `Library`) for an OOP version.

---

## Task 2: Voting System

### Requirements

* Store candidates in a dictionary:

  ```python
  { "candidate_name": vote_count }
  ```
* Track voters using a set so each voter can only vote once.
* Functions needed:

  * `register_candidates(*args, **kwargs)`: Register multiple candidates at once and allow optional details (party, region).
  * `cast_vote(voter_id, candidate)`: Allow a voter to vote if they haven’t already.
  * `election_result()`: Return the winner(s) and all candidate results.


##  Task 3: Online Store

### Requirements

* Store products as dictionaries with the fields:

  { "id": int, "name": str, "price": float, "stock": int }


* Use a list to represent all products in the store.
* Functions needed:

  * `add_product(**kwargs)`: Add a new product with flexible details.
  * `purchase_product(product_id, quantity)`: Reduce stock if available.
  * `search_products(*args)`: Search products by name or category.

> 📝 Future idea: turn this into a class-based system with `Product` and `Store` classes.


##  Task 4: Student Grading System

### Requirements

* Store student records in a dictionary:

  { "student_id": { "name": str, "scores": list, "average": float } }

* Functions needed:

  * `add_student(student_id, **kwargs)`: Add a student with flexible details.
  * `add_score(student_id, score)`: Add a new score for a student.
  * `calculate_average(student_id)`: Compute the average score.
  * `class_average()`: Compute the overall class average.

 📝 Future idea: extend this to rank students or generate simple reports.



## ⚡ Notes

* Focus is on practicing `*args` and `**kwargs`.
* Keep the solutions **simple and readable**.
* Use only Python’s built-in features — no external libraries needed.
* We will expand on each task later andbuild into a bigger project (using OOP).


