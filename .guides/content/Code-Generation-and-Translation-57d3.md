
##

We tend to think about GPT-3 text generation abilities as being related to human languages. However, it can also work with programming languages. In the example below, the model can reason about a given code sample and determine the end result.

```markdown
what is the result of the following code?
x = 3
print(x ** 2)
```

```markdown
generate python code to sort an unsorted list
```
{Try it!}(python3 box.py 22)
{Reset}(python3 reset.py 22)

Because GPT-3 can reason about code, then it should be able to find bugs in the code. 

```python
# Fix bugs in the python function
 
# Buggy Python
import Random
a = "12"
b = random.randint(1,12)
add(a,b)
```

{Try it!}(python3 box.py 23)
{Reset}(python3 reset.py 23)


We can use it to explain a piece of Python code in human language.
```
explain the following code 
import Random
a = "12"
b = random.randint(1,12)
add(a,b)
```
{Try it!}(python3 box.py 24)
{Reset}(python3 reset.py 24)

More examples can be found in the [OpenAI](https://beta.openai.com/examples) website.

{Check It!|assessment}(multiple-choice-96566435)