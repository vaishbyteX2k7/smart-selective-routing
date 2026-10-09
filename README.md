# 🚀 Smart Selective Routing

### Selective routing concept for smarter, domain-level network control.

[🌐 Live Demo](https://smart-selective-routing.higgsfield.app) · [📦 Source Code](https://github.com/vaishbyteX2k7/smart-selective-routing)

---

## 💡 Problem Statement

Traditional VPN usage often feels like an all-or-nothing choice. Users may want certain domains to use a secure tunnel while other traffic connects directly, with clear visibility into connectivity and response times.

**How might we make domain-level routing preferences easier to configure and understand?**

## 🎯 Our Solution

Smart Selective Routing is an interactive prototype that explores a user-friendly interface for choosing between **DIRECT** and **TUNNEL** policies for individual domains and viewing browser-based connectivity checks.

## ✨ Key Features

* 🌐 Domain-level DIRECT/TUNNEL rule interface
* 🔍 Browser-based public IP lookup
* ⚡ HTTPS reachability and request-duration checks
* 📊 Test A / Test B comparison examples
* 🟢 Connection status and activity indicators
* 📱 Responsive interface with animations

## 🧪 Example Test Observations

| Test        | Public IP observed | HTTPS probe duration |
| ----------- | ------------------ | -------------------: |
| Without VPN | `183.83.153.46`    |               551 ms |
| With VPN    | `219.100.37.233`   |              1250 ms |

*These values are example observations from one session, not a controlled benchmark. Actual IP addresses and timings may vary.*

## 🛠️ Technology

This project is an interactive web prototype. Refer to the source files for the specific frameworks and libraries used.

## ⚠️ Current Limitations

The current prototype demonstrates the interface and browser-based checks. Its domain rules do **not** independently configure operating-system routes or enforce per-domain VPN tunnelling. A routing service and VPN/tunnel-engine integration would be required for real selective routing.

## 🗺️ Future Improvements

* [ ] Integrate a local routing service
* [ ] Connect domain policies to a VPN/tunnel engine
* [ ] Add reliable domain-to-route mapping
* [ ] Implement route-leak and policy-enforcement tests
* [ ] Add automated testing and documentation

## 🚀 Run Locally

1. Download or clone this repository.
2. Extract the source ZIP if you downloaded it.
3. Follow the setup instructions for the framework and package manager identified in the source files.
4. Start the development server using the project's configured command.

## 👩‍💻 Project

**Smart Selective Routing** — an interactive prototype exploring more transparent, domain-level routing preferences.

Built as a project prototype for experimentation and future development.
