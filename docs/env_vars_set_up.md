## Environment Variables.

Set these environment variables.

DEBUG

GPU
- Can set to any truthy value. Example `GPU=1`. 

NUM
- Supports 0, 2, 4, and 7. Pretrained weights for Effecient Net.

## Are you running the GPU?

Run tests with:

``` python
python3 -m pytest
```

Specifically the following test will be fast:

``` bash
python3 test/test_mnist.py TestMNIST.test_sgd
``

And the GPU will be slow:
``` bash
python3 test/test_mnist.py TestMNIST.test_sgd_gpu
``
