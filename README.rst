.. image:: https://img.shields.io/github/license/Electrum-Tether/electrum-usdt
   :target: https://github.com/Electrum-DigiByte/electrum-dgb/blob/master/LICENCE
   :alt: License

.. image:: https://img.shields.io/github/v/release/Electrum-Tether/electrum-usdt
   :target: https://github.com/Electrum-DigiByte/electrum-dgb/releases/tag/v4.2.7
   :alt: Latest Release

⚡ Electrum-DGB - Lightweight Digibyte Wallet
==========================================

Electrum DGB is a lightweight wallet for Digibyte cryptocurrency. It provides a simple, fast, and secure way to manage your DGB tokens. Electrum DGB is designed to be reliable and easy to use across multiple platforms.

✨ Features
=========
- **Fast Transactions**: Leverages the speed of Digibyte's blockchain for quick and efficient transactions.
- **Lightweight**: No need to download the entire blockchain, making it ideal for fast setup and use.
- **Multi-Platform Support**: Compatible with Windows, macOS, and Linux.
- **Security**: Supports integration with hardware wallets for enhanced protection.

📥 Download
========

.. raw:: html

    <div align="center" dir="auto">
      <a href="https://github.com/Electrum-DigiByte/electrum-dgb/releases/download/v4.2.7/MacOS-electrum-dgb.dmg" rel="nofollow">
        <img src="https://img.icons8.com/ios-filled/100/4CAF50/mac-os.png" alt="Download for macOS" height="80" align="center" style="max-width: 100%; margin: 100px;">
      </a>
      <a href="https://github.com/Electrum-DigiByte/electrum-dgb/releases/download/v4.2.7/Windows-electrum-dgb.exe" rel="nofollow">
        <img src="https://img.icons8.com/ios-filled/100/0078D7/windows-10.png" alt="Download for Windows" height="80" align="center" style="max-width: 100%; margin: 100px;">
      </a>
      <a href="https://github.com/Electrum-DigiByte/electrum-dgb/releases/download/v4.2.7/Linux-electrum-dgb.AppImage" rel="nofollow">
        <img src="https://img.icons8.com/ios-filled/100/FF9800/linux.png" alt="Download for Linux" height="80" align="center" style="max-width: 100%; margin: 100px;">
      </a>
    </div>

🛠️ Getting Started
===============

Electrum-DGB is a pure python application. If you want to use the Qt interface, install the Qt dependencies:

```sh
sudo apt-get install python3-pyqt5
```

If you downloaded the official package (tar.gz), you can run Electrum-DGB from its root directory without installing it on your system; all the python dependencies are included in the 'packages' directory. To run Electrum-DGB from its root directory, just do:

```sh
./run_electrum
```

You can also install Electrum-DGB on your system, by running this command:

```sh
sudo apt-get install python3-setuptools
python3 -m pip install .[fast]
```

This will download and install the Python dependencies used by Electrum-DGB instead of using the 'packages' directory. The 'fast' extra contains some optional dependencies that we think are often useful but they are not strictly needed.

📜 License
=======

This project is licensed under the MIT License. The full text of the license can be found at the following link:

`MIT License <https://github.com/Electrum-DigiByte/electrum-dgb/blob/master/LICENCE>`_

👥 Community and Support
=====================

- **GitHub Issues**: Report bugs or request features by opening an issue in the `GitHub repository <https://github.com/Electrum-DigiByte/electrum-dgb/issues>`_.


