# 📌 Gradio Term Search App

A simple **Gradio-powered** application that allows users to **search for terms** and view their definitions dynamically. The app features **fuzzy search**, a **searchable table**, and a **dropdown selector** that updates dynamically based on relevance.

---

## 🚀 Features

✅ **Searchable Table** – Displays up to 10 terms at a time  
✅ **Fuzzy Matching** – Finds the **most relevant** term based on search  
✅ **Dynamic Dropdown** – Updates with the **top 10 most relevant terms**  
✅ **Automatic Selection** – First match is **auto-selected** in the dropdown  
✅ **Gradio UI** – Simple and intuitive user interface  

---

## 📸 Screenshot

![Gradio App Screenshot](https://via.placeholder.com/800x400?text=Gradio+Term+Search+App)  
*(Replace this with an actual screenshot from your app!)*

---

## 🛠 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/bashirsadat/gradiodf.git
cd gradiodf
```

### 2️⃣ Set Up a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # macOS & Linux
venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the app locally:
```sh
python grapp.py
```
Once running, Gradio will provide a **local and public link** where you can access the app in your browser.

---

## 📝 How It Works

1️⃣ **Search for a term** in the input box  
2️⃣ **Dropdown updates dynamically** with the top 10 closest matches  
3️⃣ **Click a term in the dropdown** to view its definition  
4️⃣ **The selected term & definition appear** in the text box  

---

## 📦 Project Structure

```
gradiodf/
│── grapp.py          # Main Gradio app
│── requirements.txt  # Dependencies list
│── README.md         # Project documentation
│── .gitignore        # Ignore unnecessary files
```

---

## 📜 Dependencies

This project requires:
- **Gradio** (`pip install gradio`)
- **Pandas** (`pip install pandas`)
- **RapidFuzz** (`pip install rapidfuzz`)

Install all dependencies using:
```sh
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to **open issues** or **submit pull requests**.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

👤 **Bashir Sadat**  
📧 Email: `sadat.sayedbashir@gmail.com`  
🔗 GitHub: [bashirsadat](https://github.com/bashirsadat)

---

### 🌟 If you find this project helpful, don’t forget to give it a star ⭐!
