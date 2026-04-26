# 🔐 Quantum OTP Authentication

## 📌 Description
A Flask-based authentication system that generates a secure OTP using concepts inspired by the BB84 quantum key distribution protocol.

The system also calculates QBER (Quantum Bit Error Rate) to detect possible eavesdropping.

## 🚀 Features
- Secure OTP generation
- QBER-based intrusion detection
- Quantum-inspired key exchange logic
- Clean and animated UI
- Simple login verification system

## 🛠️ Tech Stack
- Python
- Flask
- HTML & CSS

## ⚙️ How It Works
1. Random bits and bases are generated
2. Receiver measures with random bases
3. Matching bases form a shared key
4. QBER is calculated
5. If QBER is high → Eavesdropping detected
6. If secure → OTP generated

## ▶️ Run the Project
```bash
pip install flask
python app.py
