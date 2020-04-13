# Shader Reference

## Introduction

You can execute a shader by typing the `xs` command in the console:

```text
xs [option] [shader-name] [arg0] ... [arg7]
```

The shader-name parameter will be based on the shader itself. You can add up to 8 parameters \(`arg0` to `arg8`\), if the shader expects them.

Available options are:

* `-n`: followed by a number, it will iterate the shader a number of times

## Built-in

A shader comes with a number of built-in functions and inputs.

### Inputs

These are the available inputs you can use in your shader:

* `uniform vec3 iVolumeSize`: 
* `uniform float iColorIndex`:
* `uniform vec3 iMirror`:
* `uniform vec3 iAxis`:
* `uniform float iFrame`:
* `uniform float iNumFrames`:
* `uniform float iIter`:
* `uniform vec4 iRand`:
* `uniform float iArgs[8]`:

### Functions

These are the available functions you can use in your shader:

* `float voxel(vec3 v)`:


