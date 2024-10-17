# React Native for Web POC

## Getting Started

### EAS Setup

Follow [the steps](https://docs.expo.dev/get-started/set-up-your-environment/?platform=ios&device=simulated&mode=development-build#create-a-development-build) to setup eas with this app

### Install dependencies

```bash
yarn
```

### Running the Application

For the Expo app, run the following command:

```bash
yarn run:expo
```

For the Next.js app, run the following command:

```bash
yarn run:next
```

## Project Structure

- `app/next`: Contains the Next.js application.
- `app/expo`: Contains the Expo application.
- `packages/components`: Shared components used across platforms.
- `packages/screens`: Shared screens that can be used in both Next.js and Expo projects.
- `packages/shared`: Shared assets
