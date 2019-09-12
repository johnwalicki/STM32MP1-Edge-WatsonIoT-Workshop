*Quick links :*
[Home](/README.md) - [Part 1](../part1/README.md) - [Part 2](../part2/README.md) - [Part 3](../part3/README.md) - [**Part 4**](../part4/README.md)
***
**Part 4** - [Watson Studio](STUDIO.md) - [Training Data](TRAINING.md) - [Notebooks](JUPYTER.md) - [**STM32MP1 model**](MODEL.md) - [Summary](SUMMARY.md)
***

# Run the model on the STM32MP1 device

## Learning Objectives

In this section you will learn how to take the model parameters generated in the previous section and implement a function to run the model on the ESP8266 to provide real-time classification.

## Logistic regression

The algorithm at the heart of the model we generated is [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression), which uses the Logit function (long-odds) then applies the Logistic sigmoid function:

Logit function for 2 predictor values h and t (humidity and temp) is: ```C + w1*h + w2*t``` where C is a constant and w1 and w2 are weighting values for the predictors.

The values of C, w1 and w2 are the values from the Jupyter Notebook in the previous section: ![model output](screenshots/WatsonStudio-model-parameters.png)

Here the coefficients are w1 and w2 and the intercept is the constant C.  Note the order of the weightings was specified by the order of the properties fed into the Vector Assembler:

```python
vectorAssembler = VectorAssembler(inputCols=["humidity","temp"], outputCol="features")
```

so the first coefficient is the weighting for the humidity property and the second coefficient is the weighting for the temperature property.

The sigmoid function is: ```f(x) = 1/(1+e^-x)```

Given the two functions we can create an implementation in Node-RED that can be run on the Node-RED edge application:

***
**Part 3** - [Watson Studio](STUDIO.md) - [Training Data](TRAINING.md) - [Notebooks](JUPYTER.md) - [**STM32MP1 model**](MODEL.md) - [Summary](SUMMARY.md)
***
