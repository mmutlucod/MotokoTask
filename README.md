# Calculator - Motoko

This project is a simple calculator application written in the Motoko language. It supports basic operations such as addition, subtraction, multiplication, and division.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero-division check)
- Memory reset

## How to Run

To run this project, you need to have the [Dfinity SDK](https://internetcomputer.org/docs/current/developer-docs/build/install-upgrade-remove/) installed. Follow the steps below to run the project:

1. Navigate to the project directory:
   ```bash
   cd hesap-makinesi

2. Start the Dfinity background services:
    ```bash
    dfx start --background
3. Deploy the project:
    ```bash
    dfx deploy
4. To test the functions, use the following commands:
    ```bash
    dfx canister call hesap_makinesi add '(5)'
    dfx canister call hesap_makinesi subtract '(2)'
    dfx canister call hesap_makinesi multiply '(3)'
    dfx canister call hesap_makinesi divide '(2)'
    dfx canister call hesap_makinesi clear

## Requirements
    Dfinity SDK
    Visual Studio Code (or any other text editor)
