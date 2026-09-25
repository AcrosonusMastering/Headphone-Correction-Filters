### 🎧 Headphone Convolution EQ Collection

A collection of 74 impulse responses (IR) in .wav format (48 kHz) designed to correct the frequency response of various headphones and earbuds.

By applying these convolution reverbs / FIR filters, you can neutralize the sound signature of your headphones for a flatter, more transparent, and balanced listening experience—ideal for mixing, mastering, or audiophile music listening.

### 📊 Methodology & Measurements

All impulse response filters in this project are created using measurement data from Rtings:

Target Curve: The EQ correction targets the reference curve established in the Rtings Frequency Response Research Study.

https://www.rtings.com/headphones/learn/research/frequency-response-1-8

Data Source: Measurements are sourced directly from Rtings due to their state-of-the-art test rigs and rigorous, standardized measurement protocols, ensuring maximum consistency across all models.

Unlike AutoEQ, which aggregates measurements from various sources without a single consistent protocol, this project uses standardized measurements from Rtings. Furthermore, AutoEQ's target curves are not always the best choice for neutral listenin

### 💾 Download
Click on the impulse file you want, then click the Download button (or the download icon in the top right).
<img width="1351" height="200" alt="image" src="https://github.com/user-attachments/assets/909f173d-5a54-433f-992b-92d20784e328" />

### 🚀 Key Features

74 headphone & earbud models supported (Sennheiser, Sony, Beyerdynamic, Apple, Audeze, Focal, JBL, and more).

Audio Format: High-quality 48 kHz .wav impulse responses.

Universal Compatibility: Works with any convolution reverb engine or FIR processor (Equalizer APO, MConvolutionEZ (free), etc.).

EXAMPLE
Anker Soundcore Life Q30:
🟪purple original 🟦blue: target: 🟥red: reponse after correction<img width="1089" height="575" alt="Capture d&#39;écran 2026-09-25 160328" src="https://github.com/user-attachments/assets/998e1d4b-9a66-4924-a4ab-be4ade32d153" />


### 🛠️ Setup & Usage Guide

### 💻 1. System-Wide Correction on Windows (Equalizer APO) (Mac OS: Audio Hijack)

To apply the correction filter to all audio coming out of your PC (Spotify, YouTube, games, browser, etc.):

Download & Install Equalizer APO:

Download the installer from SourceForge.

During installation, check the box next to the audio device (sound card/DAC) connected to your headphones.

Restart your computer when prompted.

Load the Impulse Response File:

Launch the Configuration Editor app included with Equalizer APO.

Clear or turn off default filters.

Click the green + icon > Advanced filters > Convolution.

Click the folder icon and browse to select the .wav file matching your headphone model (e.g., Sennheiser_HD600-filters-48k.wav).

(Optional) Preamplification / Gain Adjustment:

If EQ boosting causes digital clipping, add a Preamp control at the top of your signal chain and reduce the gain slightly (e.g., -3 dB to -6 dB).

### 🎛️ 2. Usage in a Digital Audio Workstation (DAW)

To apply correction exclusively within your DAW (REAPER, Pro Tools, Ableton Live, FL Studio, Cubase, Logic Pro, etc.):

Insert a Convolution Reverb plugin on your Master Channel or Monitoring FX track (e.g., ReaVerb, FabFilter Pro-R 2, SIR3, Melda MConvolutionEZ).

Import the appropriate .wav file into the plugin.

Set the plugin mix control to 100% Wet / 0% Dry.

Important: Remember to bypass or disable the plugin before exporting/rendering your final audio track!

### 🎧 Supported Models (74 Total)
### AIAIAI
- AIAIAI_TMA-2DJ

### AKG
- AKG_361
- AKG_371
- AKG_702

### Anker / Soundcore
- ANKER_P40i
- ANKER_Q30
- ANKER_SOUNDCORE_P3I

### Apple
- Apple AirPod Max 2
- Apple AirPod Pro 2
- Apple AirPod Pro 3

### Audeze
- Audeze LCD-X
- Audeze MM-100
- Audeze MM-500

### Audio-Technica
- Audio-Technica ATH-M50X
- Audio-Technica ATH-ADX3000

### Beats
- Beats Solo 4

### Beyerdynamic
- Beyerdynamic MMX 300 (2nd Gen)
- Beyerdynamic DT 770 Pro
- Beyerdynamic DT 990 Pro
- Beyerdynamic DT 1990 Pro MKII

### Bose
- Bose QuietComfort Earbuds II
- Bose QuietComfort Headphones (2nd Gen)
- Bose QuietComfort Headphones
- Bose QuietComfort Ultra Headphones (2nd Gen)

### FiiO
- FiiO FT1
- FiiO FT1 Pro

### Focal
- Focal Azurys
- Focal Bathys BT
- Focal Bathys MG

### Google
- Google Pixel Buds Pro 2

### Hedd Audio
- Hedd Heddphone D1

### HIFIMAN
- HIFIMAN Arya
- HIFIMAN HE400se
- HIFIMAN Sundara (2020)

### HyperX
- HyperX Cloud III BT

### JBL
- JBL Live 770BT
- JBL Live 780BT
- JBL Tune 520BT

### Logitech
- Logitech G535 Lightspeed BT
- Logitech G Pro X 2 Lightspeed BT

### Moondrop
- Moondrop Space Travel 2

### Nothing
- Nothing Headphone (1)
- Nothing Headphone (a)

### Razer
- Razer BlackShark V2 Pro (3)

### Samsung
- Samsung Galaxy Buds 3
- Samsung Galaxy Buds 3 Pro
- Samsung Galaxy Buds 4
- Samsung Galaxy Buds 4 Pro
- Samsung Galaxy Buds FE

### Sennheiser
- Sennheiser HD 25
- Sennheiser HD 480 Pro
- Sennheiser HD 490 Pro
- Sennheiser HD 560S
- Sennheiser HD 6XX
- Sennheiser HD 600
- Sennheiser HD 620S
- Sennheiser HD 660S2
- Sennheiser HD 800S
- Sennheiser Momentum True Wireless 4
- Sennheiser Momentum True Wireless 5

### Skullcandy
- Skullcandy Dime 3

### Sony
- Sony MDR-7506
- Sony WF-1000XM5
- Sony WF-1000XM6
- Sony WH-CH720N BT
- Sony WH-1000XM4
- Sony WH-1000XM5
- Sony WH-1000XM6

### SteelSeries
- SteelSeries Arctis Nova Pro
- SteelSeries Arctis Nova Elite
- SteelSeries Arctis Nova Pro Wireless
- SteelSeries Arctis Pro Wireless
- SteelSeries Arctis Nova 5

### Superlux
- Superlux HD681

</details>

---

## 📜 Licence & Contributions

Correction Files (IR): Designed and generated by Acrosonus Mastering studio, released under the GPLv3 license.

Measurement Data: Raw frequency response measurements used as the baseline are sourced from Rtings.com.
