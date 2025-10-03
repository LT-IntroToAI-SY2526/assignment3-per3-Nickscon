# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
    I didn't learn anything new but I reinforced my conceptual idea and how to use lists and indexes and how to incorporate functions that change lists and arrays. Such as append, using conditionals to check list elements to append elements inside of another list. Pulling a string value from one list to another list.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
    You type a query and then the chat bot matches the input to which prompt it would fit under and then matches the list arrays to each other then provides a response by pulling data from those established lists already and then prints an answer using the values pulled from the lists.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
    The real world applications of this type of pattern-matching could expanded for more string recognizing artifiical intelligence or extending to other patterns such as a chess robot such as Stockfish which could already be using this algorithims due to most things being applicable as a "Pattern" to improve this we may have to probably improve the code by a lot to be usde in real applications or expanding it to other applicable things such as higher functioning pattern recognition devices.