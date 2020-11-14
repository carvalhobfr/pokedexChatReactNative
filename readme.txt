
Running the app
yarn
react-native eject
react-native link react-native-dialogflow
react-native link react-native-voice
react-native run-android
react-native run-ios
cd server
nodemon server.js



APIs
export const dialogflowConfig = {
  "type": "service_account",
  "project_id": "XXX-XXXX-XXXX",
  "private_key_id": "XXXXX",
  "private_key": "-----BEGIN PRIVATE KEY----XXXXX\n-----END PRIVATE KEY-----\n",
  "client_email": "dialogflow-XXXX@XXXXX-XXX-XXXX.iam.gserviceaccount.com",
  "client_id": "XXXXXXXXXX",
  "auth_uri": "https://accounts.google.com/o/oauth2/auth",
  "token_uri": "https://oauth2.googleapis.com/token",
  "auth_provider_xxxx_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "https://www.googleapis.com/robot/v1/metadata/XXXX/dialogflow-XXXXXXX.iam.gserviceaccount.com"
}; 
