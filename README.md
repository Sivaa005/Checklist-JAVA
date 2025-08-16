# Checklist-JAVA
A simple desktop To-Do List Manager built using Java Swing. This project helps users add tasks, mark them as completed, and delete tasks in an interactive graphical user interface. It demonstrates the fundamentals of GUI development in Java with reusable components and event handling.

🚀 Features

➕ Add Tasks dynamically with a button

✅ Mark Tasks as Completed (strikethrough text with a checkbox)

❌ Delete Tasks instantly

📜 Scrollable Task Panel for handling multiple tasks

🧩 Reusable UI Components for modular design

🎨 Centralized Constants Class to manage GUI dimensions

🛠️ Tech Stack

Language: Java

GUI Toolkit: Swing (javax.swing, java.awt)

JDK Version: Tested on JDK 23


📂 Project Structure
To_Do/
│── CommonConst.java     # Centralized GUI size and layout constants

│── Todo.java            # Main JFrame with task panel and add button

│── TaskComponent.java   # Represents each task (checkbox + text + delete)

│── App.java             # Entry point to run the project
