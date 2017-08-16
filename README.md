# Login-With-Google
Google Login Sample application using react-native-google-sigin

# Reference Links
https://github.com/devfd/react-native-google-signin



# Steps
- Creat app 
  react-native init SiginSocial
  
- Install google-sigin
  npm install --save react-native-google-signin
  npm link
  
- I use Social Icons from react-native-elemensts
  npm install -save react-native-elements react-native-vector-icons

- Set up Project as show in the above reference link.

- After setting up, must to Google API console ==> https://console.developers.google.com
  And copy web client ID and update this in your application.

# Most Important Facts
- Make sure google-services.json configuration in your project directory (android/app/)
- Sign your app with your debug key (SHA-1)
- For the webClientId property, pass the Client ID from your Web Client.

# Fix DEVELOPER_ERR issue
https://github.com/devfd/react-native-google-signin/issues/98

