![gerihifi](.img/gerihifi-setup-logo.png)

# Streaming

- **Primary APP: Roon, Roon ARC**
- **Music Provider: Qobuz Studio**
- **Podcasts: Spotify Premium**
- **On-The-Road: Spotify, Soundcloud, Roon ARC, YT-Premium, Amazon PRIME Music**

# Digital Sources

- **Grimm Audio MU2 - Roon Core**
- **Lumin U1 Streamer - Roon Bridge**
- **Pachanko Labs Constellation Mini SE - Roon/Diretta Host**
- **SPEC RMP-UB1SFP-KEX - Roon/Diretta Target**
- **Abbas Audio 3.2SE (TDA1541A) - DAC only**
- **Abbas Audio Hermes Sig (PCM63P-K) - DAC only**
- **Holo Audio May KTE - DAC only**
- **Sony CDP XA50ES Swoboda highest-modification - CD Player (internal DAC + SPDIF)**
- **Sony CDP X505ES Swoboda full-modification - CD Player (internal DAC + TOSLINK)**
- **Cyrus CDi with external PSU - CD Transport (Abbas DAC)**

---

# DIGITAL ONLY - HiFi-Chain #2

`Speaker:` `DeVore O96 Reference - complete rebuild with active Subwoofer (RobF)`

`Speaker cable:` `Driade Flow Reference 808 Copper G 3m / Inakustik LS2404-MK2 3m`

`LAN Chaining:` `Devolo Powerline <> OXCO TeraTek<> Paul Pang Dual`

## AMP: Meishu Tonmeister 300b Silver Signature

```mermaid
sequenceDiagram
    AN Meishu TM 300B->>Holo May KTE: Analog / RCA
    Note over AN Meishu TM 300B,Holo May KTE: Cable: Audiomica Red Ref Rhod Lux<br> Power: GigaWatt LS-1 Mk3+
    AN Meishu TM 300B->>Abbas Audio 3.2SE: Analog / RCA
    Note over AN Meishu TM 300B,Abbas Audio 3.2SE: Cable: Luxman JPR-1500<br> Power: Abbas Cable
    Abbas Audio 3.2SE->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Audio 3.2SE: Cable: <br> Power:
    Abbas Hermes->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Hermes: Cable: <br> Power: Abbas Cable
    Holo May KTE->>Constellation Mini SE: USB (Titanis)
    Note over Constellation Mini SE,Holo May KTE: Cable: Signal Lynx Ref USB2.0<br> Power: Ferrum Hypsos
    Lumin U1->>Abbas Audio 3.2SE: SPDIF / COAX
    Note over Abbas Audio 3.2SE,Lumin U1: Cable: <br> Power: Lumin external PSU
    Lumin U1->>Holo May KTE: AES / EBU
    Note over Holo May KTE,Lumin U1: Cable: Driade Flow Ref 808 AES
    Constellation Mini SE->>SPEC RMP-UB1-KEX: Diretta Target (LAN-100Mbit/s)
    Note over SPEC RMP-UB1-KEX,Constellation Mini SE: Cable: <br> Power: Ferrum Hypsos
    activate SPEC RMP-UB1-KEX
    SPEC RMP-UB1-KEX->>Constellation Mini SE: Diretta Host (LAN-100Mbit/s)
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

`LAN Chaining:` `Devolo Powerline <> Paul Pang Quad`

---

## Pre/AMP: Soulution 725 (Pre) / LinnenberG G.F.Händel Monos

```mermaid
sequenceDiagram
    Soulution 725->>LinnenberG Monos: Analog / XLR
    Note over Soulution 725,LinnenberG Monos: Cable: Solution<br> Power:
    Grimm Audio MU2->>Soulution 725: xx
    Sony CDP->>Soulution 725: xx
```

---
