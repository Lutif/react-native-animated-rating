<p align="center">
  <a href="https://github.com/Lutif/react-native-animated-rating">
    React Native Animated Ratings
  </a>
</p>

<p align="center">
  Light weight animated ratings component for react native, with zero dependency. (only require react, and react-native)
</p>
<p align="center">
<img src="https://i.postimg.cc/pL1YDQCj/ezgif-5-29e59946c6.gif"/>
</p>
<p align="center">
  <a href="https://www.npmjs.com/package/react-native-animated-rating"><img src="https://img.shields.io/npm/v/react-native-animated-rating.svg?style=flat-square"></a>
  <a href="https://www.npmjs.com/package/react-native-animated-rating"><img src="https://img.shields.io/npm/dm/react-native-animated-rating.svg?style=flat-square"></a>
</p>


## Installation

Install the package using yarn or npm:

```yarn add react-native-animated-rating```

  OR
  
```npm install --save react-native-animated-rating```

## Usage

``` js
import { Rating } from 'react-native-animated-rating';

<Rating
  starSize={30}
  defaultRating={0}
  count={5}
  readonly={false}
  onRatingFinished={(rating) => console.log(rating) }
/>

```


## API


### RatingProps

| prop | default | type | description |
| ---- | ---- | ----| ---- |
| starSize | 30 | number | Pass in size for star. |
| defaultRating | 0 | number | Rating start value to show. |
| count | 5 | number | Number of stars. |
| readonly | false | boolean | Set true if you want to allow user change ratings. |
| onRatingFinshed | -- | funtion | Callback method when the user finishes rating. Gives you the final rating value as a whole number|

## Feedback 

This repo is being actively manitained. Feel free to open a new Issue with a `Feature Request` or submit a PR with an `Enhancement`.
