# Assignment 2: C First Code

## Description

In this assignment, you will complete a simple programming project using C/C++, Git, GitHub, Classroom 50, and the generative AI tool of your choice.

[Gemini](https://gemini.google.com/) is recommended because ACC students have access to [additional AI tools and features through the college](https://infohub.austincc.edu/blog/2025/08/21/acc-launches-new-ai-powered-assistant/). However, you may use any generative AI tool you prefer.

The purpose of this assignment is not primarily the difficulty of the programming problem. Instead, this assignment will walk you through the complete development process used in this course while introducing you to the tools, practices, and workflow of professional software development.

For this assignment, the source file uses the C++ `.cpp` extension and is compiled with `g++`, but the program itself intentionally uses simple C-style programming conventions.

## Background

Before beginning this assignment, you should have:

- installed and configured the required Ubuntu development environment;
- installed and configured Git;
- created and configured your GitHub account;
- verified that Git and the C/C++ compiler are working properly; and
- completed **Assignment 1: Getting Started**.

## Instructions

### Development Process

You will complete this assignment in a series of required steps. Complete the steps **in order**.

For each programming step, you will:

1. read the requirement;
2. use generative AI as directed;
3. make the required change to the program;
4. compile and test the program;
5. stage the appropriate files;
6. make the required Git commit;
7. push the commit to GitHub; and
8. review the Classroom 50 autograding results before continuing.

Do not complete the entire program first and then commit everything at the end. The development history is part of the assignment, and each required development step **must appear as a separate commit**.

For this assignment, the required commit messages will be provided. Later assignments will require you to determine appropriate commit points and write your own descriptive commit messages.

You are responsible for understanding and verifying all code you submit, including code created or suggested by generative AI. AI may assist you with the work, but you must be able to explain what the resulting code does and verify that it satisfies the assignment requirements.

### AI Setup

Before beginning the programming steps, open the generative AI tool you plan to use and begin with the following prompt:

> I am a student in a C/C++ programming course, and I am learning to program with the help of generative AI. Act as my tutor and programming partner, not simply as an answer generator.
>
> I will give you my complete assignment. Read the entire assignment so you understand the goal, requirements, constraints, and required development sequence.
>
> Help me complete the assignment **one required step at a time, in the order given**. Do not jump ahead or solve later steps early.
>
> For each step:
>
> - explain what the requirement is asking;
> - explain any programming concepts or syntax I do not understand;
> - help me develop only that step;
> - explain the code and why it works;
> - help me compile, test, and verify it;
> - point out possible errors or assumptions; and
> - do not move to the next step until I tell you the current step has been tested, committed, pushed, and checked.
>
> I am responsible for understanding everything I submit. If I appear to be accepting code without understanding it, stop and explain it to me.

Then:

> Upload or paste this complete `ASSIGNMENT.md` file into the AI conversation.

### Step 1: Display a Message

Your first programming step is to make the program display:

```text
Number Analyzer
```

Use your AI assistant to help you understand how C/C++ displays text on the screen. Ask questions until you understand the code you are adding and why it works.

Modify `main.cpp` so that running the program produces exactly:

```text
Number Analyzer
```

Compile the program locally:

```bash
g++ main.cpp -o number-analyzer
```

Then run it:

```bash
./number-analyzer
```

Once the program works correctly:

1. Check your changes with `git status`.

2. Stage `main.cpp`.

3. Commit the change using the exact message:

   `Add Number Analyzer output`

4. Push the commit to GitHub.

5. Open the Classroom 50 Feedback pull request and review the autograding results.

Do not continue to Step 2 until this step has been compiled, tested, committed, pushed, and checked.

### Step 2: Read an Integer

Modify the program so that it asks the user to enter an integer, stores the value, and then displays the value entered.

Use your AI assistant to help you understand how C/C++ stores an integer in a variable and how `scanf()` reads keyboard input. Make sure you understand each line you add.

Your program should behave like this:

```text
Number Analyzer
Enter an integer: 7
You entered 7.
```

Compile and test the program locally. Try it with more than one integer to make sure the output changes correctly.

Once the program works correctly:

1. Check your changes with `git status`.

2. Stage `main.cpp`.

3. Commit the change using the exact message:

   `Add integer input and display`

4. Push the commit to GitHub.

5. Review the Classroom 50 autograding results.

Do not continue to Step 3 until this step has been compiled, tested, committed, pushed, and checked.

### Step 3: Make a Decision

Modify the program so that it determines whether the integer entered by the user is positive, negative, or zero.

Use your AI assistant to help you understand how an `if` / `else if` / `else` statement makes a decision. Make sure you understand each condition being tested and why only one result is displayed.

For a positive number, the program should behave like this:

```text
Number Analyzer
Enter an integer: 7
You entered 7.
The number is positive.
```

For a negative number:

```text
Number Analyzer
Enter an integer: -4
You entered -4.
The number is negative.
```

For zero:

```text
Number Analyzer
Enter an integer: 0
You entered 0.
The number is zero.
```

Compile and test the program locally with at least:

- one positive integer;
- one negative integer; and
- zero.

Once the program works correctly:

1. Check your changes with `git status`.

2. Stage `main.cpp`.

3. Commit the change using the exact message:

   `Add number classification`

4. Push the commit to GitHub.

5. Review the Classroom 50 autograding results.

Do not continue to Step 4 until this step has been compiled, tested, committed, pushed, and checked.

### **Step 4: Comment the Program**

Before continuing, your program must be documented according to the course [Commenting Guidelines](https://katrompas.accprofessors.com/commenting).

Review the C/C++ commenting example linked from the guidelines. Then update `main.cpp` so that it contains:

- the required file comment header at the top of the file; and
- the required function comment block for `main()`.

Follow the commenting format **exactly as shown in the course example**. Do not add unnecessary comments or comment individual lines of code that are already clear.

When finished, review the completed program and make sure there are no debug statements, commented-out code, trivial comments, or unnecessary comments.

Then stage, commit, and push with the exact message:

```text
Add required code documentation
```

### **Step 5: Update `README.md`**

Follow the [README.md guidelines](https://katrompas.accprofessors.com/readme-guidelines) and update the `README.md` file. All Markdown files must be properly formatted and look professional. Spelling, grammar, and writing skills count.

Then stage, commit, and push with the message:

```text
Update project README
```

**Note:** Commit messages for documentation changes may be more general because the document itself describes the change.

### **Step 6: Create `ESSAY.md`**

Create a new file named `ESSAY.md` in the root of your repository. This file documents how you used generative AI and what you learned while completing the assignment. All Markdown files must be properly formatted and look professional. Spelling, grammar, and writing skills count.

Answer each of the following questions in your own words:

1. Which generative AI tool did you use, and how did you use it while completing this assignment?
2. Describe one programming concept that AI helped you understand. Explain the concept in your own words.
3. Choose one piece of code that AI helped you create or understand. Explain what the code does and why it works.
4. Describe how you tested or otherwise verified something AI suggested. What did you do, and what was the result?
5. Describe one question you asked AI to better understand, challenge, or investigate its answer. What did you learn from the exchange?

Your responses do not need to be long, but they should be specific enough to demonstrate your understanding and how you worked with AI.

After creating the file, run:

```bash
git status
```

Notice that Git identifies `ESSAY.md` as a new, untracked file.

Stage `ESSAY.md`, then commit and push it using the message:

```text
Complete AI usage essay
```

### **Step 7: Final Review and Submission**

Before submitting the assignment, verify that your repository is complete.

1. Compile the program one final time:

```bash
g++ main.cpp -o number-analyzer
```

2. Run the program and make sure it works correctly:

```bash
./number-analyzer
```

3. Run:

```bash
git status
```

Your working tree should be clean.

4. Run:

```bash
git log --oneline
```

Verify that your required development commits appear in the history.

5. Open your repository on GitHub and confirm that your latest work, `README.md`, and `ESSAY.md` are all present.

6. Review the final Classroom 50 autograding results. Remember that the autograder score represents **tests passed, not your assignment grade**.

7. Copy the **normal** HTTPS URL for your GitHub repository.

8. Submit that URL in the Blackboard assignment.
