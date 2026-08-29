# Lyrahcle — Constellation Analytics

**Never Lies.**

A professional space-cybersecurity platform for assessing, monitoring, and defending space infrastructure: satellites, ground stations, RF links, TM/TC protocols, embedded firmware, and orbital telemetry.

**Open Core** — an open, auditable core (AGPLv3) plus paid enterprise modules.

---

## 🚀 What is Lyrahcle?

Lyrahcle provides a mission-console dashboard to monitor and defend space assets in real time. It combines orbital tracking, RF signal intelligence, protocol decoding, and threat intelligence in a single platform.

---

## 🔭 Key Features

- **Asset inventory** – domains, IPs, satellites, ground stations, firmware, by program.
- **Orbital tracking** – TLEs auto-synced from Celestrak; live lat/lon/altitude via SGP4, plotted on an interactive world map.
- **RF signal intelligence** – edge `sdr-agent` streams spectrum readings to the backend.
- **RF anomaly detection** – every reading is checked against that agent's baseline (z-score, 3σ threshold); outliers are flagged automatically.
- **TM/TC protocol decoding** – paste a hex frame and get parsed fields for AX.25, CCSDS Space Packet, PUS, or CubeSat Space Protocol (CSP v1).
- **Mission-console dashboard** – React + Tailwind, dark graphite/gold identity, live subsystem status, 8s auto-refresh.

---

## 🛠️ Technologies

Go · React · Vite · Tailwind · PostgreSQL · Redis · Docker · Kubernetes · SGP4

---

## 📚 Documentation

- [API Reference](https://github.com/Lyrahcle/lyrahcle/blob/main/docs/api-reference.md)
- [Forensics](https://github.com/Lyrahcle/lyrahcle/blob/main/docs/forensics.md)
- [Deployment](https://github.com/Lyrahcle/lyrahcle/blob/main/docs/deployment.md)
- [Configuration](https://github.com/Lyrahcle/lyrahcle/blob/main/docs/configuration.md)

---

## 🤝 Contributing

We welcome contributions! Please read our [contribution guide](https://github.com/Lyrahcle/lyrahcle/blob/main/CONTRIBUTING.md) before submitting pull requests.

---

## 🔒 Security

For vulnerability disclosure and hardening status, see:

- [Security Policy](https://github.com/Lyrahcle/lyrahcle/blob/main/SECURITY.md)
- [Security Roadmap](https://github.com/Lyrahcle/lyrahcle/blob/main/SECURITY_ROADMAP.md)

---

## 📄 License

- Core: AGPLv3
- Enterprise modules: Commercial
- Shared libraries: MIT

---

## 📫 Contact

- Maintainer: [mlko01](https://github.com/mlko01)
- Email: manu.ciberseguridad@gmail.com
- LinkedIn: [in/manulsf](https://www.linkedin.com/in/manulsf)

---

## 📌 Status

🚧 Pre-v1.0.0 — core features are shipped and in active hardening. See the [security roadmap](https://github.com/Lyrahcle/lyrahcle/blob/main/SECURITY_ROADMAP.md) for details.
