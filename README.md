# ci-cd-hackaton-cariel
CI/CD hackathon - 7/30/2025


This is a simple CI/CD pipeline automation project

The steps followed to achive this were:
1) Create an AWS S3 bucket and configure it to host a static html page
<img width="2097" height="519" alt="image" src="https://github.com/user-attachments/assets/36b55106-4d1e-46ae-9510-9d04fb757558" />

2) Create a Github repository with a simple HTML file to display a message
<img width="1172" height="392" alt="image" src="https://github.com/user-attachments/assets/e9a994a5-e082-4126-9ffc-b10ec4bbed57" />

3) Create an IAM User
<img width="403" height="275" alt="image" src="https://github.com/user-attachments/assets/1e1f77eb-0baf-4939-962f-c15bdad03718" />


4) Configure secrets in the repository
<img width="977" height="365" alt="image" src="https://github.com/user-attachments/assets/cc4c8fed-7620-41ec-8138-99885f02e7e5" />

5) Create an actions that triggers in a push and uploads the repository to the s3 bucket
<img width="738" height="775" alt="image" src="https://github.com/user-attachments/assets/1ddab8d1-e972-45ad-8a7c-99dc7ac7e3c6" />

6) Whenever you make a push, the action will trigger and the repository will be uploaded to the bucket
<img width="433" height="470" alt="image" src="https://github.com/user-attachments/assets/bde449e1-e95e-44c3-a22f-5b7d5102853b" />




 

