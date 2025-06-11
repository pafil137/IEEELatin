# Radio Duty-Cycle Aloha Protocol: A ContikiMAC Redesign for Tmote Sky Simulated in Cooja

**Manuscript ID:** IEEE LATAM Submission ID: 9443 
**Authors:**  
- Jonathan K. dos Santos Silva  
- Paulo F. Candido Barbosa  
- Renato M. de Moraes  

---

## 📁 Included Scripts

    This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.

| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| `grafico.ipynb` | Fig. Tests | Comparative graphs of Aloha with RDC and without RDC for one and two hops.|
| `confidence_interval.ipynb` | Figs. 7,8,9,10 | Energy consumption calculations: energy in joules per bit for each transmission. |

---

## 📂 Required Files Databases
`simulation-runs\`, `aloha-always-on\`, `aloha-rdc\` and `csma\`: These files are required by both `grafico.ipynb` and `confidence_interval.ipynb`. Place them in the same folder as the notebooks. Each file is standalone and does not depend on any additional resources.

Open database also available at: Jonathan Kilner dos Santos Silva, Renato Mariz de Moraes, Paulo Filipe Candido Barbosa, 'Energy Consumption Tmote Sky with Aloha Protocol on Contiki OS', IEEE Dataport, March 4, 2024, doi:10.21227/nrt4-jt03.
---

## 💻 Requirements
- Jupyter Notebooks or JupyterLab.
-- Examples using Google Colab, which allows you to run and edit .ipynb files directly in the browser.

---
## ✉️ Contact
For questions or replication of results:  
paulo.fcbarbosa@upe.br
