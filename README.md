![header](https://capsule-render.vercel.app/api?type=rounded&height=150&color=0:83c8fc,50:8880fc,100:cc7dfc&text=iiSUcore%20&textBg=false&animation=fadeIn&section=header&strokeWidth=1&desc=A%20theme%20for%20RetroArch%20based%20on%20iiSU%20FrontEnd&descAlign=0&descAlignY=79&stroke=FFFFFF&fontColor=e4dafb)

> A community-crafted XMB theme for RetroArch, born from **FlatUX**, shaped by **UsagiShade**.  
> PC pals make do, don't we?

---

## 📑 Index

1. [Quick Start & Installation](#-quick-start--installation)
2. [Theme Configuration](#-theme-configuration)
3. [Audio Setup & Sound Troubleshooting](#-audio-setup--sound-troubleshooting)
4. [About iiSU](#-about-iisu)
5. [About RetroArch](#️-about-retroarch)
6. [Credits & Heritage](#-credits--heritage)
7. [To-Do List](#️-to-do-list)
8. [Legal & Licensing](#️-legal--licensing)

---

## 🚀 Quick Start & Installation

1. **Download** this repository as a ZIP or clone it.
2. **Locate your RetroArch `assets` folder** — usually found at `RetroArch/assets/`.
3. **Drag and drop** the `sounds`, `xmb` & `wallpapers` folders into that `assets` directory.
4. **Open RetroArch** and apply the theme by following the [Theme Configuration](#-theme-configuration) section below.

---

## 🎨 Theme Configuration

Navigate to the following settings inside RetroArch to get the exact intended look:

### Interface / Icon Theme

| Setting | Path | Value |
|---|---|---|
| **Menu** | `Settings` → `User Interface` | — |
| **Icon Theme** | `Appearance` → `Menu Icon Theme` | `monochromatic` |
| **Theme Color** | `Appearance` → `Theme Color` | `Background Image` |
| **Theme Color Alpha** | `Appearance` → `Theme Color Alpha` | `100` |
| **Theme Color Opacity** | `Appearance` → `Theme Color Opacity` | `1.000` |
| **Dynamic Backgrounds** | `Appearance` → `Dynamic Backgrounds` | `ON` ✅ |
| **Shadow Effects** | `Appearance` → `Shadow Effects` | `OFF` ❌ |
| **Font** | `Appearance` → `Font` | `Default` |

### Font Color (RGB)

Navigate to `Settings` → `User Interface` → `Appearance` → `Font Color` and set:

| Channel | Value |
|---|---|
| **Red** | `133` |
| **Green** | `133` |
| **Blue** | `133` |

> 💡 This neutral grey tone keeps text clean and legible across all background types.

---

## 🔊 Audio Setup & Sound Troubleshooting

iiSUcore ships with custom menu sounds and a background music track. Here's how to get everything working.

### Enabling Menu Sounds

1. Go to `Settings` → `Audio`.
2. Make sure **Audio** is globally **enabled**.
3. Under the same menu, enable **Menu Sounds**.
4. Enable **Background Music (BGM)**.

### Enabling MIDI / Menu Sound Output

RetroArch routes menu audio through your system's audio driver. If sounds aren't playing:

1. Go to `Settings` → `Audio` → `Output`.
2. Check that **Audio Driver** is set correctly for your system (e.g., `wasapi` on Windows, `alsa` or `pulse` on Linux, `coreaudio` on macOS).
3. Confirm your **Audio Device** is pointing to the correct output.
4. If you're using MIDI or a virtual audio device, make sure it's selected as the active output in your OS sound settings as well.

### Sounds Aren't Working / Sound Crappy?

Try this recommended minimal config:

- ✅ Keep **Background Music (BGM)** enabled
- ✅ Keep **OK Sound** enabled  
- ✅ Keep **Cancel Sound** enabled
- ❌ Disable all other individual menu sound effects

> This avoids audio conflicts and sound layering issues that can cause crackling or silence on some setups.

### Volume Adjustment

- **Master volume**: `Settings` → `Audio` → `Volume` — adjust the `Audio Volume` slider.
- **BGM volume**: Look for `Menu Sound Volume` or `BGM Volume` under `Settings` → `Audio` — lower this if BGM overpowers the UI sounds, or raise it if it feels too quiet.

> 🎵 The included BGM is the **iiSU Main Theme** by **[Thaddeus Silva](https://thaddeussilva.bandcamp.com/track/iisu-main-theme)**. Do yourself a favor and go listen to his full catalog.

---

## 📺 About iiSU

iiSU is a emulation FrontEnd.

- **YouTube:** [iiSU Channel](https://www.youtube.com/@iiSU)
- **Community:** [Join the Discord](https://discord.gg/iisu)
- **Website:** [iiSU Network](https://iisu.network)

---

## 🕹️ About RetroArch

RetroArch is the premier frontend for emulators, game engines, and media players.

- **Official Website:** [retroarch.com](https://www.retroarch.com/)

---

## 🎨 Credits & Heritage

### iiSUcore Evolution

Built on top of **FlatUX**, which itself is a legendary merger of **FlatUI** (pioneered for Libretro XMB) and **Retroactive**. In 2022, [baxysquare](https://github.com/baxysquare/) unified these projects to create the expanded FlatUX palette I use as the base today.

### UsagiShade Designs

A significant portion of the visual assets and aesthetic direction came from [UsagiShade](https://www.youtube.com/@usagishade). While he is no longer affiliated with iiSU, his concepts were instrumental in shaping the "iiSU look" found in this theme.

### 🎵 Background Music

The included BGM is the **iiSU Main Theme** by **[Thaddeus Silva](https://thaddeussilva.bandcamp.com/track/iisu-main-theme)**.  
Go to his Bandcamp, listen to his work, and subscribe. Now.

### 🔡 Typography

This theme uses the **Continuum** font.  
*License Note:* Historically attributed to Broderbund (a defunct American software company). Used here for aesthetic purposes.

---

## 🛠️ Waystones

- [ ] Expanded console icon set < We are here!
- [ ] Bespoke custom icons (moving away from FlatUX legacy)
- [ ] Dynamic custom backgrounds for each console
- [ ] Bundled `.conf` file for "one-click" optimal scaling and theme settings
- [ ] Integration of UsagiShade overlays
- [ ] Integrated quick-scraper *(maybe? dunno)*

---

## ⚖️ Legal & Licensing

**Disclaimer:** This project is a fan-made effort.

- Not affiliated with iiSU, Libretro, or RetroArch.
- All trademarks, logos, and brands are property of their respective owners.
- This theme is provided **as-is** for personal use and customization.