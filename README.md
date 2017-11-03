# react-node-component
Is a node for the N TREE structure (react-tree-structure)
to see how this work take a look to https://github.com/maximobelen/react-tree-test

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)
  

```js
require('styles/App.scss');

import React from 'react';
import Tree from 'react-tree-structure';
import testFile from './testFile.js';

class AppComponent extends React.Component {

    render() {
        var props = this.props;
        return (
            <div className="app">
               <Tree {...props}> </Tree>
            </div>
        );
    }
}

AppComponent.defaultProps = {
    node: testFile
};

export default AppComponent;

```

## Usage

[![NPM](https://nodei.co/npm/react-node-component.png)](https://www.npmjs.com/package/react-node-component)
