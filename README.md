# Spam_classifier_cpp
Spam Email Classifier with GUI using Hash Maps

# 📧 Spam Email Classifier (C++ + GTK GUI)

This project implements a **spam email classifier** using **hash maps** (chaining and open addressing) and a **GTK-based GUI** in C++. It classifies emails based on word frequencies learned from a dataset (CSV) and provides both classification and interactive visualizations.

---

## 🧠 Features

- 🔍 **Classify emails** as Spam or Not Spam using probability-based scoring.
- 🧱 **Two types of hash maps**:
  - Chaining (with linked lists)
  - Open Addressing (linear probing)
- 📊 **Dataset viewer** with filter and sort options.
- 🎨 **Highlighting of words** based on spam/ham contribution.
- ✏️ **Mark emails** manually as spam or ham to improve learning.
- ⚙️ **Adjustable spam threshold**.
- 📁 **Load emails** from `.txt` files.
- 💾 **Persist dataset** updates back to CSV.

---

## 🖥️ GUI Screenshot

> _Include a screenshot here if available (you can add one to the repo later)._  
Example:

![Screenshot](assets/screenshot.png)

---

## 📂 Project Structure
├── spam_filter.cpp # Main application source code
├── final.csv # Transposed CSV file with word frequencies
├── README.md # This file
├── .gitignore # Ignores object files and binaries


## 🛠️ Build & Run Instructions (Linux)

### 🔧 Prerequisites

- GTK 3 (`libgtk-3-dev`)
- g++ or any C++17-compatible compiler

### 📦 Install GTK on Ubuntu/Debian:
```bash
sudo apt-get update
sudo apt-get install libgtk-3-dev


🚀 Compile and Run:
g++ spam_filter.cpp -o spam_classifier `pkg-config --cflags --libs gtk+-3.0`
./spam_classifier

📁 CSV Format
"Word1","Word2","Word3",...
"SpamFreq1","SpamFreq2","SpamFreq3",...
"HamFreq1","HamFreq2","HamFreq3",...

🤝 Acknowledgements
GTK+3 for GUI components
Standard C++ STL
Data Structure inspiration from coursework on hashing

📜 License
This project is for educational purposes and is open to modification. Feel free to use it with credit.

✍️ Author
Kunal Jangid
B.Tech, Metallurgical & Materials Engineering
IIT Jodhpur


