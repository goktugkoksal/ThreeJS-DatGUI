# ThreeJS-DatGUI

## Install

- npm install dat.gui --save-dev

- npm install @types/dat.gui --save-dev


## Import

- import { GUI } from 'dat.gui'


## Usage
```
const gui = new GUI()

const cubeFolder = gui.addFolder('Cube')

cubeFolder.add(cube.rotation, 'x', 0, Math.PI * 2)
cubeFolder.add(cube.rotation, 'y', 0, Math.PI * 2)
cubeFolder.add(cube.rotation, 'z', 0, Math.PI * 2)

cubeFolder.open()

const cameraFolder = gui.addFolder('Camera')
cameraFolder.add(camera.position, 'z', 0, 10)
cameraFolder.open()
```
