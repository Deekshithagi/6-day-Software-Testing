Day 5:

Session 1: 
Virtual Environment, Git Workflow, and Selenium


1)Virtual Environment

  Explained the importance of using virtual environments in Python.

  Demonstrated how to create and activate a virtual environment:
  python -m venv myenv
  source myenv/bin/activate # macOS/Linux
  myenv\Scripts\activate # Windows

  Discussed installing dependencies within the virtual environment.

2)Git Workflow

  Covered essential Git commands: git init, git add, git commit, git push, and git pull.

  Discussed branching strategies, pull requests, and merging workflows.
 
  Demonstrated pushing a project to GitHub and managing repositories.

3)Selenium Automation with Python

  Installed Selenium and Chrome WebDriver.

  Walked through a simple Selenium automation script:

  from selenium import webdriver
  driver = webdriver.Chrome()
  driver.get("https://qxf2.com/selenium-tutorial-main") name = driver.find_element(by="id", value="name") name.send_keys("Qxf2")

  Explained how to locate and interact with web elements using Selenium.


Session 2: 
API Testing with Postman and Python Requests Library

1)API Testing Using Postman
  Introduced API testing fundamentals.
  Demonstrated sending GET and POST requests and validating responses.

2)API Testing with Python Requests Library
  Explained API testing using Python’s requests module.
  Executed API calls to a local server (http://127.0.0.1:5000/).

  Example GET request:
  import requests
  response = requests.get("http://127.0.0.1:5000/cars", auth=("qxf2", "qxf2")) 
  print(response.status_code)
  print(response.json())


  Example POST request to add a new car:
  response = my_session.post(url=base_url + 'cars/add', json={ 'name': 'Gwagon',
  'brand': 'Gwagon','price_range': '90-200lacs','car_type': 'sedan'}, 
  auth=(username, password))


  Implemented assertions to validate API responses:
  assert response.status_code == 201, 
  f"Expected status 201, got {response.status_code}" assert 'message' in response_content and 'successfully' inresponse_content['message'].lower(),
  "Car addition failed"


  Verified that the car count increased after adding a new entry.

