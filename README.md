# BoloKhaata – Your Business, Just a Voice Away

### Bas Bolo, Hisaab Ho Gaya! 

**BoloKhaata** is an AI-powered, multilingual digital business assistant designed for India's small shopkeepers, street vendors, micro-merchants, and independent business owners.

It simplifies everyday business management through voice commands, digital bookkeeping, customer credit tracking, invoice generation, business analytics, and government scheme discovery.

Our mission is to make digital financial tools accessible to every small business owner — even those who are not comfortable with traditional accounting software.

---

##  Why BoloKhaata?

Millions of small merchants in India still manage their daily business using paper registers, manual calculations, and informal credit records.

This creates challenges such as:
- Difficulty maintaining accurate daily transaction records.
- Losing track of customer credit (udhaar).
- Time-consuming invoice preparation.
- Limited understanding of business performance.
- Lack of awareness about government financial support schemes.
- Language and digital literacy barriers.

**BoloKhaata bridges this gap by turning everyday conversations into organized business records.**

##  Key Features

###  1. Voice-Powered Digital Khata
- Record sales, purchases, expenses, and customer credit using voice.
- Designed for Hindi, Hinglish, and English interactions.
- Convert spoken transactions into structured records.
- Review and confirm extracted information before saving.
- Manual transaction entry available as a fallback.

###  2. Smart Customer Ledger
- Maintain individual customer accounts.
- Track udhaar (credit), payments, and outstanding balances.
- View complete customer transaction histories.
- Monitor pending payments.

###  3. Invoice Generation
- Generate professional digital invoices.
- Add customer and item details.
- Calculate totals automatically.
- Download, print, and share invoices.

###  4. Business Dashboard & Analytics
- View total sales, expenses, and outstanding credit.
- Monitor daily and monthly business performance.
- Visualize transaction trends.
- Access important business information from one dashboard.

###  5. Government Schemes Discovery
Discover potentially relevant government support programmes, including:
- PM SVANidhi
- Pradhan Mantri Mudra Yojana
- PM Vishwakarma
- Other relevant central and state government schemes.

The system helps merchants explore indicative eligibility information and understand the documents they may need.

###  6. Micro-Credit Readiness Copilot
- Organize business transaction history.
- Generate business summaries using actual ledger records.
- Identify missing documents and information.
- Help merchants prepare for further loan application verification.

*BoloKhaata does not guarantee loan approval or provide official eligibility decisions.*

###  7. Inventory Management
- Maintain product and stock records.
- Track available quantities.
- Identify low-stock products.
- Monitor inventory changes.

###  8. Expense Management
- Record daily business expenses.
- Categorize expenditure.
- Understand income and expense patterns.

###  9. Payment Reminders
- Identify pending customer payments.
- Prepare payment reminder messages.
- Make it easier to follow up on outstanding udhaar.

###  10. AI Business Assistant
Ask questions about your business in natural language.

Examples:
- How much did I sell today?
- Which customers have pending payments?
- What were my expenses this month?
- Which products need restocking?

Responses should be grounded in the authenticated merchant's actual business records.

###  11. Offline-Friendly Experience
Designed to support merchants with unreliable internet connectivity through offline-friendly workflows and data synchronization.

---

##  Technology Stack

The application is designed around a modern full-stack architecture.

| Layer | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, FastAPI |
| Database | PostgreSQL |
| ORM | SQLAlchemy |
| AI Integration | LLM-based transaction understanding |
| Voice Processing | Speech recognition and natural |

 Application Workflow

Register or Log In: Merchants create an account and access their personal dashboard.

Start Using BoloKhaata: Open the voice-powered khata or select another business feature.

Speak Naturally: Enter a transaction using Hindi, Hinglish, or English.

AI Processing: Convert the voice input into structured transaction details.

Review and Confirm: Check the extracted information and correct it if needed.

Save Records: Store confirmed transactions in the merchant's digital ledger.

Analyze Business: Access invoices, customer balances, reports, and business insights.

 Target Users

Street vendors

Kirana store owners

Small shopkeepers

Local retailers

Home-based businesses

Micro-entrepreneurs

Independent service providers

 Our Impact

BoloKhaata aims to:

Promote digital financial inclusion.

Reduce dependency on paper-based bookkeeping.

Make business management accessible in local languages.

Improve transaction transparency.

Help small merchants organize their financial records.

Improve awareness of government support opportunities.

 Getting Started

Prerequisites

Install the following before running the application:

Python 3.10+

PostgreSQL

Git

A modern web browser

1. Clone the Repository

git clone https://github.com/aditi53789b-aaa/Bolo-Khaata.git

2. Navigate to the Project

cd Bolo-Khaata

3. Create a Virtual Environment

Windows PowerShell:

py -m venv venv

Activate it:

.\venv\Scripts\Activate.ps1

4. Install Dependencies

py -m pip install -r requirements.txt

5. Configure Environment Variables

Create a .env file in the appropriate backend configuration directory and add the required settings.

Example:

DATABASE_URL=postgresql://postgres:YOUR_PASSWORD@localhost:5432/bolokhaata
SECRET_KEY=your_secure_secret_key

Add the AI and voice-service API keys required by your implementation.

Never upload your .env file, API keys, or passwords to GitHub.

6. Set Up the Database

Create the PostgreSQL database and run the database initialization or migration commands provided by the project.

7. Start the Backend

Use the actual FastAPI entry point configured in your project.

For example:

uvicorn main:app --reload

8. Launch the Frontend

Open the frontend entry page in your browser or use the frontend server configured for the project.

Note: Commands may need adjustment according to the actual project directory structure and application entry points.

 Security & Privacy

BoloKhaata is designed with the following principles:

Secure password storage.

Authentication-protected business records.

Merchant-specific data isolation.

Validation of user inputs.

Protection of API credentials.

Confirmation before saving voice-extracted transactions.

Secure handling of customer and financial information.

 Future Enhancements

More Indian regional language support.

Improved voice recognition in noisy market environments.

WhatsApp-based receipt and payment reminder sharing.

Advanced business forecasting.

More government scheme integrations.

Improved offline synchronization.

Enhanced AI-powered business recommendations.

 Project

Project Name: BoloKhaata
Tagline: Bas Bolo, Hisaab Ho Gaya.
Category: AI | FinTech | Digital Inclusion | SaaS
Target Audience: Indian Micro and Small Businesses

GitHub Repository:
https://github.com/aditi53789b-aaa/Bolo-Khaata

We believe every small business deserves access to simple, intelligent, and affordable digital tools.

With BoloKhaata, managing a business should be as easy as having a conversation.

BoloKhaata — Empowering India's Small Businesses, One Voice at a Time.




