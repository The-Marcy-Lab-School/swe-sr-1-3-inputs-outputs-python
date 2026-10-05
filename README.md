# Explaining Strings and Input

Teach a brand new programmer why a string never changes, and why everything a
person types arrives as text.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Setup](#setup)
- [Instructions](#instructions)
- [Short Response Questions](#short-response-questions)
  - [Prompt 1](#prompt-1)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses —
that holds in every mode, including implementer mode. You may use it to check
grammar and spelling on writing you have already done, and you may use it
before you start to quiz you until you can explain both ideas without notes.
Paste this if you want that kind of help:

> You are acting as a tutor. Quiz me on Python string immutability and on what
> input() returns, until I can explain both without looking anything up. Tell
> me when my reasoning is wrong or imprecise. Do not write or rewrite any part
> of my response for me.

A response you did not write is worth nothing to you in an interview, which is
where this writing is really aimed.

## Setup

Work in `development/mod-1`. Make a draft branch before you start.

```sh
git checkout -b draft
```

There is no code to run here. Pushing tells GitHub to check whether you have
written a response yet, which you can see in the **Actions** tab. That check
counts words. Your instructor reads what you wrote and replies on your pull
request.

## Instructions

Write your response in `short_response.md`. Aim for a response with these
qualities. Your instructor will give you feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

## Short Response Questions

### Prompt 1

Two things surprise almost everyone learning Python, and both show up the
first time you write a program that talks to a person. Write a short lesson
explaining them.

Your lesson should have four parts:

- Explain what it means that a string is **immutable**, and show what Python
  does when you try to change one in place. A code block with the error in it
  will do more work than a paragraph.
- Explain why this prints `ada` and not `ADA`, in terms of what `upper()`
  actually returns:

  ```python
  name = "ada"
  name.upper()
  print(name)
  ```

- Explain why `input()` hands back a string even when the person typed `25`,
  and what goes wrong if you use that value as a number without converting it.
- Describe one bug you would expect a new programmer to hit because of each of
  these, and how they would recognize it from the error message.

Use these terms correctly: **immutable**, **method**, and **type conversion**.

Defining them is the assignment, so we are not defining them here.

That last part is the one that matters. An explanation that only says what is
true is easy to agree with and easy to forget. One that names the mistake it
prevents is the one somebody remembers at 11pm.

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Open a pull request to your instructor for feedback.
