 
# SarcasticGD: Sarcastic-stochastic learning with just one line
Stochastic gradient descent is well known for it's convergence garauntees and simple algorithm. However, one thing it's not known for is its ability to mock the user while it learns. Introducing **sarcastic gradient descent**: sarcastic-stochastic learning with just one line.

## Use
Using just a single line of code, users can now bear considerably more abuse and snark while they train their models. 

#### Input
```py
from sarcastic_gd.sarcastic_gd import sarcastic_gd

@sarcastic_gd
def train(X_train, y_train, B):
    # Code that makes machines take over the world

train(X_train, y_train, B)
```

#### Output
```py
(1)   err: 13.2453
(1)   err: 13.2453
(1)   err: 13.2453
.
.
.
(231) err: 0.00124e-16
>"You chose *that* model? I don't see any issue there..."
```

## Installation
The only requirement is Python >=3.6. Then you can acquire the package with:
```bash
pip install sarcastic_gd
```

## License
This package is available under the MIT license.
 
