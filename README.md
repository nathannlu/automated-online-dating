# Automating Online Dating

The motivation behind this project was my realization of how my time spent on Tinder could be spent being productive. Thinking of pickup lines is also a pain. I trained a CNN with Keras on Google Colab with [SCUT-FBP5500 dataset](https://github.com/HCIILAB/SCUT-FBP5500-Database-Release).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install.

```bash
pip3 install
```

## Usage

Grab your X-Auth-Token from devtools on any authenticated Tinder request and save it to an enviornment variable "X_AUTH_TOKEN".

```bash
python3 main.py
```

## Todos

- [ ] Extract faces from all photos and find the one that appears the most to determine the profile owner in a group setting.
- [ ] Improve accuracy in rating appearance by using a dataset generated by the user.
- [ ] Guess personality type and generate pickup line.
