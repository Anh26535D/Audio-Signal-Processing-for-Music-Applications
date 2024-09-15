# Audio Signal Processing for Music Applications

This repository contains the programming assignments for the Coursera course **Audio Signal Processing for Music Applications**.

# Note

A4Part3 has wrong output!!!

## Installation
1. Clone the source repository:
    ```
    git clone https://github.com/MTG/sms-tools.git
    ```
2. Install modules
    ```
    pip install ipython numpy matplotlib scipy cython
    # and then  by going to the direcotry  and type:
    cd software/models/utilFunctions_C
    python compileModule.py build_ext --inplace 
    ```
3. Move all folders from this repository to the sms-tools/workspace/ directory.
4. Run the submission script for each assignment (make sure to obtain the email and token first):
    ```
    cd sms-tools/workspace/A1
    python submitA1.py
    ```