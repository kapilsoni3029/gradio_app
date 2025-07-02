
# 🚖🍔 Transport & Food Price Comparator Web App

This is a **Gradio-based Python web app** that allows users to **simulate price comparisons** for:

* Ride-hailing services (Uber, Ola, Rapido, InDrive)
* Food delivery platforms (Swiggy, Zomato, Zepto, Blinkit, Instamart)

> ✅ Great for demonstrating basic UI with Gradio
> 🚫 Note: This project uses *static/dummy data* — it does **not** fetch live prices.

---

## 🛠️ Features

* 🔹 Two-in-one app with tabs: **Transport** & **Food**
* 🔹 Friendly interface powered by **Gradio**
* 🔹 Accessible via **local** and **public link (gradio.live)** when launched
* 🔹 Neatly structured function design
* 🧪 Built for demo or prototype use

---

## 📂 Project Structure

```
.
├── transport_food_comparator.ipynb    # Main Jupyter Notebook
├── README.md                          # This file
```

---

## 📦 Requirements

Make sure Python 3.7+ is installed. Then install the dependencies:

```bash
pip install gradio
```

You do **not** need the OpenAI package unless you're integrating real models (not currently used).

---

## ▶️ How to Run

1. Open `transport_food_comparator.ipynb` using **Jupyter Notebook**, **Jupyter Lab**, or **VS Code**
2. Run all the cells
3. A Gradio interface will launch:

   * Local: `http://127.0.0.1:7861`
   * Public: `https://xxxx.gradio.live`

Use either to interact with your app!

---

## 🧩 Functionality

### 🚖 Transport Tab

* Input: `From Location`, `To Location`
* Output: Static price comparison from:

  * Uber
  * Ola
  * Rapido
  * InDrive

### 🍔 Food Tab

* Input: Food item name
* Output: Static price comparison from:

  * Swiggy
  * Zomato
  * Zepto
  * Blinkit
  * Instamart

---

## 🚫 Disclaimer

* This app uses **mock data** for educational/demonstration purposes.
* There is **no real-time API integration**.
* Any reference to company names is purely for demonstration and **non-commercial**.


