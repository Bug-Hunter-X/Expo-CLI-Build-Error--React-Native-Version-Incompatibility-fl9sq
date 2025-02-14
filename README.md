# Expo CLI Build Error: React Native Version Incompatibility

This repository demonstrates a common issue encountered when developing Expo projects: incompatibility between the Expo CLI and newer versions of React Native.

The project builds successfully using EAS Build but fails with the Expo CLI. This is because the Expo CLI might not support all the features and dependencies introduced in the latest React Native versions.

**Steps to reproduce:**

1. Clone this repository.
2. Try to build the project using `expo start`.
3. Observe the build error related to React Native version mismatch.
4. Try building with EAS Build (this should succeed).

**Solution:**

1. Update the Expo CLI to the latest version using `npm install -g expo-cli` or `yarn global add expo-cli`.
2. (If the above doesn't work) Check the compatibility matrix of Expo CLI and React Native versions to identify a compatible version of React Native for your Expo CLI.  You might need to downgrade your React Native version accordingly.