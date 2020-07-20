## Description
### I'm trying to use [Official SectionList Example](https://reactnative.dev/docs/sectionlist) but it getting me the error on both RN 0.62.0 and 0.63.1:

![Screenshot from 2020-07-20 23-26-45](https://user-images.githubusercontent.com/9418556/87980556-0fd48c80-cae9-11ea-8a6e-8dcda5d38e16.png)
![Screenshot from 2020-07-21 00-15-38](https://user-images.githubusercontent.com/9418556/87980658-32ff3c00-cae9-11ea-87d1-1c88e6948012.png)


## React Native version:
```
System:
    OS: Linux 4.15 Ubuntu 18.04.2 LTS (Bionic Beaver)
    CPU: (8) x64 Intel(R) Core(TM) i7-4702MQ CPU @ 2.20GHz
    Memory: 1.05 GB / 11.65 GB
    Shell: 5.4.2 - /usr/bin/zsh
  Binaries:
    Node: 12.18.2 - /usr/bin/node
    Yarn: 1.22.0 - /usr/bin/yarn
    npm: 6.14.5 - /usr/local/bin/npm
    Watchman: 4.9.0 - /usr/local/bin/watchman
  SDKs:
    Android SDK:
      API Levels: 23, 24, 25, 26, 27, 28, 29
      Build Tools: 27.0.3, 28.0.2, 28.0.3, 29.0.2
      Android NDK: Not Found
  IDEs:
    Android Studio: Not Found
  Languages:
    Java: 1.8.0_252 - /usr/bin/javac
    Python: 2.7.17 - /usr/bin/python
  npmPackages:
    @react-native-community/cli: Not Found
    react: 16.13.1 => 16.13.1 
    react-native: 0.63.1 => 0.63.1 
  npmGlobalPackages:
    *react-native*: Not Found
```

## Steps To Reproduce
Provide a detailed list of steps that reproduce the issue.

1. react-native init RNSectionListError --template react-native-template-typescript
2. just put [https://reactnative.dev/docs/sectionlist](https://reactnative.dev/docs/sectionlist) example code in `App.tsx` and try to run.

## Expected Results
It's clear! render SectionList!
