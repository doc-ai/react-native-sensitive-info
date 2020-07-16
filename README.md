<img alt="GoStack" src="./cover.png" />



## DOC - AI version:

Modifications to getItem
# getItem 
Get Item will also grab from flutter secure store if you call it like this:
The key name is same as the key of test key in Flutter 

This branch will handle adding prefixes and unencrypting the flutter
```
sensitiveInfo.getItem('testKey', { sharedPreferencesName: 'FlutterSecureStorage' }).then(console.log);
```
Important not `getAllItem` will still return encrypted values

<center>

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![npm version](https://badge.fury.io/js/react-native-sensitive-info.svg)](https://badge.fury.io/js/react-native-sensitive-info)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![npm bundle size](https://img.shields.io/bundlephobia/min/react-native-sensitive-info)

</center>

# React Native Sensitive Info

`react-native-sensitive-info` manages all data stored in Android Shared Preferences, iOS Keychain and Windows Credentials. You can set and get all key/value using simple methods.

# Install

Install `react-native-sensitive-info` into your project using:

```bash
npm i -S react-native-sensitive-info
```

```bash
yarn add react-native-sensitive-info
```

# Docs

Check out the [docs](https://mcodex.github.io/react-native-sensitive-info/docs)

# Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://mcodex.github.io"><img src="https://avatars2.githubusercontent.com/u/5920613?v=4" width="100px;" alt=""/><br /><sub><b>Mateus Andrade</b></sub></a><br /><a href="https://github.com/mCodex/react-native-sensitive-info/commits?author=mcodex" title="Documentation">📖</a> <a href="https://github.com/mCodex/react-native-sensitive-info/commits?author=mcodex" title="Code">💻</a> <a href="https://github.com/mCodex/react-native-sensitive-info/pulls?q=is%3Apr+reviewed-by%3Amcodex" title="Reviewed Pull Requests">👀</a> <a href="#ideas-mcodex" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

# Contributing

Pull requests are always welcome :)