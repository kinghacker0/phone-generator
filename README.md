# PhoneNoGenerator

PhoneNoGenerator is a Python tool that generates all possible phone numbers from a given masked phone number format. The program replaces all 'X' characters in the input with digits (0-9) and outputs the resulting numbers to a file. It also includes a colorful ASCII banner and command-line arguments for easy usage.

## Features

- Generates all possible Indian phone numbers based on a given masked phone number.
- Uses `itertools` to generate all combinations of digits for the 'X' placeholders.
- Output can be saved to a custom file using the `-o` flag.
- Includes a colorful ASCII banner in RGB.
- Provides a help flag (`-h`) for user guidance.

## Installation

To use the tool, you need Python 3 and the following dependencies:

1. **Python 3**: Ensure Python 3 is installed on your machine. You can check by running:

    ```bash
    python3 --version
    ```

2. **Install the required Python dependencies**:

    Install the `termcolor` library for colored terminal output:

    ```bash
    pip install termcolor
    ```
2. **Clone Repo**:
   
    ```bash
    git clone https://github.com/kinghacker0/phone-generator
    ```


## Usage

Once the tool is installed, you can run it directly from the command line.

### Basic Usage

To generate possible phone numbers from a masked input (e.g., `860XXXXXX9`), use the following command:

```bash
python3 phoneno_generator.py 860XXXXXX9
