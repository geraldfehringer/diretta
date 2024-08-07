# DIRETTA - HiFi-Chain #1

`Speaker:` `DeVore O96 Reference - complete rebuild with active Subwoofer (RobF)`

`LAN Chaining:` `Power of Ethernet <> OXCO <> Paul Pang Dual`

## AMP: Meishu Tonmeister 300b Silver Signature

```mermaid
sequenceDiagram
    AN Meishu TM 300B->>Holo May KTE: Analog / RCA
    Note over AN Meishu TM 300B,Holo May KTE: Cable: <br> Power: GigaWatt
    AN Meishu TM 300B->>Abbas Audio 3.2SE: Analog / RCA
    Note over AN Meishu TM 300B,Abbas Audio 3.2SE: Cable: <br> Power: GigaWatt
    Holo May KTE->>Constellation Mini SE: USB (Titanis)
    Note over Constellation Mini SE,Holo May KTE: Cable: <br> Power: GigaWatt
    Abbas Audio 3.2SE->>Constellation Mini SE: SPDIF / COAX
    Note over Constellation Mini SE,Abbas Audio 3.2SE: Cable: <br> Power:
    Lumin U1->>Abbas Audio 3.2SE: SPDIF / COAX
    Note over Abbas Audio 3.2SE,Lumin U1: Cable: <br> Power:
    Lumin U1->>Holo May KTE: AES / EBU
    Note over Holo May KTE,Lumin U1: Cable: <br> Power:
    Constellation Mini SE->>SPEC RMP-UB1-KEX: Diretta Target (LAN-100Mbit/s)
    Note over SPEC RMP-UB1-KEX,Constellation Mini SE: Cable: <br> Power: Ferrum Hypsos
    activate SPEC RMP-UB1-KEX
    SPEC RMP-UB1-KEX->>Constellation Mini SE: Diretta Host (LAN-100Mbit/s)
    deactivate SPEC RMP-UB1-KEX
```
