# Python Image Resizer

Resize all images in a folder

## Python Packages

Just for reference, no install needed.
```python
from PIL import Image, ImageOps
from os import listdir
from os.path import isfile, join
```

## Usage

In the `main.py` file make sure to set the `InputPath` `OutputPath ` `ImageResize` `Overwrite`

```python
# The folder for the raw images that you want to resize
InputPath = './input'
# The resized images will be placed in this folder, make sure its empty < but not needed
OutputPath = './output'
# The Output resolution x, y
ImageResize = (266, 375)
# IMPORTANT: Will Overwrite files if True 
Overwrite = False
```
Set this values in the `main.py` file, then you can run the `main.py`


```bash
python main.py
```

## Contributing
Pull requests are welcome.
## License
MIT
