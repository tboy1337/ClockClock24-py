# ClockClock24 Python

Python port of the [ClockClock project](https://clockclock.com/).

> ClockClock 24 is both a kinetic sculpture and a functioning clock. Its hands veer from unpredictable, mechanical spinning, to perfect, synchronised alignment; to visually represent the abstract concept of time, and to report real time.

## 🛠 Technical information

This project is a Python port of the original JavaScript/React implementation, using:
- [Python](https://www.python.org/) (3.6 or higher)
- [Tkinter](https://docs.python.org/3/library/tkinter.html) for the graphical interface

## Installation

### Install from PyPI

The simplest way to install ClockClock24 is directly from PyPI:

```sh
pip install clockclock24-py
```

### Install from source

To install the package from source:

```sh
# Clone the repository
git clone https://github.com/tboy1337/ClockClock24-py.git
cd ClockClock24-py

# Install in development mode
pip install -e .

# Or install directly
pip install .
```

## Running the application

After installation, you can run the application in several ways:

```sh
# Using the entry point (available after pip installation)
clockclock24

# Or run the module directly
python -m clockclock24_py.main

# Or from the repository root
python run.py
```

## Usage

Once the application is running:
- Press the spacebar to trigger the animation
- The clock will automatically update to show the current time
- Resize the window to adjust the clock size

## License

This project is licensed under the MIT License - see the LICENSE.txt file for details.