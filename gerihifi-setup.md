![gerihifi](.img/gerihifi2-setup-logo.png)

`Last update:`  `Aug 7th`

# Streaming

- **Primary APP:** Roon
- **Music Provider:** Qobuz Studio
- **Podcasts:** Spotify Premium
- **On-The-Road:** Spotify, Soundcloud, Roon ARC, YT-Premium, Amazon PRIME Music

# Digital Sources

- **Grimm Audio MU2 - Roon Core**
  - Volume: fixed, through Soulution 725 Pre-AMP
- **Lumin U1 Streamer - Roon Bridge**
  - Volume: fixed, through AN 300B or Brinkmann Marconi Pre-AMP
- **Pachanko Labs Constellation Mini SE - Roon/Diretta Host**
- **SPEC RMP-UB1SFP-KEX - Roon/Diretta Target**
- **Abbas Audio 3.2SE (TDA1541A) - DAC only**
- **Abbas Audio Hermes Sig (PCM63P-K) - DAC only**
- **Holo Audio May KTE - DAC only**
- **Sony CDP XA50ES Swoboda highest-modification - CD Player (internal DAC + SPDIF)**
- **Sony CDP X505ES Swoboda full-modification - CD Player (internal DAC + TOSLINK)**
- **Cyrus CDi with external PSU - CD Transport (Abbas DAC + Holo May/SPDIF)**

---

# DIGITAL ONLY - HiFi-Chain #2

`Speaker:` `DeVore O96 Reference - complete rebuild with active Subwoofer (RobF)`

`Speaker cable:` `Driade Flow Reference 808 Copper G 3m / Inakustik LS2404-MK2 3m`

`Speaker spikes:` `DIY wood-stand, marble slap and with basotec foam pads under speaker and slap`

`LAN Chaining:` `Devolo Powerline <> OXCO TeraTek<> Paul Pang Dual`

`Power Conditioner:` `AudioQuest Niagara 3000 (AN 300B,CD-Cyrus,CD-Sony,Abbas DAC,Constellation)`

`Netzleiste:` `Cardas Audio Nautilus (der Rest)`

## AMP: Meishu Tonmeister 300b Silver Signature

```mermaid
sequenceDiagram
    AN Meishu TM 300B->>Holo May KTE: Analog / RCA
    Note over AN Meishu TM 300B,Holo May KTE: Cable: Audiomica Red Ref Rhod Lux<br> Power: GigaWatt LS-1 Mk3+
    AN Meishu TM 300B->>Abbas Audio 3.2SE: Analog / RCA
    Note over AN Meishu TM 300B,Abbas Audio 3.2SE: Cable: Luxman JPR-1500<br> Power: Abbas Cable
    Abbas Audio 3.2SE->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Audio 3.2SE: Cable: Authentic Audio Image Meastro 2<br> Power: Ferrum Hypsos
    Abbas Hermes->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Hermes: Cable: Signal Projects Hydra
    Holo May KTE->>Constellation Mini SE: USB (Titanis)
    Note over Constellation Mini SE,Holo May KTE: Cable: Signal Lynx Ref USB2.0<br> Power: LessLoss DFPC Reference
    Lumin U1->>Abbas Audio 3.2SE: SPDIF / COAX
    Note over Abbas Audio 3.2SE,Lumin U1: Cable: Abbas digital<br> Power: Lumin external PSU
    Lumin U1->>Holo May KTE: Digital / AES-EBU
    Note over Holo May KTE,Lumin U1: Cable: Driade Flow Ref 808 AES
    Constellation Mini SE->>SPEC RMP-UB1-KEX: Diretta Target (LAN-1Gbit/s)
    Note over SPEC RMP-UB1-KEX,Constellation Mini SE: Cable: LAN-1Gbits (IPv6) <br> Power: Ferrum Hypsos
    activate SPEC RMP-UB1-KEX
    SPEC RMP-UB1-KEX->>Constellation Mini SE: Diretta Host (LAN-1Gbit/s)
    deactivate SPEC RMP-UB1-KEX
```

---

## Pre/AMP: Brinkmann Audio Marconi MK-II (Pre) / Brinkmann Stereo MK-II (AMP)

```mermaid
sequenceDiagram
    Marconi MK-II->>Holo May KTE: Analog / XLR
    Note over Marconi MK-II,Holo May KTE: Cable: Curious Cables XLR<br> Power: External Brinkmann
    Stereo MK-II->>Marconi MK-II: Analog / RCA
    Note over Marconi MK-II,Stereo MK-II: Cable: Driade Flow Ref 808<br> Power: Furutech Alpha OCC
    Marconi MK-II->>Abbas Hermes: Analog / XLR
    Note over Marconi MK-II,Abbas Hermes: Cable: <br> Power: Abbas Cable
```

---

# DIGITAL ONLY - HiFi-Chain #1

`Speaker:` `ELAC Concentro S507 (v1)`

`Speaker cable:` `Inakustik LS2404-MK2 Bi-Wire to Single-Wire 4m`

`Speaker spikes:` `Stackaudio Auva 100 with felt pads`

`LAN Chaining:` `Devolo Powerline <> Paul Pang Quad`

`Power Conditioner:` `Stromtank S-1000 (Monos,Grimm MU2,Soulution)`

`Netzleiste:` `Cardas Audio Nautilus (CD-Player,PaulPang)`

---

## Pre/AMP: Soulution 725 (Pre) / LinnenberG G.F.Händel Monos (AMP)

```mermaid
sequenceDiagram
    Soulution 725->>LinnenberG Monos: Analog / XLR
    Note over Soulution 725,LinnenberG Monos: Cable: Gutewire EON-Z XLR<br> Power: LessLoss DFPC Reference
    Note over LinnenberG Monos,Soulution 725: Power: GigaWatt LC3-mK3
    Grimm Audio MU2->>Soulution 725: Analog / XLR
    Note over Grimm Audio MU2,Soulution 725: Cable: Driade Flow Ref 808 XLR<br> Power: The Essence Reference-II
    Sony XA50ES->>Soulution 725: Analog / RCA
    Note over Soulution 725,Sony XA50ES: Cable: Swoboda RVI+100 WBT<br> Power: Swoboda Ref 2 150 Furutech gold
```

---
