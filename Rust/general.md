# Ownership
Rules
1. Each value has a variable called its owner
2. Only one owner at a time
3. When owner goes out of scope, the value will be dropped


## Borrowing

## Slices

## Name Conventions
* Crates - snake_case (but prefer single word)
* Modules - snake_case
* Types - CamelCase
* Traits - CamelCase
* Enum variants - CamelCase
* Functions - snake_case
* Methods - snake_case
* General constructors	- new or with_more_details
* Conversion constructors - from_some_other_type
* Local variables - snake_case
* Static variables - SCREAMING_SNAKE_CASE
* Constant variables - SCREAMING_SNAKE_CASE
* Type parameters - concise CamelCase, usually single uppercase letter: T
* Lifetimes	- short, lowercase: 'a
