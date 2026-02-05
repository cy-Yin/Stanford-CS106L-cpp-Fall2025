This repository contains all the materials of the course "**Standard C++ Programming**" in the **Stanford CS106L** in the semester of **fall 2025**, including the slides and my solutions of all the 7(+1) assignments.

One can find the course website [here](https://web.stanford.edu/class/cs106l/index.html).

About the assignments, one can find the official **homework starter** repository [here](https://github.com/cs106l/cs106l-assignments). Since each term the assignments may be slightly different, if you want to get the exact same assignments as in this repository, please refer to the commit `24e6717` of the starter repository, which is the version I used in fall 2025.

Or just click [this link](https://github.com/cs106l/cs106l-assignments/tree/24e6717339152fa1ae7ac35845a58893b6540596) to directly access fall2025-version assignments.

### Setup Instructions

I have done the assignments on my local machine with **Ubuntu 20.04 LTS** installed. To set up the development environment, please follow the instructions below:
```shell
sudo apt update
sudo apt-get install python3 python3-venv
sudo apt-get install g++-14
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-14 14
sudo apt-get install git
```

And make sure that you have installed 
- `python3` version >= 3.8 
- `g++` version >= 14

> [!NOTE]
> In the [official repository](https://github.com/cs106l/cs106l-assignments), it suggests to use `g++-10` if you are using **Linux**. However, I found that `g++-10` has some problems with `c++23` standard, so I used `g++-14` instead.