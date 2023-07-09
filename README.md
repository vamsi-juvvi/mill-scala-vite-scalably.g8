# mill-scala-vite-scalably-hello.g8

A Hello World template [Giter8](http://www.foundweekends.org/giter8/)
template for [Mill](https://com-lihaoyi.github.io/mill/mill/Intro_to_Mill.html) that is a starting point for the use of scalablytyped for `ts → ScalaJS` conversion in your scalaJS projects with [Vite](https://vitejs.dev/) as your development server and bundler.

The template is built on top of the following
 - Forked from _LiHaoyi's_ [mill-scala-hello.g8](https://github.com/com-lihaoyi/mill-scala-hello.g8)
 - Updated using code in _Lorenzo Gabriele (lolgab)'s_ [scalajs-vite-example](https://github.com/lolgab/scalajs-vite-example) to introduce the following changes
   - Vite as the dev server __(fast, Hot Module Reloading, minimal config etc)__
   - Use of scalablytyped to convert babylonjs-ts to scalaJS

And contains the following additions:   
   - Use of Laminar (scalaJS lib) for reactive elements
   - Use of BabylonJS (ts/js) for 3D graphics   
   - Chart.js with Laminar example from 

## Appreciation
 - Thanks to [Li Haoyi](https://github.com/lihaoyi) for [Mill](https://com-lihaoyi.github.io/mill/mill/Intro_to_Mill.html) among his many contributions.
 - Thanks to [Lorenzo Gabriele - lolgab](https://github.com/lolgab) for his example utilizing Vite and the [mill-scalablytyped plugin](https://github.com/lolgab/mill-scalablytyped)

## Getting Started

_Usage with Giter8_

```sh
g8 vamsi-juvvi/mill-scala-vite-scalably-hello.g8
```

_Usage with Mill_

```sh
mill init vamsi-juvvi/mill-scala-vite-scalably-hello.g8
```

and then follow instructions in the generated tree's README.md:
- how to build the project
- how to add new js dependencies.