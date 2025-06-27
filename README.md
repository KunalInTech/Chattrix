# 💬 Chattrix - Java Real-Time Chat Application

A sleek, real-time **two-way messaging app** built using **Java Swing** for the GUI and **Java Socket Programming** for networking. Designed using a **Client-Server architecture**, this project allows two users to exchange text messages interactively — styled like modern messaging platforms.

---

## 🚀 Features

- 🖥️ WhatsApp-inspired GUI using **Java Swing**
- 📡 Real-time two-way communication with **Java Sockets**
- 🧵 Multi-threaded server for smooth interactions
- ⏱️ Timestamped messages for real-time feedback
- 🎨 Chat bubbles styled with `BoxLayout` & custom fonts
- 🔘 Clean UI with icons for back, video, phone, and more

---

## 🧠 Tech Stack

- **Java**
- **Java Swing**
- **Socket Programming**
- **Multithreading**
- **AWT/Event Handling**

---

## 🏗️ Architecture

```plaintext
+-----------+     Socket     +------------+
|  Client   | <============> |  Server    |
+-----------+                +------------+
| GUI (Swing)               | GUI (Swing)
| DataInputStream/Output    | DataInputStream/Output
| ActionListener            | ServerSocket Listener
