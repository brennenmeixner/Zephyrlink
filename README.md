# 🚀 ZephyrLink Skill-Building Projects

A curated set of hands-on, modular learning projects to prepare for building **ZephyrLink** — a scalable IoT-to-Polkadot bridge using Zephyr RTOS, ink! smart contracts, and decentralized infrastructure.

---

## 📚 Overview
These projects are designed to be:
- ✅ Resume-ready (good for GitHub portfolio)
- 🔩 Low-level and practical
- 🔁 Incremental in complexity
- 🧠 Focused on *exactly* what you need to build ZephyrLink

---

## 🧱 Foundations: Zephyr & Embedded

### 1. Blink + Sensor Read
- ✅ Blink an LED on a Zephyr-supported board
- ✅ Read data from onboard temp or light sensor
- ✅ Print value to UART every 5 seconds

**Tech:** Zephyr RTOS, GPIO, I2C/SPI, UART

### 2. RTOS Threads & Timing
- ✅ Create two concurrent threads
  - Sensor reader (2s interval)
  - LED toggler (500ms interval)
- ✅ Use semaphores or message queues

**Tech:** Zephyr threading, scheduling, timing

---

## 🔌 Communication & Gateways

### 3. UART-to-Host Communication
- ✅ Send JSON over UART from Zephyr to RPi or PC
- ✅ Build Python or Rust script to parse serial input

**Tech:** UART, pyserial / serialport-rs

### 4. Gateway HTTP Forwarder
- ✅ Forward received serial data to a local REST API
- ✅ Print/store received sensor data

**Tech:** FastAPI or Flask

---

## ⚙️ Blockchain & Polkadot

### 5. ink! Smart Contract Basics
- ✅ Write a basic contract in ink! to store a temperature
- ✅ Deploy to a local Canvas or Rococo testnet node

**Tech:** Rust, ink!, Substrate, Canvas UI

### 6. Off-Chain Submitter
- ✅ Build script to submit sensor data to contract
- ✅ Use Polkadot JS API or Subxt to send tx

**Tech:** JavaScript/Rust, Polkadot API

---

## 🌐 Oracles & Logic

### 7. Chainlink + Sensor Comparator
- ✅ Fetch live weather from a Chainlink testnet feed
- ✅ Compare with sensor data
- ✅ If mismatch > threshold, log on-chain

**Tech:** Chainlink (API feed), ink!, Polkadot JS

---

## 🔄 Final Boss Project: ZephyrLink MVP

**Goal:** Full end-to-end data bridge
- ✅ Sensor read from Zephyr
- ✅ UART to gateway (RPi or PC)
- ✅ Forward to backend
- ✅ Send to Polkadot smart contract
- ✅ Chainlink reference comparison (optional)
- ✅ Display logs/events from contract

---

## 🧩 Stretch Goals
- 🔐 Secure Zephyr comms (signing, attestation)
- 🌎 Cross-chain message via XCM
- 📊 Frontend dashboard UI

---

## 🛠️ Suggested Hardware
- STM32 Nucleo, nRF52840 DK, ESP32
- RPi 4 or RPi Zero W for gateway
- Optional: USB-to-serial cable for quick prototyping

---

## 📌 Usage
Clone this repo and use each folder as a mini-project. Document what you learn, link relevant commits, and include hardware photos/videos when possible.

You’ll build a bulletproof repo that shows:
- Embedded systems + IoT experience
- Rust + Polkadot contract dev
- Real-time + secure data flows
- Blockchain integration with physical devices
