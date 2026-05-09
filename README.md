<div align="center">
  <!-- Buraya ileride AuraLabs logosunun linkini ekleyeceğiz -->
  <img src="https://via.placeholder.com/120x120/0a0a0b/6366f1?text=A" alt="AuraLabs Logo" width="100"/>

  # AuraLabs EnvCipher 🛡️
  
  **The Local-First, Military-Grade Environment Variable Vault for Professionals.**

  [![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg?style=for-the-badge&color=6366f1)]()
  [![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg?style=for-the-badge&color=27272a)]()
  [![Encryption](https://img.shields.io/badge/Encryption-AES--256-green.svg?style=for-the-badge&color=10b981)]()
  [![Price](https://img.shields.io/badge/License-Free-success.svg?style=for-the-badge&color=10b981)]()

</div>

---

## ⚡ What is EnvCipher?
Tired of managing sensitive API keys, database credentials, and tracking bot tokens in easily compromised `.env` files? 

Developed by **AuraLabs PC**, EnvCipher is a lightweight, strictly offline desktop application that encrypts your sensitive variables using **AES-256 military-grade encryption**. It acts as a central, isolated command center for all your automation bots, SaaS projects, and local servers.

## 🔥 Key Features

*   **🔒 Local-First Security:** No cloud sync, no accounts, no subscriptions. Your data never leaves your computer. Everything is stored in a locally encrypted SQLite database.
*   **💼 Workspace Isolation:** Create infinite workspaces (e.g., *Amazon Bot*, *Global Vault*, *Local API*) to keep your projects completely separated.
*   **📋 1-Click Copy:** Reveal and copy variables instantly as RAW, JavaScript (`process.env.KEY`), or Python (`os.getenv("KEY")`) formats.
*   **🏷️ Environment Tagging:** Tag keys strictly as `PROD`, `STAGE`, or `DEV` to prevent deployment disasters.
*   **📦 Bulk Export/Import:** Seamlessly export your selected keys into a perfectly formatted `.env` file for your production servers.

## 🚀 Installation (Windows)

EnvCipher is completely free to use.

1. Go to the [Releases](../../releases) page.
2. Download the latest `EnvCipher_Setup.exe` file.
3. Install and run the application.
4. Set your **Master Password** (Do not lose this, there is no cloud recovery!).
5. Start building securely.

## 🛡️ Security Architecture
EnvCipher relies on a strictly offline architecture. The Master Password you set on the first run is hashed via **SHA-256**. Your actual keys and values are encrypted and decrypted entirely in-memory using **AES-256** standard. If the `.db` file is ever stolen, it is mathematically unreadable without your Master Password.

---

<div align="center">
  
**Built with precision by [AuraLabs PC](https://github.com/AuraLabs-PC)**  
*Hardware Integration & B2B Software Solutions based in Turkey.*

</div>
