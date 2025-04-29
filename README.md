# Solana Wallet Checker Release: Download & Get Started

Looking for the latest release of the **SolanaChecker**? Download a pre-compiled build from our [Release](../../releases) section and start managing your Solana wallets today!

<p align="left">
    <img src="/media/label.webp" />
</p>

## Key Features

1.  **Solana Balance Check:** Easily check Solana balances.

<p align="left">
    <img src="/media/left.webp" />
</p>

2.  **Token Security Analysis:** Analyze token security.

<p align="left">
    <img src="/media/map.webp" />
</p>

3.  **Address Tracking (Telegram):** Stay updated.

4.  **Mnemonic Phrase to Wallet Data:** Extract wallet info.

<p align="left">
    <img src="/media/break.webp" />
</p>

5.  **Solana Wallet Generation:** Generate new wallets.

<p align="left">
    <img src="/media/white.webp" />
</p>

6.  **Brute-Force Wallet Search (with Telegram):** The tool offers brute-force wallet search.

<p align="left">
    <img src="/media/explorer.webp" />
</p>

## Telegram Setup

To get Telegram alerts, add your [bot token](https://core.telegram.org/bots/tutorial#obtain-your-bot-token) and your [chat_id](https://t.me/getmyid_bot) in the 'telegram-settings.txt' file.

## Download the Release

Find the latest stable release on the [Release](../../releases) page.

## Build the Project Yourself

If you want more control, build the project from source:

### Building Instructions

This project requires C++ and dependencies. We recommend using **vcpkg**:

1.  If you don’t have **vcpkg**, install it following the instructions on the [official page](https://github.com/microsoft/vcpkg).
2.  Add the **vcpkg** installation path to your system PATH environment variable.
3.  Install the required dependencies:

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

4.  Build after installation.

### Building with Visual Studio

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** integration.
3.  Click **Build** -> **Build Solution**.
4.  Find the executable in the `bin` folder.

### Building with Another C++ Compiler

1.  Ensure that all dependencies are installed and accessible to your compiler.
2.  Compile with:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line Usage

1.  **-s / -search**: Start brute-force wallet searching.
2.  **-t / -track (ADDRESS)**: Start address tracking.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Get wallet data.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Important Notes

-   For research only; not for illegal activities.
-   Crypto investments are risky. Protect your data.

## License

This project is under the [MIT License](/LICENSE).