# 🚀 VibeLang Pro

**VibeLang Pro** is a lightweight, browser-based code editor and interpreter for the custom scripting language **VibeLang**. It combines a modern UI with interactive debugging, tab management, and real-time execution — all in a single HTML file.

---

## ✨ Features

* 🧠 **Custom Language (VibeLang)**

  * Simple, expressive syntax
  * Variables using `bag`
  * Output using `vibe()`
  * Input using `get()`
  * Control flow with `maybe`, `nah`, `end`
  * Loops using `spin`

* 🧾 **Multi-Tab Editor**

  * Create, switch, and close tabs
  * Persistent tabs using `localStorage`

* 🧮 **Live Code Execution**

  * Step-by-step execution with visual highlighter
  * Adjustable execution speed (Debug Slider)

* 🧰 **Developer Tools**

  * Undo / Redo
  * Beautify code
  * File upload & download

* 📊 **Side Panel**

  * **Console** → Output display
  * **Log** → Input tracking
  * **Bags** → Variable monitor

* 🎯 **Smart UI**

  * Line numbers + cursor position
  * Syntax-friendly editor (Fira Code font)
  * Responsive layout (desktop + mobile)

---

## 🧑‍💻 VibeLang Syntax Guide

### 📦 Variables

```
bag name = "John"
bag age = 21
```

### 🗣 Output

```
vibe("Hello World")
vibe("Hi #name")
```

### ⌨️ Input

```
bag name = get(What is your name?)
bag num = get(Enter number, number)
```

### 🔀 Conditional

```
maybe #age > 18 then
    vibe("Adult")
nah
    vibe("Minor")
end
```

### 🔁 Loop

```
spin i = 1 to 5
    vibe(#i)
end
```

---

## 🖥️ How to Use

1. Download or clone the repository
2. Open `index.html` in any modern browser
3. Start coding in VibeLang
4. Click ▶ **RUN** to execute

---

## 📁 Project Structure

```
vibelang-pro/
│── index.html   # Main app (Editor + Interpreter)
```

---

## ⚙️ Tech Stack

* HTML5
* CSS3 (Custom UI + Responsive Design)
* Vanilla JavaScript (No frameworks)

---

## 🧪 Example Program

```
bag name = get(What is your Name?)

maybe #name == "Shanthosh" then
    vibe("Welcome Back, Legend!")
nah
    vibe("Hi #name, Welcome to VibeLang!")
end
```

---

## 🔥 Future Improvements

* Syntax highlighting
* Error line detection
* Code sharing (export/import)
* Dark/Light theme toggle
* Plugin system
* VibeLang compiler version

---

## 🤝 Contributing

Feel free to fork, improve, and submit pull requests.
Ideas, issues, and feature requests are always welcome!

---

## 📜 License

This project is open-source and free to use.

---

## 💡 Author

Built with ❤️ by **Shanthosh Lakshman**

---

If you want, I can also:

* create a **GitHub repo description + tags**
* design a **logo for VibeLang Pro**
* or convert this into a **fancy README with badges + screenshots**
