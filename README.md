
# Kidney Tumor Detection

This Project is to Detect Tumor or any other disease any CT scan given. i have made model a mutliclass CNN model to detect the Tumor.To run the application run this command locally:




## Run Locally

Clone the project

```bash
  git clone https://github.com/bot69dude/mlops_project.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```



## File data_ingestion.ipynb

after training the model run this command locally before running mlflow

```bash
  mlflow ui
```
after running the command you will see this page in the mlflow
![Screenshot (1)](https://github.com/bot69dude/mlops_project/assets/127757589/e0928732-240b-4aa4-9251-2732bd963547)

after running mlflow.set_tracking_uri('http://127.0.0.1:5000') you will recieve matrices page:
![Screenshot (4)](https://github.com/bot69dude/mlops_project/assets/127757589/d318454b-df92-4ca5-bee9-0e95df91f586)

after running mlflow.register_model you would be able to register your Model:
![Screenshot (2)](https://github.com/bot69dude/mlops_project/assets/127757589/d16b7c26-0fc1-4d82-ad96-230c95a2f852)

later it would be reached to production stage :
![Screenshot (3)](https://github.com/bot69dude/mlops_project/assets/127757589/f8a99411-6ff2-413d-bb4d-91c0f923dd14)



