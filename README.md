# XSS Demo

This project contains a simple demo for protecting against XSS attacks with good, bad, and sanitized data.

Start the app by running `yarn start` in your terminal. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. Then, try entering various inputs into the search boxes. To simulate an XSS attack, try entering the following code into both search boxes:

```html
<img src="1" onerror="alert('Gotcha!')" />
```

Note that the first example executes the XSS attack but that the second doesn't.
---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Run the app

`export NODE_OPTIONS=--openssl-legacy-provider`

WINDOWS:
`set NODE_OPTIONS=--openssl-legacy-provider`

`npm install`

`yarn start`
Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.
