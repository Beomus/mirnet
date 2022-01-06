# How to get this setup

**Note:** I am using the *MacAir M1 chip*

- [ ] miniforge3: <https://github.com/conda-forge/miniforge>

- [ ] ```conda create --prefix ./env python=X```

- [ ] ```conda activate ./env```

- [ ] Install dependencies: `conda install -c apple tensorflow-deps`

- [ ] Install tf-macos: `python -m pip install tensorflow-macos`

- [ ] Install tf-metal for GPU: `python -m pip install tensorflow-metal`

- [ ] Install whatever packages here

- [ ] Test the installation:

```python3
import tensorflow as tf
print(f"TensorFlow has access to the following devices:\n{tf.config.list_physical_devices()}")
print(f"TensorFlow version: {tf.__version__}")
```
