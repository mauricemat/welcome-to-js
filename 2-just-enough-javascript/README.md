# Just Enough JavaScript

JavaScript is a huge and powerful programming language, this makes it exciting
but also challenging to learn.

In this module you will only learn a small part of what JavaScript has to offer.
You will learn _just enough_ JavaScript to make small programs that process text
and interact with users. Why just enough, and not a little more? Because reading
and understanding program logic is more important than JavaScript, so why let
the code get in the way?

In this directory is is all the JavaScript you will find in this module's
examples and exercises. Don't be mistaken, there's a lot you can do with only
this!

---

## Priorities

Concepts and examples in this chapter are each given a priority (🥚, 🐣, 🐥).
The main goal of this module is learning to read and trace code that is already
written.

You know you have mastered an example when you can answer all the `[ask me]`
questions about it, and/or when you can use a trace table to explain how it
works.

---

## Exercises

There are a few different kinds of exercises in Just Enough JavaScript. None of
these exercises will ask you to write code from an empty file, to write
functions, or to pass some automated tests.

Instead the exercises will be built around completed programs. You will need to
either fill in missing pieces, rearranged the lines, or trace how the variables
are used.

---

### 🥚 Quiz

> _static & dynamic analysis_

Some chapters will have a `/quiz` folder, these contain multiple choice
questions to test your knowledge. By the end of this module you should be
comfortable finding the right answers for each quiz **_and_** understanding why
the wrong answers are incorrect.

Careful, passing the quizzes is not enough! Being able to answer questions is
not the same thing as building and practicing skills. Even if you are
comfortable with the quiz in a chapter, you should _still_ keep practice the
exercises.

---

### 🥚 WriteMe

> _static analysis_

With WriteMe exercises you will practice writing out programs from a blank page.
On the left is an empty editor, on the right is the finished code: you need to
re-write the program _exactly_ into the editor on the left. But there's a catch!
You can only see one of the editors at a time, and you can't copy-type >:) Your
goal will be to memorize the syntax and structures of JavaScript, you will not
be running these programs or changing them.

You can study these exercises alone to memorize and master JS syntax, flipping
between _read_ and \_write like a flashcard. Or you can do them in small groups.
If you study these in groups you and your group members should take turns in
each role:

- **Reader**: The _reader_ will open the finished program and will read the
  program out loud, guiding the _writer_ as they complete the program. The
  reader's challenge is help the writer _exactly_ reproduce the code; each
  space, each new line, each character, each capital letter, everything!
- **Writers**: the _writers_ will try to write down _exactly_ the correct
  program following only the instructions of reader. No peaking! The writers
  should not look at the finished program, only listen to the advice of their
  reader and follow the hints in the editor.

Looking for an extra challenge? Try to complete these exercises _without ever_
showing each other your screens!

---

### 🥚 Reading

> _static analysis_

Practice reading small programs and identifying key features in the code. You
will need to find syntax features, different scopes, variable usage, and much
more.

---

### 🥚 Tracing Execution

> _dynamic analysis_

You will learn how to _be the computer_, how to execute code line by line with
your mind the same way the computer does. Until you learn how to _trace_ code,
programs and bugs will be a mystery! After you've learned how to trace, it will
still be hard to understand programs but you'll at least know how to start :)
Learning to trace is tricky, but will save you many many hours in the future.

Because it can be hard to know if you are tracing correctly without someone by
your side to answer your questions, there are a few buttons to help you along
the way:

- **table**: the _table_ button will open an empty trace table in your browser
  that you can use to step through a program by hand.
- **trace**: the _trace_ button will log a trace of the program's execution to
  the console. You can use this to learn how to step through a program, and to
  see if your trace tables are correct.
- **openIn jsTutor**: exercises without user interactions can be opened in JS
  Tutor, this website will show you what is happening in program memory with
  each step.

If you like to draw on code as you trace what's happening you can do that with
any file! Just replace `?--defaults` in your browser's URL bar with `?highlight`
and you're good to go.

