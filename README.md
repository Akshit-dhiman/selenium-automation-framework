# Selenium Automation Framework

This project is a scalable test automation framework built using Selenium WebDriver and Java. It supports UI and API testing with reporting, parallel execution, and CI/CD integration.

---

## 🚀 Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- RestAssured (API Testing)
- Extent Reports
- Allure Reports
- Jenkins (CI/CD)
- Git

---

## 📌 Key Features

- Page Object Model (POM) design pattern  
- Data-driven testing using JSON  
- Cross-browser parallel execution  
- Retry mechanism for failed test cases  
- Integrated reporting (Extent & Allure)  
- Screenshot capture for failures  
- API testing using RestAssured  
- Email notification after execution  

---

## 📊 Reports Preview

### Extent Report
![Extent Report](https://user-images.githubusercontent.com/26399692/138960828-90e184a0-a354-43bc-b55d-c440b29b9d7a.png)

### Allure Report
![Allure Report](https://user-images.githubusercontent.com/26399692/135977881-10e654b4-6224-4aa9-8343-841af16aeeb3.png)

---

## 📂 Project Structure

- `src/main/java` → Page classes, utilities, core framework  
- `src/test/java` → Test cases  
- `resources` → Test data, config files  
- `reports` → Execution reports  

---

## ▶️ How to Run (Local)

1. Clone the repository  
2. Open in IntelliJ / Eclipse  
3. Run `testng.xml` as TestNG suite  

To generate Allure report:

```bash
allure serve allure-results
