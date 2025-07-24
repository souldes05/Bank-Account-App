# Bank-Account-App
Bank Account App 
🏦 Kenya National Bank App
A simple interactive banking simulation app built with Streamlit. It allows users to:

Create a bank account

Deposit and withdraw funds

Check their account balance

Ideal for beginner Python learners looking to understand classes, user input handling, and Streamlit UI development.

🚀 Features
✅ Easy account creation with auto-generated account numbers

💰 Real-time deposits and withdrawals with balance updates

🔐 Session-based account tracking (temporary memory)

📱 Clean and interactive Streamlit user interface

📸 App Preview

<sub>(Replace this with your own app screenshot)</sub>

🛠️ Technologies Used
Python 3

Streamlit

📦 Installation
Clone this repository

bash
Copy
Edit
git clone https://github.com/your-username/kenya-bank-app.git
cd kenya-bank-app
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install streamlit
Run the app

bash
Copy
Edit
streamlit run bank_app.py
🧪 How to Use
Launch the app using the command above.

Enter your name to create an account.

Choose one of the available options:

Deposit

Withdraw

Check Balance

To reset the session or simulate exit, click the Exit button.

📁 File Structure
plaintext
Copy
Edit
kenya-bank-app/
│
├── bank_app.py       # Main application file
├── README.md         # Project documentation
└── requirements.txt  # (Optional) Dependencies list
✅ Example Account Format
Name: John Doe

Generated Account Number: JOH7X9F2B1Q

Initial Balance: KSH 0.00

🔒 Notes
All account data is temporary and stored in memory (st.session_state). It resets once you refresh or close the app.

For persistent storage (e.g. database or CSV), enhancements can be added.

📌 To Do (Optional Enhancements)
 Add user login & authentication

 Save account data to a database or CSV

 Track transaction history

 Add mobile responsiveness with Streamlit styling

🙌 Author
Desmond Tutu
📧 Email: yourname@example.com
🔗 GitHub: @your-username

📄 License
This project is licensed under the MIT License.
Feel free to fork, modify, and share!
