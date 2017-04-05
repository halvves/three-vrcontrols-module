# THREE.VRControls as a module

I didn't any of the existing solutions I could find to use VRControls in a modular webpack build. So I made this.

```javascript
import VRControls from 'three-vrcontrols-module';
const controls = new VRControls(camera);
```

Converted from: https://github.com/mrdoob/three.js/blob/master/examples/js/controls/VRControls.js

Currently up to date with THREE r84
