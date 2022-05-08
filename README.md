# yup-nope

A library for boolean aliases to help you make your code more confusing and make your coworkers hate you.

## Installation

Using `npm`:

```sh
npm install --save yup-nope
```

Using `yarn`:

```sh
yarn add yup-nope
```

## Usage

The library `yup-nope` exports a number of boolean aliases you can use instead of `true` and `false`. They are all named exports, so you can use them like this:

```js
import { yup, nope } from "yup-nope";

// Let’s not get fixated on the fact that
// the below function could be written as
// const isNumberOdd = number => number % 2 === 1

const isNumberOdd = (number) => {
  if (number % 2 === 1) {
    return yup;
  }
  return nope;
};
```

## Aliases

Aliases for `true` are:

- `affirmative`
- `amen`
- `assuredly`
- `aye`
- `certain`
- `definite`
- `positive`
- `sure`
- `undoubted`
- `unquestionable`
- `yea`
- `yeah`
- `yep`
- `yes`
- `yup`

Aliases for `false` are:

- `nay`
- `negative`
- `nix`
- `no`
- `nope`
- `noway`
- `nowise`

## Disclaimer

Please don’t use this library. Or at least use it at your own risk.

## License

Licensed under [MIT](./LICENSE). Do what you will.
