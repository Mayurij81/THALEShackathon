Our Idea Solution Prototype:
DOSSIER-DEFENDER
This project is a chatbot designed to enhance cybersecurity awareness. Built using Rasa, the chatbot helps users learn about various aspects of cybersecurity, including phishing attacks, strong password practices, multi-factor authentication (MFA), malware, data privacy, encryption, and more. It provides tips, answers frequently asked questions, and enables users to report issues such as phishing or data breaches.
As the THALES website does not have a chatbot as of 22nd November,2024 our ideation also gives a small suggestion :)


Features
User-friendly Interaction: Provides concise, easy-to-understand responses to cybersecurity questions.
Cybersecurity Tips: Offers guidance on strong passwords, MFA, firewalls, and encryption.
Reporting Issues: Allows users to report phishing attempts and suspected data breaches.
Prevention Advice: Explains how to avoid malware infections and protect sensitive data.
Customizable: Can be enhanced with further expert suggestions for better 

Tech Stack
Framework: Rasa Open Source
Programming Language: Python
Chat Interface: Custom HTML/JavaScript


Setup Instructions
1. Clone the Repository
bash
Copy code
git clone [https://github.com/yourusername/cybersecurity-chatbot](https://github.com/Mayurij81/THALEShackathon).git
cd cybersecurity-chatbot
2. Install Dependencies
Ensure you have Python 3.8+ and pip installed. Then, run:

bash
Copy code
pip install -r requirements.txt
3. Train the Chatbot
To train the model:

bash
Copy code
rasa train
4. Run the Rasa Server
Start the Rasa action server and core:

bash
Copy code
rasa run --enable-api
5. (Optional) Run Rasa in Interactive Mode
For testing and debugging:

bash
Copy code
rasa interactive
6. Integrate the Chatbot
Use the provided index.html file to integrate the chatbot into your website, or follow Rasa’s guides to connect to other platforms like Slack or Telegram.

Files in the Project
domain.yml: Defines intents, entities, responses, and configuration for the chatbot.
data/nlu.yml: Contains examples of user inputs for training the chatbot.
data/stories.yml: Defines conversation flows and expected user-bot interactions.
rules.yml: Specifies chatbot behavior for specific scenarios.
index.html: A simple custom-built chat interface for integrating the bot into websites.
README.md: This documentation.

How to Use the Chatbot
Sample Conversations
Greeting
Copy code
User: Hi
Bot:  Hello! I'm Dossier-Defender here to assist you with any questions or concerns about cybersecurity. 
        Whether you need tips to stay safe online, want to learn about best practices, 
        or have a specific concern, feel free to ask!

Ask for Tips


User: Can you give me some cybersecurity tips?
Bot: Sure! Use strong passwords, enable MFA, avoid clicking on suspicious links, and be cautious about public Wi-Fi.
Report a Phishing Attempt


User: I received a suspicious email. What should I do?
Bot: If you suspect phishing, report it to your IT department or forward the email to cybersecurity@domain.com.



Future Enhancements
Machine Learning: Improve intent recognition with additional training data.
Multilingual Support: Expand the bot to support multiple languages.
Advanced Security Checks: Integrate APIs for real-time URL or email analysis.
Contributing
Contributions are welcome! Follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Submit a pull request with a detailed description of your changes.
