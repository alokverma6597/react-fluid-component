
# React Fluid Level Component
**A React Component that based on D3 and use for liquid Cotainer.**

[![npm](https://img.shields.io/npm/v/react-native-material-ui.svg)]
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


# Usage


```js
import React, { Component } from 'react';
import logo from './logo.svg';
import './App.css';
import FluidLevel from './component/pc_fluid_level';

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
