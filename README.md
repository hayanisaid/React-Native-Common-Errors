# The most common React Native errors and their solutions:

## 1 -  React Native : Error: Duplicate resources - Android
   **Solution** [source](https://stackoverflow.com/questions/53239705/react-native-error-duplicate-resources-android)
  ```
  rm -rf ./android/app/src/main/res/drawable-*

  rm -rf ./android/app/src/main/res/raw
  ```
## 2 - Error message "error:0308010C:digital envelope routines::unsupported"

   **Solution** [source](https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported)
  - For MacOS
  ```
  export NODE_OPTIONS=--openssl-legacy-provider
  ```
  - For Windows
  ```
  set NODE_OPTIONS=--openssl-legacy-provider
  ```
