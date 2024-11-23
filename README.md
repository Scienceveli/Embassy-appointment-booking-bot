# **Automated Visa Appointment Bot** ✈️💳

# [![Bot Icon](https://raw.githubusercontent.com/Scienceveli/Embassy-appointment-booking-bot/main/image.png)](https://www.goxvisa.com/) Automated Visa Appointment Bot ✈️💳

---

### **Overview**

This project is an **Automated Visa Appointment Bot** that simplifies the process of booking appointments for work visas (Visa D) via platforms like **GoxVisa**. The bot automatically logs in, fetches available appointment slots, and returns the data to users via Telegram with a simple command.

---

### **Key Features**

- **Automated Login:**  
  - Logs into your account on **GoxVisa** automatically using your credentials.

- **Real-Time Appointment Retrieval:**  
  - Fetches available appointment slots for work visas (Visa D).

- **User-Friendly Interface:**  
  - Available via **Telegram**, allowing users to get appointment slots with a single command.

- **Secure Data:**  
  - Credentials are securely stored in an `.env` file to prevent exposure.

- **Notification Alerts:**  
  - Example Notification:  
    🇪🇬 **Cairo**  
    🛂 **Short Stay Visa - Type C**  
    🏖️ **Tourism**  
    ⏰ **Time:** 11:49:26  
    🔔 **Reminder:** Available now!

---

### **How to Use**

1. **Setup:**  
   Clone the repository and navigate to the project folder.
   ```bash
   git clone https://github.com/Scienceveli/automated-visa-appointment-bot.git
   cd automated-visa-appointment-bot
   ```

2. **Install Requirements:**  
   - Make sure you have Python installed.
   - Install required libraries using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure:**  
   Create a `.env` file in the root directory and add your **GoxVisa** login credentials:
   ```text
   USERNAME=your_username
   PASSWORD=your_password
   ```

4. **Run the Bot:**  
   Start the bot by running:
   ```bash
   python telegram_bot.py
   ```

5. **Interact with the Bot:**  
   - Use `/appointments` to get available appointment slots.

---

### **Technologies Used**

- **Python** – Programming language used for development.
- **Selenium** – Web automation for login and appointment retrieval.
- **Telegram API** – For building the Telegram bot.

---

### **How It Works**

- **Login Automation:**  
   The bot logs in automatically using the credentials stored in the `.env` file.

- **Fetch Appointments:**  
   The bot accesses the appointments page and retrieves available slots for Visa D appointments.

- **Telegram Interaction:**  
   The bot responds to commands such as `/appointments` and displays the available dates.

---

### **License**

This project is licensed under the MIT License - see the LICENSE file for details.

---

## **Contact for Purchase**

If you're interested in purchasing the project or have any inquiries, feel free to reach out to me directly:

- **Name:** Ahmed Samir  
- **Phone:** [📞 +201029107547](tel:+201029107547)  
- **Facebook:** [🧑‍💻 sciencael](https://www.facebook.com/sciencael)

Looking forward to hearing from you!

---

### **Demo Video**

You can watch the bot in action here:  
[Watch the Demo Video](https://www.youtube.com/watch?v=Z0MhodgYfmc)
```

This is a professional and well-structured description for your GitHub README. It explains the bot's functionality, how to use it, and provides contact information for purchasing or inquiries.
