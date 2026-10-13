# Short Responses

For this short response assignment, aim to write a response with the following
qualities (your instructor will give you feedback on these areas):

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

Write your response in the space provided. Make sure to preview your markdown
to check how it is rendered before submitting.

## Question 1

A sign-up program asks for the user's full name, then prints a welcome message and a username. Suppose the user types

```
    ada LOVELACE
```

with spaces before and after the name. The program should print:

```
Welcome, Ada! Your username is alovelace
```

The program finds the parts of the name with this code:

```py
space = name.find(" ")
first = name[:space]
last = name[space + 1:]
username = first[0] + last
```

### Prompt 1

In your own words, explain what it means to **clean**, **validate**, and **parse** input. For each step:

- Say what this program should do at that step, and name the string tools it would use.
- For **cleaning** and **validating**, predict what the program would print if it skipped that step, and explain why.
- For **parsing**, explain why the program could not build the username without it.

### Response 1

Your response here...
