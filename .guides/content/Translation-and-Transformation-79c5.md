##

In addition to text generation, the GPT-3 model can translate and transform text.

## Translation

Translation is the process of converting information from one form to another. In the example below, we are asking the model to convert a phrase from English into French.

```markdown
translate the following to French: I am hungry and I want some pizza.
```

{Try it!}(python3 box.py 15)
{Reset}(python3 reset.py 15)

In addition, the model can figure out a translation without having to be told the specific language. In the example below, it can determine that a phrase in Spanish needs to be converted into English.

```
what does "Me gustaría comer una pizza" mean
```

{Try it!}(python3 box.py 16)
{Reset}(python3 reset.py 16)

Translation is not just going from one language to another. We can ask the model to translate a text from first- to second- or third-person. The following example translates the phrase from first-person to third-person.

```markdown
Convert first-person to the third-person: "I am big eater. I like to eat pizza in my car"
```

{Try it!}(python3 box.py 17)
{Reset}(python3 reset.py 17)

|||challenge
## Try this variation:
Translate the phrase from present tense to past tense.

```markdown
convert the following to past tense: I go to the store
```

{Try it!}(python3 box.py 18)
{Reset}(python3 reset.py 18)

|||

## Transformation 

Transformation has a slight but important difference from translation. Transformation is the process of converting information from one structure or format into another. In the example below, we give the model a sentence that is grammatically incorrect. GPT-3 can transform it into correct English.

```markdown
Correct sentences into standard English
I'm go to hunt for food. I no went to the park.
```

{Try it!}(python3 box.py 19)
{Reset}(python3 reset.py 19)

We can transform a text into a version that is easier to understand. The following example asks the model to simplify the definition of a function so a second grader can understand it.

```markdown
simplify the following text for a 2nd grader:

Functions are a sequence of instructions packaged as unit that perform a specific task. Programming languages come with pre-defined functions in their standard library. You can also create your own user-defined functions.
```
{Try it!}(python3 box.py 20)
{Reset}(python3 reset.py 20)

We can use OpenAI to transform from one programing language to another. The following example converts a simple for loop in Python to its equivalent in JavaScript.

```markdown
convert python to javascript 

for i in range (0,8):
    i=i+1
    print(i+2) 
```
{Try it!}(python3 box.py 21)
{Reset}(python3 reset.py 21)

{Check It!|assessment}(fill-in-the-blanks-3430980134)
