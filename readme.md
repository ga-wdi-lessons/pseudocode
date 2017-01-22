# Pseudocode

## Learning Objectives
- Describe the role of pseudocode in development
- List the steps for problem solving
- Create pseudocode to describe a basic problem

## What Is Pseudocode? (10 minutes / 0:10)

Pseudocode is a way to describe the solution to a problem without writing code in full.
* Writing pseudocode forces you to think critically about the problem and break it down into smaller steps.
* It is usually written using a combination of english and logic. As a result, it is easy to read.
* It might display some features of the final product, such as indentation and code blocks.

Pseudocode should describe the entire logic of a problem so that programming becomes a task of translating pseudocode line by line into actual code.

## We Do: What Does Pseudocode Look Like? (15 minutes / 0:25)

<!-- AM: Should start by showing a good example of pseudocode. In the current lesson, they have no reference to what constitutes good pseudocode before judging whether the following examples are good or not. -->

For each of following examples, let's discuss why each might be considered a good or bad examples of pseudocode...

### Problem 1: Determining If a Number is Even or Odd

#### Example 1.1

```
PROGRAM IsEvenOrOdd:
  var num = number;
  IF (num % 2 === 0)
    THEN Print "even";
    ELSE Print "odd";
  ENDIF;
END.
```

<details>
  <summary><strong>What do we think?</strong></summary>

  > This is not a great example. Here we are using "var" in our pseudocode when it should read plain english! Also, we should not be using the javascript syntax "===" in our conditional.  Would a non-programmer know that `num % 2 === 0` indicates an even number?

</details>

#### Example 1.2

```
PROGRAM IsEvenOrOdd:
  Read number;
  IF (number divided by two has no remainder)
      THEN Print the number is even;
      ELSE Print the number is odd;
  ENDIF;
END.
```

<details>
  <summary><strong>What do we think?</strong></summary>

  > This is better.  It's closer to english.  It clearly states what we are trying to achieve and how, without getting bogged down in the minutia of code.  Even someone that doesn't code can help us check our logic.  Is any number that can be divided by two, cleanly -- without leaving a remainder -- even? Is anything else odd?

</details>

### Problem 2: How to Make a PB&J Sandwich

