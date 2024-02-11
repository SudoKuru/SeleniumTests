# E2E Testing Frameworks

Mobile Testing Frameworks Options:

- [Maestro](https://maestro.mobile.dev/platform-support/react-native)
  - Integrates with expo go
  - In yaml so may not be able to handle our complex functionality
  - https://medium.com/lingvano/native-e2e-testing-with-maestro-and-expo-14e9e9b0f0fe


- [Detox](https://github.com/wix/Detox)
    - expo has guide for integrating
    - https://blog.expo.dev/testing-expo-apps-with-detox-and-react-native-testing-library-7fbdbb82ac87
    - https://docs.expo.dev/build-reference/e2e-tests/
    - potentially easier to run in pipeline than appium https://remarkablemark.org/blog/2023/02/18/how-to-run-react-native-detox-tests-on-github-actions/
    - https://github.com/calitb/expo-e2e-demo/tree/main

- [webdriverio](https://webdriver.io/)
    - supports web, apps through appium, and potentially some desktop applications
    - tried to get tauri example integration to work and it did not work

- [Robot Framework](https://github.com/robotframework/robotframework)

- [Nightwatchjs](https://github.com/nightwatchjs/nightwatch)



CI/CD Android and iOS

- May be able to get iOS simulator: https://github.com/futureware-tech/simulator-action
- https://forums.expo.dev/t/building-ios-app-without-paid-developer-account/67973/2
- https://docs.expo.dev/build-reference/simulators/