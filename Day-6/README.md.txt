Day 6:

Session 1:

1)Selenium Automation with Python

  Installed Selenium and Chrome WebDriver.

  Walked through a simple Selenium automation script:

  from selenium import webdriver
  driver = webdriver.Chrome()
  driver.get("https://qxf2.com/selenium-tutorial-main")
  name = driver.find_element("xpath", "//input[@id='name']")# Find the name field and fill name
  name.send_keys('Deekshitha')
  driver.find_element("xpath", "//input[@name='email']").send_keys('deekshitha@qxf2.com')# Find the email field and fill your email
  phone = driver.find_element("id", "phone")# Find the phone no field and fill phone no
  phone.send_keys('9999999999')
  
  button = driver.find_element("xpath", "//button[text()='Click me!']")
  button.click()# Identify the xpath for Click me button and click on it


  Explained how to interact with web elements using Selenium.

Session 2:
 
 Introduction to Machine learning model.
 Built a Machine learning model to perform Twitter sentiment analysis.
 The model was trained to classify the tweets as positive or negative.
 
 Algorithm used:
 Linear Regression, Random Forest.

 Linear Regression :As a baseline model.

 Random Forest: For improved accuracy and better handling of classification.
 
 We trained and tested the model using preprocessed tweets data.



