# Merchant-Payment-Operations-Mobile-App

Key Highlights of This Structure:

Expo Router is used properly with route groups (_auth), (_tabs) — very important for the JD.
Clean separation of concerns (API, Store, Hooks, Components).
Scalable for future additions.
Easy to maintain and show during interviews.


2. SmartPay - Merchant Wallet & POS App

Bashsrc/
├── features/
│   ├── wallet/
│   ├── pos/
│   ├── invoice/
│   └── offline/
├── components/
│   ├── pos/                # BigAmountInput, PayButton
│   ├── wallet/             # BalanceCard, QuickActions
│   └── invoice/            # InvoicePreview, PDFButton

2. SmartPay - Merchant Wallet & POS App
Recommended Extra Folders:
Bashsrc/
├── features/
│   ├── wallet/
│   ├── pos/
│   ├── invoice/
│   └── offline/
├── components/
│   ├── pos/                # BigAmountInput, PayButton
│   ├── wallet/             # BalanceCard, QuickActions
│   └── invoice/            # InvoicePreview, PDFButton
