# Albion - PortMaster (ARM64) 🌍

![Albion Banner](https://via.placeholder.com/800x250?text=Albion+PortMaster)

*(Read in [English](#english) | Leia em [Português](#português))*

---

## 🇺🇸 English

A native Linux (ARM64) port of the classic RPG **Albion** for retro handheld consoles like the R36S (running ArkOS/DarkOS), compatible with PortMaster. 

This port utilizes the [SR Engine by M-HT](https://github.com/M-HT/SR), which provides native execution, gamepad-to-mouse emulation, and enhanced 3D rendering without the need for DOSBox.

### ⚙️ Requirements
* A supported retro handheld device (R36S, etc.) running a PortMaster-compatible OS (ArkOS, etc.).
* Original game files of Albion (The [GOG.com version](https://www.gog.com/game/albion) is highly recommended).

### 📥 Installation Guide

1. **Install or Extract the Game:** Install Albion on your PC. If you are using the GOG version, you can install it or extract the setup files using `innoextract`.
2. **Mount and Copy CD Data:** The GOG version includes a file named `game.gog` (this is a BIN image of the CD). Mount it (using tools like WinCDEmu or gCDEmu) and copy the `ALBION` subdirectory from the CD into your main installed game folder.
3. **Rename the Directory:** Rename the copied CD folder to `ALBIONCD` (Must be uppercase, no spaces).
4. **Edit SETUP.INI:** Open `SETUP.INI` in the main game folder. Find the line starting with `SOURCE_PATH=` and change it to `SOURCE_PATH=ALBIONCD\`.
5. **Transfer to SD Card:** Download the latest release `.zip` of this port. Extract the contents directly into the `ports` directory of your SD card (usually `/roms/ports/`).
6. **Move Game Files:** Copy your prepared Albion game files (including the `ALBIONCD` folder and modified `SETUP.INI`) into the `/ports/albion/` directory on your SD card.
7. Launch **Albion** from the Ports menu on your device.

### 🎮 Hotkeys & Controls

The game features native gamepad support enabled via the game's engine.

| Button | Action |
| :--- | :--- |
| **D-Pad / Left Analog** | Mouse Movement / Arrow Keys |
| **A / X** | Left Mouse Button |
| **B / Y** | Right Mouse Button |
| **Start** | Virtual Keyboard |
| **Select** | Tab Key (Map/Menu) |
| **L1** | Alt Key |
| **R1** | Ctrl Key |
| **Select + Start** | Force Quit (via PortMaster) |

### 🙏 Credits
* **M-HT** for the incredible [SR Engine](https://github.com/M-HT/SR).
* Ported and configured by **Emerson Barcelos**.

---

## 🇧🇷 Português

Port nativo de Linux (ARM64) do clássico RPG **Albion** para consoles portáteis retrô como o R36S (rodando ArkOS/DarkOS), compatível com o PortMaster.

Este port utiliza a [Engine SR criada por M-HT](https://github.com/M-HT/SR), que permite execução nativa, emulação de mouse direto no gamepad e renderização 3D aprimorada sem a necessidade do DOSBox.

### ⚙️ Requisitos
* Um console portátil compatível (R36S, etc.) rodando um sistema com suporte ao PortMaster (ArkOS, etc.).
* Arquivos originais do jogo Albion (A [versão da GOG.com](https://www.gog.com/game/albion) é altamente recomendada).

### 📥 Guia de Instalação

1. **Instale ou Extraia o Jogo:** Instale o Albion no seu PC. Se estiver usando a versão da GOG, você pode instalá-lo normalmente ou extrair os arquivos de instalação (usando `innoextract`).
2. **Monte e Copie os Dados do CD:** A versão da GOG inclui um arquivo chamado `game.gog` (que é uma imagem BIN do CD). Monte esta imagem (usando WinCDEmu ou gCDEmu) e copie o subdiretório `ALBION` de dentro do CD para a pasta principal do jogo instalado no seu PC.
3. **Renomeie o Diretório:** Renomeie a pasta do CD que você acabou de copiar para `ALBIONCD` (Deve ser tudo em maiúsculo e sem espaços).
4. **Edite o SETUP.INI:** Abra o arquivo `SETUP.INI` na raiz da pasta do jogo. Encontre a linha que começa com `SOURCE_PATH=` e altere para `SOURCE_PATH=ALBIONCD\`.
5. **Transfira para o Cartão SD:** Baixe o arquivo `.zip` da última *release* deste port. Extraia o conteúdo diretamente para o diretório `ports` do seu cartão SD (geralmente `/roms/ports/`).
6. **Mova os Arquivos do Jogo:** Copie os arquivos originais do seu jogo Albion preparados (incluindo a pasta `ALBIONCD` e o `SETUP.INI` modificado) para dentro do diretório `/ports/albion/` no seu cartão SD.
7. Inicie o **Albion** através do menu de Ports do seu console.

### 🎮 Controles e Atalhos

O jogo possui suporte nativo a controles habilitado diretamente pela engine.

| Botão | Ação |
| :--- | :--- |
| **D-Pad / Analógico Esq.** | Movimento do Mouse / Setas Direcionais |
| **A / X** | Botão Esquerdo do Mouse |
| **B / Y** | Botão Direito do Mouse |
| **Start** | Teclado Virtual |
| **Select** | Tecla Tab (Mapa/Menu) |
| **L1** | Tecla Alt |
| **R1** | Tecla Ctrl |
| **Select + Start** | Fechar o jogo (via PortMaster) |

### 🙏 Créditos
* **M-HT** pela incrível [Engine SR](https://github.com/M-HT/SR).
* Port e configuração por **Emerson Barcelos**.
