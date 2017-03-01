
# React Fluid Level Component
**A React Component that based on D3 and use for liquid Container.**

![npm](https://img.shields.io/npm/v/react-native-material-ui.svg)
[![npm](https://img.shields.io/npm/dm/react-native-material-ui.svg)](https://img.shields.io/npm/dm/react-native-material-ui.svg)
![Alok](https://img.shields.io/badge/byALoK-reactComponent-blue.svg)
[![Dependencies](https://david-dm.org/xotahal/react-native-material-ui.svg)](https://david-dm.org/xotahal/react-native-material-ui.svg)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/xotahal/react-native-material-ui/master/LICENSE)


# Getting Started
```bash
$ npm i react-fluid-component --save
or
$ yarn add react-fluid-component
```

Overview
--------
A React Component that based on D3 and use for liquid Container .

```
<FluidLevel id="fillguage" height={200} width={200} value={0.60} />

```
### Props in more detail:

 See details about each key below.

#### id

Sets the id for Fluid Component and that is required props .


#### height

 Sets the height of the fluid Component .


#### width

  Sets the width of the fluid Component .

#### value

  A most important props for generating Fluid Level Component.Just pass the value like 0.50 for 50% and get the Fluid level Component fill up 50% .


# Usage


```js
import React, { Component } from 'react';
import logo from './logo.svg';
import './App.css';
import FluidLevel from 'react-fluid-component';

class App extends Component {
  render() {
    return (
      <div className="App">
        <div className="App-header">
          <img src={logo} className="App-logo" alt="logo" />
          <h2>Fluid Level Demo</h2>
          <FluidLevel id="fillguage" height={200} width={200} value={0.60} />
        </div>
      </div>
    );
  }
}

export default App;
```

<img src="https://raw.githubusercontent.com/alokverma6597/react-fluid-component/master/resources/FluidLevelDemo.png" width="285">

# For Demo

Clone the repo as a new project:

```
git clone https://github.com/alokverma6597/react-fluid-component <react-fluid-component>
```
Start Server:

```
cd react-fluid-component
npm i
npm start
```
Run App:

```
npm start command automatically initiate browser at 3000 port
http:://localhost:3000
```
