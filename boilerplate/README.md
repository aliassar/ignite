# Welcome to your new ignited app (with web capabilities)!

## The latest and greatest boilerplate for Infinite Red opinions

This is the boilerplate that [Infinite Red](https://infinite.red) uses as a way to test bleeding-edge changes to our React Native stack.

Currently includes:

- React Native
- React Navigation
- MobX State Tree
- TypeScript
- And more!

#### Main documentation can be read at master branch.

## Tips to consider

- New modules that should be compiled with babel needed to be added to `babelInclude` in `config-override.js`
- `Image`s need have dimensions otherwise `react-native-web` can't show them
- `index.js` file is specified only for Web and `indes.native.js` is used for mobile

## Development Checklist

- [X] Web Applicability 
- [X] Using as PWA
- [X] Mobile working like before
- [ ] Can be debugged with Reactotron with Web
- [ ] StoryBook on web
- [ ] E2E & Unit Testing
- [ ] React Navigation #9551 error on build
