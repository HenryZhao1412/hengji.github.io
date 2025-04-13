# Hengji's learning blog about Deep Learning & Fastai

The learning after reading the fastbook "01_intro.ipynb"

## Maching Learning

### Traditional Programs

Normally, when the coders are planing to write a program to solve some problems, they just need to think about what inputs they need and what acts should the code do, and then write the code. For example when we are writing a function in Python, we need to think about what input the function require and what steps it should do and what varaible it will return. Like the Python below.

```python
def two_number_addition(number1, number2):
    value = number1 + number2
    return value
```
To the code upon, it takes two numbers as input and do the addition operation. We use the following graph to represent this step.

![Program](image1.png)

### Weight

Weights are variables, the notebook take a example of the dog classifier, it takes images pixels as inputs, the weights are values define how the program will operate. The structure is shown in the following figure.

![Weight](image2.png)

### Weight Update
During the machine learning model process, weight should be able to be adjusted every time according to the results of training. It should be sent to the model together with the input data, then the model will give out the result of the training, the model will compare the results with the real label, then evaluate the performance of the model, if the performance do not good, the weight will be updated and then send to the model with input data again, after several iterations, make the performance of the model be perfect. The process should be like the following figure.






































