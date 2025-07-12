# Gemini Workspace In Postman       

This project is aimed for the developers to interact with the Gemini API's through the Gemini Workspace in postman providing a central hub for exploration,integration and troubleshooting.This will reduce the 
initial learning curve to get started with the Gemini API's.

<img width="1920" height="1014" alt="image" src="https://github.com/user-attachments/assets/1ef1db7e-0066-4e95-9981-5bc7e268d37e" />

For a detailed walkthrough on getting started with this workspace and other onboarding videos, please refer to our [YouTube channel](https://youtube.com/@gemini-workspace?si=qhGk521dJ6MK4eS1).

# Get Started

## Step 1 : Fork the collection

You cannot directly make changes to the orignal collection , so you need to fork it first before using it. To fork the collection , simply click the fork button on the top right side.With the new update the developers can now send API requests without forking the workspace or collection. You can also click the below button to fork the collection.

<img src="https://content.pstmn.io/3a5b447d-6821-42c8-9218-87fcc06176ba/Zm9yayBpbWcucG5n">

## Step 2 : Getting the API key

To get started working with Gemini APIs, you must first be authorized to access them. The easiest way to authenticate to the Gemini API is to configure an API key.

1. Go to the [Google AI Studio ](https://aistudio.google.com/prompts/new_chat) and click on **Get API key button**.
    

<img src="https://content.pstmn.io/32c9c665-ad5a-4538-b86e-11b1c007c7fc/MXN0IEd1aWRlLnBuZw==">

2\. Click on **Create API key button** to create the API key.

<img src="https://content.pstmn.io/7c531cdf-2128-40ed-8f66-17a1acf126fb/R3VpZGUgMi5wbmc=">

3\. Copy the generated API key and you are good to go !

## Step 3 : Configure your API key in Postman Vault

Now that you have generated your API key , it's time to store it in **Postman Vault** so that it can be used as an authorization to access the Gemini API's and send requests.

#### Why we recommend storing your Gemini API key in Postman Vault ?

Postman provides a Vault for storing sensitive data locally. Data stored in this vault is not synced with Postman Cloud and can only be accessed in your local Postman Instance.

> We recommend using [Postman Vault](https://learning.postman.com/docs/sending-requests/postman-vault/postman-vault-secrets/) to store sensitive data. 
  

1. Click on the vault button present on the bottom right corner of the Gemini API collection or use the shorcut key : `Ctrl + Shift + V` to access the vault.
    

<img src="https://content.pstmn.io/e2006ad3-469d-4405-834c-d47061ec512d/U2NyZWVuc2hvdCAyMDI1LTA3LTExIDEzMDQzNS5wbmc=">

2\. After Opening Postman vault, paste your API key as a value to key - api key

<img src="https://content.pstmn.io/8057e938-19fe-45eb-a59f-a20481bd321f/aW1hZ2UucG5n" width="1381" height="437">

## Step 4 : Configure auth token and Project Id

Go to the Gemini - Testing Environment to store the Project Id and authentication token for your project.

<img src="https://content.pstmn.io/f88f1e74-33f2-46e0-b11e-26e0763dc8d0/aW1hZ2UucG5n" width="1331" height="746">

and now that you have configured the key , you can start exploring the collection !
