# Queen-Katherine-token-QKTRN-
ERC 20 token with dynamic tax logic and loyalty rewards
#  Queen Katherine Token (QKTRN)

**QKTRN** is a custom ERC-20-compatible token designed to reward loyalty, discourage panic selling, and grow organically through narrative, scarcity, and ritualized mechanics. It features dynamic sell tax logic, a treasury-backed Security Pot, and modular architecture for future upgrades.

---

##  Overview

- **Token Name**: Queen Katherine
- **Symbol**: QKTRN
- **Decimals**: 18
- **Network**: Polygon (Mainnet or Mumbai)
- **Contract Type**: Custom ERC-20 with dynamic tax and reward logic

---

##  Key Features

- **Dynamic Sell Tax**  
  - 10% tax when price is at or below the floor  
  - 5% tax when price is above the floor  
  - Tax split: 50% to Security Pot, 50% to loyal holders

- **Security Pot**  
  - Accumulates half of sell tax  
  - Owner-controlled emergency withdrawal

- **Loyalty Rewards**  
  - Remaining tax is distributed proportionally to holders (excluding seller)

- **Manual Price Control**  
  - `setCurrentPrice()` and `setPriceFloor()` allow simulation of price dynamics pre-launch  
  - Future upgrade path includes oracle-based automation

- **Modular Design**  
  - Easy to extend with staking, governance, or oracle modules  
  - Clean separation of concerns for maintainability

---

##  Centralization Notes

This is an early-stage prototype. Current design includes:
- Owner-controlled minting and treasury withdrawal
- Manual price setting

These controls are intended for testing and early distribution. Future versions may include:
- DAO-based governance
- Multi-sig treasury control
- Automated price feeds

---

##  License

This project is licensed under the [MIT License](LICENSE).

---

##  Roadmap

- [x] Deploy to Polygon testnet
- [x] Verify and publish on Polyscan
- [ ] Add token logo and metadata to token lists
- [ ] Integrate price oracle (Chainlink or Uniswap)
- [ ] Launch staking and governance modules
- [ ] Community distribution and ritual design

---

##  Contributing

Pull requests and forks are welcome. If you’d like to contribute to the QKTRN ecosystem — whether through code, design, or myth-making — feel free to reach out.

---

##  Philosophy

QKTRN is more than a token — it’s a myth in motion. Inspired by historical systems of value, ritual, and sovereignty, it aims to grow not just through code, but through history.
