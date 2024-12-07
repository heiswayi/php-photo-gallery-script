# php-photo-gallery-script

A simple photography site built with [nanogallery2](https://github.com/nanostudio-org/nanogallery2).

## Instructions

### 1. Prepare image files

Rename your image files properly as this will be used as image title. Recommended to not more than `20` characters as by default, the title length that is more than `20` characters will be stripped from thumbnail display.

### 2. Put image files into `photos` directory

Then, put all of your images into `photos` directory. Example of file structure:

```
./photos                        (directory)
    +-- Album A                 (directory)
    |     +-- Picture-1.jpg     (file)
    |     +-- Picture-2.jpg     (file)
    |     +-- ...
    +-- Album B                 (directory)
    |     +-- Picture-3.jpg     (file)
    |     +-- Picture-4.jpg     (file)
    |     +-- ...
    +-- Picture-5.jpg           (file)
    +-- Picture-6.jpg           (file)
    +-- Picture-7.jpg           (file)
    +-- ...
```

### 3. Make `photos` directory writable

```bash
sudo chmod -R 777 photos/
```
