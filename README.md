# BIP39 Seed Phrase Offline Recovery Tool

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Security](https://img.shields.io/badge/Security-Offline_Tool-red.svg)

A secure offline tool to recover Bitcoin/BIP39 private keys from partial or mistyped seed phrases.

## Features

- 🔍 **Smart typo correction** for common seed phrase errors:
  - Adjacent character swaps (`wlalet` → `wallet`)
  - Missing/extra characters
  - Case sensitivity issues
  - Digit substitution patterns
  - Symbol omissions

- 🔐 **Multi-standard support**:
  - BIP39 (Mnemonic phrases)
  - BIP32/BIP44/BIP84 derivation paths
  - Optional passphrase support

- 📊 **Balance verification** (optional online mode):
  - Blockchain.com API integration
  - Multi-address checking