<details>
<summary>Trace Tables</summary>

Trace tables have been around as long as computer programming (probably). The
challenge with a trace table is to run the code in your head, keeping track of
all the variables in your program by hand. This is also called a _dry run_ or a
_desk check_.

You can write trace tables on paper with a pencil, or you can use the trace
tables built into Study Lenses. There are three different types of trace table
available in Study Lenses:

1. **steps**: The _steps_ table asks you to be the computer and to go step by
   step through the program, recording each time a variable is declared, read,
   or assigned. When you use the steps table you can check your work by pressing
   `trace` button and comparing your table to the console output.
2. **values**: The _values_ table is the traditional type of trace table. With
   the _values_ table you only keep track of each time a variable is assigned a
   new value. You can also check your _values_ table by using the `trace` button
   and only checking against the _assign_ logs
3. **Operators**: This table is for studying operator precedence, you'll learn
   more about this in Debugging.

You may find that the **steps** table is more helpful in the beginning when you
are first learning. It forces you to pay close attention to each step of program
execution.

Later on you may prefer the **values** table because it allows you to look at
the bigger picture and see more clearly the _strategy_ (or _algorithm_) of a
program.

<details>
<summary>links about <strong>values</strong> trace tables</summary>
<br>

- videos
  - [TeamComputing](https://www.youtube.com/watch?v=DyeVR1zb7Jo)
  - [Computer Science Tutorials](https://www.youtube.com/watch?v=UbANyxE7pGE)
  - [Chris Mayfield](https://www.youtube.com/watch?v=tJGrie7k97c)
  - [Revise Computer Science](https://www.youtube.com/watch?v=dzYlncc72O0)
  - [5 Minutes to Code: Programming Basics "Trace Tables"](https://www.youtube.com/watch?v=i2qLAVBUERs)
- articles
  - [akxl - Desk Checking](https://www.akxl.org/JavaProgramming1/TraceTables.htm)
  - [101computing](https://www.101computing.net/using-trace-tables/),
    [online table](https://www.101computing.net/trace-table/)
  - [ibcomputerscience](https://ibcomputerscience.xyz/trace-tables/)
  - [wikipedia](https://en.wikipedia.org/wiki/Trace_table)
  - [bits of bytes](https://www.bitsofbytes.co/trace-tables.html)

</details>

</details>

---

### 🐣 Fill in the Blanks

> _static analysis_

Fill-in-the-blanks exercises will be JS scripts with some blanks for you to fill
in and (sometimes) a comment describing what should happen. Some exercises will
simple like this:

```js
'use strict';

console.log(true && _); // true
```

But others will be more complex. Larger exercises will open with the `?blanks`
lens where you will be able to decide how many words you want to remove from the
program. You will be shown a list of all the words that have ben removed from
the program, and have the option to compare the modified program to the correct
solution using a _diff editor_.

---

### 🐣 Parsons Problems

> _static & dynamic analysis_

Parsons problems are designed to help you study snippets of code without getting
caught by errors. You'll be given lines of code and your task is to place them
in order. But it's not always as easy as it sounds! Exercises will have extra
lines as distraction, you'll need to figure out which lines are part of the
program and which are there to confuse you.

- [all of the learning, less of the time time](https://computinged.wordpress.com/2017/11/17/parsons-problems-have-same-learning-gains-as-writing-or-fixing-code-in-less-time-koli-calling-2017-preview)
- [How to study programming](https://medium.com/swlh/how-to-study-computer-programming-parsons-problems-2bfdefabfd86)
- [what are these?](https://georgejmount.com/parsons-problems/)

---

### 🐣 Loggercises

> _dynamic analysis_

Loggercises are exercises where you practice writing as many programs as
possible that print the same logs. When you run a program the console will
display the _expected logs_ (what your program _should_ print) and your _actual
logs_ (what your program _did_ print). If your actual logs are different from
the expected logs the exercise will show which logs are incorrect.

These exercises are meant for exploring JavaScript and all the creative ways you
can write code that does the same thing. For example:

<details>
<summary>Here are 3 solutions to the challenge "<em>write
a program that logs <code>1</code>, <code>2</code>, <code>3</code></em>"</summary>
<br />

```js
'use strict';

console.log(1);
console.log(2);
console.log(3);
```

```js
'use strict';

let number = 1;
console.log(number);

number = number + 1;
console.log(number);

number = number + 1;
console.log(number);
```

```js
'use strict';

let number = 1;
while (number < 4) {
  console.log(number);
  number = number + 1;
}
```

</details>

There will be two types of loggercise:

- **Not Interactive**: These exercises will not have any user interactions, all
  you need to do is write code that matches the expected logs.
- **Interactive**: Interactive exercises will be more complicated. You'll need
  to write some code _and/or_ pass in the correct input to match the expected
  logs.

Each exercise comes with a few starter programs to help you think of different
ways to solve the same problem. But you're not limited to these suggestions, you
can always start a new solution from an empty page!

---

### 🐔 Specs

> _static & dynamic analysis_

> these exercises can be more challenging, if you get lots of errors or can't
> finish them right away that's ok. You'll learn more about writing programs
> later on.

"Specs" is short for "specifications". In development a
[_specification_](https://en.wikipedia.org/wiki/Software_requirements_specification#Structure)
is a description of the software that needs to be built - specific enough that
the team can get started but general enough that it doesn't tell them how to
write each file of code. Importantly, specs will also help a team know when
their software is good enough to call it done.

The `specs` exercises will ask you to write small interactive programs that meet
certain specifications. None of these exercises will be large programs, and each
one can be solved using only what you have learned in previous chapters of Just
Enough JavaScript.

All exercises will have these 4 parts:

1. **User Stories**: those are the interactions a user can have with this
   software when it is finished. You will also be given _acceptance criteria_ to
   help you know when you've satisfied the user story.
2. **Test Cases**: example input/output pairs - What data can you expect to come
   out of your program when you input certain values? You can use these test
   cases to make sure your software functions correctly. But don't stop there!
   See if you can think of other strange inputs that might break your program.
3. **Starter Code**: each exercise will have some starter code with a couple `_`
   blanks. You can change this as much as you want, it's just a suggestion
4. **Checklist**: working code does not mean you're finished! There is a
   checklist to help you know when your code is complete. You will need to make
   sure your code is formatted, has good variable names, is well-commented and
   error-free.

Even with these constraints, there are many different solutions to each problem.
See how many you can find! Below are 3 different ways to write a program that
meet the same specifications - to add excitement to the user's input (and there
are still many more solutions):

<details>
<summary>the challenge</summary>

```js
'use strict';
/*
  1. ===== the user story =====

  a user can provide any input to a prompt
    - given the input is null, the program is sad
    - given the input is not null, the program is excited

  2. ===== the test cases =====

  test cases:
    the user cancels:
      null -> ':('
    any input is exciting:
      '' -> '!'
      'hi' -> 'hi!'
      'javascript' -> 'javascript!'
*/

// 3.  ===== the starter code =====

console.log('--- begin program ---');

/* --- gather user input --- */

let input = prompt(_);
console.log('input:', input);

/* --- declare initial output --- */

let output = _;

/* --- create final output --- */

/* --- alert the result --- */

console.log('output:', output);
alert(output);

console.log('--- end program ---');

/*
  4. ===== the checklist =====

  checklist:
    [ ] the code is formatted
    [ ] variable names are clear and helpful
    [ ] each line of code is explained in a comment above that line
      - use full sentences and correct JS vocabulary
    [ ] the program runs
    [ ] the program has no errors
    [ ] all of the test cases work
    [ ] you tested strange inputs that could break your program (edge cases)
*/
```

</details>

<details>
<summary>solution 1</summary>

```js
'use strict';
/*
  a user can provide any input to a prompt
    - given the input is null, the program is sad
    - given the input is not null, the program is excited

  test cases:
    the user cancels:
      null -> ':('
    any input is exciting:
      '' -> '!'
      'hi' -> 'hi!'
      'javascript' -> 'javascript!'
*/

console.log('--- begin program ---');

/* --- gather user input --- */

// maybe not the most clear instructions, but it's good enough for now
let input = prompt('if you cancel i will be sad. otherwise i will be excited.');
console.log('input:', input);

/* --- declare initial output --- */

// declaring output to an empty string
//  it will be assigned the correct value in a conditional later on
let output = '';

/* --- create final output --- */

// input will only be null if the user canceled
if (input === null) {
  // assign the sad output value because the user canceled
  output = ':(';
} else {
  // this is the path for any input that is not from the user canceling
  //  since the user didn't cancel, i assigned added some excitement
  output = input + '!';
}

/* --- alert the result --- */

console.log('output:', output);
alert(output);

console.log('--- end program ---');

/*
  checklist:
    [x] the code is formatted
    [x] variable names are clear and helpful
    [x] each line of code is explained in a comment above that line
      - use full sentences and correct JS vocabulary
    [x] the program runs
    [x] the program has no errors
    [x] all of the test cases work
    [x] you tested strange inputs that could break your program (edge cases)
*/
```

</details>

<details>
<summary>solution 2</summary>

```js
'use strict';
/*
  a user can provide any input to a prompt
    - given the input is null, the program is sad
    - given the input is not null, the program is excited

  test cases:
    the user cancels:
      null -> ':('
    any input is exciting:
      '' -> '!'
      'hi' -> 'hi!'
      'javascript' -> 'javascript!'
*/

console.log('--- begin program ---');

/* --- gather user input --- */

// maybe not the most clear instructions, but it's good enough for now
let input = prompt('give me something to be excited about:');
console.log('input:', input);

/* --- declare initial output --- */

// initialized the output to the sad output, assuming the user canceled
//  if they didn't cancel, the program will later reassign the correct value
let output = ':(';

/* --- create final output --- */

// check if the user inputted a string value
if (input !== null) {
  // if they did not cancel, be excited about their input
  output = input + '!';
}

/* --- alert the result --- */

console.log('output:', output);
alert(output);

console.log('--- end program ---');

/*
  checklist:
    [x] the code is formatted
    [x] variable names are clear and helpful
    [x] each line of code is explained in a comment above that line
      - use full sentences and correct JS vocabulary
    [x] the program runs
    [x] the program has no errors
    [x] all of the test cases work
    [x] you tested strange inputs that could break your program (edge cases)
*/
```

</details>

<details>
<summary>solution 3</summary>

```js
'use strict';
/*
  a user can provide any input to a prompt
    - given the input is null, the program is sad
    - given the input is not null, the program is excited

  test cases:
    the user cancels:
      null -> ':('
    any input is exciting:
      '' -> '!'
      'hi' -> 'hi!'
      'javascript' -> 'javascript!'
*/

console.log('--- begin program ---');

/* --- gather user input --- */

// maybe not the most clear instructions, but it's good enough for now
let input = prompt('give me something to be excited about:');
console.log('input:', input);

/* --- declare initial output --- */

// initialize the output to be excited, assuming the user didn't cancel
//  if they did cancel, the program will later reassign the correct value
let output = input + '!';

/* --- create final output --- */

// check if the user actually canceled
if (input === null) {
  // if they did cancel, be sad
  output = ':(';
}

/* --- alert the result --- */

console.log('output:', output);
alert(output);

console.log('--- end program ---');

/*
  checklist:
    [x] the code is formatted
    [x] variable names are clear and helpful
    [x] each line of code is explained in a comment above that line
      - use full sentences and correct JS vocabulary
    [x] the program runs
    [x] the program has no errors
    [x] all of the test cases work
    [x] you tested strange inputs that could break your program (edge cases)
*/
```

</details>
