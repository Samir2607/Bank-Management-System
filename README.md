The Bank Management System aka ATM Simulator System is a Java-based desktop application that simulates essential ATM functionalities such as account creation, deposits, withdrawals, mini statements, and PIN management. It provides an intuitive GUI interface using Java Swing and AWT, and stores all user and transaction data securely in a MySQL database.

👨‍💻 Author Name - Samir Kumar

🚀 Features
Open New Account: Register a new user with personal details and an initial deposit.

Deposit Money: Add funds to an existing account.

Withdraw Money: Withdraw cash while ensuring sufficient balance.

Mini Statement: View recent transactions.

PIN Change: Securely update your ATM PIN.

GUI Interface: Easy-to-use desktop interface built using Java Swing & AWT.

🛠️ Technologies Used
Component	Description
Language	Core Java
GUI	Java Swing and AWT
Database	MySQL
Database Access	JDBC (Java Database Connectivity)
IDE (Optional)	Eclipse / IntelliJ IDEA / NetBeans

🏗️ Project Structure
bash
Copy
Edit
ATM-Simulator-System/
├── src/
│   ├── Main.java
│   ├── AccountCreation.java
│   ├── Deposit.java
│   ├── Withdraw.java
│   ├── MiniStatement.java
│   ├── PinChange.java
│   └── DatabaseConnection.java
├── db/
│   └── atm_database.sql
├── README.md
📂 Database Schema
Database Name: atm_system

Tables:

users - Stores account and personal details

transactions - Logs deposit, withdrawal, and other activities

Sample schema and initial setup script is available in the db/atm_database.sql file.

🔧 Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/ATM-Simulator-System.git
cd ATM-Simulator-System
Import project into your preferred IDE.

Set up MySQL database:

Open MySQL Workbench or any MySQL client.

Run the SQL script in db/atm_database.sql to create tables.

Configure JDBC:

Update the database credentials in DatabaseConnection.java.

Run the application:

Execute Main.java to launch the application.

📸 Screenshots
(Add screenshots of your UI here – e.g., account creation, deposit screen, mini statement)

🧠 Interview Introduction (Self-Intro)
"I developed a Bank Management System, also known as an ATM Simulator System, using Core Java for the backend logic and Swing/AWT for the graphical interface. The system connects to a MySQL database using JDBC, and it simulates real-world banking features like creating new accounts, money deposits/withdrawals, generating mini statements, and PIN changes. It helped me solidify my knowledge of Java GUI development and database integration."

📌 Future Enhancements
Add login authentication with encrypted PIN storage.

Add support for transaction receipts (PDF).

Implement an admin dashboard to monitor all accounts.

Improve UI with JavaFX or web-based interface.

📃 License
This project is open-source and free to use under the MIT License.
