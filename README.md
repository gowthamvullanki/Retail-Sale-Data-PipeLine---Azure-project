Created Azure free Trail Account
 <img width="940" height="500" alt="image" src="https://github.com/user-attachments/assets/4560a642-ccd9-4f7d-85be-3f0ec0af4f87" />




CREATED RESORCE GROUP
 
<img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/f246002d-4ac6-4045-bf70-261d23c1749d" />





CREATED SERVER AND AZURE SQL DATABASE ATTACHED IT TO OUR RESORCE GROUP

 <img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/d9f7d4d3-684b-41cc-88e7-60c37726eaca" />






OPEN THE VULLANKIDB AND CLICK ON QUERY EDITOR

<img width="940" height="446" alt="image" src="https://github.com/user-attachments/assets/eb3ab9e5-ba71-4453-81eb-b430f962924b" />

 





CONNECT IT WITH YOUR USERNAME AND PASSWORD

<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/4f1a1eda-98f3-489a-bcbd-b3cc10f07322" />

 

CREATE TRASACTIONS, STORES AND PRODUCT TABLES

 <img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/979e0949-24a2-4e52-aa53-0953fcaebb14" />


CREATED STORAGE ACCOUNT

 <img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/6f4f1401-ed88-4e3f-a7b3-55b6e6cea88c" />





OPEN IT AND CLICK ON THE CONTAINER INSIDE DATA STORAGE:

 <img width="940" height="449" alt="image" src="https://github.com/user-attachments/assets/1a8a5f96-e5e2-420d-9982-74823e8e8abd" />


CREATED NEW CONTAINER ‘VULLANKI’ AND OPEN IT

 <img width="940" height="452" alt="image" src="https://github.com/user-attachments/assets/07de9b87-0d5a-4672-a766-de8d3f064a9d" />









Add directories bronze silver and gold

<img width="940" height="450" alt="image" src="https://github.com/user-attachments/assets/63c66bf6-ccff-4b54-ba45-10468ca586ab" />

 

Create inside in bronze
 
<img width="940" height="447" alt="image" src="https://github.com/user-attachments/assets/13c76508-9429-495b-bab1-865f9082c082" />







Create Azure data factory

<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/18db34f7-3253-40b4-8428-0b4810436500" />

 

Check ADF added in Resource group

 <img width="940" height="454" alt="image" src="https://github.com/user-attachments/assets/918b15d1-119b-46e1-b908-7d5bfb40cd30" />









Open ADF and click on launch Studio

 <img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/02954a85-7668-47fc-a863-36eb93118396" />



Click on the new pipeline inside the ADF

 <img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/0da457a8-8e78-436b-8f67-f5b095b010e2" />








Copy data
 <img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/035ee69a-7d7a-4e2e-8f8e-da3d3b58b83e" />


Here we are connect adf with azure sql database
 <img width="940" height="449" alt="image" src="https://github.com/user-attachments/assets/18984f0c-fb8b-4b08-b4dc-60a3686eecf8" />








After connection we need assign our table according to name
<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/fa297fe3-aaf0-41f7-b4fe-1cb5909c2907" />

 

Link it ADLS
<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/dd5b8d0e-7c6f-4005-b592-2511a854fabf" />

 








Format
<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/1fa51599-8d31-4408-82b6-e4de5e663250" />

 

Mention details of storage account
 <img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/759f4d55-c0dd-4cc9-9832-9a6725d23ceb" />








Open this
 <img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/96213457-6938-4b51-942b-417354438eb0" />





For Api data
 <img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/2133da55-f755-4977-976a-fdaab7578dc5" />






Give base url
<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/3bc64666-964e-4fa5-9371-38eac3f56f9a" />

 

Give main url
 <img width="940" height="452" alt="image" src="https://github.com/user-attachments/assets/d5079c2e-ce9d-425f-a0da-004e42566b3a" />










This is final pipeline we need debug and publish all
<img width="940" height="449" alt="image" src="https://github.com/user-attachments/assets/e9ab38fb-e474-4b62-8fed-73b30ff84f62" />

 

All scucceeded
<img width="940" height="456" alt="image" src="https://github.com/user-attachments/assets/a0d96150-d0f7-429c-99a4-5a0f05e926f7" />

 






We got data into our transaction in ADLS
<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/11608ed3-cae1-4f91-96df-9b6835170225" />


We use databricks to get data from Azure using mount and process it
<img width="1783" height="882" alt="ChatGPT Image Sep 10, 2026, 08_02_37 PM" src="https://github.com/user-attachments/assets/9aa5360a-a25e-4b15-9d03-5a8e3d6d24c0" />

We inject data into silver and gold layers in azure storage using databricks
<img width="1788" height="880" alt="ChatGPT Image Sep 10, 2026, 08_06_02 PM" src="https://github.com/user-attachments/assets/26f84a3b-3581-491c-a7d1-7eac3a582f08" />


Power BI

<img width="940" height="524" alt="image" src="https://github.com/user-attachments/assets/ffa71d7d-9ec8-46ec-a01b-5d6d08818b77" />








 


 

