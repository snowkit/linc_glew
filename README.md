# linc/GLEW
Haxe/hxcpp @:native bindings for [GLEW](https://github.com/nigels-com/glew).

This is a [linc](http://snowkit.github.io/linc/) library.

---

This library works with the Haxe cpp target only.

---
### Install

`haxelib git linc_glew https://github.com/snowkit/linc_glew.git`

### License

See LICENSE.md

### OpenGL + GLEW

For a full OpenGL API with GLEW available, see https://github.com/snowkit/linc_opengl

### Example usage

```haxe
import glew.GLEW;

...

var result = GLEW.init();
if(result != GLEW.OK) {
    throw 'Failed to initialize GLEW:' + GLEW.error(result);
}

```