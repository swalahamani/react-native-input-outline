# React Native Input Outline

A performant TextInput with fully configurable options 🚀

![React Native Bottom Sheet](./mockup-1.gif)

I built this library because of all the performance issues I noticed in other TextInput libraries.
This library is extremely performant thanks to Reanimated v2. Leave a star if you enjoy it!

Performant React Native TextInputs built with Reanimated 2.

## Installation

```sh
yarn add react-native-reanimated@2.0.0-rc.0 react-native-input-outline
```

Reanimated v2 is required for this library to work.

## Usage

```js
import { InputOutline } from 'react-native-input-outline';

<InputOutline />;
```

All vanilla [ReactNative TextInput Props](https://reactnative.dev/docs/textinput#props) are supported as well as others configured from this library shown below.

### Props

|                Prop | Desription                                                                                                                                                                                              | Default   | Type                                                            |
| ------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | --------------------------------------------------------------- |
|   `TextInput Props` | Inherited Props                                                                                                                                                                                         |           | [TextInput Props](https://reactnative.dev/docs/textinput#props) |
|       `placeholder` | The string that will be rendered before text input has been entered.                                                                                                                                    |           | `string`                                                        |
|          `fontSize` | Font size for TextInput.                                                                                                                                                                                | `14`      | `number`                                                        |
|   `paddingVertical` | Vertical padding for TextInput Container. Used to calculate animations.                                                                                                                                 | `12`      | `number`                                                        |
| `paddingHorizontal` | Horizontal padding for TextInput Container.                                                                                                                                                             | `16`      | `number`                                                        |
|       `activeColor` | Color when focused.                                                                                                                                                                                     | `'blue'`  | `string`                                                        |
|     `inactiveColor` | Color when blurred (not focused).                                                                                                                                                                       | `'black'` | `string`                                                        |
|        `errorColor` | Color that is displayed when in error state.                                                                                                                                                            | `'red'`   | `string`                                                        |
|             `error` | Error message to be displayed. If anything is provided to error besided null or undefined, then the component is within an error state, thus displaying the error message provided here and errorColor. | `'red'`   | `string`                                                        |

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
