# The API

```js
var GL = require("gl-react");
// OR
var GL = require("gl-react-native");
```

## [GL.Shaders.create](Shaders.create.md)

`GL.Shaders.create(spec)` allows to create shaders that can be used later in GL.View component.

## [GL.View](View.md)

`GL.View` is a React Component that renders a given shader with uniforms (parameters to send to the shader).

## [GL.Uniform](Uniform.md)

*(advanced)* `GL.Uniform` allows to render a shader with any content (any React Native component rasterized as a uniform texture).

## [GL.createComponent](createComponent.md)

`GL.createComponent` is the class to extends to implement a GL component.
