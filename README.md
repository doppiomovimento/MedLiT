# MedLiT-seed: An Ultralightweight Foundation Model for 2D Medical Imaging

MedLiT-seed is a compact, ultralight foundation model designed for efficient transfer learning and evaluation across 2D medical imaging tasks.  
This repository provides:

- The **MedLiT-seed** model  
- A ready-to-run **Google Colab evaluation notebook**  
- Full support for all **MedMNIST 2D datasets (224×224)**  
- Easy loading of pretrained weights through a single variable (`weight_path`)  

---

## 📥 Pretrained Weights

Download pretrained MedLiT-seed weights from:

[link to weights](https://drive.google.com/file/d/1C9hO6Nr3NdfPo3mBWkkDL6X4AFu814f_/view?usp=share_link)

The notebook expects that you unzip and upload the downloaded folder into your **Google Drive** and set the `weight_path` variable accordingly.

---

## 🧪 Running the Notebook

The notebook will:

- Install dependencies
- Load the pretrained MedLiT-seed model
- Evaluate performance across every MedMNIST 2D dataset

---

## 📜 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.
- You may use, modify, and redistribute the code
- Any public or network-facing derivative work must also be released under AGPL-3.0
- Users must be given access to the corresponding source code

---

## ⚠️ Institutional & Ethical Notice

MedLiT-seed is intended for **research and education**.
It is **not** a clinical diagnostic tool, medical device, or production medical AI system.
Users are responsible for dataset compliance, privacy, and ethical approvals where required.
