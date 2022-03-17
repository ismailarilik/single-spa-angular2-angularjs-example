# root-config

An app shell implementation using single-spa using its layout engine feature, initially generated with the command `npx create-single-spa --moduleType root-config`.

It shows these features of single-spa:

- Inter-app communication ([https://single-spa.js.org/docs/recommended-setup/#inter-app-communication](https://single-spa.js.org/docs/recommended-setup/#inter-app-communication))
- Lifecycle props ([https://single-spa.js.org/docs/building-applications/#lifecycle-props](https://single-spa.js.org/docs/building-applications/#lifecycle-props))

## Requirements

- Node.js v16
- A running angular-app-parcel (Please locate it under the same namespace as this repo)
- A running angularjs-app (Please locate it under the same namespace as this repo)
- A running react-app-shell (Please locate it under the same namespace as this repo)

## Running

```sh
# Install dependencies
> npm install
# Start the root config app
> npm start
# Go to http://localhost:9000/
```

For more detail about how to register microfrontends into this app shell, please look at the [official single-spa website](https://single-spa.js.org).
