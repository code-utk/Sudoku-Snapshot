# Sudoku-Snapshot
===================

*Take a picture of a Sudoku and have Sudoku Snapshot solve it for you!*

----------
 TODO:
---------
 - [ ] Improve algorithm to get better Sudoku Grid extraction, make it `more robust against blurs` .
 - [ ] Improve `empty cell detection`. Only a basic logic is used right now.
 
Prerequisites:
-------------

- Python 2.7 but __not__ Python 3
    - Download from [here](https://www.python.org/downloads/)

- OpenCV
    - `sudo apt-get install python-opencv` (preferred)
    - Install OpenCV from [here](http://opencv.org/downloads.html) 

- Numpy (1.11.0)
    - `pip install numpy` (preferred)
    - You can build it from source [here](https://github.com/numpy/numpy)

How to use: 
----------
    git clone https://github.com/code-utk/Sudoku-Snapshot.git
    cd Sudoku-Snapshot
    python sudoku.py <path-to-input-image>
    
Working:
-------
> Here's a Sudoku image from a smartphone:

![Input Sudoku Image](images/sudoku.jpg)
</br>
