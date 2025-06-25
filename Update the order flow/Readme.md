# 🍽️ Food Ordering Bot – Google Dialogflow

This project is a conversational AI-powered Food Ordering Bot built using **Google Dialogflow**. It allows customers to interact naturally to place, update, or cancel food orders through voice or text.

## 🧠 Features

- **Place Your Order**: Users can select items, specify quantities, and confirm their orders.
- **Update Your Order**: Modify existing orders by changing items or quantities. The system validates the order using stored data.
- **Cancel Your Order**: Cancel orders with a simple command, validated against existing order records.

## 🔧 Technology Stack

- **Google Dialogflow (CX)** – Manages conversation flow and intent recognition.
- **Python Webhooks** – Handle backend logic for order validation, updates, and cancellations.
- **Google Cloud Run** – Hosts and executes webhook functions securely and scalably.
- **REST API** – Stores order details and supports validation during update and cancel operations.

## 📂 Project Structure

- Dialogflow agent with defined intents and flows
- Webhook backend for dynamic responses and validations
- Cloud Run deployment for serverless execution
- REST API for persistent order data management

## 📌 Use Case

Ideal for restaurants, cafes, and food delivery services aiming to automate their ordering process and enhance customer experience with a smart assistant.

## 📁 Project Materials

- **Presentation (PPT)** – Overview of the bot’s concept and implementation.
- **Flowchart** – Visual guide to the bot’s conversation and backend flow.

## 📄 Additional Documentation

More detailed information about each flow—**Place Order**, **Update Order**, and **Cancel Order**—is provided in the individual folders containing their respective `README.md` files.


