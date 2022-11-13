# Sign-in with Ethereum (SIWE)

Made with the official tutorial found here: https://docs.login.xyz/sign-in-with-ethereum/quickstart-guide

### Guide

One terminal for `frontend`.

To run frontend:
```
cd siwe-frontend && npm run dev
```

To run backend:
One terminal for `backend`.
```
cd siwe-backend && node src/index.js 
```

Browser: Go to [http://localhost:8080/]

### Adding support for CSS

Define both plugins, with htmlwebpack first then the css plugin.
Then Define the rules.
Then in index.html add <link/> tag.

1. [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin)
2. [css-loader](https://github.com/webpack-contrib/css-loader)

- Additional Resources: [lightrun solutions](https://lightrun.com/answers/webpack-contrib-mini-css-extract-plugin-webpack-html-loader-and-minicssextractplugin)