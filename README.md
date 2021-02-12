# Local COCO Viewer

> Simple COCO Objects Viewer in Tkinter. Allows quick viewing on local machine.

![Example images](examples/example.jpg)

## Requirements
`python3` `PIL`

## Installation
- Clone the repository
```
git clone https://github.com/trsvchn/coco-viewer.git
```

- Install all necessary dependencies. It is highly recommended to install dependencies in a virtual environment
```console
# For Python venv
pip install -r requirements.txt
```

## Usage

```bash
python cocoviewer.py -h

usage: cocoviewer.py [-h] [-i PATH] [-a PATH]

View images with bboxes from the COCO dataset

optional arguments:
  -h, --help                    show this help message and exit
  -i PATH, --images PATH        path to images folder
  -a PATH, --annotations PATH   path to annotations json file
```

## Example:
Using microstructure scans:
```bash
python cocoviewer.py -i input\images -a input\annotations\output.json
```

Using official COCO dataset images:
```bash 
python cocoviewer.py -i coco\images -a coco\annotations\sample.json
```

