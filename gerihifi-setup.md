# DIRETTA - HiFi-Chain #1

`Speaker:` `DeVore O96 Reference - complete rebuild with active Subwoofer (RobF)` \
`Speaker cable:` `Driade Flow Reference 808 Copper G`

`LAN Chaining:` `Power of Ethernet <> OXCO <> Paul Pang Dual`

## Digital Sources

- **Grimm Audio MU2 - Roon Core**
- **Lumin U1 Streamer - Roon Bridge**
- **Pachanko Labs Constellation Mini SE - Roon/Diretta Host**
- **SPEC RMP-UB1SFP-KEX - Roon/Diretta Target**
- **Abbas Audio 3.2SE (TDA1541A) - DAC only**
- **Abbas Audio Hermes Sig (PCM63P-K) - DAC only**
- **Holo Audio May KTE - DAC only**
- **Sony CDP X505ES Swoboda full-modification - CD Player (internal DAC)**
- **Cyrus CDi with external PSU - CD Transport (Abbas DAC)**

## AMP: Meishu Tonmeister 300b Silver Signature

```mermaid
sequenceDiagram
    AN Meishu TM 300B->>Holo May KTE: Analog / RCA
    Note over AN Meishu TM 300B,Holo May KTE: Cable: Audiomica Red Ref Rhod Lux<br> Power: GigaWatt LS-1 Mk3+
    AN Meishu TM 300B->>Abbas Audio 3.2SE: Analog / RCA
    Note over AN Meishu TM 300B,Abbas Audio 3.2SE: Cable: Luxman JPR-1500<br> Power: Abbas Cable
    Holo May KTE->>Constellation Mini SE: USB (Titanis)
    Note over Constellation Mini SE,Holo May KTE: Cable: Signal Lynx Ref USB2.0<br> Power: Ferrum Hypsos
    Abbas Audio 3.2SE->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Audio 3.2SE: Cable: <br> Power:
    Abbas Hermes->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Hermes: Cable: <br> Power: Abbas Cable
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
