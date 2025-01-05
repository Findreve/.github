<h1 align="center">
  <br>
  <a href="https://find.yxqi.cn" alt="logo" ><img src="./Findreve.png" width="150"/></a>
  <br>
  Findreve
  <br>
</h1>
<h4 align="center">Track, Tag, and Retrieve – Simplifying Item Recovery.</h4>

<p align="center">
  <a href="https://www.yxqi.cn">Homepage</a> •
  <a href="https://find.yxqi.cn">Demo</a> •
  <a href="https://findreve.yxqi.cn">Documents</a> •
  <a href="https://github.com/Findreve/Findreve/releases">Download</a> •
  <a href="#License">License</a> •
  <a href="https://auth.yxqi.cn/product/5">Pricing</a>
</p>

## Introduction
Findreve is a powerful yet intuitive solution designed to help you manage your belongings
and ensure their safe return if lost. Each item is assigned a `unique ID` and generates a
`secure link`, easily embedded into a `QR code` or `NFC tag`. When scanned, the code directs
finders to a dedicated webpage displaying item details and your contact information, 
ensuring privacy and ease of communication. Whether you’re managing personal belongings
or professional assets, Findreve bridges the gap between lost and found with efficiency
and simplicity.

## Install
Findreve is a Python-based application. You need to have Python 3.8 or higher installed on
your server. Then, clone this repository to your server and install the required
dependencies:

- **NiceGUI**: `pip install nicegui==2.5.0` if Windows else `pip3 install nicegui==2.5.0`
- **aiosqlite**: `pip install aiosqlite` if Windows else `pip3 install aiosqlite`
- **QRCode**: `pip install QRCode` if Windows else `pip3 install QRCode`

## Launch
Run the following command to start Findreve:
> Python main.py

Upon launch, Findreve will create a SQLite database in the project's root directory and
display the administrator's account and password in the console.

## Stacks
- Nicegui

## License
Findreve is available in two versions:

Open Source Free Version: Licensed under the GPLv3.

Donation-Based Premium Version: By making a donation, you can access a version with
additional features and source code, which allows further development for personal or
internal use. However, redistribution of the modified or original source code is not
permitted.
