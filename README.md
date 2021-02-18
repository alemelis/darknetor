# darknetor

Hacked version of pytorch yolov4: [https://github.com/WongKinYiu/PyTorch_YOLOv4](https://github.com/WongKinYiu/PyTorch_YOLOv4)

The main purpose of this repo is to parse `cfg` files and return a `nn.Module` to be used as feature extractor.

```python
from darknetor.models.models import Darknet

backbone = Darknet('path/to/model.cfg')
```

## Acknowledgements

* [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
* [https://github.com/ultralytics/yolov3](https://github.com/ultralytics/yolov3)
* [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)
