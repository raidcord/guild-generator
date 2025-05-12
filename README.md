[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br />
<div align="center">
  <a href="https://github.com/raidcord/guild-generator"> 
    <img src="images/image.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">RAID CORD guild-tag server generator</h3>

  <p align="center">
     Generates multiple Discord guild-servers instantly and checks them concurrently for specific features using a Terminal User Interface (TUI).
    <br />
    <a href="https://github.com/raidcord/guild-generator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/raidcord/guild-generator">View Demo</a>
    ·
    <a href="https://github.com/raidcord/guild-generator/issues">Report Bug</a>
    ·
    <a href="https://github.com/raidcord/guild-generator/issues">Request Feature</a> 
  </p>
</div>

# RAID CORD Guild Generator

Efficiently create and analyze Discord guilds with RAID CORD, featuring a command-line interface for easy operation.

![TUI in Action](images/example.gif)

## Installation Instructions

### Auto Installation and Setup (Easier)

1.  Download the repository or clone using:
    ```sh
    git clone https://github.com/raidcord/guild-generator.git 
    ```
2.  Ensure you have [Node.js](https://nodejs.org/) (version 18+ recommended) installed.
3.  Run the `setup.bat` file (for Windows).
    *   This will install all necessary project dependencies using npm.
    *(Note: For non-Windows users, simply run `npm install` in the terminal after cloning.)*

*You don't have to edit any files initially; the script will ask you for required inputs (like Token and Webhook URL) when you run it.*

### Manual Configuration

1.  Open your terminal.
2.  Clone the repository:
    ```sh
    git clone https://github.com/raidcord/guild-generator.git 
    ```
    *or download the ZIP and extract it.*
3.  Navigate to the project directory:
    ```sh
    cd guild-generator 
    ```
4.  Install dependencies:
    ```sh
    npm install
    ```
5.  Run the script:
    ```sh
    node index.js
    ```

## System Requirements

Ensure your system meets these prerequisites:

1.  [Node.js](https://nodejs.org/) 16+ (the latest LTS version is recommended).
2.  Git installed on your device (for cloning).
3.  Windows, macOS, or Linux.
4.  A curious mind (and an understanding of the risks involved).

## 🚨 IMPORTANT WARNING 🚨

**This tool is provided for educational and experimental purposes only. The developers are not responsible for any negative consequences, including account bans, that may arise from its use. USE AT YOUR OWN EXTREME RISK.**

## Specifications

1.  **Concurrent Guild Generation:** Creates multiple Discord guilds rapidly.
2.  **Feature Checking:** Automatically checks newly created guilds for specific features 
3.  **Webhook Notifications:** Sends alerts to a Discord webhook when guilds with desired features are found.
4.  **Interactive TUI:** User-friendly terminal interface for easy operation and input.
5.  **Configuration at Runtime:** Prompts for necessary inputs like Discord token and webhook URL.
6.  IMPORTANT -> This script bypasses new discord patches and it is currently working in 09/05/2025

> **Note:** As of May 12th, 2025, RAID CORD guild-tag server generator is functional based on current Discord API interactions. APIs can change, and patches may become necessary. This project demonstrates interactions with the Discord API via a self-bot, which is inherently risky. Remember, sharing knowledge benefits everyone; please provide credit if you find our work valuable or adapt it.


[contributors-shield]: https://img.shields.io/github/contributors/raidcord/guild-generator.svg?style=for-the-badge
[contributors-url]: https://github.com/raidcord/guild-generator/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/raidcord/guild-generator.svg?style=for-the-badge
[forks-url]: https://github.com/raidcord/guild-generator/network/members
[stars-shield]: https://img.shields.io/github/stars/raidcord/guild-generator.svg?style=for-the-badge
[stars-url]: https://github.com/raidcord/guild-generator/stargazers
[issues-shield]: https://img.shields.io/github/issues/raidcord/guild-generator.svg?style=for-the-badge
[issues-url]: https://github.com/raidcord/guild-generator/issues
