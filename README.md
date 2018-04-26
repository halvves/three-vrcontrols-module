# THREE.VRControls as a module

[![Latest NPM release][npm-badge]][npm-badge-url]
[![License][license-badge]][license-badge-url]
[![Peer Dependencies][peer-dependencies-badge]][peer-dependencies-badge-url]
[![Dev Dependencies][dev-dependencies-badge]][dev-dependencies-badge-url]

I didn't like any of the existing solutions I could find for using VRControls in a modular js build. So I made this.

1. Install:
```bash
npm i -S three-vrcontrols-module
```

2. Use:
```javascript
import VRControls from 'three-vrcontrols-module';
const controls = new VRControls(camera);
```

Converted from: https://github.com/mrdoob/three.js/blob/master/examples/js/controls/VRControls.js

Currently up to date with THREE r92

[npm-badge]: https://img.shields.io/npm/v/three-vrcontrols-module.svg
[npm-badge-url]: https://www.npmjs.com/package/three-vrcontrols-module
[license-badge]: https://img.shields.io/npm/l/three-vrcontrols-module.svg
[license-badge-url]: ./LICENSE.md
[peer-dependencies-badge]: https://david-dm.org/halvves/three-vrcontrols-module/peer-status.svg
[peer-dependencies-badge-url]: https://david-dm.org/halvves/three-vrcontrols-module?type=peer
[dev-dependencies-badge]: https://david-dm.org/halvves/three-vrcontrols-module/dev-status.svg
[dev-dependencies-badge-url]: https://david-dm.org/halvves/three-vrcontrols-module?type=dev
