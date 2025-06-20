# Amharic E-Commerce NER Pipeline

This project is part of the 10 Academy KAIM Week 4 Challenge to build a Named Entity Recognition (NER) system that extracts structured business information (Product, Price, and Location) from unstructured Amharic text data shared in Telegram-based e-commerce channels.

## 📌 Project Tasks

### ✅ Task 1: Data Ingestion and Preprocessing

- Connect to at least 5 Ethiopian Telegram e-commerce channels.
- Scrape messages including text, images, and documents using a custom Telegram scraper.
- Tokenize and normalize Amharic text.
- Clean and structure the data into a unified JSON/CSV format, including metadata.
- Save cleaned data for labeling and modeling.

### ✅ Task 2: Labeling for NER (CoNLL Format)

- Select 30–50 representative messages.
- Label Product, Price, and Location entities using CoNLL tagging scheme.
- Save labeled data to `data/labeled/labeled_data.txt`.

## 🔗 Telegram Channels Used

1. @shager_onlinestore
2. @EthioProductStore
3. @EthiomartStore
4. @ZMallEthiopia
5. @ZenaMart
6. @AddisShopee

## 📁 Folder Structure

See the main directory structure inside this repository.

## 🧰 Dependencies

python-telegram-bot
telethon
pandas
regex
nltk
torch
transformers

## 📧 Contact

> Project by Alazar, KAIM Cohort 5 – Week 4..