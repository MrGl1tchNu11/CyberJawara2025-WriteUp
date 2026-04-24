# 🐺 CyberJawara 2025 Writeups - Mr.Gl1tchNu11's Digital Archives

<div align="center">

```
"The network is vast and infinite... just like the challenges in this CTF."
                                        - Silver Wolf
```

![Team Banner](https://img.shields.io/badge/Team-kata_rizqi_lengah_dikit_mau_di_ddos_platformnya_hati_hati_ya_panitia-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMCA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDQgOUwxMC45MSA4LjI2TDEyIDJaIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+Cjwvc3ZnPgo=)
![CTF](https://img.shields.io/badge/CTF-CyberJawara_2025-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

</div>

## 🎯 About This Repository

Welcome to MrGl1tchNu11's digital archives! This repository contains **complete writeups** for the **CyberJawara 2025/2026 Capture The Flag** competition, solved with Silver Wolf's signature hacking style from Honkai Star Rail.

Just like Silver Wolf who excels at infiltrating digital systems and cracking complex codes, these writeups will guide you through an epic journey in the cybersecurity world with a systematic and elegant approach.

### 👥 Team Members

- **[Yulius Wijaya](https://github.com/Carv3dSoul)**
- **[Muhamad Rizqi Wiransyah](https://github.com/MrGl1tchNu11)**
- **[Vincent Aurigo Osnard](https://github.com/yunx1aoo)**

---

## 🏆 Competition Overview

This repository is divided into two major phases:

### 📁 Qualification Round

### 📁 Finals Round

---

## 🌟 Qualification Round - Challenge Categories

### 🔍 **Forensics**

1. **Accidental** - Network Traffic & Image Analysis
   - Technique: PCAP analysis, TCP stream following, file extraction, binwalk
   - Flag: `CJ2025{1t_w4$_fUn_4uth0ring_CJ_4nd_f1n4lly_w3_wr4pp3d_th1$_up_gg!}`

### 🔐 **Cryptography**

1. **virtuoso** - Zero-Knowledge Proof Exploitation
   - Technique: Groth16 forgery, malleable verifying key attack, ZKP manipulation
   - Flag: `CJ{even_zer0_kn0wledge_pr00f_can_still_be_f00led_with_zer00000}`

### 🔧 **Reverse Engineering**

1. **Hermes** - React Native APK Analysis
   - Technique: Hermes bytecode decompilation, AES decryption, SHA-512 cracking
   - Flag: `CJ{hermEs_liNk_c0uld_fEEd_a_ViLLag3_in_Liber1A}`

2. **chanel** - Go Binary Constraint Solving
   - Technique: IDA decompilation, constraint extraction, Z3 solver automation
   - Flag: `CJ{she_want_chanel_GO_get_it___}`

### 💥 **PWN**

1. **Spushcode** - Shellcode Injection
   - Technique: Syscall shellcode, two-stage payload, filtered instruction bypass
   - Flag: `CJ2025{6ff0ccf9403824e463c179984ec9955664f215ed4d7da476897f4ac51312655d}`

2. **forgotten-flag** - Format String Vulnerability
   - Technique: Format string exploitation, BSS leak, memory dump
   - Flag: `CJ2025{110556da2fe3399b70415b6a714d0a129a2a4a22b5ee736188e52e121bf4bdb2}`

---

## 🏆 Finals Round - Challenge Categories

### 💥 **PWN**

1. **babu-format** 🩸 _(First Blood)_ - Format String Vulnerability + Buffer Overflow
   - Technique: `__printf_chk` bypass via `%p` chain leak, ret2libc, ROP chain, `shutdown("send")` EOF trigger
   - Flag: `CJ2025{ae930705f5c710dd698adff99055dfb3347f52965f15891a7fc92cb2512e749c}`

### 🔍 **Forensics**

1. **7sFetcher** - AWS CloudTrail & Web Log Investigation
   - Technique: SSRF via IMDSv1, AWS credential theft analysis, CloudTrail event reconstruction, 24-question forensic challenge
   - Flag: `CJ2025{i_cant_clear_xaleid_scopix_pls_help_ea25a5410b12}`

2. **S7** - Industrial Control System (ICS) PCAP Analysis
   - Technique: S7Comm protocol dissection, Job/Ack_Data pairing, byte-address reconstruction, scrambled base64 recovery via pyshark
   - Flag: `CJ2025{c6c2631ac08abbc38a590ba8ed68044a64f6bfa01f6e4b2a34e29d9dc5adac80}`

### 🔧 **Reverse Engineering**

1. **legacy-project** - Delphi PE32 Binary Analysis
   - Technique: IDA Pro decompilation, Delphi VMT traversal, custom modular arithmetic solver, reverse-engineered hash comparison
   - Flag: `CJ{D0_U_R3M3MB3R_ME2_C213CCA9D34CBF5B7B61}`

2. **Safe Extension** - WebAssembly (WASM) Cipher Reversal
   - Technique: WASM disassembly, ARX (Add-Rotate-XOR) cipher identification, 6-round decryption, v128 SIMD constant extraction
   - Flag: `CJ{b3_c4REful_0f_m4l1c10us_3x73ns10ns}`

---

## 🌌 Repository Structure

```
CyberJawara-2025/
├── Quals/
│   └── pdf/
│       └── PELAJAR_kata rizqi lengah dikit mau di ddos platformnya, hati hati ya panitia_Writeup.pdf
│
├── Finals/
│   └── pdf/
│       └── CJ2025-pelajar-KATA RIZQI LENGAH DI ya gitu la kira kira.pdf
│
└── README.md
```

---

## 📋 Complete Challenge Overview

### Qualification Round

| Category  | Challenge      | Difficulty | Technique                    | Status |
| --------- | -------------- | ---------- | ---------------------------- | ------ |
| Forensics | Accidental     | ⭐⭐       | PCAP & Image Extraction      | ✅     |
| Crypto    | virtuoso       | ⭐⭐⭐⭐⭐ | Zero-Knowledge Proof Attack  | ✅     |
| Reverse   | Hermes         | ⭐⭐⭐⭐   | Hermes Bytecode Analysis     | ✅     |
| Reverse   | chanel         | ⭐⭐⭐⭐⭐ | Go Binary Constraint Solving | ✅     |
| PWN       | Spushcode      | ⭐⭐⭐     | Shellcode Injection          | ✅     |
| PWN       | forgotten-flag | ⭐⭐⭐     | Format String Vulnerability  | ✅     |

### Finals Round

| Category  | Challenge      | Points | Difficulty | Technique                           | Status |
| --------- | -------------- | ------ | ---------- | ----------------------------------- | ------ |
| PWN       | babu-format 🩸 | 1000   | ⭐⭐⭐⭐   | Format String + ROP Chain           | ✅     |
| Forensics | 7sFetcher      | 371    | ⭐⭐⭐     | AWS SSRF & CloudTrail Analysis      | ✅     |
| Forensics | S7             | 321    | ⭐⭐⭐     | S7Comm PCAP & Base64 Reconstruction | ✅     |
| Reverse   | legacy-project | 593    | ⭐⭐⭐⭐   | Delphi PE32 Binary Reversing        | ✅     |
| Reverse   | Safe Extension | 371    | ⭐⭐⭐⭐   | WASM ARX Cipher Decryption          | ✅     |

---

<div align="center">

**"Every expert was once a beginner. Every pro was once an amateur."**

_Keep hacking, keep learning! 🐺⚡_

[![Star this repo](https://img.shields.io/github/stars/MrGl1tchNu11/CyberJawara2025-WriteUp?style=social)](https://github.com/MrGl1tchNu11/CyberJawara2025-WriteUp)
[![Fork this repo](https://img.shields.io/github/forks/MrGl1tchNu11/CyberJawara2025-WriteUp?style=social)](https://github.com/MrGl1tchNu11/CyberJawara2025-WriteUp)

_Made with 💜 by Mr.Gl1tchNu11_

</div>
