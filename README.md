# 🛒 Online Shopping Chatbot

This project is an Amazon Lex chatbot named **OnlineShoppingBot** designed to assist users with online shopping. It collects customer details, guides users through product selections, and provides a personalized shopping experience.

## 🎯 Features
- Collects basic customer details (Name, Email, Contact Number, Address).
- Offers product selections from various categories like Electronics, Clothing, Home Appliances, Beauty products, groceries etc.
- The bot suggests products based on user preferences.
– Users can add/remove products before checkout.
Captures customer details and finalizes purchases.
- Uses advanced Amazon Lex features for a seamless conversation flow.

## 🛠️ Tech Stack & Tools
Technology	Usage
Amazon Lex	Natural Language Understanding (NLU) for chatbot interactions
AWS Lambda	Backend processing & API integration
DynamoDB	Storing user data and order details
Flask	Web integration for chatbot
Python	Backend scripting & API calls (boto3, requests, json)

## 🚀 Getting Started
1. Clone the Repository
```sh
git clone https://github.com/Apoorva-Bhat23/OnlineShoppingBot.git
cd OnlineShoppingBot
```
2. Install Dependencies
```sh
pip install -r requirements.txt
```
3. Deploy to AWS
Configure AWS CLI:
```sh
aws configure
```
Upload Lambda functions & deploy Lex bot:
```sh
aws lex-models put-bot --name OnlineShoppingBot --cli-input-json file://bot_config.json
```
4. Run Locally
```sh
python app.py
```
Then open http://localhost:5000 in your browser.

## 🎯 Future Enhancements
- Voice Shopping Integration – Support for Alexa & Google Assistant
- Payment Gateway – Secure checkout via Stripe/PayPal
- Multilingual Support – Expand bot capabilities for different languages

## 📜 License
This project is licensed under the MIT License.
