# App-Automation-on-EMI-Calculator-with-Appium-Selenium

## Scenario:
 If an user take loan (?) tk from a bank with interest of (?)% and  want to give (?) tk per month as EMI (installment) and processing fee (?)%, 
 how many time period it will take to complete the loan? Take the values from dataset and assert the monthly EMI, total interest, processing 
 fee amount and total payment from the result view. (See below image)

  For solve this question, create a dataset using following values:

  Amount | Interest | EMI | Processing Fee | Monthly EMI | Total Interest | Processing Fee | Total Payment | Period (Year) | Period (Month)

  100000 | 6 | 2000 | 2% | 2000 | 15361.08 | 2000 | 115361.08 | 4 | 10
  200000 | 8 | 5000 | 2% | 5000 | 33391.61 | 4000 | 233391.61 | 3 | 11

  250000 | 7 | 8000 | 1.5% | 8000 | 26804.51 | 3750 | 276804.51 | 2 | 11

  50000 | 10 | 1000 | 5% | 1000 | 14949.12 | 2500 | 64949.12 | 5 | 5
  
  ## Technology and Tools Used:
  - Selenium
  - TestNG
  - Appium
  - Android studio
  - Appium inspector
  - intellij idea
  - Gradle
  - Allure
  
  ## How to run this project:
  - clone this project

  - hit the following command into the root directory in terminal:
       - gradle clean test
  - For generating Report in Allure hit the following command
       - allure generate allure-results --clean -o allure-report
  - For view Report in Allure hit the following command
       - allure serve allure-results
       
  ## Allure Report:
  ![1](https://user-images.githubusercontent.com/71556293/230310657-832f5313-8c64-458d-9a97-2f239d7c9192.png)
![2](https://user-images.githubusercontent.com/71556293/230310682-937d3783-7b6a-4e45-91d8-4d12bf9f6f4b.png)
![3](https://user-images.githubusercontent.com/71556293/230310705-b2332a63-76af-4173-844f-0b52100f74db.png)
![4](https://user-images.githubusercontent.com/71556293/230310721-eaca9165-bc41-4ff7-bed2-452610637f19.png)
