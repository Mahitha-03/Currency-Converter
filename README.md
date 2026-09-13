# 💱 Currency Converter – Java Swing Application

A desktop-based **Currency Converter application** developed using **Java Swing**.

The application allows users to enter an amount, select the source currency and target currency, and calculate the converted amount using predefined conversion rates.

---

## 🚀 Features

### 💰 Currency Conversion

- Enter the amount to be converted
- Select the source currency
- Select the target currency
- Convert the amount using predefined exchange rates
- Display the converted amount using a pop-up message

### 🌍 Supported Currencies

The application currently supports:

- USD – US Dollar
- PHP – Philippine Peso
- INR – Indian Rupee
- AUD – Australian Dollar

### 🖥️ Graphical User Interface

The application provides a simple desktop interface using Java Swing components:

- Text field for entering the amount
- Dropdown menu for selecting the source currency
- Dropdown menu for selecting the target currency
- Convert button
- Message dialog for displaying the result
---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Java** | Core programming language |
| **Java Swing** | Graphical User Interface |
| **AWT** | GUI and event-handling support |
| **NetBeans IDE** | Development environment |

---

## 📁 Project Structure

```text
Currency-Converter/
│
├── screenshot/
│
├── CurrencyConverter.form
├── CurrencyConverter.java
├── CurrencyConverterJava.jar
│
├── README.TXT
└── README.md
```

### File Description

| File / Folder | Description |
|---------------|-------------|
| `CurrencyConverter.java` | Main Java source code containing the currency conversion logic and GUI |
| `CurrencyConverter.form` | NetBeans GUI form file |
| `CurrencyConverterJava.jar` | Executable Java application JAR |
| `screenshot/` | Project screenshots |
| `README.md` | Project documentation |
| `README.TXT` | Project information |

---

## ⚙️ Setup Instructions

### Prerequisites

Make sure you have:

- Java JDK installed
- NetBeans IDE
- Git

Check your Java installation:

```bash
java -version
```

Check the Java compiler:

```bash
javac -version
```

---

## 📥 Clone the Repository

Clone the project from GitHub:

```bash
git clone https://github.com/Mahitha-03/Currency-Converter.git
```

Navigate to the project:

```bash
cd Currency-Converter
```

---

## ▶️ Run the Application Using NetBeans

1. Open **NetBeans IDE**.
2. Select **File → Open Project**.
3. Select the `Currency-Converter` folder.
4. Open the project.
5. Open `CurrencyConverter.java`.
6. Run the application.

The Currency Converter GUI will open.

## 🔄 How It Works

```text
             User
               │
               ▼
        Enter Amount
               │
               ▼
       Select From Currency
               │
               ▼
        Select To Currency
               │
               ▼
         Click Convert
               │
               ▼
      Read Selected Currencies
               │
               ▼
       Apply Conversion Rate
               │
               ▼
       Calculate Final Amount
               │
               ▼
       Display Converted Amount


## 🖥️ User Interface

The application contains:

```text
Currency Converter

Amount:  [____________]

From:    [USD ▼]

To:      [INR ▼]

         [ Convert ]
```

The source and target currencies are selected through dropdown menus, and the result is displayed using a message dialog.

---

## 🔮 Future Enhancements

- Add more currencies
- Add a reset button
- Improve input validation
- Add more conversion combinations
- Add live exchange rates in a future version
- Improve the graphical interface
- Add conversion history

---

## 👩‍💻 Author

**Mahitha**

GitHub:

https://github.com/Mahitha-03

---

## 📄 License

This project was developed for educational and learning purposes.
