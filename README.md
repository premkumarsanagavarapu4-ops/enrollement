# 🚀 Setup Your Mac

Setup Your Mac is a macOS automation project that streamlines the post-enrollment setup process for managed Macs. It leverages **swiftDialog**, **SYM-Helper**, and **Jamf Pro** to provide users with an interactive setup experience while automating software installation, configuration, and validation.

---

## ✨ Features

- Interactive setup interface using **swiftDialog**
- Automated Mac provisioning after enrollment
- Supports **Jamf Pro Policy Custom Events**
- Built-in validation scripts for installed applications and services
- Modular architecture for easy customization
- Compatible with Apple's Automated Device Enrollment (ADE)

---

## 📂 Project Structure

```
Setup-Your-Mac/
│
├── Setup-Your-Mac-via-Dialog.bash      # Main setup script
├── Prompt-to-Setup-Your-Mac.bash       # Reminder script for users
├── Validations/                        # Validation scripts
├── AGENTS.md                           # AI agent instructions
├── CHANGELOG.md                        # Version history
├── CONTRIBUTING.md                     # Contribution guidelines
├── CONTRIBUTORS.md                     # Contributors
├── LICENSE                             # License information
└── README.md                           # Documentation
```

---

## 📋 Requirements

- macOS
- Jamf Pro
- swiftDialog
- SYM-Helper (recommended)
- Administrative privileges

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/setup-your-mac/Setup-Your-Mac.git
cd Setup-Your-Mac
```

### 2. Configure

Edit the required variables in:

```
Setup-Your-Mac-via-Dialog.bash
```

Configure your:

- Jamf Pro Policies
- Custom Events
- Branding
- Validation scripts
- Software installation workflow

### 3. Run

```bash
chmod +x Setup-Your-Mac-via-Dialog.bash
./Setup-Your-Mac-via-Dialog.bash
```

---

## 📁 Validation Scripts

The `Validations` folder contains scripts that verify whether required software or services are installed and functioning correctly.

Examples include:

- Cisco Umbrella
- CrowdStrike Falcon
- Printers
- BeyondTrust PAM
- Other organization-specific validations

---

## 🔧 Customization

You can customize:

- Company branding
- Logo and icons
- Setup workflow
- Installation order
- Validation logic
- User prompts
- Completion actions

---

## 🤝 Contributing

Contributions are welcome!

Please read:

- `CONTRIBUTING.md`
- `AGENTS.md`

before submitting pull requests.

---

## 📄 License

This project is distributed under the terms of the included **LICENSE** file.

---

## 🙏 Acknowledgements

Special thanks to all contributors and the macOS administration community for maintaining and improving **Setup Your Mac**.

---

## 📚 Documentation

For complete documentation, configuration guides, and release notes, refer to the project Wiki and documentation included with the repository.
