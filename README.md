<h1 align="center">React Native + Next.js Monorepo</h1>

<p align="center">
  <img src="https://img.shields.io/badge/-React Native-gray" />
  <img src="https://img.shields.io/badge/-Next.js-green" />
  <img src="https://img.shields.io/badge/-Monorepo-blue" />
  <img src="https://img.shields.io/badge/-React Native Web-red" />
</p>

![Repository Banner](https://i.imgur.com/wPdflX8.png[/img])

This is a basic monorepo for React Native and Next.js using React Native Web to share components across the packages.

Note that this project doesn't use Expo, if you are looking for that there are other alternatives out there.

## Getting Started

Fork or clone this repo and then install the dependencies:

```bash
yarn
cd packages/mobile && npx pod-install
```

## Building the project

```bash
yarn all
```

To run the app in iOS, Android & web.

Or

```bash
yarn ios
yarn android
yarn web
```

To run the project in a specific platform.

## Contributing

I intend to keep this repository as simple as possible. If you want to add libraries or add features, please do fork the repo. I will be only accepting fixes and improvements for the core/basic functionalities.
