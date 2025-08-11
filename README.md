# BankingApp 💰

A simple **Java Banking Application** with a **Swing GUI**.  
It supports **Deposit**, **Withdraw**, **Balance Check**, **OTP generation**, and **Transaction History storage**, with **PIN verification** for secure transactions.

---

## 📂 Project Structure

BankingApp/
│
├── src/
│ ├── core/ # Core banking logic
│ │ ├── BankAccount.java
│ │ ├── Transaction.java
│ │ └── BankingSystem.java
│ │
│ ├── gui/ # GUI components
│ │ └── BankingGUI.java
│ │
│ ├── utils/ # Utility classes
│ │ ├── OTPGenerator.java
│ │ └── DataStore.java
│ │
│ └── main/ # Application entry point
│ └── Main.java
│
└── data/
└── transactions.txt

---

## ✨ Features
- **PIN-based security** for deposit and withdrawal.
- **Deposit and Withdraw** with real-time balance updates.
- **OTP generator** for extra verification.
- **Transaction history** saved in `transactions.txt`.
- **Swing-based GUI** for user-friendly interaction.

---

## 🚀 How to Run
1. Clone or download the repository.
2. Open a terminal in the project folder.
3. Compile the project:
   ```bash
   javac -d bin src/main/Main.java src/core/*.java src/gui/*.java src/utils/*.java
java -cp bin main.Main

🛠 Requirements
Java JDK 8+

Any OS (Windows, macOS, Linux)

🔐 Default Credentials
Account Holder: Ramesh
Initial Balance: ₹5000
PIN: 1234

📌 Notes
The transactions.txt file will be created in the data/ directory automatically when transactions occur.

You can modify the PIN, initial balance, and account holder name in Main.java.

📜 License
This project is open-source and free to use.


<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c53f5a20-6bd9-4b61-88df-be49b955dd79" />

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/714fbb73-9f33-4a15-9284-943efc0d0538" />


<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/e173d1ce-fa98-40ff-aa9c-941d0a7eca38" />

