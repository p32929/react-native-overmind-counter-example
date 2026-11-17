# react-native-overmind-counter-example

A small example app that shows how to use [Overmind](https://overmindjs.org) for state in a bare React Native app: a counter, two screens, and nothing else in the way. Handy when you want to see the whole setup working before you add Overmind to your own app.

> Built in 2021 with React Native 0.64. It is kept as an example and is not updated to the latest React Native.

## What's included

1. **Bare React Native** (not Expo) in TypeScript
2. **Overmind** : state, actions and a typed `useAppState` / `useActions` helper
3. **React Navigation** stack with two screens
4. **React Native Paper** for the UI and `react-native-vector-icons` for icons

## Project layout

```
App.tsx                                  Overmind provider + navigation stack
src/Routes/HomeScreen.tsx                screen one
src/Routes/CounterScreen.tsx             reads and mutates the counter
src/Components/MyHeader.tsx              shared header
src/Others/Overmind/OvermindState.ts     the state
src/Others/Overmind/OvermindActions.ts   the actions
src/Others/Overmind/OvermindHelper.ts    config + typed hooks
```

## Getting started

```bash
git clone https://github.com/p32929/react-native-overmind-counter-example.git
cd react-native-overmind-counter-example
npm install

npm start          # metro bundler
npm run android    # or
npm run ios        # (run `cd ios && pod install` first)
```

Icons need one extra step on a fresh clone:

```bash
npm run ic         # react-native link react-native-vector-icons
```

## Related boilerplates

1. [expo-overmind-counter-example](https://github.com/p32929/expo-overmind-counter-example): the same thing on Expo, easier to run
2. [react-typescript-overmind-counter-example](https://github.com/p32929/react-typescript-overmind-counter-example): the plain React version

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make this example better.

## You might also like

<a href="https://openstore.pfay.workers.dev/cards/p32929?n=4&amp;repo=react-native-overmind-counter-example"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929.svg?n=4&amp;repo=react-native-overmind-counter-example&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929.svg?n=4&amp;repo=react-native-overmind-counter-example&amp;theme=light" width="100%" alt="More apps by p32929 on OpenStore"></picture></a>

<p><a href="https://p32929.github.io/share/?repo=react-native-overmind-counter-example"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
