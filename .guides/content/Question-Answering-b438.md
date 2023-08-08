##

We have seen how GPT-3 answers questions based on existing knowledge. What happens if we ask it a question that it could not know based on existing data? Copy the question below and paste it into the file on the left. Click the `TRY IT` button to see the response, which appears in the file on the left.

```markdown
Q: What is my name?
```

{Try it!}(python3 box.py 1)

You can use the reset button below to clear the text in the file on the left.

{Reset}(python3 reset.py 1)

Notice how it tells you some variation of it does not know. We are going to show the model a pattern to use instead of saying "I don't know". Guide the model towards a factual answering by showing it how to respond to questions that fall outside its knowledge base. Using a `?` to indicate a response to words and phrases that it does not know provides a natural response that seems to work better than more abstract replies. Copy the entirety of the block below and paste into your box. 

```markdown
Q: Who is james bond?
A: James Bond is a fictional character created by Ian Fleming. Bond is a British secret agent who works for MI6.

Q: what is a lkdaos?
A: ?

Q: who was Barack Obama?
A: Barack Obama was the 44th President of the United States.

Q:what is ploasd?
```

{Try it!}(python3 box.py 2)

{Reset}(python3 reset.py 2)

After running the code above try running a question it would know, such as the one below. GPT-3 responds with the correct answer because you are only training the model to respond with a `?` when it does not know the answer.

```markdown
Q:what planet is the biggest in our solar system?
```

{Try it!}(python3 box.py 3)

{Reset}(python3 reset.py 3)

GPT-3 also has the ability to generate answers for questions that require a complex response. For example, you can ask the model to return ten movies from the science fiction genre.

```markdown
List 10 science fiction movies:
```

{Try it!}(python3 box.py 4)

{Reset}(python3 reset.py 4)

You can use the reset button to clear the text file and create new and complex questions for GPT-3. Use the `TRY IT` button to generate another response.

{Check It!|assessment}(multiple-choice-3923568454)
