# Pseudocode

## Learning Objectives
- Describe the role of pseudocode in development
- List the steps for problem solving
- Create pseudocode to describe a basic problem

## What Is Pseudocode? (5 minutes / 0:05)

Pseudocode is a way to describe the solution to a problem without writing code in full.
* Writing pseudocode forces you to think critically about the problem and break it down into smaller steps.
* It is usually written using a combination of English and logic. As a result, it is easy to read.
* It might display some features of the final product, such as indentation and code blocks.

Pseudocode should describe the entire logic of a problem so that programming becomes a task of translating pseudocode line by line into actual code.

### How to Make a PB&J Sandwich (10 minutes / 0:15)

> Source: [Get Creative Today](http://getcreativetoday.com/lessons/pseudo-code-flowcharts/)

We're going to make a PB&J sandwich — for real.

In today's demo, the supporting instructor will act like a computer. You'll be tasked with guiding the instructor through the process of making the sandwich. Keep in mind that your instructions will need to be explicit otherwise things could get messy!

<details>
<summary>**Here's one approach to solving our problem**</summary>

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

> A. This example's sequence is very thorough! However, we are still assuming certain conditions that our utensils or ingredients already exist. What if we are out of plates? Will we grab a napkin instead to place our sandwich on? What if we are out of jelly? Will you throw the sandwich away or eat it with just peanut butter?
</details>

## Approaching a Coding Problem (15 minutes / 0:35)


Computers are not smart. We need to give them step by step instructions to account for conditions. They can not adapt to make changes without being explicitly told. Programing is a series of tasks, which can be completed only if a certain number of conditions are met.

Computers can not adapt, but we can.  Your first pass at pseudocode will probably not cover everything.  Once you know more, you may come back to update and refactor your pseudocode.

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

#### "Break It Down"

This process is iterative.  We keep circling around and repeating the earlier steps, just at a different level.

When we first approach a problem, we see the big picture. "Break it down" gives us big steps. Then we take one of those steps and "Break it down". Now, starting small, we write pseudocode to help illustrate the problem.  

Pseudocoding proves that we have *identified* the problem, understand it *conceptually*, and have *broken it down* into *small steps* that we can follow.

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

  > This is better.  It's closer to English.  It clearly states what we are trying to achieve and how, without getting bogged down in the minutia of code.  Even someone that doesn't code can help us check our logic.  Is any number that can be divided by two, cleanly -- without leaving a remainder -- even? Is anything else odd?

</details>


## You Do: Pseudocode a Real-World Problem (15 minutes / 0:50)

Break into pairs and pick one of the below games to pseudocode.

Take 10 minutes to pseudocode the game with your partner. Each pair should then swap code with another team and spend 5 minutes
reviewing each other's code, leaving feedback.

### Option 1: A Trivia Game

The game should have a preset list of questions, which are shown one at a time
to the user. The user submits their answer and goes to the next question. After
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
