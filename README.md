# react-native-cardstack-view

[![npm](https://img.shields.io/npm/dt/react-native-cardstack-view.svg?style=flat-square)](https://www.npmjs.com/package/react-native-cardstack-view)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/amandeepmittal/eslint-config-amanhimself)
![code style expo](https://img.shields.io/badge/code%20style-expo-blue.svg)
![code style react-native](https://img.shields.io/badge/code%20style-react%20native-ff69b4.svg)

An easy way to add card stack view component to your iOS, Android and Expo application that uses React Native. ⚛️ + 📱

## Installation

**using Yarn**

```shell
yarn add react-native-cardstack-view
```

**using npm**

```shell
npm install --save react-native-cardstack-view
```

**react native link**

```shell
react-native link
```

## Usage

Example:

```js
import CardStackView from 'react-native-cardstack-view';

	<View style={styles.container}>
          <CardsView backgroundColor="#4545aa">
            <Text>Hola!</Text>
          </CardStackView>
			</View>
```

Note: it will not render correctly until you provide a `backgroundColor` prop. It accepts children props so you can manipulate and style the text inside accordingly.

![ss1](https://i.imgur.com/ilsnYB7.png)

## Built With

- Create React Native App
- React Native

## License

This project is licensed under the MIT License - see the LICENSE file for more details.
