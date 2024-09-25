# Mifare 1K Magic UID Reset (Magic Cards Only)

## Overview
**Mifare 1k Magic UID Reset** is a tool that allows setting of **UID on special versions (magic cards)** of Mifare 1K.
Those are also called **Gen1 UID Re-Writable**.
It will also recover damaged cards that have had **invalid data written to block 0** (e.g. wrong BCC). Currently **only 4 Byte UID** is supported.

## How to Run It

1. You need to have **ACR122U** and a **Mifare 1K Magic Card on it**.
2. Download the **[Mifare-1K-Magic-UID-Reset](https://github.com/skylandersNFC/Mifare-1K-Magic-UID-Reset/releases/)** zip archive and **extract it**.
3. Run "**Mifare-1k-Magic-UID-Reset.exe**"
4. Your **magic card** was just factory formated with UID "**00000000**"
5. If you want **different UID**, open "**Reset.bat**" and change it.

## How to Run It Manually from CMD

1. Open **CMD** where the **nfc-mfsetuid.exe** file is.
2. Use this command **`nfc-mfsetuid 00000000 -f`**
3. For **different UID**, replace **`00000000`** with whatever you want.

## Screenshot

![Mifare 1k Magic UID Reset](https://raw.githubusercontent.com/skylandersNFC/Mifare-1k-Magic-UID-Reset/main/images/Reset_Screenshot.jpg)
