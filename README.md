# Chat-With-RTX-typeScript-api

This project is a test of a chat with "Chat to RTX" API, the project is made with React and TypeScript, the project is a chat that sends a message to the server and receives a response, the project is made with the create-react-app template.

![Chat-With-RTX-typeScript-api](/res/capture.png)

## What is ChatRTX?

ChatRTX is a demonstration application that allows you to customize a large language model (LLM) GPT connected to your own content: documents, notes, videos, or other data. By leveraging retrieval-augmented generation (RAG), TensorRT-LLM, and RTX acceleration, you can query a customized chatbot for contextually relevant answers quickly. Since everything runs locally on your RTX Windows PC or workstation, you'll get fast, secure results.

You can find more information about ChatRTX in the following link: [ChatRTX](https://www.nvidia.com/en-us/ai-on-rtx/chatrtx/)

## API Documentation

**File**: chatApi.ts

**Description**: This class is used to send a message to the RTX chat server and get the response.

**Usage**:
```javascript
    const port = 5000;
    const queueManager = new chatApi(port);
    queueManager
        .sendMessage(message)
        .then((response) => {
            console.log("Server response: ", response);
        })
        .catch((error) => {
            console.error("Error:", error);
        });
```
## Available Scripts

In the project directory, you can run:

### `npm install`

Installs all the dependencies required for the project to run.\
This is a one time command to be run after cloning the project.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


