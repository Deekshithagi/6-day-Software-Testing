Day 4:
Session 1:

Created a resume portfolio using Bootstrap.

Hosted the portfolio on Render (Deployment tool) with following steps:

1)Select GitHub to connect your repository.

2)Choose Web Services as the deployment option.

3)Select the repository which we want to host.

4)Use the following build command:
  pip install fastapi "uvicorn[standard]"

5)Use the following start command:
   uvicorn app:app --host 0.0.0.0 --port 8000

6)Choose the free plan (if available) to deploy the service.

7)After deployment, copy the provided URL to view the deployed application.


Session 2:
 
1) Installing FinTest Pro Extension
 Added test_main.py to the portfolio website folder.
 Used TestClient from fastapi.testclient to validate the homepage functionality.
2)Setting Up GitHub Actions for CI/CD
 Created a main.yml file to automate testing processes.
 Configured GitHub Actions to trigger on push events to the main branch or any other 
specified branch.
 Installed dependencies within the workflow.
 Executed tests using: 
 pytest test_main.py
3)Managing Dependencies
 Added FastAPI and pytest dependencies to requirements.txt for seamless 
integration and testing
