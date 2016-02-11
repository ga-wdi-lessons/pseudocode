# Pseudocode

## Learning Objectives
- Describe the role of pseudocode in development
- List the steps for problem solving
- Create pseudocode to describe a basic problem


## What is pseudocode? (10 m)

According to wikipedia, [pseudocode is](https://en.wikipedia.org/wiki/Pseudocode):
e
> Pseudocode is an informal high-level description of the operating principle of a computer program or other algorithm.

> It uses the structural conventions of a programming language, but is intended for human reading rather than machine reading.

This is a great opportunity to turn tech speak in, well, human speak.  Let's break that down.

???

### We Do: What does that look like? (45 m)


??? Show good examples

- to_oz


??? Compare and contrast examples




## Exercise: Draw Toast
http://gamestorming.com/core-games/draw-toast/
http://www.drawtoast.com/
Got a wicked problem? First, tell me how you make toast.


## Approaching a coding problem

- Identify the Problem
- Conceptualize
  - Big picture, big strokes
- Break it down
- Start small

### Identify the Problem

Use the examples from Problem Solving (Waiter, etc) BUT only for Identifying the problem.  

??? Maybe let the struggle to come up with answers for very short time.

### Review: the Steps

- Identify the Problem
- Conceptualize
  - Big picture, big strokes
- Break it down
- Start small

Q. Where does pseudocode fit?
---

> Break it down OR Start small

This process is iterative.  We keep circling around and repeating the earlier steps, just at a different level.

When we first approach a problem, we see the big picture.  "Break it down" gives us big steps.  Then, we take one of those steps and "Break it down".  Now, starting small, we write pseudocode to help illustrate the problem.  

Pseudocoding proves that we have *identified* the problem, understand it *conceptually*, and have *broken it down* into *small steps* that we can follow.


## Exercise: Buy Eggs

A programmer is going to the grocery store and his wife tells him, "Buy a gallon of milk, and if there are eggs, buy a dozen." So the programmer goes, buys everything, and drives back to his house. Upon arrival, his wife angrily asks him, "Why did you get 13 gallons of milk?" The programmer says, "There were eggs!"

1. Write the pseudocode that shows why he only bought 13 gallons.
2. Write pseudocode that gets me (errr.  um.  THAT programmer) to buy milk and eggs.

## Exercise: Pseudocode FizzBuzz

You're given a robot. The robot has no imagination or creativity whatsoever, but it's good at following rules.

The robot can only obey 9 commands: 

- Add two numbers together
- Subtract two numbers
- Multiply two numbers
- Divide two numbers
- Find the remainder of one number divided by another
- Remember a number
  - For example, "Number A is 42"
- Say something
- Go back to an earlier step in the instructions
- Tell if two numbers are equal, and if they are do one thing, and otherwise do another thing
  - For example, "If Number A equals 42, say 'Hello'. Otherwise, go back to step 3."

You need to write a list of instructions for the robot so that when it's given a number &mdash; say, 73 &mdash; for each number between 1 and 73:

- If the number is divisible by 3 it says "Fizz"
- If the number is divisible by 5 it says "Buzz"
- If the number is divisible by 3 and 5 it says "FizzBuzz"
- If the number isn't divisible by 3 or 5 is says the number

So if the number was 9, the robot would say:

```
"One"
"Two"
"Fizz"
"Four"
"Buzz"
"Six"
"Seven"
"Eight"
"Nine"
```

To start, consider:

- How would you get the robot to count to 73? You can't just say, "Count to 73." That's not one of the commands the robot knows. Of the 9 commands you've been given, which might be helpful?

- How can you tell if one number is divisible by another? (For example, 8 is divisible by 2, but not by 3.)

