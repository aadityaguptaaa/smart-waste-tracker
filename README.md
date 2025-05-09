<img src="https://1.bp.blogspot.com/-N-XwxleEyOo/WYQEtqUZGnI/AAAAAAAAwRI/Klh5vIblR_EzyXjHsm1zh5WP3hWZMaciACLcBGAs/s1600/SRM%2BLogo.png" height=70>
<p align="center">
  <img src="https://raw.githubusercontent.com/aadityaguptaaa/smart-waste-management-system/main/assets/logo.png" alt="Smart Waste Management System Logo" height="70"/>
</p>

<h1 align="center">Smart Waste Management System</h1>



An intelligent and scalable platform for managing urban waste collection processes, developed during the 4th semester as part of the Database Management Systems (DBMS) coursework at SRM Institute of Science and Technology.



---

## 📚 About the Project

The Smart Waste Management System (SWMS) integrates a structured MySQL database with a web interface to optimize the collection, monitoring, and management of urban waste. The system enables features such as complaint registration, vehicle tracking, area-wise waste logging, and insightful analytics for administrators and authorities.

---

## 📑 Table of Contents


- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Database Schema](#-database-schema)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)


---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Bootstrap if used)
- **Backend:** Node.js / PHP (specify based on your project)
- **Database:** MySQL (`nfdb`)
- **Visualization:** Chart.js / Google Charts *(if used)*

---

## 📥 Installation

To set up the project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/aadityaguptaaa/smart-waste-management-system.git
cd smart-waste-management-system
```

### 2. Install Dependencies

Ensure Node.js is installed on your system. Then install project dependencies:

```bash
npm install
```

> If you're using another backend (e.g., PHP), skip this and configure your server environment accordingly.

### 3. Configure the Database

Open MySQL and execute the following commands:

```sql
CREATE DATABASE nfdb;
USE nfdb;
SOURCE sql/schema.sql;
```

Update your database credentials in the configuration file (`.env` or `config.js` / `config.php`) as per your environment.

### 4. Run the Application

Start the backend server:

```bash
node main.js
```

The application will be available at:  
👉 `http://localhost:3000`

---

## 🚀 Usage

- Login as an **Admin** or **User** using pre-defined credentials.
- Log and monitor waste data across various areas.
- Track collection vehicles and register complaints.
- Access dashboards with real-time charts and reports.
- Analyze and improve operational efficiency using data insights.

---

## 🧬 Database Schema

The system utilizes a relational MySQL database (`nfdb`) with the following key tables:

- **User** – Stores system users and their roles.
- **Area** – Defines locations/wards for waste management.
- **Vehicle** – Tracks collection trucks and assignment.
- **Waste_Produced** – Logs daily/weekly waste data by area.
- **Waste_Collection** – Records vehicle operations and dates.
- **Complaint** – Captures user grievances and feedback.

Key Features:

- Relational joins and normalization
- Views, triggers, and stored procedures
- Aggregate and analytical SQL functions

---

## 🤝 Contributing

We welcome contributions to improve the platform. To contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to your branch: `git push origin feature-name`
5. Submit a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Aaditya Gupta**  
B.Tech CSE Core – 2nd Year, 4th Semester  
SRM Institute of Science and Technology  
GitHub: [@aadityaguptaaa](https://github.com/aadityaguptaaa)
LinkedIn: [aadityaxgupta](https://www.linkedin.com/in/aadityaxgupta/)
