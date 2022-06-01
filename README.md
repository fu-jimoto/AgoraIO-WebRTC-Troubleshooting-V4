# Agora WebRTC Precall Test

Use this sample app to check if the following item works for Agora WebRTC before starting a call.

- Browser Compatibility
- Microphone
- Speaker
- Resolution
- Connection
- Camera (optional)

## Build and Run the Sample App

Ensure you have an Agora developer account and an App ID before using this app, see [Agora Account](https://docs.agora.io/en/2.3.1/product/Voice/Quickstart%20Guide/web_prepare?platform=Web#creating-an-agora-account-and-getting-an-app-id) for details.

1.  Fill your App ID in the `settings.js` file under **./src/utils**.
2.  Install dependencies:

    `npm install`

3.  To run the app locally:

    `npm run dev`

    Visit `localhost:8080` on your browser.

4.  Build the app for production:

    `npm run build`

    Built files need to be served over an HTTP server.

## Licence

MIT
