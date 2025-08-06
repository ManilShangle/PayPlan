# PayPlan – Chrome Extension for Managing BNPL Payments

> Helping Gen Z manage Buy Now, Pay Later (BNPL) debt through AI-powered automation and financial awareness.

## Overview

PayPlan is a Chrome extension that detects BNPL confirmations (like Klarna, Afterpay), extracts the payment plan using OCR, and syncs it to a built-in calendar and your Google Calendar. Users can also manually manage payments and customize their reminders.

### Features

- 🧠 **AI Detection**: Automatically detects BNPL confirmation pages using a custom PyTorch model
- 🔎 **OCR Extraction**: Pulls out total cost, vendor, and payment dates using Tesseract.js
- 📅 **Calendar View**: View and edit payment plans via an interactive calendar UI
- 🔁 **Google Calendar Sync**: All changes reflect in your personal Google Calendar
- 🛠️ **Manual Edits**: Add, edit, or delete any BNPL payment manually
- 🔒 **Privacy First**: No sensitive data is stored or transmitted

## Why I Built It

BNPL usage is skyrocketing, especially among Gen Z, but it's easy to lose track and fall into debt. I built PayPlan to give people seamless, intelligent tools to stay on top of their payments, reduce financial stress, and build better habits.

## Links

- [Read the full story](#)
- [Landing Page](manilshangle.github.io/PayPlanWebsite)
- Coming soon on the [Chrome Web Store](#)

## 🔐 Security & Privacy

- No data is sold or stored externally
- BNPL detection happens locally and server inference only runs image classification
- Google Calendar sync uses secure OAuth2 via Google Cloud

## 👨‍💻 Author

Built by Manil Shangle
[LinkedIn](https://www.linkedin.com/in/manilshangle) • [GitHub](https://github.com/ManilShangle) • [Support Page](manilshangle.github.io/PayPlanWebsite/support.html)