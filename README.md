
# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

## 📌 Project Overview
HandsMen Threads is a forward-thinking fashion brand transforming its operations using a Salesforce-powered CRM platform. The main goal is to streamline business workflows, automate order-related communication, track inventory, and enhance customer loyalty through targeted engagement.

## 🎯 Key Features
- **Custom Salesforce Objects**: Customer, Order, Product, Inventory, and LoyaltyTier.
- **Order Confirmation Automation**: Flows send confirmation emails immediately.
- **Dynamic Loyalty Program**: Automatically update tiers based on purchase volume.
- **Proactive Stock Alerts**: Emails inventory staff when stock is low.
- **Scheduled Batch Processing**: Nightly Apex jobs process bulk data.

## 🧠 Technologies
- Salesforce Flow Builder
- Apex Triggers & Batch Apex
- Validation Rules
- Lightning App Builder
- Profiles & Permission Sets

## 📂 Data Model Structure
| Object      | Purpose                                     |
|-------------|---------------------------------------------|
| Customer    | Stores customer data                        |
| Order       | Manages purchases and statuses              |
| Product     | Catalog and pricing                         |
| Inventory   | Tracks stock levels                         |
| LoyaltyTier | Customer segmentation by purchase volume    |

## 🏗️ Architecture & Automation
- **Flows**: Order Confirmation, Loyalty Update, Stock Alert
- **Apex**: Triggers for order processing, Batch Apex for nightly jobs
- **Validation**: Address, quantity checks, email formatting

## 🚀 Getting Started
```bash
git clone https://github.com/Neerja13/Handsmen-Threads.git
```
Deploy to Salesforce org using SFDX or Change Sets. Setup metadata, users, and test flows.

## ✅ Benefits
- Automates workflows
- Timely customer communication
- Maintains data integrity
- Scalable Salesforce architecture

## 🌟 Learnings & Future Plans
- Learned Salesforce object modeling and flows
- Future: LWC, AI product suggestions, Einstein bots

## 📁 Project Structure
```
force-app/
  ├── objects/
  ├── classes/
  ├── triggers/
  ├── flows/
  ├── layouts/
  ├── profiles/
  └── email/
```

## 📌 Demo & Documentation
- [  ] Add demo video link
-  Documentation : [ https://drive.google.com/file/d/12TcshhYzd8vElja8tENb9-W_FVEgpvVh/view?usp=sharing ]

## 📬 Contributing / Feedback
Open an issue or pull request to collaborate or suggest improvements.

## 📝 License
For academic and learning use. Fork freely.
