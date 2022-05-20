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

- `absolutely`
- `achcha`
- `affirmative`
- `agreed`
- `alright`
- `alrighty`
- `amen`
- `assuredly`
- `aye`
- `ayuh`
- `betcha`
- `certain`
- `certainly`
- `cha`
- `chaa`
- `definite`
- `definitely`
- `defo`
- `fine`
- `forsooth`
- `indeed`
- `indubitably`
- `kay`
- `mHmm`
- `mkay`
- `ok`
- `okay`
- `oke`
- `okeyDoke`
- `okeyDokey`
- `positive`
- `right`
- `righty`
- `rightyHo`
- `rightyO`
- `roger`
- `rogerThat`
- `sure`
- `surely`
- `totally`
- `totes`
- `uhHuh`
- `undoubted`
- `undoubtedly`
- `unquestionable`
- `unquestionably`
- `verily`
- `word`
- `ya`
- `yarp`
- `yas`
- `ye`
- `yea`
- `yeah`
- `yep`
- `yepperdoodles`
- `yeppers`
- `yes`
- `yesh`
- `yiss`
- `yomp`
- `yup`
- `yupperdoodles`
- `yuppers`
- `yush`

Aliases for `false` are:

- `aHoax`
- `aLie`
- `bollocks`
- `fakeNews`
- `nae`
- `nah`
- `nahUh`
- `naw`
- `nay`
- `negative`
- `negatory`
- `nix`
- `nizz`
- `no`
- `noNo`
- `nonsense`
- `nope`
- `noway`
- `nowise`
- `rubbish`
- `sham`
- `simplyNotTrue`
- `yeahNah`
- `yeahRight`
- `youMustBeKidding`

## Disclaimer

Please don’t use this library. Or at least use it at your own risk of being frowned upon, ridiculed, or fired from your job. Consider yourself warned.

## License

Licensed under [MIT](./LICENSE). Do what you will.
