
# Photo Editor

A Python script to quickly edit photos





## Installation

Get started

1) Clone my project

```bash
  git clone git@github.com:YuhboiJC/Photo-Editor.git
```
Or

2) Download zip

## Run
To run create two files

```bash
cd Photo-Editor
mkdir imgs
mkdir editedImgs
```

Run

```bash
  python3 photoEditor.py
```


## Optimizations

To change how you would like your photos edited follow the https://pillow.readthedocs.io/en/latest/handbook/index.html and save changes to:
PhotoEditor.py
```bash
{edit = img.filter(ImageFilter.SHARPEN).convert('L').rotate(-90)

    factor = 1.5
    enhancer = ImageEnhance.Contrast(edit)
    edit = enhancer.enhance(factor)}
