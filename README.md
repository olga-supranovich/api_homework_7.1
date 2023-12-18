# api_homework_7.1

 This repository includes:
 - a Postman collection 'Change task' 
 - environment file 'verifier_cloud_homework_7.1.postman'
 
 Follow the steps below to get started.

## Prerequisites
1. **Postman Installed:** Make sure you have [Postman](https://www.postman.com/) installed on your local machine and Postman account created.
2. **GitHub Account:** Ensure you have an active GitHub account.
3. **Integrate Postman with GitHub:** follow instructions here [Integrate Postman with GitHub](https://learning.postman.com/docs/integrations/available-integrations/github/) - you'll need API sync with GitHub option. 

## Getting Started

### 1. Connect to GitHub collection
1. Select **APIs** in the sidebar and create new API.

2. Under **Connect repository**, select **Connect** and select **GitHub** repository.

3. A browser tab opens asking you to sign in to your repository. Follow the onscreen instructions. When you're finished, close the browser tab and return to Postman.

4. On the **Connect your GitHub repository** page back in Postman, enter  **Organization** 'olga-supranovich' and **Repository** 'api_homework_7.1'. Select **Initial branch** 'main'. Click **Connect Repository**.
5. To push/pull changes done to collection go to  **Source Control** (fork icon) on the left.

### 2. Set Environment Variables

1. From GitHub repository download file **verifier_cloud_homework_7.1.postman_environment.json** import it in Postman.
2. Select imported **sqlverifier-live-test** with the necessary variables. Remember variables are set on 2 levels:
   - **Environment Variables**: baseUrl, adminUser, adminPassword, token
   - **Collection Variables**: taskId, taskText, taskTextUpdated
   - **Local Variables**: currentDate, createdTaskDate 