> Source: [Get Creative Today](http://getcreativetoday.com/lessons/pseudo-code-flowcharts/)

#### Example 2.1

<!-- AM: Should this example come first? It uses no code at all and might be a better intro the the concept. -->

```
Make PB&J Sandwich:
  Gather bread, peanut butter and jelly.
  Apply peanut butter to slice of bread.
  Apply jelly to another slice of bread.
  Bring to two slices of bread together.
  Eat and enjoy.
```

<details>
  <summary><strong>What do we think?</strong></summary>

  > This is a good place to start.  It is a good set of instructions and intuitive for us to follow.  However, we still don't know what physical steps are required.
  >
  > Take a second to imagine.  Imagine if you had never made a sandwich before.  Ever.  Think about the instructions you would need for that for that first sandwich.  A computer has no real memory.  Every time it starts a task, it has no recollection of performing it before.  We must tell it every single step, every single time.  We need to break these down into smaller steps for the computer to understand.

</details>

#### Example 2.2

```
PROGRAM MakePB&JSandwich:
  Grab a paper plate;
  Open bread container;
  Grab bread package;
  Untwist bread package;
  Open bread bag and remove two slices;
  Place slices on paper plate;
  Grab a plastic knife;
  Open peanut butter jar;
  Use knife to scoop out peanut butter;
  Apply peanut butter to one slice of bread;
  Spread peanut butter on slice;
  Place knife on plate;
  Close peanut butter jar;
  Open jelly bottle;
  Squeeze jelly onto second bread slice;
  Close jelly bottle;
  Place down jelly;
  Pick up knife;
  Spread jelly on slice;
  Bring two slices of bread together;
  Cut slices in half down the middle;
  Throw knife in the trash;
  Pick up one half of sandwich;
  Enjoy;
END.  
```

<details>
  <summary><strong>What do we think?</strong></summary>

  > This example's sequence is very thorough! However, we are still assuming certain conditions that our utensils or ingredients already exist. What if we are out of plates? Will we grab a napkin instead to place our sandwich on? What if we are out of jelly? Will you throw the sandwich away or eat it with just peanut butter?

</details>

Computers are not smart. We need to give them step by step instructions to account for conditions. They can not adapt to make changes without being explicitly told. Programing is a series of tasks, which can be completed only if a certain number of conditions are met.

Computers can not adapt, but we can.  Your first pass at pseudocode will probably not cover everything.  Once you know more, you may come back to update and refactor your pseudocode.


## You Do: Solve the Waiter Problem (10 minutes / 0:35)

> 5 minutes exercise. 5 minutes review.

Spend 5 minutes starting to pseudocode the following problem...

A waiter has N tables, each with 2-4 guests.
- The waiter makes rounds between each of their tables, the bar, and the kitchen.
- The waiter takes drink orders for a new table, then submits them to the bar.
- Drinks are delivered when all table orders are ready.
- The waiter takes food orders for a new table, then submits them to the kitchen.
- Food is delivered when all table orders are ready.
- The waiter checks idle tables for additional requests, then submits them appropriately.
- Additional requested items are delivered when all table orders are ready.

We realize you don't have enough time to solve the problem fully. Through this exercise, however, you will begin to see the importance of clearly identifying a problem.

#### Q. In one sentence, what problem were you solving?

## Approaching a Coding Problem (15 minutes / 0:50)

Pseudocode isn't just about writing down the steps that you already know. It's a tool to help you work through the problem. Before we can write pseudocode to solve the problem, we need to know the problem.  

#### Identify the Problem

- What exactly are we trying to solve?
- What are we delivering?

#### Conceptualize

- Look at the big picture
- Avoid details
- Whiteboards and pen-and-paper can be useful tools here

#### Break It Down

- Break the conceptual models down into concrete steps / actionable items
- Identify risks (e.g., gaps in knowledge and technology)

#### Start Small, Stay Small

Write code using those concrete steps
- Verify that each step achieves what we want before continuing on
- If we do too much at once and things break, which they always do, we won't know what is causing the problem
- Humans thrive on easy wins and forward progress. Use this to your advantage.


### Where Does Pseudocode Fit In?

<!-- AM: Seems like it fits in only with "Break It Down" -->

#### "Break It Down" or "Start Small"

This process is iterative.  We keep circling around and repeating the earlier steps, just at a different level.

When we first approach a problem, we see the big picture. "Break it down" gives us big steps. Then we take one of those steps and "Break it down". Now, starting small, we write pseudocode to help illustrate the problem.  

Pseudocoding proves that we have *identified* the problem, understand it *conceptually*, and have *broken it down* into *small steps* that we can follow.


## Pseudocode Syntax

<!-- AM: Have students go through this section themselves -->

There is no singular pseudocode syntax. It just needs to be clear, simple and concise. Here's one example...

#### General Structure of Pseudocode

```
PROGRAM <ProgramName>:

<Do Stuff>

END
```

#### Selection: IF/ELSE Statements

```
IF (<Condition>)
  THEN <Statements>
  ELSE <Statements>
ENDIF
```

#### Iteration: LOOP

```
WHILE (<Condition>)

ENDWHILE
```

> Source: [Introduction to Pseudocode](http://www.slideshare.net/DamianGordon1/pseudocode-10373156)

## You Do: Pseudocode a Real-World Problem (20 minutes / 1:00)

> 15 minutes exercise. 5 minutes review.

<!-- AM: Already gone over the time limit. Need to figure out what to remove from lesson. -->

<!-- AM: If we keep this exercise, remove options and have all students to the same one. -->

Break into small groups and pick one of the below games to pseudocode.

Students should take 10 minutes to pseudocode the first problem in pairs. Each pair should then swap code with another team and spend 5 minutes
reviewing each other's code, leaving feedback.

### Option 1: A Trivia Game

The game should have a preset list of questions, which are shown one at a time
to the user. The user submits their answer and goes the the next question. After
each question they can see whether they were correct or incorrect. They can also
see their total score.

### Option 2: Concentration

The user should see a grid of cards. Clicking a card reveals it and allows them
to click another card. If they match, the cards stay up and if not they flip
back over. Users get a point for every pair they flip. The game ends after 1
minute or all cards have been matched.

### Option 3: Flash Cards

The user should start with a shuffled list of pre-existing cards. They can go
back and forth between cards and 'flip' the flash card to go from back-to-front
or front-to-back.

Optionally, users may mark a card 'correct' if they knew the answer on the back
of the flash card, in which case it's temporarily removed from the deck.

### Option 4: War (Card Game)

Users can play the [game of 'war'](https://en.wikipedia.org/wiki/War_(card_game))
against a computer. The game continues until 1 player runs out of cards.

## Conclusion

1. What are some helpful steps for solving problems?
2. What does pseudocode help us do?
3. Do we only pseudocode at the start of a project?

## Resources

- [Introduction to Pseudocode](http://www.slideshare.net/DamianGordon1/pseudocode-10373156)
- [Get Creative Today](http://getcreativetoday.com/lessons/pseudo-code-flowcharts/)

## Screencasts

- [Pseudocoding](https://www.youtube.com/playlist?list=PL-6bwUTtCRVTMUUSjqIYVXYyfZBzs8saD)
