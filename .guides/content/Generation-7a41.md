##

Up until this point, we have used the GPT-3 model as a means to answer questions or classify words. One of the more interesting features associated with OpenAI is its ability to generate new and innovative content. For example, you can create a prompt that asks the model to generate three different product descriptions.

```markdown
Create 3 product names for the following description
a laptop that can last you 20 years
```

{Try it!}(python3 box.py 9)
{Reset}(python3 reset.py 9)

|||challenge
## Try this variation:

Have the model create two taglines for a donut shop.

```markdown
write 2 taglines for a donut shop
```

{Try it!}(python3 box.py 10)
{Reset}(python3 reset.py 10)
|||

The generation is not limited to simply text. You can ask OpenAI to generate emoji based on text in the prompt. In this example, we are asking the model to turn movie titles into emoji.

```markdown
Convert these movie titles into emoji: Matrix, Mulan, Spy kids
```

{Try it!}(python3 box.py 11)
{Reset}(python3 reset.py 11)

Not only can GPT-3 produce emoji, but it can also do the inverse. You can ask the model to generate movie titles based on a sequence of emoji.

```markdown
Based on the following guess the movie title : 🎥🔎, 🐎🔪, 🕵🏼‍♀️🧒
```

{Try it!}(python3 box.py 12)
{Reset}(python3 reset.py 12)

Lastly, the GPT-3 model can work with prompts that are more open-ended in nature. There should be multiple responses told from two different points of view, and they should still remain coherent.

```markdown
Emulate a text message conversation.
```
{Try it!}(python3 box.py 13)
{Reset}(python3 reset.py 13)

|||challenge
## Try these variations:
Give the conversation a topic (some good news) and have the conversation last longer.

```markdown
Emulate a long text message conversation about some good news.
```

{Try it!}(python3 box.py 14)
{Reset}(python3 reset.py 14)

|||

{Check It!|assessment}(multiple-choice-3902080072)
