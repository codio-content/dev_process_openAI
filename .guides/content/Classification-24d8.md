##

GPT-3 can classify items into categories. Preface your prompt with instructions to classify a list of words.

```markdown
classify the following : cat, dog , car , plane
```

{Try it!}(python3 box.py 5)

{Reset}(python3 reset.py 5)

The model can use pattern matching to format the output of the classifications. The prompt below first asks GPT-3 to classify the list of objects. The next two lines are the pattern. List the object from the prompt and, on a new line, print `category:` followed by the classification of the object.

```markdown
classify the following : cat, dog , car , plane
cat
category: animal
```

{Try it!}(python3 box.py 6)

{Reset}(python3 reset.py 6)

The pattern matching above is similar to the way we guided the model in responding to questions that fall outside its knowledge base.

You can also ask GPT-3 to replace its own classification system with another. The examples below prompt the model to use the Entertainment Software Ratings Board (ESRB) rating system with an accompanying text. Compare the ratings between the two examples. 

<details>
<summary><strong>What is the ESRB?</strong></summary>
The ESRB is an organization that rates video game content (in Canada and the US) according to age and content. They use a system similar to the motion picture rating system.
</details>

```markdown
Provide an ESRB rating for the following text:

"There was once a great ninja who lived in a small village in Japan. He was a master of all the ninja arts and was respected by all who knew him. One day, a rival ninja from a nearby village challenged him to a duel. The ninja accepted and they fought a fierce battle."
```

{Try it!}(python3 box.py 7)

{Reset}(python3 reset.py 7)

```markdown
Provide an ESRB rating for the following text:

"Once upon a time, there was a vampire who lived in a dark, dank castle. He was a handsome vampire, with a strong jaw and piercing blue eyes. But he was also a cold-blooded killer, and he enjoyed nothing more than sinking his teeth into their neck and drinking the blood of his victims."
```

{Try it!}(python3 box.py 8)

{Reset}(python3 reset.py 8)

The GPT-3 model is adaptive in that it can use a third-party rating system for classification purposes.

{Check It!|assessment}(parsons-puzzle-2609532982)
