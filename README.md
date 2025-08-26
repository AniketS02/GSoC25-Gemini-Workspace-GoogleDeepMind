# Gemini Workspace In Postman       

This project is aimed for the developers to interact with the Gemini API's through the Gemini Workspace in postman providing a central hub for exploration,integration and troubleshooting.This will reduce the 
initial learning curve to get started with the Gemini API's.

<img width="1920" height="1014" alt="image" src="https://github.com/user-attachments/assets/1ef1db7e-0066-4e95-9981-5bc7e268d37e" />

For a detailed walkthrough on getting started with this workspace and other onboarding videos, please refer to our [YouTube channel](https://youtube.com/@gemini-workspace?si=qhGk521dJ6MK4eS1).

# Get Started

## Step 1 : Fork the collection

You cannot directly make changes to the orignal collection , so you need to fork it first before using it. To fork the collection , simply click the fork button on the top right side.With the new update the developers can now send API requests without forking the workspace or collection. You can also click the below button to fork the collection.

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman">](https://app.getpostman.com/run-collection/42721875-eefa27af-54f9-4bb6-884d-62cb16a58716?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D42721875-eefa27af-54f9-4bb6-884d-62cb16a58716%26entityType%3Dcollection%26workspaceId%3D3b07f56f-41b4-4561-b731-eec56c9fbaf6)

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