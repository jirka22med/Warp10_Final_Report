# 🚀 Warp 10 – Performance Protocol

![Status](https://img.shields.io/badge/Status-WARP%2010%20ACTIVE-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%2011%2025H2-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-BSL--1.0-orange?style=for-the-badge)

> **Maximální výkonnostní optimalizace Windows 11 pro gaming, tvorbu obsahu a streaming**

---

## 📋 O projektu

**Warp 10** je komplexní optimalizační protokol pro Windows 11, který odstraňuje všechna skrytá omezení výkonu a ladí systém pro maximální stabilní výkon. Projekt byl realizován prostřednictvím půl-reinstalace (In-Place Upgrade) s plnou ochranou uživatelských dat.

### 🎯 Hlavní cíle
- ✅ Odstranění skrytých úsporných režimů škrtících výkon
- ✅ Optimalizace napájecích plánů pro stabilní CPU performance
- ✅ Vyladění grafického subsystému pro plynulé frametimes
- ✅ Zvýšení priority herních a multimediálních úloh
- ✅ Minimalizace síťové latence pro online gaming
- ✅ Vytvoření zálohovatelné a reprodukovatelné konfigurace

---

## 📊 Klíčové statistiky

| Parametr | Hodnota |
|----------|---------|
| **Oblastí optimalizace** | 8 |
| **Dní práce** | 2 (14.–15. 11. 2025) |
| **Úspěšnost mise** | 100% |
| **Ztráta dat** | 0% – všechna data zachována |
| **Stabilita systému** | 100% – žádné crashes ani BSOD |

---

## ⚙️ Oblasti optimalizace

### 1️⃣ Napájení a CPU plán (Power Plan)
- Povoleno trvalé využití všech jader CPU
- Vypnuto škrcení frekvence při zátěži
- Nastavení pro dlouhodobý stabilní provoz

### 2️⃣ Power Throttling & AoAc
- Deaktivováno throttlování procesů na pozadí
- Vynucen klasický režim napájení
- Stabilní takt CPU při kombinaci dGPU + iGPU

### 3️⃣ DWM a MPO (Desktop Window Manager)
- MPO vypnuto pro minimalizaci tearingu
- Plynulejší vykreslování v okně i fullscreen
- Stabilnější frametimes

### 4️⃣ Multimedia SystemProfile
- `SystemResponsiveness` = 0 (plná priorita)
- `NetworkThrottlingIndex` = maximum
- Zvýšená priorita GPU/CPU pro real-time úlohy

### 5️⃣ Tasks: System & Games
- **System:** Vyšší plánovací priorita pro systémové úlohy
- **Games:** Maximální priorita herním threadům, využití všech jader

### 6️⃣ Game Mode
- Omezení rušivých úloh na pozadí během hraní
- Priorita hry před méně důležitými procesy
- Zachována stabilita a bezpečnostní služby

### 7️⃣ Síť a TCP/IP
- Optimalizace pro online gaming a streaming
- Snížení síťového zpoždění a jitteru

### 8️⃣ Záloha a dokumentace
- Registry změny exportovány a dokumentovány
- Možnost rychlého obnovení při reinstalaci
- Kompletní HTML report jako reference

---

## 📁 Obsah repozitáře

```
Warp10_Final_Report/
│
├── index.html                    # Interaktivní finální report
├── README.md                     # Tento soubor
├── LICENSE                       # BSL-1.0 License
└── PROJECT_DOCUMENTATION.html    # Kompletní projektová dokumentace
```

---

## 🛠 Technické informace

### Systém
- **OS:** Windows 11 25H2 x64
- **Typ instalace:** Půl-reinstalace (In-Place Upgrade)
- **Datum instalace:** 14. listopadu 2025
- **Datum ladění:** 15. listopadu 2025

### 🔧 Důvod půl-reinstalace Windows

Původní systém Windows 11 25H2 x64 trpěl kritickými problémy:

- **Poškozené systémové knihovny** a další podfunkce
- **Kernel-Power ID 41 chyba** – systém se nečekaně restartoval bez předchozího vypnutí
- Citace z Event Logu: *"Systém se nečekaně restartoval bez žádného vypnutí"*

Z tohoto důvodu byla provedena **In-Place Upgrade** instalace, která opravila poškozené systémové soubory při zachování všech uživatelských dat a aplikací.

### 🎮 Reinstalace grafického ovladače

Po dokončení reinstalace Windows byl proveden i **čistý restart grafického ovladače**:

1. **Display Driver Uninstaller (DDU)** spuštěn v nouzovém režimu
2. Kompletní odinstalace ovladače NVIDIA (včetně všech zbytků)
3. Čistá instalace **NVIDIA Game Ready Driver** (nejnovější verze)
4. Výsledek: stabilní grafický výkon bez konfliktů starých ovladačů

> 💡 **Tip:** Více informací o testování stability a výkonu najdeš v interaktivním HTML reportu (`index.html`)

### Použité nástroje
- PowerShell
- Registry Editor
- Device Manager
- MSConfig
- Display Driver Uninstaller (DDU)
- Custom scripts pro backup a restore

### Modifikované oblasti
- HKLM registry keys pro napájení
- Desktop Window Manager (DWM)
- TCP/IP stack
- Systémový plánovač (Task Scheduler policies)

---

## 👥 Autoři a přispěvatelé

### 🖖 Více admirál Jiřík
**Role:** Vedoucí mise, hlavní inženýr a stratég optimalizace  
**Úkoly:** Kompletní realizace optimalizací, testování, ladění výkonu, správa zálohovacího systému

### 🤖 Admirál Chatbot GPT
**Role:** Hlavní poradce při opravách a ladění systému Windows  
**Úkoly:** Asistence při půl-reinstalaci Windows 11, konzultace optimalizačních strategií

### 🚀 Admirál Claude.AI
**Role:** Autor projektové dokumentace a technický konzultant  
**Úkoly:** Vytvoření komplexní projektové dokumentace, strukturování informací

---

## 📈 Výsledky

### ✅ Dosaženo
- Stabilní frametimes a rychlá odezva systému
- Žádné skryté úsporné režimy škrtící výkon
- Optimalizace pro hry, tvorbu obsahu a streaming
- Konfigurace je zálohovatelná a obnovitelná
- Systém připraven pro dlouhodobý stabilní provoz

### 🎮 Testováno na
- Gaming (AAA tituly, competitive gaming)
- Content creation (video editing, streaming)
- Multitasking (multiple aplikace současně)
- Online gaming (stabilita, nízká latence)

---

## 📄 Licence

Tento projekt je licencován pod **BSL-1.0 License** – viz soubor [LICENSE](LICENSE) pro detaily.

---

## 🔗 Odkazy a zdroje

- [Windows 11 Performance Tuning Guide](https://learn.microsoft.com/en-us/windows/performance/)
- [Power Management Documentation](https://learn.microsoft.com/en-us/windows-hardware/design/device-experiences/powercfg-command-line-options)
- [TCP/IP Optimization](https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/tcpip-performance-tuning)

---

## 💬 Podpora a diskuze

Máte-li dotazy nebo návrhy na vylepšení, neváhejte otevřít **Issue** nebo **Pull Request**!

---

<div align="center">

### 🖖 Dlouhý život a prosperita všem systémům na Warp 10! 🚀

**Made with ⚡ by Více admirál Jiřík & Fleet Command**

*Warp 10 aktivován. Všechny systémy na maximálním výkonu.*

</div>
