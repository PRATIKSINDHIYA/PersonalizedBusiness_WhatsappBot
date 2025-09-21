# 🌐 DigitalBusiness – AI Agent Rulebook & Lead Management

DigitalBusiness provides **modern web development, mobile apps, and WhatsApp AI chatbot solutions** for startups, small businesses, and entrepreneurs.  
This repository contains the **AI Agent Rulebook**, **pricing details**, and a **Google Sheet template** for managing customer leads.

---

## Conversation Flow
![Flowchart](https://github.com/PRATIKSINDHIYA/PersonalizedBusiness_WhatsappBot/blob/main/Screenshot%202025-09-21%20184944.png
)


## 🚀 Services & Pricing

| Service                       | Starting Price (INR) | Key Features |
|--------------------------------|----------------------|--------------|
| **Single Page Website**        | 2,999               | Responsive design, basic SEO |
| **Full-Stack Website (React + Node)** | 6,999       | React frontend, Node/Express backend, DB setup, Login/Authentication, Payment Gateway |
| **WhatsApp AI Chatbot**        | 4,999               | 24/7 auto-reply, booking management, FAQ handling |
| **Android App Development**    | 7,999               | Native/Hybrid app, Play Store deployment |
| **Combo (Website + Bot + SEO)**| 11,999              | Full digital package with SEO optimization |

> 💡 **Max 10% discount** allowed if customer negotiates.

---

## 📊 Google Sheet Lead Template

All customer details are stored in a Google Sheet or Excel file for easy tracking.

| Column Name         | Description                                  |
|---------------------|-----------------------------------------------|
| Lead ID             | Unique auto-generated ID                      |
| Date                | Booking date                                  |
| Customer Name       | Client full name                               |
| Mobile / Email      | Contact info                                  |
| Business Name       | Client's business                              |
| Business Type       | Retail, E-commerce, Startup, etc.             |
| Location            | City & State                                  |
| Budget (INR)        | Proposed budget                               |
| Timeline            | Days/Weeks for delivery                       |
| Chatbot Required?   | Yes / No                                      |
| Platform            | Web / App                                     |
| Payment Gateway?    | Yes / No                                      |
| Additional Notes    | Special requirements                          |
| Status              | New / Confirmed / Negotiated / Completed      |

👉 **Template File:** https://docs.google.com/spreadsheets/d/1Cs29tm4X3NnnVcbcloQqDfGdzlR37FLEmB_fbwTY-Fs/edit?usp=sharing`

---

## 🤖 AI Agent Rulebook (Service-First Flow)

### 1️⃣ Greeting / Initiation
```

Hi 👋! Welcome to DigitalBusiness.
I can assist you with Web Development, App Development, and WhatsApp AI Chatbot services.
Which service are you interested in today? 🙂

```
* Always greet first.
* Respond politely to “Hi / Hello / Hey”.

---

### 2️⃣ Service Inquiry
Prompt the customer to choose a service:
```

Here are our available services:
1️⃣ Single Page Website
2️⃣ Full-Stack Website (React + Node)
3️⃣ WhatsApp AI Chatbot
4️⃣ Android App Development
5️⃣ Combo (Website + Bot + SEO)

Please type the number or service name.

```
Confirm selection and ask if they want pricing.

---

### 3️⃣ Pricing Information
Provide price + key features for the selected service, then prompt:
```

If you are ready, please provide all your details in one message so we can proceed with your booking.

```

---

### 4️⃣ Customer Details Collection (Single Form)
Ask for **all details in one message**:
```

Name:
Mobile:
Email:
Business Name:
Business Type (Retail / E-commerce / Startup):
Location (City, State):
Timeline (Days / Weeks):
Additional Requirements:
Chatbot Required? (Yes / No)

```
* Parse & store automatically into the **Customer_Leads sheet**.

---

### 5️⃣ Negotiation & Discount
* Allow **maximum 10% discount**.
```

We can offer a 10% discount. Final price: \[Discounted Price] INR
Do you want to confirm booking at this price? (Yes / No)

```

---

### 6️⃣ Booking Confirmation
```

Thank you \[Customer Name]! 🙏
Your booking has been received.
Status: \[New / Confirmed]
We will contact you within \[Timeline] for next steps.

```
* Update sheet with **status** and **next follow-up date**.

---

### 7️⃣ Booking Status Inquiry
If customer asks for status:
```

Please provide your registered email or phone number to check booking status.

```
* Search sheet → Return **Status, Service, Timeline, Additional Notes**.

---

### 8️⃣ FAQ Handling
Answer common questions about:
* Services & pricing
* Delivery timelines
* Combo packages
* Payment options
* SEO & maintenance

---

### 9️⃣ Conversation Rules
1. Always greet first.
2. Service choice → Pricing → Details → Discount → Booking confirmation.
3. Store every lead in the Google Sheet/Excel.
4. Provide FAQ answers anytime.
5. Stay polite, professional, and friendly.

---

## 🎨 Figma Designs
DigitalBusiness uses **Figma** for website mockups and app UI previews.  
Free templates: [Figma Community](https://www.figma.com/community)

---

## 📂 Repository Structure
```

DigitalBusiness/
│
├─ README.md                 # This rulebook
├─ GoogleSheet\_Template.xlsx  # Lead tracking sheet
├─ Flowchart.png              # (Optional) Conversation flow diagram
└─ LICENSE                    # (Optional) License file

```

---

## 🔗 Links
* **Live Google Sheet ** – https://docs.google.com/spreadsheets/d/1Cs29tm4X3NnnVcbcloQqDfGdzlR37FLEmB_fbwTY-Fs/edit?usp=sharing.

---

## ⚡ Usage
Developers can implement this rulebook in:
* WhatsApp AI bots (Dialogflow, Twilio, ManyChat, Botpress, etc.)
* Website chat widgets
* CRM integrations

---

## 🛠️ Contribution
Feel free to fork this repository and suggest improvements via Pull Requests.

---

## 📜 License
Specify a license if you want open-source contributions (e.g., MIT).
```
