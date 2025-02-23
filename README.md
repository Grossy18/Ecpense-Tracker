# 💰 Personal Expense Tracker

## 📌 Overview
The **Personal Expense Tracker** is a web application that helps users manage their personal finances efficiently. It enables users to track expenses, categorize spending, and analyze financial trends with graphical reports.

## 🚀 Features
- Add, update, and delete expenses.
- Secure authentication using Spring Security.
- Categorize expenses for better tracking.
- Generate graphical reports (pie charts, bar graphs) using JFreeChart.
- Responsive UI for seamless user experience.

## 🛠️ Technologies Used
- **Backend:** Spring Boot, Hibernate, MySQL, Spring Security
- **Frontend:** HTML, CSS, Bootstrap
- **Charting:** JFreeChart for visualizing expense trends

## 📂 Project Structure
```
personal-expense-tracker/
│── src/            # Source code (Java, Controllers, Services)
│── resources/      # Configuration files, templates
│── public/         # Static assets (CSS, JS, Images)
│── pom.xml         # Dependencies and project setup
│── README.md       # Project Documentation
```

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/personal-expense-tracker.git
   cd personal-expense-tracker
   ```

2. **Set up MySQL Database:**
   - Create a new MySQL database: `expensetracker`
   - Update database credentials in `application.properties`

3. **Install dependencies and build the project:**
   ```sh
   mvn clean install
   ```

4. **Run the application:**
   ```sh
   mvn spring-boot:run
   ```

5. **Access the application:**
   - Open `http://localhost:8080` in your browser.

## 🌍 Deployment
### Deploy on AWS / Heroku / Render:
1. Push the project to GitHub.
2. Configure environment variables for database credentials.
3. Deploy using your preferred hosting service.

## 🏆 Future Enhancements
- Implement user budget limits.
- Add recurring expense tracking.
- Enhance reporting with additional charts and filters.

## 📜 License
This project is open-source and available under the **MIT License**.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📬 Contact
For any queries or suggestions, reach out at **amitghadage249@gmail.com**.
