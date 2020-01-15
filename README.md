# Lab2 - CYBR 2980
Variables, assignment, numerical types, arithmetic operators

## Magic8Ball.py
Create a program that will allow the user to ask a question, then provide a random response like a Magic 8 Ball.

- A traditional Magic 8 Ball has 20 possible answers:
- As I see it, yes.
- Ask again later.
- Better not tell you now.
- Cannot predict now.
- Concentrate and ask again.
- Don’t count on it.
- It is certain.
- It is decidedly so.
- Most likely.
- My reply is no.
- My sources say no.
- Outlook not so good.
- Outlook good.
- Reply hazy, try again.
- Signs point to yes.
- Very doubtful.
- Without a doubt.
- Yes.
- Yes – definitely.
- You may rely on it.

You may select to use these or answers you have created. They key is that they are given a random answer to the question they ask.

How to create a list of possible answers:
```
answers = ["thing 1", "thing 2"] # Each item must be in quotes, separated by a comma.
```
Since we imported random at the top of our file, we can use the following code to select a random item from the list.
```
response = random.choice(answers)
```
