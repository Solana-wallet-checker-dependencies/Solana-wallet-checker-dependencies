# Solana Wallet Checker Dependencies: Build and Configure with Ease

**SolanaChecker** is a comprehensive tool for interacting with the Solana blockchain. It provides users with several useful functions for checking wallet status, managing assets, and exploring the network. This guide will help you to ensure you have the correct Solana wallet checker dependencies installed and configured to run the project.

<p align="left">
    <img src="/previews/black.webp" />
</p>

## Program Features

1.  **Check Solana Address Balance:** Check Solana balance.

<p align="left">
    <img src="/previews/crisp.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security.

<p align="left">
    <img src="/previews/area.webp" />
</p>

3.  **Track Solana Addresses:** Get Telegram notifications.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet data using a mnemonic phrase (seed phrase).

<p align="left">
    <img src="/previews/tall.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/previews/chart.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Research):** Brute-force.

<p align="left">
    <img src="/previews/system.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build, Then Install Dependencies

You can download a pre-compiled build, or build the project yourself. Building the project from source and understanding how to manage your Solana wallet checker dependencies is crucial for security and customization.

## Building the Project: Dependency Management

This section outlines the steps for handling the Solana wallet checker dependencies, ensuring a successful build process.

### Installing Dependencies Using vcpkg (Recommended):

*   **vcpkg** simplifies dependency management, making it easier to build.
    1.  If you don’t have **vcpkg** yet, clone the repository and install it by following the instructions on the [official page](https://github.com/microsoft/vcpkg).
    2.  Add vcpkg to your system PATH.
    3.  Run the following commands in your terminal:

        -   Install **OpenSSL**:
            ```bash
            vcpkg install openssl
            ```

        -   Install **nlohmann-json**:
            ```bash
            vcpkg install nlohmann-json
            ```

        -   Install **Crypto++**:
            ```bash
            vcpkg install cryptopp
            ```

        -   Install **libsodium**:
            ```bash
            vcpkg install libsodium
            ```
    4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Make sure **vcpkg** is correctly integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: After Dependencies are Met

Use the command line once the dependencies are correct:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).