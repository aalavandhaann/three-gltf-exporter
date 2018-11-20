# three.js glTF exporter
![three.js version](https://img.shields.io/badge/three.js-v0.98.0-green.svg?style=flat-square)
![license](https://img.shields.io/npm/l/three-gltf-loader.svg?style=flat-square)
[![GitHub issues](https://img.shields.io/github/issues/aalavandhaann/three-gltf-exporter.svg?style=flat-square)](https://github.com/aalavandhaann/three-gltf-exporter/issues)


## Installation
```
npm i --save three-gltf-exporter
```

## Description
three.js's r98 [GLTFExporter](https://threejs.org/docs/#examples/exporters/GLTFExporter) wrapped as a module for easy importing.

## Usage
```javascript
import * as THREE from 'three';
import GLTFExporter from 'three-gltf-exporter';

const loader = new GLTFExporter();
```

## Usage es6
```javascript
import GLTFExporter from 'three'
var gexporter = new GLTFExporter();
```
## Notes for rollup
In your rollup.config.js and in the commonjs section ensure to include the below for using this library for es6 projects. This might be necessary for any three-based libraries

```javascript
commonjs({
      include: [
        'node_modules/three-gltf-exporter/**',      
      ]
    }),
```

For further documentation, see [the GLTFExporter docs](https://threejs.org/docs/#examples/exporters/GLTFExporter).

## Reporting Issues
Please note that this is just a wrapper for the [glTF exporter provided by three.js](https://github.com/mrdoob/three.js/blob/master/examples/js/exporters/GLTFExporter.js). Therefore, any issues regarding the loader should be reported directly via the [three.js issue tracker](https://github.com/mrdoob/three.js/issues/).
For issues directly related to the wrapper or this package specifically, feel free to contact me.
