# Oscar Enghag

```
Civ.ing. Datateknik · LTH (2025–)
Elektricitetsmekaniker · Försvarsmakten (2023–)
Lund, SE
```

Jag bygger saker som löser problem jag själv stött på. Ett urval — med bevis i stället för adjektiv:

| Projekt | Uppvisning |
|---|---|
| [kuvert](https://github.com/madlad-code/kuvert) | Eget krypterat överföringsprotokoll för LAN (X25519 → HKDF → ChaCha20-Poly1305, SAS-kod mot MITM; primitiverna från `cryptography`, aldrig egna). Tamper-testerna flippar bitar i chiffertexten och bevisar att överföringen avbryts. Hotmodellen dokumenterar även vad som *inte* skyddas. |
| [trailing_stop_loss](https://github.com/madlad-code/trailing_stop_loss) | 60 000 Monte Carlo-körningar med slumpad exit som kontrollgrupp: trailing stop sänker träffsäkerheten i 30/30 kombinationer men förbättrar svansrisken (CVaR₅) i 27/30. Slutsatsen följer datat — inte tvärtom. |
| [FS-Lap-Simulation](https://github.com/madlad-code/FS-Lap-Simulation) | Varvtidssimulator med Pacejka-däckmodell och lastöverföring, validerad mot FSG 2025: skidpad +5,4 %, medelfart inom publicerat intervall, acceleration +17 % — avvikelsen förklarad (modellen är 2WD, toppbilarna 4WD), inte bortförklarad. |
| [natvakt](https://github.com/madlad-code/natvakt) | Parsar rå ARP/mDNS/DHCP själv i stället för att wrappa nmap, och larmar när okänd MAC dyker upp på nätverket. Byggd för att köra dygnet runt på en Raspberry Pi. |
| [tender-scan](https://github.com/madlad-code/tender-scan) | Extraherar takvolymer ur eForms-XML och jämför mot faktiska avrop i ramavtal — beslutsunderlag ingen öppen databas sammanställer. Tesen validerad mot ett verkligt avtal innan koden skrevs. |
| [option_pricing](https://github.com/madlad-code/option_pricing) | Implied volatility-smile löst ur en riktig SPY-optionskedja (Brent), och variansreduktion med uppmätt effekt: kontrollvariat sänker standardfelet 2,6× — inklusive det oväntade resultatet att kombinationen med antitetiska variabler är sämre än kontrollvariat ensam. |

### Arbetssätt

```
docker compose up   är vägen in i varje repo
README              lovar aldrig mer än koden håller — Begränsningar-sektion i varje
tester              invarianter (energibalans, tamper, paritet), inte bara lyckliga exempel
```

### Stack

```
Hårdvara   SystemVerilog · FPGA (Cyclone V) · RISC-V RV32I · KiCad · kraftsystem
Nätverk    ARP/mDNS · scapy · protokolldesign · X25519/ChaCha20 · Docker
Analys     Python · NumPy · SciPy · optionsprissättning · Monte Carlo
Web        TypeScript · React · Vite · Netlify
```

### Bakgrund

```
2025–       Datateknik, LTH — algoritmer, systemarkitektur, hårdvara
2023–       Elektricitetsmekaniker · Försvarsmakten · A8/Livgardet
2025        Internship · Noda Intelligent Systems
```

---

[oscarenghag.netlify.app](https://oscarenghag.netlify.app) · `oscarenghag@gmail.com`
