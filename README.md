
---

# Hotel Customer Service Desktop Application

A JavaFX-based hotel reservation and customer service desktop application.
It helps manage room bookings, profiles, admin tasks, and includes an AI-powered chatbot for real-time support.

---

## 📋 Features

✨ **For Customers**

* Room booking, modification, and cancellation.
* Profile management and booking history.
* Submit feedback and view FAQs.
* AI-powered chatbot (Langchain4j) to answer common questions.

✨ **For Admins**

* View and manage bookings, rooms, and customers.
* Handle modification requests and customer enquiries.
* Manage FAQs and update knowledge base.
* View ratings, feedback, and reports.

✨ **Technical Highlights**

* MVC Architecture.
* JavaFX UI with FXML (designed via Scene Builder).
* Data persistence using local CSV files.
* Event-driven UI interactions.

---

## 🖥️ Tech Stack

* **Frontend:** JavaFX, FXML, Scene Builder
* **Backend:** Java, File I/O, OOP
* **AI:** Langchain4j (AI-powered chatbot)
* **IDE:** IntelliJ IDEA
* **Tools:** Draw\.io (diagrams), GanttProject (timeline)

---

## 📂 Project Structure

```
src/
├── controller/   # JavaFX controllers
├── model/        # Entity classes & data handlers
├── view/         # FXML layouts
├── MainApp.java  # Application entry point
data/
├── users.txt
├── bookings.txt
├── faqs.txt
README.md
.gitignore
```

---

## 🚀 How to Run

1️⃣ Clone the repository:

```bash
git clone https://github.com/yourusername/hotel-customer-service-app.git
```

2️⃣ Open the project in **IntelliJ IDEA** or your preferred Java IDE.

3️⃣ Build the project and run:

```
MainApp.java
```

4️⃣ Ensure the `data/` folder (with `users.txt`, `bookings.txt`, `faqs.txt`) exists in the working directory.

5️⃣ Enjoy the application!

---

---

## 📖 License

For academic and learning purposes only.

---

