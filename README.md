# Whiteboard
react-fabricjs-whiteboard ( 👷‍♀️ 🔨)
React whiteboard component based on Fabric.js and React-PDF.

Demo page: https://vigorous-heisenberg-7f8730.netlify.app/


Compatibility
React 17


Installation
npm install react-fabricjs-whiteboard
or

yarn add react-fabricjs-whiteboard

Usage
import { Whiteboard } from "react-fabricjs-whiteboard";

const App = () => {
  return <Whiteboard aspectRatio={4 / 3}/>
};

props
Name	Type	Default	Description
aspectRatio	number	4/3	An aspect ratio(width/height) of the canvas. You can resize the canvas with the same aspect ratio.
