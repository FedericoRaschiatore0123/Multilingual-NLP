# README - Homework 2 NLP


## Installation
To run the code, install the following dependencies:

```shell
 pip install accelerate -U
 pip install transformers 
 pip install datasets 
```

## Train the model with original data

```python 2071132_main.py train --data original  ```

 This command trains the model using original dataset

## Test the model with original data
``` python 2071132_main.py test --data original ```

 This command tests the model using original dataset

# Train the model with adversarial data
``` python 2071132_main.py train --data adversarial ```

 This command trains the model using adversarial dataset

# Test the model with adversarial data
``` python 2071132_main.py test --data adversarial  ```
 This command tests the model using adversarial dataset
