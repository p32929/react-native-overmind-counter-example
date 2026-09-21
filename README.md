# react-native-overmind-counter-example

A minimal bare React Native app showing how to wire Overmind state into React Native — a counter, two screens, and nothing else in the way.

## What's included

- **Bare React Native** (not Expo) in TypeScript
- **Overmind** — state, actions and a typed `useAppState` / `useActions` helper
- **React Navigation** stack with two screens
- **React Native Paper** for the UI and `react-native-vector-icons` for icons

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

- [expo-overmind-counter-example](https://github.com/p32929/expo-overmind-counter-example) — the same thing on Expo — easier to run
- [react-typescript-overmind-counter-example](https://github.com/p32929/react-typescript-overmind-counter-example) — the plain React version

## Contributing

Contributions are warmly welcomed and greatly appreciated! Whether it's a bug fix, new feature, or improvement, your input helps make this project better for everyone.

Before submitting a pull request, please:

1. Create an issue describing the feature or bug fix you'd like to work on
2. Wait for discussion and approval to ensure alignment with project goals
3. Fork the repository and create your feature branch
4. Submit your pull request with a clear description of changes

This approach helps avoid duplicate efforts and ensures smooth collaboration. Thank you for considering contributing!

## Share

Sharing this repository with your friends is just one click away from here

[![facebook](https://user-images.githubusercontent.com/6418354/179013321-ac1d1452-0689-493f-9066-940cf2302b6e.png)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/p32929/react-native-overmind-counter-example/)
[![twitter](https://user-images.githubusercontent.com/6418354/179013351-7d8d6d1c-4ce2-46ab-bef8-4c4765a1b888.png)](https://twitter.com/intent/tweet?url=https://github.com/p32929/react-native-overmind-counter-example/)
[![tumblr](https://user-images.githubusercontent.com/6418354/179013343-3111f55a-3b90-40c7-8487-9777348672b0.png)](https://www.tumblr.com/share?v=3&u=https://github.com/p32929/react-native-overmind-counter-example/)
[![pocket](https://user-images.githubusercontent.com/6418354/179013334-b095c45f-becf-49f4-9ee1-5a731a9b1f85.png)](https://getpocket.com/save?url=https://github.com/p32929/react-native-overmind-counter-example/)
[![pinterest](https://user-images.githubusercontent.com/6418354/179013331-44cd9206-11b1-4b65-becb-5863b61c828f.png)](https://pinterest.com/pin/create/button/?url=https://github.com/p32929/react-native-overmind-counter-example/)
[![reddit](https://user-images.githubusercontent.com/6418354/179013338-7416ae3f-73ba-4522-86e1-1374d7082d22.png)](https://www.reddit.com/submit?url=https://github.com/p32929/react-native-overmind-counter-example/)
[![linkedin](https://user-images.githubusercontent.com/6418354/179013327-ca7b7102-1da8-4b1c-858f-1a6e5f21bd70.png)](https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/p32929/react-native-overmind-counter-example/)
[![whatsapp](https://user-images.githubusercontent.com/6418354/179013353-f477fa0b-3e6f-4138-a357-c9991b23ff88.png)](https://api.whatsapp.com/send?text=https://github.com/p32929/react-native-overmind-counter-example/)
