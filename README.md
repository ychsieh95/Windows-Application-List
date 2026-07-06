# Windows-Application-List

A curated list of recommended applications for Windows.

---

## Overview

A structured summary of recommended utilities for Windows 10 and 11, cataloged by functional environments:

* **Category 1: System, Customization & Package Management**
    * [ExplorerPatcher](#1-explorerpatcher) — Classic Windows UI and taskbar restoration.
    * [Glow](#2-glow) — Advanced system analysis and hardware diagnostics.
    * [Microsoft PC Manager](#3-microsoft-pc-manager) — Official lightweight system optimization and maintenance tool.
    * [NetSpeedTray](#4-netspeedtray) — Lightweight real-time network and hardware monitoring in the taskbar.
    * [UniGetUI](#5-unigetui) — Intuitive package manager graphical user interface.
* **Category 2: Terminal Emulators & Remote Management**
    * [Cmder](#6-cmder) — Portable console emulator wrapper with enhanced shell features.
    * [MobaXterm](#7-mobaxterm) — All-in-one workstation for remote computing and network infrastructure management.
    * [RustDesk](#8-rustdesk) — Secure, open-source, and self-hosted remote desktop alternative.
* **Category 3: Shells & Environment Customization**
    * [Git for Windows / Git Bash](#9-git-for-windows--git-bash) — Light POSIX-compliant environment and version control utilities.
    * [Oh My Posh](#10-oh-my-posh) — Agnostic and highly customizable prompt theme engine for any shell.

---

## Category 1: System, Customization & Package Management
Utilities designed to monitor hardware, optimize performance, tweak the Windows interface, or streamline software installations.

### 1. [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher)

#### 🇺🇸 English (en-us)
**ExplorerPatcher** is an open-source utility designed to enhance working environments on Windows 11 by bringing back classic, highly functional UI behaviors from Windows 10. It interacts deeply with the Windows Explorer shell to restore familiar workflows that were removed in newer OS iterations.

* **Key Features:**
    * **Classic Taskbar Restoration:** Choose between the native Windows 11 taskbar or the classic Windows 10 style, allowing for custom positioning (top, left, or right sides of the screen).
    * **Start Menu Customization:** Enables users to bring back the Windows 10 tile layout or open the standard Windows 11 Start Menu directly to the "All Apps" list.
    * **Context Menu Modding:** Replaces the padded Windows 11 context menu with the classic, snappier Windows 10/7 right-click menus without altering registry keys manually.
    * **System Tray Improvements:** Restores legacy system icons and functionality, such as the classic network flyout and the separate Windows 10 volume/battery dialogs.

#### 🇹🇼 繁體中文 (zh-tw)
**ExplorerPatcher** 是一款旨在優化 Windows 11 工作環境的開源工具，能將許多經典且實用的 Windows 10 使用者介面（UI）行為帶回新系統。它透過與 Windows 檔案總管外殼（Shell）深度互動，還原了許多被新系統拔除的滑鼠與鍵盤工作流程。

* **核心功能特色：**
    * **經典工作列還原：** 可自由選擇要使用 Windows 11 原生樣式或是 Windows 10 經典工作列，並支援將工作列移至螢幕上方、left側或右側。
    * **開始功能表自訂：** 允許使用者找回 Windows 10 的動態磚版面，或者將 Windows 11 的開始功能表預設設定為直接開啟「所有應用程式」清單。
    * **右鍵選單修改：** 將 Windows 11 繁複的右鍵快顯功能表，替換回經典、反應更迅速的 Windows 10/7 傳統樣式，無需手動修改登錄檔。
    * **系統匣外觀改善：** 還原舊版的系統圖示與彈出視窗功能，例如經典的網路連接面板，以及獨立的 Windows 10 音量與電池調整介面。

---

### 2. [Glow](https://github.com/turkaysoft/glow)

#### 🇺🇸 English (en-us)
**Glow** is a modern, open-source system analysis tool designed to provide deep insights into Windows hardware and software configurations. Acting as a contemporary alternative to classic diagnostics tools, it collects comprehensive telemetry across your motherboard, processor, memory, operating system, and connected peripherals within a clean, intuitive interface.

* **Key Features:**
    * **Deep Hardware Diagnostics:** Reveals granular details about CPU architectures, RAM timings, storage health (S.M.A.R.T. attributes), and motherboard specifications.
    * **Software & OS Telemetry:** Analyzes active Windows features, installed drivers, running services, network properties, and environment variables.
    * **Exportable System Reports:** Generates structured HTML, TXT, or JSON summary reports for effortless system auditing or troubleshooting documentation.
    * **Native & Portable Architecture:** Operates with native execution and zero installation overhead, making it an ideal utility for IT professionals deployment via USB.

#### 🇹🇼 繁體中文 (zh-tw)
**Glow** 是一款現代化的開源系統分析工具，旨在提供深入的 Windows 硬體與軟體組態資訊。作為傳統診斷工具的當代替代方案，它能在簡潔直觀的介面中，全面收集主機板、處理器、記憶體、作業系統及連接週邊的詳細遙測數據。

* **核心功能特色：**
    * **深度硬體診斷：** 顯示 CPU 架構、RAM 時序、儲存裝置健康度（S.M.A.R.T. 屬性）以及主機板規格等細緻的系統核心資訊。
    * **軟體與系統遙測：** 分析當前 Windows 功能狀態、已安裝的驅動程式、運作中的服務、網路屬性以及環境變數。
    * **可匯出之系統報告：** 支援產生結構化的 HTML、TXT 或 JSON 摘要報告，讓系統稽核或故障排除的文件記錄變得非常輕鬆。
    * **原生免安裝架構：** 採原生執行且完全免安裝，極低資源佔用，非常適合 IT 專業人員裝入隨身碟中隨身攜帶部署。

---

### 3. [Microsoft PC Manager](https://pcmanager.microsoft.com/)

#### 🇺🇸 English (en-us)
**Microsoft PC Manager** is an official, lightweight desktop utility developed by Microsoft to optimize system performance and maintain computer health. It brings together native Windows maintenance features into a single, streamlined interface to simplify basic optimization.

* **Key Features:**
    * **One-Click Boost:** Instantly clears temporary storage files and reclaims system memory (RAM) to speed up sluggish execution.
    * **Storage Management:** Deeply cleans log files, manages large files scattered across your drives, and controls storage sense setups.
    * **Startup App Control:** Disables resource-heavy startup applications to decrease boot times and optimize background operations.
    * **Health Checkup:** Scans for potential system anomalies, customizes malware detection settings, and detects residual junk files safely.

#### 🇹🇼 繁體中文 (zh-tw)
**Microsoft PC Manager**（微軟電腦管家）是一款由微軟官方開發的輕量級桌面工具，旨在優化系統效能並維護電腦健康。它將 Windows 原生的多項維護功能整合到單一且流暢的介面中，簡化了電腦的基礎優化流程。

* **核心功能特色：**
    * **一鍵加速（Boost）：** 瞬間清理系統暫存檔案並釋放記憶體（RAM）空間，快速改善電腦卡頓.
    * **儲存空間管理：** 深度清理日誌與暫存檔、快速篩選硬碟中的大檔案，並能直接配置儲存空間感知器。
    * **開機啟動項控制：** 輕鬆停用高資源佔用的開機自啟動軟體，大幅縮短開機時間並優化背景運作。
    * **系統健康檢查：** 快速掃描潛在的系統異常、管理安全防護設定，並安全地清除垃圾檔案。

---

### 4. [NetSpeedTray](https://github.com/mullsoft/NetSpeedTray)

#### 🇺🇸 English (en-us)
**NetSpeedTray** is a lightweight, open-source system utility for Windows 10 and 11 that displays live upload and download speeds directly on your taskbar. It blends seamlessly with the native Windows UI while operating with minimal CPU and RAM usage to maximize battery life.

* **Key Features:**
    * **Real-Time Network Monitoring:** Shows precise, sub-second bandwidth speeds right in your line of sight.
    * **Hardware Telemetry:** Tracks CPU/GPU utilization, temperatures, power consumption (Watts), RAM, and VRAM alongside network speeds.
    * **High Customization:** Offers visual color-coding based on speed thresholds, custom fonts, arrow styles, and an optional mini-graph overlay.
    * **Per-App Traffic Breakdown:** Includes a dedicated dashboard to view bandwidth usage on a per-process basis and set monthly data usage caps.

#### 🇹🇼 繁體中文 (zh-tw)
**NetSpeedTray** 是一款專為 Windows 10 和 11 設計的輕量級開源系統工具，能在工作列上直接顯示即時的網路「上傳」與「下載」速度。它的設計完美融入 Windows 原生介面，且記憶體與 CPU 佔用極低，完全不影響電池續航力。

* **核心功能特色：**
    * **即時網速監控：** 在工作列角落以毫秒級的速度更新當前的網路頻寬，讓你一眼掌握網路狀況。
    * **硬體狀態監控：** 除了網速外，還能同步顯示 CPU/GPU 使用率、溫度、功耗（瓦數）以及 RAM / VRAM 的佔用情況。
    * **高度自訂化：** 支援依據網速高低自動變換顏色（觸發門檻可自訂），並可自行調整字型、箭頭樣式或開啟微型歷史走勢圖。
    * **單一應用程式流量分析：** 內建詳細的管理面板，可查看是哪一個軟體程式在佔用網路頻寬，並支援設定每月網路流量上限警告。

---

### 5. [UniGetUI](https://github.com/marticliment/UniGetUI)

#### 🇺🇸 English (en-us)
**UniGetUI** (formerly WingetUI) is an intuitive, open-source Graphical User Interface (GUI) designed to manage command-line package managers on Windows 10 and 11. Instead of typing complex terminal commands, UniGetUI provides a unified dashboard to seamlessly discover, install, update, and uninstall software.

* **Supported Package Managers:** WinGet, Scoop, Chocolatey, Pip, NPM, Bun, .NET Tool, PowerShell Gallery, and Cargo.
* **Key Features:**
    * **One-Click Batch Operations:** Easily bulk-install or update multiple applications at once.
    * **Backup & Restore:** Export custom software lists to effortlessly replicate your setup on a new PC.
    * **Automated Notifications:** Runs quietly in the system tray to alert you when software updates are available, with options to skip specific versions.
    * **Custom Installation Switches:** Force 32-bit architecture, choose older versions, or customize install directories directly from the UI.

#### 🇹🇼 繁體中文 (zh-tw)
**UniGetUI**（前身為 WingetUI）是一款直觀且開源的圖形化使用者介面（GUI）工具，專為 Windows 10 和 11 上的各大「命令列套件管理器」所設計。有了它，你不需要在終端機輸入複雜的指令，就能透過統一的視窗輕鬆進行軟體的搜尋、安裝、更新與解除安裝。

* **支援的套件管理器：** WinGet、Scoop、Chocolatey、Pip、NPM、Bun、.NET Tool、PowerShell Gallery 及 Cargo。
* **核心功能特色：**
    * **一鍵批次處理：** 勾選多個軟體，即可一次完成批次安裝或大量更新。
    * **備份與還原：** 支援匯出已安裝的軟體清單，換新電腦時能一鍵還原你習慣的軟體環境。
    * **自動更新通知：** 可常駐於系統工作列，在有軟體新版本時主動跳出通知，並支援略過特定版本的更新。
    * **自訂安裝參數：** 可直接在介面上選擇安裝舊版本、強制安裝 32 位元架構或自訂安裝路徑。

---

## Category 2: Terminal Emulators & Remote Management
Environments used to host shells, run commands, and manage remote connections or network infrastructure.

### 6. [Cmder](https://cmder.app/)

#### 🇺🇸 English (en-us)
**Cmder** is a popular, portable terminal emulator wrapper for Windows designed to alleviate the lack of a proper CLI experience. It combines Monokai color schemes, Git integration, and custom shell features into a standalone software package that does not require installation.

* **Key Features:**
    * **ConEmu Integration:** Built on top of the robust ConEmu terminal frontend, offering multi-tab management, split panes, and window transparency.
    * **Portable Configuration:** Runs entirely out of its own folder; carry your entire terminal environment, aliases, and settings on a USB drive.
    * **Clink Power:** Enhances the standard Windows Command Prompt (`cmd.exe`) with Unix-like features such as bash-style completion, history searching, and line editing.
    * **Multi-Shell Support:** Seamlessly handles `cmd.exe`, PowerShell, WSL (Windows Subsystem for Linux), and Git Bash within a unified interface.

#### 🇹🇼 繁體中文 (zh-tw)
**Cmder** 是一款廣受歡迎且可攜式的 Windows 終端機模擬器包裝工具，旨在解決 Windows 原生命令列介面體驗不佳的問題。它將 Monokai 色彩配置、Git 整合與自訂 Shell 功能打包成一個完全免安裝的獨立軟體。

* **核心功能特色：**
    * **整合 ConEmu：** 基於強大的 ConEmu 終端機前端建構，支援多頁籤管理、視窗分割與半透明背景效果。
    * **便攜式配置：** 完全在自身的資料夾內執行；你可以把整個終端機環境、別名（aliases）與設定裝進隨身碟隨身攜帶。
    * **Clink 強化增益：** 賦予原生 Windows 命令提示字元（`cmd.exe`）類似 Unix 的能力，例如 Bash 風格的自動補全、歷史紀錄搜尋與行編輯功能。
    * **多 Shell 支援：** 能在同一個統一介面中輕鬆切換與執行 `cmd.exe`、PowerShell、WSL（Windows 的 Linux 子系統）及 Git Bash。

---

### 7. [MobaXterm](https://mobaxterm.mobatek.net/)

#### 🇺🇸 English (en-us)
**MobaXterm** is an all-in-one toolbox for remote computing, tailored for sysadmins, developers, and power users who need to manage remote network infrastructure. It packs essential Unix tools, network utilities, and remote access clients into a single Windows desktop application.

* **Key Features:**
    * **Multi-Protocol Session Manager:** Manage SSH, Telnet, RDP, VNC, FTP, SFTP, and XDMCP connections through a structured, tabbed user interface.
    * **Embedded X11 Server:** Fully configured Xserver allows users to display remote Linux graphical applications directly on a Windows desktop.
    * **Graphical SFTP Browser:** Automatically opens a graphical file browser whenever you connect via SSH, allowing simple drag-and-drop file transfers.
    * **Network Tool Integration:** Bundles useful network utilities like port scanners, network scanners, packet captures, and an embedded TFTP/HTTP server.

#### 🇹🇼 繁體中文 (zh-tw)
**MobaXterm** 是一款全能型遠端運算工具箱，專為需要管理遠端網路基礎架構的系統管理員、開發人員與進階使用者量身打造。它將必備的 Unix 工具、網路公用程式與遠端存取用戶端整合進單一 Windows 桌面應用程式中。

* **核心功能特色：**
    * **多協定連線管理器：** 透過結構化的頁籤介面，統一管理 SSH、Telnet, RDP、VNC、FTP、SFTP 及 XDMCP 等遠端連線。
    * **內建 X11 伺服器：** 內含完整配置的 Xserver，讓使用者能直接在 Windows 桌面上顯示並操作遠端 Linux 的圖形化應用程式。
    * **圖形化 SFTP 瀏覽器：** 當你透過 SSH 連線時，系統會自動在側邊欄開啟圖形化檔案瀏覽器，支援直接拖曳檔案進行傳輸。
    * **整合網路工具：** 內建多種實用的網路工具，如埠口掃描器（Port Scanner）、網路掃描器、封包擷取工具，以及嵌入式的 TFTP/HTTP 伺服器。

---

### 8. [RustDesk](https://rustdesk.com/)

#### 🇺🇸 English (en-us)
**RustDesk** is a powerful, full-featured remote desktop application built using Rust. Acting as an open-source alternative to proprietary solutions like TeamViewer or AnyDesk, it gives users complete data security over their remote connections.

* **Key Features:**
    * **Self-Hosting Options:** Allows you to easily set up your own rendezvous/relay servers to guarantee complete ownership of your data traffic.
    * **End-to-End Encryption:** Secures all sessions using TLS 1.3 and banking-grade NaCl end-to-end encryption to prevent eavesdropping.
    * **Cross-Platform Access:** Effortlessly controls or connects from Windows, macOS, Linux, iOS, Android, and web browsers.
    * **Built-in File Transfer & Chat:** Includes a light integrated file manager and instant text chat capabilities directly within the active connection session.

#### 🇹🇼 繁體中文 (zh-tw)
**RustDesk** 是一款使用 Rust 語言編寫、功能強大的遠端桌面連線軟體。作為 TeamViewer 或 AnyDesk 等商業閉源軟體的開源替代方案，它能讓使用者對自己的遠端連線資料安全擁有完全的主導權。

* **核心功能特色：**
    * **支援自建伺服器（Self-Hosting）：** 允許使用者輕鬆架設專屬的中繼（Relay）與媒合伺服器，確保連線流量裝載絕不經過第三方伺服器。
    * **端到端加密：** 所有連線階段均採用 TLS 1.3 以及銀行級的 NaCl 端到端加密技術，徹底防止連線被竊聽。
    * **全平台相容：** 支援 Windows、macOS、Linux、iOS、Android 以及網頁瀏覽器，可跨平台雙向輕鬆遙控。
    * **內建檔案傳輸與聊天：** 視窗內整合了輕量級檔案管理器與即時文字通訊功能，方便在遠端操控時同步傳遞檔案與溝通。

---

## Category 3: Shells & Environment Customization
Tools that interpret commands or visually enhance terminal environments.

### 9. [Git for Windows / Git Bash](https://gitforwindows.org/)

#### 🇺🇸 English (en-us)
**Git for Windows** focusing on **Git Bash** provides a lightweight environment that brings a full Unix-like command-line experience to Windows systems. It acts as a bridge for developers who need to run standard open-source build scripts and Git version control workflows without jumping to a full Linux virtual machine.

* **Key Features:**
    * **MSYS2 Environment:** Emulates a POSIX-compliant environment on Windows, providing a native port of the GNU Bash shell.
    * **Standard Linux Utilities:** Bundles indispensable command-line tools such as `ssh`, `scp`, `tar`, `gzip`, `grep`, `awk`, `sed`, and `curl`.
    * **Seamless Git Integration:** Comes pre-packaged with Git version control, running optimized aliases and shell autocompletions for repository management.
    * **Windows Path Translation:** Automatically translates Unix-style file paths (`/c/Users/...`) to native Windows formats (`C:\Users\...`) on the fly.

#### 🇹🇼 繁體中文 (zh-tw)
**Git for Windows**（核心包含 **Git Bash**）提供了一個輕量級環境，為 Windows 系統帶來了完整的類 Unix 命令列體驗。對於需要在 Windows 下執行標準開源建置腳本與 Git 版本控制流程，卻又不想啟動完整 Linux 虛擬機的開發者來說，這是一座完美的橋樑。

* **核心功能特色：**
    * **MSYS2 環境模擬：** 在 Windows 上模擬符合 POSIX 標準的環境，提供 GNU Bash Shell 的原生移植版本。
    * **標準 Linux 公用程式：** 隨附許多不可或缺的命令列工具，例如 `ssh`、`scp`、`tar`、`gzip`、`grep`、`awk`、`sed` 以及 `curl`。
    * **無縫 Git 整合：** 預裝了 Git 版本控制系統，並針對版本庫（Repository）管理進行了別名優化與 Shell 自動補全。
    * **Windows 路徑自動轉換：** 在執行過程中，會自動將 Unix 風格的檔案路徑（如 `/c/Users/...`）即時翻譯為 Windows 原生路徑格式（如 `C:\Users\...`）。

---

### 10. [Oh My Posh](https://ohmyposh.dev/)

#### 🇺🇸 English (en-us)
**Oh My Posh** is a highly customizable, cross-platform prompt theme engine designed for any shell. It allows users to turn plain text terminal prompts into highly informative, visually striking dashboards using Nerd Fonts to display contextual icons and glyphs.

* **Key Features:**
    * **Cross-Shell Compatibility:** Works uniformly across PowerShell, cmd (via Clink), Bash, Zsh, Fish, and NuShell on Windows, macOS, and Linux.
    * **Context-Aware Segments:** Dynamically displays real-time details such as Git branch state (clean/dirty/ahead/behind), battery level, execution time, and exit codes.
    * **Language Runtime Telemetry:** Automatically detects project folders and highlights active software versions for Node.js, Python, Go, Rust, .NET, and Java.
    * **JSON/YAML Theme Configuration:** Customize layouts, foreground/background colors, and segment logic using simple configuration files or community-driven pre-made themes.

#### 🇹🇼 繁體中文 (zh-tw)
**Oh My Posh** 是一款高度可自訂且跨平台的終端機提示字元（Prompt）主題引擎，適用於幾乎所有的 Shell。它能讓使用者利用 Nerd Fonts（圖示字型）來顯示環境圖示，將原本枯燥的純文字命令列提示字元，升級為資訊豐富、視覺效果驚豔的儀表板。

* **核心功能特色：**
    * **跨 Shell 相容性：** 統一支援 Windows、macOS 和 Linux 上的 PowerShell、cmd（透過 Clink）、Bash、Zsh、Fish 及 NuShell。
    * **情境感知區段（Segments）：** 動態顯示即時狀態資訊，例如 Git 分支狀態（乾淨/有變更/領先/落後）、電池電量、指令執行耗時與錯誤碼（Exit Codes）。
    * **程式語言環境偵測：** 自動辨識當前的專案資料夾，並主動標示 active 的軟體版本，例如 Node.js、Python、Go、Rust、.NET 及 Java。
    * **JSON/YAML 主題配置：** 使用簡單的設定檔即可完全自訂版面配置、前景色/背景色與區段邏輯，亦可直接套用社群提供的數百種現成主題。
