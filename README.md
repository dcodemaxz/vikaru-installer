
# <div align='center'>Vikaru-Installer</div>

<div align="center">

<img src="https://raw.githubusercontent.com/dcodemaxz/Vikaru-Bot/refs/heads/main/media/image.png" alt="Header Image" width="100%"/>

<br/>

<a href="https://chat.whatsapp.com/GlNdk54lm9V7C4U54SXnh1">
    <img src="https://img.shields.io/badge/WhatsApp-Comunity-25D366?logo=whatsapp&logoColor=white" alt="WhatsApp Comunity" />
</a>

<a href="https://github.com/dcodemaxz/Vikaru-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/dcodemaxz/Vikaru-Bot" alt="Stars"/>
</a>
<a href="https://github.com/dcodemaxz/Vikaru-Bot/network/members">
    <img src="https://img.shields.io/github/forks/dcodemaxz/Vikaru-Bot" alt="Forks"/>
</a>

</div>

---

## 🧭 About Vikaru-Installer

**Vikaru-Installer** is a simple, automated installer designed to help users easily manage, update, and run Node.js-based bots.  
It includes built-in dependency management, restart handling, and SSH key generation for secure updates and maintenance.

---

## ⚙️ Installation

### 1. Update your terminal environment (Ubuntu / Termux)

```bash
apt update && apt upgrade -y
```

### 2. Install required packages

```bash
apt install git bash -y
```

### 3. Clone the installer repository

```bash
git clone https://github.com/dcodemaxz/vikaru-installer.git vikaru
```

---

## 🚀 Getting Started

### 1. Enter the project directory

```bash
cd vikaru # or = vikaru-installer
```

### 2. Grant chmod permission

```bash
chmod +x start
```

### 3. Run the installer

```bash
./start # or = bash start
```

### 4. Generate SSH key (for verification and updates)

From the menu, select:

```
• [4] Create keys
```

Then copy the generated **public key** and send it to the [developer](https://wa.me/+6289508899033) for activation.

> ⚠️ Never share your **private key** (`id_ed25519`).

### 5. Install vikaru-md

From the menu, select:

```
• [2] Install Bot
```

---

## 💡 Features

<img src="https://raw.githubusercontent.com/dcodemaxz/Vikaru-Bot/refs/heads/main/media/start.png" alt="Feature Image" width="100%"/>

- **[1] Start Bot** → Runs the bot in loop mode. Automatically restarts after crashes or errors.  
- **[2] Install Bot** → Clones and installs the bot project from the GitHub repository.  
- **[3] Update Bot** → Pulls updates from the developer’s repository and applies them safely.  
- **[4] Create Keys** → Generates an SSH key pair for secure update authentication.  
- **[5] About** → Displays credits and system information.  

> The script ensures continuous operation and simplifies the bot management process for both VPS and Termux environments.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open a pull request or submit an issue to improve the project.

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).
