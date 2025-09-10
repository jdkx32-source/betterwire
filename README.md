<p align="center">
    <img src="https://github.com/jdkx32-source/betterwire/blob/main/bw_logo_3.png?raw=true" alt="BetterWire Visual" width="700"/>
</p>

<p align="center">
  <strong>Your Services, Your Rules. Globally Accessible.</strong>
</p>

<p align="center">
  <a href="#-key-features">Features</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="https://betterwire.netlify.app/documentation"><strong>Full Documentation »</strong></a>
</p>

## 🚀 What is BetterWire?

BetterWire is a simple, high-performance, and secure tunneling system written in **Go**. It punches a secure hole through complex networks to expose your local services (like game servers, web servers, or development environments) to the internet without needing complex port forwarding on your router.

The entire project is managed through a clean **web dashboard**, making it easy to add or remove port rules on the fly.

## 🤔 Why Was BetterWire Created?

BetterWire was born out of the need for a more stable and flexible tunneling solution. For a long time, I used services like `playit.gg`, which, while great for their simple setup, often came with persistent **ping problems** that impacted the experience.

Most importantly, I was missing a solution that I could **host myself** to have full control over latency and performance. BetterWire was created to fill exactly this gap: it offers the simplicity of well-known services but with the power and sovereignty of a self-hosted solution.


<br>

> ### ➡️ Visit the Official Website!
> For a full feature overview, downloads, and live demos, check out our website:
> **[https://betterwire.netlify.app/](https://betterwire.netlify.app/)**

<br>

## ✨ Key Features

- **💻 Full Web Dashboard:** Manage all clients and port forwardings in real-time.
- **🛡️ Secure:** All communication between client and server is encrypted.
- **⚡ Blazing Fast:** Built with Go for minimal latency and high performance.
- **🔄 TCP & UDP Support:** Forward any kind of traffic, from websites to game servers.
- **🧩 Simple Setup:** Get up and running in minutes with easy-to-understand `yml` configuration files.
- **🌐 Cross-Platform:** Run the server and client on Linux or Windows. Mix and match as you need!

---

## 🔧 How It Works

The concept is simple. The BetterWire client on your local machine establishes a secure, persistent control connection to your public BetterWire server. When a user connects to a public port on your server, the server tells your client to open a direct data tunnel to forward the traffic.

**User** `—🌐—>` **BetterWire Server** `—🔒—>` **BetterWire Client** `—🏠—>` **Your Local Service**

---

## 🏁 Quick Start

Getting started is easy. For detailed instructions, please read the **[Full Documentation](https://betterwire.netlify.app/documentation)**.

### 1. Server Setup (on a VPS)
- Download the latest release for your OS.
- Place the `server` executable and `index.html` in the same directory.
- Configure `server_config.yml` with your desired ports and secrets.
- Run the server (we recommend using `screen` on Linux).

### 2. Client Setup (at home)
- Download the latest release for your OS.
- Configure `client_config.yml` with your server's IP and the same secret.
- Add the local ports you want to expose (e.g., `tcp:25565`).
- Run the client.

**That's it! Your service is now live via your server's IP.**

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, bug fixes, or improvements, feel free to open an issue or submit a pull request.
