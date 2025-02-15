# CartFlow-Testing
The application under test is CartFlow, an e-commerce platform.



## About the Project

> ***The TestNG script is designed to evaluate the functionality of a dummy e-commerce website. The script performs various tests, checking functionalities, and maintains an Excel file  to store the results of Sanity and Regression testing.***

## CartFlow Shopping Interface (Products page)
![image](https://github.com/iamsatyamyadav/Qkart_Automation_Project/assets/103804433/d365789f-f3e3-4432-9e53-c96144331f1f)




## During this project,
- Debugged failing test cases and issues with log statements
- Automated testing with selenium
- Utilised implicit and explicit waits correctly to avoid synchronisation issues
- Improved the tests with XPath
- Migrated tests to the TestNG test automation framework
- Performed Data-driven test automation with Apache POI


## Modularise test code and debug issues
### Scope of Work
- Modularised existing test code for readability and to avoid code duplication
- Fixed various bugs present in the existing code base for Register and Login pages
- Used IDE debugger with breakpoints to find and resolve issues faster
### Skills used
`Java`, `Selenium`, `Locators`, `HTML`, `Developer Tools`, `XPath`, `TestNG`




## Features

- Registration and login functionality testing
- Search box functionality testing
- Cart functionality testing
- Checkout functionality testing
- Contact us form functionality testing
- Advertisement functionality testing
- Privacy policy and about us functionality testing

# Setup

This project requires the following software and dependencies:

- **Java JDK 17.x.x:** Ensure you have Java Development Kit version 17 or above installed. You can download it [here](https://www.oracle.com/java/technologies/javase-downloads.html).

- **Gradle 8.x.x:** Make sure you have Gradle version 8 or above installed. You can download it [here](https://gradle.org/install/).

- **WebDriverManager:** To manage WebDriver binaries automatically. Add the WebDriverManager dependency to your project. More information can be found [here](https://github.com/bonigarcia/webdrivermanager).

- **Selenium:** The project relies on Selenium for automated testing. Ensure you have the latest version of Selenium WebDriver added to your dependencies. Details can be found [here](https://www.selenium.dev/downloads/).

- **TestNG Framework:** This project uses TestNG for test execution and reporting. Add the TestNG dependency to your project. Information can be found [here](https://testng.org/doc/).

- **Apache POI:** Used for updating Excel files. Add the Apache POI dependency to your project. Details can be found [here](https://poi.apache.org/).

### Example Gradle Dependency Configuration:

```gradle
dependencies {
    testImplementation 'org.testng:testng:7.5'
    // This dependency is used by the application.
    implementation 'com.google.guava:guava:31.1-jre'
    implementation group: 'io.github.bonigarcia', name: 'webdrivermanager', version: '5.6.2'
    implementation group: 'org.seleniumhq.selenium', name: 'selenium-java', version: '4.15.0'
    implementation group: 'org.apache.poi', name: 'poi-ooxml', version: '5.2.4'
}
```

> [!NOTE]
> Some of the dependencies may not work in furure. Update to their latest version

# Instructions

Clone/Download the code to your local machine. Pull the code stubs/Unpack the file. Open your terminal/shell. Navigate to the project folder in your terminal.

> ***For Windows:*** Execute the command in the terminal (command prompt or powershell).
```
gradle build
```
> ***For Mac/Linux:*** Execute this command in the bash terminal.
```
./gradlew run
```

Wait for some time and bingo! you will have the output in the file named `TestResult.xlsx` and the screenshots in the folder named `screenshots`.


## 🤝 Thanks for taking the time to view our project! We hope that you found it interesting and informative.
