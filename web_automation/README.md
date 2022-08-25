# Accumulus Web Automation Testing


Language: _Python 3.X_

Tool: _Pycharm, Selenium Webdriver_

Testing framework: _pytest_

Reporting: _allure_

Structure: _POM_ 

**Packages to be installed:**
Run a command in terminal `pip install -r requirments.txt`

**Command to run test from Pycharm Terminal:** 
`pytest -v -s <test file to be executed>`

**Command to run test in parallel from Pycharm Terminal:** 
`pytest -v -s -n <number of parallel executions> <test file to be executed>`

**Command to run test by specifying browser & Headless mode from Pycharm Terminal:**
`pytest -v -s --browser <CHROME,FIREFOX> --headless <True,False> <test file to be executed>`

**Command to generate allure report:** 
**`pytest --alluredir=path_of_reports_folder -v -s <test files to be executed>`**

**Command to view the allure report in browser:**
`allure serve <path_of_reports_folder>`
