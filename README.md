# Simbox Tracking Platform (Cyber Warrior Hackathon 2025 – Team Exodia)

🚀 Finalist project (Top 20 / 110+ teams, 520+ participants) at Thailand’s national cybersecurity hackathon.

## 📌 Overview
Fraudulent call center gangs often use **Simbox (GSM Gateway)** to rotate SIM cards and disguise international calls as local.  
This project proposes a **geo-locating Simbox detection platform** that integrates:

- **GIS analysis**: suspicious area heatmaps from cell tower + call data
- **IMSI Catcher (StingRay)**: field device to intercept IMSI of suspicious SIMs
- **Cellular Triangulation**: precise localization of Simbox in target areas:contentReference[oaicite:2]{index=2}

## 🔑 Key Features
- Suspicious call behavior detection (abnormal call volume, SIM rotation)
- Location approximation from Cell ID + triangulation:contentReference[oaicite:3]{index=3}
- Heatmap visualization for risk area mapping
- Automatic alerts to authorities
- Field operation support with IMSI Catcher

## 🏆 Hackathon Results
- Selected as **Top 20 Finalist** in Cyber Warrior Hackathon 2025  
- Presented workflow, technical + security implications to national-level judges

## 📄 Documents
- [📑 Final Proposal (PDF)](docs/Simbox_Proposal.pdf)  
- [🎞️ Presentation Slides](docs/Simbox_Presentation.pdf)

## 🔬 Future Work
- Integration with real telco data feeds
- AI/ML for anomaly detection
- Expansion to cross-border criminal investigation support

## 📜 Citation
If referencing, please cite:

```bibtex
@misc{Exodia2025Simbox,
  title = {Simbox Tracking Platform using GIS, IMSI Catcher and Cellular Triangulation},
  author = {Exodia Team},
  year = {2025},
  note = {Cyber Warrior Hackathon Finalist Project},
}
