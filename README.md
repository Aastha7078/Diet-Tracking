# Diet Tracking and Consultation System

A comprehensive Java-based application designed to help users track their daily food intake and receive personalized dietary consultation. This system provides a user-friendly interface for monitoring nutritional goals and maintaining a healthy lifestyle.

## 🚀 Features

- **User Authentication**: Secure login and signup functionality
- **Food Intake Logging**: Track daily consumption of calories, proteins, fats, and carbohydrates
- **Nutritional Summaries**: View detailed daily and weekly nutritional reports
- **Personalized Goals**: Set and monitor custom daily targets for all macronutrients
- **Dietary Consultation**: Receive recommendations based on logged intake and personal goals
- **Database Integration**: Persistent storage of user data, food logs, and nutritional goals

## 🛠️ Technology Stack

- **Programming Language**: Java
- **Database**: MySQL
- **Database Connectivity**: JDBC
- **Development Environment**: NetBeans IDE

## 📋 Prerequisites

Before running this application, ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- MySQL Server
- JDBC MySQL Connector

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aastha7078/Diet-Tracking.git
   cd Diet-Tracking
   ```

2. **Database Setup**
   - Start your MySQL server
   - Create a new database for the application
   - Update database connection details in `DatabaseConnection.java`

3. **Compile the application**
   ```bash
   javac *.java
   ```

4. **Run the application**
   ```bash
   java DietTracker
   ```

## 📖 Usage

1. **Login/Signup**: Create a new account or login with existing credentials
2. **Set Goals**: Configure your daily nutritional targets
3. **Log Food**: Record your daily food intake with detailed nutritional information
4. **View Reports**: Monitor your progress through daily and weekly summaries
5. **Get Consultation**: Receive dietary recommendations based on your data

## 📁 Project Structure

```
Diet-Tracking/
├── DietTracker.java        # Main application entry point
├── LoginPage.java          # User authentication interface
├── MainMenu.java           # Main navigation interface
├── DatabaseConnection.java # Database connectivity handler
├── README.md              # Project documentation
└── .gitignore             # Git ignore rules
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Development Status

This project is currently in development. The core structure has been established, and implementation of features is ongoing.

## 📞 Contact

For any questions or suggestions, please feel free to reach out through GitHub issues.

---

*This project is part of a learning initiative to create practical Java applications with database integration.*
