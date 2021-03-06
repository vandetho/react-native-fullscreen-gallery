# react-native-fullscreen-gallery

This package provides a gallery with a variety of different indicator animations at 60 fps

[See example app](https://github.com/vandetho/react-native-fullscreen-gallery-example)

[Snack](https://snack.expo.dev/@vandetho/f6c3a4)

## Installation

Use npm or yarn to install the library:

`npm i --save react-native-fullscreen-gallery`

or

`yarn add react-native-fullscreen-gallery`

## Props

| Prop                 | Required           | Description                                           | Type                                 | Default     |
|----------------------|--------------------|-------------------------------------------------------|--------------------------------------|-------------|
| `images`             | <center>✔</center> | Your array of images                                  | `array`  or `ImageSourcePropType[]`️ |             |
| `horizontal`         |                    | Scroll Orientation                                    | `boolean`                            | `true`      |
| `indicatorMode`      |                    | Indicator mode                                        | `thumbnail` `dot`                    | `thumbnail` |
| `resizeMode`         |                    | Image Resize Mode                                     | `ImageResizeMode`                    | `contain`   |
| `slideAnimationType` |                    | Slide animation Type                                  | `slide` `zoom` `fade`                | `slide`     |
| `dotSize`            |                    | Indicator Size                                        | `number`                             | `10`        |
| `dotColor`           |                    | Indicator Color                                       | `string`                             | `#FFFFFF`   |
| `dotType`            |                    | Indicator animation type                              | `expand` `rotary` `fade` `liquid`    | `expand`    |
| `withZoom`           |                    | Only work with liquid animation for a zoom out effect | `boolean`                            | `false`     |
