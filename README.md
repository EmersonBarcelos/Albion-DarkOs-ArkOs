<div align="center">

# Albion - PortMaster (Darkos/Arkos) 🌍

[![English](https://img.shields.io/badge/Language-English-blue?style=for-the-badge)](#-english)
[![Português](https://img.shields.io/badge/Idioma-Português-green?style=for-the-badge)]#-português

</div>

---

## <a id="-english"></a>🇺🇸 English

A native Linux (ARM64) port of the classic RPG **Albion** for retro handheld consoles like the R36S (running ArkOS/DarkOS), compatible with PortMaster. 

This port utilizes the [SR Engine by M-HT](https://github.com/M-HT/SR), which provides native execution, gamepad-to-mouse emulation, and enhanced 3D rendering[span_0](start_span)[span_0](end_span).

### ⚙️ Requirements
* A supported retro handheld device (R36S, etc.) running a PortMaster-compatible OS (ArkOS, etc.).
* Original game files of Albion (The [GOG.com version](https://www.gog.com/game/albion) or original CD version is required)[span_1](start_span)[span_1](end_span).

### 📥 Installation Guide

1. **Install or Extract the Game:** Install Albion on your PC. If you are using the GOG version, you can install it or extract the setup files using `innoextract`[span_2](start_span)[span_2](end_span).
2. **Mount and Copy CD Data:** The GOG version includes a file named `game.gog` (this is a BIN image of the CD)[span_3](start_span)[span_3](end_span). Mount it and copy the `ALBION` subdirectory from the CD into your main installed game folder[span_4](start_span)[span_4](end_span).
3. **Rename the Directory:** Rename the copied CD folder to `ALBIONCD` (Must be uppercase, no spaces).
4. **Edit SETUP.INI:** Open `SETUP.INI` in the main game folder. Find the line starting with `SOURCE_PATH=` and change it to `SOURCE_PATH=ALBIONCD\`[span_5](start_span)[span_5](end_span).
5. **Transfer to SD Card:** Download the latest release `.zip` of this port. Extract the contents directly into the `ports` directory of your SD card (usually `/roms/ports/`).
6. **Move Game Files:** Copy your prepared Albion game files (including the `ALBIONCD` folder and modified `SETUP.INI`) into the `/ports/albion/` directory on your SD card.
7. Launch **Albion** from the Ports menu on your device.

### 🎮 Hotkeys & Controls

The game features native gamepad support enabled via the game's engine[span_6](start_span)[span_6](end_span).

| Button | Action |
| :--- | :--- |
| **D-Pad / Left Analog** | Mouse Movement / Arrow Keys[span_7](start_span)[span_7](end_span) |
| **A / X** | Left Mouse Button[span_8](start_span)[span_8](end_span) |
| **B / Y** | Right Mouse Button[span_9](start_span)[span_9](end_span) |
| **Start** | Virtual Keyboard[span_10](start_span)[span_10](end_span) |
| **Select** | Tab Key (Map/Menu)[span_11](start_span)[span_11](end_span) |
| **L1** | Alt Key[span_12](start_span)[span_12](end_span) |
| **R1** | Ctrl Key[span_13](start_span)[span_13](end_span) |
| **Select + Start** | Force Quit (via PortMaster) |

### 🙏 Credits
* **M-HT** for the incredible [SR Engine](https://github.com/M-HT/SR)[span_14](start_span)[span_14](end_span).
* Ported and configured by **Emerson Barcelos**.

---

## <a id="-português"></a>🇧🇷 Português

Port nativo de Linux (ARM64) do clássico RPG **Albion** para consoles portáteis retrô como o R36S (rodando ArkOS/DarkOS), compatível com o PortMaster.

Este port utiliza a [Engine SR criada por M-HT](https://github.com/M-HT/SR), que permite execução nativa, emulação de mouse direto no gamepad e renderização 3D aprimorada[span_15](start_span)[span_15](end_span).

### ⚙️ Requisitos
* Um console portátil compatível (R36S, etc.) rodando um sistema com suporte ao PortMaster (ArkOS, etc.).
* Arquivos originais do jogo Albion (A [versão da GOG.com](https://www.gog.com/game/albion) ou os arquivos originais do CD são obrigatórios)[span_16](start_span)[span_16](end_span).

### 📥 Guia de Instalação

1. **Instale ou Extraia o Jogo:** Instale o Albion no seu PC. Se estiver usando a versão da GOG, você pode instalá-la normalmente ou extrair os arquivos de instalação (usando `innoextract`)[span_17](start_span)[span_17](end_span).
2. **Monte e Copie os Dados do CD:** A versão da GOG inclui um arquivo chamado `game.gog` (que é uma imagem BIN do CD)[span_18](start_span)[span_18](end_span). Monte esta imagem e copie o subdiretório `ALBION` de dentro do CD para a pasta principal do jogo instalado no seu PC[span_19](start_span)[span_19](end_span).
3. **Renomeie o Diretório:** Renomeie a pasta do CD que você acabou de copiar para `ALBIONCD` (Deve ser tudo em maiúsculo e sem espaços).
4. **Edite o SETUP.INI:** Abra o arquivo `SETUP.INI` na raiz da pasta do jogo. Encontre a linha que começa com `SOURCE_PATH=` e altere para `SOURCE_PATH=ALBIONCD\`[span_20](start_span)[span_20](end_span).
5. **Transfira para o Cartão SD:** Baixe o arquivo `.zip` da última *release* deste port. Extraia o conteúdo diretamente para o diretório `ports` do seu cartão SD (geralmente `/roms/ports/`).
6. **Mova os Arquivos do Jogo:** Copie os arquivos originais do seu jogo Albion preparados (incluindo a pasta `ALBIONCD` e o `SETUP.INI` modificado) para dentro do diretório `/ports/albion/` no seu cartão SD.
7. Inicie o **Albion** através do menu de Ports do seu console.

### 🎮 Controles e Atalhos

O jogo possui suporte nativo a controles habilitado diretamente pela engine[span_21](start_span)[span_21](end_span).

| Botão | Ação |
| :--- | :--- |
| **D-Pad / Analógico Esq.** | Movimento do Mouse / Setas Direcionais[span_22](start_span)[span_22](end_span) |
| **A / X** | Botão Esquerdo do Mouse[span_23](start_span)[span_23](end_span) |
| **B / Y** | Botão Direito do Mouse[span_24](start_span)[span_24](end_span) |
| **Start** | Teclado Virtual[span_25](start_span)[span_25](end_span) |
| **Select** | Tecla Tab (Mapa/Menu)[span_26](start_span)[span_26](end_span) |
| **L1** | Tecla Alt[span_27](start_span)[span_27](end_span) |
| **R1** | Tecla Ctrl[span_28](start_span)[span_28](end_span) |
| **Select + Start** | Fechar o jogo (via PortMaster) |

### 🙏 Créditos
* **M-HT** pela incrível [Engine SR](https://github.com/M-HT/SR)[span_29](start_span)[span_29](end_span).
* Port e configuração por **Emerson Barcelos**.
