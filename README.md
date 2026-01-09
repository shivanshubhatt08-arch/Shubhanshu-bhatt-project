
# 🔢 PIN Code Lock Cracker Assistant  
### Educational Security Simulator (Python)

## 📌 Overview

The **PIN Code Lock Cracker Assistant** is an educational Python project designed to demonstrate how **numeric PIN-based security systems** (such as ATM PINs, phone locks, and digital door locks) can become vulnerable when weak security practices are used.

This project focuses **only on numeric PINs (0–9)** and simulates common attack techniques in a **controlled, ethical, and educational environment**. The goal is not hacking, but **understanding security weaknesses and learning how to defend against them**.

---

## 🎯 Project Objectives

- Understand how numeric PIN systems work
- Demonstrate why short PINs are insecure
- Simulate brute-force attacks on dummy PINs
- Learn secure PIN storage using hashing
- Understand defensive mechanisms like rate limiting and lockouts
- Build security-aware thinking as a developer

---

## 🧠 Why PIN-Based Security?

Many real-world systems still rely on:
- 4-digit PINs
- No attempt limits
- No delay or lockout mechanisms

This project shows **how fast such systems can fail** and **how proper security design prevents attacks**.

---

## 🛠️ Features

### 1️⃣ PIN Strength Analyzer
Analyzes a numeric PIN based on:
- PIN length (4-digit vs 6-digit)
- Repeated digits (e.g. `1111`)
- Sequential patterns (e.g. `1234`, `9876`)
- Low entropy combinations

**Output Example:**