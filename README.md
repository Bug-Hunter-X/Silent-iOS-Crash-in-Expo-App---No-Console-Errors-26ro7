# Silent iOS Crash in Expo App

This repository demonstrates a bug encountered in an Expo app where the app crashes silently on iOS devices without providing any error messages in the console logs. The app functions correctly on Android. The bug seems to be related to a timing issue or asynchronous operation and involves React Navigation and AsyncStorage.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `expo start`.
4. Test the app on both iOS and Android simulators or devices.

## Potential Solutions

The solution file explores strategies to identify and resolve the silent crash, focusing on asynchronous operations, error handling, and potential race conditions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have a solution or improvement.