# getgrass2

This repository contains the code for `getgrass2`, a bot designed to establish WebSocket connections through various HTTP and SOCKS proxies, specifically aimed at farming for Grass Airdrop Season 2.

## Overview

`getgrass2` connects to a specified WebSocket server using both HTTP and SOCKS proxies. It leverages the `ws` library for WebSocket communication and integrates the `https-proxy-agent` and `socks-proxy-agent` libraries for enhanced proxy support. This allows for more versatile and resilient connections, accommodating a wider range of proxy types.

## Installation

** for Terminal on Linux, follow these commands below before to Main Instalation:
   ```bash
   sudo apt install npm
   ```
   ```bash
   sudo apt install git
   ```
** Termux reposity, copy this command to your Termux on Android or IOS

   ```bash
   pkg install
   ```
   ```bash
   pkg install nodejs
   ```
   ```bash
   pkg update
   ```
   ```bash
   pkg upgrade
   ```
   ```bash
   pkg install git
   ```

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Madkalex/getgrass2.git
   ```

2. Navigate to the project directory:

   ```bash
   cd getgrass2
   ```

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

## Usage

1. Obtain your user ID from the Getgrass website:

   - Visit [https://app.getgrass.io/dashboard](https://app.getgrass.io/register/?referralCode=6ACtNYTict4Qugb).
   - Open your browser's developer tools (usually by pressing F12 or right-clicking and selecting "Inspect").
   - Go to the "Console" tab.
   - Paste the following command and press Enter:

     ```javascript
     localStorage.getItem('userId');
     ```

   - Copy the value returned, which is your user ID.

2. Create a file named `uid.txt` in the project directory and list your user IDs, each on a new line, like so:

   ```text
   123123213
   12313123
   ```

3. To specify proxies, create a file named `proxy.txt` in the project directory and add your desired proxy URLs, following the same new-line format, like this:

   ```text
   http://username:password@hostname:port
   socks5://username:password@hostname:port
   ```

4. To run the `getgrass-bot`, execute the following command in your terminal:

   ```bash
   npm start
   ```

## Donations

If you would like to support the development of this project, you can make a donation using the following addresses:

- **Solana**: `CKxw8CvyysexbD2GesZM4kLdVeWnc79vTPeeY25pcbLd`
- **EVM**: `0x0245BC50FE24d9d8F3c18d0CdE39BaD63E86026e`
- **BTC**: `bc1p947gruyx3d2wdyc0netehk5e708sd6ur7sfljucdtc6m6ew9v2fq9yqsjr`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contribution

If you find this project useful, please consider giving it a star on GitHub! Your support motivates further development and enhancements.
