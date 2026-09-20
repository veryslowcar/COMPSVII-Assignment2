## 1. What triggers this workflow to run? (Look at the on: section)
    When code is pushed to the main branch
## 2. What are the four main steps this workflow performs? (List each step name)
    Checkout code, Validate HTML files, Check links, Upload artifact
## 3. What does the "Checkout code" step do and why is it necessary?
    Gets code from the respository and its important because it uses actions/checkout@v4 
## 4. What is the purpose of the environment configuration?
    The purpose of the environment configuration is to output the website URL
## 5. How does this automated deployment improve reliability compared to manual deployment?
    This automated deployment improves reliability because the same process happens every single time code is pushed to the main branch
## 6. What would happen if you pushed code to a different branch (not main)?
    The workflow wouldn't work properly and the website wouldn't be deployed because it got pushed to a different branch.