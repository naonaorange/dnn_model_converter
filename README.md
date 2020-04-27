# dnn_model_converter

this script convert dnn model to other format.

at now, we can convert Keras model format(h5) to Tensorflow model format(pb) only.

# Environment
Python 3.7 or upper

# Install

Please install tensorflow and keras.
```sh
pip install tensorflow==1.15.2 keras==2.2.4
```

# How to use

```python
dnn_model_converter.py mnist.h5 mnist.pb
```

