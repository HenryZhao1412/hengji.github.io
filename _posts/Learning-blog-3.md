# Learning & Learning the bird & woodland model.

This blog is my learning about the example file `00-is-it-a-bird-creating-a-model-from-your-own-data.ipynb`, then I would explain my learning about this model from the perspective of code.

## Check the Internet connection

```python
import socket, warnings
try:
    socket.setdefaulttimeout(1)
    socket.socket(socket.AFINET, socket.SOCK_DGRAM.connect(('1.1.1.1', 53))
except socket.error as ex: raise Exception("STOP: No internet. Click '>|' in top right and set 'Internet' switch to on")
```

This step is to check if the device can connect to the Internet. In this file, it requires us to download the images from internet and then use the downloaded images to train this model. So, check internet connection is important, the result of not connecting, we will see the Figure 1 after we run the later codes.







































