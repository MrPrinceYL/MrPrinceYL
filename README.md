<h1 align="center">Hi, I'm MrPrince 👋</h1>

<p align="center">
  Developer who likes to take things apart and rebuild them.<br>
  Reverse engineering &amp; static recompilation in <b>Rust</b> · security tools in <b>Python</b> · web prototypes
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Bevy-232326?style=flat&logo=bevy&logoColor=white" alt="Bevy">
  <img src="https://img.shields.io/badge/Ghidra-CC0000?style=flat&logoColor=white" alt="Ghidra">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
</p>

---

## 🎮 Reverse engineering & recompilation

Console games statically recompiled to native Rust: the original machine code is lifted with
Ghidra, turned into Rust, and runs on a console runtime written from scratch inside a Bevy app.
No game files are included; you bring your own disc.

| Project | What it is | Status |
|---|---|---|
| [**tekken5-recomp**](https://github.com/MrPrinceYL/tekken5-recomp) | Tekken 5 (PS2): Emotion Engine, IOP and VU code recompiled; PS2 runtime with GS rasterizer, SPU2, IPU | Playable, Arcade History WIP |
| [**tekken3-recomp**](https://github.com/MrPrinceYL/tekken3-recomp) | Tekken 3 (PS1): R3000A code and overlays recompiled; PS1 runtime with GPU, SPU, CD-ROM, GTE, MDEC, HLE BIOS | Playable |
| [**devilwithin-coop**](https://github.com/MrPrinceYL/devilwithin-coop) | Devil Within (Tekken 5's action mode) with local two-player co-op, split screen, mod menu | WIP |
| [**tekken5-t3-merge**](https://github.com/MrPrinceYL/tekken5-t3-merge) | Mod bringing Dr. B, Ogre, True Ogre, Gon and Gun Jack from Tekken 3 into Tekken 5 | WIP |

## 🛡️ Security tools

| Project | What it is |
|---|---|
| [**ai-phishing-detector**](https://github.com/MrPrinceYL/ai-phishing-detector) | Checks URLs and e-mails for phishing signs with readable heuristics and an optional Claude second opinion |
| [**ai-vulnerability-explainer**](https://github.com/MrPrinceYL/ai-vulnerability-explainer) | Explains vulnerabilities in code snippets in plain language (CWE, risk, fix), rules + optional Claude review |

## 🌐 Web

| Project | What it is |
|---|---|
| [**wholic-PoC**](https://github.com/MrPrinceYL/wholic-PoC) | Craftsman booking app prototype: e-mail code login, booking flow with transparent prices, VOB contract, invoice / SEPA / PayPal |

---

## 🔭 Currently working on

- Arcade History mode in the Tekken 5 recompilation
- Polishing co-op and split screen in Devil Within
