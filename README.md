<img src='avataaars-example.png' style='width: 128px; height: 136px;'/>

Original React library was developed by [Fang-Pen Lin](https://twitter.com/fangpenlin), based on a [Sketch library](https://avataaars.com/) designed by [Pablo Stanley](https://twitter.com/pablostanley).

This is a rewrite of Fang-Pen Lin's work but as a API, this allow it to be used for things like: 
  - Serverless function.
  - Generating an avatar from your terminal.
  - Use it inside any web framework.

Being a rewrite we removed, added and renamed stuff so this is not compatible with things like [https://getavataaars.com](https://getavataaars.com)

## Usage

#### This project is still work in progress and not useable yet

<!-- ## Demo

```
git clone https://github.com/ItsKerolos/react-native-avataaars
cd react-native-avataaars
npm install
npm run web
``` -->

<!-- ## Usage

```
npm install react-native-avatars --save
```

<!-- ```jsx
import * as React from 'react'
import Avatar from 'avataaars'

export default class MyComponent extends React.Component {
  render () {
    return 
      <div>
        Your avatar:
        <Avatar
          style={{width: '100px', height: '100px'}}
          avatarStyle='Circle'
          topType='LongHairMiaWallace'
          accessoriesType='Prescription02'
          hairColor='BrownDark'
          facialHairType='Blank'
          clotheType='Hoodie'
          clotheColor='PastelBlue'
          eyeType='Happy'
          eyebrowType='Default'
          mouthType='Smile'
          skinColor='Light'
        />
      </div>
  }
}
```

To showcase individual pieces of the avatar you can use the Piece component, for example:

```jsx
import * as React from 'react'
import {Piece} from 'avataaars';

export default class MyComponent extends React.Component {
  render () {
    return 
      <div>
        <Piece pieceType="mouth" pieceSize="100" mouthType="Eating"/>
        <Piece pieceType="eyes" pieceSize="100" eyeType="Dizzy"/>
        <Piece pieceType="eyebrows" pieceSize="100" eyebrowType="RaisedExcited"/>
        <Piece pieceType="accessories" pieceSize="100" accessoriesType="Round"/>
        <Piece pieceType="top" pieceSize="100" topType="LongHairFro" hairColor="Red"/>
        <Piece pieceType="facialHair" pieceSize="100" facialHairType="BeardMajestic"/>
        <Piece pieceType="clothe" pieceSize="100" clotheType="Hoodie" clotheColor="Red"/>
        <Piece pieceType="graphics" pieceSize="100" graphicType="Skull" />
        <Piece pieceType="skin" pieceSize="100" skinColor="Brown" />
      </div>
  }
}
```
