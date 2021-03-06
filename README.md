# @elrondnetwork/dapp-template
The __Elrond dApp Template__, built using [React.js](https://reactjs.org/) and [Typescript](https://www.typescriptlang.org/).
It's a basic implementation of [@elrondnetwork/dapp-core](https://www.npmjs.com/package/@elrondnetwork/dapp-core), providing the basics for Elrond authentication and TX signing.

See [Dapp template](https://dapp-template.elrond.com/) for live demo.

## Requirements

* Node.js version 12.16.2+
* Npm version 6.14.4+

## Getting Started

The dapp is a client side only poject and is built using the [Create React App](https://create-react-app.dev)  scripts.

### Instalation and running

### Step 1. Install modules

From a terminal, navigate to the project folder and run:

```bash
npm install
```

### Step 2. Update Configs

Edit a new file `src/config.tsx` and copy the content of `src/config.devnet.tsx`. If you want to develop against `testnet`, change all instances of `devnet` to `testnet`.

### Step 3. Running in development mode

In the project folder run:

```bash
npm run start
```

This will start the React app in development mode, using the configs found in the `config.tsx` file.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### Step 4. Build for testing and production use

A build of the app is necessary to deploy for testing purposes or for production use.
To build the project run:

```bash
npm run build
```

## Roadmap

See the [open issues](https://github.com/ElrondNetwork/dapp-template/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

One can contribute by creating _pull requests_, or by opening _issues_ for discovered bugs or desired features.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Developers

The [Elrond Team](https://elrond.com/team/).
