# Number Guessing Game in Rust  
This is a number guessing game written in Rust.  

## Code Credits  
The code is taken from chapter 2 of The Rust Programming Language by Steve Klabnik and Carol Nichols ([online version](https://doc.rust-lang.org/book/title-page.html) and [print version](https://nostarch.com/Rust2018) available).

## Purpose  
The book uses the code to show some of the Rust language and environment features. I've picked out a few of these that I find interesting and written about them.  

* [Initial Impressions of Rust](https://jeremybytes.blogspot.com/2021/09/initial-impressions-of-rust.html)

Here are a few of my picks:  
1. ```cargo new``` creates a new project **and** creates a Git repository.  
2. Pattern matching with ```match```.  
3. Error handling:  
    * Functions can return a Result type with an "Ok" / "Err" enum.
    * ```.expects("something bad happened")``` to include a message when an error happens (unhandled error).
    * Pattern matching on the Result lets you handle an error.
4. Variables are immutable by default and must be marked "mut" explicitly if the values can be changed.  
5. Variables can be shadowed, which allows us to reuse variable names (this seems much better when seen in context).

