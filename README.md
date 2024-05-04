# dlhw

This repository contains the solutions to the exercises given during the "Deep Learning" course I took during my DSSC studies at the University of Trieste (AY 2023/2024).

***Student:*** [Isac Pasianotto](https://github.com/IsacPasianotto/)
***Course repository:*** [Deep Learning](https://github.com/emaballarin/deeplearning-units/tree/main)


## To get started

All the exercise are solved using mainly [`pytorch`](https://pytorch.org/) package.


***Disclaimer:*** The code was tested only on the following configuration:
- Host system: [Fedora](https://fedoraproject.org/): `40`
- Python version: `3.12.2`

However, I am quite confident that the [`requirements.txt`](./requirements.txt) should be enough to make the code run on your machine.

To set up the [`venv`](https://docs.python.org/3/library/venv.html) virtual environment and install the required packages, run the following commands (assuming you are in a Unix-like environment with `python3.12` and `pip3` installed): 

```bash
python3.12 -m venv dlhwenv
source dlhwenv/bin/activate
pip3 install -r requirements.txt
```

And you should be good to go!

Once you are done, you can deactivate the virtual environment by running:

```bash
deactivate
```