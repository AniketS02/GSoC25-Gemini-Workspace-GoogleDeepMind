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

**References**

# **Models**

- [fetch model](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-2c5285fe-def2-49bf-b8fc-8cae0c84cbf4?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Text Generation

- [Generate Text from Text Input](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-ee884b1f-ce83-40bb-8d08-6d95285ffca1?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Thinking with Gemini 2.5](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-31c8313b-6765-4ab8-9df5-038f7d385e25?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [System Instructions](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-5fbdcaa5-447e-4419-86bb-10f463988e4a?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Multimodal Inputs](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-953f3bd1-d8be-4614-aa09-fbc5e58bf0fa?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Streaming Responses](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-1fd4b609-834c-4b4f-aa13-8efdebc7d1ec?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Multi-Turn conversations (Chat)](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-4d937806-1137-4428-80c8-3233ef2a7bd8?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Streaming Multi-turn conversations (Chat)](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-475c13e7-c9a8-4adf-aac8-cdcc77cb0179?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Variation Of Parameters

- [top_p variation](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-33815a1a-ad42-4317-8e57-754e92006fef?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [top_k variation](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-d8adef9a-3f16-4b16-ac1e-1cf0d1e9b147?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [temperature variation](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-e9198855-bd45-4b87-86e2-5eb4b7a66ba8?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [stopSequences variation](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-0a216c56-b2d2-4431-9df6-87fb3ac03702?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [maxOutputTokens variation](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-3c3f7da7-c0e6-4128-81b8-78777af6f003?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Image Generation

- Text-and-image-to-image
    
    - Using Inline Image
        
        - [Passing inline image data](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-c12d71e3-1abc-45a4-8122-45201d12125f?action=share&source=copy-link&creator=42721875&ctx=documentation)
            
    - Uploading images
        
        - [Image : 1.Get the upload url](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-7991759f-a5ae-46e9-9f58-2c96967d0c33?action=share&source=copy-link&creator=42721875&ctx=documentation)
            
        - [Image : 2.upload The Image](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-ee6b6849-a868-4b6a-b4dc-ea353e16f61f?action=share&source=copy-link&creator=42721875&ctx=documentation)
            
        - [Image : 3.Generate Content](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-b3655423-7d9a-44ec-be1f-82fb1c099b44?action=share&source=copy-link&creator=42721875&ctx=documentation)
            
    - [Text-to-image](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-f5215112-d924-4955-8cd2-6ef1d2e5901a?action=share&source=copy-link&creator=42721875&ctx=documentation)
        

# Imagen (Image Generation Model)

- [Futuristic Bear](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-568a73c8-2390-4334-a569-15e1887a5a76?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Veo (Video Generation Model)

- [Veo 3](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-e04fd203-0bb4-4f12-8de6-0b07994c0823?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Speech Generation

- [Single-speaker text-to-speech](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-f3abec7b-ddc0-40d2-a5d7-1c7cccfcc155?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Multi-speaker text-to-speech](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-183ef096-61c5-45cd-a9b2-80c4f55ac44c?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Structured Output

- [Configuring a schema](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-e24912f9-59e3-4f74-ba09-97310e2c5acd?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Thinking

- [Generating content with thinking](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-8f86b8e1-d26f-44d1-8046-69dd6db7a353?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Thinking budgets](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-75cd03c1-0db4-4b86-b0ba-e1ec36ec57d6?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Function Calling

- [Schedule Meeting](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-bd0d6a5d-b803-4349-b62c-d1ad8a4dcfa6?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Get Weather](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-b87f8110-2235-43e8-9c67-635ed0c50450?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Create Chart](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-943c3d55-da75-48fa-9aee-02c6a87108ff?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Document Understanding

- As Encoded PDF
    
    - [PDF Input](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-61f72545-6adb-4bc2-8fb1-af9bcc30adad?action=share&source=copy-link&creator=42721875&ctx=documentation)
        
- Upload PDF
    
    - [Document : 1.Get the upload url for PDF](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-8dd2f8aa-9eef-44c2-b6c6-e4cb5c46cfa0?action=share&source=copy-link&creator=42721875&ctx=documentation)
        
    - [Document : 2.Upload The PDF](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-df7ad886-79d6-489f-8124-129058293329?action=share&source=copy-link&creator=42721875&ctx=documentation)
        
    - [Document : 3.Generate Content](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-47a86465-4987-40b5-8c23-1975c3b0aedb?action=share&source=copy-link&creator=42721875&ctx=documentation)
        

# Image Understanding

- [1.Get the upload Url](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-1f25e88e-a6e3-4157-a60f-5c58562aa602?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [2.Upload The Image](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-149245f7-4878-4b0c-a7fd-cc004cda15bd?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [3.Generate Content](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-28a8f867-2a1d-4ae2-af3f-36718cd4ba55?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Video Understanding

- [Video : 1.Get the Upload url Video](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-962aecd6-69d1-4465-90a6-c52259541a44?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [2.Upload The Video](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-2df3e64e-44b9-499a-9bda-e2de2752f461?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [3.Generate Content](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-545c1ec9-9800-4067-9246-9dfaa5a72e98?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Audio Understanding

- [1.Get the Upload Url Audio](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-69ac26eb-583d-4edd-90c5-75a8e475b730?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [2.Upload The Audio](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-704b3c18-1a7b-453b-b2bb-7c2f3c8a84da?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [3.Generate Content](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-545c1ec9-9800-4067-9246-9dfaa5a72e98?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Code Execution

- [Enable Code Execution](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-398e3c86-5ac4-42f2-9579-cce34f853f81?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Use Code execution in chat](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-7ab02f71-d696-48ea-a228-95618e11f351?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Count Tokens

- [Text Token](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-d61c6499-403b-45bc-bda3-50d72f61f5b3?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Chat Token](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-8ca32a61-c544-4897-af4a-e87999185cbe?action=share&source=copy-link&creator=42721875&ctx=documentation)
    
- [Media Token](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-64e3c6f1-4e09-47d1-bac8-f720e5e9fad9?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# Tutorial

- [Chatbot](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-f25b7098-db5b-4e92-b4d9-eeec0b9bc65c?action=share&source=copy-link&creator=42721875&ctx=documentation)
    

# OpenAI Compatibility

- [Access Using OpenAI libraries](https://web.postman.co/workspace/%5BGSoC%5D-Develop-a-Gemini-Workspa~3b07f56f-41b4-4561-b731-eec56c9fbaf6/request/42721875-29fe6c50-bc99-430b-a314-6a1bf39a0c7a?action=share&source=copy-link&creator=42721875&ctx=documentation)

---
    
| Model variant | Input(s) | Output | Optimized for |
| --- | --- | --- | --- |
| [Gemini 2.5 Pro](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-pro)  <br>`gemini-2.5-pro` | Audio, images, videos, text, and PDF | Text | Enhanced thinking and reasoning, multimodal understanding, advanced coding, and more |
| [Gemini 2.5 Flash](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash)  <br>`gemini-2.5-flash` | Audio, images, videos, and text | Text | Adaptive thinking, cost efficiency |
| [Gemini 2.5 Flash-Lite](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash-lite)  <br>`gemini-2.5-flash-lite` | Text, image, video, audio | Text | Most cost-efficient model supporting high throughput |
| [Gemini 2.5 Flash Live](https://ai.google.dev/gemini-api/docs/models#live-api)  <br>`gemini-live-2.5-flash-preview` | Audio, video, and text | Text, audio | Low-latency bidirectional voice and video interactions |
| [Gemini 2.5 Flash Native Audio](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash-native-audio)  <br>`gemini-2.5-flash-preview-native-audio-dialog` &  <br>`gemini-2.5-flash-exp-native-audio-thinking-dialog` | Audio, videos, and text | Text and audio, interleaved | High quality, natural conversational audio outputs, with or without thinking |
| [Gemini 2.5 Flash Preview TTS](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash-preview-tts)  <br>`gemini-2.5-flash-preview-tts` | Text | Audio | Low latency, controllable, single- and multi-speaker text-to-speech audio generation |
| [Gemini 2.5 Pro Preview TTS](https://ai.google.dev/gemini-api/docs/models#gemini-2.5-pro-preview-tts)  <br>`gemini-2.5-pro-preview-tts` | Text | Audio | Low latency, controllable, single- and multi-speaker text-to-speech audio generation |
| [Gemini 2.0 Flash](https://ai.google.dev/gemini-api/docs/models#gemini-2.0-flash)  <br>`gemini-2.0-flash` | Audio, images, videos, and text | Text | Next generation features, speed, and realtime streaming. |
| [Gemini 2.0 Flash Preview Image Generation](https://ai.google.dev/gemini-api/docs/models#gemini-2.0-flash-preview-image-generation)  <br>`gemini-2.0-flash-preview-image-generation` | Audio, images, videos, and text | Text, images | Conversational image generation and editing |
| [Gemini 2.0 Flash-Lite](https://ai.google.dev/gemini-api/docs/models#gemini-2.0-flash-lite)  <br>`gemini-2.0-flash-lite` | Audio, images, videos, and text | Text | Cost efficiency and low latency |
| [Gemini 2.0 Flash Live](https://ai.google.dev/gemini-api/docs/models#live-api-2.0)  <br>`gemini-2.0-flash-live-001` | Audio, video, and text | Text, audio | Low-latency bidirectional voice and video interactions |
| [Gemini 1.5 Flash](https://ai.google.dev/gemini-api/docs/models#gemini-1.5-flash)  <br>`gemini-1.5-flash` | Audio, images, videos, and text | Text | Fast and versatile performance across a diverse variety of tasks  <br>Deprecated |
| [Gemini 1.5 Flash-8B](https://ai.google.dev/gemini-api/docs/models#gemini-1.5-flash-8b)  <br>`gemini-1.5-flash-8b` | Audio, images, videos, and text | Text | High volume and lower intelligence tasks  <br>Deprecated |
| [Gemini 1.5 Pro](https://ai.google.dev/gemini-api/docs/models#gemini-1.5-pro)  <br>`gemini-1.5-pro` | Audio, images, videos, and text | Text | Complex reasoning tasks requiring more intelligence  <br>Deprecated |

You can view the rate limits for each model on the [rate limits page](https://ai.google.dev/gemini-api/docs/rate-limits).

---

# How to use Gemini API mock server (Detailed Guide)

Postman mock servers simulate the behavior of a real API server, allowing for API development and testing without requiring the actual API to be live. They function by accepting requests and returning predefined responses based on examples saved within a Postman collection.

The mock server for this collection is :-

- Gemini API mock server (main collection) - [Gemini API mock server base URL](https://ec2df728-b79f-460b-bc9d-15f6015b309f.mock.pstmn.ioEndFragment)
    

Follow the steps below to make a mock request :

## Step - 1 :

Create a new request with method same as the method of the api request you want to mock. (Example - POST,GET,PUT,DELETE)

## Step - 2 :

Use the `Gemini API Mock Server Base URL` environment variable as an endpoint present in both Gemini-Testing and Mock Server Environment.

<img src="https://content.pstmn.io/aa17cc0e-a892-48e3-baba-d3c7dabc9a41/U2NyZWVuc2hvdCAyMDI1LTA4LTE2IDIzMzk1MC5wbmc=">

## Step - 3 :

Now, go to the example of the api request that you want to mock and copy the endpoint. Hit the send button along with all the neccessary things such as valid API key and response JSON.

<img src="https://content.pstmn.io/49ab75d7-0fde-4647-b4aa-8328d51e27dd/U2NyZWVuc2hvdCAyMDI1LTA4LTE3IDAwMjYzOC5wbmc=">

---

# 🛠️ Troubleshooting or Stuck ?

If you’re having issues:

- Double-check if your API key is correctly set in the testing environment
    
- Ensure you’ve selected the right environment. **Gemini-Testing Environment**
    
- Look for detailed errors in the **response body and console**
    

For a detailed walkthrough on getting started with this workspace and other onboarding videos, please refer to our [YouTube channel](https://youtube.com/@gemini-workspace?si=qhGk521dJ6MK4eS1).

**Watch this video**: [Getting Started with the Gemini Workspace](https://youtu.be/YETs9UNij1I)

---

# Ask for help

We want you to get the best support possible when working with this workspace. If you're stuck and need help with specific Gemini issues, we recommend that you explore the following channels.

- [Google AI Studio](https://aistudio.google.com/prompts/new_chat)
    

To test the Gemini models using the user interface

- [Gemini API docs](https://ai.google.dev/gemini-api/docs)
    

For detailed Understanding/Information of every capabilites of the Gemini Models.

- [Gemini Developer Forum](https://discuss.ai.google.dev/c/gemini-api/4)
    

For Postman specific questions or feedback about this workspace:

- [Postman's Community Forum](https://community.postman.com/t/ai-provider-workspaces-and-collections/74143) - Provide feedback and ask questions about this workspace, ask general Postman questions, understand how to use a feature, how to build a workflow, etc.
    

For Postman specific issues:

- [Postman Github Issues](https://github.com/postmanlabs/postman-app-support) - Submit feature requests, bug reports, etc here