# app-services
app service demo python code



# Step-by-Step to Deploy:
- Create a zip file (containing app.py, requirements.txt, runtime.txt)
- Upload zip using Deployment Center in Azure Portal
Configure App Setting:
    In Azure Web App → Configuration → Application settings
Add:
    - Name: AZURE_POSTGRESQL_CONNECTIONSTRING
    - Value: dbname=myflaskapp-database host=myflaskapp-server.postgres.database.azure.com port=5432 sslmode=require user=gqpetpxjkk password=idcPDsoMyk$V$qLr
- Save and Restart App Service
- Test: Open your Web App URL — your form will appear.
<img width="685" alt="image" src="https://github.com/user-attachments/assets/46f9c6c1-107e-41c8-8ea6-47868c04a644" />
