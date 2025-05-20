# Daliesque
🎨 Daliesque - Art Gallery Management System
---

### ✅ **Daliesque | Art Gallery Management System**

```markdown
# 🎨 Daliesque - Art Gallery Management System

**Daliesque** is a Java-based desktop application designed to manage art galleries. It allows users to handle artist profiles, artwork entries, and sales using a local MySQL database. The UI is built with Swing, and the database connection is managed via JDBC.

## 📌 Features

- CRUD operations on artists and artworks
- Customer management
- Sales tracking
- Java Swing GUI
- MySQL database integration
- Performance-optimized queries

## 🛠 Technologies

- Java
- Java Swing (UI)
- MySQL
- JDBC
- NetBeans (optional, for build)

## 📁 Project Structure

Art/
├── src/art/
│ ├── cusomerinfo.java
│ └── NewJFrame.java
├── build.xml
├── manifest.mf



> Note: There may be a typo in the filename `cusomerinfo.java` – it likely means `customerinfo.java`.

## 🛠 Database Setup

1. Create a MySQL database (e.g., `gallery_db`).
2. Import the SQL schema if available (`daliesque.sql`).
3. Update your DB credentials in the Java source code.

```java
// Example JDBC URL setup
String url = "jdbc:mysql://localhost:3306/gallery_db";
String username = "root";
String password = "your_password";
🚀 How to Run
Compile the Java source:


javac src/art/*.java
Run the main UI:

java art.NewJFrame
📸 Screenshots
(Include UI panels: artist info, artwork entry, sales dashboard if available)

📃 License
Hasin Md. Daiyan
