<p align="center">

  <img width="300px" src="/public/images/icon.png" alt ="なんかいい感じの画像">

</p>

<h1 align="center">Edison</h1>

<p align="center">Edison can control Arduino with TypeScript or JavaScript!</p>

<p align="center">

</p>

## Documentation

Our documentation site is [here](https://edison-js-document.vercel.app/)!

## If you have not yet installed the Arduino IDE ?

please click on [the official site](https://www.arduino.cc/en/software) and install it.

## How to use in WSL

Please read [this article](https://zenn.dev/konjikun/articles/e905f4ce99d3ea).

## Installation

Install Edison your project

```console
npm install edison
```

or

```console
yarn add edison
```

## Getting Started

```.ts
import { attachLed, board, SerialPort } from 'edison'

board.on('ready', (port: SerialPort) => {
  const led = attachLed(port, 12)
  console.log(1)
  led.blink(500)
})
```

## Contributing

We love collaborating with folks inside and outside of GitHub and welcome contributions!

> 👉 [Discord](eHB5dBkZyW)
