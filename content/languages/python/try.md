+++
title = "Try Except"
+++

> Code Might Fail

It's important to use `try`/`except`/`finally` whenever your application 
could fail through no fault of your own.

### Questions

- Shouldn't we fix all errors first?
- Why do we need `try`/`except`/`finally`?

### Answer

We should always strive to fix all coding and logic errors. 
However, sometimes our code can be perfect - but exceptions can still happen. 
`try`/`except`/`finally` is a way to gracefully 
handle unexpected errors and prevent our program from crashing.

### Example

Suppose you write a script to read `baseball_game_results.csv` each night 
at midnight. 

It runs fine until someone changes the filename to `rslts.csv`. 

Now, your code terminates with an ugly error because the necessary file can't 
be found. 

To code professionally, we can use `try`/`except` to handle 
this error gracefully. 

```python
try:
    # Attempt to open the file
    with open('baseball_game_results.csv', 'r') as f:
        # Do something with the file
        
except FileNotFoundError:
    # Handle the case where the file is not found
    print('ERROR: File not found. Please name the file to baseball_game_results.csv')
finally:
    # Clean up any resources (e.g. file handles) used by the code
     
```

### Other Programming Languages

Other programming languages use something very similar, 
but  might use the keywords `try/catch/finally`. 
As in "try this, and if you catch an exception, do this."

## Throwing Exceptions

Exceptions are thrown by nested functions, up, up, up, 
until some level "catches" the exception and deals with it, 
or the program terminates with an ugly error.
 It's important to handle exceptions gracefully and 
 prevent our programs from crashing.