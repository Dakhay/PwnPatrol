<img src="https://github.com/Dakhay/PwnPatrol/assets/74660357/83741ab1-ac44-42d4-afba-c23398e957bb" alt="PwnPatrol_logo" width="300"/>

# PwnPatrol

PwnPatrol is a simple and fast tool designed for quick checks in pwn. It can display functions, assembly code, pseudo-code in C, trace library calls, and check security hardening.

## Features

- Display functions with their addresses.
- Show assembly code for specified functions.
- Show pseudo-code in C for specified functions.
- Trace library calls using `ltrace`.
- Run security checks using `checksec` and `hardening-check`.
- Perform full analysis with a single command.

## Installation

### Prerequisites

- `radare2`
- `Python3`
- `pip`

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/PwnPatrol.git
   cd PwnPatrol
   ```

2. Exemple :

   ```bash
   python3 pwnpatrol.py -f -s binary.bin
   python3 pwnpatrol.py binary.bin -a main 
   ```


<img src="https://github.com/Dakhay/PwnPatrol/assets/74660357/33b09393-8faa-4a74-aa40-2c05513b93d5" alt="PwnPatrol_example" width="1000"/>
